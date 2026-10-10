# README – Standalone qgis2web Export

This export is completely "self-contained".

To view the map, simply open "index.html" by double-clicking it.
No web server or additional software is required.

The map works because all the required JavaScript libraries are included
in the export. The application loads the GeoJSON layer data and their styles
directly from the local files.

## Publishing on a Website

If you upload the entire folder to a web server, the map will work 
immediately by opening the "index.html" file.

Example:

"https://www.example.com/my-map/index.html"

## Sharing the Public Geoportal

The map has a Share this Geoportal control in the upper-right corner. It
shows a QR code, a link to open the public map, and an option to download
the QR code as an SVG. The QR code links to:

https://mfpd7g4g4f-maker.github.io/Spatial-Database-of-Permanent-Survey-Marks-in-Lae-District/#12/-6.6938/146.9829

Keep `images/geoportal-qr.svg` with the rest of the published site files.
