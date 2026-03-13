# 🌙 Eid ul Fitr Greeting Card

A beautiful, personalised **Eid ul Fitr greeting website** built with pure HTML, CSS & JavaScript. Create a custom Eid card for your loved ones and share it as a single short link — no backend, no redirects, no apps needed.

🔗 **Live Demo:** [muhammadasim2009.github.io/eid-greeting](https://muhammadasim2009.github.io/eid-greeting/)

---

## ✨ Features

- 🎨 **4 Beautiful Themes** — Royal Night, Rose Garden, Emerald, Purple Majesty
- 💌 **Personalised Cards** — Custom recipient name, message & sender name
- 🔗 **Shareable Short Link** — All data encoded in the URL hash, no server needed
- 📱 **WhatsApp Share** — Send your greeting link directly via WhatsApp
- 🎆 **Animated Effects** — Fireworks, floating petals, swaying lanterns & twinkling stars
- 🌙 **Animated Moon** — Crescent moon with glowing stars and shooting stars
- ⏳ **Eid Countdown Timer** — Live countdown to Eid day
- 💬 **4 Preset Messages** — Ready-made heartfelt messages with one click
- ✍️ **Custom Messages** — Write your own personal message
- 🖨️ **Print / Save** — Clean print layout to save as PDF
- 📋 **Copy Message** — Copy the greeting text to clipboard
- 📱 **Fully Responsive** — Works perfectly on mobile, tablet & desktop
- ⚡ **Zero Dependencies** — Pure HTML, CSS & JS — no frameworks, no npm

---

## 🚀 How It Works

### For the Sender
1. Open the website
2. Pick a **theme** (4 colour options)
3. Enter the **recipient's name**
4. Choose a **preset message** or write your own
5. Enter **your name** and set the **Eid date**
6. Click **"Generate Greeting Link"**
7. A short shareable link appears instantly
8. Copy it or send directly via **WhatsApp**

### For the Receiver
- They simply **click the link**
- The greeting page opens **directly** with their name, your message, fireworks and all animations
- No app, no login, no loading screen

---

## 🔗 How the URL Works

All greeting data is packed into the **URL hash** using Base64 encoding:

```
https://muhammadasim2009.github.io/eid-greeting/#QXNpbXwwfE11aGFtbWFkIEFzaW18NDUxfG4
```

**Data packed inside (pipe-separated → Base64):**
```
name | messageIndex | senderName | daysSince2025 | themeChar
```

| Field | Example | How stored |
|---|---|---|
| Recipient name | `Asim` | Plain text |
| Message | Preset #0 | Index `0`–`3` only (not full text!) |
| Sender name | `Muhammad Asim` | Plain text |
| Eid date | `2026-03-21` | Days since Jan 2025 |
| Theme | `night` | Single char `n/r/e/p` |

✅ No server · ✅ No redirect · ✅ No third party · ✅ Works forever

---

## 🎨 Themes Preview

| Theme | Colors |
|---|---|
| 🌑 Royal Night | Deep navy + Gold |
| 🌸 Rose Garden | Deep rose + Pink gold |
| 🌿 Emerald | Deep forest green + Mint |
| 💜 Purple Majesty | Deep purple + Lavender |

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure & layout |
| CSS3 | Animations, themes, responsive design |
| Vanilla JavaScript | URL encoding/decoding, fireworks, countdown |
| Canvas API | Fireworks particle animation |
| SVG | Moon, lanterns, decorative elements |
| Google Fonts | Amiri, Playfair Display, Crimson Pro |
| Base64 / btoa & atob | URL data encoding & decoding |
| GitHub Pages | Free hosting |

---

## 📁 Project Structure

```
eid-greeting/
│
├── index.html       # The entire app — single self-contained file
└── README.md        # You are here
```

> Everything lives in a single `index.html` file. No build steps, no dependencies, no configuration.

---

## 🖥️ Run Locally

No installation needed. Just:

```bash
# Clone the repo
git clone https://github.com/MuhammadAsim2009/eid-greeting.git

# Open in browser
cd eid-greeting
open index.html
```

Or simply **double-click** `index.html` — it works offline too.

---

## 🌐 Deploy to GitHub Pages

1. Push `index.html` to your repo's `main` branch
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Click **Save**
5. Your site goes live at:
   ```
   https://muhammadasim2009.github.io/eid-greeting/
   ```

---

## 🤲 Islamic Phrases Used

| Arabic | Transliteration | Meaning |
|---|---|---|
| عيد مبارك | Eid Mubarak | Blessed Eid |
| بارك الله فيك | Barakallahu feek | May Allah bless you |
| تقبّل الله منا ومنكم | Taqabbal Allahu minna wa minkum | May Allah accept from us and from you |

---

## 👨‍💻 Author

**Muhammad Asim**
- GitHub: [@MuhammadAsim2009](https://github.com/MuhammadAsim2009)
- Intern @ Tryunity Solution
- Student @ Aptech Larkana

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🌙 Eid Mubarak!

> *May this Eid bring you and your loved ones endless joy, peace, and blessings.*
> 
> **عيد مبارك وكل عام وأنتم بخير** 🎉
