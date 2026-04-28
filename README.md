# Eluno Legal Site

Minimal static legal pages for **Eluno**, designed for GitHub Pages.

## Files

- `index.html`
- `privacy.html`
- `terms.html`
- `styles.css`

## Publish on GitHub Pages

### Option A: Publish from root

1. Push this project to a GitHub repository.
2. Open **Settings** -> **Pages**.
3. Under **Build and deployment**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or your default branch)
   - **Folder**: `/ (root)`
4. Save and wait for deployment.

### Option B: Publish from `/docs`

1. Move site files into a `/docs` folder.
2. Commit and push.
3. In **Settings** -> **Pages**, select branch `main` and folder `/docs`.
4. Save and wait for deployment.

## URL format examples

For repository name `eluno` under user `zxus777`:

- `https://zxus777.github.io/eluno/`
- `https://zxus777.github.io/eluno/privacy.html`
- `https://zxus777.github.io/eluno/terms.html`

## Verify after deploy

- Open all three pages and confirm they load.
- Check navigation links between Privacy Policy and Terms of Service.
- Confirm mobile layout and readable typography.
- Confirm contact email link opens a mail client.
