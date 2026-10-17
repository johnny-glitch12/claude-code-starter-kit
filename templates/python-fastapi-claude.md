# Project

Python 3.11+ FastAPI service.

## Commands
- Run: `uvicorn main:app --reload`
- Test: `pytest`
- Lint: `ruff check .`

## Rules
- All functions must have type hints.
- Use Pydantic models for request/response bodies.
- Raise HTTPException for expected errors. Don't return error dicts.
- Keep business logic out of route handlers. Put it in separate modules.
- Use dependency injection for database sessions and auth.

## Don't
- Don't hardcode secrets.
- Don't use `print` for logging. Use the logging module.
- Don't catch broad `Exception` unless you re-raise or log it properly.
