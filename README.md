# Flask DevOps Lab

## Endpoints
- `GET /hello` → returns `{"message": "Hello, World!"}`
- `POST /echo` → returns the same JSON sent in the request with status 201

## Tests
- `test_hello()` tests the GET `/hello` route
- `test_echo()` tests the POST `/echo` route

## DevOps / CI
This project includes:
- GitHub Actions test workflow (pytest + coverage)
- Matrix builds for Python 3.10, 3.11, 3.12
- Linting via Flake8
- CodeQL security scanning
- Codecov coverage reporting
- Dependabot weekly updates

## Instructions
See screenshots in submission for workflow results.
