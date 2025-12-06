# Deepak Paswan - Portfolio Website

A modern, responsive portfolio website showcasing my projects, skills, and social media links. Perfect for sharing on LinkedIn, Instagram, and other social media platforms.

## 🌟 Features

- **Modern Design**: Beautiful gradient-based UI with smooth animations
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **GitHub Integration**: Automatically fetches and displays your latest repositories
- **Social Media Links**: Easy access to GitHub, LinkedIn, and Instagram
- **Smooth Animations**: Engaging scroll effects and transitions
- **Fast Loading**: Optimized for performance

## 🚀 Getting Started

### Option 1: Direct Use (No Server Required)

Simply open `index.html` in your web browser. The website will work, but GitHub API calls might be limited due to CORS restrictions.

### Option 2: Local Server (Recommended)

For the best experience with GitHub API integration:

1. **Using Python** (if installed):
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```

2. **Using Node.js** (if installed):
   ```bash
   npx http-server
   ```

3. **Using VS Code**:
   - Install the "Live Server" extension
   - Right-click on `index.html` and select "Open with Live Server"

4. Open your browser and navigate to `http://localhost:8000`

### Option 3: Deploy Online

You can deploy this website to:
- **GitHub Pages**: Free hosting for static sites
- **Netlify**: Drag and drop deployment
- **Vercel**: Fast deployment with GitHub integration
- **Any static hosting service**

## 📁 File Structure

```
portfolio-website/
│
├── index.html      # Main HTML structure
├── styles.css      # All styling and responsive design
├── script.js       # JavaScript for interactivity and GitHub API
└── README.md       # This file
```

## 🎨 Customization

### Update Your Information

1. **GitHub Username**: Edit `script.js` and change `GITHUB_USERNAME` variable
2. **Social Media Links**: Update links in `index.html`:
   - GitHub: Line with `href="https://github.com/dpkpaswan"`
   - LinkedIn: Line with `href="https://www.linkedin.com/in/deepakpaswan1"`
   - Instagram: Line with `href="https://www.instagram.com/dpkpaswan"`

### Change Colors

Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;    /* Main color */
    --secondary-color: #8b5cf6;  /* Secondary color */
    --accent-color: #ec4899;      /* Accent color */
}
```

### Modify Content

- **About Section**: Edit the text in the `#about` section of `index.html`
- **Skills**: Update the skill tags in the about section
- **Statistics**: Modify the numbers in `script.js` (animateStats function)

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)**: Dynamic content loading and interactivity
- **GitHub API**: Fetching repository information
- **Font Awesome**: Icons

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 Notes

- The website uses the GitHub API to fetch your repositories. If you have many repositories, only the 6 most recently updated ones will be displayed.
- Make sure your GitHub repositories are public if you want them to appear on the website.
- For production use, consider adding error handling and loading states.

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!

## 📄 License

This project is open source and available for personal use.

---

**Made with ❤️ by Deepak Paswan**

For questions or suggestions, reach out via [LinkedIn](https://www.linkedin.com/in/deepakpaswan1) or [GitHub](https://github.com/dpkpaswan).

