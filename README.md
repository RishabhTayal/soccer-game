# Soccer

Arcade 1v1 soccer. You are HOME (blue #10) vs AWAY (red #9).

## Play

Open `index.html` in a browser, or visit the Vercel deploy.

- Move: WASD or arrow keys
- Kick: hold Space to charge, release to shoot
- Sprint: Shift
- Start / play again: Space, Enter, or click

3-minute match. You attack the right goal.

## Run locally

```bash
# just open the file
open index.html
```

Or serve it:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Deploy (Vercel)

This is a static site. Root `index.html`, no build step.

Import the GitHub repo in Vercel (framework: Other / no framework). Every push to `main` publishes.

Or from the CLI:

```bash
npx vercel --prod
```
