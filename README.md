
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Telserahe | Telang Seger, Sereh & Jahe</title>

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

header{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
color:white;
padding:15px 40px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo img{
height:55px
}

nav a{
color:white;
margin-left:25px;
text-decoration:none;
font-weight:500
}

.hero{
min-height:80vh;
display:flex;
align-items:center;
justify-content:space-between;
padding:60px 10%;
background:linear-gradient(120deg,#F6F1E7,#EFE3FF);
}

.hero-text{
max-width:500px;
position:relative;
}

/* LOGO WATERMARK */
.hero-text::before{
content:"";
position:absolute;
top:-60px;
left:-80px;
width:350px;
height:350px;
background:url('logo.png') no-repeat center;
background-size:contain;
opacity:0.08;
z-index:0;
}

.hero-text h1{
font-size:48px;
color:#5E2A84;
margin-bottom:20px;
position:relative;
z-index:1;
}

.hero-text p{
font-size:18px;
margin-bottom:30px;
line-height:1.6;
position:relative;
z-index:1;
}

.btn{
background:#C9A25D;
color:white;
padding:14px 30px;
border-radius:30px;
text-decoration:none;
font-weight:600;
display:inline-block;
position:relative;
z-index:1;
}

.hero-img img{
width:350px
}

.section{
padding:80px 10%;
text-align:center
}

.section h2{
font-size:32px;
color:#5E2A84;
margin-bottom:40px
}

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
margin-bottom:15px
}

.price{
font-size:20px;
font-weight:600;
margin:10px 0 20px 0
}

.testimonial{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 8px 20px rgba(0,0,0,0.08);
margin-top:20px
}

.cta{
background:linear-gradient(135deg,#5E2A84,#7B3FB2);
color:white;
padding:80px 20px;
text-align:center
}

footer{
background:#3E1A5C;
color:white;
padding:30px;
text-align:center
}

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
<a href="#testimoni">Testimoni</a>
<a href="#kontak">Kontak</a>
</nav>

</header>

<section class="hero" id="home">

<div class="hero-text">

<h1>Telang Seger, Sereh & Jahe</h1>

<p>
Minuman herbal alami dengan perpaduan bunga telang, sereh, jahe dan madu.
Segar, sehat, dan cocok diminum kapan saja.
</p>

<a class="btn" href="#produk">Pesan Sekarang</a>

</div>

<div class="hero-img">
<img src="produk.png">
</div>

</section>

</body>
