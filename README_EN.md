<p align="center"><img src="./assets/icon-256.png" width="104" alt="SonicLab Flow icon"></p>
<h1 align="center">SonicLab Flow</h1>
<p align="center"><strong>A local sound library and professional workstation</strong></p>
<p align="center">Search, audition, organize, and deliver — a library of ten thousand sounds, handled on one machine.</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/简体中文-2B2F38?style=for-the-badge&labelColor=15171C" alt="简体中文"></a>
  <a href="./README_EN.md"><img src="https://img.shields.io/badge/English-7C6FF7?style=for-the-badge&labelColor=15171C" alt="English"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Release-v0.6.9_BETA-7C6FF7?style=flat-square" alt="v0.6.9 Beta">
  <img src="https://img.shields.io/badge/Closed--source-All_rights_reserved-1F9D75?style=flat-square" alt="Closed source">
</p>

<p align="center"><a href="https://garrygit888.github.io/SonicLab_Flow_Updates/">Website</a> · <a href="https://cnb.cool/garrykai/SonicLab_Flow_Updates/-/releases/tag/v0.6.9">CNB Download</a> · <a href="https://github.com/GarryGit888/SonicLab_Flow_Updates/releases/tag/v0.6.9">GitHub Download</a> · <a href="#contact-the-developer">Contact</a></p>

<img src="./assets/hero-workspace.jpg" width="100%" alt="SonicLab Flow main window: library tree, audio list with AI tags, metadata inspector, and bottom waveform">

> **This is a closed-source BETA.** SonicLab Flow is an independently developed commercial product. Its source code is not published; this repository only hosts installers, release information, and product documentation.

## What is SonicLab Flow?

SonicLab Flow is built for film editors, sound designers, game audio teams, and anyone maintaining a large sound effects library. It brings search, audition, tagging, and delivery into one desktop window: mount existing folders without moving the originals, judge sounds through Chinese titles, tags, AI descriptions, and waveforms, then send the chosen files straight to an editing timeline.

| Principle | What it means |
| --- | --- |
| Local-first | Media, indexes, waveform caches, and metadata stay on your machine. Audio files are never uploaded. |
| Workflow-focused | Search → audition → organize → deliver, all reachable from one window with fewer tool switches. |
| Metadata follows the file | Chinese titles, tags, descriptions, and artwork are written back into the files themselves, UCS-compatible, so nothing is lost when tools or machines change. |
| Built for scale | Ten-thousand-file libraries filter instantly, with a dual-layer waveform engine and parallel loading that keep scrolling and playback smooth. |

## Highlights

- **Chinese-first search**: Filter by filename, Chinese title, tags, and AI descriptions in parallel — Chinese keywords reach straight into an English library.
- **Click-to-play auditioning**: Click anywhere in a row for instant playback; the inline waveform and the main waveform light up together, and long files stay responsive.
- **Dual-layer waveform engine**: A preview layer appears first and the high-resolution layer fills in seamlessly; the bottom waveform is there for detail and in/out points.
- **UCS metadata management**: Edit Chinese titles, tags, descriptions, and artwork once, then write them back into the file itself, including UCS category fields.
- **Tags and batch organization**: Tag library, color marks, flags, rename, batch operations, and playlists keep organization in one place.
- **AI Agent assistant**: A side panel for conversational search and recommendations with switchable models — describe the use case, mood, and duration when you cannot name the sound.
- **AI Chinese tags and descriptions**: Generate Chinese tags and descriptions for English assets automatically, so even an untagged library becomes searchable in Chinese.
- **Direct-to-timeline delivery**: Send selected audio to a DaVinci Resolve timeline in one click, or drag it into other editing software.
- **FreeSound integration**: Search and audition FreeSound assets in-app, and download original files after a one-time OAuth2 authorization.
- **Cross-platform desktop**: Builds for macOS Apple Silicon, macOS Intel, and Windows x64.

## Product Tour

<table>
  <tr>
    <td width="50%"><img src="./assets/search.jpg" alt="Chinese search interface"><br><strong>Large-library search</strong><br>Filename, Chinese title, tags, and AI descriptions filter in parallel; Chinese keywords reach English libraries.</td>
    <td width="50%"><img src="./assets/agent.jpg" alt="AI Agent panel"><br><strong>AI Agent assistant</strong><br>Conversational search and recommendations by use case, mood, and duration.</td>
  </tr>
  <tr>
    <td colspan="2"><img src="./assets/waveform.jpg" alt="Waveform and audition interface"><br><strong>Dual-layer waveforms and fast auditioning</strong><br>Click inline waveforms to play; the main waveform confirms detail and in/out points.</td>
  </tr>
</table>

## What's new in v0.6.9

**New**

- FreeSound OAuth2 sign-in: save your client credentials once, authorize once, and download FreeSound originals long-term with automatic credential refresh.

**Fixed**

