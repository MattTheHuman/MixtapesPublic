# v2.17.0 - Playlist Automation & Security Hardening

**Released: November 2026**

## What's new

- **Automatic Spotify playlist updates** - With Auto-manage enabled, released mixtape playlists now regenerate automatically when tracks are added or removed.
- **Release-gated playlist creation** - Spotify playlists are now created once a mixtape is set to Released to prevent pre-release exposure.
- **Playlist link health checks** - Mixtape edit now verifies linked Spotify playlists still exist and shows recovery guidance if a playlist was deleted on Spotify.
- **Security hardening improvements** - Security monitoring coverage and dependency update hygiene were strengthened as part of this release cycle.
- **Improved anonymous submission clarity** - Redacted submitter bars now use the site accent yellow for clearer visual contrast.

## Notes

- Automatic playlist updates are controlled by site settings and intended for communities with an admin Spotify connection configured.
- If a linked Spotify playlist has been deleted, admins can clear the stale link and regenerate to relink a new playlist.
- Security hardening work in this release focuses on faster dependency maintenance and improved operational response to vulnerability findings.
