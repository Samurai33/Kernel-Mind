# KernelMind — Focused Sound for Developers

![KernelMind logo](kernel_mind_logo.png)

[![version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/KernelMind/KernelMind/releases) [![license](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE) [![ci](https://github.com/KernelMind/KernelMind/workflows/CI/CD%20Pipeline/badge.svg)](https://github.com/KernelMind/KernelMind/actions)

> Neuroscience-informed ambient music + interactive tooling to help developers focus, debug, and create.

Try: [Listen](#where-to-listen--download) • [Download](#installation) • [Contribute](#contributing) • [Docs](#research--evidence)

---

## TL;DR

- Music and tools designed to help developers enter and sustain flow: high-fidelity masters (48kHz/24-bit), optional binaural beats (6–40Hz differences), and IDE integrations.
- Research-first, privacy-first, open core.

---

## Table of Contents

- [Demo / Screenshots](#demo--screenshots)
- [Quick start](#quick-start)
- [Installation](#installation)
- [Examples](#examples)
- [Key features](#key-features)
- [Architecture](#architecture)
- [Roadmap](#roadmap)
- [Research & Evidence](#research--evidence)
- [Contributing](#contributing)
- [Where to listen / download](#where-to-listen--download)
- [Security & Privacy](#security--privacy)
- [License](#license)
- [Contact](#contact)
- [Contributors](#contributors)

---

## Demo / Screenshots

> (Placeholder) Add 1 GIF or screenshot showing the player or desktop app here.

![App preview](assets/demo-placeholder.png)

---

## Quick start

1. Try the web player: https://kernelmind.audio/player
2. Install the desktop app or the VS Code extension for in-editor sessions.
3. Use headphones to enable binaural options.

To run the web player locally (development):

```bash
git clone https://github.com/KernelMind/KernelMind.git
cd "Kernel Mind"
npm install
npm run dev
```

Requirements for development: Node 16+ (recommended), npm 8+.

---

## Installation

Desktop (users):

- Windows (Chocolatey):

```powershell
choco install kernelmind
```

- macOS (Homebrew):

```bash
brew install --cask kernelmind
```

- Linux (Snap):

```bash
sudo snap install kernelmind
```

VS Code extension (developer / user):

```bash
code --install-extension kernelmind.vscode-extension
```

---

## Examples

Web embed (HTML):

```html
<iframe src="https://kernelmind.audio/player/embed" width="800" height="200" title="KernelMind player"></iframe>
```

JavaScript SDK (browser):

```js
import { KernelMindPlayer } from '@kernelmind/player'
const player = new KernelMindPlayer({ track: 'overclock', binauralFreq: 18 })
player.start()
```

VS Code: open the Command Palette and run "KernelMind: Start Focus Session" (or install via the command above).

---

## Key features

- High-fidelity masters: 48kHz / 24-bit, target -16 LUFS.
- Binaural options with conservative carrier defaults (~220 Hz) and differences in the 6–40 Hz range.
- Adaptive BPM: optional feature that nudges tempo to match typing rhythm.
- IDE-aware: smart activation, focus sessions, notification muting, session export.
- Exportable stems for remixing and reproducible research.

---

## Architecture

- Audio: mastered WAV/FLAC assets, binaural engine (oscillators + HRTF) served by a Web Audio player.
- Web app: React + Web Audio API.
- Desktop: Electron wrapper for low-latency audio and local integrations.
- Integrations: VS Code & JetBrains plugins communicating via local RPC.
- Research: opt-in telemetry pipeline and reproducible notebooks in `/research`.

---

## Roadmap

- 2025 Q1: Beta desktop app + EEG pilot study (internal)
- 2025 Q2: Public research results + full app release
- 2025 Q3: Expanded IDE integrations and personalization
- Ongoing: Open dataset releases and community studies

See [IMPLEMENTATION_ROADMAP.md](IMPLEMENTATION_ROADMAP.md) for full details.

---

## Research & Evidence

We maintain a conservative, research-first stance. Effects vary across individuals; full literature, protocols, and validation plans are in [SCIENTIFIC_RESEARCH.md](SCIENTIFIC_RESEARCH.md). If you're conducting experiments, please follow reproducible protocols and consider pre-registration.

---

## Contributing

We welcome developers, music producers, and researchers. Start with:

- [CONTRIBUTING.md](CONTRIBUTING.md)
- Join the community on Discord (link in repo header)
- Look for issues tagged `good first issue`

---

## Where to listen / download

- Streaming: Spotify, Apple Music, YouTube Music, SoundCloud
- High-quality downloads (FLAC / MP3): https://kernelmind.audio/download
- Stems & producer resources: https://kernelmind.audio/download/stems

---

## Security & Privacy

- Privacy-first: telemetry is opt-in and anonymized.
- Report security issues: [security@kernelmind.audio](mailto:security@kernelmind.audio)
- See [SECURITY.md](SECURITY.md) for the policy and disclosure process.

---

## License

MIT — see [LICENSE](LICENSE).

---

## Contact

- General: hello@kernelmind.audio
- Security: security@kernelmind.audio
- Research: research@kernelmind.audio

---

## Contributors

Thanks to everyone who contributed — see the contributors graph on GitHub.

---

Made with ❤️ for the global developer community.