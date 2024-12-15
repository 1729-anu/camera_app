# Media Gallery and Animation Project

This project combines a responsive media gallery with advanced animations and canvas interactions. It showcases the use of IndexedDB for managing media storage, CSS animations, and HTML canvas drawing techniques.

## Features

### 1. Media Gallery
- Displays images and videos from an IndexedDB database.
- Allows users to download or delete media directly from the gallery.
- Responsive design to fit different screen sizes.

### 2. Animations
- Animated elements using CSS, including scaling boxes and fading circles.
- Demonstrates the use of `@keyframes` and CSS transitions.

### 3. Canvas Interactions
- Draw lines, rectangles, and other graphics on an HTML canvas.
- Integrates images onto the canvas for enhanced visuals.

## Technologies Used

- **HTML**: Structure and layout of the application.
- **CSS**: Styling for animations and responsive design.
- **JavaScript**: Logic for managing IndexedDB and canvas drawings.
- **IndexedDB**: Client-side database for storing media objects.

## Project Structure

```
project-directory/
|-- animation.html          # Animation demonstration
|-- canvas.html             # Canvas drawing example
|-- gallery.html            # Media gallery layout
|-- gallery.css             # Styling for the gallery
|-- dbScript.js             # JavaScript for IndexedDB operations
|-- assets/                 # (Optional) Folder for images/videos
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/media-gallery-animation.git
   ```

2. Open the desired HTML file in a browser:
   - **animation.html**: View animations.
   - **canvas.html**: Experiment with canvas drawings.
   - **gallery.html**: Explore the media gallery.

3. Add media items:
   - Use the provided `gallery.html` to interact with the IndexedDB database.
   - Media objects (images/videos) can be added through pre-defined JavaScript functions.
