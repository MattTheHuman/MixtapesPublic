# v2.15.0 - Security Maintenance Release

**Released: October 2026**

## What's new

- **Security remediation across dependencies** - Updated frontend and backend dependency trees to address reported vulnerability advisories.
- **Frontend hardening updates** - Angular toolchain and transitive npm packages were refreshed to clear `npm audit` findings.
- **Backend package updates** - Vulnerable NuGet packages were upgraded in both application and test projects.
- **Open Graph image pipeline migration** - Server-side OG image generation was migrated from SixLabors to SkiaSharp.
- **Container baseline refresh** - Docker build/runtime inputs were updated as part of the security maintenance pass.

## Notes

This is a security-focused maintenance release. No end-user workflow changes are required; improvements are primarily in dependency hygiene, build/runtime safety, and long-term maintainability.
