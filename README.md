# github_homepage

Source for my GitHub Pages homepage.

- Live site: https://windymaker.github.io/
- Repository: https://github.com/windymaker/windymaker.github.io

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site. Plain HTML and inline CSS, no JavaScript. |

There are no dependencies, no build step and no lockfile — nothing to install.

## How to preview locally

Open `index.html` directly in a browser (double-click it), or serve the folder if you prefer a real HTTP origin:

```powershell
cd github_homepage
python -m http.server 8000
# then open http://localhost:8000/
```

## How it is published

GitHub Pages serves the `main` branch, repository root, of the public repository
`windymaker/windymaker.github.io`. Pushing `index.html` to that branch is the whole deploy.