- Download failures no longer misreport as "invalid API key"; the app now explains that OAuth2 download authorization is required.
- FreeSound preview waveforms no longer render as empty black shapes in the dark theme.
- Batch writes during library scans no longer hold the database write lock for long periods, which previously slowed saving favorites, tags, and playback state.

**Improved**

- Redesigned FreeSound detail panel: expandable descriptions, pill-style tags, and short license names.
- A more compact main toolbar: AI is now a themed icon button, "Waveform" is renamed, and grouped dividers tighten the layout.

See the [CNB release](https://cnb.cool/garrykai/SonicLab_Flow_Updates/-/releases/tag/v0.6.9) and [GitHub Releases](https://github.com/GarryGit888/SonicLab_Flow_Updates/releases) for the full history.

## System requirements

| Platform | Minimum | Architecture |
| --- | --- | --- |
| macOS | 10.15 Catalina | Apple Silicon (arm64) / Intel (x86_64) |
| Windows | Windows 10 | x64 (Windows 11 supported) |

## Download SonicLab Flow 0.6.9

| Platform | Primary (CNB) | Mirror (GitHub) |
| --- | --- | --- |
| macOS Apple Silicon | [DMG](https://cnb.cool/garrykai/SonicLab_Flow_Updates/-/releases/download/v0.6.9/SonicLab_Flow_v0.6.9_mac_arm64_installer.dmg) | [GitHub Release](https://github.com/GarryGit888/SonicLab_Flow_Updates/releases/tag/v0.6.9) |
| macOS Intel | [DMG](https://cnb.cool/garrykai/SonicLab_Flow_Updates/-/releases/download/v0.6.9/SonicLab_Flow_v0.6.9_intel_mac_installer.dmg) | [GitHub Release](https://github.com/GarryGit888/SonicLab_Flow_Updates/releases/tag/v0.6.9) |
| Windows x64 | [Installer](https://cnb.cool/garrykai/SonicLab_Flow_Updates/-/releases/download/v0.6.9/SonicLab_Flow_v0.6.9_windows_setup.exe) | [GitHub Release](https://github.com/GarryGit888/SonicLab_Flow_Updates/releases/tag/v0.6.9) |

> **Installation notes**
>
> - macOS builds are currently unsigned, unnotarized BETA packages. On first launch, right-click the app in Finder and choose Open, or allow it under System Settings → Privacy & Security.
> - If Windows SmartScreen appears on first run, choose More info → Run anyway.
> - Download only from the official release pages above and verify the SHA-256 checksums listed there.
> - In-app updates read the CNB manifest: [update/manifest.json](https://cnb.cool/garrykai/SonicLab_Flow_Updates/-/git/raw/main/update/manifest.json).

## Quick start

1. Download and install the build that matches your operating system and processor.
2. Add your sound folders to the library — original files are not copied or moved.
3. Wait for the local index to finish, then search by filename, Chinese title, tags, or AI description.
4. Click inline waveforms to audition, confirm in/out points on the main waveform, and fill in tags or Chinese titles as needed.
5. Send selections to a DaVinci Resolve timeline in one click, or drag them into other editing software.

## Tech stack

<p><img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron"> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"> <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"> <img src="https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white" alt="FFmpeg"></p>

These badges describe the main technologies behind SonicLab Flow. **This public release repository does not contain SonicLab Flow's source code.** It holds installer release information, public documentation, website files, and product media only.

## Closed source, in beta

- SonicLab Flow is closed-source commercial software, currently in public BETA. Features and interactions may still change.
- The source code is not published and no open-source license is granted; all rights to the product and documentation are reserved.
- Feedback is welcome during BETA, but stability is not guaranteed for production use — keep backups of original media and project files.

## Privacy and data

- SonicLab Flow is built around a local library, local database, and local caches. Audio files are not uploaded.
- The app connects to external services only when you configure AI providers, authorize FreeSound, or explicitly use an online capability.
- Review the privacy policy and license of any third-party model, API, or platform before enabling it.

## Contact the developer

For issues, feature requests, or help with installation and workflows, contact me directly:

| Channel | Contact |
| --- | --- |
| WeChat | `Garry_kai888` (please mention "SonicLab Flow") |
| GitHub | [GarryGit888](https://github.com/GarryGit888) |
| Bilibili | [space.bilibili.com/11074718](https://space.bilibili.com/11074718) |
| Xiaohongshu | [Garry's profile](https://www.xiaohongshu.com/user/profile/600255b20000000001004b60) |
| Issues | [GitHub Issues](https://github.com/GarryGit888/SonicLab_Flow_Updates/issues) |
| CNB | [cnb.cool/garrykai](https://cnb.cool/garrykai) |

When reporting an issue, include the SonicLab Flow version, operating system and processor, reproduction steps, and relevant screenshots or log excerpts.

---

<p align="center">Copyright 2024-2026 SonicLab Flow. All rights reserved.</p>
