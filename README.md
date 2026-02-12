# openHealthDocs
The documentation to the MIS "Open Health"

## GitHub Pages Site with Jekyll

This repository is configured as a GitHub Pages site using Jekyll. The site is built automatically when changes are pushed to the repository.

### Local Development

To run the site locally:

1. Install Ruby and Bundler (if not already installed)
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Build the site:
   ```bash
   bundle exec jekyll build
   ```
4. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```
   The site will be available at `http://localhost:4000/openHealthDocs/`

### Configuration

The site is configured in `_config.yml`. Key settings:
- **Title**: Open Health Documentation
- **Base URL**: `/openHealthDocs`
- **Theme**: minima

### Adding Content

- Blog posts go in the `_posts/` directory
- Pages can be added as `.markdown` files in the root directory
- Follow Jekyll's naming conventions for posts: `YYYY-MM-DD-title.markdown`

