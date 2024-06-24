## Shopify Theme Development Template

### Techstack
- Alpinsejs
- Tailwindcss

### Description
This template can be used to quickly start developing a shopify theme. It uses "Dawn" as the base theme. 

The setup is kept pretty simple (no rocket science). Alpine.js (v3.14.1) is downloded in /assets/alpine.js file and added in theme.liquid file from there.

Tailwindcss is added as an npm package so that it can be watched. To learn more about how it is set up, just follow the tailwindcss docs.

### Prerequisites
- Make sure Shopify CLI is installed. Just follow their docs to install it. (Note: at this moment of time, Node.js 20 doesn't work, so use Node.js 18) 


### How to start
1. Run ```npm run install``` in the root folder
2. Then run ```npm run dev``` in root folder which will watch tailwindcss changes in .liquid files
3. Then in another terminal run ```shopify theme dev --theme-editor-sync``` to start the shopify dev server
4. That's it! From now on, any changes made to .liquid files will be shown automatically to the browser.