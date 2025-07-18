---
inclusion: fileMatch
fileMatchPattern: '*.py'
---

# Project Structure Guidelines

## Python Project Structure
- Use a modular approach with clear separation of concerns
- Organize code into logical packages and modules
- Keep related functionality together
- Use __init__.py files to control package exports
- Place tests in a separate directory structure mirroring the main package

## Configuration Management
- Store configuration in dedicated config files
- Use environment variables for sensitive information
- Separate configuration from code
- Provide sensible defaults for all configuration options

## Dependency Management
- Use requirements.txt for listing dependencies
- Pin dependency versions for reproducibility
- Group dependencies by purpose (main, dev, test)
- Document why dependencies are needed
- Use a virtual environment to manage dependencies.
- Name virtual environment .venv
- Never install dependencies outside of a virtual environment.