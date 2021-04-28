<!DOCTYPE html>
<html>
<title>Loop</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Nunito:wght@200;400&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="icon" href="greenlogo.svg"/>

<style>
body,h1,h2,h3,h4,h5,h6 {font-family: 'Nunito', sans-serif;}

body, html {
  height: 100%;
  line-height: 1.8;
}

/* Full height image header */
.bgimg-1 {
  background-position: center;
  background-size: cover;
  background-image: url("/w3images/mac.jpg");
  min-height: 100%;
}

.w3-bar .w3-button {
  padding: 16px;
}
</style>
<body>
  <body style="background-color: #c6d1ff;"></body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-card" id="myNavbar">
    <a href="#home" class="w3-bar-item w3-button"><img src="greenlogo.svg" alt="Loop Logo " width="150" height="58"></a>
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <a href="#causes" class="w3-bar-item w3-button w3-padding-32">Causes of Extinction</a>
      <a href="#animals" class="w3-bar-item w3-button w3-padding-32">Endangered Animals</a>
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">ABOUT</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">TEAM</a>
  <a href="#work" onclick="w3_close()" class="w3-bar-item w3-button">WORK</a>
  <a href="#pricing" onclick="w3_close()" class="w3-bar-item w3-button">PRICING</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
</nav>


<!-- Map Section -->
<div class="w3-container w3-margin-left" style="padding:128px 16px;" id="home">
  <h1 style="font-weight: bold">Do you know that animals are disappearing?</h1>
  <p>In both the worlds of animals and plants, there are now 41,415 species on the IUCN Red List (endangered species list), 
    and <br>16,306 of them are endangered species threatened with extinction. Learn more about the endangered species from 
    the story below.<br><br>
    Hover on to the map to learn more about the number of endangered species in each country.<br>
    Also, click on the icon to learn about the top 10 endangered animals as of 2020.</p>
    <div class="w3-center" style="margin-top: 5%;"><img src="map.svg" alt="Loop Logo" width=50% height=auto></div>
</div>


<!-- Tab Section -->
<div class="w3-container" style="background: white" id="causes">
  <br><br><h3 class="w3-center">Three Main Causes of Animal Extinction</h3><br><br>
<button class="tablink" onclick="openCity('habitat', this, '#c6d1ff')" id="defaultOpen">
  <div class="w3-section">
    <div class="w3-center">
      <img class="w3-margin-top" src="habitat.svg" alt="John" style="width:20%;">
      <div class="w3-container">
        <h3 style="color: black; font-weight: bold;">Habitat Loss</h3>
        <p>Habitat loss may be the greatest threat to biodiversity on earth, affecting 85% species. Most habitat loss is due to intense harvesting and agricultural expansion by human.</p>
      </div>
    </div>
  </div>
</button>
<button class="tablink" onclick="openCity('poaching', this, '#c6d1ff')">  
  <div class="w3-section">
  <div class="w3-center">
    <img class="w3-margin-top" src="poaching.svg" alt="John" style="width:20%;">
    <div class="w3-container">
      <h3 style="color: black; font-weight: bold;">Poaching</h3>
      <p>Poaching is the illegal hunting, capture or collection of wildlife by human that leads to the maiming
        of many animals not intended for consumption and in some cases, extinction.</p>
    </div>
  </div>
</div></button>
<button class="tablink" onclick="openCity('climate', this, '#c6d1ff')">  <div class="w3-section">
  <div class="w3-center">
    <img class="w3-margin-top" src="climate.svg" alt="John" style="width:20%;">
    <div class="w3-container">
      <h3 style="color: black; font-weight: bold;">Climate Change</h3>
      <p>Human adds greenhouse gasses to the atmosphere, which arise the planet’s temperature, consequently melting ice caps, raising sea levels and warming oceans.</p>
    </div>
  </div>
</div></button>

