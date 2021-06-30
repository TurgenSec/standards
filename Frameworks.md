# Languages

Order of preference:

- Typescript
- Python3 - With Types

Try to stick to these unless absolutely necessary and discussed with stakeholders.

# Frameworks

## Typescript

- [NestJS](https://nestjs.com/) - Has batteries included.

## Python

- [FastAPI](https://fastapi.tiangolo.com/) with Pydantic

# Testing/Linting

## Typescript

- Jest
- ESLint
- Prettier

## Python

- PyTest
- Flake8
- Black
- MyPy

# Pre Commit hooks

All repos should have PreCommit hooks configured which ensures non-compliant code is not checked in.
It should check the Coding style and Type Compatiablitiy.

## Typescript

- Husky
- Lint-Staged

## Python

- pre-commit
