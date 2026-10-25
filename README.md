# CHECK FATE

A chess roguelite for phones and browsers. You are the king: survive twenty minutes on an endless board while the pieces close in. Every enemy moves and strikes by the rules of chess, and every strike is announced on the board a moment before it lands.

Game by Dawid Hyla.

## Play

Open `index.html` in any modern browser, or publish this folder with GitHub Pages:

1. Create a repository and upload `index.html`, `.nojekyll` and this README.
2. In the repository settings open Pages, choose "Deploy from a branch", branch `main`, folder `/ (root)`.
3. After a minute the game is live at `https://<your-name>.github.io/<repository>/`.

Progress is saved in the browser (localStorage). The game is one self-contained file; only the fonts load from Google Fonts.

## Controls

Swipe in any of eight directions to move the king one square, or simply tap the screen on the side of the king you want him to go (on a keyboard: arrows or WASD, plus Q E Z C for the diagonals). Step into an enemy piece to strike it. Red squares are about to be struck.

## For testers

Development settings (shorter reigns, immortality, the starting minute, all maps open and so on) are hidden in this build. Open the page with `?dev=1` at the end of the address to show them.
