# India by Pincode Colors
A simple data visualization that maps India's postal pincodes to hexadecimal colors, creating a colorful geographic representation of the country's postal system.

## Overview
This project converts each 6-digit Indian pincode into a hexadecimal color code and displays the corresponding postal areas on an interactive map. 
Each pincode area is filled with its unique color, creating a vibrant mosaic that represents India's postal geography. 
Each 6-digit pincode (e.g., `560001`) becomes a hexadecimal color code (`#560001`)

### Installation

1. **Download the required data file**
   - Download data from: [data.gov.in/resource/delivery-post-office-pincode-boundary]
   - Place the file as data.geojson in the same directory as `index.html`

2. **Start a local web server**
   
   Using Python (recommended):
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   
   Using Node.js:
   ```bash
   npx http-server
   ```
   
   Using PHP:
   ```bash
   php -S localhost:8000
   ```

4. **Open in browser**
   - Navigate to `http://localhost:8000`
   - Wait for the map to load (may take a few moments depending on data size)

### Dependencies
- **Leaflet.js**: Interactive mapping library
- **OpenStreetMap**: Base map tiles
- No additional build tools or frameworks required


- **Created by**: [Hiran Venugopalan](https://hiran.in) using Claude AI.
- **Thanks to**: [OSM Kerala Team](https://kerala.openstreetmap.in/maintainers/)
- **Data Source**: [Government of India Open Data Platform](https://data.gov.in/resource/delivery-post-office-pincode-boundary)
