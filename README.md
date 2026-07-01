# Manatosh Maiti - Monorepo

Consolidated repository for all my projects and applications.

## 📁 Repository Structure

```
Monorepo/
├── auto-hire-framework/     # GenAI Job Search Automation App
│   ├── src/                 # React components and utilities
│   ├── components/          # Reusable UI components
│   ├── lib/                 # Library wrappers (Firebase, Gemini)
│   ├── package.json
│   ├── tsconfig.json
│   ├── vite.config.ts
│   └── README.md
├── .github/
│   └── workflows/           # CI/CD workflows
├── package.json             # Root workspace config
└── README.md
```

## 🚀 Quick Start

### Installation

```bash
# Install dependencies for all packages
npm install
```

### Development

```bash
# Start development server for auto-hire-framework
cd auto-hire-framework
npm run dev
```

Or from root (if using workspace scripts):

```bash
npm run dev:autohire
```

### Build

```bash
# Build auto-hire-framework
cd auto-hire-framework
npm run build
```

## 📦 Projects

### AutoHire Framework

A GenAI-powered job search automation app that:
- Automatically searches for jobs matching your profile
- Evaluates candidates using Gemini API
- Generates customized cover letters
- Sends email alerts for high-match opportunities

**Tech Stack:** React, Vite, Firebase, Gemini API, TypeScript, Tailwind CSS

**Location:** `./auto-hire-framework`

**Setup:**

1. Navigate to the project:
   ```bash
   cd auto-hire-framework
   ```

2. Create `.env` file:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Run development server:
   ```bash
   npm run dev
   ```

## 🔧 Workspace Configuration

This monorepo uses npm workspaces. All projects are managed from the root `package.json`.

### Available Scripts

From the root directory:

```bash
# Install all dependencies
npm install

# Build all projects
npm run build:all

# Lint all projects
npm run lint:all

# Run tests (when available)
npm run test:all
```

## 📋 Prerequisites

- **Node.js** v18 or newer
- **npm** v9 or newer
- **Git** for version control

### For AutoHire Framework

- [Gemini API Key](https://aistudio.google.com/app/apikey)
- Firebase project with Firestore enabled

## 🤝 Contributing

When adding new projects to the monorepo:

1. Create a new directory under the root
2. Add a `package.json` with workspace configuration
3. Update this README with project details
4. Add CI/CD workflows if needed

## 📝 License

This project is part of Manatosh Maiti's portfolio.

## 🔗 Links

- **GitHub:** [@manatoshtech09-collab](https://github.com/manatoshtech09-collab)
- **AutoHire Framework:** [Original Repository](https://github.com/manatoshtech09-collab/AutoHire-Framework)

---

**Last Updated:** July 1, 2026
