
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Telserahe</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
box-sizing:border-box;
margin:0;
padding:0;
}

body{
font-family:'Poppins',sans-serif;
background:#F6F1E7;
color:#333;
}

.container{
max-width:1100px;
margin:auto;
padding:0 20px;
}

/* HEADER */

header{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
padding:15px 0;
}

nav{
display:flex;
justify-content:center;
gap:25px;
}

nav a{
color:white;
text-decoration:none;
font-weight:500;
}

/* HERO */

.hero{
display:flex;
align-items:center;
justify-content:space-between;
gap:40px;
padding:70px 0;
background:linear-gradient(120deg,#F6F1E7,#EFE3FF);
position:relative;
overflow:hidden;
}

.hero::before{
content:"";
position:absolute;
width:420px;
height:420px;
background:url("logo.png") no-repeat center;
background-size:contain;
opacity:0.06;
left:50%;
top:50%;
transform:translate(-50%,-50%);
}

.hero-text{
max-width:480px;
z-index:2;
}

.brand{
font-size:34px;
font-weight:700;
color:#5E2A84;
margin-bottom:15px;
}

.hero-text p{
font-size:17px;
margin-bottom:25px;
line-height:1.6;
}

.btn{
background:#C9A25D;
color:white;
padding:12px 26px;
border-radius:30px;
text-decoration:none;
font-weight:600;
display:inline-block;
}

.hero-img img{
width:260px;
}

/* SECTION */

.section{
padding:70px 0;
text-align:center;
}

.section h2{
font-size:28px;
color:#5E2A84;
margin-bottom:40px;
}

/* FEATURES */

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:25px;
}

.feature{
background:white;
padding:22px;
border-radius:12px;
box-shadow:0 5px 18px rgba(0,0,0,0.08);
}

/* PRODUK */

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:30px;
}

.product-card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 8px 22px rgba(0,0,0,0.08);
}

.product-img img{
width:160px;
}

.price{
font-size:20px;
font-weight:600;
margin:10px 0 18px;
}

/* TESTIMONI */

.testimoni{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.testi-card{
background:white;
padding:25px;
border-radius:12px;
box-shadow:0 6px 20px rgba(0,0,0,0.08);
}

/* SOSIAL MEDIA */

.social-links{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
}

.social-links a{
text-decoration:none;
padding:12px 20px;
border-radius:25px;
color:white;
font-weight:500;
}

.wa-btn{background:#25D366;}
.ig-btn{background:#E1306C;}
.tt-btn{background:#000;}

/* CTA */

.cta{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
color:white;
padding:70px 20px;
text-align:center;
}

/* FOOTER */

footer{
background:#3E1A5C;
color:white;
padding:25px;
text-align:center;
}

/* FLOAT WA */

.wa-float{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
width:55px;
height:55px;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
font-size:25px;
color:white;
text-decoration:none;
box-shadow:0 5px 15px rgba(0,0,0,0.3);
}

/* MOBILE */

@media(max-width:900px){

.hero{
flex-direction:column;
text-align:center;
}

.hero-img img{
margin-top:25px;
width:200px;
}

.brand{
font-size:26px;
}

}

</style>

</head>

<body>

<header>

<nav>
<a href="#home">Home</a>
<a href="#manfaat">Manfaat</a>
<a href="#produk">Produk</a>
<a href="#testimoni">Testimoni</a>
<a href="#kontak">Kontak</a>
</nav>

</header>

<!-- HERO -->

<section class="hero" id="home">

<div class="container hero">

<div class="hero-text">

<div class="brand">
Telserahe : Telang Segar, Serai & Jahe
</div>

<p>
Minuman herbal alami dengan perpaduan bunga telang, serai, jahe dan madu.
Segar, sehat, dan cocok diminum kapan saja.
</p>

<a class="btn"
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe%20%F0%9F%91%8B%0ASaya%20ingin%20memesan%20produk%20Telserahe.">
Pesan Sekarang
</a>

</div>

<div class="hero-img">
<img src="produk.png">
</div>

</div>

</section>

<!-- MANFAAT -->

<section class="section container" id="manfaat">

<h2>Manfaat Bahan Alami</h2>

<div class="features">

<div class="feature">
<h3>🌸 Bunga Telang</h3>
<p>Kaya antioksidan dan baik untuk kesehatan tubuh.</p>
</div>

<div class="feature">
<h3>🌿 Sereh</h3>
<p>Menyegarkan tubuh dan membantu detoks alami.</p>
</div>

<div class="feature">
<h3>🫚 Jahe</h3>
<p>Menghangatkan tubuh dan meningkatkan imun.</p>
</div>

<div class="feature">
<h3>🍯 Madu</h3>
<p>Pemanis alami yang sehat dan menambah energi.</p>
</div>

</div>

</section>

<!-- PRODUK -->

<section class="section container" id="produk">

<h2>Produk Kami</h2>

<div class="products">

<div class="product-card">

<div class="product-img">
<img src="produk250.png">
</div>

<h3>Telserahe 250ml</h3>

<div class="price">Rp 6.000</div>

<a class="btn"
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe%20%F0%9F%91%8B%0ASaya%20ingin%20memesan%20Telserahe%20250ml.">
Pesan
</a>

</div>

<div class="product-card">

<div class="product-img">
<img src="produk500.png">
</div>

<h3>Telserahe 500ml</h3>

<div class="price">Rp 10.000</div>

<a class="btn"
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe%20%F0%9F%91%8B%0ASaya%20ingin%20memesan%20Telserahe%20500ml.">
Pesan
</a>

</div>

</div>

</section>

<!-- TESTIMONI -->

<section class="section container" id="testimoni">

<h2>Testimoni Pelanggan</h2>

<div class="testimoni">

<div class="testi-card">
⭐️⭐️⭐️⭐️⭐️  
"Rasanya segar banget, jahenya terasa tapi tetap ringan."
</div>

<div class="testi-card">
⭐️⭐️⭐️⭐️⭐️  
"Warna telangnya cantik, rasanya unik dan sehat."
</div>

<div class="testi-card">
⭐️⭐️⭐️⭐️⭐️  
"Cocok diminum dingin, apalagi siang hari."
</div>

</div>

</section>

<!-- SOSIAL MEDIA -->

<section class="section container" id="kontak">

<h2>Media Sosial</h2>

<div class="social-links">

<a class="wa-btn"
href="https://wa.me/6282182167104">
WhatsApp
</a>

<a class="ig-btn"
href="https://instagram.com/telserahee_telang">
Instagram
</a>

<a class="tt-btn"
href="https://tiktok.com/@telserahe_telang">
TikTok
</a>

</div>

</section>

<footer>

<p>© 2026 Telserahe</p>

</footer>

<a class="wa-float"
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe%20%F0%9F%91%8B%20Saya%20ingin%20bertanya%20tentang%20produk.">
💬
</a>

</body>
