# DisplayNOW 1.0 Beta 1 — Build 119

DisplayNOW's first public beta.

## What DisplayNOW does

Turn another Mac into an extra display over your local network.

Beta 1 includes:
- Extend Mode
- Mirror Mode
- App Mode
- Window Mode
- Keyboard and mouse control
- Visual Display Manager
- Wi-Fi, Ethernet and supported Thunderbolt networking paths
- Receiver availability and remembered-device workflow
- Battery status for connected MacBook Receivers
- One Universal DisplayNOW app for supported Apple Silicon and Intel Macs

## Beta status

This release is intended for testing. Please report compatibility problems and unexpected behaviour through GitHub Issues.

When reporting an issue, include:
- Host Mac model
- Receiver Mac model
- macOS version on each
- DisplayNOW mode
- Wi-Fi / Ethernet / Thunderbolt
- What you expected
- What happened

## Opening DisplayNOW if macOS blocks it

DisplayNOW Beta is not yet Apple-notarised.

Move DisplayNOW.app to Applications first. Try opening it normally and check System Settings → Privacy & Security → Open Anyway if offered.

If macOS still blocks the app and you trust the copy downloaded from this repository:

```bash
xattr -cr "/Applications/DisplayNOW.app"
```

Then open DisplayNOW normally.

Do not disable Gatekeeper globally.

## Security note

Beta 1's application transport is local-network TCP and is not yet cryptographically authenticated or encrypted. Use it only on networks you trust.

## Support

If DisplayNOW is useful to you, development can be supported through Patreon:
https://www.patreon.com/cw/SuBjEcT1991
