# Hikari Collection

Open-source Android engineering organization developing high-performance reading applications, document visualization pipelines, and mobile graphics components.
Engineered for modularity, memory efficiency, native Material 3 design, and privacy-first local architecture.

---

## Architectural Focus

- **Display & Decoders**: Subsampling tile decoders for multi-megapixel graphics, smooth pan-and-zoom touch dispatch, bidirectional reading layouts, and continuous vertical scroll virtualization.
- **Android Presentation**: Pure Jetpack Compose UI, Material 3 Expressive design tokens, dynamic Monet palette extraction (Android 12+), and full edge-to-edge window inset management.
- **Data & Storage Abstraction**: High-throughput file system abstractions for Android Storage Access Framework (SAF), CBZ/EPUB archive decoders, and deterministic `.hkbackup` migration schemas.
- **System Integrity**: Zero analytics, zero background telemetry, offline-first local persistence, and clean multi-module Gradle domain separation.

---

## Core Repositories

- **[hikari](https://github.com/HikariCollection/hikari)** — Flagship open-source manga reader for Android built with Kotlin and Jetpack Compose. Combines subsampling tile decoders, dynamic Monet color extraction, modular multi-project domain architecture, and zero-telemetry local storage.
- **[subsampling-scale-image-view](https://github.com/HikariCollection/subsampling-scale-image-view)** — Memory-bounded view component displaying high-resolution imagery through dynamic tile decoders without loading full bitmaps into heap memory.
- **[DirectionalViewPager](https://github.com/HikariCollection/DirectionalViewPager)** — Bidirectional swipe paging component facilitating horizontal and vertical document navigation.
- **[unifile](https://github.com/HikariCollection/unifile)** — High-performance file abstraction layer optimized for Android Storage Access Framework documents and local files.
