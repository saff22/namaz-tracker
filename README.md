# Namaz Tracker

A simple React web app to track daily Namaz (prayers).

## Features

- Track your daily prayers: Fajr, Dhuhr, Asr, Maghrib, Isha
- Data is saved locally in your browser
- Clean, mobile-friendly interface

## Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```
2. **Run the app locally:**
   ```bash
   npm start
   ```
3. **Build for production:**
   ```bash
   npm run build
   ```

## Deploy to GitHub Pages

1. Edit `package.json` and set the `"homepage"` field to:
   ```
   "homepage": "https://saff22.github.io/namaz-tracker"
   ```
2. Add these scripts to your `package.json`:
   ```json
   "predeploy": "npm run build",
   "deploy": "gh-pages -d build"
   ```
3. Install the gh-pages package:
   ```bash
   npm install --save-dev gh-pages
   ```
4. Deploy:
   ```bash
   npm run deploy
   ```

Your app will be available at [https://saff22.github.io/namaz-tracker](https://saff22.github.io/namaz-tracker).

---

## License

MIT
