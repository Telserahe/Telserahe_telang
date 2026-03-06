<!DOCTYPE html><html lang="id"><head><meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Telserahe</title><link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet"><style>

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

/* CONTAINER */

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

/* LOGO BACKGROUND */

.hero::before{
content:"";
position:absolute;
width:420px;
height:420px;
background:url("logo.png") no-repeat center;
background-size:contain;
opacity:0.05;
left:50%;
top:50%;
transform:translate(-50%,-50%);
}

.hero-text{
max-width:500px;
z-index:2;
}

.brand{
font-size:36px;
font-weight:700;
color:#5E2A84;
margin-bottom:15px;
}

.hero-text p{
font-size:18px;
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
margin-bottom:15px;
}

/* HERO IMAGE */

.hero-img img{
width:280px;
mix-blend-mode:multiply;
}

/* SECTION */

.section{
padding:70px 0;
text-align:center;
}

.section h2{
font-size:30px;
color:#5E2A84;
margin-bottom:35px;
}

/* FEATURES */

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:25px;
}

.feature{
background:white;
padding:25px;
border-radius:12px;
box-shadow:0 5px 18px rgba(0,0,0,0.08);
}

/* ORDER FORM */

.order-box{
max-width:420px;
margin:auto;
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 8px 22px rgba(0,0,0,0.08);
text-align:left;
}

.order-box label{
font-weight:500;
}

.order-box input,
.order-box select,
.order-box textarea{
width:100%;
padding:10px;
margin-top:5px;
margin-bottom:15px;
border-radius:8px;
border:1px solid #ddd;
}

/* TESTIMONI */

.testimonial{
background:white;
padding:25px;
border-radius:12px;
box-shadow:0 6px 20px rgba(0,0,0,0.08);
margin-top:15px;
}

/* FOOTER */

footer{
background:#3E1A5C;
color:white;
padding:25px;
text-align:center;
}

/* FLOAT SOCIAL */

.social-float{
position:fixed;
bottom:20px;
right:20px;
display:flex;
flex-direction:column;
gap:10px;
z-index:999;
}

.social-float a{
width:55px;
height:55px;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
font-size:22px;
color:white;
text-decoration:none;
box-shadow:0 5px 15px rgba(0,0,0,0.25);
}

.wa{
background:#25D366;
}

.ig{
background:#E1306C;
}

/* MOBILE */

@media(max-width:900px){

.hero{
flex-direction:column;
text-align:center;
}

.hero-img img{
width:220px;
margin-top:30px;
}

.brand{
font-size:26px;
}

.hero-text p{
font-size:16px;
}

}

</style></head><body><header><nav>
<a href="#home">Home</a>
<a href="#manfaat">Manfaat</a>
<a href="#produk">Produk</a>
<a href="#testimoni">Testimoni</a>
<a href="#kontak">Kontak</a>
</nav></header><!-- HERO --><section class="hero container" id="home"><div class="hero-text"><div class="brand">
Telserahe : Telang Segar, Serai & Jahe
</div><p>
Minuman herbal alami dengan perpaduan bunga telang, serai, jahe dan madu.
Segar, sehat, dan cocok diminum kapan saja.
</p><a class="btn" href="#produk">Pesan Sekarang</a>

</div><div class="hero-img">
<img src="produk.png">
</div></section><!-- MANFAAT --><section class="section container" id="manfaat"><h2>Manfaat Bahan Alami</h2><div class="features"><div class="feature">
<h3>🌸 Bunga Telang</h3>
<p>Kaya antioksidan dan baik untuk kesehatan tubuh.</p>
</div><div class="feature">
<h3>🌿 Sereh</h3>
<p>Menyegarkan tubuh dan membantu detoks alami.</p>
</div><div class="feature">
<h3>🫚 Jahe</h3>
<p>Menghangatkan tubuh dan meningkatkan imun.</p>
</div><div class="feature">
<h3>🍯 Madu</h3>
<p>Pemanis alami yang sehat dan menambah energi.</p>
</div></div></section><!-- ORDER --><section class="section container" id="produk"><h2>Pesan Produk</h2><div class="order-box"><label>Produk</label>

<select id="produk_select"><option value="Telserahe 250ml">Telserahe 250ml - Rp 6.000</option><option value="Telserahe 500ml">Telserahe 500ml - Rp 10.000</option></select><label>Jumlah Botol</label>

<input type="number" id="jumlah" value="1"><label>Nama</label>

<input type="text" id="nama"><label>Alamat</label>

<textarea id="alamat"></textarea><button onclick="pesanWA()" class="btn" style="width:100%">
Pesan via WhatsApp
</button></div></section><!-- TESTIMONI --><section class="section container" id="testimoni"><h2>Testimoni Pelanggan</h2><div class="testimonial">
⭐️⭐️⭐️⭐️⭐️
<p>"Minumannya segar banget dan jahenya terasa alami!"</p>
</div><div class="testimonial">
⭐️⭐️⭐️⭐️⭐️
<p>"Warna telangnya cantik dan rasanya unik."</p>
</div></section><footer id="kontak"><p>WhatsApp : 082182167104</p>
<p>Instagram : @telserahee_telang</p><p>© 2026 Telserahe</p></footer><!-- FLOAT SOCIAL --><div class="social-float"><a class="wa" href="https://wa.me/6282182167104">💬</a>

<a class="ig" href="https://instagram.com/telserahee_telang">📷</a>

</div><script>

function pesanWA(){

let produk=document.getElementById("produk_select").value;
let jumlah=document.getElementById("jumlah").value;
let nama=document.getElementById("nama").value;
let alamat=document.getElementById("alamat").value;

let pesan=
"Halo Admin Telserahe 👋%0A%0A"+
"Saya ingin memesan:%0A%0A"+
"Produk : "+produk+"%0A"+
"Jumlah : "+jumlah+" botol%0A%0A"+
"Nama : "+nama+"%0A"+
"Alamat : "+alamat+"%0A%0A"+
"Terima kasih.";

window.open("https://wa.me/6282182167104?text="+pesan);

}

</script></body>
