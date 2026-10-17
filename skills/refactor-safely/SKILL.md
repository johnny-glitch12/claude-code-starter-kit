---
name: refactor-safely
description: Refactor code while preserving behavior. Use when asked to clean up or restructure code without changing what it does.
---

When refactoring:

1. Confirm the current behavior with existing tests or by reading the code carefully.
2. Make small, incremental changes.
3. Keep the public interface the same unless the user explicitly wants it changed.
4. Suggest or run tests after each meaningful change.
5. Explain what improved and why.

Do not mix refactoring with new features in the same change.
