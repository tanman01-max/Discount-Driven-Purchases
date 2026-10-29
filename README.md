# DiscountIQ

GitHub Pages-ready version of DiscountIQ.

## Publish
1. Upload **index.html** and **.nojekyll** to the root of a GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select `main` and `/ (root)`.
5. Save and open the generated GitHub Pages URL.

This version is static and does not require Node.js, npm, or a backend server.

### Authentication note
The included login is a client-side gate using browser localStorage. It is suitable for a demo/prototype on GitHub Pages, but it is **not a secure production authentication system**. Do not use it to protect confidential data or real user accounts.
