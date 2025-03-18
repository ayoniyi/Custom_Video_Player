# Custom Video Player

A modern, feature-rich video player built with HTML, CSS, and vanilla JavaScript. This project provides a YouTube-like video player experience with a clean interface and extensive keyboard controls.

## Features

- **Playback Controls**:

  - Play/Pause toggle
  - Video timeline with preview thumbnails
  - Volume control with mute option
  - Playback speed adjustment (0.25x - 2x)
  - Time display (current time / total duration)

- **Display Modes**:

  - Theater mode
  - Fullscreen mode
  - Mini player (Picture-in-Picture)

- **Additional Features**:

  - Closed captions support
  - Timeline scrubbing with preview images
  - Volume level indication
  - Responsive design

- **Keyboard Shortcuts**:
  - Space/K: Play/Pause
  - F: Toggle fullscreen
  - T: Toggle theater mode
  - I: Toggle mini player
  - M: Toggle mute
  - Left Arrow/J: Skip backward 5 seconds
  - Right Arrow/L: Skip forward 5 seconds
  - C: Toggle captions

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- HTML5 Video API

## Setup Instructions

1. Clone the repository:

   ```
   git clone https://github.com/your-username/custom-video-player.git
   cd custom-video-player
   ```

2. Open the project in your favorite web server or use a Live Server extension in your code editor.

3. Open `index.html` in your browser to view the video player.

## Project Structure

- `index.html` - Main HTML structure
- `style.css` - CSS styling for the video player
- `script.js` - JavaScript functionality
- `assets/` - Contains video files and thumbnail previews
  - `x.mp4` - Sample video
  - `previewImgs/` - Timeline preview thumbnails
  - `subtitles.vtt` - Captions file in WebVTT format

## Customization

### Using Your Own Video

To use your own video, replace the video source in the HTML:

```html
<video src="path/to/your/video.mp4">
  <track kind="captions" srclang="en" src="path/to/your/captions.vtt" />
</video>
```

### Preview Images

For timeline preview thumbnails, add your own preview images to the `assets/previewImgs/` directory named as `preview1.jpg`, `preview2.jpg`, etc.

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

[MIT License](LICENSE)

## Acknowledgements

This project was inspired by YouTube's video player interface and built as a learning exercise for HTML5 video API and modern CSS.
