# food-website
a restaurent website has been created by using html css and java
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Chinese Restaurant</title>
   <!-- font awesome cdn link  -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
   <link rel="stylesheet" href="https://unpkg.com/swiper@7/swiper-bundle.min.css" />
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery-js/1.4.0/css/lightgallery.min.css">
   <!-- custom css file link  -->
   <link rel="stylesheet" href="css/style.css">
</head>
<body>
<!-- header section starts     -->
<section class="header">
   <a href="#" class="logo"> <i class="fas fa-utensils"></i> food. </a>
   <nav class="navbar">
      <a href="#home">home</a>
      <a href="#about">about</a>
      <a href="#food">food</a>
      <a href="#menu">menu</a>
      <a href="#gallery">gallery</a>
      <a href="#order">order</a>
   </nav>
   <div id="menu-btn" class="fas fa-bars"></div>
</section>
<!-- header section ends    -->
<!-- home section starts  -->
<marquee><p style="font-size:20px">*YOU MUST CONNECTED TO INTERNET TO VIEW THIS WEB PAGE *</p></marquee>
<section class="home" id="home">
   <div class="swiper home-slider">
      <div class="swiper-wrapper">
         <div class="swiper-slide slide" style="background: url(images/home-slide-1.jpg) no-repeat;">
            <div class="content">
               <span>outstanding food</span>
               <h3>delicious cooking</h3>
               <a href="#" class="btn">get started</a>
            </div>
         </div>
         <div class="swiper-slide slide" style="background: url(images/home-slide-2.jpg) no-repeat;">
            <div class="content">
               <span>outstanding food</span>
               <h3>morning moment</h3>
               <a href="#" class="btn">get started</a>
            </div>
         </div>
         <div class="swiper-slide slide" style="background: url(images/home-slide-3.jpg) no-repeat;">
            <div class="content">
               <span>outstanding food</span>
               <h3>authentic kitchen</h3>
               <a href="#" class="btn">get started</a>
            </div>
         </div>
      </div>
      <div class="swiper-button-next"></div>
      <div class="swiper-button-prev"></div>
   </div>
</section>
<!-- home section ends -->
<!-- about section starts  -->
<section class="about" id="about">
   <div class="image">
      <img src="images/about-img.png" alt="">
   </div>
   <div class="content">
      <h3 class="title">welcome to our Chinese Restaurant</h3>
      <p>A well-run Restaurant is like a winning baseball team.It makes the most of every crew member's talent and takes advantage of every split-second oppurtunity to speed up service.</p>
      <a  class="btn">read more</a>
      <div class="icons-container">
         <div class="icons">
            <img src="images/about-icon-1.png" alt="">
            <h3>quality food</h3>
         </div>
         <div class="icons">
            <img src="images/about-icon-2.png" alt="">
            <h3>food & drinks</h3>
         </div>
         <div class="icons">
            <img src="images/about-icon-3.png" alt="">
            <h3>expert chefs</h3>
         </div>
      </div>
   </div>
</section>
<!-- about section ends -->
<!-- food section starts  -->
<section class="food" id="food">
   <div class="heading">
      <span>popular dishes</span>
      <h3>our delicious food</h3>
   </div>
   <div class="swiper food-slider">
      <div class="swiper-wrapper">
         <div class="swiper-slide slide" data-name="food-2">
            <img src="images/food-img-2.png" alt="">
            <h3>spl egg salad</h3>
            <div class="price">289\-</div>
         </div>
         <div class="swiper-slide slide" data-name="food-3">
            <img src="images/food-img-3.png" alt="">
            <h3>chicken wings</h3>
            <div class="price">349/-</div>
         </div>
         <div class="swiper-slide slide" data-name="food-4">
            <img src="images/food-img-4.png" alt="">
            <h3>Non-Veg salad</h3>
            <div class="price">449/-</div>
         </div>
         <div class="swiper-slide slide" data-name="food-5">
            <img src="images/food-img-5.png" alt="">
            <h3>Baked meat</h3>
            <div class="price">519/-
            </div>
         </div>
      </div>
      <div class="swiper-pagination"></div>
   </div>
</section>
<!-- food section ends -->
<!-- gallery section starts  -->
<section class="gallery" id="gallery">
   <div class="heading">
      <span>our gallery</span>
      <h3>our untold stories</h3>
   </div>
   <div class="gallery-container">
      <a href="images/food-galler-img-1.jpg" class="box">
         <img src="images/food-galler-img-1.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
      <a href="images/food-galler-img-2.jpg" class="box">
         <img src="images/food-galler-img-2.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
      <a href="images/food-galler-img-3.jpg" class="box">
         <img src="images/food-galler-img-3.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
      <a href="images/food-galler-img-4.jpg" class="box">
         <img src="images/food-galler-img-4.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
      <a href="images/food-galler-img-5.jpg" class="box">
         <img src="images/food-galler-img-5.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
      <a href="images/food-galler-img-6.jpg" class="box">
         <img src="images/food-galler-img-6.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
   </div>
