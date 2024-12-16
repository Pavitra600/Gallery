# Ex.08 Design of Interactive Image Gallery
# Date: 10/12/2024
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
          <!DOCTYPE html>
          <html lang="en">
          <head>
              <meta charset="UTF-8">
              <meta name="viewport" content="width=device-width, initial-scale=1.0">
              <title>FLOWER IMAGE GALLERY</title>
              <link rel="stylesheet" href="styles.css">
          </head>
          <body>
              <header class="gallery-header">
                  <h1>FLOWER IMAGE GALLERY</h1>
                  <p>Explore the beauty of flowers</p>
              </header>
              <div class="gallery-container">
                  <div class="gallery-item">
                      <img src="ROSE.avif" alt="Rose">
                      <div class="overlay">
                          <p>Beautiful Rose</p>
                      </div>
                  </div>
                  <div class="gallery-item">
                      <img src="Sunflower.jpg" alt="Sunflower">
                      <div class="overlay">
                          <p>Sunflower</p>
                      </div>
                  </div>
                  <div class="gallery-item">
                      <img src="lily.jpg" alt="Lily">
                      <div class="overlay">
                          <p>Lily</p>
                      </div>
                  </div>
                  <div class="gallery-item">
                      <img src="daisy.jpg" alt="Daisy">
                      <div class="overlay">
                          <p>Daisy</p>
                      </div>
                  </div>
                  <div class="gallery-item">
                      <img src="Carnation.jpg" alt="Carnation">
                      <div class="overlay">
                          <p>Carnation</p>
                      </div>
                  </div>
                  <div class="gallery-item">
                      <img src="iris.jpg" alt="Iris">
                      <div class="overlay">
                          <p>Iris</p>
                      </div>
                  </div>
                  <div class="gallery-item">
                      <img src="jasmine.jpg" alt="Jasmine">
                      <div class="overlay">
                          <p>Jasmine</p>
                      </div>
                  </div>
                  <div class="gallery-item">
                      <img src="marigold.jpg" alt="Marigold">
                      <div class="overlay">
                          <p>Marigold</p>
                      </div>
                  </div>
                  <div class="gallery-item">
                      <img src="orchid.jpg" alt="Orchid">
                      <div class="overlay">
                          <p>Orchid</p>
                      </div>
                  </div>
                  <div class="gallery-item">
                      <img src="tulip.jpg" alt="Tulip">
                      <div class="overlay">
                          <p>Tulip</p>
                      </div>
                  </div>
                  <div class="gallery-item">
                      <img src="lavender.jpg" alt="Lavender">
                      <div class="overlay">
                          <p>Lavender</p>
                      </div>
                  </div>
                  <div class="gallery-item">
                      <img src="salvia.jpg" alt="Salvia">
                      <div class="overlay">
                          <p>Salvia</p>
                      </div>
                  </div>
              </div>
          </body>
          </html>
          styles.css:
          
          
          body {
              margin: 0;
              font-family: 'Arial', sans-serif;
              background-image: url('bgflower.jpeg'); 
              background-size: cover; 
              background-position: center; 
              background-attachment: fixed; 
              color: #333;
          }
          
          .gallery-header {
              text-align: center;
              padding: 20px;
              background-color: rgba(255, 255, 255, 0.7); 
              border-bottom: 2px solid hsl(350, 53%, 39%);
          }
          
          .gallery-header h1 {
              margin: 0;
              font-size: 2.5em;
              color: hsl(350, 53%, 39%);
          }
          
          .gallery-header p {
              margin: 5px 0 0;
              font-size: 1.2em;
              color: hsl(350, 53%, 39%);
          }
          
          
          .gallery-container {
              display: grid;
              grid-template-columns: repeat(6, 1fr); 
              gap: 20px;
              padding: 20px;
              max-width: 1200px;
              margin: 0 auto;
          }
          
          /* Gallery Items */
          .gallery-item {
              position: relative;
              overflow: hidden;
              aspect-ratio: 1 / 1; 
              border-radius: 50%; 
              box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
              transition: transform 0.3s ease-in-out;
              border: 4px solid  hsl(346, 65%, 32%); 
          }
          
          .gallery-item img {
              width: 100%;
              height: 100%;
              object-fit: cover;
              border-radius: 50%; 
              transition: transform 0.3s ease;
              border: 4px solid beige; 
          }
          
          .gallery-item:hover img {
              transform: scale(1.1);
              border-color: hsl(346, 50%, 52%); 
          }
          
          
          .overlay {
              position: absolute;
              top: 0;
              left: 0;
              width: 100%;
              height: 100%;
              background: rgba(0, 0, 0, 0.6);
              color: #fff;
              display: flex;
              justify-content: center;
              align-items: center;
              opacity: 0;
              transition: opacity 0.3s ease;
              text-align: center;
              border-radius: 50%;
          }
          
          .gallery-item:hover .overlay {
              opacity: 1;
          }
          
          .overlay p {
              margin: 0;
              font-size: 1.5em;
              font-weight: bold;
          }

# OUTPUT:
![Screenshot 2024-12-16 142020](https://github.com/user-attachments/assets/61b17f0b-afd5-427d-8b11-78ef83b6b6f9)

# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
