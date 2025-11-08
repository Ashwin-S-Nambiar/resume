# Ashwin's Resume

A clean, minimal, and responsive resume website built with HTML and CSS. This project showcases my professional experience, projects, education, certifications, and skills in a beautifully designed web format with dark mode support.

## Features

- **Responsive Design**: Optimized for all devices from desktop to mobile
- **Dark Mode Toggle**: Switch between light and dark themes with persistence via localStorage
- **Clean Typography**: Uses Fira Sans font for excellent readability
- **Modern Styling**: Subtle animations and hover effects with smooth theme transitions
- **Accessibility**: Semantic HTML structure and proper contrast ratios for both themes
- **Fast Loading**: Minimal dependencies and optimized assets
- **Theme Persistence**: Remembers your theme preference across browser sessions

## Live Demo

Visit the live website: [View Site](https://resume.ashwin.co.in)

## Project Structure

```
resume/
├── index.html              # Main HTML file with resume content and JavaScript
├── style.css               # Comprehensive styling with responsive design and theming
├── images/                 # Directory for images and assets
│   ├── favicon.ico         # Website favicon
│   └── organization.svg    # Company logo placeholder
├── LICENSE                 # MIT License file
└── README.md               # Project documentation
```

## Technologies Used

- **HTML5**: Semantic markup for content structure
- **CSS3**: Modern styling with Flexbox, Grid, CSS Custom Properties, and media queries
- **JavaScript**: Theme switching functionality and localStorage management
- **Google Fonts**: Fira Sans font family
- **SVG Icons**: Scalable vector graphics for logos and theme toggle icons

## Responsive Breakpoints

The website is fully responsive with optimized layouts for:

- **Desktop**: 1024px and above
- **Tablets**: 768px - 1024px
- **Mobile Large**: 640px - 768px
- **Mobile Medium**: 480px - 640px
- **Mobile Small**: 360px - 480px
- **Mobile XS**: Below 360px

## Design Features

### Layout
- Flexible grid system for projects and skills sections
- Consistent spacing and typography
- Adaptive color scheme with CSS custom properties for light and dark themes

### Interactive Elements
- Dark/Light mode toggle with smooth transitions
- Theme preference persistence using localStorage
- Hover effects on links and buttons
- Smooth transitions and animations
- Theme toggle button with responsive positioning

### Theme Support
- **Light Theme**: Clean white background with blue accent colors
- **Dark Theme**: Dark background (#1a1a1a) with light text and blue accent colors
- **Smart Contrast**: Optimized text and background contrast ratios for both themes

## Getting Started

### Prerequisites

- A modern web browser
- Basic text editor (VS Code recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Ashwin-S-Nambiar/resume.git
```

2. Navigate to the project directory:
```bash
cd resume
```

3. Open `index.html` in your web browser or set up a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

4. Visit `http://localhost:8000` in your browser

## Customization

### Content Updates
1. Open `index.html` in your preferred editor
2. Update the personal information, work experience, projects, and skills
3. Replace placeholder images in the `images/` directory
4. Save and refresh your browser

### Styling Changes
1. Open `style.css` to modify colors, fonts, or layout
2. The CSS is well-commented and organized by sections
3. Use CSS custom properties at the top of the file to modify theme colors
4. Media queries are included for responsive adjustments

### Theme Customization
1. Modify the CSS custom properties in the `:root` and `[data-theme="dark"]` selectors
2. Update `--bg-color`, `--text-color`, `--link-color`, etc. to your preferred colors
3. The theme system automatically applies changes to both light and dark modes
4. Ensure proper contrast ratios for accessibility

### Adding New Sections
1. Follow the existing HTML structure patterns
2. Add corresponding CSS styles using the theme variables
3. Ensure responsive design is maintained
4. Test in both light and dark themes

## Dark Mode

The website features a comprehensive dark mode implementation:

### Features
- **Toggle Button**: Positioned in the top-right corner next to the print button
- **Smart Icons**: Sun icon for switching to dark mode, moon icon for switching to light mode
- **Persistence**: Theme preference is saved in localStorage and persists across browser sessions
- **Smooth Transitions**: All color changes are animated with CSS transitions

### Usage
- Click the theme toggle button in the top-right corner
- Your preference will be automatically saved
- The page will remember your choice when you return

### Implementation
- Uses CSS custom properties (CSS variables) for easy theme switching
- JavaScript handles theme detection, switching, and localStorage management
- Responsive design ensures toggle button works on all screen sizes

## Sections Included

- **Header**: Name, title, and contact information
- **About**: Professional summary
- **Work Experience**: Current and previous positions
- **Projects**: Showcased development projects
- **Education**: Academic background
- **Certifications**: Professional certifications
- **Skills**: Technical skills organized by category
- **Interactive Elements**: Dark/Light mode toggle and print functionality

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contact

**Ashwin S Nambiar**
- Email: [ashwinnambiar12345@gmail.com](mailto:ashwinnambiar12345@gmail.com)
- GitHub: [github.com/Ashwin-S-Nambiar](https://github.com/Ashwin-S-Nambiar)
- Website: [ashwin.co.in](https://ashwin.co.in)

## Contributing

Feel free to fork this project and customize it for your own resume. If you have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) for details.

---
<div align="center">
  
**Made with ❤️ by Ashwin S Nambiar**
</div>
