## Security

- Validate input sanitization practices.
- Search for risks that might expose user data.
- Prefer loading configuration and content from the database instead of hard coded content. If absolutely necessary, load it from environment variables or a non-committed config file.

## Code Quality

- Use consistent naming conventions.
- Try to reduce code duplication.
- Prefer maintainability and readability over optimization.
- If a method is used a lot, try to optimize it for performance.
- Prefer explicit error handling over silent failures.

## Testing

- Add or update tests for behavior changes when tests are available.
- Prefer deterministic tests that do not depend on timing or external services.
- Verify both success paths and important failure paths.

## Documentation

- Keep API or behavior documentation in sync with code changes.
- Document assumptions and limitations near complex logic.