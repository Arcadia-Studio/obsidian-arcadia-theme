---
file-role: handoff
status: draft
notebook: The Study
created: 2026-05-28
updated: 2026-06-10
---

# Arcadia Theme Community Submission Handoff

## Status

**PR #9992** on `obsidianmd/obsidian-releases`: **CLOSED** (auto-closed March 12, 2026)

**PR #11447** on `obsidianmd/obsidian-releases`: **OPEN** (submitted 2026-03-26)
- New branch: `add-arcadia-theme` (clean, no merge conflicts)
- PR body matches official template exactly
- JSON entry uses 2-space indentation matching upstream
- URL: https://github.com/obsidianmd/obsidian-releases/pull/11447

## Pre-Submission Checklist

Before opening a new PR, verify all of the following:

- [ ] Theme repo is public at https://github.com/Arcadia-Studio/obsidian-arcadia-theme
- [ ] `theme.css` is pushed and current (version 2.1.1)
- [ ] `manifest.json` is pushed and current (version 2.1.1)
- [ ] `README.md` is pushed and current
- [ ] `LICENSE` file exists (MIT)
- [ ] Hero screenshot exists at `screenshots/hero-dark.png` (16:9, min 512x288px)
- [ ] License compatibility with community store is confirmed

## New PR Submission Steps

### Step 1: Sync Fork

The fork at `PeterCarterSr/obsidian-releases` needs to be synced with upstream before creating a new branch.

```bash
# Authenticate gh CLI first if needed
gh auth login

# Sync the fork
gh repo sync PeterCarterSr/obsidian-releases --source obsidianmd/obsidian-releases
```

### Step 2: Create a New Branch and Add Entry

1. Fetch the current `community-css-themes.json` from the synced fork
2. Append the Arcadia entry to the end of the JSON array:
   ```json
   {
     "name": "Arcadia",
     "author": "Peter J. Carter",
     "repo": "Arcadia-Studio/obsidian-arcadia-theme",
     "screenshot": "screenshots/hero-dark.png",
     "modes": ["dark", "light"]
   }
   ```
3. Ensure the JSON is valid (use tabs for indentation, matching upstream formatting)
4. Commit to a new branch (e.g., `add-arcadia-theme`)

### Step 3: Open PR with Correct Template

Use the exact PR body below. The validator does strict matching against the official template.

```
# I am submitting a new Community Theme

## Repo URL

<!--- Paste a link to your repo here for easy access -->
Link to my theme: https://github.com/Arcadia-Studio/obsidian-arcadia-theme


## Theme checklist

<!--- Confirm that you have done the following before submitting your theme -->
- [x] My repo contains all required files (please *do not* add them to this `obsidian-releases` repo).
  - [x] `manifest.json`
  - [x] `theme.css`
  - [x] The screenshot file (16:9 aspect ratio, recommended size is 512px by 288px for fast loading).
- [x] I have indicated which modes (dark, light, or both) are compatible with my theme.
- [x] I have read the developer policies at https://docs.obsidian.md/Developer+policies, and have assessed my theme's adherence to these policies.
- [x] I have read the tips in https://docs.obsidian.md/Themes/App+themes/Theme+guidelines and have self-reviewed my theme to avoid these common pitfalls.
- [x] I have added a license in the LICENSE file.
- [x] My project respects and is compatible with the original license of any code from other themes that I'm using. I have given proper attribution to these other themes in my `README.md`.
```

### Step 4: Monitor Validation

After submitting, the bot validates automatically within minutes. Watch for:
- JSON parse errors (means the entry was malformed or merge conflict exists)
- Template mismatch (means the PR body doesn't match exactly)
- Theme repo accessibility (must be public)
- Screenshot file existence

## Key Details

- **GitHub user:** PeterCarterSr
- **Fork repo:** PeterCarterSr/obsidian-releases
- **Target repo:** obsidianmd/obsidian-releases (master)
- **Theme repo:** Arcadia-Studio/obsidian-arcadia-theme (public, `main` branch)
- **Old PR branch:** patch-2 (stale, do not reuse)
- **gh CLI location:** `/c/Program Files/GitHub CLI/gh` (add to PATH with `export PATH="$PATH:/c/Program Files/GitHub CLI"`)

## Open Questions

- **License compatibility:** Resolved. The repo ships an MIT LICENSE, the most common license among community themes and compatible with the community store.
