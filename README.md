# Nexus Playground 🚀

An interactive API explorer for the [MTEX Nexus](https://github.com/MTEXdotDev/nx.mtex.dev) JSON API gateway. Built with modern HTML5, CSS3, and vanilla JavaScript.

![API Status](https://img.shields.io/badge/API-Online-success)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- **Interactive API Testing** - Try all MTEX Nexus endpoints directly in your browser
- **Real-time Status Monitoring** - Live API health checks
- **Beautiful UI** - Modern glassmorphism design with smooth animations
- **Data Visualization** - Chart.js integration for visual data representation
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Zero Dependencies** - Pure HTML5, CSS3, and vanilla JavaScript

## 🎯 Supported Endpoints

| Endpoint | Description | Method |
|----------|-------------|--------|
| `/status` | System status & metrics | GET |
| `/user` | User test data | GET |
| `/mock` | Developer test data | GET |
| `/lorem` | Lorem posts with search | GET |
| `/utility/uuid` | UUID generator | GET |
| `/http_status` | HTTP status references | GET |

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/AI-Develops/nexus-playground.git
cd nexus-playground
```

2. Open `index.html` in your browser, or serve it using any static file server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

3. Visit `http://localhost:8000` and start exploring the API!

## 🎨 Modern CSS Features Used

- **CSS Custom Properties** - Dynamic theming and color management
- **CSS Grid** - Responsive layout system
- **Backdrop Filter** - Glassmorphism effects
- **CSS Animations** - Smooth transitions and keyframe animations
- **Modern Gradients** - Linear gradients for visual appeal
- **Flexbox** - Flexible component layouts
- **CSS Transforms** - 3D effects and animations

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with advanced features
- **JavaScript (ES6+)** - Fetch API, async/await, modern syntax
- **Chart.js** - Data visualization
- **Heroicons** - Beautiful SVG icons (embedded)

## 📁 Project Structure

```
nexus-playground/
├── index.html          # Main HTML file
├── style.css           # CSS styling with modern features
└── README.md          # This file
```

## 🌐 Live Demo

Visit the live demo: [https://ai-develops.github.io/nexus-playground/](https://ai-develops.github.io/nexus-playground/)

## 🎮 How to Use

1. **Select an Endpoint** - Click on any endpoint card
2. **Configure Parameters** - Enter optional parameters (search terms, UUID count, etc.)
3. **Try It** - Click the "Try it" button
4. **View Results** - See the JSON response and response time
5. **Visualize Data** - For applicable endpoints, view chart visualizations

## 🔧 Customization

### Changing Colors

Edit CSS variables in `style.css`:

```css
:root {
    --primary: #8b5cf6;        /* Main brand color */
    --secondary: #06b6d4;      /* Accent color */
    --bg-dark: #0f172a;        /* Background */
    /* ... more variables */
}
```

### Adding New Endpoints

1. Add a new card in `index.html`
2. Create a corresponding function in the `<script>` section
3. Style it using existing CSS classes

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📝 License

MIT License - feel free to use this project for personal or commercial purposes.

## 🙏 Acknowledgments

- [MTEX Nexus](https://github.com/MTEXdotDev/nx.mtex.dev) - The amazing API this playground is built for
- [Chart.js](https://www.chartjs.org/) - Beautiful charts
- [Heroicons](https://heroicons.com/) - Beautiful icons

## 📧 Contact

Built with ❤️ by the AI-Develops team

---

**Note:** This is a frontend-only project. The actual API is hosted at `nx.mtex.dev` and maintained by [MTEXdotDev](https://github.com/MTEXdotDev).
