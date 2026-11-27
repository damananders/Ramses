# Ramses

A personal AI assistant that runs on your own Windows PC. It answers with local models by default, and with your own online key only when you allow it. Your chats, memory and files stay on your PC.

Version 1.0.2. MIT licensed. Free.

## Install

1. **Get Ollama (recommended).** Ramses runs local models through [Ollama](https://ollama.com), a free program. Without it, Ramses can still work with an online key.
2. **Unzip this folder** anywhere, then double-click **Install Ramses.cmd**. It installs for your Windows account only and needs no administrator rights. If Windows warns about an unknown publisher, choose **More info**, then **Run anyway**.
3. **Open Ramses** from the desktop or the Start menu. The first-run setup checks your hardware, explains each choice and offers to download the models that suit your PC.

Ramses installs to `%LOCALAPPDATA%\Ramses`: the program in `app`, your own data in `data`.

**Updating:** install the new version over the old one. Your chats, settings and memory are kept.

**Removing:** double-click **Uninstall Ramses.cmd**. It removes the program and shortcuts and keeps your data folder, so you can delete that yourself or keep it for later.

## What you need

- Windows 10 or 11, 64-bit.
- For local models, a graphics card with 8 GB of memory or more is best. Ramses picks models that fit your card, and smaller models run on less.
- About 50 MB for Ramses itself, plus the models you choose (usually 5 to 20 GB each).

## What it does

- **Chats and projects.** Keep threads on their own or group them in projects with their own memory, guidelines and model. You can give each chat its own motivation and guidelines too. Open two chats side by side.
- **Long jobs.** Ramses works through multi-step tasks for hours if needed. You see each step as it happens: it is building, downloading, reading or searching. Steps fold into a short summary, and you can right-click a step for the details.
- **Files and tools.** It can read, search, write and edit files (with backups), run PowerShell and git, and search your notes. Extra tools turn on when a chat needs them.
- **Mockups and documents.** It can make page mockups you can preview in the app, and documents such as a scope or a readme. Print any document or answer, or save it as a PDF.
- **Messages.** Copy a whole answer, reply to a single message, and react with emojis. Ramses can react too.
- **Models picked for your PC.** Ramses surveys your hardware and picks the best installed model for chat, big jobs and pictures. You can change any choice, download more models from Settings, or build a Ramses model tuned for your PC. The everyday model can load when you sign in to Windows, so the first answer comes at once.
- **Plays nicely with games.** When a game starts, Ramses frees the graphics card and waits. Queued work carries on afterwards.
- **Memory.** It remembers notes you approve, keeps project memory separate, and takes daily snapshots you can restore.
- **Look and feel.** 16 colour presets or your own colours, nine styles that change the whole look (glass, northern lights, neon, a green terminal screen, warm paper and more), any installed font and interface size. You can rename the assistant, and the whole app follows the new name.
- **Accessibility.** Easier-reading font and spacing, status shapes as well as colours, larger targets, a strong focus outline, reduce motion, read-aloud with a choice of voice and speed, a sound and a notice when long tasks finish (with quiet hours), and keyboard shortcuts you can change (press ? for the list).
- **Context and usage.** See what the model reads for each chat, how full its window is, which models are in memory, and 30 days of use and spending (Ctrl+Shift+U).
- **Your phone.** Use Ramses from your phone through Tailscale, privately, with no public address. Settings, Connections, Phone access has a pairing code.
- **Quit completely.** Quit from Settings or the tray icon, and Ramses stops entirely. Opening it again picks up where you left off.

## Privacy and safety

- The service listens on this PC only (127.0.0.1). Nothing is reachable from outside unless you set up phone access.
- Secrets are kept in an encrypted local vault and removed from anything that goes online. This can't be switched off.
- Online answers only happen when you have added your own key and turned online use on. A live cost meter and an optional monthly limit keep spending visible.
- No telemetry. Ramses doesn't send usage data to anyone. Update checks ask GitHub whether a newer version exists, only while online use is on, and you can turn them off.
- Safety rails are on by default. Five autonomy levels let you decide how much Ramses may do without asking. Every action is written to a timeline you can read.
- Ramses contains user-mode tools only: no drivers, and nothing that gets around anti-cheat, DRM or anti-tamper protection.

## Support

Ramses is free. If you'd like to support it, there are links at the bottom of Settings (shown only while online use is on), and now and then a small note in the corner that you can close.

Downloads and release notes: https://github.com/damananders/Ramses/releases
Website: https://damananders.github.io/
