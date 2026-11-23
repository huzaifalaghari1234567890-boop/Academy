# 🎬 Huzaifa Academy - Official Web App & Promotional Platform

A modern, high-conversion promotional web application built for the YouTube channel **[Huzaifa Academy (@HuzaifaAcademy-z6m)](https://www.youtube.com/@HuzaifaAcademy-z6m)**.

Designed with a cinematic aesthetic inspired by Netflix and Curiosity Stream, this web app showcases all 14 official documentaries, provides on-site embedded video playback that registers views directly on YouTube, live search, 3D card tilt, animated constellation canvas, accurate live view metrics, and prominent subscription prompts to grow the channel.

---

## 🌟 Channel Overview
- **Channel Name:** Huzaifa Academy
- **Handle:** `@HuzaifaAcademy-z6m`
- **Channel URL:** [https://www.youtube.com/@HuzaifaAcademy-z6m](https://www.youtube.com/@HuzaifaAcademy-z6m)
- **Direct Subscribe Link:** [Subscribe with One Click](https://www.youtube.com/@HuzaifaAcademy-z6m?sub_confirmation=1)
- **Genre:** Educational Documentaries in Urdu covering Ancient Mysteries, Space Missions, Catastrophes, Dinosaurs, and Nature.
- **Total Verified Views:** 1,221+ Views across 14 Documentaries.

---

## 🚀 Key Web App Features

### 1. 📺 In-Page Cinema Studio Player (Guaranteed YouTube Views)
- Dedicated on-page theater stage with an interactive sidebar queue of all 14 documentaries.
- Uses official YouTube IFrame Embed API with `enablejsapi=1` and origin parameters.
- **How YouTube Views Work:** Playback initiated by viewers through the official embedded player counts legitimately towards channel view count and watch hours on YouTube!
- Quick actions underneath the player: "Watch on YouTube", "Like & Comment on YouTube" (opens directly to video comment section), "Copy Link", and "Theater Lights Out" (dims all surrounding ambient lighting).

### 2. ✨ High-End Header Animations & Branding
- **Rotating Gradient Crest Logo:** Animated rotating conic-gradient ring around the official YouTube channel avatar with verified tick badge.
- **Live Announcement Marquee Ticker:** Real-time scrolling ticker at the very top displaying breaking releases, verified views, and community updates.
- **Interactive Constellation Starfield Canvas:** Particle physics canvas that connects stars with glowing filaments and moves dynamically on mouse hover.
- **Typewriter Title Cycler:** Hero headline dynamically types and deletes mystery titles (e.g., *5,000-Year Ancient Mysteries*, *The Great Pyramid Hidden Chambers*, *Apollo 11 Moon Landing Alarm*).
- **Floating Micro-Badges:** 3D floating cards celebrating top documentaries (*344 Views Great Pyramid*, *5,000-Yr Stonehenge Enigma*).

### 3. 🎯 100% Accurate View Counting & Milestone Tracker
- Exact live view counts scraped and indexed for all 14 videos.
- Channel Milestone Progress Bar:
  - **Views Goal:** 1,221 / 2,000 Views (61% Complete)
  - **Subscribers Goal:** 33 / 100 Subscribers (33% Complete)
- Real-time animated number counters upon scroll.

### 4. 🎴 3D Card Tilt with Reflective Light Sheen
- Documentary cards tilt with 3D perspective following the viewer's mouse cursor with dynamic light reflection (`--mouse-x`, `--mouse-y`).
- Key moment / highlight badge on every documentary card.

### 5. 🔊 Web Audio API Acoustic Feedback
- Zero-external-file audio synthesizer built using native browser `AudioContext`.
- Subtle, satisfying micro-tones on category pill clicks and harmonic chimes on wheel spin or subscription.
- Header toggle button allows users to mute/unmute at any time.

### 6. 🌓 Dual Theme Mode (Cinematic Dark & Premium Daylight)
- One-click toggle between **Cosmic Dark** and **Crisp Light** modes.
- Desktop navbar button and mobile drawer switch.
- Saves user preference in `localStorage`.

### 7. 🔍 Instant Search & Multi-Category Filters
- Real-time search across titles, synopses, and tags.
- Category pills: *All (14)*, *Ancient Mysteries (4)*, *Disasters & Vanishings (4)*, *Science & Nature (3)*, and *Space & Engineering (3)*.
- Multi-attribute sort: *Newest*, *Most Viewed*, *Longest Duration*, *Shortest Duration*, *Alphabetical*.

### 8. 🎲 "Mystery Roulette" Recommendation Engine
- Interactive mystery generator that randomly decodes and presents a documentary with sound effects and direct play action.

---

## 📁 File Structure

```text
huzaifa-academy-web/
├── index.html          # Semantic single-page application with theater stage & ticker
├── styles.css          # Glassmorphic, cinematic dual-theme design with 3D animations
├── app.js              # State manager, canvas particle physics, studio player, audio synth
├── videos-data.js      # Structured catalog containing accurate live views & key moments
├── Start-Server.ps1    # Zero-dependency local PowerShell web server
└── README.md           # Documentation & instructions
```

---

## ⚡ How to Run

### Method 1: Direct File Opening
Simply double-click `index.html` in Windows File Explorer or open it in Chrome, Edge, or any modern browser.

### Method 2: Local HTTP Server (Recommended)
Open PowerShell in the project directory and run:
```powershell
powershell -ExecutionPolicy Bypass -File .\Start-Server.ps1
```
This serves the application at `http://localhost:8080/` and automatically opens your browser.
