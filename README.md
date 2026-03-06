

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

/* SEMBUNYIKAN JUDUL REPOSITORY GITHUB */
h1:first-child{
display:none;
}

/* HEADER */

header{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
color:white;
padding:15px 40px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo img{
height:55px;
}

nav a{
color:white;
margin-left:25px;
text-decoration:none;
font-weight:500;
}

/* HERO */

.hero{
min-height:80vh;
display:flex;
align-items:center;
justify-content:space-between;
padding:60px 10%;
background:linear-gradient(120deg,#F6F1E7,#EFE3FF);
}

.hero-text{
max-width:520px;
}

.hero-text h1{
font-size:46px;
color:#5E2A84;
margin-bottom:20px;
}

.hero-text p{
font-size:18px;
margin-bottom:30px;
line-height:1.6;
}

/* TOMBOL */

.btn{
background:#C9A25D;
color:white;
padding:14px 30px;
border-radius:30px;
text-decoration:none;
font-weight:600;
display:inline-block;
}

/* GAMBAR PRODUK */

.hero-img img{
width:340px;
mix-blend-mode:multiply;
}

/* SECTION */

.section{
padding:80px 10%;
text-align:center;
}

.section h2{
font-size:32px;
color:#5E2A84;
margin-bottom:40px;
}

/* FITUR */

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:30px;
}

.feature{
background:white;
padding:25px;
border-radius:12px;
box-shadow:0 6px 20px rgba(0,0,0,0.08);
}

/* PRODUK */

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:40px;
}

.product-card{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 10px 25px rgba(0,0,0,0.08);
transition:0.3s;
}

.product-card:hover{
transform:translateY(-8px);
}

.product-img img{
width:200px;
margin-bottom:15px;
}

.price{
font-size:20px;
font-weight:600;
margin:10px 0 20px 0;
}

/* TESTIMONI */

.testimonial{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 8px 20px rgba(0,0,0,0.08);
margin-top:20px;
}

/* CTA */

.cta{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
color:white;
padding:80px 20px;
text-align:center;
}

/* FOOTER */

footer{
background:#3E1A5C;
color:white;
padding:30px;
text-align:center;
}

/* WHATSAPP FLOAT */

.wa-float{
position:fixed;
bottom:25px;
right:25px;
background:#25D366;
color:white;
font-size:28px;
width:60px;
height:60px;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
text-decoration:none;
box-shadow:0 5px 15px rgba(0,0,0,0.2);
}

@media(max-width:900px){

.hero{
flex-direction:column;
text-align:center;
}

.hero-img{
margin-top:40px;
}

}

</style>

</head>

<body>

<header>

<div class="logo">
<img src="logo.png">
</div>

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

<div class="hero-text">

<h1>Telserahe: Telang Segar, Serai & Jahe</h1>

<p>
Minuman herbal alami dengan perpaduan bunga telang, serai, jahe dan madu.
Segar, sehat, dan cocok diminum kapan saja.
</p>

<a class="btn" href="#produk">Pesan Sekarang</a>

</div>

<div class="hero-img">
<img src="produk.png">
</div>

</section>

<!-- MANFAAT -->

<section class="section" id="manfaat">

<h2>Manfaat Bahan Alami</h2>

<div class="features">

<div class="feature">
<h3>🌸 Bunga Telang</h3>
<p>Kaya antioksidan dan baik untuk kesehatan tubuh.</p>
</div>

<div class="feature">
<h3>🌿 Serai</h3>
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

<section class="section" id="produk">

<h2>Produk Kami</h2>

<div class="products">

<div class="product-card">

<div class="product-img">
<img src="produk250.png">
</div>

<h3>Telserahe 250ml</h3>

<p>Ukuran praktis untuk aktivitas sehari-hari.</p>

<div class="price">Rp 6.000</div>

<a class="btn" target="_blank"
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe,%0ASaya%20ingin%20memesan%20Telserahe%20250ml.%0AJumlah%20:%20...%20botol%0ANama%20:%20%0AAlamat%20:%20">
Pesan via WhatsApp
</a>

</div>

<div class="product-card">

<div class="product-img">
<img src="produk500.png">
</div>

<h3>Telserahe 500ml</h3>

<p>Ukuran lebih besar untuk dinikmati bersama.</p>

<div class="price">Rp 10.000</div>

<a class="btn" target="_blank"
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe,%0ASaya%20ingin%20memesan%20Telserahe%20500ml.%0AJumlah%20:%20...%20botol%0ANama%20:%20%0AAlamat%20:%20">
Pesan via WhatsApp
</a>

</div>

</div>

</section>

<!-- TESTIMONI -->

<section class="section" id="testimoni">

<h2>Testimoni Pelanggan</h2>

<div class="testimonial">
⭐️⭐️⭐️⭐️⭐️
<p>"Minumannya segar banget, rasa jahenya pas dan aromanya wangi!"</p>
</div>

<div class="testimonial">
⭐️⭐️⭐️⭐️⭐️
<p>"Unik! Warna telangnya cantik dan rasanya menyehatkan."</p>
</div>

</section>

<!-- CTA -->

<section class="cta">

<h2>Segarkan Harimu dengan Telserahe</h2>

<p>Minuman herbal alami yang sehat dan menyegarkan.</p>

<br>

<a class="btn"
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe,%20saya%20ingin%20memesan%20produk.">
Pesan Sekarang
</a>

</section>

<!-- KONTAK -->

<section class="section" id="kontak">

<h2>Kontak Kami</h2>

<p>WhatsApp : 082182167104</p>
<p>Instagram : @telserahee_telang</p>
<p>Tiktok : @telserahe_telang</p>

</section>

<footer>

<p>© 2026 Telserahe - Telang Segar, Serai & Jahe</p>

</footer>

<a href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe,%20saya%20ingin%20bertanya%20tentang%20produk." 
class="wa-float">💬</a>

</body>
