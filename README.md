# Strandly — Support & Privacy Policy

Source for the two standalone pages Strandly links to from the App Store listing and
from inside the app itself (Settings → Learn more):

- **`strandly-privacy-policy.html`** — the app's Privacy Policy, covering what data
  Strandly collects, how it's used, where it's stored (on-device only, no backend), and
  the third-party services involved (OpenAI, RevenueCat, Apple/StoreKit).
- **`support.html`** — the app's Support page: a contact email and answers to the most
  common questions (deleting data, restoring on a new phone via Sign in with Apple,
  managing a subscription, restoring a purchase).

Both pages are self-contained static HTML (no build step, no dependencies beyond a
Google Fonts stylesheet) and are hosted at:

- https://orange-loris-398602.hostingersite.com/strandly-privacy-policy.html
- https://orange-loris-398602.hostingersite.com/support.html

## Deploying a change

Edit the HTML file, then upload the updated file through Hostinger's hPanel
(Websites → Manage → File Manager → `public_html`), replacing the existing file of
the same name. There's no CI/CD wired up — deployment is a manual upload.
