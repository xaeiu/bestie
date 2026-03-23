# Bestie Questions Game 🎮

A cute and colorful web-based question game for friends! Perfect for getting to know each other better or breaking the ice.

## Features

- 🎨 Bright, vibrant kid-friendly design
- 📱 Mobile-responsive layout
- ✨ Floating animations and confetti effects
- 🎲 Random question generator
- 💖 40+ thoughtful questions included
- 🔄 Tracks used questions to avoid repeats
- ⌨️ Keyboard support (Space/Enter to randomize)

## Live Demo

Open `index.html` in your browser to play!

## Deployment to GitHub Pages (Free Hosting)

1. **Create a GitHub repository:**
   - Go to [github.com](https://github.com) and create a new repository
   - Name it anything you like (e.g., "bestie-game")

2. **Push your code:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Bestie Questions Game"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## Customization

### Adding/Editing Questions

Edit the `questions.json` file to add your own questions:

```json
[
  "What's your biggest dream?",
  "Your new question here?",
  "Another question?"
]
```

### Changing Colors

Edit `styles.css` and modify the color gradients:

```css
/* Background gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Card gradient */
background: linear-gradient(135deg, #ff6b9d 0%, #ffa06b 100%);

/* Button gradient */
background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
```

### Changing Decorations

Modify the emoji decorations in `index.html`:

```html
<div class="shape shape-star">⭐</div>
```

## File Structure

```
bestie/
├── index.html       # Main HTML structure
├── styles.css       # All styling and animations
├── script.js        # Question randomization logic
├── questions.json   # Question database
└── README.md        # This file
```

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Free to use and modify for personal projects!

---

Made with 💖 for fun times with friends!
