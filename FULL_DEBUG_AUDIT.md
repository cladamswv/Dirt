# DIRTLINE MX Arcade 3.2.3 STABLE — Full Debug Audit

This clean fresh-install package is based on the exact Arcade 3.2.3 runtime code that completed the GitHub Actions Android pipeline successfully.

Verified in GitHub Actions on commit `bce2866c6089ccc9bb628df853d47ea40801c0a2`:

- Godot 4.3 project import and script/resource parsing: PASS
- Runtime five-lane/presentation smoke test: PASS
- Touch control instantiation and player-throttle movement regression: PASS
- Seven-rider grid activation and AI launch/drive regression: PASS
- Player engine and AI motorcycle audio stream regression: PASS
- Android debug APK export: PASS
- APK signature verification: PASS
- Android package/manifest verification: PASS
- APK artifact upload: PASS

The clean distribution also contains `tools/full_audit.py`, a dependency-free preflight checker for resource references, input actions, GLB containers, image/audio headers, Android/version metadata, and the specific controls/audio/grid-launch regressions fixed during 3.2.x.

Historical superseded debug/hotfix documents were removed from this distribution to avoid version confusion. Gameplay code and assets are unchanged from the passing 3.2.3 build.
