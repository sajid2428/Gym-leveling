# Gym-leveling
Its is made by deepseek ai.
# 💪 Iron Diary Pro · 1RM‑Based Workout Tracker

**Hybrid training diary with built‑in exercise library, 3 default percentage‑based plans, AI coach (Gemini), gamification, and local‑first storage.**

![Version](https://img.shields.io/badge/version-2.0-orange)
![Platform](https://img.shields.io/badge/platform-Android%20%7C%20Web%20%7C%20PWA-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 📱 Overview

Iron Diary Pro is a **standalone web app** (works offline, can be installed as PWA or wrapped into an APK) designed for lifters who want to:

- Log workouts **set by set**
- Follow **percentage‑based training plans** (based on your actual 1RM)
- Build a **V‑taper** while improving **Squat / Bench / Deadlift**
- Earn **XP**, rank up, complete daily/weekly quests, and defeat a monthly **Boss**
- Get optional AI advice via **Google Gemini** (free API key)

All data stays on your device – **no backend, no cloud** (unless you add it).

---

## ✨ Features

### 🏋️ Core Training
- **Three built‑in 5‑day splits** (Normal / Physique / Power) – all use **% of 1RM**.
- **Auto weight estimation** from your stored Squat, Bench, Deadlift maxes.
- **Exercise library** with 100+ movements, grouped by 17 muscle groups.
- **Add custom exercises** with any number of sets (reps & weight per set).

### 📅 Detailed Diary
- Calendar view – pick any day, log exercises with **set‑by‑set details**.
- Edit or delete past entries.
- Quick log button for fast entry (3 sets of 8 reps).

### 🎮 Gamification
- **Total XP** and **Hunter Rank** (Recruit → LEGEND).
- **Muscle‑specific XP** and ranks (Untrained → Legendary).
- **Daily & Weekly quests** (e.g., “Earn 60 XP”, “5 workouts this week”).
- **Monthly Boss Challenge** – earn 2000 XP in a month to get +500 bonus XP.

### 🤖 Gemini AI Coach (optional)
- Requires a free API key from [Google AI Studio](https://aistudio.google.com/).
- Generate custom 5‑day plans, adjust existing plans, ask form/diet questions.

### 📊 Physique & Strength Tracking
- Store your **shoulder / waist** measurements → automatic **V‑taper ratio**.
- Store **Squat / Bench / Deadlift** 1RMs → track total and powerlifting rank.

### 💾 Data Persistence
- All data saved automatically in your browser’s `localStorage`.
- Works **offline** (except Gemini calls).
- No account needed – your diary stays on your device.

---

## 📸 Screenshots

| Dashboard | Diary | AI Coach | Muscles |
|-----------|-------|----------|---------|
| *Shows training plan, stats, quests* | *Calendar + set‑by‑set logs* | *Chat with Gemini* | *Muscle XP progress* |

*(Add actual screenshots if you wish)*

---

## 🚀 Getting Started

### Option 1: Use the live web app
1. Open the `index.html` file in any modern browser (Chrome, Edge, Safari).
2. No installation needed – works immediately.
3. For best experience, **install as PWA** (see below).

### Option 2: Install as PWA on Android / iOS
- **Android (Chrome)**: Tap menu → “Add to Home screen” → the app opens full‑screen.
- **iOS (Safari)**: Share → “Add to Home Screen”.
- The app will have its own icon and launch without browser UI.

### Option 3: Convert to APK (Android)
Use [PWABuilder](https://www.pwabuilder.com) or [Bubblewrap](https://github.com/GoogleChromeLabs/bubblewrap):
1. Upload the HTML folder or host the files online.
2. Generate a signed APK.
3. Install on any Android device.

---

## 🧠 Using the Training Plans

### Normal (Hybrid – Physique + Power)
- Your custom plan: Chest+Shoulders, Back width, Legs (Squat), Shoulders+Chest, Deadlift+Back thickness.
- Percentages range from **30% (lateral raises)** to **85% (deadlifts)**.

### Physique (V‑Taper focus)
- Extra shoulder and lat volume, minimal oblique work.

### Power (Strength peaking)
- Heavier loads (up to 92% of 1RM), lower reps (3–5).

> **All plans display percentages only.** When you click “Log This Day”, the app calculates estimated weight in kg based on your current 1RMs.

---

## 🔧 Setting Up Gemini AI (Optional)

1. Get a free API key from [Google AI Studio](https://aistudio.google.com/).
2. In the app, go to **AI Coach** → click **“Set Gemini Key”**.
3. Paste your key.
4. Now you can:
   - Click **“Gemini Plan”** on the dashboard to generate a new 5‑day split.
   - Use **“Adjust Plan (AI)”** to modify the current plan.
   - Chat with the coach for advice.

> ⚠️ The AI is **not required** – the app works perfectly without it.

---

## 📂 Project Structure

