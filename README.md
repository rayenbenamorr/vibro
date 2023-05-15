<!DOCTYPE html>
<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
.w3-row-padding img {margin-bottom: 12px}
/* Set the width of the sidebar to 120px */
.w3-sidebar {width: 120px;background: #222;}
/* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
#main {margin-left: 120px}
/* Remove margins from "page content" on small screens */
@media only screen and (max-width: 600px) {#main {margin-left: 0}}
</style>
</head>
<body class="w3-black">

<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
  <img src="logo.png" style="width:50%" >
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>HOME</p>
  </a>
  <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ABOUT</p>
  </a>
  <a href="#photos" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-eye w3-xxlarge"></i>
    <p>PHOTOS</p>
  </a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-envelope w3-xxlarge"></i>
    <p>CONTACT</p>
  </a>
</nav>

<!-- Navbar on small screens (Hidden on medium and large screens) -->
<div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item w3-button" style="width:25% !important">Acceuil</a>
    <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">Apropos</a>
    <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">photos</a>
    <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">Contact</a>
  </div>
</div>

<!-- Page Content -->
<div class="w3-padding-large" id="main" >
  <!-- Header/Home -->
  <header class="w3-container w3-padding-32 w3-center w3-black" id="home" style="margin-top: 6%;">
    <h1 class="w3-jumbo"><span class="w3-hide-small">VIBROGRAV</h1>
    <p>GRAVITE ESPACE TEMP</p>
    <img src="Untitled Project (8)_0515.png" alt="boy" class="w3-image" width="992" height="1108">
  </header>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">description</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>      L'avènement d'une nouvelle technologie qui permettrait la manipulation de la gravité est un sujet fascinant et prometteur. Imaginez les implications que cela pourrait avoir dans les domaines de l'aéronautique, de la construction et même de la recherche spatiale. La capacité de contrôler la gravité pourrait révolutionner la façon dont nous voyageons et construisons des bâtiments, en nous permettant de manipuler la force qui nous retient sur Terre. Bien que cette technologie soit encore en développement, son potentiel est énorme et mérite d'être exploré de manière approfondie. La manipulation de la gravité est une avancée technologique qui pourrait changer la manière dont nous pensons l'univers et notre place dans celui-ci.
    </p>
    <h3 class="w3-padding-16 w3-text-light-grey">Aventage</h3>
    <p class="w3-wide">Espace</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:95%"></div>
    </div>
    <p class="w3-wide">Terre</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:85%"></div>
    </div>
    <p class="w3-wide">Sous marin</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:80%"></div>
    </div><br>
    
    

    
    
   
  <!-- End About Section -->
  </div>
  
  <!-- Portfolio Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="photos">
    <h2 class="w3-text-light-grey">Mes Photos</h2>
    <hr style="width:200px" class="w3-opacity">

    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="Untitled Project (8)_0642.png" style="width:100%">
        <img src="Untitled Project (17)_0001.png" style="width:100%">
        <img src="Untitled Project (21)_0320.png" style="width:100%">
      </div>

      <div class="w3-half">
        <img src="Untitled Project (20)_0254.png" style="width:100%">
        <img src="Untitled Project (19)_0038.png" style="width:100%">
        <img src="Untitled Project1_0025.png" style="width:100%">
       
           
      </div>
      <video style="width:100%" controls>
        <source src="xx.mp4" type="video/mp4">
       
      </video>
    <!-- End photo grid -->
    </div>
  <!-- End Portfolio Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contactez nous</h2>
    <hr style="width:200px" class="w3-opacity">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Ariana Tunisie</p>
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Phone: +216 22450577</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: business.benamor@gmail.com</p>
    </div><br>
    <p>Prenons contact.Envoyez-nous un message:</p>

    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="NOM" required name="NOM"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="PRENOM" required name="PRENOM"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="SUJET" required name="SUJET"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="MESSAGE" required name="MESSAGE"></p>
      <p>
        <button class="w3-button w3-light-grey w3-padding-large" type="submit">
          <i class="fa fa-paper-plane"></i> ENVOYER UN MESSAGE
        </button>
      </p>
    </form>
  <!-- End Contact Section -->
  </div>
  
    <!-- Footer -->
  <footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
    
  <!-- End footer -->
  </footer>

<!-- END PAGE CONTENT -->
</div>

</body>
</html>
