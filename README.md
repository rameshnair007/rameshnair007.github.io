# Ramesh Nair - Personal Website

A modern, responsive personal website and portfolio built with Jekyll and hosted on GitHub Pages. Showcasing my work, research, and professional journey in machine learning and computer vision.

## ✨ Features

- **Modern & Responsive Design**: Clean, mobile-friendly layout that works on all devices
- **Content-Rich Sections**:
  - Professional background and skills
  - Detailed project showcases with descriptions and outcomes
  - Research publications and technical reports
  - Easy contact information with social media integration
- **Technical Highlights**:
  - Built with Jekyll for static site generation
  - Custom CSS with modern design principles
  - SEO optimized with `jekyll-seo-tag`
  - RSS feed support via `jekyll-feed`
  - Font Awesome icons for enhanced visual elements

## 🚀 Getting Started

### Prerequisites

- Ruby (version 2.5.0 or higher)
- RubyGems
- GCC and Make

### Local Development

1. **Install Jekyll and Bundler**
   ```bash
   gem install jekyll bundler
   ```

2. **Clone the repository**
   ```bash
   git clone https://github.com/rameshnair007/rameshnair007.github.io.git
   cd rameshnair007.github.io
   ```

3. **Install dependencies**
   ```bash
   bundle install
   ```

4. **Run the development server**
   ```bash
   bundle exec jekyll serve
   ```

5. **Open your browser** and visit `http://localhost:4000`

## 🛠 Project Structure

```
.
├── _config.yml       # Site configuration
├── _layouts/         # HTML templates
├── assets/           # Static files
│   ├── css/          # Custom styles
│   └── images/       # Images and icons
├── _includes/        # Reusable components
├── _sass/            # SASS partials
├── _site/            # Generated site (not in version control)
├── about.md          # About page
├── contact.md        # Contact information
├── index.html        # Homepage
├── projects.md       # Projects showcase
├── publications.md   # Research publications
└── research.md       # Research work
```

## 📝 Updating Content

### Personal Information
- Update `_config.yml` for site-wide settings
- Modify `index.html` for the landing page content
- Edit `about.md` for your professional bio

### Projects & Research
- Edit `projects.md` to showcase your work
- Update `research.md` with your research focus
- Add publications to `publications.md`

### Styling
- Customize colors and fonts in `assets/css/style.css`
- Update the navigation in `_config.yml`

## 🚀 Deployment

This site is configured for GitHub Pages deployment:

1. Push your changes to the `main` branch
2. GitHub Pages will automatically build and deploy the site
3. Your site will be live at `https://<your-username>.github.io`

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

If you find any issues or have suggestions, feel free to open an issue or submit a pull request.

## 📬 Contact

For any questions or collaboration opportunities, feel free to reach out through the contact page.

MIT License
