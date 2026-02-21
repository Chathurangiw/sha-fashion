# 👗 SHA Fashion | ශා ෆැෂන්

<div align="center">

![SHA Fashion Banner](https://img.shields.io/badge/SHA-FASHION-C0141E?style=for-the-badge&labelColor=0A0A0A&color=C0141E)
![Version](https://img.shields.io/badge/Version-1.0.0-gold?style=for-the-badge&labelColor=0A0A0A)
![Language](https://img.shields.io/badge/Language-HTML%20%7C%20CSS%20%7C%20JS-C0141E?style=for-the-badge&labelColor=0A0A0A)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge&labelColor=0A0A0A)

**Premium Sri Lankan Garment & Fashion Brand Website**
*නූතන ශ්‍රී ලාංකික ඇඳුම් හා ෆැෂන් වෙළඳ නාමය*

[🌐 Live Demo](#) • [📞 Contact](#contact) • [⭐ Star this Repo](#)

</div>

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Preview](#preview)
- [Getting Started](#getting-started)
- [Deploying to GitHub Pages](#deploying-to-github-pages)
- [File Structure](#file-structure)
- [Customization](#customization)
- [Technologies Used](#technologies-used)
- [Contact](#contact)

---

## 🏷️ About

**SHA Fashion** is a professional single-page website for a Sri Lankan clothing and garment company. The site is designed with a luxury red and black theme, supports both **English and Sinhala (සිංහල)** languages, and is fully responsive across all devices.

> *ශා ෆැෂන් යනු ශ්‍රී ලාංකික ඇඳුම් සමාගමක් සඳහා නිර්මිත වෘත්තීය වෙබ් අඩවියකි.*

---

## ✨ Features

| Feature | Description |
|---|---|
| 🌐 **Bilingual** | Full English & Sinhala (සිංහල) language toggle |
| 🎨 **Brand Theme** | Red & Black luxury color scheme |
| 📱 **Responsive** | Works on mobile, tablet & desktop |
| ⚡ **Fast** | Pure HTML/CSS/JS — no frameworks needed |
| 🎭 **Animations** | Scroll-triggered fade-ups & hover effects |
| 📜 **Marquee** | Animated scrolling brand strip |
| 🗂️ **Sections** | Hero, About, Collections, Services, Testimonials, Contact, Footer |
| 📬 **Contact Form** | Inquiry form with service selector |
| 🔝 **Scroll-to-Top** | Floating back-to-top button |

---

## 🖼️ Preview

```
┌─────────────────────────────────────────┐
│  SHA FASHION  |  ශා ෆැෂන්         EN සිං │
├─────────────────────────────────────────┤
│                                         │
│   Where Style                           │
│   Meets Soul     [Hero Image Grid]      │
│                                         │
│   [Explore]  [Order Now]                │
├─────────────────────────────────────────┤
│  ✦ SHA FASHION ✦ Sri Lankan Elegance ✦  │  ← Marquee
├─────────────────────────────────────────┤
│  About │ Collections │ Services │ etc.  │
└─────────────────────────────────────────┘
```

### Sections Included:
- 🏠 **Hero** — Full-screen landing with CTA buttons
- 📖 **About** — Company story + stats (500+ clients, 50+ designs)
- 👗 **Collections** — Women's, Men's, Traditional, Custom Tailoring
- 🛠️ **Services** — 6 service cards with hover effects
- ⭐ **Testimonials** — Scrollable bilingual customer reviews
- 📞 **Contact** — Address, phone, hours + inquiry form
- 🔗 **Footer** — Links, social icons, copyright

---

## 🚀 Getting Started

### Option 1: Open Directly (No Setup Needed)

Just download and open the file:

```bash
# 1. Download the file
# 2. Double-click index.html
# 3. Opens in your browser instantly ✅
```

### Option 2: Clone from GitHub

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/sha-fashion.git

# Go into the folder
cd sha-fashion

# Open in browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## 🌍 Deploying to GitHub Pages

Follow these steps to make the site **live on the internet for free**:

### Step 1 — Create a GitHub Account
Go to [github.com](https://github.com) and sign up if you don't have an account.

### Step 2 — Create a New Repository

```
1. Click the green "New" button on your GitHub dashboard
2. Repository name: sha-fashion
3. Set to: Public ✅
4. Click "Create repository"
```

### Step 3 — Upload Your Files

**Option A: Upload via Browser (Easiest)**
```
1. Open your new repository
2. Click "Add file" → "Upload files"
3. Drag and drop your index.html file
4. Write commit message: "Initial website upload"
5. Click "Commit changes"
```

**Option B: Upload via Git (Terminal)**
```bash
# Initialize git in your project folder
git init

# Add files
git add .

# Commit
git commit -m "Initial commit - SHA Fashion website"

# Connect to GitHub (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/sha-fashion.git

# Push to GitHub
git push -u origin main
```

### Step 4 — Enable GitHub Pages

```
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source" → select "Deploy from a branch"
5. Branch: main | Folder: / (root)
6. Click "Save"
```

### Step 5 — Your Site is Live! 🎉

```
Wait 1–2 minutes, then visit:
https://YOUR-USERNAME.github.io/sha-fashion
```

> ⚠️ **Important:** Your HTML file must be named `index.html` (not `sha-fashion.html`) for GitHub Pages to serve it correctly.

---

## 📁 File Structure

```
sha-fashion/
│
├── index.html          ← Main website file (all-in-one)
└── README.md           ← This file
```

> This is a single-file website. All CSS and JavaScript are embedded inside `index.html` — no extra files needed!

---

## 🎨 Customization

### Change Company Name
Search and replace `SHA FASHION` with your name in `index.html`.

### Change Colors
Find these CSS variables at the top of the `<style>` tag:

```css
:root {
  --red: #C0141E;        /* Main brand red */
  --red-dark: #8B0000;   /* Darker red for hover */
  --black: #0A0A0A;      /* Background black */
  --gold: #C9A84C;       /* Gold accent */
}
```

### Change Contact Info
Search for these values and replace with your own:

```
📍 Address : No. 45, Galle Road, Colombo 03
📞 Phone   : +94 77 123 4567
📧 Email   : info@shafashion.lk
```

### Add Your Language Text
The language toggle uses `data-en` and `data-si` attributes:

```html
<span data-en="Your English Text" data-si="ඔබේ සිංහල පාඨය">Your English Text</span>
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure & content |
| **CSS3** | Styling, animations, responsive layout |
| **Vanilla JavaScript** | Language toggle, scroll effects, form |
| **Google Fonts** | Playfair Display, Cormorant Garamond, Noto Sans Sinhala |
| **CSS Grid & Flexbox** | Layout system |
| **IntersectionObserver API** | Scroll-triggered animations |

> ✅ No frameworks. No npm. No build tools. Just open and go.

---

## 📞 Contact

**SHA Fashion**
- 📍 No. 45, Galle Road, Colombo 03, Sri Lanka
- 📞 +94 77 123 4567
- 📧 info@shafashion.lk
- 🕐 Mon–Sat: 8:30 AM – 7:00 PM

---

## 📄 License

© 2025 SHA Fashion. All rights reserved. | සියලු හිමිකම් ඇවිරිණි.

---

<div align="center">

Made with ❤️ in Sri Lanka 🇱🇰

**⭐ If you found this helpful, please star the repository!**

</div>
