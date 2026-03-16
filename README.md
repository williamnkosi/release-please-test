# Release Please Demo

A simple Node.js project to learn how release-please works.

## Getting Started

```bash
npm install
npm start
```

## How Release Please Works

1. **Commit messages**: Use conventional commits (feat:, fix:, etc.)
2. **Release PR**: release-please creates a PR with updated versions
3. **Merge & Release**: Merging the PR triggers the release workflow

## Conventional Commits

- `feat:` - New feature (minor version bump)
- `fix:` - Bug fix (patch version bump)
- `BREAKING CHANGE:` - Major version bump

Example:
```
feat: add new calculator feature
fix: resolve calculation bug
```
