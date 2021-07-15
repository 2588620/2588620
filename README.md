<!DOCTYPE html>
<html>
<title>smile</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="index5.css" type="text/css">
<link rel="stylesheet" href="img1.jpeg" type="text/css">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
</style>
<body>
/gtm?_ga=2.172801706.80395673.1626337410-506661168.1626337410

<!-- Sidebar with image -->
  <nav class="w3-sidebar w3-hide-medium w3-hide-small" style="width:40%">
    <div class="bgimg"></div>
  </nav>

<!-- Hidden Sidebar (reveals when clicked on menu icon)-->
  <nav class="w3-sidebar w3-black w3-animate-right w3-xxlarge" style="display:none;padding-top:150px;right:0;z-index:2;color:black;" id="mySidebar">
    <a href="javascript:void(0)" onclick="closeNav()" class="w3-button w3-black w3-xxxlarge w3-display-topright" style="padding:0 12px;">
      <i class="fa fa-remove"></i>
    </a>
    <div class="w3-bar-block w3-center">
      <a href="#" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Home</a>
      <a href="#portfolio" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Portfolio</a>
      <a href="#about" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">About</a>
      <a href="#contact" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Contact</a>
    </div>
  </nav>

<!-- Page Content -->
  <div class="w3-main w3-padding-large" style="margin-left:40%">

<!-- Menu icon to open sidebar -->
  <span class="w3-button w3-top w3-white w3-xxlarge w3-text-grey w3-hover-text-black" style="width:auto;right:0;" onclick="openNav()">
    <i class="fa fa-bars"></i></span>

<!-- Header -->
  <header class="w3-center" style="padding:128px 16px;color:black;" id="home">
    <h1><b>Gabriela</b></h1>
    <p>Reseacher and Programmer.</p>
    <img src="pic)floating.jpg" class="w3-image w3-hide-large w3-hide-small w3-round" style="display:block;width:60%;margin:auto;">
    <img src="pic)floating.jpg" class="w3-image w3-hide-large w3-hide-medium w3-round" width="1000" height="1333">
  </header>

<!-- research section -->
  <div class="w3-padding-32 w3-content" id="portfolio">
    <h2><b>research</b></h2>
        <hr class="w3-opacity">

<!-- Grid for photos of reseach-->
     <div class="w3-row-padding" style="margin:0 -16px;" " color:"black"">
      <div class="w3-half">
        <img src="elfimg.jpg" style="width:100%">
      </div>
<!-- ** make as a button that opens the doc in another page-->
      <a href="cw3final.pdf"> technology and body image </a>
<!-- End photo grid -->
    </div>
<!-- End Portfolio Section -->
  </div>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-padding-32" id="about">
    <h2>a little bit about me :)</h2>
    <hr class="w3-opacity">
    <p> I am Gabriela Peixoto Goncalves, I am 19 years old. I was born in Sao Paulo, Brazil, lived in the US for one year and now I am living in Amsterdam, Netherlands. As noticed, i love to travel and get to know new places, cultures and people.
    </p>

    <h3 class="w3-padding-16">Programming:</h3>
    <p class="w3-wide">Java</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-center w3-padding-small w3-grey" style="width:75%">75%</div>
    </div>
    <p class="w3-wide">HTML</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-center w3-padding-small w3-grey" style="width:95%">95%</div>
    </div>
    <p class="w3-wide">CSS</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-center w3-padding-small w3-grey" style="width:95%">95%</div>
    </div>
    <p class="w3-wide">JavaScript</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-center w3-padding-small w3-grey" style="width:70%">70%</div>
    </div>
    <p class="w3-wide">SQL</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-center w3-padding-small w3-grey" style="width:80%">80%</div>
    </div><br>

<!--add skills: leadership, team/time menagement, -->

    <button class="w3-button w3-light-grey w3-padding-large w3-section">
      <i class="fa fa-download"></i><a href="cvfinal.pdf"> Download Resume <a/>
    </button>

<!-- End About Section -->
  </div>

<!-- contact info: -->
      <div class="w3-padding-32 w3-content" id="contact" style="margin-bottom:64px">
        <h2>Contact Me</h2>
        <hr class="w3-opacity">

        <div class="w3-section">
          <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i> Amsterdam, NL</p>
          <p><i class="fa fa-phone fa-fw w3-xxlarge w3-margin-right"></i>phone#: +31 6 ...</p>
          <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> e-mail: gabipg15@gmail.com</p>
        </div>

<!-- map -->
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d155959.8924297995!2d4.763878108967292!3d52.354582834316005!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47c63fb5949a7755%3A0x6600fd4cb7c0af8d!2zQW1zdGVyZMOj!5e0!3m2!1spt-BR!2snl!4v1626294383379!5m2!1spt-BR!2snl"
          width="600"
          height="450"
          style="border:0"
          loading="lazy"
          allowfullscreen> </iframe>

<!-- send message: -->
        <p> Lets get in touch... </br> Send me a message:</p>
        <form action="/action_page.php" target="_blank">
          <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Full Name" required name="Name"></p>
          <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Email" required name="Email"></p>
          <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Subject" required name="Subject"></p>
          <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message" required name="Message"></p>
          <p>
            <button class="w3-button w3-light-grey w3-padding-large" type="submit">
              <i class="fa fa-paper-plane"></i> SEND MESSAGE
            </button>
          </p>
        </form>
<!-- End Contact Section -->
      </div>

<!-- Footer -->
      <footer class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge" style="margin:-24px">
        <a href="https://www.facebook.com/photo/?fbid=2951579848295032&set=a.175388415914203"><i class="fa fa-facebook-official w3-hover-opacity"></i></a>
        <a href="https://www.instagram.com/gabipg15/?hl=en"><i class="fa fa-instagram w3-hover-opacity"></i></a>
        <a href="https://br.pinterest.com/gabrielapeixotogoncalves/_saved/"><i class="fa fa-pinterest-p w3-hover-opacity"></i></a>
        <a href="https://www.linkedin.com/in/gabriela-p-g/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3B39%2FSbIpxR0CtUSltMJDanQ%3D%3D"><i class="fa fa-linkedin w3-hover-opacity"></i></a>
<!-- End footer -->
      </footer>

<!-- END PAGE CONTENT -->
    </div>

    <script>
// Open and close sidebar
    function openNav() {
      document.getElementById("mySidebar").style.width = "60%";
      document.getElementById("mySidebar").style.display = "block";
    }

    function closeNav() {
      document.getElementById("mySidebar").style.display = "none";
    }
    </script>

    </body>
    </html>
