# 🥛 DoodhWala

**Subscription infrastructure for local milk delivery.**
स्थानिक दूधवाल्यांसाठी सदस्यता आणि मागणी व्यवस्थापन प्रणाली.

A bilingual (Marathi + English) landing page for a milk subscription + demand-management platform built for **local milkmen, apartment societies, and residents**.

---

## ✨ What's on the page

| Section | What it shows |
|---|---|
| 🎠 Hero carousel | Auto-rotating background of delivery/society/village scenes |
| 🥛 Floating notification | Bottom-left widget — the evening "Tomorrow's milk?" prompt, auto-pops once, fully interactive |
| 🖼️ Live demo | Change a resident's quantity → milkman's demand table updates instantly |
| 👥 Three users | Resident / Milkman / Society feature cards |
| 🕔 Milkman dashboard | Society-wise totals + flat-wise delivery marking |
| ⏸️ Vacation mode | Pause 2 Oct → 15 Oct, auto-resume 16 Oct |
| 💬 WhatsApp-first | Reply `1` / `4` to change or skip |
| 🏡 Village-friendly | Works on any phone, in Marathi, on slow networks |
| 📱 Every screen | Mobile / tablet / laptop showcase |
| 📈 Forecasting | Confirmed + historical + buffer → recommended procurement |
| 💰 Pricing | ₹499 / ₹999 / ₹3-per-customer · free for residents |

## 🌐 Language

Click the **🌐 EN** button in the navbar to toggle the entire page between **मराठी** and **English** (244+ translated strings, including live demo messages).

## 📁 Structure

```
doodhwala/
├── index.html          # single-file landing page (no build, no dependencies)
└── images/             # 13 generated illustrations (1408×768)
```

## 🚀 Run locally

No build step — just open it:

```bash
open index.html        # macOS
xdg-open index.html    # Linux
```

Or serve it:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## 🖥️ Responsiveness

4 breakpoints: `980px` · `768px` · `520px` · `prefers-reduced-motion`.
Safe-area aware floating widget, no horizontal overflow from 320px up.

---

Made in Maharashtra 🇮🇳
