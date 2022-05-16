
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="styles.css">
<style>

<title>HOME</title>

</style>
</head>
<body>

  <ul>
  
  <li><a href="Tailor.html">Home</a></li>
  <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">Action</a>
    <div class="dropdown-content">
      <a href="MayAction.html">May</a>
      <a href="JuneAction.html">June</a>
      <a href="JulyAction.html">July</a>
      <a href="AugustAction.html">August</a>
    </div>


    <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">Thriller</a>
    <div class="dropdown-content">
      <a href="MayThriller.html">May</a>
      <a href="JuneThriller.html">June</a>
      <a href="JulyThriller.html">July</a>
      <a href="AugustThriller.html">August</a>
    </div>


    <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">Romance</a>
    <div class="dropdown-content">
      <a href="MayRomance.html">May</a>
      <a href="JuneRomance.html">June</a>
      <a href="JulyRomance.html">July</a>
      <a href="AugustRomance.html">August</a>
    </div>

    <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">Animation</a>
   <div class="dropdown-content">
      <a href="MayAnimation.html">May</a>
      <a href="JuneAnimation.html">June</a>
      <a href="JulyAnimation.html">July</a>
      <a href="AugustAnimation.html">August</a>
    </div>
	
	 <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">Locations</a>
    <div class="dropdown-content">
      <a href="https://www.google.com/maps/place/Galo+Mall/@-21.1699174,27.5118047,17z/data=!3m1!4b1!4m5!3m4!1s0x1eb468658c1f08d3:0x432e75fceb562b11!8m2!3d-21.1699224!4d27.5139934">Galo Mall</a>
      <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Masa/@-24.6526162,25.9023574,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5b00b98ad88f:0x2068ef34cd99afdf!8m2!3d-24.6526211!4d25.9045461">Masa Square</a>
      <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Riverwalk/@-24.6766139,25.9336138,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5bf1e8933003:0xd515ef451ed9a5c9!8m2!3d-24.6766188!4d25.9358025">RiverWalk</a>
    </div>
	
    <li><a href="Upcoming.html">Upcoming</a></li>

    <li><a href="ContactUs.html">Contact Us</a></li>

    <li><a href="Feedback.html">FeedBack</a></li>

 
  </li>
</ul>


<div class="slideshow-container">

<div class="mySlides fade">
  <img src="https://images.hdqwalls.com/download/the-batman-red-theme-4k-m3-1336x768.jpg" width="1350" height="700">
  <div class="text">THE BATMAN</div>
</div>

<div class="mySlides fade">
  <img src="https://images.hdqwalls.com/download/sonic-the-hedgehog-2-movie-poster-at-1920x1080.jpg"width="1350" height="700">
  <div class="text">SONIC THE HEDGEHOD 2</div>
</div>

<div class="mySlides fade">
  <img src="https://images.hdqwalls.com/download/2022-morbius-b0-1920x1080.jpg" width="1350" height="700" >
  <div class="text">Caption Three</div>
</div>



<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>

</div>


<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>

<h2>NOW SHOWING</h2>
<table>

  <tr>
	<th>Fantastic Beasts And<br>The Secrets of Dumbledore</th>
	<th>Mr Bones 3</th>
  <th>The Batman</th>

	</tr>

  <tr>
    <td><p><a href="FantasticBeasts.html">
      <img src="http://www.newcapitolcinema.co.bw/tempex/fantastic-beasts-the-secrets-of-dumbledore-med.jpg" width="230" height="350"></a></p>
      <p1><a href="https://www.youtube.com/watch?v=Y9dr2zw-TXQ"><img src="youtube.gif" width="80" height="50"></a></p1>
     
      <div class="dropup">
  <button class="dropbtn">Locations</button>
  <div class="dropup-content">
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Riverwalk/@-24.6766139,25.9336138,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5bf1e8933003:0xd515ef451ed9a5c9!8m2!3d-24.6766188!4d25.9358025">RiverWalk</a>
    <a href="https://www.google.com/maps/place/Galo+Mall/@-21.1699174,27.5118047,17z/data=!3m1!4b1!4m5!3m4!1s0x1eb468658c1f08d3:0x432e75fceb562b11!8m2!3d-21.1699224!4d27.5139934">Galo Mall</a>
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Masa/@-24.6526162,25.9023574,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5b00b98ad88f:0x2068ef34cd99afdf!8m2!3d-24.6526211!4d25.9045461">Masa</a>
  </div>
