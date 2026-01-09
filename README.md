# 🟡 Pac-Man Loader Animation

A nostalgic Pac-Man inspired loading animation featuring the iconic character chomping on dots. This pure CSS animation brings the classic arcade game to life with smooth movements and perfect timing.

## ✨ Features

### Visual Effects
- **Animated Pac-Man**: Classic yellow Pac-Man with chomping mouth animation
- **Moving Dots**: Four orange dots that Pac-Man appears to eat
- **Smooth Motion**: Fluid animation with perfect timing
- **Color Scheme**: Authentic Pac-Man yellow and orange colors
- **Clean Design**: Minimalist, focused animation

### Animation Details
- **Mouth Movement**: Pac-Man's mouth opens and closes continuously
- **Dot Animation**: Dots appear to move and be consumed
- **Sequential Timing**: Coordinated animation between Pac-Man and dots
- **Infinite Loop**: Continuous loading animation
- **CSS Variables**: Dynamic color and timing control

## 🛠 Tech Stack

### Pure CSS Technologies
- **HTML5** - Simple semantic structure
- **CSS3** - All animations and visual effects
- **CSS Animations** - `@keyframes` for character movement
- **CSS Variables** - `--clr` and `--i` for dynamic properties
- **CSS Transforms** - Rotation and positioning

### CSS Features Demonstrated
- **Animation Properties** - Complex keyframe sequences
- **Transform Origin** - Rotation pivot points
- **CSS Variables** - Dynamic property usage
- **Positioning** - Absolute positioning for layering
- **Border Radius** - Creating circular shapes

## 🚀 Quick Start

### Method 1: Direct File Opening
```bash
# Navigate to the Packman-Loader directory
cd Packman-Loader

# Open index.html in your default browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

### Method 2: Local Web Server
```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js
npx http-server

# Then visit http://localhost:8000
```

## 📁 Project Structure

```
Packman-Loader/
├── index.html          # Pac-Man and dots structure
├── style.css          # All animations and styling
└── README.md          # This file
```

## 🎯 Animation Breakdown

### Pac-Man Structure
```html
<div class="packman">
    <div class="top__part"></div>
    <div class="bottom__part"></div>
</div>
```

### Dots Configuration
```html
<div class="block__dots">
    <span style="--clr: orange; --i: 1;"></span>
    <span style="--clr: orange; --i: 2;"></span>
    <span style="--clr: orange; --i: 3;"></span>
    <span style="--clr: orange; --i: 4;"></span>
</div>
```

## 🎨 Design Elements

### Color Scheme
- **Pac-Man**: Classic yellow (`#ffff00` or similar)
- **Dots**: Orange (`orange`)
- **Background**: Dark for contrast
- **Visual Style**: Retro arcade aesthetic

### Animation Timing
- **Pac-Man Chomping**: Continuous mouth movement
- **Dot Movement**: Sequential disappearance
- **Loop Duration**: Optimized for loading effect
- **Variable Delays**: `--i` property for staggered timing

## 🔧 Technical Implementation

### Component Structure
- **Container**: Main positioning context
- **Pac-Man**: Animated character with two parts
- **Dots**: Individual animated elements
- **Variables**: CSS custom properties for control

### Animation Techniques
- **Rotation**: Mouth opening/closing effect
- **Opacity**: Dot disappearance animation
- **Transform**: Movement and scaling effects
- **Timing Functions**: Smooth, realistic motion

## 🌟 Learning Opportunities

This project is perfect for learning:
- **CSS Animations**: Complex character animation
- **CSS Variables**: Dynamic property usage
- **Retro Design**: Classic arcade aesthetics
- **Animation Timing**: Coordinated multi-element animations
- **Pure CSS**: No JavaScript required
- **Creative Problem Solving**: Creating complex effects with CSS

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers

## 🎯 Use Cases

### Applications
- **Loading Screens**: Perfect for game or app loading
- **Retro Websites**: Gaming or nostalgia-themed sites
- **Progress Indicators**: Fun alternative to spinners
- **Educational Projects**: CSS animation demonstrations
- **Portfolio Pieces**: Showcasing CSS skills

### Customization Options
- **Colors**: Change `--clr` variable values
- **Speed**: Adjust animation durations
- **Size**: Scale the entire animation
- **Dot Count**: Add or remove dot elements
- **Background**: Update background color

---

**Made with ❤️ and retro gaming nostalgia** 🟡

Enjoy this classic Pac-Man animation that brings the beloved arcade character to life through pure CSS magic!
