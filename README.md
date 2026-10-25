# Rewarded support website

Public privacy and support pages for Rewarded, hosted on GitHub Pages.

- Home: https://mrseizy.github.io/rewarded-support/
- Privacy Policy URL: https://mrseizy.github.io/rewarded-support/privacy/
- Support URL: https://mrseizy.github.io/rewarded-support/support/

## Updating the site

Edit the HTML pages or `assets/styles.css`, commit, and push to `main`.
GitHub Pages publishes from the root of `main`; `.nojekyll` keeps the site buildless.
No dependencies, JavaScript, analytics, or external fonts are required.

Preview locally with `python3 -m http.server 8080`, then open http://localhost:8080/.
All in-site links are relative so they work under the GitHub Pages project path.

The privacy policy is maintained in `privacy/index.html`. Keep it aligned with the
app's actual behavior, update the effective date when it changes, and review any
App Store privacy disclosures separately. The support contact currently uses
GitHub Issues. If switching to an email address, update both pages and the policy's
support-data explanation.

The app icon belongs to Rewarded and is copied here solely for this support site.
This repository contains the public website, not the iOS app's source code.
