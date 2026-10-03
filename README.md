# git-infographic

A small static site called **git101**, a beginner-friendly guide to Git presented as a simple infographic.

> **Status:** work in progress. The shared navigation and styling are in place. The page content is still to come.

## Pages

| Page | File | Status |
| --- | --- | --- |
| Home | `index.html` | Navigation only |
| Git vs GitHub | `git-vs-github.html` | Empty |
| Commands | `commands.html` | Empty |

## Run locally

There is no build step and no dependencies. Open `index.html` in a browser, or serve the folder:

```bash
git clone https://github.com/Kleyen/git-infographic.git
cd git-infographic
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Project structure

```
git-infographic/
├── index.html
├── git-vs-github.html
├── commands.html
├── css/
│   └── style.css        # theme colors as CSS variables, nav and layout
├── scripts/
│   └── script.js        # placeholder for dark mode
└── assets/              # logo icons
```

## Built with

- HTML
- CSS (custom properties, no framework)
- Vanilla JavaScript (placeholder only)

## Roadmap

- [x] Shared navigation with an active-page highlight
- [ ] Home page content
- [ ] Git vs GitHub page
- [ ] Commands cheat sheet
- [ ] Dark mode (`scripts/script.js`)

## Credits

Icons are from [SVG Repo](https://www.svgrepo.com). Check each icon's page there for its license before reusing it.
