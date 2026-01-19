HOW TO USE

1) Put your images into the folder:
   gallery/photos/

2) Edit gallery/images.json
   - Replace the example names with your real filenames.
   - Keep the quotes and commas.

Example:
[
  "IMG_0001.jpg",
  "church-event.png",
  "photo (7).jpeg"
]

3) Run it from a web server.
   - Upload the gallery folder to your hosting, then open gallery/index.html
   OR
   - Use a simple local server (example):
     - Python:  python -m http.server 8000
     - Then open: http://localhost:8000/gallery/

Notes
- Pure HTML cannot auto-scan the folder for filenames (browser security). That is why images.json exists.
- The page will show a collage and a click-to-zoom lightbox.
