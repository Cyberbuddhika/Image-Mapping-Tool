# Image Mapping Tool

This is a simple tool to help you map your own image to find the exact coordinates of points you're interested in. With this tool, you can click on any location on your image and it will generate a marker at that point, showing the x and y coordinates.

## Files and their purpose:

- `index.html`: This is the main HTML file that structures the webpage. It links to the CSS and JavaScript files. It contains a `div` with the id `map` which is where your image will be displayed.

- `style.css`: This file contains all the styles for the webpage. It is here that you provide your image's path in the `#map` rule (replace `'/map_image/Thilan-floorplan.jpeg'` with the path to your image). The dimensions of the map (and consequently your image) are defined here too. If your image has different dimensions, adjust the width and height properties accordingly.

- `script.js`: This JavaScript file is where the functionality of the tool is defined. It adds markers at the location where the user clicks on the image. The markers display the x and y coordinates of the point clicked. An `onclick` event on a marker alerts the coordinates of that marker.

## How to use:

1. Clone or download this repository.

2. Replace the image path in the `style.css` file (under the `#map` rule) with the path to your image.

3. Open the `index.html` file in a web browser.

4. Click on the image at the location you are interested in. A marker is generated at that point displaying the x and y coordinates.

5. Click on a marker to see an alert with its coordinates.

## Note:

- The coordinates are with respect to the viewport (browser window) and not the image. So, they might change with different window sizes. Make sure to use a consistent window size while working.

- The tool currently supports JPEG images. Make sure your image is in JPEG format.

Feel free to contribute to improving this tool or open an issue if you face any problems.

Enjoy mapping!

