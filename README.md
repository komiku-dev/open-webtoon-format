<div align="center">
  <img src="/assets/wordmark.png" alt="Komiku Wordmark" width="600"/>
</div>

-----

> [\!NOTE]
> **This is an initiative by Komiku** to create a modern, dynamic, and accessible **open standard** for webtoons.

-----

### Table of Contents

  - [📜 About the Project](https://www.google.com/search?q=%23-about-the-project)
      - [The Vision](https://www.google.com/search?q=%23the-vision)
      - [The Problem](https://www.google.com/search?q=%23the-problem)
      - [Our Motivation](https://www.google.com/search?q=%23our-motivation)
  - [📦 The Format Explained](https://www.google.com/search?q=%23-the-format-explained)
      - [The Book & Chapter System](https://www.google.com/search?q=%23the-book--chapter-system)
      - [Key Benefits](https://www.google.com/search?q=%23key-benefits)
  - [🛠️ Specification](https://www.google.com/search?q=%23%EF%B8%8F-specification)
  - [❤️ Contributing](https://www.google.com/search?q=%23%EF%B8%8F-contributing)

-----

## 📜 About the Project

### The Vision

The **Webtoon Standard** redefines the digital comic not as a static strip of images, but as a rich, layered, and dynamic document. We envision a future where webtoons are interactive, effortlessly translatable, and fully accessible to all. By creating a clear separation between artwork, paneling, and text, this standard empowers creators, translators, and platforms to deliver experiences that are truly ready for the future of the web.

### The Problem

Today, the webtoon industry is built on a simple but inflexible foundation: a sequence of flattened image files. This creates a rigid ecosystem that holds back creators and the industry as a whole.

  * **Massive File Sizes:** A single chapter is often a very long, high-resolution image, leading to slow load times and high data usage for readers.
  * **Difficult Edits:** Correcting a simple typo in a speech bubble requires an artist to go back to their source files, edit the text, and re-export the entire image, a slow and cumbersome process.
  * **Inaccessible by Design:** Because all text is flattened into the artwork, it is completely invisible to screen readers, making webtoons inaccessible to visually impaired readers.
  * **The "Translation Wall":** Translation is incredibly expensive and slow. It requires skilled artists to manually erase the original text, redraw the artwork behind it, and typeset the new language into every single speech bubble.

### Our Motivation

The Webtoon Standard isn't just a theoretical exercise; it's our answer to the real-world frustrations we faced building our own platform. We repeatedly confronted the inefficiencies of the static-image workflow and realized that the industry's foundation was preventing innovation. Instead of simply building on top of a flawed system, we decided to tackle the root of the problem and create an open, modern, and efficient standard that benefits everyone in the webtoon community.

-----

## 📦 The Format Explained

### The Book & Chapter System

The standard uses a professional two-format system that separates the organization of the entire series from the content of individual chapters.

  * **The Book File: `.wtb`**
    The master file for an entire webtoon series or season. This is a container that organizes all chapters, manages their reading order, and holds series-level metadata like the main title and cover art.

  * **The Chapter File: `.wtc`**
    The file for a single chapter. This is a self-contained package that holds the layered artwork, panel flow information, dialogue text, sound effects, and other assets needed to render a dynamic and interactive experience.

### Key Benefits

#### For Authors & Translators

This format revolutionizes the creation and localization workflow. Authors can correct typos in seconds by editing a simple text field. The translation process is radically simplified—instead of manually re-drawing hundreds of images, a translator works with a single text file, cutting costs and delivery times immensely.

#### For Platforms & Readers

For the first time, webtoons can become truly accessible. Because text is separate from the artwork, it can be read aloud by screen readers, resized for comfort, or even translated on-the-fly by machine translation services. This new foundation also enables rich interactive elements (like animated panels or sound effects) and allows for smarter data loading, leading to faster, smoother reading experiences.

-----

## 🛠️ Specification

> [\!WARNING]
> The full v1.0 specification for the `.wtc` and `.wtb` formats is currently under active development. Community feedback during this phase is highly encouraged and deeply valued.

-----

## ❤️ Contributing

This is an open initiative, and we believe the best standards are built by a community. We welcome contributions of all kinds, from technical feedback and specification proposals to documentation improvements and tool development.

If you want to help shape the future of digital storytelling, please feel free to open an issue to share your thoughts or reach out to us directly at **oss@komiku.moe**.
