# Contributing to Play CV

Thank you for your interest in contributing to Play CV! This document provides guidelines and instructions for contributing.

## Code of Conduct

Please be respectful and considerate of others when contributing to this project.

## How to Contribute

1. Fork the repository
2. Create a new branch for your feature/fix
3. Make your changes
4. Submit a pull request

## Development Process

1. **Branch Naming**
   - Feature branches: `feature/your-feature-name`
   - Bug fixes: `fix/issue-description`
   - Documentation: `docs/description`

2. **Commit Messages**
   - Use clear and descriptive commit messages
   - Start with a verb (Add, Fix, Update, etc.)
   - Keep messages concise but informative

3. **Pull Requests**
   - Update the README.md with details of changes if needed
   - Include screenshots if applicable
   - Reference any related issues

## Development Setup

1. Install dependencies:
```bash
# Frontend
cd play_cv_client
npm install

# Backend
cd ../play_cv_server
pip install -r requirements.txt
```

2. Run tests:
```bash
# Frontend
npm test

# Backend
python -m pytest
```

## Style Guide

- Follow the existing code style
- Use meaningful variable and function names
- Add comments for complex logic
- Keep functions small and focused

## Questions?

Feel free to open an issue for any questions or concerns. 