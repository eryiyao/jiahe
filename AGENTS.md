# AGENTS.md

## Project Context

This is a lightweight single-page delivery order tool for Jiahe, served from `index.html` and published through GitHub Pages.

## Before Editing

- Run `git status --short --branch`.
- Check whether the local branch is behind `origin/main`.
- If it is behind, sync safely before making new edits, usually with `git pull --rebase`.
- Preserve any unrelated local or untracked user files.

## Development Notes

- Keep the app lightweight and browser-only unless the user explicitly asks for a backend or build step.
- Prefer focused edits to `index.html`, `README.md`, and static assets.
- After UI changes, verify the page in a browser at mobile and desktop sizes.
- Do not store GitHub tokens, personal access tokens, passwords, or deployment credentials in this repository.

## Release Notes

- Before pushing, confirm the branch is up to date with `origin/main`.
- If GitHub authentication fails, stop and ask the user to refresh their local GitHub credentials.
