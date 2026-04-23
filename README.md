# 🎠 Crazy Effects Image Slider

> Crazy Effects Image Slider built with pure HTML, CSS & JavaScript — auto-play, thumbnails, animations, countdown bar, fully responsive.

## ✨ Features

- **Auto Play** — Slides automatically switch every 5 seconds
- **Countdown Progress Bar** — Visual timer bar shows remaining time before next slide
- **Next / Prev Buttons** — Manual navigation with smooth direction-aware animations
- **Thumbnail Navigation** — Click any thumbnail to jump directly to that slide
- **Crazy Zoom Animations** — Next slides zoom in from right, Prev slides from left
- **Staggered Content Animation** — Tag, title, description, and buttons fade in with delay
- **Slide Counter** — Live current / total indicator
- **Keyboard Support** — Arrow keys navigate slides
- **Infinite Loop** — Never runs out of slides
- **Fully Responsive** — Works on all screen sizes

---

## 📁 Project Structure

```
slider/
│
└── slider.html       # All-in-one file (HTML + CSS + JS)
```

No external dependencies. No build tools. Just open and run.

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/crazy-effects-slider.git
cd crazy-effects-slider
```

### 2. Open in browser

```bash
# Simply open the file
open slider.html
```

Or just double-click `slider.html` in your file explorer.

---

## 🖼️ Customization

### Change Slides

In `slider.html`, find the `.list` section and update each `.item`:

```html
<div class="item">
  <img class="bg" src="YOUR_IMAGE_URL" alt="Description"/>
  <div class="content">
    <div class="tag">Your Tag</div>
    <h2>Your<br>Title</h2>
    <p>Your description text here.</p>
    <div class="btns">
      <button class="btn-primary">CTA Button</button>
      <button class="btn-outline">Secondary</button>
    </div>
  </div>
</div>
```

Also update the matching thumbnail:

```html
<div class="item"><img src="YOUR_THUMBNAIL_URL" alt="Description"/></div>
```

### Change Auto-Play Speed

Find this line in the JavaScript section:

```js
const AUTO_TIME = 5000; // milliseconds (5 seconds)
```

Change `5000` to any value you want.

Also update the CSS variable to match:

```css
--timer-duration: 5s; /* Match AUTO_TIME value */
```

### Change Accent Color

```css
:root {
  --accent: #ff4d4d; /* Change to any color */
}
```

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `→` or `↓` | Next slide |
| `←` or `↑` | Previous slide |

---


