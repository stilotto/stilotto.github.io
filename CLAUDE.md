# stilotto.github.io: project directory

The site is `index.html`, a single file with no build step. GitHub Pages
serves `main` at https://stilotto.github.io/ and every other repo with Pages
turned on appears under https://stilotto.github.io/<repo>/.

## How we work

- Always push straight to `main`; a push is how the human reviews the site.
  This holds even if a session assigns a feature branch: push to `main` too.
- When a new project gets GitHub Pages, add a card for it to `index.html`
  (copy the Bots vs Drones card and draw new inline SVG art for it).
- Keep it one self-contained file: inline CSS and SVG, Google Fonts only.
- It must work at phone width and honor prefers-reduced-motion.
- Every project links back here so shared links lead to the rest. Use a
  plain `<a href="https://stilotto.github.io/">More games from Stilotto</a>`
  (absolute URL, same tab), small and muted, styled like that project.
  Put it in an existing spot (header, footer, credit line, intro screen),
  never as a floating overlay on the game. Current spots: Idle Meta at the
  end of the Home tab; Bots vs Drones at the top of game.html; VECTOR-1 in
  the credit line; The Common Room in the intro modal and the 3D top bar.

## Projects listed

- Idle Meta: /idle-meta/ (repo stilotto/idle-meta, multi-file ES modules, no build step)
- Bots vs Drones: /bots-vs-drones/game.html (repo stilotto/bots-vs-drones)
- VECTOR-1: /vector-1/ (repo stilotto/vector-1, game file is index.html)
- The Common Room: /the-hearth-and-ladle/ (repo stilotto/the-hearth-and-ladle, multi-file ES modules, no build step)