</div>


     
      <div class="dropup">
  <button class="dropbtn">Show Times</button>
  <div class="dropup-content">
  <br><p1>1300hrs</p1><br><br>
  <p1>1700hrs</p1><br><br>
  <p1>2100hrs</p1><br><br>
  </div>
</div>

      </td>

    <td><p><a href="MrBones.html">
      <img src="http://www.newcapitolcinema.co.bw/tempex/mr-bones-3-son-of-bones-med.jpg"  width="230" height="350"></a></p>
      <p1><a href="https://www.youtube.com/watch?v=1LEsILmgbLk"><img src="youtube.gif" width="80" height="50"></a></p1>
      <p1>
      <div class="dropup">
  <button class="dropbtn">Locations</button>
  <div class="dropup-content">
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Riverwalk/@-24.6766139,25.9336138,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5bf1e8933003:0xd515ef451ed9a5c9!8m2!3d-24.6766188!4d25.9358025">RiverWalk</a>
    <a href="https://www.google.com/maps/place/Galo+Mall/@-21.1699174,27.5118047,17z/data=!3m1!4b1!4m5!3m4!1s0x1eb468658c1f08d3:0x432e75fceb562b11!8m2!3d-21.1699224!4d27.5139934">Galo Mall</a>
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Masa/@-24.6526162,25.9023574,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5b00b98ad88f:0x2068ef34cd99afdf!8m2!3d-24.6526211!4d25.9045461">Masa</a>
  </div>
</div>

      <div class="dropup">
  <button class="dropbtn">Show Times</button>
  <div class="dropup-content">
  <br><p1>1300hrs</p1><br><br>
  <p1>1700hrs</p1><br><br>
  <p1>2100hrs</p1><br><br>
  </div>
</div>

      </td>

    <td><p><a href="TheBatman.html">
      <img src="data:image/webp;base64,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"  width="230" height="350"></a></p>
      <p1><a href="https://www.youtube.com/watch?v=mqqft2x_Aa4"><img src="youtube.gif" width="80" height="50"></a></p1>
      
      <div class="dropup">
  <button class="dropbtn">Locations</button>
  <div class="dropup-content">
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Riverwalk/@-24.6766139,25.9336138,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5bf1e8933003:0xd515ef451ed9a5c9!8m2!3d-24.6766188!4d25.9358025">RiverWalk</a>
    <a href="https://www.google.com/maps/place/Galo+Mall/@-21.1699174,27.5118047,17z/data=!3m1!4b1!4m5!3m4!1s0x1eb468658c1f08d3:0x432e75fceb562b11!8m2!3d-21.1699224!4d27.5139934">Galo Mall</a>
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Masa/@-24.6526162,25.9023574,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5b00b98ad88f:0x2068ef34cd99afdf!8m2!3d-24.6526211!4d25.9045461">Masa</a>
  </div>
</div>


     
      <div class="dropup">
  <button class="dropbtn">Show Times</button>
  <div class="dropup-content">
  <br><p1>1300hrs</p1><br><br>
  <p1>1700hrs</p1><br><br>
  <p1>2100hrs</p1><br><br>
  </div>
</div>

      </td>
  </tr>

  <tr>
	<th>Sonic The HedgeHog 2</th>
	<th>The Bad Guys</th>
  <th>Morbius</th>

	</tr>

  <tr>
    <td><p><a href="Sonic2.html">
      <img src="http://www.newcapitolcinema.co.bw/tempex/sonic-the-hedgehog-2-med.jpg"  width="230" height="350"></a></p>
      <p1><a href="https://www.youtube.com/watch?v=fv_d8zSmVtA"><img src="youtube.gif" width="80" height="50"></a></p1>
      <p1>
      <div class="dropup">
  <button class="dropbtn">Locations</button>
  <div class="dropup-content">
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Riverwalk/@-24.6766139,25.9336138,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5bf1e8933003:0xd515ef451ed9a5c9!8m2!3d-24.6766188!4d25.9358025">RiverWalk</a>
    <a href="https://www.google.com/maps/place/Galo+Mall/@-21.1699174,27.5118047,17z/data=!3m1!4b1!4m5!3m4!1s0x1eb468658c1f08d3:0x432e75fceb562b11!8m2!3d-21.1699224!4d27.5139934">Galo Mall</a>
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Masa/@-24.6526162,25.9023574,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5b00b98ad88f:0x2068ef34cd99afdf!8m2!3d-24.6526211!4d25.9045461">Masa</a>
  </div>
