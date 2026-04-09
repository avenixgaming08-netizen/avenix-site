<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Avenix Resume</title>

<!-- Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&display=swap" rel="stylesheet">
<link href="https://fonts.cdnfonts.com/css/lemon-milk" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;}

body{
background:linear-gradient(135deg,#0f172a,#1e3a8a);
color:white;
font-family:'Poppins',sans-serif;
overflow-x:hidden;
}

/* NAV */
nav{
display:flex;
justify-content:space-between;
padding:25px 50px;
}
.logo{
font-weight:800;
color:#4ade80;
font-size:22px;
}
.btn{
background:white;
color:black;
padding:10px 25px;
border-radius:30px;
}

/* HERO */
.hero{
display:flex;
justify-content:space-between;
align-items:center;
padding:60px;
flex-wrap:wrap;
}

.hero h1{
font-family:'LEMON MILK', sans-serif;
font-size:70px;
letter-spacing:2px;
line-height:1.1;
text-transform:uppercase;
}

.hero p{
margin-top:15px;
opacity:0.7;
}

/* 3D PANEL */
.scene{
width:280px;
height:280px;
border-radius:30px;
background:rgba(255,255,255,0.08);
backdrop-filter:blur(20px);
display:flex;
align-items:center;
justify-content:center;
box-shadow:0 30px 60px rgba(0,0,0,0.4);
}

/* FLOAT SHAPES */
.shape{
position:absolute;
border-radius:50%;
background:rgba(255,255,255,0.08);
backdrop-filter:blur(20px);
animation:float 6s infinite;
}
.shape1{width:120px;height:120px;top:100px;left:50px;}
.shape2{width:80px;height:80px;bottom:100px;right:60px;}

@keyframes float{
0%{transform:translateY(0);}
50%{transform:translateY(-20px);}
100%{transform:translateY(0);}
}

/* SERVICES */
.cards{
display:flex;
gap:20px;
padding:40px;
flex-wrap:wrap;
}

.card{
flex:1;
min-width:200px;
padding:25px;
border-radius:20px;
background:rgba(255,255,255,0.08);
backdrop-filter:blur(20px);
}

/* AVATAR */
.team{
display:flex;
gap:40px;
padding:40px;
flex-wrap:wrap;
}

.avatar{
width:120px;
height:120px;
border-radius:50%;
background:linear-gradient(45deg,#4ade80,#3b82f6);
box-shadow:0 20px 40px rgba(0,0,0,0.4);
}

/* CONTACT */
.contact{
margin:40px;
padding:30px;
border-radius:20px;
background:rgba(255,255,255,0.1);
backdrop-filter:blur(20px);
}

/* AI */
.bot{
position:fixed;
bottom:20px;
right:20px;
background:black;
padding:15px;
border-radius:15px;
width:220px;
}

.bot button{
margin-top:10px;
width:100%;
padding:10px;
background:#4ade80;
border:none;
border-radius:10px;
}

/* WHATSAPP */
.whatsapp{
position:fixed;
bottom:20px;
left:20px;
background:#25D366;
padding:15px;
border-radius:50%;
}
</style>
</head>

<body>

<!-- Shapes -->
<div class="shape shape1"></div>
<div class="shape shape2"></div>

<!-- NAV -->
<nav>
<div class="logo">AVENIX</div>
<div class="btn">Get Started</div>
</nav>

<!-- HERO -->
<section class="hero">
<div>
<h1>INNOVATE.<br>TRANSFORM.<br>THRIVE.</h1>
<p>Rahul | Web Developer & Avenix Founder</p>
</div>

<div class="scene">
<h3>3D UI PANEL</h3>
</div>
</section>

<!-- SERVICES -->
<section class="cards">
<div class="card">Web Development</div>
<div class="card">App Systems</div>
<div class="card">Firebase Setup</div>
<div class="card">UI/UX Design</div>
</section>

<!-- AVATAR -->
<section class="team">
<div>
<div class="avatar"></div>
<h3>RAHUL</h3>
<p>Founder</p>
</div>

<div>
<div class="avatar"></div>
<h3>Developer</h3>
<p>Frontend</p>
</div>
</section>

<!-- CONTACT -->
<div class="contact">
<h3>Contact</h3>
<p>Email: avenixgaming08@gmail.com</p>
<p>Phone: +91 7463985387</p>
</div>

<!-- AI -->
<div class="bot">
<p id="aiText">Hi 👋 I am your AI assistant</p>
<button onclick="speak()">Introduce</button>
</div>

<!-- WhatsApp -->
<a href="https://wa.me/917463985387" class="whatsapp"></a>

<script>
function speak(){
const text="Hi, I am Rahul, founder of Avenix. I build modern websites, apps and Firebase systems.";
document.getElementById("aiText").innerText=text;

const speech=new SpeechSynthesisUtterance(text);
speech.lang="en-US";
speech.rate=1;
speech.pitch=1;
speech.volume=1;

speechSynthesis.speak(speech);
}
</script>

</body>
</html>
