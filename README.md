
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
background:linear-gradient(120deg,#F6F1E7,#EDE4FF);
color:#333;
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
height:50px;
}

nav a{
color:white;
margin-left:25px;
text-decoration:none;
font-weight:500;
}

/* HERO */

.hero{
min-height:85vh;
display:flex;
align-items:center;
justify-content:space-between;
padding:80px 10%;
position:relative;
}

/* background logo */

.hero::before{
content:"";
position:absolute;
width:500px;
height:500px;
background:url("logo.png") no-repeat center;
background-size:contain;
opacity:0.05;
left:0;
top:50%;
transform:translateY(-50%);
}

/* TEXT */

.hero-text{
max-width:550px;
z-index:1;
}

.hero-text h1{
font-size:56px;
color:#5E2A84;
margin-bottom:10px;
font-weight:700;
}

.hero-text h2{
font-size:26px;
color:#7B3FB2;
margin-bottom:25px;
}

.hero-text p{
font-size:18px;
margin-bottom:35px;
line-height:1.6;
}

/* BUTTON */

.btn{
background:#C9A25D;
color:white;
padding:15px 32px;
border-radius:30px;
text-decoration:none;
font-weight:600;
font-size:16px;
}

/* PRODUCT IMAGE */

.hero-img{
display:flex;
align-items:flex-end;
gap:20px;
}

.hero-img img{
width:220px;
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

/* FEATURES */

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:30px;
}

.feature{
background:white;
padding:30px;
border-radius:12px;
box-shadow:0 6px 20px rgba(0,0,0,0.08);
}

/* PRODUCT CARD */

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
}

.product-img img{
width:200px;
}

.price{
font-size:22px;
font-weight:600;
margin:10px 0 20px;
}

/* CTA */

.cta{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
color:white;
padding:80px 20px;
text-align:center;
}

footer{
background:#3E1A5C;
color:white;
padding:30px;
text-align:center;
}

/* WA FLOAT */

.wa{
position:fixed;
bottom:25px;
right:25px;
background:#25D366;
width:60px;
height:60px;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
font-size:28px;
color:white;
text-decoration:none;
}

/* MOBILE */

@media(max-width:900px){

.hero{
flex-direction:column;
text-align:center;
}

.hero-img{
margin-top:40px;
}

.hero-img img{
width:180px;
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
<a href="#kontak">Kontak</a>
</nav>

</header>

<!-- HERO -->

<section class="hero" id="home">

<div class="hero-text">

<h1>TELSERAHE</h1>

<h2>Telang Segar, Serai & Jahe</h2>

<p>
Minuman herbal alami dari bunga telang, serai, jahe dan madu.
Segar, sehat, dan cocok diminum kapan saja.
</p>

<a class="btn"
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe,%20saya%20ingin%20memesan%20produk.">
Pesan Sekarang
</a>

</div>

<div class="hero-img">

<img src="produk250.png">
<img src="produk500.png">

</div>

</section>

<!-- MANFAAT -->

<section class="section" id="manfaat">

<h2>Manfaat Bahan Alami</h2>

<div class="features">

<div class="feature">
<h3>🌸 Bunga Telang</h3>
<p>Kaya antioksidan untuk kesehatan tubuh.</p>
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
<p>Pemanis alami yang menambah energi.</p>
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

<div class="price">Rp 6.000</div>

<a class="btn"
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe,%0ASaya%20ingin%20memesan%20250ml.%0AJumlah%20:%20">
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
href="https://wa.me/6282182167104?text=Halo%20Admin%20Telserahe,%0ASaya%20ingin%20memesan%20500ml.%0AJumlah%20:%20">
Pesan
</a>

</div>

</div>

</section>

<!-- FOOTER -->

<footer>

<p>© 2026 Telserahe - Telang Segar, Serai & Jahe</p>

</footer>

<a href="https://wa.me/6282182167104" class="wa">💬</a>

</body>
