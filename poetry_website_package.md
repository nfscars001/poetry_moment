# Poetry Sharing Website

A beautiful, responsive website for sharing poems with social media image generation capabilities.

## 🌟 Features

- **Random Poem Display**: Displays a random poem from your CSV collection
- **Social Media Export**: Generates 1080x1080 images perfect for Instagram/Facebook
- **Custom Watermark**: Your logo appears on generated images
- **Mobile Responsive**: Works perfectly on all devices
- **Easy Management**: Simply edit the CSV file to add/remove poems

## 📁 Package Contents

```
poetry-website/
├── index.html          # Main website file
├── poems.csv           # Your poem database
├── watermark.png       # Your custom watermark
└── README.md          # This file
```

## 🚀 Quick Start

1. **Download/Extract**: Place all files in the same directory
2. **Customize**: Edit `poems.csv` with your poem collection
3. **Add Watermark**: Replace `watermark.png` with your logo
4. **Launch**: Open `index.html` in a web browser

## 📝 CSV Format

Your `poems.csv` should have three columns:

| Column | Description |
|--------|-------------|
| `title` | The poem title |
| `author` | The poet's name |
| `content` | The full poem text |

### Example CSV:
```csv
title,author,content
"The Road Not Taken","Robert Frost","Two roads diverged in a yellow wood,\nAnd sorry I could not travel both\nAnd be one traveler, long I stood"
"Hope","Emily Dickinson","Hope is the thing with feathers\nThat perches in the soul,\nAnd sings the tune without the words"
```

**Important Notes:**
- Use `\n` for line breaks in poems
- Wrap text in quotes if it contains commas
- Keep content under 500 characters for best image formatting

## 🎨 Customization

### Adding New Poems
1. Open `poems.csv` in any text editor or Excel
2. Add new rows with title, author, and content
3. Save the file
4. Refresh the website

### Changing the Watermark
1. Replace `watermark.png` with your logo
2. Recommended size: 80x80 pixels or larger
3. Supports PNG with transparency

### Styling Changes
Edit the CSS in `index.html` to customize:
- Colors and gradients
- Fonts and typography
- Layout and spacing
- Animation effects

## 🔧 Technical Details

- **HTML5 Canvas**: For image generation
- **Responsive Design**: CSS Grid and Flexbox
- **Cross-browser**: Works in all modern browsers
- **No Dependencies**: Pure HTML, CSS, and JavaScript
- **Local Files**: No internet connection required

## 📱 Usage

1. **View Poems**: Website loads a random poem automatically
2. **Get New Poem**: Click "New Poem" for a different random selection
3. **Save Image**: Click "Save as Image" to download a social media-ready image
4. **Share**: Upload the generated image to your social media platforms

## 🌐 Deployment Options

### Local Use
- Simply open `index.html` in any web browser
- Perfect for personal use or local testing

### Web Server
- Upload all files to your web hosting service
- Ensure all files are in the same directory
- Access via your domain name

### GitHub Pages
1. Create a new repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Access via `https://username.github.io/repository-name`

## 🎯 Image Specifications

Generated images are optimized for social media:
- **Size**: 1080x1080 pixels (Instagram square format)
- **Format**: PNG with transparent background support
- **Quality**: High resolution for crisp text
- **Branding**: Your watermark in bottom-right corner

## 🔍 Troubleshooting

### Common Issues

**"Could not load poems.csv"**
- Ensure `poems.csv` is in the same directory as `index.html`
- Check that the CSV file is properly formatted

**"No poems found"**
- Verify CSV has the correct headers: `title,author,content`
- Check for empty rows or malformed data

**Watermark not showing**
- Ensure `watermark.png` is in the same directory
- Check that the image file is not corrupted
- The website will use a text watermark as fallback

**Images not generating**
- Ensure you have a poem loaded first
- Try refreshing the page and loading a new poem
- Check browser console for errors

## 📊 Analytics & Tracking

The website includes no tracking by default. To add analytics:

1. **Google Analytics**: Add the GA script to the `<head>` section
2. **Custom Events**: Track poem views and image downloads
3. **Social Shares**: Monitor sharing activity

## 🔒 Privacy & Security

- **No Data Collection**: Website doesn't store user data
- **Local Processing**: All image generation happens in the browser
- **No External Requests**: Works completely offline
- **Safe Content**: Only displays poems from your CSV file

## 🤝 Support

For issues or questions:
1. Check this README for common solutions
2. Verify all files are in the same directory
3. Ensure CSV format is correct
4. Test in different browsers

## 📜 License

This project is open source. Feel free to modify and distribute as needed.

---

**Happy Poetry Sharing! 🎭✨**