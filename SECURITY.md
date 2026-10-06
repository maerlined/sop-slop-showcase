# Security — sop-slop showcase

Checklist, not prose. Check each box or state why it doesn't apply.

- [x] **No secrets.** One static HTML file. No keys, tokens or config.
- [x] **No personal data.** Curated text about how the system works. No names of private projects, session IDs, paths, or records from the private repo; the one sample record is labelled as adapted. Reviewed for this by the workspace's integrator session before publishing.
- [x] **No third-party requests.** System fonts only; the page contains no URLs and loads nothing.
- [x] **No data collection.** No scripts, analytics, cookies, forms or storage.
- [ ] **GitHub Actions use pinned action hashes**: *not applicable*, no workflows. Pages builds from `main` (root) without Actions.

## Updating

This repo is the page's canonical home. A change goes in by pull request, with a review before merge (the workspace's T3 process: public repo). Any claim on the page about how the private system works must match its current rules.

## Reporting

Something wrong? Open an issue on this repo.
