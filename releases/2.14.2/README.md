# v2.14.2 - Create Flow Reliability Patch

**Released: October 2026**

## What's new

- **Create Mixtape Save Fix** - Fixed a regression where saving a new mixtape could reload the page without creating it. Save now consistently submits and opens the newly created mixtape.
- **Role Check Response Fix** - The role-check endpoint now returns a concrete boolean response, improving reliability of admin-only route guards.

## Notes

This is a focused patch release aimed at create-flow reliability and auth guard stability after the platform upgrade.
