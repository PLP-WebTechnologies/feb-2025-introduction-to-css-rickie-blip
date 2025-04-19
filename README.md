# Introduction to CSS
stle.css
/* Set a background color for the body and apply a font */
body {
    background-color: #f4f4f9;
    font-family: 'Arial', sans-serif;
    color: #333;
    margin: 0;
    padding: 0;
  }
  
  /* Style for elements with class "header" */
  .header {
    text-align: center;
    color: #ffffff;
    background-color: #3498db;
    padding: 20px;
    border-bottom: 3px solid #2980b9;
  }
  
  /* Style for the image with class "profile-image" */
  .profile-image {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    border: 5px solid #2980b9;
    margin: 20px auto;
    display: block;
  }
  
  /* Style for elements with ID "content" */
  #content {
    padding: 20px;
    margin: 30px;
    border: 2px solid #ddd;
    background-color: #ffffff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  /* Add space between paragraphs and change the font size */
  p {
    margin-bottom: 15px;
    font-size: 18px;
  }
  
  /* Add some spacing around images */
  img {
    display: block;
    margin: 20px auto;
  }
  index.html
  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Web Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Header Section with class "header" -->
  <div class="header">
    <h1>Welcome to My Styled Page</h1>
  </div>

  <!-- Image with class "profile-image" -->
  <img src="https://via.placeholder.com/200" alt="Profile" class="profile-image">

  <!-- Content Section with ID "content" -->
  <div id="content">
    <p>This is some content inside the content section. It has padding, margin, and borders applied.</p>
    <p>The typography is styled with a larger font size for better readability.</p>
  </div>

</body>
</html>
