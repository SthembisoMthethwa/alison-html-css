# Asus Laptops — Practice Website

A single-page website built while learning HTML, CSS, and Git through an Alison course. This project was used as a hands-on way to practice front-end fundamentals and version control at the same time — every major milestone was committed to Git as the site was built.

## 🔗 Live Structure

A one-page site with smooth-scroll navigation between three sections: Home, About, and Laptops.

## 🛠️ Built With

- **HTML5** — semantic structure (`header`, `nav`, `main`, `section`, `footer`)
- **CSS3** — Flexbox layout, responsive card wrapping, sticky navigation, background images with overlays
- **Font Awesome** — social media icons (via CDN)
- **Git & GitHub** — version control, tracked from the very first commit

## ✨ Features

- Sticky navigation bar that stays visible while scrolling
- Full-viewport-height Home and About sections
- Two-column About layout (image + text) using Flexbox
- Responsive product card grid for laptop listings — cards wrap onto new rows automatically as the screen narrows, using `flex-wrap`
- Six laptop listings across two rows, each with image, name, description, and price
- Social media links (Facebook, Instagram, YouTube, WhatsApp) styled with Font Awesome icons
- Smooth scroll behavior between sections
- Clickable `mailto:` and WhatsApp deep links in the footer

## 📚 What I Learned

- Structuring a page with semantic HTML rather than generic `<div>`s
- The CSS box model, and why `box-sizing: border-box` avoids layout headaches
- Flexbox: `display: flex`, `justify-content`, `align-items`, `gap`, and `flex-wrap` for responsive layouts without media queries
- Positioning techniques: `position: relative`/`absolute` for overlay effects, `position: sticky` for a persistent navbar, and `z-index` for stacking order
- Using `object-fit: cover` vs CSS `background-size: cover` for controlling image cropping in different contexts
- Git fundamentals: `init`, `add`, `commit`, `remote`, `push`, fixing commit authorship, and switching between SSH and HTTPS remotes
- The importance of consistent, lowercase, hyphenated naming for files and CSS classes to avoid case-sensitivity bugs (especially between local Windows filesystems and GitHub)

## 🚀 Running Locally

1. Clone the repo: git clone https://github.com/SthembisoMthethwa/alison-html-css.git
2.   Open the folder in VSCode
3. Open `index.html` in a browser, or use the **Live Server** extension for auto-reload while editing

## 📌 Status

Actively being built as part of an ongoing HTML/CSS course.
