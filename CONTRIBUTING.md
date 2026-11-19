# Contributing

Thanks for helping! The README is generated, so please **edit only [`data/apps.json`](data/apps.json)**.

## Adding an app

Add one object to `data/apps.json`:

```json
{
  "name": "AppName",
  "repo": "owner/repo",
  "category": "menubar",
  "description": "What it does, in one line"
}
```

- `repo` is the GitHub `owner/repo` of the app's source code.
- `category` is one of the slugs below.
- `description` is optional: without it, the GitHub description is used. No trailing period, no marketing ("best", "ultimate").

The app must be **open source**, a **native or desktop app that runs on macOS**, and **maintained** (a commit in the last 24 months). Apps that stop being maintained move to the Unmaintained section automatically.

## Inclusion rules

Every pull request is checked automatically. To be accepted, the repository needs:

- at least **10 GitHub stars** (apps below 10 stay in the data but are hidden from the list until they reach it)
- to be at least **30 days old**, with at least **10 commits**
- an owner account at least **90 days old**
- a **license** file
- to be the **original project**, not a fork of an app that is still maintained

## Safety

The list links to software people install on their Macs, so anything that looks like malware is rejected and the repository is blocked for good:

- release files that are Windows scripts or shortcuts (`.scr`, `.lnk`, `.vbs`, `.bat`, `.ps1`, …)
- downloads hosted on file-sharing services (MediaFire, MEGA, Google Drive files, …) or archives with a password in the README
- obfuscated install commands (base64 piped into a shell) or instructions to disable Gatekeeper system-wide
- no source code, with only non-macOS binaries in the releases

Unsigned apps that ask you to clear the quarantine flag, and `curl | sh` installers, are allowed but reviewed by hand.

One app per pull request, please. Stars, last commit and Homebrew casks are filled in by the weekly refresh: don't add them by hand.

## Categories

| Slug | Section |
| --- | --- |
| `ai` | AI & LLM |
| `audio` | Audio & Music |
| `backup` | Backup & Sync |
| `browsers` | Browsers |
| `communication` | Chat & Communication |
| `editors` | Code & Text Editors |
| `databases` | Databases |
| `design` | Design & Graphics |
| `developer` | Developer Tools |
| `downloads` | Downloaders |
| `email` | Email |
| `files` | Files & Finder |
| `finance` | Finance & Crypto |
| `games` | Games & Emulators |
| `git` | Git |
| `images` | Images & Screenshots |
| `keyboard` | Keyboard & Input |
| `writing` | Markdown & Writing |
| `menubar` | Menu Bar |
| `network` | Network, VPN & Proxy |
| `notes` | Notes & Knowledge |
| `productivity` | Productivity |
| `reading` | Reading, News & RSS |
| `security` | Security & Privacy |
| `system` | System & Monitoring |
| `terminal` | Terminal |
| `utilities` | Utilities |
| `video` | Video & Screen Recording |
| `virtualization` | Virtualization |
| `wallpapers` | Wallpapers & Screensavers |
| `windows` | Window Management |