<div id="habitat" class="tabcontent">
  <div class="w3-container" id="team">
    <br><br>
    <div class="w3-row-padding">
      <div class="w3-half w3-section">
        <div class="w3-card" style="background-color: white;">
          <div class="w3-container">
            <h3 style="color: black; font-weight: bold;">Top 3 Lucrative Crimes</h3>
            <p>lllegal wildlife trafficking is the second most lucrative crime globally,  with
              $73–$216 billion estimated yearly value.The first one is drugs, with $426–
              $652 billion estimated yearly value. Human trafficking is third, with an
              estimated $150 billion.</p>
              <img class="w3-margin-top w3-margin-bottom" src="crimes.svg" alt="John" style="width:70%;">
          </div>
        </div>
      </div>
      <div class="w3-half w3-section">
        <div class="w3-card" style="background-color: white;">
          <div class="w3-container">
            <h3 style="color: black; font-weight: bold;">Ivory Price Rose by 10x</h3>
            <p>The price increase occurred in only 30 years after the CITES issued a worldwide ban on 
              ivory trading in 1989.</p>
              <img class="w3-margin-top w3-margin-bottom" src="ivory.svg" alt="Jane" style="width:70%">
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="poaching" class="tabcontent">
  <div class="w3-container" id="team">
    <br><br>
    <div class="w3-row-padding">
      <div class="w3-half w3-section">
        <div class="w3-card" style="background-color: white;">
          <div class="w3-container">
            <h3 style="color: black; font-weight: bold;">Top 3 Lucrative Crimes</h3>
            <p>lllegal wildlife trafficking is the second most lucrative crime globally,  with
              $73–$216 billion estimated yearly value.The first one is drugs, with $426–
              $652 billion estimated yearly value. Human trafficking is third, with an
              estimated $150 billion.</p>
              <img class="w3-margin-top w3-margin-bottom" src="crimes.svg" alt="John" style="width:70%;">
          </div>
        </div>
      </div>
      <div class="w3-half w3-section">
        <div class="w3-card" style="background-color: white;">
          <div class="w3-container">
            <h3 style="color: black; font-weight: bold;">Ivory Price Rose by 10x</h3>
            <p>The price increase occurred in only 30 years after the CITES issued a worldwide ban on 
              ivory trading in 1989.</p>
              <img class="w3-margin-top w3-margin-bottom" src="ivory.svg" alt="Jane" style="width:70%">
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="climate" class="tabcontent">
  <div class="w3-container" id="team">
    <br><br>
    <div class="w3-row-padding">
      <div class="w3-half w3-section">
        <div class="w3-card" style="background-color: white;">
          <div class="w3-container">
            <h3 style="color: black; font-weight: bold;">Top 3 Lucrative Crimes</h3>
            <p>lllegal wildlife trafficking is the second most lucrative crime globally,  with
              $73–$216 billion estimated yearly value.The first one is drugs, with $426–
              $652 billion estimated yearly value. Human trafficking is third, with an
              estimated $150 billion.</p>
              <img class="w3-margin-top w3-margin-bottom" src="crimes.svg" alt="John" style="width:70%;">
          </div>
        </div>
      </div>
      <div class="w3-half w3-section">
        <div class="w3-card" style="background-color: white;">
          <div class="w3-container">
            <h3 style="color: black; font-weight: bold;">Ivory Price Rose by 10x</h3>
            <p>The price increase occurred in only 30 years after the CITES issued a worldwide ban on 
              ivory trading in 1989.</p>
              <img class="w3-margin-top w3-margin-bottom" src="ivory.svg" alt="Jane" style="width:70%">
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
<br><br>
</div>

<!-- 3 Causes Section -->
<div class="w3-container" style="padding:128px 16px" id="animals">
  <h3 class="w3-center">Explore Endangered Animals</h3>
  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-third w3-section">
      <div class="flip-card w3-center">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <img src="Orangutan.png" alt="Avatar" style="width:100%;height:600px; border-radius: 25px;">
          </div>
          <div class="flip-card-back">
            <h1>John Doe</h1>
            <p>Architect & Engineer</p>
            <p>We love that guy</p>
          </div>
        </div>
      </div>
    </div>
    <div class="w3-third w3-section">
      <div class="flip-card w3-center">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <img src="Leopard.png" alt="Avatar" style="width:100%;height:600px; border-radius: 25px;">
          </div>
          <div class="flip-card-back">
            <h1>John Doe</h1>
            <p>Architect & Engineer</p>
            <p>We love that guy</p>
          </div>
        </div>
      </div>
    </div>
    <div class="w3-third w3-section">
      <div class="flip-card w3-center">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <img src="Turtle.png" alt="Avatar" style="width:100%;height:600px; border-radius: 25px;">
          </div>
          <div class="flip-card-back">
            <h1>John Doe</h1>
            <p>Architect & Engineer</p>
            <p>We love that guy</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Promo Section "Statistics" -->
