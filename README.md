# Greet Inspirations Website

## Files Included
- `index.html` - Main HTML file
- `logo.png` - Greet Inspirations logo
- `collage.png` - Background collage image

## How to Use

### Local Testing
1. Extract all files to a folder
2. Keep all files in the same directory
3. Open `index.html` in your web browser

### Uploading to a Web Server
1. Upload all files to your web hosting service
2. Ensure all files are in the same directory
3. Your website will be accessible at your domain

### Replacing the Image with Video
To use a video instead of the collage image:

1. Open `index.html` in a text editor
2. Find the `<img>` tag with `src="collage.png"`
3. Comment it out by wrapping it in `<!-- -->`
4. Uncomment the `<video>` tag below it
5. Replace `your-video.mp4` with your actual video filename
6. Upload your video file to the same directory

Example:
```html
<!-- <img src="collage.png" alt="Greet Inspirations collage" class="media-container" id="mediaElement"> -->

<video class="media-container" autoplay muted loop playsinline>
    <source src="your-video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

## Features
- Responsive design (works on desktop, tablet, and mobile)
- Collapsible "About" section
- Instagram link opens in new tab
- Contact email link
- Ready for video integration

## Font
The website uses Helvetica Neue/Helvetica font family with fallback to Arial and sans-serif.

## Support
For questions, contact: hello@greetinspirations.com
