# Portfolio Site

A modern, responsive portfolio website built with HTML, CSS, and vanilla JavaScript.

## Features

- Clean, modern design with grey, ash, and brown color scheme
- Fully responsive (mobile, tablet, desktop)
- Multiple project showcase
- Image placeholder frames ready for your images
- Smooth scrolling and animations
- Contact form

## GitHub Pages Setup

To deploy this site on GitHub Pages:

1. **Create a GitHub repository** (or use an existing one)
   - Repository name can be anything (e.g., `portfolio`, `my-portfolio`)

2. **Push your files to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under **Source**, select **Deploy from a branch**
   - Choose **main** branch and **/ (root)** folder
   - Click **Save**

4. **Access your site**
   - Your site will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`
   - It may take a few minutes for the site to be live

## File Structure

```
portfolio_site/
├── index.html                 # Main portfolio page
├── project-hr-warehouse.html  # HR Data Warehouse project detail page
├── styles.css                 # All styling
├── script.js                  # JavaScript functionality
└── README.md                  # This file
```

## Customization

- Replace image placeholders with your actual images
- Update project information in `index.html`
- Modify colors in `styles.css` (CSS variables at the top)
- Add more project detail pages following the `project-hr-warehouse.html` template

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal use.
