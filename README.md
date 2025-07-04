# Fredericksburg Birding Club Website

This site is ready to deploy to GitHub Pages.

## How to Deploy

1. Make sure your code is committed to your repository.
2. Install dependencies:
   ```sh
   npm install
   ```
3. Deploy to GitHub Pages:
   ```sh
   npm run deploy
   ```

This will publish the site using the contents of the repository root.

## Notes
- Ensure your repository is public and has GitHub Pages enabled (set to deploy from the `gh-pages` branch or `/` root as needed).
- If your repository is not named `fredbirds`, update the `homepage` field in `package.json` accordingly for custom domains or user/organization pages.
- If you want to use a custom domain, add a `CNAME` file with your domain name.
