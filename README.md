# Crisp chat widget demo

A small static website that shows how to embed a Crisp chat widget in a regular HTML page.

**[Open the GitHub Pages demo](https://theowllaw.github.io/n8nwebsite/)**

## How it works

- [index.html](index.html) renders the page and loads the demo script.
- [script.js](script.js) sets the Crisp website ID and loads the widget.
- [style.css](style.css) styles the page.

Crisp serves the chat widget and handles the chat session. The repository name reflects the original n8n experiment. The published source only embeds Crisp and contains no n8n workflow or backend.

## Run locally

1. Clone or download this repository.
2. Open `index.html` in a browser. The static page needs no build step or package install. The widget needs an internet connection.
3. To connect your own Crisp workspace, replace the website ID in `script.js` with your own.

The GitHub Pages demo is a preview of the widget embed. Use your own Crisp workspace to test sending messages.
