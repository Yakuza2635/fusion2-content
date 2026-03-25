# Fusion Content

[![GitHub](https://img.shields.io/badge/GitHub-Yakuza2635-181717?style=flat&logo=github)](https://github.com/Yakuza2635)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Fusion](https://img.shields.io/badge/For-Fusion_App-orange)](https://apps.apple.com/app/fusion-media-library-manager/id6741428023)

Curated folder posters, resource filters, widget configs, and addon settings for the [Fusion](https://apps.apple.com/app/fusion-media-library-manager/id6741428023) media library manager.

---

## Quick Start

### Folders

**Settings → Folders → Import Folders from URL**

| Category | Import URL |
|----------|------------|
| Animation Studios | `https://raw.githubusercontent.com/Yakuza2635/fusion2-content/main/folders/posters/animation/posters-animation.json` |
| Collections | `https://raw.githubusercontent.com/Yakuza2635/fusion2-content/main/folders/posters/collections/posters-collections.json` |
| Genres | `https://raw.githubusercontent.com/Yakuza2635/fusion2-content/main/folders/posters/genres/posters-genres.json` |
| Lists | `https://raw.githubusercontent.com/Yakuza2635/fusion2-content/main/folders/posters/lists/posters-lists.json` |
| Releases | `https://raw.githubusercontent.com/Yakuza2635/fusion2-content/main/folders/posters/releases/posters-releases.json` |
| Streaming Services | `https://raw.githubusercontent.com/Yakuza2635/fusion2-content/main/folders/posters/streaming/posters-streaming.json` |
| Studios | `https://raw.githubusercontent.com/Yakuza2635/fusion2-content/main/folders/posters/studios/posters-studios.json` |
| Landscapes (Streaming) | `https://raw.githubusercontent.com/Yakuza2635/fusion2-content/main/folders/landscapes/streaming/landscapes-streaming.json` |
| Squares (Streaming) | `https://raw.githubusercontent.com/Yakuza2635/fusion2-content/main/folders/squares/streaming/squares-streaming.json` |

### Resource Filters

**Settings → Resource Filters → Import from URL**

| Category | Import URL |
|----------|------------|
| All Filters | `https://raw.githubusercontent.com/Yakuza2635/fusion2-content/main/resource-filters/filters/filters.json` |

### Widgets

**Settings → Widgets → Import**

| Config | Import URL |
|--------|------------|
| Fusion Widgets | `https://raw.githubusercontent.com/Yakuza2635/fusion2-content/main/widgets/fusion-widgets-v0.1.json` |

---

## What's Included

### Folders

| Category | Count | Description |
|----------|-------|-------------|
| Animation Studios | 8 | DreamWorks, Pixar, Studio Ghibli, Disney Animation, and more |
| Collections | 37 | Popular franchises: MCU, DC, Star Wars, Harry Potter, LOTR, and more |
| Genres | 24 | Action, Comedy, Drama, Horror, Sci-Fi, Anime, KDrama, and more |
| Lists | 2 | Top Rated Movies, Popular Movies |
| Releases | 4 | Latest 4K, Full HD, 4K Remux, Dolby Vision releases |
| Streaming Services | 25+ | Netflix, Disney+, Prime Video, HBO Max, and more |
| Studios | 12 | Warner Bros, Universal, Paramount, Marvel Studios, and more |

### Resource Filters (65 filters)

| Group | Count | Items |
|-------|-------|-------|
| Media Source | 10 | Remux T1-T3, Bluray T1-T3, Web T1-T3, Web Scene |
| Resolution | 3 | 4K/2160p, 1080p, 720p |
| Dynamic Range | 5 | Dolby Vision, HDR10+, HDR10, HDR, SDR |
| Audio | 8 | Dolby Atmos, TrueHD, DTS-X, DTS-HD MA, DTS-HD, DD+, DTS, DD |
| Audio Channels | 3 | 7.1, 6.1, 5.1 |
| Languages | 36 | English, Spanish, French, German, Japanese, Portuguese, and more |

### Configs

| Config | Description |
|--------|-------------|
| Fusion Widgets | Widget export — Top 10 rows, Discover, Streaming Services, Genres, Decades |
| AIOMetadata | 577 catalogs across Streaming, Genres, Directors, Actors, Decades, Collections |
| AIOStreams | Stream filtering with regex patterns for codec, resolution, audio |

---

## Repository Structure

```
fusion2-content/
├── folders/
│   ├── posters/          # Poster-format images per category
│   │   ├── animation/
│   │   ├── collections/
│   │   ├── genres/
│   │   ├── lists/
│   │   ├── releases/
│   │   ├── streaming/
│   │   └── studios/
│   ├── landscapes/       # Landscape-format images
│   │   ├── awards/
│   │   ├── decades/
│   │   ├── discover/
│   │   └── streaming/
│   └── squares/          # Square-format images
│       └── streaming/
├── resource-filters/
│   └── filters/          # Filter icons and JSON config
├── widgets/              # Fusion widget export configs
├── addons/               # AIOMetadata & AIOStreams configs
│   ├── aiometadata/
│   └── aiostreams/
├── assets/               # Streaming logos reference
├── screenshots/
├── CONTRIBUTING.md
├── SECURITY.md
├── LICENSE
└── README.md
```

---

## UME Ecosystem

This repo is part of the **Unified Media Experience** suite:

| Repo | Description |
|------|-------------|
| **fusion2-content** (this) | Posters, filters, widgets, and addon configs for Fusion |
| [omni-content](https://github.com/Yakuza2635/omni-content) | Regex tags, catalog logos, snapshots, and configs for Omni |
| [ume-config-vault](https://github.com/Yakuza2635/ume-config-vault) | Centralized config vault for all UME apps |
| [aiostreams](https://github.com/Yakuza2635/aiostreams) | Custom formatters for AIOStreams/Stremio |
| [fusion-content](https://github.com/Yakuza2635/fusion-content) | Archive of previous Fusion content version |

---

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## Credits

- [iFusion Gallery](https://ifusion.netlify.app/) — Filter posters and original configurations
- [Vidhin05/Releases-Regex](https://github.com/Vidhin05/Releases-Regex) — Anime release group quality tier regex patterns
- [Fusion App](https://discord.gg/wrMgang5) — The media library manager

## License

This project is licensed under the [MIT License](LICENSE).
