## 1. Getting Started

NOTE: npm commands overwrite the ./public directory.

Project's source files are placed in ./src/ directory. 
* ./src/assets - default static files (eg. image placeholders). You should replace them with your own files.
* ./src/tailwind/ - Tailwind config file used to build the theme. Variables used in Theme Customizer are located in tailwind.config.js file.

All your pages (templates) are stored in separated .pug files
* ./src/pug/*.pug 

## 2. Installation

```
# Install dependencies
npm install 

# Run dev server with live preview (Browsersync)
npm run watch

# Or make a production build 
npm run build
```
