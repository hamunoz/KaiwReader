<div align="center">
<img src="https://raw.githubusercontent.com/hamunoz/KaiwReader/refs/heads/main/logo_transparente_borde.png" width="400px">

# KaiwReader - BETA



**A modern Android novel reader with multi-source support, TTS, and offline reading**

[![Android](https://img.shields.io/badge/Platform-Android-green.svg)](https://www.android.com/)
[![Min SDK](https://img.shields.io/badge/Min%20SDK-26-blue.svg)](https://developer.android.com/about/versions/oreo)
[![License](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](LICENSE)

· [Features](#features) ·

</div>

---


## 📖 About

**KaiwReader** is a free, open-source Android novel reader **built around translation**: read web novels from multiple sources in your own language, in real time, without losing your place.
Right behind it comes an **immersive TTS audiobook mode**; everything else — offline reading, dynamic library, stats, recommendations — is a plus on top of that core.

Born from [Novery](https://github.com/1Finn2me/Novery) by 1Finn2me — after a long road through NovelDokusha and QuickNovel — and modified until it became its own thing. Inspired by [Tachiyomi](https://github.com/tachiyomiorg/tachiyomi) and [QuickNovel](https://github.com/LagradOst/QuickNovel), built with **Jetpack Compose** and **Material 3**.

---

<div id="features"></div>

## ✨ Features

### 🌍 Real-time Translator
- **Instant Translation**: Toggle real-time translation on/off without losing your place  
- **Multi-Language Support**: Access content in your preferred language using advanced translation engines  
- **Layout Stability**: Specialized engine that prevents scroll jumps and position loss during translation  
- **On-Device & Online Engines**: ML Kit offline models or Google online translation, with one-touch model management  
- **Persistent Cache**: SQL translation cache with a 5-chapter smart buffer for zero-latency re-reading  
- **TTS Continuity**: Text-to-Speech keeps reading the translated text, even in the background  
- **Progress Tracking**: Real-time visual feedback on translation status for each paragraph  

### 🎧 Immersive TTS Audiobook
- **Audiobook Mode**: Full-screen Material 3 player — cover art, title, author and giant controls — turns any novel into an audiobook  
- **Foreground Playback**: Dedicated media-playback service keeps reading with the screen off or the app in the background, with notification controls  
- **Listening Controls**: Scrubber with elapsed/remaining time, `-15s` / `+30s` jumps, previous/next chapter, speed (`1x`–`2x`) and sleep timer  
- **Translated Audio**: Continues into the next chapters using the translated text  
- **Smart Focus**: Returns the reader to the last spoken sentence when you leave audiobook mode  

### 📚 Multi-Source Browse & Search
- **Multiple novel sources**: Support for a variety of web novel providers
- Progressive streaming search with fuzzy matching and history  
- Enable/disable individual sources  

### 📖 Reader
- Continuous scroll or Chaptered view  
- Customizable fonts, sizing, spacing, alignment, and colors  
- **Comfortable Mode (Bookshelf)**: Optimized high-density grid for a true "book wall" experience
- **Tablet Optimized**: Pixel-perfect layout adjustments for large screens
- Fullscreen mode with auto-hiding controls and volume key navigation  
- Bookmarks  
- Stable position tracking across sessions  

### 💾 Offline & Performance
- **Predictive Reader**: Background preloading of adjacent chapters for instant, "zero-wipe" transitions  
- **Persistent Cache**: Robust local caching for seamless offline reading of recently accessed chapters  
- **Optimized Download Queue**: Multi-priority background downloading for entire series  

### 📚 Dynamic Library (Full CRUD)
- **Custom Shelves**: Move beyond static status; create, rename, delete, merge, and reorder your own categories  
- **Bulk Operations**: Multi-select novels to move, delete, or mark status in seconds  
- **Detection**: Real-time new chapter detection with intelligent badge indicators  

### 🤖 Smart Recommendations
- **Provider Rotation (2+3)**: Dynamic matching engine that balances 2 user favorites with 3 random active sources for fresh discovery  
- **Learning Engine**: Learns from your reading patterns, tags 
- **Blocklist**: Advanced filters to hide unwanted tags or low-quality sources  

### 🎨 Theming & UI
- Material You dynamic colors (Android 12+)  
- Light, Dark, and AMOLED black modes  
- **Edge-to-Edge**: Full system bar integration with dynamic color matching
- 7 preset themes + full custom color picker  
- Independent reader color scheme  

### 📊 Advanced Stats & Gamification
- **Gamified Progress**: Reader levels (Novice to Legendary) and 11 unique unlockable achievements  
- **Deep Analytics**: Weekly activity charts, reading time breakdown, and daily streaks  
- **History Timeline**: Grouped by date with chapter-level completion progress  

---



## ⚠️ Disclaimer
KaiwReader does not host, store, or distribute any content. The app functions as a search
engine and aggregator — it crawls and displays content from third-party websites that
are publicly accessible through any standard web browser. KaiwReader has no affiliation
with, and no control over, the content provided by these sources.

Any legal concerns regarding content should be directed to the respective website
operators and content hosts. In cases of copyright infringement, please contact the
responsible parties or file hosts directly.

This application is intended for personal and educational use only. Users are solely
responsible for ensuring their use of the app complies with all applicable local,
national, and international laws. Use KaiwReader at your own risk.

By using this application, you acknowledge that the developers of KaiwReader bear no
responsibility for any content accessed through third-party sources, nor for any
consequences arising from the use of this app.
---

<div align="center">

⭐ **Star the repo if you find KaiwReader useful!**  

[Report Bug](../../issues) · [Request Feature](../../issues)

</div>
