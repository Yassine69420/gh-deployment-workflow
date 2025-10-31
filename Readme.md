# gh-deployment-workflow

This repository shows a minimal GitHub Actions workflow that deploys `index.html` to GitHub Pages.

**Behavior**
- Every push to the `main` branch that **changes** `index.html` will run the workflow and publish the page.
- The published page will be available at:
  `https://<your-username>.github.io/gh-deployment-workflow/`

Replace `<your-username>` with your GitHub username.

## Files
- `index.html` — the page that will be published.
- `.github/workflows/deploy.yml` — the GitHub Actions workflow that uploads and deploys the page to GitHub Pages.

## How to use
1. Push this repo to GitHub with default branch `main`.
2. Optionally verify GitHub Pages settings (usually Pages will detect the Actions workflow).
3. Update `index.html`, commit and push — the workflow will run and deploy the updated page.
