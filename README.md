<!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AVENIX | Rahul</title><!-- Fonts --><link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600;800&display=swap" rel="stylesheet"><style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}

body{
  background:linear-gradient(135deg,#0f172a,#1e3a8a);
  color:white;
}

/* NAV */
.nav{
  display:flex;
  justify-content:space-between;
  padding:20px 40px;
}
.logo{font-weight:800;font-size:20px;color:#22c55e}

/* HERO */
.hero{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:60px;
}

.left h1{
  font-size:60px;
  font-weight:800;
  line-height:1.1;
}

.left p{margin-top:10px;color:#ccc;}

.btn{
  margin-top:20px;
  padding:12px 20px;
  border-radius:30px;
  border:none;
  background:#22c55e;
  color:black;
  cursor:pointer;
}

/* 3D CARD */
.card{
  background:rgba(255,255,255,0.05);
  padding:25px;
  border-radius:20px;
  backdrop-filter:blur(20px);
  transition:0.4s;
}
.card:hover{
  transform:translateY(-10px) scale(1.03);
  box-shadow:0 0 30px #22c55e;
}

/* GRID */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:20px;
  padding:40px;
}

/* PROFILE */
.profile{
  display:flex;
  align-items:center;
  gap:20px;
  padding:40px;
}

.avatar{
  width:80px;
  height:80px;
  border-radius:50%;
  background:linear-gradient(#22c55e,#0ea5e9);
}

/* AI CHAT */
.chat{
  position:fixed;
  bottom:20px;
  right:20px;
  width:260px;
  background:#111;
  border-radius:15px;
  padding:15px;
}

.chat button{
  width:100%;
  margin-top:10px;
  padding:10px;
  border:none;
  background:#22c55e;
  cursor:pointer;
}
</style></head><body><!-- NAV --><div class="nav">
  <div class="logo">AVENIX</div>
  <button class="btn">Get Started</button>
</div><!-- HERO --><div class="hero">
  <div class="left">
    <h1>INNOVATE.<br>TRANSFORM.<br>THRIVE.</h1>
    <p>Rahul | Web Developer & Avenix Founder</p><a href="tel:+917463985387"><button class="btn">Call</button></a>

  </div>  <div class="card">
    <h3>3D UI PANEL</h3>
    <p>Modern glass design block</p>
  </div>
</div><!-- SERVICES --><div class="grid">
  <div class="card">Web Development</div>
  <div class="card">App Systems</div>
  <div class="card">Firebase Setup</div>
  <div class="card">UI/UX Design</div>
</div><!-- PROFILE --><div class="profile">
  <div class="avatar"></div>
  <div>
    <h2>RAHUL</h2>
    <p>avenixgaming08@gmail.com</p>
    <p>+91 7463985387</p>
  </div>
</div><!-- AI ASSISTANT --><div class="chat">
  <p id="aiText">Hi 👋 I am your AI assistant</p>
  <button onclick="talk()">Introduce</button>
</div><script>
function talk(){
  let msg="Hi, I am Rahul. Founder of Avenix. I build websites and apps.";
  document.getElementById("aiText").innerText=msg;

  let speech=new SpeechSynthesisUtterance(msg);
  speech.lang="en-US";
  speechSynthesis.speak(speech);
}
</script></body>
</html>