<div class="w3-container w3-row w3-center w3-pink w3-padding-64">
  <div class="w3-third" style="color: black;">
    <span class="w3-xxlarge">41,415</span>
    <br>Species Listed on the Red List
  </div>
  <div class="w3-third" style="color: black;">
    <span class="w3-xxlarge">40%</span>
    <br>Endangered Specied
  </div>
  <div class="w3-third" style="color: black;">
    <span class="w3-xxlarge">10%</span>
    <br>Increased From Last Year
  </div>
</div>

<!-- 3 Causes Section -->
<div class="w3-container" style="padding:128px 16px; background: white" id="extinction">
  <h3 class="w3-center">Three Main Causes of Animal Extinction</h3>
  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-third w3-section">
      <div class="w3-card w3-center" style="background-color: #ffdbcd;">
        <img class="w3-margin-top" src="habitat.svg" alt="John" style="width:20%;">
        <div class="w3-container">
          <h3 style="color: black; font-weight: bold;">Habitat Loss</h3>
          <p>Habitat loss may be the greatest threat to biodiversity on earth, affecting 85% species. Most habitat loss is due to intense harvesting and agricultural expansion by human.</p>
        </div>
      </div>
    </div>
    <div class="w3-third w3-section">
      <div class="w3-card w3-center" style="background-color: #c6d1ff;">
        <img class="w3-margin-top" src="poaching.svg" alt="Jane" style="width:20%">
        <div class="w3-container">
          <h3 style="color: black; font-weight: bold;">Poaching</h3>
          <p>Poaching is the illegal hunting, capture or collection of wildlife by human that leads to the maiming
            of many animals not intended for consumption and in some cases, extinction. </p>
        </div>
      </div>
    </div>
    <div class="w3-third w3-section">
      <div class="w3-card w3-center" style="background-color: #ffdbcd;">
        <img class="w3-margin-top" src="climate.svg" alt="Mike" style="width:20%">
        <div class="w3-container">
          <h3 style="color: black; font-weight: bold;">Climate Change</h3>
          <p>Human adds greenhouse gasses to the atmosphere, which arise the planet’s temperature, consequently melting ice caps, raising sea levels and warming oceans. </p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 2 Causes Section -->
<div class="w3-container" style="padding:128px 16px;" id="team">
  <div class="w3-row-padding">
    <div class="w3-half w3-section">
      <div class="w3-card" style="background-color: white;">
        <div class="w3-container">
          <h3 style="color: black; font-weight: bold;">Top 3 Lucrative Crimes</h3>
          <p>lllegal wildlife trafficking is the second most lucrative crime globally,  with
            $73–$216 billion estimated yearly value.The first one is drugs, with $426–
            $652 billion estimated yearly value. Human trafficking is third, with an
            estimated $150 billion.</p>
            <img class="w3-margin-top w3-margin-bottom" src="crimes.svg" alt="John" style="width:70%;">
        </div>
      </div>
    </div>
    <div class="w3-half w3-section">
      <div class="w3-card" style="background-color: white;">
        <div class="w3-container">
          <h3 style="color: black; font-weight: bold;">Ivory Price Rose by 10x</h3>
          <p>The price increase occurred in only 30 years after the CITES issued a worldwide ban on 
            ivory trading in 1989.</p>
            <img class="w3-margin-top w3-margin-bottom" src="ivory.svg" alt="Jane" style="width:70%">
        </div>
      </div>
    </div>
  </div>
</div>


<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
</footer>
 
<script>
// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}


// Toggle between showing and hiding the sidebar when clicking the menu icon
var mySidebar = document.getElementById("mySidebar");

function w3_open() {
  if (mySidebar.style.display === 'block') {
    mySidebar.style.display = 'none';
  } else {
    mySidebar.style.display = 'block';
  }
}

// Close the sidebar with the close button
function w3_close() {
    mySidebar.style.display = "none";
}

function openCity(cityName, elmnt, color) {
  // Hide all elements with class="tabcontent" by default */
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }

  // Remove the background color of all tablinks/buttons
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }

  // Show the specific tab content
  document.getElementById(cityName).style.display = "block";

  // Add the specific color to the button used to open the tab content
  elmnt.style.backgroundColor = color;
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>

</body>
</html>
