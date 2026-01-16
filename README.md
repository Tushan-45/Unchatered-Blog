# Uncharted 4 Blog Website

A responsive blog website dedicated to Uncharted 4: A Thief's End, featuring blog cards, game information, and an embedded video trailer.

## 📋 Project Overview

This project is a static HTML/CSS website showcasing blog posts about Uncharted 4: A Thief's End. It features a modern card-based layout that adapts to different screen sizes and includes an embedded video section.

## 🎮 Features

- **Responsive Grid Layout**: Automatically adjusts from 1 to 4 columns based on screen width
- **8 Blog Cards**: Each covering different aspects of Uncharted 4
- **Hover Effects**: Interactive card animations and color transitions
- **Embedded Video**: Auto-playing trailer section
- **Mobile-First Design**: Optimized for all device sizes

## 🛠️ Technologies Used

- HTML5
- CSS3
- Responsive Grid Layout
- CSS Animations & Transitions

## 📁 File Structure

```
project-folder/
│
├── index.html (or your HTML file name)
├── style29.css
├── uncharted logo.jpeg (favicon)
├── image.png (author avatar)
├── Uncharted Trailer - Made with Clipchamp.mp4 (video)
│
└── images/
    ├── Uncharted 4 - Final Battle, Eytan Zana.jpeg
    ├── Uncharted 4.jpeg
    ├── Uncharted 4_ A Thief's End _ Screenshot.jpeg
    ├── Uncharted 4_ A Thief's End.jpeg
    ├── Uncharted_ Explore the Unknown 🎮.jpeg
    ├── download (1).jpeg
    ├── un 2.jpeg
    └── UNCHARTED 4 - The Game Magazine art by RUIZBURGOS on DeviantArt.jpeg
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- All image and video files in the correct directory

### Installation

1. Clone or download this repository
2. Ensure all images are in the same directory as your HTML file (or update paths accordingly)
3. Open `index.html` in your web browser

```bash
# If using a local server (recommended)
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📱 Responsive Breakpoints

| Screen Width | Columns |
|-------------|---------|
| < 650px     | 1       |
| 650px - 999px | 2     |
| 1000px - 1339px | 3   |
| ≥ 1340px    | 4       |

## 🎨 Customization

### Changing Colors

Edit the CSS hover effects in `style29.css`:

```css
.header_title:hover {
    color: rgb(73, 26, 227); /* Change this */
}

.card_title:hover {
    color: rgb(61, 61, 248); /* Change this */
}
```

### Modifying Card Content

Each card follows this structure in the HTML:

```html
<div class="card_container">
    <a href="a" class="card_image_container">
        <img src="your-image.jpeg" alt="description" class="card_image" loading="lazy"/>
    </a>
    <div class="card_title_container">
        <a href="a">
            <h2 class="card_title">YOUR TITLE</h2>
        </a>
        <p class="card_desc">Your description here</p>
    </div>
    <!-- Footer section -->
</div>
```

## 🔗 External Links

The website includes links to:
- [Uncharted: Legacy of Thieves Collection on Steam](https://store.steampowered.com/app/1659420/UNCHARTED_Legacy_of_Thieves_Collection/)
- [Uncharted 4 Wikipedia Page](https://en.wikipedia.org/wiki/Uncharted_4:_A_Thief%27s_End)

## ⚠️ Notes

- The video will autoplay when the page loads (muted by default)
- All card links currently point to `href="a"` - update these with actual URLs
- The `loading="lazy"` attribute is used for performance optimization
- Ensure video format is compatible with all target browsers

## 🖼️ Image Requirements

- **Card Images**: Recommended size 400x200px (will be cropped to fit)
- **Author Avatar**: 25x25px (circular)
- **Favicon**: Standard favicon size (16x16 or 32x32px)

## 📄 License

This is a personal/educational project. Uncharted 4 and all related content are property of Naughty Dog and Sony Interactive Entertainment.

## 🤝 Credits

- Game: Uncharted 4: A Thief's End by Naughty Dog
- Blog Author: "The Lost Legacy"
- Release Date: May 10, 2016

## 📧 Contact

For questions or suggestions about this project, please open an issue in the repository.

---

**Happy Treasure Hunting! 🏴‍☠️**
