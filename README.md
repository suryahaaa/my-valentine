# Valentine's Landing Page - GitHub Pages Deployment Guide 💕

## Quick Start

This is a beautiful Valentine's themed landing page that reveals photos and video when she clicks "Yes!"

## How to Deploy to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and log in
2. Click the "+" icon in the top right and select "New repository"
3. Name it something like `valentine-surprise` or `my-valentine`
4. Make it **Public** (required for GitHub Pages free hosting)
5. Click "Create repository"

### Step 2: Upload Your Files
1. In your new repository, click "uploading an existing file"
2. Drag and drop the `index.html` file
3. Add your photos and video files (see below for naming)
4. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. Go to your repository's **Settings** tab
2. Scroll down to **Pages** in the left sidebar
3. Under "Source", select **main** branch
4. Click **Save**
5. Your site will be live at: `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Adding Your Photos and Video

### File Setup
1. Upload your media files to the repository:
   - `photo1.jpg` - First photo
   - `photo2.jpg` - Second photo
   - `video.mp4` - Your video

### Update the HTML
Open `index.html` and find the placeholders (around line 300-330):

**Replace Photo 1:**
```html
<!-- Find this: -->
<div class="placeholder-image">
    📸
</div>

<!-- Replace with: -->
<img src="photo1.jpg" alt="Our beautiful memory" style="width: 100%; height: 300px; object-fit: cover; border-radius: 15px;">
```

**Replace Photo 2:**
```html
<!-- Find this: -->
<div class="placeholder-image">
    💑
</div>

<!-- Replace with: -->
<img src="photo2.jpg" alt="Forever together" style="width: 100%; height: 300px; object-fit: cover; border-radius: 15px;">
```

**Replace Video:**
```html
<!-- Find this: -->
<div class="placeholder-video">
    🎬
</div>

<!-- Replace with: -->
<video controls style="width: 100%; border-radius: 15px;">
    <source src="video.mp4" type="video/mp4">
    Your browser doesn't support video.
</video>
```

## Features ✨

- **Romantic Valentine's theme** with rose and burgundy colors
- **Animated floating hearts** in the background
- **"No" button runs away** from the cursor (fun interaction!)
- **Rose petal animation** when she clicks "Yes!"
- **Smooth reveal** of your photos and video
- **Fully responsive** - works on mobile and desktop

## Customization Tips

### Change the Question
Edit line 229 in `index.html`:
```html
<h1>Will You Be<br>My Valentine?</h1>
```

### Change the Success Message
Edit line 265:
```html
<h2 class="celebration-title">You Just Made Me The Happiest! 💝</h2>
```

### Change Photo Captions
Edit the text in `<p class="media-caption">` tags

## Troubleshooting

**Site not loading?**
- Wait 2-3 minutes after enabling GitHub Pages
- Make sure repository is Public
- Check that `index.html` is in the root folder

**Media not showing?**
- Make sure file names match exactly (case-sensitive!)
- Check that media files are in the same folder as index.html
- Try using lowercase filenames: `photo1.jpg` not `Photo1.JPG`

**Video not playing?**
- Use MP4 format for best compatibility
- Keep video file size under 100MB for faster loading

## Support

If you need help, feel free to ask! This is designed to be simple and romantic. Good luck! 💝

---

Made with ❤️ for someone special
