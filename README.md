<div align="center">

# ✦ Genchron Network Visualizer

### Visual Analytics for Gendered Networks in Medieval Chronicles

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-c9a84c?style=for-the-badge&logo=github)](https://samsomyajit.github.io/Genchron/)
[![Version](https://img.shields.io/badge/Version-3.2-7c5cbf?style=for-the-badge)](https://github.com/Samsomyajit/Genchron/releases/tag/ver3.2)
[![License](https://img.shields.io/badge/License-See%20LICENSE-b5a98a?style=for-the-badge)](./LICENSE)
[![Built With](https://img.shields.io/badge/Built%20With-React%20%26%20Cytoscape.js-61dafb?style=for-the-badge&logo=react)](https://reactjs.org/)

<br/>

> *An open-source tool for exploring gendered social networks in late antique and early medieval historical chronicles.*

</div>

---

## 🌐 Live Demo

**→ [https://samsomyajit.github.io/Genchron/](https://samsomyajit.github.io/Genchron/)**

---

## 📖 Abstract

Traditional methodologies in historical analysis have often marginalised the contributions of women, resulting in an incomplete understanding of social structures in historical chronicles. This research addresses this gap by developing and applying visual analytics tools to highlight gendered networks within historical chronicles, particularly from the late antique and early medieval periods.

The primary objectives of this study are to:
- Design a novel visual analytics tool that emphasises gendered interactions
- Assess the impact of design choices on data interpretation
- Evaluate the challenges and limitations inherent in using such tools for historical analysis

**Genchron: Network Visualizer** was developed using **React.js** and **Cytoscape.js**, allowing for dynamic, real-time manipulation of network visualisations and providing a platform for historians to explore gender dynamics with greater depth and flexibility.

The results demonstrated that Genchron significantly enhances the ability to analyse complex gendered networks, offering insights that challenge traditional historical narratives. The tool's design — which emphasises interactivity and user control — was shown to be particularly effective in uncovering the roles of women within these networks.

> This research contributes to the field of **Historical Social Network Analysis (HSNA)** and digital humanities by providing a novel tool that advances the methodological framework for gender analysis and paves the way for future research into the social structures of the past.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔍 **Dynamic Search** | Search and filter nodes by name or attribute |
| 🎨 **Color Coding** | Visually distinguish nodes by gender or role |
| 📐 **Multiple Layouts** | Switch between force-directed, hierarchical, and circular layouts |
| 📊 **Network Metrics** | Real-time degree, centrality, and community statistics |
| 🔗 **Edge Filtering** | Adjust edge visibility using a degree threshold slider |
| 🏘️ **Community Detection** | Identify and highlight network clusters |
| 📷 **Snapshot Export** | Download the current visualisation as an image |
| 📁 **Data Import** | Load custom datasets via JSON |

---

## 🛠️ Tech Stack

- **Frontend:** React.js (Create React App)
- **Visualisation:** Cytoscape.js
- **Styling:** Custom CSS with glassmorphism dark-academic theme
- **Deployment:** GitHub Pages (served from `main` branch `/docs`)

---

## 🚀 Getting Started

The live version is available at **[https://samsomyajit.github.io/Genchron/](https://samsomyajit.github.io/Genchron/)**.

To run locally, clone the source and install dependencies (requires Node.js ≥ 14):

```bash
git clone https://github.com/Samsomyajit/Genchron.git
cd Genchron
npm install
npm start
```

---

## 📜 Instructions

1. **Open** the live link above or run the app locally.
2. **Log in** with your credentials to access the visualiser.
3. Use the **left-hand controls panel** to adjust the layout, filter by degree, toggle labels/edges, and pick node colours.
4. **Click any node** to view its properties and connections in the right-hand panel.
5. Use the **degree filter slider** at the bottom to focus on high-degree nodes.
6. Click **Show Communities** to run community detection and colour-code clusters.
7. Use **Download Snapshot** to export the current graph as an image.

---

## 📄 License

See the [LICENSE](./LICENSE) file for details.

---

<div align="center">

*Built for the digital humanities — illuminating the hidden voices of medieval history.*

</div>
