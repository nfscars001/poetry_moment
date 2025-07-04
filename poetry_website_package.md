# Poetry Sharing Website Package

This package contains all the files needed to run your poetry sharing website.

## Package Contents

### 1. index.html
The main website file (see HTML artifact above)

### 2. poems.csv
Your poem library database

### 3. watermark.png
Your custom watermark image

### 4. README.md
Installation and usage instructions

---

## File Structure
```
poetry-website/
├── index.html
├── poems.csv
├── watermark.png
└── README.md
```

## Installation Instructions

1. **Extract Files**: Place all files in the same directory
2. **Update CSV**: Edit `poems.csv` with your poem collection
3. **Customize Watermark**: Replace `watermark.png` with your logo
4. **Serve Files**: Open `index.html` in a web browser or serve via a web server

## CSV Format

Your `poems.csv` should have three columns:
- `title`: The poem title
- `author`: The poet's name  
- `content`: The full poem text (use \n for line breaks)

Example:
```csv
title,author,content
"The Road Not Taken","Robert Frost","Two roads diverged in a yellow wood,\nAnd sorry I could not travel both\nAnd be one traveler, long I stood"
"Hope","Emily Dickinson","Hope is the thing with feathers\nThat perches in the soul,\nAnd sings the tune without the words"
```

## Features

- **Random Poem Display**: Shows a different poem each time "New Poem" is clicked
- **Social Media Export**: Generates 1080x1080 images perfect for Instagram/Facebook
- **Custom Watermark**: Your logo appears on generated images
- **Mobile Responsive**: Works on all devices
- **Easy Updates**: Just edit the CSV file to add/remove poems

## Usage

1. Open `index.html` in a web browser
2. Click "New Poem" to display a random poem
3. Click "Save as Image" to download the poem as a shareable image
4. The generated image will include your watermark

## Customization

### Adding Poems
Edit `poems.csv` and add new rows with title, author, and content.

### Changing Watermark
Replace `watermark.png` with your desired logo (recommended size: 80x80 pixels or larger).

### Styling
Modify the CSS in `index.html` to change colors, fonts, or layout.

## Technical Notes

- Uses HTML5 Canvas for image generation
- Responsive design with CSS Grid and Flexbox
- Supports line breaks in poem content
- Fallback text watermark if image is missing
- Cross-browser compatible

## Support

For issues or questions, ensure all files are in the same directory and that your CSV follows the correct format.