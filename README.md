# My Web Tools (Workshop)

A single home for small, useful browser apps. Drop each app into its own folder and they’ll be hosted automatically via **GitHub Pages**.

---

## Quick Start
1. Create a new public repo (e.g., `my-web-tools`) on GitHub.
2. Upload the contents of this ZIP to the repo root.
3. Go to **Settings → Pages** → set **Source** to `main` branch and `/ (root)`.
4. Your site will be live at: `https://<your-username>.github.io/my-web-tools/`

## Adding your existing tools
- Put your budget app files into `budget-tracker/`
- Put your income app files into `income-tracker/`
- Visit the site and click each card to open

## Replacing a file (e.g., new `index.html`)
- In GitHub, open the folder → **Add file → Upload files** → choose your new file
- If asked, accept **Replace** and **Commit changes**
- GitHub keeps the old version in history — no need to keep `index-old.html` as a backup

## Deleting a file
- Click the file → click the trash can (top right) → **Commit changes**

## Restoring a previous version (undo)
- Click **History** on the file or repo
- Open the previous commit → **Revert** or copy the old content back in

## Organizing multiple tools
```
/ (repo root)
  index.html          # Hub page linking to your tools
  /budget-tracker/    # Put your app files here
  /income-tracker/    # Put your app files here
  /assets/            # Images or shared assets
```
Each folder can be opened at `/folder-name/` (e.g., `/budget-tracker/`).

## Notes
- Don’t upload files > 100MB (GitHub blocks them).
- Don’t store secrets (passwords, API keys) in a public repo.
- Use short commit messages like “update budget categories” to keep history readable.

See `assets/github-cheatsheet.png` for a visual “buttons & clicks” guide.
