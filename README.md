# Starting Block

A modern WordPress starter theme for developers.

## What's in the theme?
1. **Ultra-Minimal CLI-Based Build System**
   - Direct Sass CLI compilation with sourcemaps
   - PostCSS autoprefixing
   - Browser Sync for live reloading
   - No task runner bloat - just npm scripts!
2. **Underscores Foundation**
   - Clean, semantic HTML5 structure
   - Accessibility ready
   - Translation ready
3. **Modern CSS**
   - Normalize.css for browser consistency
   - CSS Grid for layouts
   - Mobile-first responsive design
   - SASS with organized partials

## Getting Started
1. Start with a fresh WordPress install
2. Clone this repository into your themes folder
3. Run `npm install` to install build dependencies
4. Update the proxy URL in the `serve` script in `package.json` to match your local development URL
5. Run `npm start` to start development (Sass watching + browser sync)
6. Create a new home page in WordPress admin and apply the home template
7. In WordPress admin, go to Settings > Reading, and set "Your homepage displays" to "A static page" using your new homepage