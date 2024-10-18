# Bang Bang Bunny Website

This is the official website for Bang Bang Bunny, a punk rap band. The site is built using Jekyll and is based on the [Clean Blog Jekyll](https://startbootstrap.com/themes/clean-blog-jekyll/) theme.

## Features

- Responsive design optimized for mobile devices
- Home page with YouTube video embed and Instagram feed
- About page with image slider
- Blog posts page
- Contact form with Formspree integration and reCAPTCHA
- Social media links (Facebook, Instagram)
- Custom color scheme matching the band's branding

## Installation & Setup

1. Clone this repository
2. Install Jekyll and Bundler if you haven't already:
   ```
   gem install jekyll bundler
   ```
3. Install dependencies:
   ```
   bundle install
   ```
4. Run the site locally:
   ```
   bundle exec jekyll serve
   ```

## Configuration

Main settings can be configured in `_config.yml`:

- Site title and description
- Social media links
- Formspree ID for contact form
- reCAPTCHA site key

## Content Management

- Blog posts are stored in the `_posts` directory
- Pages are in the root directory (e.g., `about.html`, `contact.html`)
- Images are stored in the `img` directory

## Custom Styles

Custom styles are added in `_sass/styles.scss`. This includes:

- Mobile navigation menu
- Custom button colors
- Responsive iframe for Bandcamp embed

## Deployment

The site is set up to deploy to GitHub Pages. Push changes to the `main` branch to trigger a deployment.

## Third-party Integrations

- YouTube for video embed
- Instagram feed (using Elfsight widget)
- Spotify artist embed
- Formspree for contact form
- reCAPTCHA for form protection

## Contributing

This is a private project for Bang Bang Bunny. If you're a band member or authorized contributor, please create a pull request for any changes.

## License

This project is private and not open for public use or distribution.
