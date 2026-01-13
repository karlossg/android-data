# Android Data Network

A static website for Genesys TTRPG campaign materials set in the Android universe.

## Overview

This repository contains static HTML/CSS pages designed to serve as in-game props and reference materials for a tabletop RPG campaign. The design mimics sci-fi data terminals and medical databases fitting the Android/Cyberpunk aesthetic.

## Pages

- **index.html** - Main landing page / navigation hub
- **medical-records.html** - Medical database with health profiles for 5 player characters

## Player Characters

1. **Tauron McClicce** - Active operative with cybernetic enhancements
2. **Bernal Diaz de Castillo** - Veteran under medical observation
3. **Filas Kowalsky** - Gene-modified netrunner
4. **Vince Smith** - Psychoparticle carrier in cryo-stasis
5. **Rex** - Emancipated bioroid

## Deploying to GitHub Pages

1. Go to your repository on GitHub
2. Navigate to **Settings** > **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose the branch (usually `main` or `master`) and folder (`/ (root)`)
5. Click **Save**
6. Your site will be available at: `https://[username].github.io/android-data/`

## Local Development

Simply open any HTML file in a web browser - no build process required.

```bash
# Using Python's built-in server (optional)
python -m http.server 8000

# Then visit http://localhost:8000
```

## Tech Stack

- Pure HTML5/CSS3
- No JavaScript dependencies
- Google Fonts (Orbitron, Roboto Mono, Share Tech Mono)
- Responsive design for mobile/tablet viewing

## License

This project is for personal tabletop gaming use. Android and related trademarks are property of Fantasy Flight Games.
