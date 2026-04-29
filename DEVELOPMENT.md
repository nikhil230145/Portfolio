# 📖 Development Guide

## 📋 Table of Contents
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Deployment](#deployment)
- [Troubleshooting](#troubleshooting)

## 🚀 Getting Started

### Prerequisites
- Text editor (VS Code, Sublime, etc.)
- Git
- Basic knowledge of HTML, CSS, JavaScript
- Modern web browser

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/nikhil230145/Portfolio.git
   cd Portfolio
   ```

2. **Start a local server** (Choose one)
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (http-server)
   npx http-server
   
   # Using Node.js (live-server)
   npx live-server
   ```

3. **Open in browser**
   - Navigate to `http://localhost:8000`

## 📁 Project Structure

```
Portfolio/
├── index.html              # Main HTML file
├── css/
│   └── styles.css         # Main stylesheet
├── js/
│   └── script.js          # JavaScript functionality
├── assets/
│   ├── images/            # Portfolio images
│   ├── icons/             # Icon files
│   └── favicon.ico        # Website favicon
├── README.md              # Project documentation
├── CONTRIBUTING.md        # Contribution guidelines
├── LICENSE                # MIT License
└── .gitignore             # Git ignore rules
```

## 🎨 Customization

### Update Personal Information

Edit `index.html`:
- Replace "Nikhil" with your name
- Update email in contact section
- Update social media links
- Modify project descriptions
- Update skills and percentages

### Customize Colors

Edit `css/styles.css` - Update CSS variables:
```css
:root {
  --primary-color: #0066cc;        /* Main color */
  --secondary-color: #00875a;      /* Accent color */
  --accent-color: #ff6b6b;         /* Highlight color */
  --bg-color: #f5f5f5;             /* Background */
  --card-bg: #ffffff;              /* Card background */
  --text-color: #1a1a1a;           /* Text color */
  --text-muted: #666666;           /* Muted text */
  --border-color: #e0e0e0;         /* Border color */
}
```

### Add Your Projects

1. Open `index.html`
2. Find the "Featured Projects" section
3. Copy a project card and modify:
   - Project icon emoji
   - Project title
   - Project description
   - Technologies used
   - Project link

Example:
```html
<article class="project-card">
  <div class="project-icon">🚀</div>
  <h3>My Amazing Project</h3>
  <p>Description of your project and what it does.</p>
  <div class="project-tags">
    <span class="tag">HTML</span>
    <span class="tag">CSS</span>
  </div>
  <a href="https://your-project-link.com" class="btn btn-secondary">
    View Project →
  </a>
</article>
```

### Update Skills

Edit skills percentages in `index.html`:
```html
<div class="skill-header">
  <span>Your Skill</span>
  <span class="skill-percent">80%</span>
</div>
<div class="skill-bar">
  <div class="skill-progress" style="width: 80%"></div>
</div>
```

### Add Profile Image

1. Place your image in `assets/images/`
2. Add to HTML (optional enhancement)
3. Reference in CSS or HTML

## 🚀 Deployment

### Deploy on GitHub Pages

1. **Settings in GitHub**
   - Go to repository settings
   - Scroll to "Pages" section
   - Select "main" branch
   - Click "Save"

2. **Access your portfolio**
   - URL: `https://nikhil230145.github.io/Portfolio`
   - May take 1-2 minutes to appear

### Deploy on Other Platforms

- **Netlify**: Drag and drop your files
- **Vercel**: Connect GitHub repository
- **Heroku**: Use Procfile for deployment
- **Firebase**: Use Firebase Hosting
- **Custom Domain**: Update DNS records

## 🔧 Troubleshooting

### Local Server Not Working
- Ensure you're in the correct directory
- Try a different port: `python -m http.server 9000`
- Check if port is already in use

### Styles Not Loading
- Clear browser cache (Ctrl+Shift+Delete)
- Hard refresh (Ctrl+Shift+R)
- Check file paths are correct

### JavaScript Not Working
- Open browser console (F12)
- Check for errors
- Verify script.js path in HTML

### GitHub Pages Not Updating
- Wait 2-3 minutes
- Clear browser cache
- Hard refresh the page
- Check branch is set to "main"

### Image Not Loading
- Verify image path is correct
- Check file name case sensitivity
- Ensure image format is supported (jpg, png, gif, webp)

## 📝 Best Practices

1. **Version Control**
   - Commit frequently with clear messages
   - Use branches for new features
   - Create pull requests for changes

2. **Code Quality**
   - Keep HTML semantic
   - Use meaningful class names
   - Comment complex code
   - Test across browsers

3. **Performance**
   - Optimize images
   - Minimize CSS/JS
   - Use lazy loading
   - Remove unused code

4. **Accessibility**
   - Use semantic HTML
   - Add alt text to images
   - Ensure keyboard navigation
   - Use proper color contrast

5. **Security**
   - Keep dependencies updated
   - Don't commit sensitive data
   - Validate user input
   - Use HTTPS for production

## 🎓 Learning Resources

- [MDN Web Docs](https://developer.mozilla.org)
- [CSS-Tricks](https://css-tricks.com)
- [JavaScript.info](https://javascript.info)
- [Web Accessibility](https://www.w3.org/WAI)
- [Git Documentation](https://git-scm.com/doc)

## 📞 Need Help?

- Check existing issues
- Create a new issue
- Review documentation
- Check browser console for errors

---

Happy coding! 🎉
