# Advanced Dork Search (Local)

**Advanced Dork Search (Local)** is a single-machine tool to **build advanced search queries (Google dorks / open-directory queries)** for educational, research, and authorized security testing.  
It *only generates* search queries and opens them in your browser — it does **not** scrape or automate scanning. Use responsibly.

This repository is released under the **MIT License**.

---

## Table of contents
- [Features](#features)  
- [Quick demo / screenshot](#quick-demo--screenshot)  
- [Requirements](#requirements)  
- [Install & run (Windows / XAMPP)](#install--run-windows--xampp)  
- [Files in this repo](#files-in-this-repo)  
- [Activation flow (one-time local activation)](#activation-flow-one-time-local-activation)  
- [Usage](#usage)  
- [Configuration](#configuration)  
- [Custom Searx / Engine](#custom-searx--engine)  
- [Security & Responsible Use](#security--responsible-use)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact / Reporting](#contact--reporting)

---

## Features
- Clean, dark, Ewasion-inspired UI optimized for building dork queries.  
- Filetype quick-tiles: TV/Movies, Books, Music, Software/ISO/Games, Images, Other.  
- Engine selector (Google, Startpage, Searx, FilePursuit).  
- Site filter, custom dork input, copy dork, copy URL, open search in new tab.  
- One-time **activation** tied to the machine fingerprint. Activation data stored locally.  
- Local-only storage for presets (in browser `localStorage`) — no external servers.  
- MIT-licensed for permissive reuse.

---

## Quick demo / screenshot
<img width="1354" height="892" alt="image" src="https://github.com/user-attachments/assets/2b7d7457-2b7d-42a8-baa9-f8b9dc7496a0" />


---

## Requirements
- Windows OS 
- Modern web browser (Chrome, Edge, Firefox).

---

## Steps to run this tool 
1. Clone or download this repository to your windows machine  
   ```bash
   git clone https://github.com/thelegendavanish/advanced-dork-search.git advsearch
2. Extract the zip to the root of C drive `root` , looks like e.g. `C:\advanceddorksearch`.  
