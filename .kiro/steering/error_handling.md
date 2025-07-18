---
inclusion: manual
---

# Error Handling Guidelines

## General Principles
- Be specific about which exceptions to catch
- Don't catch exceptions you can't handle properly
- Log exceptions with appropriate context
- Provide meaningful error messages to users
- Use custom exception classes for domain-specific errors

## Exception Hierarchy
- Create a base exception class for your application
- Derive specific exception types from the base class
- Group related exceptions in modules
- Use exception chaining to preserve context

## Recovery Strategies
- Implement retry mechanisms for transient failures
- Provide fallback behavior when appropriate
- Fail fast for unrecoverable errors
- Clean up resources in finally blocks or context managers