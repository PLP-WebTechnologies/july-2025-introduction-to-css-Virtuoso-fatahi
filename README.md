[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/RyEig_hB)

# 🎨 Introduction to CSS: Social Links Profile

## Overview

This project demonstrates foundational CSS concepts and the Box Model by building a visually appealing social links profile page. The page showcases a profile image, name, location, bio, and a set of styled social links, all using custom CSS.

## Features

- **External CSS Styling:** All styles are defined in [`styles.css`](july-2025-introduction-to-css-Virtuoso-fatahi/styles.css) and linked from [`index.html`](july-2025-introduction-to-css-Virtuoso-fatahi/index.html).
- **Box Model Usage:** The layout uses margin, padding, border-radius, and box-shadow to illustrate the CSS Box Model.
- **Responsive & Centered Layout:** The profile card is centered and adapts to different screen sizes.
- **Custom Fonts:** Uses the Inter font from Google Fonts for modern typography.
- **Profile Image:** Circular avatar with centered alignment.
- **Styled Social Links:** Interactive buttons for GitHub, Portfolio, LinkedIn, Twitter, and Behance, with hover effects.

## File Structure

```
july-2025-introduction-to-css-Virtuoso-fatahi/
│
├── index.html         # Main HTML file
├── styles.css         # External CSS stylesheet
├── README.md          # Project documentation
└── assets/
    └── images/
        └── avatar-fatahi.png  # Profile image
```

## How It Works

- **HTML Structure:**  
  The main content is wrapped in a `<main class="container">` for layout.  
  - `.profile-image`: Displays the avatar.  
  - `.profile-header`: Shows name, location, and bio.  
  - `.profile-link`: Contains social link buttons.

- **CSS Highlights:**  
  - Universal selector sets `box-sizing: border-box` for predictable sizing.
  - `.container` uses margin, padding, border-radius, and box-shadow for a card effect.
  - `.profile-image img` is styled as a circle.
  - `.btn` class styles links as block-level buttons with hover transitions.

## Usage

1. **Clone or Download** the repository.
2. Open [`index.html`](july-2025-introduction-to-css-Virtuoso-fatahi/index.html) in your browser.
3. Ensure [`styles.css`](july-2025-introduction-to-css-Virtuoso-fatahi/styles.css) and the avatar image are present in the correct paths.

## Customization

- Replace `avatar-fatahi.png` in `assets/images/` with your own image if desired.
- Edit the social links in [`index.html`](july-2025-introduction-to-css-Virtuoso-fatahi/index.html) to point to your profiles.

## Learning Outcomes

- Linking external CSS to HTML.
- Using selectors and basic properties: `color`, `font-size`, `margin`, `padding`, `border`, `background`.
- Applying the CSS Box Model for layout and spacing.
- Writing clean, maintainable CSS.
