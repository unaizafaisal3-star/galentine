# 💖 Will You Be My Galentine?

An interactive, romantic web experience to ask someone to be your Galentine! This project is a beautifully designed single-page application with smooth animations, heartfelt memories, and a fun interactive "No" button that evades clicks.

## ✨ Features

- **Landing Section** – A charming introduction with a call-to-action button
- **Memories Carousel** – Showcase your favorite moments or reasons why you cherish the relationship
- 
- **Evasive "No" Button** – The "No" button escapes when hovered over (they can't escape! 😄)
- **Celebration Screen** – Confetti animation and a victory message when they click "YES"
- **Background Music** – Plays an instrumental as they explore (music toggle available)
- **Floating Hearts** – Ambient decorative hearts floating across the background
- **Responsive Design** – Works beautifully on mobile and desktop devices
- **Smooth Scrolling** – Navigate through sections with smooth scroll animations

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A web server (for local testing) or simply open `index.html` in your browser

### Setup

1. **Clone or download** the project files
2. **Add your music** – Replace `song.mp3` with your own background music file in the root directory
3. **Customize the memories** – Edit the memory cards in `index.html` with your own messages
4. **Open in browser** – Open `index.html` directly or serve it via a local server

### To Run Locally
```bash
# Option 1: Python
python -m http.server 8000

# Option 2: Node.js (with http-server)
npx http-server

# Then navigate to http://localhost:8000
```

## 🎨 Customization

### Edit Memories
In `index.html`, find the memory cards section and modify the text and emojis:
```html
<div class="memory-card">
    <span class="emoji">😂</span>
    <h3>Your Title</h3>
    <p>Your custom message here</p>
</div>
```

### Change Colors
Modify the CSS variables in the `<style>` section:
```css
:root {
    --pink-primary: #FFADCB;
    --pink-dark: #FF85B3;
    --lavender: #D4C1EC;
    --cream: #FFF9FB;
    --text-color: #7A5C61;
}
```

### Update Music
Replace the source link in the audio tag:
```html
<audio id="bgMusic" loop>
    <source src="your-song.mp3" type="audio/mpeg">
</audio>
```

### Celebration Message
Find the celebration section and customize the message:
```html
<p><strong>When:</strong> Whenever you want jaanemann</p>
<p><strong>Where:</strong> Our favorite spot</p>
```

## 🎵 Music Note

The project includes a placeholder for background music (`song.mp3`). For the best experience:
- Use royalty-free music or a song you have permission to use
- MP3 format works best
- Host the file in the same directory as `index.html`

Some great sources:
- [Pixabay Music](https://pixabay.com/music/)
- [Freesound](https://freesound.org/)
- Your own music files

## 📱 Browser Compatibility

- ✅ Chrome/Chromium (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 📝 License

Feel free to use and customize this for your special someone! 💕

## 💬 Tips

- Personalize it! The more custom details, the more meaningful it becomes
- Test on the device your Galentine will use it on
- Make sure the music file is ready before sharing
- The evasive "No" button is just for fun – they'll want to click "YES"! ✨

---

Made with 💖 for asking that special person to be your Galentine!
