# AGENTS.md

This repository contains the living **Gentleman's Code** and **Lady's Code** in British English and translated editions.

## Repository layout

- `gentleman.md` — Gentleman's Code in British English.
- `lady.md` — Lady's Code in British English.
- `int/gentleman/<language>.md` — translations of the Gentleman's Code; Russian is `int/gentleman/ru.md`.
- `int/lady/<language>.md` — translations of the Lady's Code; Russian is `int/lady/ru.md`.
- `README.md` — public index and links to available editions.

When adding, moving, or renaming an edition, keep `README.md` links in sync. Translations should preserve the meaning and structure of their corresponding code.

## Commits

Use a leading emoji plus a short imperative subject, with one logical change per commit.

- `📖` codex, documentation, or governance; `🌐` translation-only changes; `🧹` cleanup; `🔧` repository housekeeping or technical files.
- A codex revision may include its matching translations; unrelated content, governance, and technical changes must stay separate.
- Technical files such as `.gitignore` always get their own commit, e.g. `🔧 Update .gitignore`.
- Do not include internal task/audit identifiers or coding-agent attribution in commit messages.
