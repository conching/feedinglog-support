# BumpTrackr Feeding Log — Support Site

Support, FAQ, and privacy pages for **BumpTrackr Feeding Log**, an iOS app for
tracking newborn feeds, pump sessions, and hydration, with real-time iCloud
sharing between partners.

## Live pages

| Page | URL |
|------|-----|
| Home | https://conching.github.io/feedinglog-support/ |
| Support & FAQ | https://conching.github.io/feedinglog-support/support |
| Privacy Policy | https://conching.github.io/feedinglog-support/privacy |

These URLs are published on the app's App Store listing and must stay reachable.

## Stack

Static [Jekyll](https://jekyllrb.com/) site, built and served by GitHub Pages
from `main`. There is no local build step.

| Path | Purpose |
|------|---------|
| `index.md`, `support.md`, `privacy.md` | Page content (kramdown, `parse_block_html` on so inline HTML works) |
| `_layouts/default.html` | Shared page shell, nav, and styles |
| `_config.yml` | Site title, description, and `baseurl` |
| `app-icon.png` | App icon used in the page header |

## Making changes

Edit the relevant `.md` file and push to `main`. GitHub Pages rebuilds
automatically, usually within a minute. Confirm the live URL afterward —
a broken support link is an App Store review issue.

Contact: conching@me.com
