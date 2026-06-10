---
file-role: arcadia
status: draft
notebook: The Study
created: 2026-05-28
updated: 2026-05-28
---

# Contributing to Arcadia Theme

Thank you for your interest in contributing to the Arcadia Theme for Obsidian.

## Reporting Bugs

1. Check existing [issues](https://github.com/Arcadia-Studio/obsidian-arcadia-theme/issues) to avoid duplicates
2. Use the **Bug Report** issue template
3. Include: Obsidian version, OS, steps to reproduce, expected vs actual behavior
4. Screenshots are helpful, especially for visual bugs

## Requesting Features

1. Use the **Feature Request** issue template
2. Describe the feature and why it would be useful
3. If possible, reference how other themes handle it

## Submitting Pull Requests

1. Fork the repository
2. Create a feature branch from `main`
3. Make your changes to `theme.css` (the single distribution file)
4. Test in both dark and light modes
5. Test with Style Settings enabled and disabled
6. Submit a PR with a clear description

### Code Style

- CSS comments use `/* === SECTION N: NAME === */` headers
- Custom properties use `--ctp-` prefix for colors, `--arcadia-` for other variables
- RGB triplet format for color variables: `--ctp-name: R, G, B;`
- Use `!important` only when overriding Obsidian core styles; document why
- No duplicate section numbers
- Single blank line between rule blocks, double before section headers

### What NOT to do

- Do not remove existing color schemes, checkbox types, or Style Settings options
- Do not change the file structure (Obsidian requires a single `theme.css`)
- Do not add minification (Style Settings requires CSS comment blocks)
- Do not add JavaScript (themes are CSS-only)

## Questions?

Open a discussion or issue on GitHub.
