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
- A local PHP-capable server (Windows examples): **XAMPP** (Apache + PHP), **IIS** with PHP, or similar.  
- PHP 7.0+ recommended.  
- Modern web browser (Chrome, Edge, Firefox).

---

## Install & run (Windows / XAMPP)
1. Install [XAMPP](https://www.apachefriends.org/) and start **Apache** (and PHP is bundled).  
2. Clone or download this repository into your XAMPP `htdocs` folder, e.g. `C:\xampp\htdocs\advsearch`.  
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git advsearch
