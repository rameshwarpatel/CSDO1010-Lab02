# Commit Rules

- Commit early and in small, logical units.
- Use imperative, present-tense language in messages: _add_, _update_, _remove_.
- Follow the Conventional Commits style: `feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`.
- Keep the subject line under 50 characters.
- Leave a blank line before any detailed description.
- Reference issues where applicable, e.g., `Fixes #101`.
- Exclude temporary, build, or generated files from commits.
- Never, **ever** expose credentials, secrets, tokens, keys, passwords in a repository.

**Examples**:

| Type         | Example Commit Message                     |
| :----------- | :----------------------------------------- |
| **feat**     | feat: add initial lab instructions         |
| **fix**      | fix: correct directory creation command    |
| **docs**     | docs: clarify prerequisites section        |
| **chore**    | chore: update .gitignore with IDE files    |
| **refactor** | refactor: rename vars for clarity          |
| **test**     | test: add unit tests for parser edge cases |
