# ChemSafe AI — iPad browser edition

This edition is a single-file web app designed for Safari on iPad. It does not require Python,
Streamlit, or an app-store installation. It stores entered information in Safari's local browser
storage on this iPad.

## Easiest way to use it
The app needs to be opened from a web address for the most reliable Safari experience. You can
publish this folder for free with GitHub Pages:

1. On the iPad, open github.com in Safari and sign in or create a GitHub account.
2. Create a new public repository, for example `chemsafe-ai`.
3. Upload `index.html` from this folder to the repository root.
4. In the repository, open Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch; choose `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Open the Pages URL shown on that settings page in Safari.
7. Use Safari's Share button → Add to Home Screen if you want an app-like icon.

You can also publish the file using another static web host. No server or API key is required.

## What works
- Search chemical identity by name, formula, or CAS.
- Add chemicals.
- Enter SDS-based hazard, PPE, handling, first-aid, and spill data.
- Save pairwise compatibility assessments with source and conditions.
- Retrieve entered information in the corresponding sections.
- Local keyword lookup assistant that only answers from saved records.
- Export/import a JSON backup.

## Data and safety
Starter chemicals have identity data only. No safety recommendations are pre-filled. A missing
record means unknown, never safe or compatible. Use the current SDS for the exact product,
supplier, and concentration; check your institution's procedures and qualified safety staff.
This educational prototype is not a certified safety system or emergency service.

Data is stored in this browser on this iPad. Clearing Safari website data may erase it. Export
regular JSON backups from Manage Data. Data is not automatically synchronized to other devices.
