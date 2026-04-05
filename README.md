# Custom Keyboard Shop

A simple, lightweight keyboard gallery site built with Alpine.js and Tailwind CSS.

## Features

- ✨ Product gallery with filtering and search
- 🔍 Click any keyboard to view full details in a modal
- 📱 Fully responsive design
- 🎨 Clean, modern UI with Tailwind CSS
- ⚡ Zero build process - just HTML, Alpine.js, and Tailwind CDN

## Getting Started

1. Add your keyboard photos to the `images/` folder
2. Edit the `keyboards` array in `index.html` (around line 203) with your keyboard details
3. Open `index.html` in a browser to preview
4. Deploy to any static hosting (Netlify, Vercel, GitHub Pages, etc.)

## Customizing Your Keyboards

Find the `keyboards` array in the `<script>` section and update with your details:

```javascript
keyboards: [
    {
        id: 1,
        name: 'Your Keyboard Name',
        category: '60%',  // Options: 60%, 75%, TKL, Full Size
        price: 180,
        description: 'Describe your keyboard...',
        image: 'images/your-photo.jpg',
        switches: 'Cherry MX Blue',
        keycaps: 'PBT Double-Shot',
        caseMaterial: 'Aluminum',
        available: true  // Set to false when sold
    },
    // Add more keyboards...
]
```

## Deploying

### Netlify (Easiest)
1. Drag and drop the `keyboard-shop` folder to netlify.com/drop
2. Done! You'll get a live URL instantly

### GitHub Pages
1. Create a GitHub repo
2. Push this folder
3. Enable GitHub Pages in repo settings
4. Your site will be live at `username.github.io/repo-name`

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this folder
3. Follow prompts

## Tips

- Use placeholder images initially (like https://via.placeholder.com/800x600)
- Take consistent photos of your keyboards (same angle, lighting, background)
- Update `available: false` when a keyboard sells
- Recommended image size: 800x600px or 1200x800px

Enjoy! 🎹
