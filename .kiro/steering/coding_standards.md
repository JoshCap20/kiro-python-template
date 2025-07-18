# Coding Standards

## Python Coding Standards
- Follow PEP 8 style guidelines
- Use type hints for function parameters and return values
- Write docstrings for all modules, classes, and functions
- Use meaningful variable and function names
- Keep functions small and focused on a single responsibility
- Split up larger functions
- Use context managers for resource management
- Handle exceptions appropriately with specific exception types

## Git Usage
- Create a git commit after each completed task or subtask
- Group related edits by clear, specific commits
- Write descriptive commit messages with:
  - A concise summary line (50 characters or less)
  - A blank line followed by a more detailed explanation
  - List of specific changes made using bullet points
  - Reference to the task ID or issue number being addressed
- Tests should be included in commits to test modifications or add new coverage
- Use a .gitignore file in root directory to exclude non-relevant directories and files
- Avoid committing incomplete or broken code

## Testing Standards
- Write unit tests for all functions and methods
- Aim for at least 80% code coverage
- Use pytest for testing
- Mock external dependencies in tests
- Use fixtures for test setup
- Place tests in a separate directory structure mirroring the main package

## Documentation Standards
- Document all public APIs
- Include examples in docstrings
- Keep documentation up-to-date with code changes
- Use README files to provide overview and setup instructions
