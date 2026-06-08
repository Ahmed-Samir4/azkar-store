# Azkar — Chrome Extension (store assets)

This repository contains the store-facing assets for the "Azkar" browser extension (v1.8.0). It is prepared for public hosting so you can point the Chrome Web Store to the privacy policy and listing material.

**Included**
- `store-assets/PRIVACY-POLICY.md` — privacy policy (Arabic + English).

**Purpose**
- Host `PRIVACY-POLICY.md` at a public URL (GitHub repo) and paste that URL into the Chrome Web Store Privacy Policy field.

Note: `STORE-LISTING.md` is included for copy-paste only — do NOT upload it inside the store package. Fill the Web Store listing fields by copying text from `STORE-LISTING.md` in this repo.

**Before you push**
1. Verify `store-assets/PRIVACY-POLICY.md` contains the correct contact details (already filled).
2. Enable GitHub Pages for this repo (branch: `main`, folder: `/`) to publish the visitor site.

**Recommended Git commands**

```bash
# from this folder (azkar-store)
git init
git add .
git commit -m "Add store assets: privacy policy and listing"
# create a public repo on GitHub (via the website) named e.g. azkar-store
# then push (replace <user> and <repo>):
git remote add origin git@github.com:<user>/<repo>.git
git branch -M main
git push -u origin main
```

**Privacy policy URL templates**
- Raw file URL (works immediately after push):
  `https://raw.githubusercontent.com/Ahmed-Samir4/azkar-store/main/store-assets/PRIVACY-POLICY.md`
- GitHub Pages (recommended): enable Pages (branch `main`) and the policy will be available at:
  `https://Ahmed-Samir4.github.io/azkar-store/store-assets/privacy-policy.html`

**What to include in the Chrome Web Store Privacy practices tab**
 - Single-purpose statement and permission justifications are provided in `STORE-LISTING.md` for you to copy into the dashboard (do not upload the file itself).
 - Paste the public Privacy Policy URL after you push.

**Privacy policy URL to use in the Chrome Web Store**
`https://Ahmed-Samir4.github.io/azkar-store/store-assets/privacy-policy.html`

If you want, I can (a) prepare a simple HTML page for GitHub Pages, (b) open and update the contact line with an email you provide, or (c) create the Git repo and push if you give me access tokens. Which would you like next?
