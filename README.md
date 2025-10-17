# SimplStream 🚀

[![Stars](https://img.shields.io/github/stars/JustANormalChurro/SimplStream?style=social)](https://github.com/JustANormalChurro/SimplStream/stargazers)
[![Forks](https://img.shields.io/github/forks/JustANormalChurro/SimplStream?style=social)](https://github.com/JustANormalChurro/SimplStream/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue?logo=react)](https://reactjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue?logo=typescript)](https://www.typescriptlang.org)
[![Issues](https://img.shields.io/github/issues/JustANormalChurro/SimplStream)](https://github.com/JustANormalChurro/SimplStream/issues)

<div align="center">
  <img src="https://i.imgur.com/JiTNH8d.png" alt="SimplStream Logo" width="300"/>
  <br><br>
  <p><em>It's not just streaming, it's SimplStreaming</em></p>
</div>

## 🌟 Introduction

Welcome to **SimplStream**, the revolutionary free and open-source streaming platform designed for the modern viewer who craves endless entertainment without the hassle of subscriptions, ads, or complexity. Born from a solo developer's passion for accessible media, SimplStream aggregates a massive library of movies, TV shows, and live channels into one intuitive, browser-based app. Whether you're binge-watching the latest Netflix hit, catching a Premier League match, or discovering hidden gems with our "Surprise Me" feature, SimplStream puts you in control.

In a world dominated by fragmented streaming services – where you need a separate app for Disney, another for Hulu, and yet another for sports – SimplStream breaks the mold. It pulls together mainstream content from across the ecosystem (think *Stranger Things* from Netflix, *The Mandalorian* from Disney+, *The Boys* from Prime Video, and more) via reliable third-party embeds, all while keeping things 100% free. No paywalls, no regional blocks, just pure streaming bliss optimized for desktops, mobiles, tablets, and even 4K TVs.

Launched on October 16, 2025, as version 1.0, SimplStream is more than an app – it's a movement toward democratized entertainment. Built with love by [Andy](https://github.com/JustANormalChurro) (aka JustANormalChurro), this project invites you to star, fork, and contribute to make it even better. Dive in, and let the credits roll!

### Why SimplStream?
- **Cost-Free Forever**: Enjoy unlimited access without monthly fees. Support via optional donations keeps it running.
- **Universal Library**: Access thousands of titles aggregated from top sources – effectively combining Netflix, Disney+, Hulu, Prime, and beyond.
- **Live TV Included**: 30+ channels for real-time sports, news, kids' programming, and entertainment – no extra add-ons needed.
- **User-Centric Design**: Personalized profiles, seamless resume playback, and smart recommendations make it feel like home.
- **Privacy First**: No data collection; everything stays local in your browser.

If you're tired of subscription fatigue and ready for a smarter way to stream, SimplStream is your new best friend. Let's get streaming!

## 🎯 Key Features

SimplStream packs a punch with features that rival premium services while staying refreshingly simple. Here's what sets it apart:

### Core Streaming
- **Vast On-Demand Library**: Stream movies and TV shows from embeds like VidSRC, Vidlink Pro, 111Movies, Videasy, and Vidfast. Covers ~87,000 movies and ~19,000 series with daily updates – from blockbusters to cult classics.
- **Multi-Server Integration**: Switch between sources on-the-fly for the best quality or when one goes down. Supports up to 4K resolution where available.
- **Trailer & Cast Exploration**: Watch official YouTube trailers and dive into cast modals with biographies, filmographies, and age calculators.

### Live TV Excellence
- **30+ Dedicated Channels**: Categorized for easy browsing – Kids (Cartoon Network, Disney, Nick Jr.), Sports (ESPN, NFL, NBA, WWE), News (CNN, Fox News, MSNBC), Entertainment (NBC, FX, TBS), and more via DaddyLive embeds.
- **Real-Time Access**: Never miss breaking news, live sports, or family favorites. Channel descriptions and numbers make navigation a breeze.

### Personalization & Tools
- **Profile Management**: Create unlimited profiles with avatars, PIN protection, security words, and ad preferences. Anonymous mode for quick sessions.
- **Watchlist & History**: Add items to your list, track viewing progress, and resume from exact timestamps (e.g., "Continue from 45:23").
- **Ratings System**: Rate content 1-5 stars to fuel personalized "Surprise Me" recommendations based on your history and genres.
- **Ad Control**: Minimal, non-intrusive banners and countdowns – toggle "Remove Ads" for free in settings.

### Interface & Accessibility
- **Responsive Design**: Works flawlessly on any device – from phones to 4K TVs (optimized at 3840x2160 with couch-friendly navigation).
- **Theme Support**: Light, dark, or system modes via context API for eye comfort day or night.
- **Universal Playback**: Embedded player with full-screen support, no external apps required.

### Bonus Perks
- **Import/Export Data**: Backup your profiles, watchlists, and ratings as JSON – portable across devices.
- **No Account Required**: Jump in anonymously, or level up with profiles for full features.
- **Ethical & Transparent**: Clear terms disclaim liability for embeds; focuses on UI/UX innovation.

With these features, SimplStream isn't just a player – it's your personal entertainment hub.

## 📱 Screenshots & Demo

### Home Dashboard
![Home Dashboard](https://i.imgur.com/LdGMen8.png)  
*Personalized rows for trending movies, TV, recommendations, and quick Live TV access.*

### Detail Page
![Detail View](https://i.imgur.com/moOgkU7.png)  
*Rich overviews, ratings, cast carousel, trailers, and "Play/Add to List" buttons.*

### Live TV Grid
![Live TV](https://i.imgur.com/fzFaI7A.png)  
*Categorized channels with search and favorites – flip like cable TV.*

### Profile Selector
![Profile Selector](https://i.imgur.com/0QlrtHZ.png)  
*Who's watching? screen with customizable avatars and easy profile switching.*

**Live Demo**: Try it at [simplstream.bolt.host](https://simplstream.bolt.host) (hosted via Bolt.new).

## 🚀 Quick Start

Getting SimplStream up and running is as easy as 1-2-3. It's a standard Vite + React project – no Docker or complex setups.

### Prerequisites
- Node.js (v18+)
- Yarn or npm
- A modern browser (Chrome, Firefox, Safari, Edge)

### Installation
1. **Clone the Repo**:
   ```
   git clone https://github.com/JustANormalChurro/SimplStream.git
   cd SimplStream
   ```

2. **Install Dependencies**:
   ```
   npm install
   # or
   yarn install
   ```

3. **Environment Setup** (Optional but Recommended):
   - Create a `.env` file in the root:
     ```
     VITE_TMDB_API_KEY=your_tmdb_key_here  # Get free from https://www.themoviedb.org/
     ```
   - Note: TMDB key is required for metadata/posters. Without it, fallback to placeholders.

4. **Run Locally**:
   ```
   npm run dev
   # or
   yarn dev
   ```
   - Open [http://localhost:5173](http://localhost:5173) – boom, you're streaming!

### Build for Production
```
npm run build
# Serves from /dist – deploy to Netlify, Vercel, or GitHub Pages.
```

### Deployment Options
- **Vercel**: Connect GitHub repo – auto-deploys on push.
- **Netlify**: Drag/drop the `dist` folder.
- **GitHub Pages**: Add `base: '/SimplStream/'` in `vite.config.ts` and push to `gh-pages` branch.

For Android APK builds (via Capacitor):
1. `npm i @capacitor/core @capacitor/cli`
2. `npx cap init`
3. `npm run build && npx cap add android`
4. Open in Android Studio and build APK.

## 📖 Usage Guide

### Getting Started
1. **Launch the App**: Open in your browser – no login needed for basics.
2. **Create a Profile**: Click the avatar icon > "New Profile" > Set name, color, and optional PIN.
3. **Browse Content**:
   - **Home**: Scroll trending, recommendations, and categories.
   - **Search**: Type titles for instant results.
   - **Live TV**: Switch to the TV tab for channels.
4. **Play Something**:
   - Click a poster > "Play" button.
   - Resume from history or start fresh.
   - Swap servers if quality dips.
5. **Personalize**:
   - Add to Watchlist (heart icon).
   - Rate post-watch (stars in details).
   - Hit "Surprise Me" for a random pick.

### Pro Tips
- **Ad-Free Mode**: In Profile Settings > Toggle "Remove Ads".
- **4K TV Setup**: Use a browser like Chrome on smart TV; enable full-screen.
- **Data Backup**: Settings > "Export Data" > Save JSON file.
- **Troubleshooting**: Check console for TMDB errors; clear localStorage if profiles glitch.

For full docs, see the [Wiki](https://github.com/JustANormalChurro/SimplStream/wiki).

## 🛠 Tech Stack

SimplStream is built for speed, scalability, and developer joy:

- **Frontend**: React 18, TypeScript 5, Vite (build tool), Tailwind CSS (styling).
- **State & Context**: React Context for themes/profiles; LocalStorage for persistence.
- **APIs & Data**:
  - TMDB API for metadata, posters, trailers, cast.
  - Embed providers: VidSRC, Vidlink Pro, etc., for streams.
  - DaddyLive for Live TV.
- **Libraries**:
  - Lucide React (icons).
  - React Router (navigation – planned for v1.1).
  - Custom hooks for storage, ratings, recommendations.
- **Dev Tools**: ESLint, Prettier, Vitest (testing).

No backend – everything client-side for zero server costs!

## 🤝 Contributing

Love SimplStream? Help make it legendary! We welcome all contributions, from bug fixes to wild features.

### How to Contribute
1. **Fork the Repo** & clone your fork.
2. **Create a Branch**: `git checkout -b feature/amazing-idea`.
3. **Make Changes**: Follow code style (run `npm run lint`).
4. **Test**: `npm run test` – add tests if possible.
5. **Commit & Push**: `git commit -m "Add amazing idea" && git push`.
6. **Pull Request**: Open a PR to `main` – reference issues!
7. **Discuss**: Join the conversation in Issues or Discussions.

### Guidelines
- **Code Style**: TypeScript strict mode; semantic commits.
- **Features**: Prioritize user privacy and performance.
- **Bugs**: Report with steps to reproduce + screenshots.
- **Ideas**: Post in Discussions – e.g., "Mobile PWA Support?"

Top contributors get shoutouts in releases. Current hero: Andy (100% commits so far)!

### Roadmap (v1.1+)
- PWA offline caching.
- React Router for SPA navigation.
- More embed providers.
- Internationalization (i18n).
- Voice search for TV.

See [Projects](https://github.com/JustANormalChurro/SimplStream/projects) for details.

## 📄 License

This project is licensed under the MIT License – free to use, modify, and distribute. See [LICENSE](LICENSE) for details.

**Note on Content**: SimplStream's UI/UX is MIT, but embeds are third-party – stream responsibly and respect copyrights.

## 🙌 Acknowledgments

- **TMDB**: For amazing metadata API.
- **Embed Providers**: VidSRC, DaddyLive, etc., for the streams.
- **Open-Source Heroes**: Lucide, Tailwind, Vite – powering the magic.
- **Community**: Early testers and stars – you rock!
- **Inspiration**: Netflix's polish meets Stremio's aggregation.

## 💬 Support & Contact

Questions? Bugs? Feature requests? Hit us up:

- **Email**: [admin.simplstream@protonmail.com](mailto:admin.simplstream@protonmail.com)

Donate to keep it free: [Cash App $justanormalchrurro](https://cash.app/$justanormalchrurro). Every coffee counts! ☕

---

<div align="center">
  <p><strong>Made with ❤️ by <a href="https://github.com/JustANormalChurro">Andy</a> – Stream Simple, Live Epic!</strong></p>
  <br>
  <img src="https://i.imgur.com/RURTeBy.png" alt="SimplStream Logo Light" width="300"/>
</div>

*Last Updated: October 16, 2025*
