# GitHub Pages + Codespaces: iOS Settings Software Update Demo

A static, responsive HTML/CSS/JavaScript example inspired by **Settings → General → Software Update**.

> This is an unofficial UI simulation. It does not connect to Apple update services, access iOS Settings, or install software. The “iOS 2.0” wording is a project prompt, not a real update offer.

## Run in GitHub Codespaces
1. Create a new GitHub repository and upload these files, or add this folder to a repository.
2. Choose **Code → Codespaces → Create codespace on main**.
3. In the terminal, run:
   ```bash
   python3 -m http.server 8000
   ```
4. Open the forwarded port 8000 in the Ports panel.

## Publish with GitHub Pages
1. Push `index.html` and `README.md` to the repository's `main` branch.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`, then Save.
5. Visit the Pages URL shown in Settings → Pages after deployment completes.

GitHub Pages hosts static files, so no build step or backend is needed.

## Files
- `index.html` — complete app in one file
- `.devcontainer/devcontainer.json` — small Codespaces configuration

## Customize
Edit the text, CSS variables, colors, and simulated update interaction in `index.html`.
