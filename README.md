# memoryauditprotocol.org

Source for the Memory Audit Protocol website.

One file. No build step, no dependencies, no JavaScript. `index.html` is the site.

## Deploy

Hosting is cPanel on Spaceship, in the EU. This repository is the source of truth; the hosting is a deploy target.

The server clones this repository through cPanel's Git Version Control and a cron job copies `index.html` into the document root. No deployment credentials are stored in GitHub, and no server paths are recorded here.

To ship a change: push to `main`. The server picks it up on the next cron run.

## Constraints

The site is about data governance, so it holds itself to the standard it argues for:

- No third-party requests of any kind. No CDN fonts, no external scripts, no remote images.
- No cookies, and therefore no consent banner.
- No analytics.

Anything added later has to keep all three true.
