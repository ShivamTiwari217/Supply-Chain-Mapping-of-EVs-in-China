Supply Chain Mapping of EVs in China: Interactive Dashboard

📖 Overview

This repository contains the interactive frontend visualization tool developed for the thesis "Supply Chain Mapping of Electric Vehicles (EVs) in China." The application serves as a digital companion to the research, providing a visual exploration of the EV lifecycle—from upstream raw material extraction to downstream end-of-life recycling. It aims to quantify and visualize the dominance of key players (e.g., CATL, BYD) and the environmental impact of the supply chain based on varying energy grid intensities.

✨ Key Features

Lifecycle Navigation: Interactive flow allowing users to toggle between Upstream (Mining/Refining), Midstream (Battery Mfg), Downstream (Use Phase), and End-of-Life (Recycling).

Dynamic Data Visualizations: Integrated charts (Bar, Doughnut, Line) visualizing:

Global processing capacity vs. mining reserves.

Market share of major battery manufacturers.

EV sales penetration rates.

Emissions Calculator: A "Grid Mix" simulator that allows users to adjust the percentage of coal power in the electricity grid to see real-time changes in total lifecycle CO2 emissions compared to Internal Combustion Engine (ICE) vehicles.

Methodology Section: A dedicated view explaining the Life Cycle Assessment (LCA) approach and GREET model adaptations used in the research.

🛠️ Tech Stack

This project is built as a lightweight, serverless Single Page Application (SPA).

Core: HTML5, Vanilla JavaScript (ES6+)

Styling: Tailwind CSS (via CDN)

Visualization: Chart.js (via CDN)

📊 Data Sources & Methodology

The data visualized in this dashboard is aggregated from the following sources (as detailed in the full thesis):

Market Data: CRU Group, S&P Global Platts, China Association of Automobile Manufacturers (CAAM).

Emissions Factors: Adapted from the GREET 2024 Model, modified for China's regional grid intensity (North vs. South China Grid).

Corporate Data: Public financial reports from CATL, BYD, and Ganfeng Lithium.

📂 Project Structure

/
├── README.md               # Project documentation
└── index.html              # The complete SPA code (HTML/CSS/JS)


Icons: Unicode & CSS shapes (No external icon libraries or SVGs used)

