# app.prayersealed.org

Public pages for the **Prayer Sealed** app, published by Prayer Sealed Ministries, Inc.:

| Page | Address |
| --- | --- |
| Overview | https://app.prayersealed.org/ |
| Privacy Policy | https://app.prayersealed.org/privacy |
| Terms of Service | https://app.prayersealed.org/terms |
| Support | https://app.prayersealed.org/support |
| Delete your account | https://app.prayersealed.org/delete-account |

The ministry's own site is [prayersealed.org](https://prayersealed.org) ([repo](https://github.com/prayer-sealed-ministries/prayersealed.org)).

## How it is served

A static site on GitHub Pages. Every push to `main` runs `.github/workflows/pages.yml`, which publishes the repository root as-is (no build step); it can also be run by hand from **Actions → Deploy to GitHub Pages**. Pages settings must use **Source: GitHub Actions**, with custom domain `app.prayersealed.org` (also recorded in `CNAME`). Pages are plain HTML sharing `styles/site.css`.

These pages moved from `prayerwarriors.mobi/prayer-sealed/…`. Once this site is live, the old addresses forward here (configured in the `Prayerwarriors.mobi` hosting), because the app, the App Store and Google Play listings, and Google Play's account-deletion link point at them. The demo mockup stays at `prayerwarriors.mobi/prayer-sealed/mockup/`.

## Changing a policy

The Privacy Policy and Terms are binding documents. When either changes, update its "Last updated" date in the same commit; both documents say that is how changes are announced.
