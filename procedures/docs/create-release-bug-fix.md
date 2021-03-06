Steps to create a BUG-FIX release
==================================


## Pre-release tasks

- [ ] Merge commits @quicksketch, @serundeputy
- [ ] Create a new bugfix release to follow the current version
- [ ] Move all unfinished issues to the next bugfix release
- [ ] Draft Release notes @serundeputy, @quicksketch, @jenlampton
- [ ] Draft Security Advisory (if necessary) @serundeputy, @quicksketch

## Release tasks

- [ ] Update bootstrap.inc with version number @quicksketch, @serundeputy
- [ ] Tag for release, push to GitHub @quicksketch, @serundeputy
- [ ] Revert version number back @quicksketch, @serundeputy
- [ ] Create release notes on GitHub @serundeputy, @quicksketch, @jenlampton
- [ ] Update the front page download link on b.org.
- [ ] Tweet that a new release is out @quicksketch, @jenlampton, @thejimbirch
- If this is a security release:
  - [ ] Publish Security Advisory on b.org
  - [ ] Mark the release node on b.org as a security release (tick the checkbox)

## Post-release tasks (asap)

- [ ] Update the docker image to the latest @serundeputy
- [ ] Push the bug-fix release to the Pantheon repository @quicksketch, @serundeputy
- [ ] Update the Wikipedia articles to at least show the proper version number and date for latest release @klonos
  - [ ] https://en.wikipedia.org/wiki/Backdrop_CMS
  - [ ] https://en.wikipedia.org/wiki/List_of_content_management_systems
