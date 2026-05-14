# memory-game

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple yet challenging memory game where you represent numbers in binary by selecting cells from a grid of powers of two.

## Demo

Play the game live at: **[https://code4fukui.github.io/memory-game/](https://code4fukui.github.io/memory-game/)**

## How to Play

1.  A target number is shown at the top of the screen (e.g., "13をおぼえてね" which means "Memorize 13").
2.  Your goal is to click cells in the 4x4 grid so their values sum up to the target number.
3.  Each cell in the grid represents a power of two (1, 2, 4, 8, ... 32768).
4.  When the sum of the selected cells is correct, you automatically advance to the next level.
5.  Complete all 10 levels to win. The target numbers become larger as you progress.

## Features

- **Binary Puzzle Gameplay:** Challenge your memory by representing numbers as a sum of powers of two.
- **Progressive Difficulty:** 10 levels with target numbers increasing in magnitude up to 65,535.
- **Interactive Grid:** A 4x4 grid with clear visual feedback for selected cells.
- **Lightweight & Fast:** Runs entirely in the browser with no server-side dependencies.

## Usage

To run the game locally, simply open the `index.html` file in your web browser.

## Attribution

This application is based on an idea by Taisuke Fukuno ([App CC BY 福野泰介](https://fukuno.jig.jp/3300)).

## License

MIT License — see [LICENSE](LICENSE).