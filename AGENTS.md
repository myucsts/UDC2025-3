# Repository Guidelines

## Project Structure & Module Organization
- Repository root currently contains `README.md` and this guide; no source, test, or asset directories are defined yet.
- When code is added, prefer top-level directories like `src/`, `tests/`, and `assets/` to keep responsibilities clear.

## Build, Test, and Development Commands
- No build, test, or dev scripts are configured yet.
- Add a documented command in `README.md` once a toolchain is introduced (for example, `npm test`, `make build`, or `go test ./...`).

## Coding Style & Naming Conventions
- No style or lint configuration is present.
- Until standards are added, follow the language defaults and keep naming consistent within each module (for example, `snake_case` for filenames or `PascalCase` for types).
- If formatting tools are introduced, document them here (for example, `prettier`, `ruff`, or `gofmt`).

## Testing Guidelines
- No test framework or coverage requirements are defined.
- When tests are added, place them in `tests/` or alongside modules (for example, `src/foo.test.ts`) and document the runner command here.

## Commit & Pull Request Guidelines
- Git history only includes an initial commit; no message convention is established.
- Use short, imperative commit subjects (for example, "Add parser skeleton") and include a brief PR description.
- If PRs add user-facing changes, include a short summary and any relevant screenshots or logs.

## Security & Configuration Tips
- Avoid committing secrets. Store local config in a gitignored file (for example, `.env`) if needed.
- Document any required environment variables in `README.md` once they exist.
