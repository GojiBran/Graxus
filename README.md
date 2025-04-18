# Graxus
 Graxus - Idle Clicker?

# 🥚 Graxus: The Living Collective - GDD

## 🎮 Overview
**Graxus** is an idle swarm evolution game where players hatch, grow, and multiply creatures called **Grax** into a massive swarm.  
Care for them collectively by feeding and entertaining, and watch as they evolve through stages and eventually multiply.

---

## 📜 Core Gameplay

| System | Description |
|:-------|:------------|
| **Start** | Hatch the first Grax manually by pressing `Start`. |
| **Growth** | Each Grax grows automatically over time and when fed/played with. |
| **Hunger / Boredom** | Grax become hungry and bored over time; neglect causes death. |
| **Stages** | Grax evolve through `Egg → Baby → Adult` based on group growth. |
| **Multiplication** | Adults ready to multiply can hatch new eggs when paired. |
| **Death** | If a Grax reaches 100% hunger or boredom, it dies and is counted as "Ascended." |

---

## 🧬 Core Systems

| System | Details |
|:-------|:--------|
| **Traits** | Each Grax has one random trait affecting growth, hunger, and boredom rates. |
| **Group Evolution** | Entire stage group must reach 100% growth before evolving. |
| **Adult Growth Sync** | All adults have averaged growth to represent the entire adult stage. |
| **Reproduction Penalty** | After hatching a baby, adult growth is halved to simulate effort. |
| **First Split** | The first adult hatches one free egg automatically without a partner. |
| **Loading Bar** | Smooth animated loading with sound feedback. |
| **Sparkles & Effects** | Visual sparkles on Grax cards and neon-style UI. |

---

## 🎨 Visual Style

| Element | Style |
|:--------|:------|
| **Theme** | Dark neon retro aesthetic (`#111` background, `#99cc33` neon green). |
| **Font** | `'Press Start 2P'` retro pixel font. |
| **Cards** | Neon glowing cards per stage with progress bars for Hunger, Boredom, Growth. |
| **Progress Bars** | Dark backgrounds with neon-colored progress fill and centered labels. |
| **Sparkles** | Small animated sparkles drift on cards for a living effect. |

---

## 🔊 Sound

- **Pop Sounds**: Square wave pops when events like hatch or load complete.
- **Loading Complete Sound**: Higher-pitch pop to signal game ready.
  
---

## ⚙️ Technical Details

| Feature | Status |
|:--------|:-------|
| **Auto-saving** | LocalStorage saves swarm state. |
| **Tick System** | Every 5 seconds, all Grax stats are updated (hunger, boredom, growth). |
| **Recovery Boost** | Every 30 seconds, small passive healing and growth boost. |
| **Manual Feed/Play** | Player can Feed and Play via buttons anytime. |
| **Mobile Support** | Fully responsive with Bootstrap 5 layout. |
| **Performance** | Lightweight, no frameworks beyond Bootstrap. Fast on desktop and mobile. |

---

## 🚀 Future Expansion Ideas (Optional)

| Idea | Quick Note |
|:-----|:-----------|
| **Grax Moods** | Grax show emotions when hungry, bored, happy, etc. |
| **Rare Traits** | Shiny or rare Grax with unique visual effects. |
| **Achievements** | Milestones for growing large swarms. |
| **Monolith System** | Auto-feeds and entertains Grax slowly over time. |
| **Grax Naming** | Allow players to rename individual Grax. |
| **Gene Mixing** | Future feature where offspring traits combine from parents. |

---

# 📅 Version 2.3 Status

- ✅ Full hatch → evolve → multiply flow complete.
- ✅ Adult growth synchronized.
- ✅ Reproduction penalty working.
- ✅ Smooth loading, clean UI.
- ✅ Polished to "playable alpha" level.
- 🔥 Ready for expansion modules!

---

# 🖊️ Credits

- **Design & Development:** Goji (You 🐙)
- **ChatGPT Assistance:** Markdown formatting, code polish, game design help ✨

---

# 📂 Save Location

- **Browser Storage:** `localStorage` keys:
  - `graxusSave` — current swarm data
  - `graxCounter` — counter for unique Grax IDs

---

# 📸 Example Screenshots (Future)

- [ ] Swarm overview with stages
- [ ] Closeup of sparkles and loading screen
- [ ] Progress bar dynamics over time

---

# 🧪 Testing Checklist

- [x] Starter Egg hatches properly
- [x] Hunger/Boredom/Growth update over time
- [x] Feeding and Playing work properly
- [x] Group evolves only when entire stage is 100%
- [x] Adults average growth correctly
- [x] First adult splits correctly
- [x] Normal adult multiplication applies penalty
- [x] Game saves/reloads automatically
- [x] Mobile layout functional
- [x] Loading bar + sound plays properly

---

# 💬 Final Notes

**Graxus v2.3** is stable, adorable, and ready for future upgrades.  
Already more polished than many indie "idle" games in the wild today.  
🌱 **Grow the collective. Multiply. Evolve.** 🐙
