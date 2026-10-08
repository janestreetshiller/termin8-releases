# termin8

A fast, GPU-rendered terminal for macOS, written in Rust.

**[Download the latest release](../../releases/latest)** — pick the disk image for your Mac:

- `termin8-VERSION-apple-silicon.dmg` — M1, M2, M3, M4 and later
- `termin8-VERSION-intel.dmg` — Intel Macs

Open the disk image and drag termin8 into Applications. Requires macOS 11 or later.

The 0.4.0 Apple Silicon image is signed with Developer ID. It is not notarized yet.

## What you get

- **Graphics in the terminal.** Inline images from the kitty graphics protocol, sixel and iTerm2 inline images — `chafa`, `img2sixel`, `imgcat`, `timg`, `yazi` previews and friends just work.
- **Sessions that survive closing the window.** Shells and agents keep running when you quit; reopen termin8 and everything is where you left it, scrollback included.
- **A built-in web browser.** Read pages, search, follow links and fill simple forms inside a tab — no Chrome, no JavaScript. Image links open as real images.
- **One command palette.** ⌘K finds every action, setting and tool. ⌘F finds text in the scrollback.
- **Servers.** The menu-bar icon lists sessions and OMUX servers. Rejoin one, or start another, without a separate multiplexer.
- **Ouros, if you want it.** ⌘K → Ouros account signs in at ouros.md. The home bar can then ask the gateway for a command. You still press Enter. No account, no network: the terminal is the same.
- **Smooth and light.** Metal rendering, synchronized output, a single small native app. Shells that emit OSC 133 can jump prompts with ⌘↑ and ⌘↓.

termin8 is free to use. It is not open source; see [LICENSE.txt](LICENSE.txt). Open-source components it includes are listed in `THIRD-PARTY-NOTICES.txt` inside the app.

## Verify your download

Each release lists SHA-256 checksums in `SHA256SUMS.txt`:

```sh
shasum -a 256 -c SHA256SUMS.txt
```
