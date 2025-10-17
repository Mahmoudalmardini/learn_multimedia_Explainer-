# Learn Multimedia - Explainer

An interactive multimedia learning platform demonstrating various image, audio, and video formats with visual comparisons and explanations.

## Features

- 📸 **Image Format Comparisons** - Visual demonstrations of JPEG, PNG, and WebP formats
- 🎵 **Audio Format Examples** - MP3 bitrate comparisons (32, 96, 192 kbps vs original WAV)
- 🎥 **Video Explanations** - Educational video content about multimedia formats
- 💡 **Interactive UI** - Modern, user-friendly interface

## Pages

- `index.html` - Main landing page
- `jpeg.html` - JPEG format explanation
- `mp3.html` - MP3 format comparison
- `login.html` - User login page

## Deployment

This site is configured for deployment on Railway using static file serving.

### Deploy to Railway

1. Push to GitHub
2. Connect your repository to Railway
3. Railway will auto-deploy using the nixpacks.toml configuration

## Local Development

Simply open `index.html` in a web browser, or use a local server:

```bash
npx serve .
```

## Project Structure

```
├── index.html
├── jpeg.html
├── mp3.html
├── login.html
├── media/
│   ├── audio/
│   ├── images/
│   ├── video/
│   └── Logo.png
└── styles/
    └── style.css
```

## Author

Mahmoud Almardini

## License

All rights reserved.

