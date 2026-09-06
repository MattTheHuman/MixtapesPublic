# v2.14.1 - Tech Stack and Performance Upgrade

**Released: September 2026**

## What's new

- **Angular 21 Upgrade** - Frontend upgraded to Angular 21 with TypeScript 5.9 and modernized signal-first patterns.
- **.NET 10 Backend** - Server runtime upgraded to .NET 10 for current platform support.
- **Faster Route Loading** - Core app pages now lazy-load so first load is lighter and navigation scales better.
- **About Changelog Refresh** - About page changelog is now data-driven and deferred for faster initial rendering.
- **Image Loading Improvements** - Artwork and avatar surfaces now use lazy loading and async decoding for better performance on large pages.
- **Small Mobile Refresh** - Mobile track rows now use tighter likes/listens spacing, the mobile header brand links back to home, the Spotify call-to-action is shortened to "Listen" on phones, and the update announcement popup now handles browser height changes with smoother scrolling.
- **Playlist Generation Reliability** - Playlist generation now includes stronger validation, clearer failure messaging, and safer guardrails for unsupported states.

## Notes

This release focuses on platform modernization, performance, and long-term maintainability. End-user behavior remains the same, with faster loading and a cleaner delivery pipeline behind the scenes.
