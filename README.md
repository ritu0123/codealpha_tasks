# codealpha_tasks
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Responsive Image Gallery</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <h1>Image Gallery</h1>

  <div class="filter-buttons">
    <button data-filter="all">All</button>
    <button data-filter="nature">Nature</button>
    <button data-filter="city">City</button>
    <button data-filter="animals">Animals</button>
  </div>

  <div class="gallery">
    <div class="gallery-item" data-category="nature">
      <img src="images/img1.jpg" alt="Nature 1" />
    </div>
    <div class="gallery-item" data-category="city">
      <img src="images/img2.jpg" alt="City 1" />
    </div>
    <div class="gallery-item" data-category="animals">
      <img src="images/img3.jpg" alt="Animal 1" />
    </div>
    <!-- Add more items as needed -->
  </div>

  <!-- Lightbox -->
  <div class="lightbox" id="lightbox">
    <span class="close">&times;</span>
    <img class="lightbox-image" id="lightbox-img" src="" />
    <div class="lightbox-nav">
      <button id="prev">&#10094;</button>
      <button id="next">&#10095;</button>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
