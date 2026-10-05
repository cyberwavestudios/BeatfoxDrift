# Beatfox: Drift — open-access self-hosting handoff

This private repository belongs to `cyberwavestudios`. Download **BeatfoxDrift-open-access-source-and-build.zip** from [the handoff release](https://github.com/cyberwavestudios/BeatfoxDrift/releases/tag/open-access-handoff-2026-10-05). It contains the complete source, built Node app, soundtrack, and assets. The small `BeatfoxDrift-source-code-snapshot.zip` on the main branch omits music and is **not** deployable by itself. Do not use GitHub’s automatic “Source code (zip)” archive for deployment.

The Patreon access-code screen and validation handler were removed in this GitHub edition; no `ACCESS_CODE` is needed. `SELF-HOSTING.md` inside the complete ZIP has deployment notes. The rebuilt app passed TypeScript and production build checks, opened directly to the game menu, and its score advanced after START DRIFTING in a localhost browser test.

Run the Node app behind HTTPS and test full gameplay, audio, and mobile behavior before changing DNS or cancelling Replit. Historical high-score rows and all secrets remain outside GitHub. The live Replit app was not changed.
