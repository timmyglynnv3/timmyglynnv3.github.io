# timmyglynnv3.github.io
Personal Website


<!DOCTYPE html>
<html>
<title>CONTACT</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif;}
body, html {
    height: 100%;
    color: #777;
    line-height: 1.8;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3 {
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
    background-image: url('https://cdn-images-1.medium.com/max/1600/0*QUqE4WGF8_cC9bIl.jpg');
    min-height: 100%;
}

/* Second image (Portfolio) */
.bgimg-2 {
    background-image: url("/w3images/parallax2.jpg");
    min-height: 400px;
}

/* Third image (Contact) */
.bgimg-3 {
    background-image: url("/w3images/parallax3.jpg");
    min-height: 400px;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1024px) {
    .bgimg-1, .bgimg-2, .bgimg-3 {
        background-attachment: scroll;
    }
}
</style>
<body>


<!-- Navbar (sit on top) -->
<div class="w3-top">
        <div class="w3-bar" id="myNavbar">
          <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
            <i class="fa fa-bars"></i>
          </a>
          <a href="https://timmyglynnv3.github.io/" class="w3-bar-item w3-button w3-white">TIMMY GLYNN</a>
          <!-- <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> ABOUT</a> -->
          <a href="https://timmyglynnv3.github.io/software/" class="w3-bar-item w3-button w3-white w3-hide-small"><i class="fa fa-th"></i> SOFTWARE</a>
          <a href="https://timmyglynnv3.github.io/contact/" class="w3-bar-item w3-button w3-white w3-hide-small"><i class="fa fa-envelope"></i> CONTACT</a>
          <a href="#" class="w3-bar-item w3-button w3-white w3-hide-small w3-right w3-hover-red">
            <i class="fa fa-search"></i>
          </a>
        </div>
      
        <!-- Navbar on small screens -->
        <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
         <!-- <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT</a> -->
          <a href="https://timmyglynnv3.github.io/software/" class="w3-bar-item w3-button" onclick="toggleFunction()">SOFTWARE</a>
          <a href="https://timmyglynnv3.github.io/contact/" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
          <a href="#" class="w3-bar-item w3-button">SEARCH</a>
        </div>
      </div>



<!-- Container (Contact Section) -->
<div class="w3-content w3-container w3-padding-64" id="contact">
        <h3 class="w3-center">CONTACT ME</h3>
        <p class="w3-center"><em>I'd love your feedback!</em></p>
      
        <div class="w3-row w3-padding-32 w3-section">
          <div class="w3-col m4 w3-container">
            <!-- Add Google Maps -->
            <div id="googleMap" class="w3-round-large w3-greyscale" style="width:100%;height:400px;"></div>
          </div>
          <div class="w3-col m8 w3-panel">
            <div class="w3-large w3-margin-bottom">
              <i class="fa fa-map-marker fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Pittsburgh, PA<br>
              <i class="fa fa-phone fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Phone: +1 215-694-7564<br>
              <i class="fa fa-envelope fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Email: timmyglynnv3@gmail.com<br>
            </div>
            <p>Swing by for a cup of <i class="fa fa-coffee"></i>, or leave me a note:</p>
            <form action="/action_page.php" target="_blank">
              <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
                <div class="w3-half">
                  <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
                </div>
                <div class="w3-half">
                  <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
                </div>
              </div>
              <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
              <button class="w3-button w3-black w3-right w3-section" type="submit">
                <i class="fa fa-paper-plane"></i> SEND MESSAGE
              </button>
            </form>
          </div>
        </div>
      </div>




                  <body>
              <script>
                function initMap() {
                  var uluru = {lat: 40.4280292, lng: -79.9754504};
                  var map = new google.maps.Map(document.getElementById('map'), {
                    zoom: 10,
                    center: uluru
                  });
                  var marker = new google.maps.Marker({
                    position: uluru,
                    map: map
                  });
                }
              </script>
              <script async defer
              src="https://maps.googleapis.com/maps/api/js?key=AIzaSyC2n761R8ph9q5dDs5Zr-DrQiyZhJ6Xrko&callback=initMap">
              </script>
            </body>
            </div>


  <!---
              <body>
                  <script>
                      function myMap() {
                      var mapProp= {
                          center:new google.maps.LatLng(40.4280292,-79.9754504),
                          zoom:5,
                      };
                      var map=new google.maps.Map(document.getElementById("googleMap"),mapProp);
                      }
                      </script>
                      
                      <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyC2n761R8ph9q5dDs5Zr-DrQiyZhJ6Xrko&callback=myMap"></script>
        
                      </body> -->


          </div>