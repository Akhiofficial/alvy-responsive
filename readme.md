# Fashion Studio Website Clone

A responsive fashion studio website clone inspired by Alvy Template, built as part of Day 23 Responsive Project from Sheriyans Coding School.

## ✨ Features

- **Fully Responsive**: Mobile-first design with desktop enhancements
- **Dark Theme**: Modern dark color scheme with elegant typography
- **Team Cards**: Interactive cards with overlay effects (no position absolute)
- **SCSS Architecture**: Organized with mixins and variables
- **Pure CSS**: No JavaScript required

## 🏗️ Project Structure
├── assets/ # Images (team cards, section images)
├── index.html # Main HTML file
├── style.scss # SCSS source
├── style.css # Compiled CSS
└── README.md # This file


## 🎨 Sections

1. **Hero Section** - Studio branding with CTA
2. **Statistics** - Client metrics and achievements  
3. **Philosophy** - Company values and approach
4. **Vision** - Mission statement and goals
5. **Team** - Three team member cards with social links

## 🛠️ Key Techniques

- **Flexbox Layout**: No absolute positioning for team cards
- **Aspect Ratio**: Consistent card proportions (`aspect-ratio: 1/1`)
- **Backdrop Filter**: Glass-morphism effects on overlays
- **Mobile-First**: Base styles for mobile, enhanced for desktop (≥900px)

## 🚀 Getting Started

1. Open `index.html` in your browser
2. For SCSS development: `sass style.scss style.css --watch`

## 📱 Responsive Breakpoints

- **Mobile**: < 900px (stacked layout)
- **Desktop**: ≥ 900px (side-by-side layouts)

## 🎨 Color Scheme

```scss
$background: rgb(24, 24, 24);      // Dark background
$text-color: rgb(222, 216, 216);   // Light text
$overlay: rgba(190, 190, 190, 0.351); // Glass effect
```

## 🔧 Customization

**Add Team Member:**
1. Add image to `assets/`
2. Create new card with unique class
3. Copy existing card SCSS pattern

**Change Colors:**
Update color values in `style.scss`

---

**Built with ❤️ | Sheriyans Coding School - Day 23 Project**