# QRCODE Generator
QR code that generate a link to the page with rendered 10 random movies

## Task 
[] Create A QR Code Generator - Create a QR code generator. After scanning a QR code there should be a link to the page with rendered 10 random movies (title + image).

### Requirements
- Project must be done in Nest.js
- You should use typescript.
- Project should be on some free platform (Heroku, etc.) and must be available to test online. We want to make sure you are aware of how to deploy apps.
- Place your code on github (or any other platform you prefer to store your code). Send us back a link to it. Make sure it is public.

### task
- Your task is to generate a QR code that will give a user link to the page with a list of 10 movies.
- For this you will need two pages:
- Page with a QR code to scan
- Page with a list of movies received from the scanning of QR code.
- How you will display it on the front-end is totally up to you. It might react, jquery, pure js, or build-in templates - it doesn't matter to us. We will look only backend logic.
- QR code must be regenerated every 10 seconds and return a new link to another 10 random movies.

### Demo movies JSON

[json data](https://gist.github.com/saniyusuf/406b843afdfb9c6a86e25753fe2761f4)