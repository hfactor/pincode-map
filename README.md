# PIN Code Map

A simple data visualization that maps (pun intended) [Postal Index Number](https://en.wikipedia.org/wiki/Postal_Index_Number) (PIN) Codes of India to [Hex Triplet](https://en.wikipedia.org/wiki/Web_colors#Hex_triplet) colours, resulting in a colourful geographic representation of the Indian Postal Code System.

## Overview

This project converts each 6-digit PIN Code into a hexadecimal colour code and displays the corresponding postal areas on an interactive map. Each geographical region of a PIN is filled with the corresponding hexadecimal colour, creating a vibrant mosaic representing Indian postal geography.

Each 6-digit PIN (for example, `560001`) becomes a hexadecimal colour code (`#560001`)



## Installation

1. **Download the required data file**
   - From [data.gov.in](https://data.gov.in/resource/delivery-post-office-pincode-boundary), download the data.
   - Place the file as `data.geojson` in the same directory as `index.html`.

2. **Start a local web server**

   Using Python3 (recommended):

   ```bash
   python -m http.server 8000
   ```

   Using Python 2

   ```bash
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

3. **Open in browser**

   - Navigate to `http://localhost:8000`
   - Wait for the map to load (may take time depending on data size)

## Dependencies

- [**leaflet.js**](https://leafletjs.com/). It is the interactive mapping library.
- **OpenStreetMap** for base map tiles.
- No additional build tools or frameworks are required

## References

- **Created by** [Hiran Venugopalan](https://hiran.in) using Claude AI  
- **Thanks to** [OSM Kerala Team](https://kerala.openstreetmap.in/maintainers/)  
- **Data Source** is on [Government of India Open Data Platform](https://data.gov.in/resource/delivery-post-office-pincode-boundary)
