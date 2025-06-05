# 🌌 DECISION LOOP - Cyberpunk Arcade Nexus 🌃

> **Jack into the Grid. One Second. One Choice. Infinite Loops.**  
> Welcome to **DECISION LOOP**, a neon-drenched, reflex-sharpening arcade game forged in the underbelly of Neon City, 2087. This HTML5 neuro-thriller hacks your brain with rapid-fire decisions, retro CRT visuals, and chiptune beats that pulse like a rogue AI. Built for mobile renegades and desktop jackers, it’s your ticket to defy the Grid—or crash trying.

---

## 🔌 Boot Sequence: Welcome to the Grid

In a dystopian future, the Grid—a sentient network of code—rules Neon City. You’re a *neurojacker*, a rogue hacker plugged into **DECISION LOOP**, an illegal arcade node designed to test your neural limits. Your mission: outsmart a relentless stream of binary prompts (**TAP**, **SWIPE**, **HOLD**) in 1-second cycles, rack up **mind coins**, and climb the leaderboard before your link burns out.

This isn’t just a game—it’s a cyberpunk rebellion. With glowing neon greens (#00FF00), magentas (#FF00FF), and cyans (#00FFFF), **DECISION LOOP** fuses 1980s arcade vibes with 22nd-century edge. Optimized for low-end rigs (3GB RAM, iOS 14+, Android 10+), it’s built to keep you wired for hours.

```
   ╔════════════════════════════════════╗
   ║  DECISION LOOP - NEON CITY 2087    ║
   ║  >> TAP TO SURVIVE THE GRID <<     ║
   ╚════════════════════════════════════╝
```

![Game Screenshot](https://raw.githubusercontent.com/kasduck/Decision_Loop_Game/refs/heads/main/SS1.png)  

---

## 💾 Core Protocols: How to Play

**DECISION LOOP** is a high-stakes arcade gauntlet where every second tests your reflexes. The Grid throws prompts at you, and you’ve got **1 second** to respond—or face a neural crash. Chain correct inputs to enter **Combo Mode**, survive **Glitch Events**, and master **Mind Challenges** to prove you’re the ultimate jacker.

### 📊 Game Mechanics

| Mechanic | Description | Reward/Penalty |
|---------|-------------|----------------|
| **Prompts** | React to **TAP**, **DON’T TAP**, **↑/↓/←/→**, **HOLD** (0.5s), or **DOUBLE TAP** (0.3s). | Correct: +8% Survival, +Score<br>Incorrect: -25% Survival<br>Missed: -35% Survival |
| **Survival Bar** | Your neural link’s health (50–100%). | Depletes to 0% = Game Over |
| **Risk Bar** | Bold choices (e.g., TAP with high risk) boost it (0–100%). | Higher Risk = Bigger Score Multiplier |
| **Multiplier** | Chain 3 correct inputs to grow (1x–8x, +0.3x). | Resets to 1x on miss, drops -0.5x on error |
| **Combo Mode** | 8 consecutive correct inputs trigger a 0.8s speed frenzy (6s duration). | +Score, Visual/Audio Surge |
| **Glitch Mode** | Rare (1% after 50 correct inputs), 3s screen distortion. | Survive: 500 Mind Coins, “Glitch Survivor” Badge |
| **Psych-Out Patterns** | Memorize sequences (e.g., “TAP, ↑, DON’T TAP”) every 10 prompts. | 100 Prompts: Pattern Journal (+10% Survival) |
| **Mind Challenges** | Optional rules: “Only use left hand” (+10% Score), “Tilt to survive” (+15% Risk), “No swipes” (+20% Survival). | Random (5% chance) if enabled |
| **Prestige** | Score 10,000 to restart with perks (Level 1: +100ms speed, Level 2: +5% Survival, Level 3: 2x Mind Coins). | Saved in Local Storage |

### 🎮 Controls
- **Tap**: Click/tap for **TAP** or **DOUBLE TAP**.
- **Swipe**: Drag for **↑/↓/←/→** (min 30px).
- **Hold**: Press 0.5s for **HOLD**.
- **Tilt**: Device tilt (>15° left/right) for **←/→** (optional).
- **Keyboard**: Space/Enter for **TAP**, arrow keys for **↑/↓/←/→**.

---

## 🌃 Cyberpunk Features: Neon Overload

**DECISION LOOP** isn’t just a game—it’s a sensory hack. Dive into its cyberpunk soul:

- **Neon Aesthetic**: CRT scanlines, Orbitron font, and a palette of #00FF00, #FF00FF, #00FFFF. Pulsing timer rings and glitchy game overs scream retro-futurism.
- **Chiptune Audio**: 8-bit square/sawtooth waves and WAVs (coin.wav, static.wav) scale pitch with your multiplier (10% per level). ASMR-like whooshes and crackles keep you locked in.
- **Mind Coins**: Earn 1–10 coins (20% chance per correct input, 2x at Prestige Level 3). Flex your haul in the UI.
- **Leaderboard**: Mock rivals like “YourEx” and “BrokeCoder” taunt you (GDPR opt-in, updates every 10s).
- **Idle XP**: Rack up 10 XP/hour offline (max 240/day). Get a “+120 XP waiting!” alert after 24 hours.
- **Accessibility**: Colorblind mode (pastel palette), tilt-free option, ARIA labels for screen readers.

```
   ╔═ NEON CITY LEADERBOARD ═╗
   ║ 1. YourEx: 12,345     ║
   ║ 2. BrokeCoder: 11,234 ║
   ║ 3. You: 10,000        ║
   ╚═══════════════════════╝
```

---

## 🛠️ Jack In: Setup Guide

Ready to hack the Grid? Follow these steps:

1. **Clone the Repo**:
   ```bash
   git clone https://github.com/your-repo/decision-loop.git
   ```
2. **Boot Up**: Open `index.html` in Chrome, Firefox, or Safari. No server needed—pure HTML5.
3. **Gear Check**: Optimized for mobile (iOS 14+, Android 10+) and desktop. 3GB RAM minimum for 60 FPS.
4. **Start the Loop**: Tap **START GAME** on the tutorial screen. Follow prompts, survive, and dominate.
5. **Tweak Settings**: Hit ⚙️ to toggle tilt, colorblind mode, dark mode, mind challenges, or GDPR opt-in.

![Settings Modal](https://raw.githubusercontent.com/kasduck/Decision_Loop_Game/refs/heads/main/SS2.png)  

---

## 🧠 Addiction Matrix: Why You Can’t Unplug

**DECISION LOOP** is a dopamine injector, built on behavioral psychology:

| Principle | Implementation | Effect |
|-----------|---------------|--------|
| **Skinner’s Rewards** | Variable mind coins (1–10, 20% chance), fake achievements (e.g., “Glitch Survivor”). | Keeps you chasing the next hit. |
| **Flow State** | 1-second cycles, rhythmic audio, pulsing visuals. | Time melts; sessions hit 5+ minutes. |
| **Loss Aversion** | Glitchy game overs (2s grayscale, static.wav), near-fail shakes (<10% Survival). | Failure stings, retries soar. |
| **Social Comparison** | Mock leaderboard with taunting usernames. | Fuels rivalry and bragging rights. |
| **Zeigarnik Effect** | Pattern memorization (e.g., “TAP, ↑, DON’T TAP”). | Unfinished patterns hook you back. |

> 💉 **Pro Tip**: Enable Mind Challenges for a cognitive overload that’ll rewire your brain.

---

## 🔍 Interactive Features

<details>
<summary>🎨 Customize Your Hack</summary>
Tweak the Grid to your liking in the **Settings** modal:
- **Tilt Input**: Enable/disable device tilt for “←”/“→”.
- **Colorblind Mode**: Pastel palette for better contrast.
- **Dark Mode**: Gray backdrop for low-light hacking.
- **Mind Challenges**: Random cognitive tests for extra rewards.
- **GDPR Opt-In**: Join the leaderboard to flex your score.
</details>

<details>
<summary>🏆 Prestige Perks</summary>
Hit 10,000 points to prestige and unlock:
- **Level 1**: +100ms game speed (slower prompts).
- **Level 2**: +5% Survival per correct input.
- **Level 3**: 2x mind coins for every drop.
</details>

<details>
<summary>📜 Pattern Journal</summary>
After 100 prompts, unlock a journal of memorized patterns (e.g., “TAP, ↑, DON’T TAP”). Earn +10% Survival for mastering the Grid’s tricks.
</details>

---

## ⚙️ Tech Specs

| Component | Details |
|-----------|---------|
| **Stack** | HTML5, CSS, JavaScript, Web Audio API. No frameworks. |
| **Assets** | Orbitron font (Google Fonts), WAVs (<1MB, coin.wav, static.wav). |
| **Storage** | Local storage for scores, coins, prestige, settings, idle XP. |
| **Performance** | 60 FPS on 3GB RAM devices. Low battery mode disables CRT overlay. |
| **Accessibility** | WCAG 2.1 AA partial compliance (ARIA labels, colorblind mode). |

![Game Over Screen](https://raw.githubusercontent.com/kasduck/Decision_Loop_Game/refs/heads/main/SS3.png)  

---

## 🚨 Known Glitches in the Grid

- **Pattern Journal**: Uses a basic alert. Styled modal planned for v2.0.
- **Tilt Sensitivity**: May be twitchy on some devices. Calibration in progress.
- **Monetization**: Mock purchase buttons (coins, skins) are WIP.
- **Achievements**: Limited variety. More badges (e.g., “Brain Sync”) coming.

---

## 🌌 Future Upgrades

| Feature | Status | ETA |
|---------|--------|-----|
| **Friend Codes** | 6-digit shareable codes for leaderboard access. | v2.0 |
| **Skins** | Blue/purple neon themes for mind coins. | v2.0 |
| **Rewarded Ads** | Opt-in 30s ads for 50 coins. | v2.0 |
| **Analytics** | Mock Firebase events for DAU/retention. | v2.1 |
| **Testing** | Usability tests with 12 jackers. | v2.1 |

---

## 🧑‍💻 Credits

- **Neurojacker**: [Kasduck] – Forged in Neon City’s shadows.
- **Inspiration**: *Tron*, *Neuromancer*, 1980s arcades, behavioral psych (Skinner, Csikszentmihalyi, Kahneman).
- **Assets**: Google Fonts (Orbitron), freesound.org (WAVs).

---

## 📡 Join the Rebellion

Jack into **DECISION LOOP** and own the Grid. Share your high scores, report glitches, or propose hacks in the [Issues](https://github.com/your-repo/decision-loop/issues) tab. Stay wired, jacker.

> **“The Grid doesn’t sleep. Neither should you.”**  
> — Anonymous Neurojacker, 2087

![Neon City](https://raw.githubusercontent.com/kasduck/Decision_Loop_Game/refs/heads/main/SSS.jpg)  
*Replace with a cyberpunk-themed banner.*
