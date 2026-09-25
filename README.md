# 📚 Hindi & English Essays Collection

Ek single-file HTML web app — Hindi aur English essays padhne, likhne aur manage karne ke liye. Koi installation nahi, koi server nahi — bas `index.html` browser mein kholo.

## 🚀 Use kaise karein
**Option A — Direct kholo:**
1. Teeno file (`index.html`, `style.css`, `script.js`) ek hi folder mein rakho.
2. `index.html` ko double-click karke browser (Chrome/Edge/Firefox) mein khol lo.

**Option B — GitHub Pages pe host karo (free):**
1. GitHub par naya repository banao (e.g. `essay-reader`).
2. `index.html`, `style.css`, `script.js` — teeno files usi repo ke root mein upload/commit karo.
3. Repo → **Settings → Pages** → Source: `main` branch, folder `/ (root)` → **Save**.
4. 1-2 min baad `https://<username>.github.io/essay-reader/` pe live ho jayega.

## ✨ Features

### Reading & Display
- Font size slider (10px – unlimited, `Ctrl + Mouse Wheel` se bhi)
- Font style (Sans/Serif/Monospace/Georgia/Verdana)
- Text color (8 preset colors)
- Bold toggle
- Reading Mode — bada font + yellow + bold, distraction-free
- Focus Mode — sirf text, baaki UI hide
- Fullscreen mode
- Dark / Light theme
- Hindi ⇄ English language toggle

### Essay Management (Tabs)
- 39+ ready essays, unlimited khud ke essays add karo
- Tab **right-click** karne par menu:
  - ➕ **Add Essay**
  - ⬇️ **Download as HTML** — sirf usi ek essay ki full-featured standalone HTML file banti hai
  - 🗑️ **Delete Essay**
- Tabs ko drag/long-press karke reorder karo
- Essay edit karo (sirf khud ke add kiye hue)
- Position choose karke essay kahin bhi insert karo (start/end/custom number)

### Tools
- 📊 Essay Statistics (words, chars, lines, reading time)
- 📋 Copy essay text
- 📤 Share (mobile)
- 🌐 Free translation (via API)
- 📄 Export as TXT
- 🔖 Bookmark essays
- 🔍 Search in current essay
- 📚 Search across all essays
- ⏱️ Live Timer (Stopwatch / Countdown)
- 🌙 Night filter
- 🖨️ Print (current styling ke saath)

### Downloaded Single-Essay HTML
Right-click → Download se banne wali file mein bhi apne features hain:
- Full-screen text layout (koi khaali margin nahi)
- Font size, Bold, Color, Reading Mode, Focus Mode
- Theme toggle, Fullscreen, Print, Copy, TXT download
- Search in essay
- **Keyboard shortcuts** (niche dekho)

## ⌨️ Keyboard Shortcuts (Main App)
| Key | Action |
|---|---|
| `↑ / ↓` | Scroll |
| `← / →` | Font size |
| `Ctrl + Wheel` | Font size (fine) |
| `B` | Bold |
| `H` | Focus Mode |
| `R` | Reading Mode |
| `F` | Fullscreen |
| `G` | Cycle text color |
| `J` | Theme toggle |
| `N / P` | Next / Previous essay |
| `1–99` | Essay number pe jump |
| `Space / Shift+Space` | Page scroll |
| `?` | Shortcuts dikhao |
| `ESC` | Kisi bhi mode se bahar |

## ⌨️ Keyboard Shortcuts (Downloaded Single-Essay File)
| Key | Action |
|---|---|
| `↑ / ↓` | Scroll |
| `← / →` | Font size |
| `Ctrl + Wheel` | Font size |
| `Space` | Page scroll |
| `B` | Bold |
| `H` | Focus Mode |
| `R` | Reading Mode |
| `F` | Fullscreen |
| `G` | Cycle color |
| `J` | Theme toggle |
| `L` | Language toggle (agar dono available ho) |
| `Ctrl + F` | Search |
| `?` | Shortcuts panel |
| `ESC` | Band karo / mode se bahar |

## 💾 Data Storage
Sab data **browser ke localStorage** mein save hota hai (koi backend/database nahi):
- Khud ke add kiye essays
- Essay order, bookmarks
- Theme, reading settings, active tab

⚠️ Browser data/cache clear karne se ye saara data delete ho sakta hai — important essays ko **Download / TXT export** karke backup rakhna behtar hai.

## 🗂️ Files
```
index.html   → Page structure
style.css    → Sara styling / themes
script.js    → Sara logic (essays, tabs, tools, shortcuts)
README.md    → Ye documentation
```

---
Made with ❤️
