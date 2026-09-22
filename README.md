# Elite Gaming Zone — Website

A single self-contained `index.html` (video, images and fonts are all embedded inside it), ready to deploy on GitHub Pages.

## How to make it live on GitHub Pages

1. Go to https://github.com and create a **new repository** (e.g. `elite-gaming-zone`). Keep it Public.
2. On the new repo's page, click **"uploading an existing file"** (or drag-and-drop).
3. Drag in `index.html` from this folder and click **Commit changes**.
4. In the repo, go to **Settings → Pages** (left sidebar).
5. Under "Build and deployment" → **Source**, choose **Deploy from a branch**.
6. Under **Branch**, choose `main` and folder `/ (root)`, then click **Save**.
7. Wait 1-2 minutes, then refresh that Pages settings page — GitHub will show your live URL, something like:
   `https://<your-username>.github.io/elite-gaming-zone/`

That link is your live website — share it with anyone.

## Updating the site later

Just edit `index.html` (or ask Claude to make changes and give you a new one), upload it again to the same repo overwriting the old file, and GitHub Pages updates automatically within a minute or two.

## Using your own domain (optional)

In the same **Settings → Pages** screen there's a **Custom domain** field — enter your domain there and follow GitHub's instructions to point your DNS at GitHub Pages.
