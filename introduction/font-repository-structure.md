---
description: How to organise files for both the design and the engineering work.
---

# Font Repository Structure

This repository structure is used for every font family in the catalog. Organising work files consistently helps with streamlining the process.

{% embed url="https://github.com/MarmiteDefontes/repository-structure/tree/main" %}
Repository template on GitHub
{% endembed %}

**The structure:**

<pre><code><strong>.
</strong><strong>documentation
</strong>├── assets
├── reference-library
├── research
└── specimen
fonts
├── otf
├── ttf
├── variable
└── webfonts
sources
├── archives
└── character-sets
README.md
</code></pre>

**Structure sample in a nutshell:**

```
Winslow                          ‹— Family name (root folder)
    ├── documentation            ‹— All things related to design and communication
    │   ├── assets               ‹— Ready to use assets for communication
    │   ├── reference-library    ‹— Inspiration sources
    │   ├── research             ‹— Test files that are not source files
    │   └── specimen             ‹— Specimen source files and exports
    ├── fonts                    ‹— Exports/instances (aka the software files) 
    │   ├── otf                  ‹— OpenType files
    │   ├── ttf                  ‹— TrueType files
    │   ├── variable             ‹— Variable font files
    │   └── webfonts             ‹— woff2 files
    ├── sources                  ‹— Production files for the family
    │   ├── archives             ‹— Obsolete production files
    │   └── character-sets       ‹— Glyphs custom filters files
    └── README.md                ‹— Font ID and information details markdown file
```

### Folders and sub-folders content

#### <mark style="background-color:blue;">documentation</mark>

All things related to design and communication.

* **assets**: ready to use media files (image, videos, etc.) used to promote the font family
* **reference-library**: all elements that inspire and inform the design and technical development of the family. For instance: images, articles, research papers, sample font files from other designers, hi-res scans.
* **research**:  design files for the family. For instance: sketches, Illustrator files, prototype files (that are not sources).
* **specimen**:  the production files for the specimen document. For instance: Illustrator or InDesign files and the related PDF exports (for website use).

<mark style="background-color:blue;">fonts</mark>

The font files that are the lastest version and use by customers.

* **otf**: OpenType files / .otf
* **ttf**: TrueType files / .ttf
* **variable**: variable font files / .ttf
* **webfonts**: for the web / .woff2

<mark style="background-color:blue;">sources</mark>

The production files.

* **archives**: obsolete files (or versioning fallback cause we all fear losing&#x20;
* **character-sets**: local copy of the custom filters for Glyphs from Christoph Koeberlin's [Latin Character Sets](https://github.com/koeberlin/Latin-Character-Sets)
* **Name-of-the-Font.glyphs**
* **other production files**: scripts, ufo, design space files, etc.

### Read me file (README.md)

This file contains all the key information about the font family project.

Content:

* **Name-of-the-Font**
* **Sample image**
* **About this font**: short description
* **Moodboard**: inspiration overview
* **Research**: notes about design drafts and concepts
* &#x20;**Design Principles**: main intentions for the family
* **Specimen concept**: idea behind the promotion material
* **Open questions**: what might not make it in the release version, but needs to be captured
* **Font specifications**
  * **Masters** included
  * **Axis** in the font family
  * **Production notes**
  * **Character set(s)**
  * **Build** instructions
* **Changelog**
* **Acknowledgements and credits**
  * Authors
  * Contributors
* **License**
* **About Marmite Defontes**
* **Repository Layout** credits

{% hint style="info" %}
**Good to know:** This structure is inspired by my own practice, my learning during the [Practica Program](https://practicaprogram.com/) and the [Google Fonts repo organisation principles](https://googlefonts.github.io/gf-guide/googlefonts.html#repository-structure) and [Google Fonts project template](https://github.com/googlefonts/googlefonts-project-template).
{% endhint %}
