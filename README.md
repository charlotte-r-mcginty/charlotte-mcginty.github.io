# charlotte-mcginty.github.io

My personal blog and portfolio site built with Jekyll.

## Setup & Development

### Prerequisites
- Ruby 2.5.0 or higher
- Bundler

### Local Development

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Run the Jekyll development server:
   ```bash
   bundle exec jekyll serve
   ```

3. View at `http://localhost:4000`

### Adding Your Photo

1. Create `assets/images/` directory if it doesn't exist
2. Add your profile photo as `assets/images/profile.jpg`
3. Update the image path in `about.md` if needed

### Customization

- Edit `_config.yml` to update your site title, description, and social links
- Edit `about.md` to update your bio and information
- Add blog posts in the `_posts/` directory with the format `YYYY-MM-DD-title.md`

## Deployment

This site is automatically deployed to GitHub Pages when you push to the main branch.
