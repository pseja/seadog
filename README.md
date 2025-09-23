# SeaDog

One file client-side web app to visualize C/C++ file dependencies using an interactive force-directed graph. This tool helps developers understand and analyze the relationships between C/C++ source files in a project.

## Features
- **Interactive Visualization**: Displays C file dependencies as a force-directed graph.
- **Client-Side Only**: No server required; everything runs in the browser.
- **Simple and Lightweight**: Single-file implementation for easy usage and distribution.

## Usage
### Online
1. Open [SeaDog on GitHub Pages](https://pseja.github.io/seadog/)
2. Click `Browse` and select a C/C++ folder you would like to visualize
3. When prompted, click on `Upload`

### Local
1. Clone this repository or download `seadog.html`
2. Open `seadog.html`
3. Click `Browse` and select a C/C++ folder you would like to visualize
4. When prompted, click on `Upload`

## Acknowledgements
- Inspired by [Obsidian's Graph view](https://help.obsidian.md/plugins/graph).
- Special thanks to the [D3.js open-source JavaScript library](https://d3js.org/) for graph visualization.

## Example visualization
[Curl master branch](https://github.com/curl/curl)
![curl master branch image](imgs/curl-visualization.png)
