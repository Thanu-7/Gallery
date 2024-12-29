# Ex.08 Design of Interactive Image Gallery
# Date: 28.10.2024
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
```
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: beige;


}
div.gallery {
  border: 1px solid #ccc;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: 700px;
}

div.desc {
  padding: 15px;
  text-align: center;
}

* {
  box-sizing: border-box;
}

.responsive {
  padding: 0 6px;
  float: left;
  width: 24.99999%;
}

@media only screen and (max-width: 700px) {
  .responsive {
    width: 49.99999%;
    margin: 6px 0;
  }
}

@media only screen and (max-width: 500px) {
  .responsive {
    width: 100%;
  }
}

.clearfix:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<h1 style="text-align: center; background-color:plum;">Responsive Image Gallery</h1>
<center>
  <h2 >Thanushree Vijayakanth - 24900679</h2>
</center>


<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="1.jpg">
      <img src="1.jpg" alt="Cinque Terre" height="250px"  >
    </a>
  </div>
</div>


<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="2.jpg">
      <img src="2.jpg" alt="Forest" height="250px">
    </a>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="3.jpg">
      <img src="3.jpg" alt="Northern Lights" height="250px">
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="4.jpg">
      <img src="4.jpg" alt="Mountains" height="250px" >
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="5.jpg">
      <img src="5.jpg" alt="Mountains" height="250px">
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="6.jpg">
      <img src="6.jpg" alt="Mountains" height="250px">
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="7.jpg">
      <img src="7.jpg" alt="Mountains" height="250px">
    </a>

  </div>
</div>



<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="9.jpg">
      <img src="9.jpg" alt="Mountains" height="250px">
    </a>

  </div>
</div>



</body>
</html>
```
# OUTPUT:
![imagegal](https://github.com/user-attachments/assets/2eee12ef-74f4-45cf-a353-710567a423ac)

![imagegal1](https://github.com/user-attachments/assets/b58c4364-990a-442c-9877-a5a3e14993e3)

![gal1](https://github.com/user-attachments/assets/1642f795-a4fa-44e1-b531-ed16f5900510)

![gal2](https://github.com/user-attachments/assets/f0da6f58-6b4b-4bc7-b881-bf93c20a3056)


# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
