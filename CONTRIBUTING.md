# Contributing to Vacurim

First off, thanks for taking the time to contribute! 🎉

This document explains how to report issues, suggest features, and submit pull requests to the Vacurim public repository.

---

## Repository Scope

This repository contains:

- The **landing page** for Vacurim's free online tools (served via GitHub Pages).
- The **source code** for the **Currency Calculator** free tool.
- **Documentation** and **screenshots** for Vacurim's premium Codex product line.

This repository does **not** contain the source code for the premium desktop applications (Swiss Codex, Vatican Codex, Suite). Those are proprietary and distributed only through [vacurim.com](https://vacurim.com/).

---

## Ways to Contribute

| Type | How |
|------|-----|
| 🐛 Bug report (free tools, README, landing page) | Open an issue using the **Bug report** template. |
| 💡 Feature request (free tools, documentation) | Open an issue using the **Feature request** template. |
| 📝 Documentation improvement | Open a pull request against `main`. |
| 🎨 UI / UX improvement to free tools | Open a pull request against `main`. |
| 🌐 Translation | Open a pull request against `main`. |
| 💬 Question | Email support@vacurim.com (we do not use GitHub Discussions yet). |

---

## Before You Open an Issue

Please search existing issues first to avoid duplicates. When filing a bug, include:

- The tool name and URL (e.g. `https://vacurim.com/tools/currency-calculator/`).
- Browser + version, OS.
- Steps to reproduce.
- Expected vs. actual behavior.
- Screenshots if relevant.

---

## Pull Request Process

1. **Fork** the repository.
2. Create a branch: `git checkout -b fix/short-description` or `feat/short-description`.
3. Make your changes. Keep commits focused — one logical change per commit.
4. Test your change locally. For `tools/currency-calculator/index.html`, open the file in a browser.
5. Commit with a clear message (see **Commit Style** below).
6. Push to your fork and open a pull request against `main`.
7. Fill in the PR template.
8. Respond to review feedback.

### Commit Style

Use the [Conventional Commits](https://www.conventionalcommits.org/) format:

```
<type>(<scope>): <subject>

<body>
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `chore`.

Example: `docs(readme): fix broken link in manuscript digitizer section`

---

## Code Style

### HTML / CSS / JavaScript (free tools)

- Indent with 2 spaces.
- Use semantic HTML5 tags.
- Keep functions small and focused.
- Comment non-obvious logic in English.
- No external dependencies for free tools — they must run from a single `index.html` if possible.

### Markdown (documentation)

- Use ATX-style headings (`#` not `===`).
- Wrap lines at ~120 characters.
- Use fenced code blocks with language hints.

---

## Code of Conduct

Participation in this project is governed by the [Code of Conduct](CODE_OF_CONDUCT.md). Please be excellent to each other.

---

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE). The Vacurim brand, logo, and product names remain the exclusive property of Vacurim.

---

## Questions?

- Email: support@vacurim.com
- Website: [vacurim.com/contact/](https://vacurim.com/contact/)

Thanks again for helping make Vacurim better! 🙏
