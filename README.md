# Brain Games: Memory & Focus — Support

Static support site for the iOS app **Brain Games: Memory & Focus**, designed to satisfy App Store Connect's required Support URL (and the Privacy Policy URL).

## Pages

- `index.html` — support home with contact + FAQ
- `privacy.html` — privacy policy
- `terms.html` — terms of use

Contact: **braingamessupport@gmail.com**

## Publish with GitHub Pages

1. Create a new **public** repo on GitHub (e.g. `brain-games-support`).
2. Push these files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial support site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)** → Save
4. Wait ~1 minute. Your site will be live at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```
5. Paste that URL into App Store Connect → App Information → **Support URL**.
   Use `https://<your-username>.github.io/<repo-name>/privacy.html` for **Privacy Policy URL**.

## Customizing

- Update FAQ answers in `index.html` to match your actual app behavior.
- Review `privacy.html` carefully — if you add analytics, ads, accounts, or anything that collects data, update the policy accordingly. This template assumes no personal data collection.
- Change the emoji favicon / logo (`🧠`) to match your brand if desired.
