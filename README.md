# ⚔️ ANIME VAULT — Character Archive

> A dark, cinematic anime character gallery built with pure HTML, CSS & JavaScript.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## ✨ Features

- **20 Characters** across 4 anime series
- **Netflix-style horizontal scroll** per series
- **Filter tabs** — switch between JJK, Naruto, AOT, Demon Slayer
- **Aura Glow** — each character has a unique color aura that matches their power
- **Battle Stats** — Wins, Losses & Win Rate per character
- **Status Badge** — Alive / Deceased
- **Rank Badge** — Special Grade, Hashira, Hokage, etc.
- **Iconic quotes** for every character
- **Death details** — cause of death for deceased characters
- **Click any card** → Full detail modal with abilities & full death story
- **Smooth animations** — hover zoom, glow effects, grain overlay
- **No frameworks** — pure vanilla HTML/CSS/JS, zero dependencies

---

## 🎭 Characters

| Anime | Characters |
|-------|-----------|
| **Jujutsu Kaisen** | Gojo Satoru, Sukuna, Itadori, Megumi, Toji |
| **Naruto** | Naruto, Sasuke, Itachi, Minato, Madara |
| **Attack on Titan** | Eren, Levi, Zeke, Erwin, Armin |
| **Demon Slayer** | Tanjiro, Muzan, Rengoku, Akaza, Douma |

---

## 🚀 Usage

No installation needed. Just open the file:

```bash
git clone https://github.com/YOUR_USERNAME/anime-vault.git
cd anime-vault
open anime-gallery.html
```

Or just double-click `anime-gallery.html` in your file manager.

---

## 🛠️ Add a Character

Inside `anime-gallery.html`, find the `CHARS` array and add a new object:

```js
{
  anime: "JJK",              // JJK | Naruto | AOT | DS
  name: "CHARACTER NAME",
  title: "Title / Role",
  img: "https://your-image-url.jpg",
  quote: "Iconic quote here.",
  aura: "#hexcolor",         // Aura glow color
  rank: "RANK",
  status: "alive",           // alive | dead | unknown
  wins: 100,
  losses: 2,
  abilities: ["Ability 1", "Ability 2"],
  death: null                // or { by: "Killer", reason: "Full story..." }
}
```

---

## 📁 Structure

```
anime-vault/
└── anime-gallery.html    # Everything in one file
└── README.md
```

---

## 🎨 Design

- **Dark cinematic** aesthetic with noise grain overlay
- **Bebas Neue** for titles, **Rajdhani** for UI, **Noto Serif JP** for quotes
- Each character has a unique **aura color** used across glow, quote border & name gradient
- Fully **responsive** — works on mobile & desktop

---

*Built with 🖤 — no libraries, no frameworks, just vibes.*
