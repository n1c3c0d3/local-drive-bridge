# Local Drive Bridge

Static homepage and privacy policy for a personal Google OAuth project used by
rclone and KDE KIO.

## GitHub Pages

1. Create a public GitHub repository.
2. Upload `index.html`, `privacy.html`, and `styles.css` to its default branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the default branch and `/ (root)`, then save.

Use the resulting URLs in Google Auth Platform:

- Application homepage: the site root URL
- Privacy policy: the site URL ending in `/privacy.html`
- Authorized domain: the GitHub Pages hostname without `https://` or a path

The Google Auth Platform app name should be **Local Drive Bridge** so it
matches the site.
