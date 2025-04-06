# Liquor Store Visualization Project

## Description
This project visualizes a hierarchical dataset of liquor stores using D3.js. The data is loaded from a JSON file (`liquor.json`) and displayed as a radial tree diagram. Each node in the tree represents a liquor store or a category, with clickable links to their respective locations on Google Maps.

## Files
- **liquor.json**: Contains the hierarchical data of liquor stores, including their names, icons, and URLs.
- **liquor.html**: The main HTML file that renders the visualization using D3.js.
- **liquor_shops.png**: The default icon used for nodes without specific icons.

## Features
- Radial tree visualization of liquor store data.
- Hover effects to highlight nodes and display their icons.
- Clickable links on store names to open their Google Maps location.
- Dynamic resizing and styling of nodes and links.

## How to Use
1. Place all files (`liquor.json`, `liquor.html`, and `liquor_shops.png`) in the same directory.
2. Open `liquor.html` in a web browser.
3. The visualization will load automatically, displaying the hierarchical data from `liquor.json`.

## Dependencies
- **D3.js**: The project uses D3.js version 6. Ensure you have an internet connection to load the library from the CDN.

## Customization
- **Data**: Update `liquor.json` to add or modify liquor store data.
- **Icons**: Replace `liquor_shops.png` or add custom icons for specific nodes in the JSON file.
- **Styling**: Modify the CSS in `liquor.html` to change the appearance of the visualization.

## Notes
- Ensure the JSON file is properly formatted and free of syntax errors.
- Use a modern browser for the best experience (e.g., Chrome, Firefox, Edge).

## License
This project is for personal or educational use. Modify and distribute as needed.
