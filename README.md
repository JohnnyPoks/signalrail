# SignalRail

SignalRail is a Windows desktop app that watches Telegram channels for trading signals and
places the corresponding trades on Quotex automatically, under money-management rules you set
(daily targets, loss caps, per-trade risk). It's in early testing — you're likely reading this
because you were asked to try it, not because you found it on your own.

The source code is private; this repository exists only to host the installer, since a private
repo's release assets can't be downloaded without a GitHub account.

## Download

**[Latest release →](https://github.com/JohnnyPoks/signalrail/releases/latest)**

Download the `.exe` from the release's Assets section and run it. It's a normal Windows
installer — no account or sign-up needed for the install itself.

Only the current version is kept here. Older builds are removed when a new one is published, so
you're never looking at a release with a bug or a security gap that's since been fixed.

## Windows will warn you before it runs

This installer isn't signed with a paid code-signing certificate yet, so Windows SmartScreen
will show a blue "Windows protected your PC" screen the first time you run it. This is normal for
an app at this stage, not a sign that something's wrong.

To continue:
1. Click **More info**
2. Click **Run anyway**

## System requirements

- Windows 10 or 11, 64-bit
- A Quotex account (a free demo account works for testing)
- A Telegram account, if you want to connect a signal channel

## Reporting problems

Send feedback to whoever gave you this link. If the app crashes, it writes a diagnostic log you
can copy from Settings → Desktop app → View recent logs — include that when you report something
that didn't work.