</div>

     
      <div class="dropup">
  <button class="dropbtn">Show Times</button>
  <div class="dropup-content">
  <br><p1>1300hrs</p1><br><br>
  <p1>1700hrs</p1><br><br>
  <p1>2100hrs</p1><br><br>
  </div>
</div>

      </td>

    <td><p><a href="TheBadGuys.html">
      <img src="https://m.media-amazon.com/images/M/MV5BNmM2YjhlZTYtMjMxZi00OTc1LWFlMmUtN2E5YzkyZTNhOGE1XkEyXkFqcGdeQXVyMTA2ODkwNzM5._V1_UX100_CR0,0,100,100_AL_.jpg"  width="230" height="350"></a></p>
      <p1><a href="https://www.youtube.com/watch?v=m8Xt0yXaDPU"><img src="youtube.gif" width="80" height="50"></a></p1>
      
      <div class="dropup">
  <button class="dropbtn">Locations</button>
  <div class="dropup-content">
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Riverwalk/@-24.6766139,25.9336138,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5bf1e8933003:0xd515ef451ed9a5c9!8m2!3d-24.6766188!4d25.9358025">RiverWalk</a>
    <a href="https://www.google.com/maps/place/Galo+Mall/@-21.1699174,27.5118047,17z/data=!3m1!4b1!4m5!3m4!1s0x1eb468658c1f08d3:0x432e75fceb562b11!8m2!3d-21.1699224!4d27.5139934">Galo Mall</a>
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Masa/@-24.6526162,25.9023574,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5b00b98ad88f:0x2068ef34cd99afdf!8m2!3d-24.6526211!4d25.9045461">Masa</a>
  </div>
</div>


     
      <div class="dropup">
  <button class="dropbtn">Show Times</button>
  <div class="dropup-content">
  <br><p1>1300hrs</p1><br><br>
  <p1>1700hrs</p1><br><br>
  <p1>2100hrs</p1><br><br>
  </div>
</div>

      </td>

    <td><p><a href="Morbius.html">
      <img src="data:image/jpeg;base64,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" width="230" height="350"></a></p>
      <p1><a href="https://www.youtube.com/watch?v=oZ6iiRrz1SY"><img src="youtube.gif" width="80" height="50"></a></p1>
      
      <div class="dropup">
  <button class="dropbtn">Locations</button>
  <div class="dropup-content">
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Riverwalk/@-24.6766139,25.9336138,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5bf1e8933003:0xd515ef451ed9a5c9!8m2!3d-24.6766188!4d25.9358025">RiverWalk</a>
    <a href="https://www.google.com/maps/place/Galo+Mall/@-21.1699174,27.5118047,17z/data=!3m1!4b1!4m5!3m4!1s0x1eb468658c1f08d3:0x432e75fceb562b11!8m2!3d-21.1699224!4d27.5139934">Galo Mall</a>
    <a href="https://www.google.com/maps/place/New+Capitol+Cinemas+-+Masa/@-24.6526162,25.9023574,17z/data=!3m1!4b1!4m5!3m4!1s0x1ebb5b00b98ad88f:0x2068ef34cd99afdf!8m2!3d-24.6526211!4d25.9045461">Masa</a>
  </div>
</div>


     
      <div class="dropup">
  <button class="dropbtn">Show Times</button>
  <div class="dropup-content">
  <br><p1>1300hrs</p1><br><br>
  <p1>1700hrs</p1><br><br>
  <p1>2100hrs</p1><br><br>
  </div>
</div>

      </td>
  </tr>
</table>
<br>
<br>
<br>

</body>
</html>
