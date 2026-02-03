# Arcadia Theme for Obsidian

A comprehensive, professional Obsidian theme with **23 color schemes**, OneNote-style features, and extensive customization through Style Settings.

![Arcadia Theme Preview](screenshots/hero-dark.png)

---

> **Enjoying Arcadia?** [![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat-square&logo=buy-me-a-coffee)](https://buymeacoffee.com/drcarterd)

---

## Table of Contents

- [Installation](#installation)
- [Requirements](#requirements)
- [Color Schemes](#color-schemes)
- [Style Settings Configuration](#style-settings-configuration)
- [Feature Guide](#feature-guide)
  - [File Icons](#file-icons)
  - [Alternate Checkboxes](#alternate-checkboxes)
  - [Custom Callouts](#custom-callouts)
  - [Sticky Notes](#sticky-notes)
  - [Paper Styles](#paper-styles)
  - [Media Embedding](#media-embedding)
  - [Code Blocks](#code-blocks)
  - [Cards View](#cards-view)
  - [Rainbow Folders](#rainbow-folders)
  - [Tag Colors](#tag-colors)
  - [Progress Bars](#progress-bars)
  - [Image Controls](#image-controls)
- [Accessibility](#accessibility)
- [Support This Theme](#support-this-theme)
- [Credits](#credits)
- [Changelog](#changelog)

---

## Installation

### From Community Themes (Recommended)

1. Open Obsidian **Settings**
2. Go to **Appearance** → **Themes**
3. Click **Manage** and search for **"Arcadia"**
4. Click **Install and use**

### Manual Installation

1. Download `theme.css` and `manifest.json` from this repository
2. In your vault, navigate to `.obsidian/themes/`
3. Create a new folder called `Arcadia`
4. Place both files inside the `Arcadia` folder
5. In Obsidian: **Settings** → **Appearance** → **Themes** → Select **"Arcadia"**

---

## Requirements

### Required
- **Obsidian** version 0.16.0 or higher

### Highly Recommended
- **[Style Settings Plugin](https://github.com/mgmeyers/obsidian-style-settings)** — Enables all customization options

Without Style Settings, you'll get the default Arcadia appearance. With it, you unlock 60+ customization options.

**To install Style Settings:**
1. **Settings** → **Community Plugins** → **Browse**
2. Search for **"Style Settings"**
3. Click **Install**, then **Enable**
4. Access theme options via **Settings** → **Style Settings** → **Arcadia**

---

## Color Schemes

### Dark Themes (11)

| Theme | Description | Best For |
|-------|-------------|----------|
| **Granite** (Default) | Neutral dark gray | General use |
| **Stone** | Cool slate tones | Minimalist preference |
| **Olive** | Warm earthy greens | Nature lovers |
| **Flint** | Cool professional blue-gray | Focused work |
| **Navy** | Deep ocean blues | Late night writing |
| **Ember** | Warm firelight oranges | Cozy reading |
| **Twilight** | Purple dusk tones | Creative work |
| **Forest** | Deep woodland greens | Calm focus |
| **Crimson** | Elegant wine reds | Dramatic appearance |
| **Slate** | Modern cool gray | Clean aesthetic |
| **Amber** | Golden warmth | Nostalgic feel |

### Light Themes (12)

| Theme | Description | Best For |
|-------|-------------|----------|
| **Marble** (Default) | Clean white | Daytime use |
| **Sage** | Soft green tint | Gentle on eyes |
| **Pearl** | Cool ivory | Elegant writing |
| **Cloud** | Soft blue | Calm atmosphere |
| **Dawn** | Warm peach | Morning sessions |
| **Lavender** | Purple tint | Creative mood |
| **Mint** | Fresh green | Energizing |
| **Rose** | Soft pink | Gentle aesthetic |
| **Silver** | Cool gray | Professional |
| **Cream** | Golden white | Warm comfort |
| **NY Times** | Classic newspaper | Long-form reading |
| **Wikipedia** | Encyclopedia style | Research & reference |

### How to Change Color Scheme

1. Open **Settings** → **Style Settings**
2. Expand **Arcadia Theme** → **Color Scheme**
3. Choose **Dark Theme Variant** or **Light Theme Variant**
4. Select your preferred scheme from the dropdown

---

## Style Settings Configuration

After installing the Style Settings plugin, you'll find these option categories:

### Arcadia Theme (Main)
- **Dark Theme Variant** — Choose from 11 dark color schemes
- **Light Theme Variant** — Choose from 12 light color schemes

### Arcadia Typography
- **Heading Font** — Inter, Vollkorn, EB Garamond, Libre Caslon, Merriweather, Crimson Pro, Lora, Literata
- **Body Font** — Same options as heading font
- **Monospace Font** — JetBrains Mono, Fira Code, Source Code Pro, IBM Plex Mono
- **Enable OpenDyslexic** — Toggle dyslexia-friendly font

### Arcadia Accent Colors
Choose from 15 accent colors: Blue, Purple, Pink, Red, Orange, Yellow, Green, Teal, Cyan, Indigo, Violet, Rose, Amber, Emerald, Sky

### Arcadia Code Blocks
- **Syntax Theme** — Dracula, Nord, GitHub Dark, GitHub Light
- **Show Line Numbers** — Toggle line numbers in code blocks
- **Show Language Label** — Toggle language badge on code blocks

### Arcadia File Icons
- **Enable File Icons** — Toggle custom file type icons
- **Icon Color Mode** — Colorful or Monochrome

### Arcadia Checkboxes
- **Enable Alternate Checkboxes** — Toggle custom checkbox styles

### Arcadia Editor
- **Line Width** — Narrow, Medium, Wide, Full
- **Line Height** — Compact, Normal, Relaxed, Spacious

### Arcadia UI
- **Tab Style** — Default, Rounded, Pill, Underline
- **Enable Rainbow Folders** — Color-code top-level folders
- **Enable Cards View** — Grid layout for file lists

### Arcadia Paper & Notes
- **Paper Styles** — Lined, Grid, Dot, Legal, Cornell, Graph, Isometric, Music
- **Page Tint** — White, Cream, Blue, Green, Pink, Yellow, Gray
- **Sticky Note Style** — Default, Pushpin, Folded Corner, Flat

---

## Feature Guide

### File Icons

Custom colored icons appear next to files in the file explorer, making it easy to identify file types at a glance.

**Supported file types (50+):**

| Category | Extensions |
|----------|------------|
| Documents | `.md`, `.txt`, `.rtf`, `.pdf` |
| Microsoft Office | `.doc`, `.docx`, `.xls`, `.xlsx`, `.ppt`, `.pptx` |
| Images | `.png`, `.jpg`, `.jpeg`, `.gif`, `.bmp`, `.webp`, `.svg` |
| Audio | `.mp3`, `.wav`, `.ogg`, `.flac`, `.m4a` |
| Video | `.mp4`, `.webm`, `.mov`, `.avi`, `.mkv` |
| Code | `.js`, `.ts`, `.py`, `.java`, `.html`, `.css`, `.json`, `.xml`, `.yaml` |
| Archives | `.zip`, `.rar`, `.7z`, `.tar`, `.gz` |
| Ebooks | `.epub`, `.mobi` |
| Fonts | `.ttf`, `.otf`, `.woff` |

**To enable/disable:**
**Settings** → **Style Settings** → **Arcadia File Icons** → **Enable File Icons**

---

### Alternate Checkboxes

21 unique checkbox styles for task management and note-taking.

**Usage:** Type a checkbox with a special character inside the brackets.

| Syntax | Result | Use Case |
|--------|--------|----------|
| `- [ ]` | Empty checkbox | Incomplete task |
| `- [x]` | Green checkmark | Completed task |
| `- [-]` | Red strikethrough | Canceled task |
| `- [>]` | Blue arrow right | Forwarded/Deferred |
| `- [<]` | Purple calendar | Scheduled |
| `- [?]` | Blue question mark | Question to answer |
| `- [!]` | Red exclamation | Important/Urgent |
| `- [*]` | Gold star | Starred/Favorite |
| `- ["]` | Cyan quote marks | Quote or citation |
| `- [l]` | Orange pin | Location |
| `- [i]` | Blue info circle | Information |
| `- [b]` | Pink bookmark | Bookmark |
| `- [S]` | Green dollar | Savings/Money |
| `- [p]` | Green thumbs up | Pro/Positive |
| `- [c]` | Red thumbs down | Con/Negative |
| `- [/]` | Orange half-fill | In Progress |
| `- [u]` | Red up arrow | High Priority |
| `- [d]` | Blue down arrow | Low Priority |
| `- [w]` | Gold trophy | Win/Achievement |
| `- [k]` | Yellow key | Key point |
| `- [f]` | Orange flame | Urgent/Hot |
| `- [I]` | Yellow lightbulb | Idea |

**Example in your notes:**
```markdown
## Project Tasks
- [x] Research completed
- [/] Writing in progress
- [ ] Review needed
- [!] Deadline Friday
- [?] Ask about budget
- [I] New feature idea
- [p] Good user feedback
- [c] Performance issue
```

**To enable/disable:**
**Settings** → **Style Settings** → **Arcadia Checkboxes** → **Enable Alternate Checkboxes**

---

### Custom Callouts

Extended callout types beyond Obsidian's defaults.

**Usage:** Create a blockquote with `[!callout-type]` on the first line.

#### Timeline Callout
```markdown
> [!timeline] Project History
> **2024-01** - Project started
> **2024-03** - Beta release
> **2024-06** - Version 1.0
```

#### Profile/Person Callout
```markdown
> [!profile] John Smith
> Role: Project Manager
> Email: john@example.com
```

#### Aside/Margin Note
```markdown
> [!aside] Quick Note
> This appears as a sidebar note.
```

#### Definition Callout
```markdown
> [!definition] Markdown
> A lightweight markup language for creating formatted text.
```

#### Pro/Con Callouts
```markdown
> [!pro] Advantages
> - Fast performance
> - Easy to use

> [!con] Disadvantages
> - Learning curve
> - Limited features
```

#### Goal/Target Callout
```markdown
> [!goal] Q4 Objectives
> - Launch new product
> - Increase sales 20%
```

#### Bookmark/Reference Callout
```markdown
> [!bookmark] Resources
> - [Obsidian Help](https://help.obsidian.md)
> - [Style Settings](https://github.com/mgmeyers/obsidian-style-settings)
```

#### Question/Answer Callouts
```markdown
> [!question] How do I install themes?
> This is a common question.

> [!answer]
> Go to Settings → Appearance → Themes → Manage
```

#### Recipe/Steps Callout
```markdown
> [!recipe] Chocolate Cake
> 1. Preheat oven to 350°F
> 2. Mix dry ingredients
> 3. Add wet ingredients
> 4. Bake for 30 minutes
```

#### Kanban-style Callout
```markdown
> [!kanban] Sprint Board
> **To Do** | **In Progress** | **Done**
> Task 1 | Task 2 | Task 3
```

#### Paraphrase/Citation Callout
```markdown
> [!paraphrase] Einstein (1905)
> Energy equals mass times the speed of light squared.
```

#### Stats/Metrics Callout
```markdown
> [!stats] Monthly Report
> - Users: 10,000
> - Revenue: $50,000
> - Growth: 15%
```

---

### Sticky Notes

OneNote-style sticky note callouts in 8 colors.

**Usage:**
```markdown
> [!sticky-yellow] Remember
> Don't forget the meeting at 3pm!

> [!sticky-pink] Important
> Deadline is Friday.

> [!sticky-blue] Idea
> What if we tried a different approach?

> [!sticky-green] Done
> Task completed successfully.

> [!sticky-purple] Creative
> Brainstorm session notes.

> [!sticky-orange] Warning
> Check the budget first.

> [!sticky-gray] Archive
> Old notes for reference.

> [!sticky-teal] Project
> Sprint planning notes.
```

**Alternative syntax (also works):**
```markdown
> [!note-yellow] Title
> Content here

> [!note-pink] Title
> Content here
```

**Small inline sticky notes:**
Add `-sm` or `-small` suffix for compact stickies:
```markdown
> [!sticky-yellow-sm] Quick note
> Brief content
```

**Style variations** (enable in Style Settings):
- **Pushpin Style** — Adds a red pushpin at the top
- **Folded Corner** — Adds a folded corner effect
- **Flat Style** — Removes rotation and shadow

**To configure:**
**Settings** → **Style Settings** → **Arcadia Paper & Notes** → **Sticky Note Style**

---

> **Like what you see?** Help support continued development: [![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat-square&logo=buy-me-a-coffee)](https://buymeacoffee.com/drcarterd)

---

### Paper Styles

Transform your editor into realistic paper backgrounds.

**Available paper styles:**

| Style | Description | Best For |
|-------|-------------|----------|
| **Lined** | College ruled horizontal lines | Note-taking |
| **Grid** | Square graph paper | Diagrams, math |
| **Dot** | Bullet journal dot grid | Flexible layouts |
| **Graph** | Engineering graph paper | Technical drawing |
| **Legal** | Yellow legal pad | Traditional notes |
| **Cornell** | Cornell note-taking format | Study notes |
| **Isometric** | 3D isometric grid | 3D sketches |
| **Music** | Musical staff lines | Sheet music |

**To enable:**
**Settings** → **Style Settings** → **Arcadia Paper & Notes** → Select paper style toggle

**Page tint colors:**
- White (default)
- Cream
- Blue
- Green
- Pink
- Yellow
- Gray

**To change tint:**
**Settings** → **Style Settings** → **Arcadia Paper & Notes** → **Page Tint**

---

### Media Embedding

OneNote-style polished media presentation.

**Images:**
- Subtle shadows and rounded corners
- Smooth hover effects
- Optional lightbox (click to expand)

**Image size presets:**
```markdown
![[image.png|small]]   // 200px
![[image.png|medium]]  // 400px
![[image.png|large]]   // 600px
![[image.png|full]]    // 100% width
```

**Float images:**
```markdown
![[image.png|left]]    // Float left
![[image.png|right]]   // Float right
```

**Image captions:**
```markdown
![[image.png|This is my caption]]
```

**Video styling:**
- Custom player appearance
- Rounded corners
- Hover effects on controls

**Audio styling:**
- Pill-shaped player design
- Custom progress bar
- Consistent with theme colors

**Media gallery grid:**
Place multiple images in a callout for automatic grid layout:
```markdown
> [!gallery]
> ![[photo1.jpg]]
> ![[photo2.jpg]]
> ![[photo3.jpg]]
> ![[photo4.jpg]]
```

---

### Code Blocks

Enhanced code block styling with syntax themes.

**Syntax themes available:**
- **Dracula** — Popular dark theme with purple accents
- **Nord** — Arctic, north-bluish color palette
- **GitHub Dark** — GitHub's dark mode colors
- **GitHub Light** — GitHub's light mode colors

**Features:**
- Language label badge (shows "javascript", "python", etc.)
- Optional line numbers
- Copy button styling
- Smooth scrolling for long code

**To configure:**
**Settings** → **Style Settings** → **Arcadia Code Blocks**
- **Syntax Theme** — Choose color scheme
- **Show Line Numbers** — Toggle on/off
- **Show Language Label** — Toggle on/off

**Usage:**
~~~markdown
```javascript
function hello() {
  console.log("Hello, World!");
}
```
~~~

---

### Cards View

Display file lists as a grid of cards (great with Dataview).

**To enable:**
**Settings** → **Style Settings** → **Arcadia UI** → **Enable Cards View**

**Works with:**
- File explorer (folder contents)
- Search results
- Dataview TABLE queries

**Dataview example:**
```dataview
TABLE file.mtime as "Modified", file.size as "Size"
FROM "Projects"
SORT file.mtime DESC
```

---

### Rainbow Folders

Automatically color-code top-level folders in the file explorer.

**Color cycle (10 colors):**
1. Blue
2. Purple
3. Pink
4. Red
5. Orange
6. Yellow
7. Green
8. Teal
9. Cyan
10. Indigo

**To enable:**
**Settings** → **Style Settings** → **Arcadia UI** → **Enable Rainbow Folders**

Subfolders inherit a slightly muted version of their parent's color.

---

### Tag Colors

Tags are displayed as colored pills.

**Default colors by tag pattern:**
- `#project/*` — Blue
- `#status/*` — Green
- `#priority/*` — Red
- `#type/*` — Purple

Tags automatically get consistent colors based on their text.

---

### Progress Bars

Create visual progress indicators.

**Syntax using HTML:**
```html
<progress value="75" max="100"></progress>
```

**Syntax using Dataview:**
```dataview
TABLE
  "<progress value='" + progress + "' max='100'></progress>" as Progress
FROM "Projects"
```

---

### Image Controls

**Width controls:**
```markdown
![[image.png|100]]    // 100px wide
![[image.png|200]]    // 200px wide
![[image.png|50%]]    // 50% of container
```

**Position controls:**
```markdown
![[image.png|center]]  // Centered
![[image.png|left]]    // Float left
![[image.png|right]]   // Float right
```

**Style controls:**
```markdown
![[image.png|rounded]]   // Extra rounded corners
![[image.png|no-shadow]] // Remove shadow
![[image.png|border]]    // Add border
```

**Combine multiple:**
```markdown
![[image.png|300|center|rounded]]
```

---

## Accessibility

Arcadia includes several accessibility features:

### Visual Accessibility
- **WCAG AA compliant** contrast ratios
- **OpenDyslexic font** option for dyslexia
- **High contrast mode** available
- **Reduced motion** support (respects system preference)

### To enable accessibility features:

**OpenDyslexic font:**
**Settings** → **Style Settings** → **Arcadia Typography** → **Enable OpenDyslexic**

**Reduced motion:**
Automatically detected from your system settings. Or manually:
**Settings** → **Style Settings** → **Arcadia UI** → **Reduce Motion**

**Large audio player:**
**Settings** → **Style Settings** → **Arcadia Media** → **Large Audio Player**

---

## Plugin Compatibility

Arcadia is tested and styled for these popular plugins:

| Plugin | Compatibility |
|--------|---------------|
| **Style Settings** | Full integration (required for customization) |
| **Dataview** | Styled tables and lists |
| **Tasks** | Checkbox styling |
| **Kanban** | Board styling |
| **Calendar** | Date styling |
| **Excalidraw** | Canvas integration |

---

## Support This Theme

If you find Arcadia useful for your work, consider supporting its development:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=for-the-badge&logo=buy-me-a-coffee)](https://buymeacoffee.com/drcarterd)

**[Buy me a coffee](https://buymeacoffee.com/drcarterd)**

Your support helps maintain and improve this theme.

---

## Credits

**Author:** Peter J. Carter
**Website:** [theologyinfocus.org](https://theologyinfocus.org)

---

## License

**CC BY-NC 4.0** — Free to use and modify for personal/non-commercial purposes. Attribution required. For commercial use, contact the author.

---

## Changelog

### Version 2.0.0 (Current)
- 23 color schemes (11 dark, 12 light)
- 50+ file type icons with colors
- 21 alternate checkbox types
- OneNote-style media embedding
- Paper styles (lined, grid, dot, legal, Cornell, graph, isometric, music)
- Sticky notes callouts (8 colors with style variations)
- Code syntax themes (Dracula, Nord, GitHub)
- Rainbow folders
- Cards view for Dataview
- Tag color pills
- Progress bar styling
- Custom callouts (timeline, profile, definition, pro/con, etc.)
- Full Style Settings integration (60+ options)
- WCAG AA accessibility compliance
- OpenDyslexic font support
- Print styles for media
- Mobile responsive design
