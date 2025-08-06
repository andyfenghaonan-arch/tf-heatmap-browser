# Transcription Factor Heatmap Browser - Demo Version

🧬 **A lightweight demonstration of Hi-ChIP data visualization for transcription factors**

## 🌐 Live Demo

**Access the live demo here:** https://andyfenghaonan-arch.github.io/tf-heatmap-browser/

*Deployed on GitHub Pages for easy access and demonstration.*

## Demo Overview

This is a **demo version** of the TF Heatmap Browser containing only `chr1_0.png` files from each transcription factor dataset for demonstration purposes.

### Available Data
- **KLF4**: 1 file (ENCFF761ZKW)
- **NANOG**: 2 files (ENCFF153EHS, ENCFF926YZX) 
- **OCT4**: 3 files (ENCFF003PEE, ENCFF259JPA, ENCFF906LPL)
- **Rad21**: 2 files (ENCFF056GWP, ENCFF081AYT)

**Demo Limitation**: Only chromosome 1, position 0 data is available (chr1_0.png files).

## Usage

1. Open `index.html` in a web browser
2. Select a **Transcription Factor**
3. Choose an **ENCODE ID** 
4. Select **chr1** (only available chromosome in demo)
5. Enter position **0** (only available position in demo)
6. Click **View Heatmap** to display the visualization

## Data Structure

```
data/
├── KLF4/ENCFF761ZKW/chr1/chr1_0.png
├── NANOG/ENCFF153EHS/chr1/chr1_0.png
├── NANOG/ENCFF926YZX/chr1/chr1_0.png
├── OCT4/ENCFF003PEE/chr1/chr1_0.png
├── OCT4/ENCFF259JPA/chr1/chr1_0.png
├── OCT4/ENCFF906LPL/chr1/chr1_0.png
├── Rad21/ENCFF056GWP/chr1/chr1_0.png
└── Rad21/ENCFF081AYT/chr1/chr1_0.png
```

## Technology

- **Static HTML/CSS/JavaScript** - No server required
- **PNG Heatmaps** - Each file represents a 2MB genomic window
- **ENCODE Integration** - Real transcription factor datasets
- **Responsive Design** - Works on desktop and mobile

## Full Version

The complete version contains 25,360 PNG files (9.9GB) covering all chromosomes and positions. This demo version contains only 8 files (2.9MB) for GitHub Pages compatibility.

## Deployment

This demo is optimized for GitHub Pages deployment with minimal file size and static hosting requirements.