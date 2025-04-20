# Portfolio for Mohammad Alassiri

This is a Jekyll-based personal portfolio website, ready for deployment on GitHub Pages with a custom domain (alassiri.nl).

## Features
- Clean, modern design
- Homepage, About, Projects, and Contact sections
- Easy deployment to GitHub Pages
- Custom domain support

## Setup & Deployment

1. **Install dependencies:**
   ```sh
   bundle install
   ```
2. **Serve locally:**
   ```sh
   bundle exec jekyll serve
   ```
   Visit `http://localhost:4000` to preview.
3. **Deploy to GitHub Pages:**
   - Push your code to the `main` or `gh-pages` branch of your GitHub repository.
   - In your repo settings, enable GitHub Pages and set the branch to `main` (or `gh-pages`).
   - Add your custom domain (`alassiri.nl`) in the GitHub Pages settings.
   - Ensure the `CNAME` file contains `alassiri.nl`.
4. **DNS Setup:**
   - Point your domain's DNS A record to GitHub Pages IPs or use a CNAME record as per GitHub Pages documentation.

## Customization
- Edit `_config.yml` for site settings.
- Update `index.markdown`, `about.markdown`, and add project/contact content as needed.
- Add posts in the `_posts/` directory.

---

For more, see the [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages).
