# 🥚 Graxus: The Living Collective (idle clicker?)

## 🎮 Overview
Graxus is an idle swarm evolution game where players hatch, grow, and multiply creatures called Grax into a massive collective.  
Feed and entertain them to keep them alive and watch as the swarm evolves and multiplies.

---

## 📜 Core Gameplay

| System | Description |
|:-------|:------------|
| Start | Hatch the first Grax manually by pressing Start. |
| Growth | Grax grow automatically over time and faster when fed or played with. |
| Hunger / Boredom | Grax get hungry and bored over time. If either reaches 100%, they die. |
| Stages | Grax evolve through Egg → Baby → Adult. The entire stage must reach 100% growth to evolve. |
| Multiplication | Adults ready to multiply can pair up to hatch a new Grax. |
| Death | Dead Grax are counted as "Ascended" and no longer participate in the swarm. |

---

## 🧬 Core Systems

| System | Details |
|:-------|:--------|
| Traits | Each Grax has one random trait that affects their growth, hunger, and boredom rates. |
| Group Evolution | All Grax in a stage must reach 100% growth before evolving. No individuals evolve alone. |
| Adult Growth Sync | Adult Grax share an average growth value to represent their collective readiness. |
| Reproduction Penalty | When new Grax hatch, existing adults lose 50% growth and re-average. |
| First Split | The first adult automatically hatches one egg when ready, without needing a partner. |
| Loading Bar | Visual loading screen with animation and sound effect. |
| Sparkles | Sparkling visual effects on swarm cards for atmosphere. |

---

## 🎨 Visual Style

