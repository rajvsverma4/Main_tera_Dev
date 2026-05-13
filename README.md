# 🐱💛 Main Tera — May 13 Project Memory

## What We Built
A fun interactive website for the **"Main Tera" May 13 internet trend**, inspired by the user's existing Valentine's Day project (`valentine-riya-main.zip`).

---

## The Trend Explained
- **May 13** in Hindi = **"Main Tera"** (I am yours)
- May = "Main" | 13 = "Tera"
- Goes viral every year on May 13 with Bollywood song edits and memes
- Most popular song used: **Kalank Title Track** by Arijit Singh (2019, music by Pritam, lyrics by Amitabh Bhattacharya)
- Key lyrics: *"Main gehra tamas, tu sunehra savera… Main tera ho, main tera"*

---

## Original Valentine's Project (Reference)
File: `valentine-riya-main.zip`
- **Stack:** Plain HTML + CSS + JS (no framework)
- **Flow:** Multi-screen interactive story with Yes/No buttons, jumping "No" button, slider, video reveal at end
- **Features:** Heart rain, typewriter text, page flash, speech bubbles, audio/video assets
- **Theme:** Pink/red romantic gradient

---

## What We Built — Main Tera Website

### File
`index.html` — single self-contained file, no dependencies

### Design Decisions
- **Language:** English only (all UI/buttons/text) — lyrics kept in **Hinglish only**
- **Theme:** Deep night sky (dark purple) + gold/amber — different from the pink Valentine's site
- **Fonts:** Playfair Display (serif, italic for lyrics) + Nunito (UI)
- **Background:** Animated starfield + falling emoji rain (💛🐱🎵✨🌙)

### Interactive Flow (same structure as Valentine's project)
| Screen | Content |
|--------|---------|
| S1 | Explains May 13 = Main Tera pun. Cat image. Yes/No buttons |
| S2 | Introduces Kalank song with Hinglish lyrics. Jumping No button |
| S3 | "Are you mine?" question. Jumping No button |
| S4 | Slider — "How much am I yours?" with cat image |
| S5 | Celebration: "I AM YOURS! 💛" |
| Final Card | Cat emoji + full Hinglish lyrics + **YouTube embed** + replay button |

### Hinglish Lyrics Used
- Screen 2: *"Main gehra tamas, tu sunehra savera…"*
- Screen 5: *"Main tera ho, main tera… Musafir main bhatka, tu mera."*
- Final card: *"Main gehra tamas, tu sunehra savera… Main tera ho, main tera."*

### Cat Images
- Source: `cataas.com` API (Cat as a Service)
- Each screen has a different cat with custom text overlay:
  - S1: "May 13"
  - S2: "I am yours"
  - S3: "Be Mine"
  - S4: "Slide!"
- Fallback: `placekitten.com` (via `onerror`)
- ⚠️ Both APIs are unreliable — noted for future fix

### Song
- **YouTube embed:** Kalank Title Track — `https://www.youtube.com/embed/Grr0FlC8SQA`
- **Start time:** `start=227` (3 min 47 sec) — plays directly from the **"Main tera main tera"** ending section
- Autoplay enabled

---

## GitHub Deployment

### Repo Setup
- Repo name: `main-tera-may13`
- Visibility: **Public** (required for free GitHub Pages)
- File structure:
  ```
  main-tera-may13/
  ├── README.md
  └── index.html
  ```

### Steps
1. github.com/new → create public repo
2. Upload `index.html` via Add file → Upload files
3. Settings → Pages → Branch: main, folder: / (root) → Save
4. Live at: `https://USERNAME.github.io/main-tera-may13/`

### Issue Faced
- User's repo was set to **Private** → Pages showed "Upgrade" prompt
- Fix: Settings → Danger Zone → Change visibility → Make public

---

## Known Issues / Future Improvements
- [ ] `cataas.com` returns 403 sometimes — replace with self-hosted cat images in `images/` folder
- [ ] YouTube autoplay blocked on iOS Safari — user has to tap play manually
- [ ] Could add a **shareable card generator** for sending to someone on May 13
- [ ] Could add background music (like the Valentine's project had)

---

## Key Files
| File | Location |
|------|----------|
| Final website | `/mnt/user-data/outputs/main-tera-may13/index.html` |
| Original Valentine's zip | `/mnt/user-data/uploads/valentine-riya-main.zip` |
| This memory file | `/mnt/user-data/outputs/main-tera-project-memory.md` |

---

*Chat date: May 13, 2026 — literally Main Tera day! 🐱💛*
