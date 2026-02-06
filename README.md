# Illustration & Animation Portfolio

A clean, modern portfolio website featuring your illustration and animation work, with a beautiful yellow-orange color theme.

## 🚀 Quick Setup Guide

### Setting Up on GitHub Pages

1. **Create a new GitHub repository**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it: `yourusername.github.io` (replace `yourusername` with your GitHub username)
   - Make it public
   - Don't initialize with README

2. **Upload your files**
   - Upload all the files from this project to your repository:
     - `index.html`
     - `styles.css`
     - `script.js`
     - Create an `images` folder (see structure below)

3. **Enable GitHub Pages**
   - Go to your repository Settings
   - Scroll down to "Pages" section
   - Under "Source", select "main" branch
   - Click Save
   - Your site will be live at: `https://yourusername.github.io`

## 📁 Folder Structure

```
your-portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript for interactions
├── README.md           # This file
│
└── images/             # Create this folder
    ├── illustrations/  # Your illustration images
    │   ├── sample1.jpg
    │   ├── sample2.jpg
    │   └── ...
    │
    ├── animations/     # Your animation files
    │   ├── sample1.mp4
    │   ├── sample1-thumb.jpg
    │   ├── sample2.gif
    │   └── ...
    │
    └── profile.jpg     # Your profile photo
```

## ✏️ How to Edit Your Portfolio

### 1. Customize Your Information

In `index.html`, find and replace:

- **Line 6**: Change `"Your Name - Illustration & Animation Portfolio"` to your actual name
- **Line 12**: Change `"Your Name"` in the logo to your name
- **Line 44**: Update the hero title
- **Line 45**: Update the tagline
- **Lines 102-106**: Write your bio in the About section
- **Line 117**: Add your email address
- **Lines 118-119**: Add your social media links

### 2. Add Your Artwork

#### Adding Illustrations:

In `index.html`, find the Illustrations section (around line 53) and add more gallery items:

```html
<div class="gallery-item">
    <img src="images/illustrations/your-image.jpg" alt="Description">
    <div class="overlay">
        <h3>Project Title</h3>
        <p>Brief description</p>
    </div>
</div>
```

#### Adding Animations:

For videos:
```html
<div class="gallery-item">
    <video src="images/animations/your-video.mp4" poster="images/animations/thumbnail.jpg" controls></video>
    <div class="overlay">
        <h3>Animation Title</h3>
        <p>Description</p>
    </div>
</div>
```

For GIFs:
```html
<div class="gallery-item">
    <img src="images/animations/your-animation.gif" alt="Animation">
    <div class="overlay">
        <h3>Animation Title</h3>
        <p>Description</p>
    </div>
</div>
```

### 3. Upload Your Images

1. Create the folder structure shown above
2. Place your images in the appropriate folders
3. Make sure filenames match what you wrote in the HTML
4. Supported formats:
   - Images: `.jpg`, `.png`, `.gif`, `.webp`
   - Videos: `.mp4`, `.webm`

### 4. Customize Colors (Optional)

If you want to adjust the yellow-orange theme, edit `styles.css` at the top:

```css
:root {
    --primary-color: #FF9F1C;      /* Main yellow-orange */
    --primary-dark: #E88F15;       /* Darker shade for hover */
    --primary-light: #FFB347;      /* Lighter accent */
}
```

## 🎨 Features

- ✨ Smooth scrolling navigation
- 📱 Fully responsive (works on phones, tablets, desktops)
- 🎭 Hover animations on gallery items
- 🎬 Support for both images and videos
- 🌟 Modern, clean design
- 🎨 Yellow-orange color theme
- ⚡ Fast loading times

## 📝 Tips for Best Results

1. **Image Optimization**: 
   - Compress your images before uploading (use tools like TinyPNG)
   - Recommended size: 1200px wide for illustrations
   - Keep file sizes under 1MB for faster loading

2. **Consistent Naming**:
   - Use lowercase filenames
   - No spaces (use hyphens: `my-artwork.jpg`)

3. **Regular Updates**:
   - Simply edit `index.html` to add new work
   - Upload new images to the `images` folder
   - Commit and push changes to GitHub

## 🔄 Updating Your Site

After making changes:

1. Edit your files locally
2. Go to your GitHub repository
3. Upload the changed files (or use Git commands if you're familiar)
4. GitHub Pages will automatically update within a few minutes

## 💡 Need Help?

- GitHub Pages Documentation: https://pages.github.com/
- HTML Guide: https://www.w3schools.com/html/
- CSS Guide: https://www.w3schools.com/css/

## 📄 License

This template is free to use for your personal portfolio!

---

Made with 💛 for showcasing your creative work
