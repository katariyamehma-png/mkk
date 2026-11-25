# Atelier Dwell — Minimalist Home Design & Global Architecture Website

A clean, minimalist, responsive static website built with **HTML, CSS, and vanilla JavaScript** to help anyone wondering how to build or design a **small or large home**.

## Folder Structure

```text
mkk/
├── index.html                  # Main page: Hero, "How to design my home?" interactive advisor, quick links, global styles preview & language inspiration demo
├── pages/
│   ├── color-combinations.html # Curated color combination ideas + live room color visualizer + one-click hex copy
│   ├── home-setup.html         # Room-by-room guide on how to set your home (diagrams, proportions & interactive checklists)
│   ├── styles.html             # 24 architectural & interior styles across countries, cultures & time periods with filters & detail modal
│   └── inspiration.html        # Multilingual inspiration demo across 24 languages + blank "Listen to Inspiration" section
├── css/
│   └── styles.css              # Shared minimalist, responsive stylesheet
├── js/
│   ├── data.js                 # Structured data for advisor plans, palettes, setup guides, global styles & 24 languages
│   ├── main.js                 # Navigation toggle, toast utility, clipboard helper & interactive home advisor
│   ├── colors.js               # Palette filtering & live SVG room visualizer
│   ├── setup.js                # Interactive room tabs, floorplan diagrams & checklists
│   ├── styles-explorer.js      # Search, region/era/size filtering & detail modal for global styles
│   └── inspiration.js          # Language selector & multilingual inspiration display
└── README.md
```

## How to Open

Open `index.html` directly in any web browser (works without a build step or local server), or serve the folder with any static server.
