# stilotto.github.io: project directory

The site is `index.html`, a single file with no build step. GitHub Pages
serves `main` at https://stilotto.github.io/ and every other repo with Pages
turned on appears under https://stilotto.github.io/<repo>/.

## How we work

- Push straight to `main`; a push is how the human reviews the site.
- When a new project gets GitHub Pages, add a card for it to `index.html`
  (copy the Bots vs Drones card and draw new inline SVG art for it).
- Keep it one self-contained file: inline CSS and SVG, Google Fonts only.
- It must work at phone width and honor prefers-reduced-motion.

## Projects listed

- Bots vs Drones: /bots-vs-drones/game.html (repo stilotto/bots-vs-drones)
- VECTOR-1: /vector-1/ (repo stilotto/vector-1, game file is index.html)
- The Common Room: /the-hearth-and-ladle/ (repo stilotto/the-hearth-and-ladle, multi-file ES modules, no build step)
