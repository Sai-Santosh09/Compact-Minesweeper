# Minesweeper

A simple Minesweeper game made with HTML, CSS, and JavaScript under 3KB.

## how to use it

Open `dist/index.html` in a browser, or copy the Data URI from `dist/uri.txt` into your browser.

Left click to open a cell and right click to place a flag.

## how it works

The game creates a 10×10 board and randomly places 10 mines. Each cell calculates the number of nearby mines. Opening an empty cell automatically reveals nearby empty cells.

The game ends when you open a mine or reveal all cells without mines.

## building
```bash
npm install
node build.mjs
```
