# ZYNOVA Calculator & AI

This is the static website package for ZYNOVA.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository, for example `zynova-calculator`.
2. Upload `index.html` and this `README.md` to the repository root (not inside another folder).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for GitHub Pages to finish deploying. The repository's Pages section will show the website address.

## Important functionality note

The current build keeps the calculator, quizzes, learning content, local profile, and local browser storage available. Online account authentication, cross-device cloud synchronisation, and real subscription checkout require a separately hosted backend and are not enabled by this static-only package. Do not enter sensitive or real passwords into a demonstration/local-only account flow.

## Updating the site

Replace the root `index.html` with the new version and commit the change. GitHub Pages will publish the update automatically after the deployment finishes.
