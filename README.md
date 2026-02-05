# Playing Cards Deck 🃏

A responsive Playing Cards Deck web page built with HTML5 and CSS Flexbox.  
This project demonstrates layout control, alignment techniques, and component-based structure using modern CSS.

---

## 🎯 Project Overview

The goal of this project is to render a deck-style layout of playing cards while applying precise Flexbox alignment rules at multiple levels of the layout.

Each card is structured into logical sections and aligned using container and item-level Flexbox properties.

---

## ✨ Key Features

- Clean and semantic HTML structure
- Responsive card layout using Flexbox
- Horizontal centering with wrapping support
- Consistent spacing between cards
- Card components divided into logical regions
- Visual distinction between red and black suits
- Scalable layout that adapts to different screen sizes

---

## 🧩 Layout & Flexbox Usage

### Container (`#playing-cards`)
- `display flex`
- `justify-content center`
- `flex-wrap wrap`
- `gap 20px`

### Card (`.card`)
- Fixed width and height
- `display flex`
- `justify-content space-between`

### Card Sections
- `.left` → aligned to the start of the card
- `.middle` → centered and stacked vertically
- `.right` → aligned to the end of the card

The middle section uses
- `display flex`
- `flex-direction column`

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Flexbox
- No external libraries or frameworks

---

## 📂 Project Structure
  playing-cards
├── index.html
└── README.md  
