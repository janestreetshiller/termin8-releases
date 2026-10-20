Download the current Apple Silicon release: [Termin8 0.4.5 ZIP](https://github.com/janestreetshiller/termin8-releases/releases/download/v0.4.5/termin8-0.4.5-apple-silicon.zip). Intel Macs: [Termin8 0.4.3](https://github.com/janestreetshiller/termin8-releases/releases/tag/v0.4.3).

Open the ZIP and move termin8.app to Applications. The Apple Silicon build is Developer ID signed but not notarized. If macOS blocks the first launch, use System Settings -> Privacy & Security -> Open Anyway.

the last terminal you';; ever need.

# termin8

termin8 is a modern terminal app for macOS that feels faster and more capable than the built-in Terminal.

What it does
- Renders text and images smoothly using your Mac's GPU so scrolling and animations feel very fast and fluid.
- Shows images directly inside the terminal. When a command or link produces an image (a photo, a preview, a rendered chart), termin8 displays it inline instead of forcing you to open a separate image viewer.
- Keeps your sessions alive even after you close the window. Your shells and running programs continue to run in the background, and when you reopen the app everything — including scrollback — is restored where you left it.
- Includes a lightweight, text-first web browser inside a tab. You can read pages, follow links and fill simple forms without opening a full web browser.
- Lets you quickly find actions, settings and commands with a single command palette. Use it to open tabs, change preferences, or run built-in tools without digging through menus.
- Lists and reconnects to remote sessions or servers from the menu bar so joining a session is quick and straightforward.
- Provides convenient keyboard shortcuts for common tasks (searching scrollback, jumping between prompts, and more) so you spend less time reaching for the mouse.
- Is designed to be small, efficient and unobtrusive: a single native app that focuses on speed and clarity.

Getting started
1. Download the latest release for your Mac from the Releases page.
   - Use the Apple Silicon image on M1/M2/M3/M4 and later machines.
   - Use the Intel image on older Intel Macs.
2. Open the disk image (.dmg) and drag termin8 into your Applications folder.
3. Requires macOS 11 or later.

Security and authenticity
- Each release includes a SHA-256 checksum file (SHA256SUMS.txt). Verify downloads with:
  shasum -a 256 -c SHA256SUMS.txt
- Some releases may be signed with a Developer ID; notarization status is noted on each release.

License and third-party software
- termin8 is free to use but not open source. See LICENSE.txt for the legal terms.
- Open-source components included with the app are listed in THIRD-PARTY-NOTICES.txt inside the application bundle.

Want help or more detail?
If you’d like the README to emphasize usage examples, keyboard shortcuts, or a short walkthrough for first-time users, I can add a quick start section and a few short examples next.
