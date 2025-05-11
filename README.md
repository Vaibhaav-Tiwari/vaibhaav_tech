# Vaibhaav.tech Website

This is a static website for the domain vaibhaav.tech, based on a minimal, clean design.

## Structure

The website consists of the following main files:

- `index.html` - The homepage
- `about.html` - The about page
- `blog.html` - Blog post listing page
- `progress.html` - Progress reports listing page
- `favicons/site.webmanifest` - Web app manifest file

## Features

- Responsive design that works on all devices
- Dark/light mode toggle with user preference persistence
- Clean, minimalist aesthetic
- Fast loading (no external CSS frameworks, minimal JavaScript)
- SEO-friendly metadata
- Social media sharing metadata (Open Graph and Twitter cards)

## Setup and Deployment

### Local Development

1. Clone this repository
2. Open any of the HTML files in your browser to view them
3. Make changes as needed
4. Create a `favicons` directory and add your favicon files:
   - favicon.ico
   - favicon-16x16.png
   - favicon-32x32.png
   - apple-touch-icon.png
   - android-chrome-192x192.png
   - android-chrome-512x512.png
5. Create an `images` directory and add your social media preview image as `vaibhaav-social.png`
6. Create a `fonts` directory and add the IBM Plex Mono font:
   - Create a `woff2` subdirectory
   - Add `IBMPlexMono-Regular.woff2` to this directory

### Deployment

This is a static website that can be deployed to any web hosting service:

1. GitHub Pages:
   - Push to a GitHub repository
   - Enable GitHub Pages in the repository settings
   - Set it to deploy from your desired branch

2. Netlify:
   - Connect your GitHub repository to Netlify
   - Configure build settings (not needed for this static site)
   - Deploy

3. Vercel:
   - Import your GitHub repository
   - Configure as needed
   - Deploy

4. Traditional web hosting:
   - Upload all files to your web server via FTP
   - Ensure your domain is pointed to your hosting provider

## Customization

### Adding Content

To add new blog posts or progress reports:

1. Create new HTML files for each post/report
2. Update the respective listing pages (`blog.html` or `progress.html`) to include links to the new content

### Styling

All styling is contained within the `<style>` tags in each HTML file. To make global style changes, you'll need to update each file.

For a larger site, consider:
1. Extracting styles to a separate CSS file
2. Implementing a simple build system (like Eleventy or Jekyll)
3. Using templates for consistent layout

## License

All content is copyright of Vaibhaav.tech unless otherwise stated.

## Credits

- Design inspiration from [lelouch.dev](https://lelouch.dev) & [cneuralnetworks](cneuralnetworks.netlify.app)
- Font: [IBM Plex Mono](https://www.ibm.com/plex/) 