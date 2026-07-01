# GenAI Job Search Automation App

This project was built with React, Vite, and Firebase. It uses the Gemini API to search for jobs and evaluate candidates based on their resume and LinkedIn profile.

## Features

- **Automated Job Search**: Periodically searches for jobs matching your provided role, location, and seniority.
- **Candidate Evaluation**: Uses Gemini to evaluate a candidate's base resume and LinkedIn against specific job descriptions to provide a Relevancy Score. Includes factual resume tailoring.
- **Auto-generated Materials**: Can generate draft a customized cover letter for highly matched roles.
- **Email Alerts**: Mocked or implemented alerts for new jobs with a match score >= 90%.

## Prerequisites

- Node.js (v18 or newer recommended)
- A [Gemini API Key](https://aistudio.google.com/app/apikey)
- A Firebase project with Firestore enabled

## Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Environment Variables:**
   Rename `.env.example` to `.env` (or create a `.env` file) and add your Gemini API Key:
   ```env
   GEMINI_API_KEY="your_actual_gemini_api_key_here"
   ```

3. **Firebase Configuration:**
   If the project relies on Firebase, ensure you have your Firebase config appropriately loaded. In AI Studio, this relies on a `firebase-applet-config.json` file at the root or configured in your environment.
   ```json
   {
     "apiKey": "...",
     "authDomain": "...",
     "projectId": "...",
     "storageBucket": "...",
     "messagingSenderId": "...",
     "appId": "...",
     "firestoreDatabaseId": "(default)"
   }
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```

## Deployment

To build the app for production, run:
```bash
npm run build
```
This will generate a `dist/` folder with the static files.

## Project Structure
- `src/components/`: All React UI components including the job search, and dashboard.
- `src/lib/`: Utility functions and library wrappers (e.g., Firebase, Gemini).
- `.env.example`: Example environment variables.
