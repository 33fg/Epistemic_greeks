# Epistemic Greek Project

A public website for the Epistemic Greek Project, exploring knowledge, truth, and understanding through ancient Greek philosophy and modern epistemic frameworks.

## 🚀 Quick Start

This is a static GitHub Pages site. To set it up:

### 1. Create a New GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `epistemic-greek` (or your preferred name)
3. Make it **public**
4. **Do not** initialize with README, .gitignore, or license (we already have these)

### 2. Clone and Setup

```bash
# Clone your new repository
git clone https://github.com/YOUR_USERNAME/epistemic-greek.git
cd epistemic-greek

# Copy files from this directory
cp -r /path/to/epistemic-greek-site/* .

# Or if you're already in the epistemic-greek-site directory:
cd epistemic-greek-site
git init
git add .
git commit -m "Initial commit: GitHub Pages site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/epistemic-greek.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings**
3. Scroll down to **Pages** (in the left sidebar)
4. Under **Source**, select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Click **Save**

Your site will be available at:
`https://YOUR_USERNAME.github.io/epistemic-greek/`

### 4. Update Repository Links

Before pushing, update the following files with your actual GitHub username:

- `index.html` - Replace `yourusername` with your GitHub username in:
  - GitHub repository links
  - GitHub Issues link
  - GitHub Discussions link

You can use this command to update all instances:

```bash
# Replace YOUR_USERNAME with your actual GitHub username
sed -i '' 's/yourusername/YOUR_USERNAME/g' index.html
```

## 📁 Project Structure

```
epistemic-greek-site/
├── index.html      # Main landing page
├── styles.css      # Stylesheet
├── script.js       # JavaScript for interactions
└── README.md       # This file
```

## 🎨 Customization

### Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    /* ... */
}
```

### Content

Edit `index.html` to update:
- Project description
- Research areas
- Resources
- Contact information

### Fonts

The site uses:
- **Inter** - For body text
- **Crimson Text** - For headings

You can change fonts in the `<head>` section of `index.html`.

## 🔧 Development

To preview locally:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server -p 8000

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 📝 License

Update the license information in:
- `index.html` (footer section)
- Add a `LICENSE` file if needed

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📧 Contact

Update contact information in the `#contact` section of `index.html`.

---

**Note**: Remember to replace `yourusername` with your actual GitHub username before pushing to GitHub!
