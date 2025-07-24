# Image-Color--Analyzer
A web application that extracts a color palette from uploaded images based on their mood and vibe. The app uses k-means clustering to identify the most representative colors in an image and allows users to interact with these colors by dragging color indicators around the image to sample new colors.

Features
Color Extraction: Automatically extracts 5 dominant colors from uploaded images
Interactive Color Sampling: Drag color indicators around the image to sample new colors
Pixel Zoom: Hover over the image to see a magnified view of pixels
Copy Colors: Click on any color in the palette to copy its hex code to clipboard
Drag & Drop: Upload images by dragging and dropping files onto the application
Responsive Design: Works well on both desktop and mobile devices
Installation
Clone the repository:
bash

Collapse
Copy
1
git clone https://github.com/yourusername/mood-palette.git
Install dependencies:
bash

Collapse
Copy
1
npm install
Start the application:
bash

Collapse
Copy
1
npm start
Alternatively, you can simply open the index.html file in a modern web browser.

Usage
Click "Choose image" or drag and drop an image onto the upload area
Wait for the application to process the image and extract colors
Interact with the color indicators by dragging them around the image
Click on any color in the palette to copy its hex code
Hover over the image to see a pixel zoom view
Technologies Used
HTML5 Canvas for image processing
JavaScript for the core functionality
CSS3 for styling and animations
K-means clustering algorithm for color extraction
Modern web APIs (Clipboard API, Drag and Drop API)
File Structure

Collapse
Copy
1
2
3
4
mood-palette/
├── index.html          # Main HTML file
├── style.css           # CSS styles (embedded in HTML)
└── script.js           # JavaScript functionality (embedded in HTML)
Requirements
Modern web browser with support for ES6+ JavaScript
Internet connection for loading external resources (Font Awesome)
Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License.

requirements.txt

Collapse
Copy
1
2
3
4
# No external dependencies required
# All libraries are loaded from CDN:
# - Font Awesome (for icons)
# - Modern browser features (ES6+, Canvas API, Clipboard API, Drag and Drop API)
The application is designed as a standalone HTML file with no external dependencies, making it extremely easy to run. All necessary libraries (Font Awesome for icons) are loaded from CDNs, and the core functionality uses modern browser APIs that are widely supported in current browsers.

