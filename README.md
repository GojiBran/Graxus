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
