MATT TECHNOLOGIES V3 - MOBILE DESIGN PATCH

This package is designed to be copied into the existing Express/EJS Matt Technologies project.

Files:
- public/style.css              Replace the existing CSS
- public/matt-technologies-logo.png
- public/matt-technologies-mark.png
- views/Partials.ejs             Replace/update the existing Partials.ejs
- views/home.ejs                 Replace/update the existing home.ejs

IMPORTANT:
1. Keep the filename Partials.ejs with a capital P because the current EJS templates use include("Partials").
2. Keep this application as a Render Web Service, not a Static Site, because it uses Express/EJS/PostgreSQL.
3. The server already serves the public folder, so the images must be inside public/.
4. Commit these files to GitHub and let Render redeploy the main branch.

Render:
Build command: npm install (or yarn if your existing service is already working)
Start command: node server.js
