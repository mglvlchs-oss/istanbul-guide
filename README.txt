ISTANBUL GUIDE — iPhone Web App

This folder is ready to host as a static website.

IMPORTANT
The Add to Home Screen / offline-app features require HTTPS hosting. Opening index.html directly from Files will NOT install the PWA.

FASTEST SETUP WITH GITHUB PAGES
1. Create a new GitHub repository (for example: istanbul-guide).
2. Upload every file and folder from this package, preserving the structure.
3. In the repository: Settings → Pages → Deploy from a branch → main → / (root) → Save.
4. Wait for GitHub Pages to publish the site.
5. Open the resulting HTTPS URL in Safari on the iPhone.
6. Tap Share → Add to Home Screen → Add.

The icon is already configured. The service worker caches the guide for offline use after the first successful load.