| Element | Style |
|:--------|:------|
| Theme | Dark neon aesthetic (#111 background, #99cc33 neon accents). |
| Font | 'Press Start 2P' retro pixel font. |
| Cards | Neon-bordered cards for each stage group with visual meters. |
| Progress Bars | Centered text labels with neon color fills. |
| Sparkles | Animated floating sparkles to make the swarm feel alive. |

---

## 🔊 Sound

- Pop sounds when hatching or loading finishes.
- Higher-pitched pop to indicate successful actions.

---

## ⚙️ Technical Details

| Feature | Status |
|:--------|:-------|
| Auto-saving | Saves swarm data to browser localStorage automatically. |
| Tick System | Updates Grax stats every 5 seconds. |
| Recovery Boost | Small recovery in hunger and boredom every 30 seconds. |
| Manual Feed/Play | Players can boost growth anytime with buttons. |
| Mobile Support | Fully responsive design. |
| Performance | Lightweight, minimal external libraries (only Bootstrap 5). |

---

## 🚀 Expansion Ideas

| Idea | Note |
|:-----|:-----|
| Grax Moods | Visual indicators for different emotional states. |
| Rare Traits | Rare shiny Grax variants with special visuals. |
| Achievements | Unlock rewards for growing larger swarms. |
| Monolith System | Slow automatic feeding and entertainment over time. |
| Grax Naming | Rename individual Grax. |
| Gene Mixing | Combine parent traits during reproduction. |

---

## 📂 Save Data Structure

| Key | Data |
|:----|:-----|
| graxusSave | JSON of all live and dead Grax. |
| graxCounter | Running number to assign unique Grax IDs. |

---

## 📋 Testing Checklist

- [x] Starter egg hatches correctly
- [x] Hunger, boredom, and growth update over time
- [x] Feeding and playing modify stats correctly
- [x] Entire stage evolves together
- [x] Adult growth is properly averaged
- [x] First split without partner works
- [x] Adults reproduce correctly
- [x] Saving and loading works automatically
- [x] Mobile layout functional
- [x] Loading bar and pop sound work on startup

---

## 🧠 Final Notes

Graxus v2.3 is stable, polished, and fully playable as an idle swarm evolution game.  
The base system is modular and expandable for future features.  
Graxus will continue to grow as new ideas are added.

---

# 🥚 How to Play **Graxus - The Living Collective**

## 🎮 Basic Goal
- **Grow your Graxus swarm!**  
- **Hatch**, **feed**, **play**, and **evolve** your Grax into a thriving living collective.  
- Keep them **alive** by managing **hunger** and **boredom**, and help them **multiply** to build a bigger swarm!

---

## 🛠 Controls
| Button     | What it Does |
|:-----------|:-------------|
| **Start**  | Hatches your first Graxus egg. (You must start here!) |
| **Feed**   | Lowers everyone's hunger and helps them grow faster. |
| **Play**   | Lowers everyone's boredom and helps them grow faster. |
| **Reset**  | Wipes your entire save and restarts the game. |

---

## 🐣 Stages of a Grax
- **Egg** 🥚 → **Baby** 🍄 → **Adult** 🐙
- Each stage has different growth rates and needs.
- **Feed** and **play** with them to help them **grow**!

---

## 🌱 Growth & Evolution
- When a Grax reaches **100% growth**, it **evolves** to the next stage:
  - **Egg → Baby**
  - **Baby → Adult**
- When Adults are ready (after growing), they can **multiply** to hatch more Eggs!

---

## ⚠️ Danger: Death
- If **Hunger** or **Boredom** hits **100%**, the Grax **dies** (they "ascend" ☠️).
- Dead Grax are lost forever — keep your swarm happy!

---

## ✨ Special Features
- **Random Traits**: Every Grax has a personality (like "Lazy" or "Energetic") that changes how fast they grow, get hungry, and get bored.
- **Sparkles**: More Grax = more sparkles on your cards! ✨
- **Progress Bars**: Hunger, Boredom, and Growth are shown right on the cards.
- **Tick Bar**: A loading bar at the bottom shows time passing between automatic updates ("ticks").

---

## 🔄 Automatic Things
- Every few seconds (every **5 seconds**):
  - Grax get **hungrier**, **bored**, and **grow** automatically.
- Every **30 seconds**:
  - All Grax get a **small healing boost** to Hunger and Boredom, and extra Growth.
- Adults **multiply** automatically if conditions are right!

---

## 🧠 Pro Tips
- **Feed and play often**!  
- **Don’t wait too long** between actions or your Grax might die!
- Once you get **Adults**, **more eggs** will hatch automatically!
- **Bigger swarms** mean more chances to expand faster — but also harder to manage!

---

# 💾 Saving
- Your progress saves automatically in your browser (`localStorage`).
- Closing or refreshing the page **keeps** your swarm!
- Pressing **Reset** will **delete everything** and start over.

---

# ⚙️ **Graxus - The Living Collective Mechanics**

## 🥚 1. Starting the Game
- Click **Start** to hatch your first **Grax-001** egg.
- Each Grax starts with:
  - **Hunger** = 0
  - **Boredom** = 0
  - **Growth** = 0
  - **Stage** = Egg
  - A **random trait** (like Lazy, Chill, Hyper, etc.)

---

## 🧬 2. Traits
| Trait | Growth Rate | Hunger Rate | Boredom Rate |
|:------|:------------|:------------|:-------------|
| Lazy | 0.3 | 1 | 1 |
| Energetic | 0.7 | 1 | 2 |
| Greedy | 0.5 | 2 | 1 |
| Chill | 0.5 | 0.5 | 0.5 |
| Hyper | 0.8 | 1.5 | 2 |
| Balanced | 0.5 | 1 | 1 |

- Traits control how fast Grax grow, get hungry, or get bored.

---

## ⏳ 3. Ticking System
- **Every 5 seconds**, Grax update:
  - Hunger and Boredom **increase**.
  - Growth **increases** slightly.
- **Every 30 seconds**, Grax heal:
  - Hunger and Boredom **decrease** a little.
  - Growth **boosts** by 3%.

---

## 🥕 4. Feeding and Playing
| Action | Effect |
|:-------|:-------|
| **Feed** | -20 Hunger + Growth Boost |
| **Play** | -20 Boredom + Growth Boost |

| Stage | Feed Boost | Play Boost |
|:------|:-----------|:-----------|
| Egg | +2% | +1% |
| Baby | +6% | +4% |
| Adult | +10% | +7% |

---

## 🌱 5. Stage Evolution
- **Egg → Baby → Adult**
- Evolve when reaching **100% growth**.
- Evolving resets Hunger and Boredom to 0.

---

## 🐙 6. Multiplication
- **First Split**:  
  One ready Adult hatches a new Egg solo (only once).
- **Normal Multiplication**:  
  Two ready Adults create a new Egg together.
- After 2 babies, an Adult can no longer reproduce.

---

## 💀 7. Death
- If Hunger **or** Boredom reaches **100%**, a Grax **dies** ("Ascended").

---

## 🔄 8. Saving & Persistence
- All progress saves automatically in your browser.
- **Reset** button wipes your save.

---

# 🎯 Life Cycle Diagram

> 🥚 Egg → 🍄 Baby → 🐙 Adult → 🥚 Egg → 🍄 Baby → 🐙 Adult → ...

---

# 🧠 Bonus
- **Sparkles** appear on cards based on Grax amount.
- **Tick Progress Bar** shows time until next automatic update.
- **Growth Sync**: Adults sync their growth level after hatching a baby.