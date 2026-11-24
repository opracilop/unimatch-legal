# unimatch-legal

Public GitHub Pages site for UniMatch legal pages (privacy policy only).  
**Does not contain the UniMatch app source code.**

## Live URL (after Pages is enabled)

`https://<your-github-username>.github.io/unimatch-legal/`

Use that URL in Google Play Console → App content → Privacy policy.

## Publish

```powershell
cd C:\Users\polic\Documents\unimatch-legal
git init
git add .
git commit -m "Add UniMatch privacy policy for Play Store"
gh repo create unimatch-legal --public --source=. --remote=origin --push
```

Then on GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `/ (root)` → Save**.

Wait ~1 minute and open the Pages URL.
