# nicecoldmc.github.io# Project Hollow site

Source for the Project Hollow website, a hub for NicecoldMC's Minecraft projects. It is plain HTML and CSS, with no build step, and is hosted on GitHub Pages.

## Files

| File | What it is |
|---|---|
| `index.html` | Home page with a card for each project |
| `null-pvp.html` | Project page for the Null PvP+ modpack |
| `style.css` | Shared styling for every page |

## Editing

Change a file on GitHub (open it, click the pencil icon, commit) and the live site updates after a minute or so.

To add a project:
1. Copy `null-pvp.html` to a new file, for example `my-project.html`, and edit the text.
2. In `index.html`, copy a `card` block and point its "Project page" link at the new file.

## Hosting

In the repository settings, open **Pages**, choose **Deploy from a branch**, then select the `main` branch and the `/ (root)` folder.

## License

[MIT](LICENSE.md). The projects linked from the site keep their own licenses.
