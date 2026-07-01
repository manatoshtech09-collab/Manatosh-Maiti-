# Contributing to Manatosh Maiti Monorepo

Thank you for your interest in contributing! Here's how you can help.

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/Manatosh-Maiti-.git`
3. Create a feature branch: `git checkout -b feature/your-feature`
4. Install dependencies: `npm install`

## Development Workflow

### Starting Development

```bash
# For AutoHire Framework
cd auto-hire-framework
npm run dev
```

### Building

```bash
# Build a specific project
npm run build:autohire

# Build all projects
npm run build:all
```

### Linting

```bash
# Lint all projects
npm run lint:all

# Lint specific project
npm run lint:autohire
```

## Code Guidelines

- Use TypeScript for type safety
- Follow the existing code style
- Write clear commit messages
- Test your changes locally before pushing
- Update documentation as needed

## Submitting a Pull Request

1. Push your changes to your fork
2. Create a pull request against the `main` branch
3. Describe your changes clearly
4. Wait for CI checks to pass
5. Request review from maintainers

## Reporting Issues

If you find a bug or have a feature request:

1. Check if the issue already exists
2. Create a new issue with a clear title and description
3. Include steps to reproduce (for bugs)
4. Include relevant screenshots or logs

## Project Structure

When adding new projects:

1. Create a new directory in the root
2. Add a `package.json` with workspace configuration
3. Include a `README.md` with setup instructions
4. Update the root README with project details
5. Add CI/CD workflows if needed

---

Thanks for contributing! 🚀
