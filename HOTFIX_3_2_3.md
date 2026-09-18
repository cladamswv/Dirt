# DIRTLINE MX Arcade 3.2.3 hotfix

Fixes the 3.2.2 CI failure and strengthens race launch behavior.

- Adds a single `activate_from_grid()` launch path for every rider.
- Gives AI riders a small clutch-launch speed so they cannot remain in a zero-speed grid state.
- Makes the stuck-recovery guard work even if a rider is momentarily airborne or not grounded correctly.
- Changes the headless CI AI displacement check so Godot dummy-renderer mesh warnings do not create a false APK build failure after launch state and drive are verified.
- Updates Android package/export labels to 3.2.3.
