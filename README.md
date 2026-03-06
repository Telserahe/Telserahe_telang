

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Telserahe</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
box-sizing:border-box;
margin:0;
padding:0
}

body{
font-family:'Poppins',sans-serif;
background:#F6F1E7;
color:#333
}

/* HEADER */

header{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
color:white;
padding:20px 40px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo img{
height:50px
}

nav a{
color:white;
margin-left:25px;
text-decoration:none;
font-weight:500
}

/* HERO */

.hero{
min-height:80vh;
display:flex;
align-items:center;
justify-content:space-between;
padding:60px 10%;
background:linear-gradient(120deg,#F6F1E7,#EFE3FF);
position:relative;
}

/* LOGO BACKGROUND */

.hero::before{
content:"";
position:absolute;
width:500px;
height:500px;
background:url("logo.png") no-repeat center;
background-size:contain;
opacity:0.06;
left:50%;
top:50%;
transform:translate(-50%,-50%);
}

/* HERO TEXT */

.hero-text{
max-width:500px;
z-index:1;
}

.hero-text h1{
font-size:48px;
color:#5E2A84;
margin-bottom:15px
}

.hero-text h2{
font-size:26px;
color:#7B3FB2;
margin-bottom:20px
}

.hero-text p{
font-size:18px;
margin-bottom:30px;
line-height:1.6
}

/* BUTTON */

.btn{
background:#C9A25D;
color:white;
padding:14px 30px;
border-radius:30px;
text-decoration:none;
font-weight:600;
display:inline-block
}

/* HERO IMAGE */

.hero-img img{
width:320px;
z-index:1;
}

/* SECTION */

.section{
padding:80px 10%;
text-align:center
}

.section h2{
font-size:32px;
color:#5E2A84;
margin-bottom:40px
}

/* FEATURES */

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:30px
}

.feature{
background:white;
padding:25px;
border-radius:12px;
box-shadow:0 6px 20px rgba(0,0,0,0.08)
}

/* PRODUCTS */

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:40px
}

.product-card{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 10px 25px rgba(0,0,0,0.08);
transition:0.3s
}

.product-card:hover{
transform:translateY(-8px)
}

.product-img img{
width:200px;
margin-bottom:20px
}

.price{
font-size:20px;
font-weight:600;
margin:10px 0 20px 0
}

/* TESTIMONI */

.testimonial{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 8px 20px rgba(0,0,0,0.08);
margin-top:20px
}

/* CTA */

.cta{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
color:white;
padding:80px 20px;
text-align:center
}

/* FOOTER */

footer{
background:#3E1A5C;
color:white;
padding:30px;
text-align:center
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

/* MOBILE */

@media(max-width:900px){

.hero{
flex-direction:column;
text-align:center
}

.hero-img{
margin-top:40px
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

<section class="hero" id="home">

<div class="hero-text">

<h1>TELSERAHE</h1>

<h2>Telang Segar, Serai & Jahe</h2>

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

<footer>

<p>© 2026 Telserahe - Telang Segar, Serai & Jahe</p>

</footer>

<a href="https://wa.me/6282182167104" class="wa-float">💬</a>

</body>