</section>
<!-- gallery section ends -->
<!-- menu section starts  -->
<section class="menu" id="menu">
   <div class="heading">
      <span>our menu</span>
      <h3>our popular dishes</h3>
   </div>
   <div class="swiper menu-slider">
      <div class="swiper-wrapper">
         <div class="swiper-slide slide">
            <h3 class="title">breakfast</h3>
            <div class="box-container">
               <div class="box">
                  <div class="info">
                     <h3>Chai</h3>
                     <p>Morning Beast</p>
                  </div>
                  <div class="price">49/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Garlic bread</h3>
                     <p>Breakfast</p>
                  </div>
                  <div class="price">149/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Freshly squeezed orange juice.</h3>
                     <p>Prevents Energy</p>
                  </div>
                  <div class="price">149/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>aloo paratha</h3>
                     <p>Includes Onion</p>
                  </div>
                  <div class="price">149/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Cold coffee</h3>
                     <p>Cappuccino </p>
                  </div>
                  <div class="price">129/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Masala dosa</h3>
                     <p>spicy</p>
                  </div>
                  <div class="price">89/-</div>
               </div>
            </div>
         </div>
         <div class="swiper-slide slide">
            <h3 class="title">lunch</h3>
            <div class="box-container">
               <div class="box">
                  <div class="info">
                     <h3>chicken manchuria</h3>
                     <p>Specially from China</p>
                  </div>
                  <div class="price">159/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>chicken biriyani</h3>
                     <p>Delicious!</p>
                  </div>
                  <div class="price">249/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>kubani ka meetha</h3>
                     <p>Sweet</p>
                  </div>
                  <div class="price">249/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Urricas</h3>
                     <p>Appricot</p>
                  </div>
                  <div class="price">199/-</div>
               </div>
            </div>
         </div>
         <div class="swiper-slide slide">
            <h3 class="title">dinner</h3>
            <div class="box-container">
               <div class="box">
                  <div class="info">
                     <h3>Okonomiyaki</h3>
                     <p>Specially from Japan</p>
                  </div>
                  <div class="price">349/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>lasagna</h3>
                     <p>Special for Dinner</p>
                  </div>
                  <div class="price">349/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>fried rice</h3>
                     <p>indian</p>
                  </div>
                  <div class="price">249/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>chicken noodles</h3>
                     <p> dolor sit amet </p>
                  </div>
                  <div class="price">$49.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Fugu</h3>
                     <p>Energetic</p>
                  </div>
                  <div class="price">249/-</div>
               </div>
            </div>
         </div>
         <div class="swiper-slide slide">
            <h3 class="title">drinks</h3>
            <div class="box-container">
               <div class="box">
                  <div class="info">
                     <h3>Fountain soda</h3>
                     <p>Cold drink</p>
                  </div>
                  <div class="price">119</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>badam milk</h3>
                     <p>Cold drink</p>
                  </div>
                  <div class="price">129.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Sweet Lassi</h3>
                     <p>Cold drink</p>
                  </div>
                  <div class="price">119/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>pepsi</h3>
                     <p>Cold drink</p>
                  </div>
                  <div class="price">79/-</div>
               </div>
            </div>
         </div>
         <div class="swiper-slide slide">
            <h3 class="title">dessert</h3>
            <div class="box-container">
               <div class="box">
                  <div class="info">
                     <h3>black current cake</h3>
                     <p>Cake</p>
                  </div>
                  <div class="price">349/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>french fries</h3>
                     <p>Best of Menu</p>
                  </div>
                  <div class="price">149/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>macaroons</h3>
                     <p>sliced cheese</p>
                  </div>
                  <div class="price">129/-</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>CHURROS</h3>
                     <p>Chips</p>
                  </div>
                  <div class="price">149/-</div>
               </div>
            </div>
         </div>
      </div>
      <div class="swiper-pagination"></div>
   </div>
</section>
<!-- menu section ends -->
<!-- footer section starts  -->
<section class="footer">
   <div class="icons-container">
      <div class="icons">
         <i class="fas fa-clock"></i>
         <h3>opening hours</h3>
         <p>11:00am to 10:00pm</p>
      </div>
      <div class="icons">
         <i class="fas fa-phone"></i>
         <h3>phone</h3>
         <p>+91-9030870721</p>
         <p>+91-7997914015</p>
         <p>+91-9676324814<p>
      </div>
      <div class="icons">
         <i class="fas fa-envelope"></i>
         <h3>email</h3>
         <p>yaswanthmaradana16@gmail.com</p>
         <p>srikokulaputrilocknadh3545@gmail.com</p>
         <p>0.ravitejabathini.0@gmail.com</p>
         <p></p>
      </div>
      <div class="icons">
         <i class="fas fa-map"></i>
         <h3>address</h3>
         <p>Phagwara ,India-144401</p>
      </div>
   </div>
   <div class="share">
      <a href="https://www.facebook.com/badri.nadh.10?mibextid=ZbWKwL" target="_blank" class="fab fa-facebook-f"></a>
      <a href="https://www.instagram.com/yaswanth_maradana/" target="_blank" class="fab fa-instagram"></a>
   </div>
   <div class="credit"> created by <span>Yaswanth,Trilock and Ravi teja</span> | all rights reserved! | From K22HW</div>
</section>
<!-- footer section ends  -->
<script src="https://unpkg.com/swiper@7/swiper-bundle.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery-js/1.4.0/js/lightgallery.min.js"></script>
<!-- custom js file link  -->
<script src="js/script.js"></script>
<script>
   lightGallery(document.querySelector('.gallery .gallery-container'));
</script>
</body>
</html>
