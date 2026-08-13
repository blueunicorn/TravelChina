<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>TravelChina - Your Smart Travel Companion</title>
<link rel="stylesheet" href="https://blueunicorn.github.io/TravelChina/assets/swiper-bundle.min.css">
<script src="https://blueunicorn.github.io/TravelChina/assets/swiper-bundle.min.js"></script>
<style>
:root{
    --primary:#082b6f;
    --primary2:#0e4bb8;
    --gold:#f5b942;
    --light:#f7f9fc;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:
        -apple-system,
        BlinkMacSystemFont,
        "Segoe UI",
        "PingFang SC",
        "Hiragino Sans GB",
        "Microsoft YaHei",
        "Noto Sans",
        Arial,
        sans-serif;
    color:#222;
    line-height:1.6;
}

a{
    text-decoration:none;
}

.container{
    width:min(1200px,92%);
    margin:auto;
}

.hero{

    background:
    linear-gradient(135deg,#082b6f,#0e4bb8);

    color:white;
    text-align:center;

    padding:120px 20px;
}

.hero h1{
    font-size:4.5rem;
    margin-bottom:20px;
}

.hero p{
    max-width:850px;
    margin:auto;
    opacity:.95;
    font-size:1.15rem;
}

.btn{

    display:inline-block;

    margin-top:35px;

    background:var(--gold);
    color:#111;

    padding:18px 38px;

    border-radius:50px;

    font-weight:700;

    transition:.3s;
}

.btn:hover{

    transform:translateY(-4px);

}

.section{
    padding:90px 0;
}

.section-title{

    text-align:center;

    color:var(--primary);

    font-size:2.7rem;

    margin-bottom:20px;
}

.section-subtitle{

    text-align:center;

    max-width:850px;

    margin:auto;
    margin-bottom:60px;

    color:#666;
}

.features{

    display:grid;

    grid-template-columns:
    repeat(auto-fit,minmax(280px,1fr));

    gap:25px;
}

.card{

    background:white;

    padding:30px;

    border-radius:20px;

    box-shadow:
    0 10px 25px rgba(0,0,0,.08);
}

.card h3{

    color:var(--primary);

    margin-bottom:12px;
}

.gallery-section{

    background:#f8fafc;
}

.screenshotSwiper{

    width:100%;
    padding:20px 0 80px;
}

.swiper-slide{

    display:flex;
    justify-content:center;
    align-items:center;
}

.swiper-slide img{

    width:100%;
    max-width:380px;

    border-radius:30px;

    box-shadow:
    0 25px 50px rgba(0,0,0,.18);

    transition:.3s;
}

.swiper-slide img:hover{

    transform:translateY(-8px);
}

.swiper-button-next,
.swiper-button-prev{

    color:var(--primary);
}

.swiper-pagination-bullet-active{

    background:var(--gold);
}

.why{

    background:white;
}

.why-grid{

    display:grid;

    grid-template-columns:
    repeat(auto-fit,minmax(250px,1fr));

    gap:20px;
}

.why-item{

    background:#f7f9fc;

    padding:25px;

    border-radius:16px;
}

.why-item h4{

    color:var(--primary);

    margin-bottom:10px;
}

.cta{

    background:
    linear-gradient(135deg,#082b6f,#0e4bb8);

    color:white;

    text-align:center;

    padding:100px 20px;
}

.cta h2{

    font-size:3rem;

    margin-bottom:20px;
}

.footer{

    padding:30px;

    text-align:center;

    color:#666;
}

@media(max-width:768px){

.hero h1{

font-size:2.8rem;

}

.section-title{

font-size:2rem;

}

.cta h2{

font-size:2rem;

}

}

</style>

</head>

<body>
<section class="section gallery-section">

<div class="container">

<h2 class="section-title">
App Screenshots
</h2>

<p class="section-subtitle">
Swipe, drag or wait for automatic slideshow.
</p>

<div class="swiper screenshotSwiper">

<div class="swiper-wrapper">

<div class="swiper-slide">
<img src="https://blueunicorn.github.io/TravelChina/images/Designer-1.png"/>
</div>

<div class="swiper-slide">
<img src="https://blueunicorn.github.io/TravelChina/images/Designer-2.png"/>
</div>

<div class="swiper-slide">
<img src="https://blueunicorn.github.io/TravelChina/images/Designer-3.png"/>
</div>

<div class="swiper-slide">
<img src="https://blueunicorn.github.io/TravelChina/images/Designer-4.png"/>
</div>

<div class="swiper-slide">
<img src="https://blueunicorn.github.io/TravelChina/images/Designer-5.png"/>
</div>

<div class="swiper-slide">
<img src="https://blueunicorn.github.io/TravelChina/images/Designer-6.png"/>
</div>

<div class="swiper-slide">
<img src="https://blueunicorn.github.io/TravelChina/images/Designer-7.png"/>
</div>

</div>

<div class="swiper-pagination"></div>

<div class="swiper-button-next"></div>
<div class="swiper-button-prev"></div>

</div>

</div>

</section>
<section class="hero">

<div class="container">

<h1>TravelChina</h1>

<p>
Your Smart Travel Companion for Exploring China.
Discover over 950 attractions, city guides, metro maps,
travel phrases, ticket prices, transportation information,
favorites and smart search in one powerful app.
</p>

<a
class="btn"
href="https://play.google.com/store/apps/details?id=com.travelchina"
target="_blank">

Download on Google Play

</a>

</div>

</section>

<section class="section">

<div class="container">

<h2 class="section-title">
Why TravelChina
</h2>

<p class="section-subtitle">
Built for international travelers visiting China.
Everything you need in one app.
</p>

<div class="features">

<div class="card">
<h3>🏛️ 950+ Attractions</h3>
<p>
Detailed attraction guides, descriptions,
ratings, opening times and ticket prices.
</p>
</div>

<div class="card">
<h3>🏙️ 33 City Guides</h3>
<p>
Explore China's major cities with practical
travel information and local insights.
</p>
</div>

<div class="card">
<h3>🚇 Metro Maps</h3>
<p>
Official metro maps and transportation
guides for 33 Chinese cities.
</p>
</div>

<div class="card">
<h3>💬 Daily Phrases</h3>
<p>
200+ essential Chinese phrases with
pronunciation support.
</p>
</div>

<div class="card">
<h3>🔍 Smart Search</h3>
<p>
Quickly find attractions, cities and
travel information.
</p>
</div>

<div class="card">
<h3>❤️ Favorites</h3>
<p>
Save attractions and organize your trip
with ease.
</p>
</div>

</div>

</div>

</section>



<section class="section why">

<div class="container">

<h2 class="section-title">
Everything You Need in China
</h2>

<div class="why-grid">

<div class="why-item">
<h4>🌏 Multi-language Support</h4>
<p>Search and travel with confidence.</p>
</div>

<div class="why-item">
<h4>📍 Transportation Info</h4>
<p>Metro, routes and airport connections.</p>
</div>

<div class="why-item">
<h4>⭐ Ratings & Reviews</h4>
<p>Find the best attractions quickly.</p>
</div>

<div class="why-item">
<h4>📱 Offline-Friendly Access</h4>
<p>Essential travel information anytime.</p>
</div>

</div>

</div>

</section>

<section class="cta">

<h2>Ready to Explore China?</h2>

<p>
Download TravelChina today and make every journey easier.
</p>

<a
class="btn"
href="https://play.google.com/store/apps/details?id=com.travelchina"
target="_blank">

Get It On Google Play

</a>

</section>

<footer class="footer">

© 2026 TravelChina

</footer>

<script>

new Swiper(".screenshotSwiper", {

    loop:true,

    centeredSlides:true,

    grabCursor:true,

    speed:900,

    effect:"coverflow",

    coverflowEffect:{
        rotate:0,
        stretch:0,
        depth:180,
        modifier:2,
        slideShadows:false
    },

    autoplay:{
        delay:2500,
        disableOnInteraction:false,
        pauseOnMouseEnter:true
    },

    pagination:{
        el:".swiper-pagination",
        clickable:true
    },

    navigation:{
        nextEl:".swiper-button-next",
        prevEl:".swiper-button-prev"
    },

    breakpoints:{

        0:{
            slidesPerView:1
        },

        768:{
            slidesPerView:2
        },

        1200:{
            slidesPerView:3
        }

    }

});

</script>

</body>
</html>
