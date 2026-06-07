# Diddy Nightmare

A comprehensive information hub documenting significant events and developments.

**Live Site:** https://aindiancoder.github.io/Diddy-nightmare-/

## 📋 Project Overview

This project provides factual, well-sourced information about events and developments related to the Diddy situation. The site is built as an interactive timeline with resources and documentation.

## 🚀 Features

- **Interactive Timeline** - Chronological documentation of key events
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Resource Library** - Curated articles, images, and references
- **Smooth Navigation** - Easy-to-use interface with smooth scrolling
- **Modern UI** - Clean, professional design with animations

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Responsive styling with animations
- **JavaScript (Vanilla)** - Interactive features and enhancements
- **GitHub Pages** - Free hosting

## 📁 Project Structure

```
Diddy-nightmare-/
├── index.html      # Main HTML file
├── styles.css      # Styling and responsive design
├── script.js       # JavaScript functionality
├── README.md       # Project documentation
└── assets/         # (Optional) Images and media files
```

## 🎯 Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/aindiancoder/Diddy-nightmare-.git
   cd Diddy-nightmare-
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

### Deployment

The site automatically deploys to GitHub Pages when you push to the `main` branch.

## 📝 How to Add Content

### Adding Timeline Events

Edit the `index.html` file and add new timeline items:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3>Event Title</h3>
        <p class="date">Date: Month Day, Year</p>
        <p>Description of the event with sources and details.</p>
    </div>
</div>
```

### Customizing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #1a1a2e;
    --secondary-color: #16213e;
    --accent-color: #e94560;
    --text-light: #eaeaea;
    --text-dark: #333;
}
```

## 📊 Sections

1. **Home** - Introduction and call-to-action
2. **Timeline** - Chronological events
3. **About** - Project mission and information
4. **Resources** - Links to articles, galleries, references, and discussions

## 🎨 Customization

### Add a New Section

1. Add HTML in `index.html`:
```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2>Section Title</h2>
        <!-- Your content here -->
    </div>
</section>
```

2. Add CSS in `styles.css`:
```css
.new-section {
    padding: 80px 0;
    background: #fff;
}
```

3. Add navigation link in `navbar`:
```html
<li><a href="#new-section">New Section</a></li>
```

## 📱 Responsive Breakpoints

- **Desktop:** 1200px and above
- **Tablet:** 768px to 1199px
- **Mobile:** Below 768px
- **Small Mobile:** Below 480px

## 🔗 Resources & References

Add your sources and external links here:

- [Link 1](#)
- [Link 2](#)
- [Link 3](#)

## ⚖️ License

This project is open source and available under the MIT License.

## 👤 Author

**aindiancoder**
- GitHub: [@aindiancoder](https://github.com/aindiancoder)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

**Last Updated:** June 2026

*For the most current information, please visit the live site or check the latest commits.*
