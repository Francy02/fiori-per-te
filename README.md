# Fiori per Te - Animated Flowers

A beautiful, interactive web application featuring animated flowers with glowing lights and night sky effects. This project creates a serene visual experience with CSS animations and is dedicated with love.

## Overview

**Fiori per Te** (Flowers for You) is a responsive web application that showcases elegantly animated flowers set against a starry night background. The project demonstrates advanced CSS animation techniques combined with smooth transitions and visual effects.

## Features

- **Animated Flowers**: Multiple flowers with smooth blooming and swaying animations
- **Glowing Lights**: Dynamic light effects around flower petals creating a magical atmosphere
- **Night Sky Background**: Beautiful gradient background with starfield patterns simulating a night sky
- **Smooth Transitions**: Loading animation that gradually reveals the scene
- **Responsive Design**: Optimized viewing experience across different screen sizes
- **Modern CSS Animations**: Complex keyframe animations for realistic flower movement and growth

## Project Structure

```
fiori-per-te-main/
├── index.html      # Main HTML structure with flower elements
├── style.css       # Comprehensive CSS including animations and styling
├── script.js       # JavaScript for page loading effects
└── README.md       # Project documentation
```

## Files Description

### index.html
Contains the semantic HTML structure defining:
- Three distinct flower elements with varying designs
- All necessary leaves, petals, and light elements
- Proper semantic markup for accessibility

### style.css
Comprehensive stylesheet featuring:
- Complete flower styling and positioning
- Keyframe animations for blooming and movement effects
- Night sky background with gradient and pattern effects
- Responsive scaling and transform effects
- Animation timings and delays for sequential effects

### script.js
Lightweight JavaScript handling:
- Page load detection
- Removal of the `not-loaded` class to trigger initial animations
- Smooth transition from loading state to fully rendered state

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. Clone or download the project:
```bash
git clone https://github.com/yourusername/fiori-per-te-main.git
cd fiori-per-te-main
```

2. Open the application:
Simply open `index.html` in your web browser.

```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

## Customization

You can easily customize the appearance:

- **Colors**: Modify CSS variables and gradient values in `style.css`
- **Animation Speed**: Adjust `--fl-speed` variable and keyframe durations
- **Flower Count**: Duplicate flower elements in `index.html` and create corresponding CSS rules
- **Background**: Customize the `.night` class styling for different sky effects

## Browser Compatibility

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Mobile browsers: Full support with responsive scaling

## Performance

The application is optimized for performance:
- Uses CSS-only animations (GPU accelerated)
- Minimal JavaScript footprint
- Efficient use of transforms and opacity for smooth 60fps animations

## License

This project is open source and available for personal and educational use.

## Author

Created as a heartfelt dedication with love

## Contributing

Contributions and improvements are welcome! Feel free to submit pull requests or suggest enhancements.

---

**Enjoy the beauty of Fiori per Te!** 
