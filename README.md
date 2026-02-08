<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday 💜</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500&display=swap" rel="stylesheet">

<style>
body{
  margin:0;
  min-height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  background:linear-gradient(135deg,#1b1b2f,#2a2a4f);
  font-family:Poppins,sans-serif;
  color:white;
  overflow:hidden;
}
.card{
  background:#2f2f55;
  padding:2.5rem;
  border-radius:24px;
  width:90%;
  max-width:500px;
  text-align:center;
  box-shadow:0 20px 40px rgba(0,0,0,.4);
  animation:fadeIn 1s ease;
}
h1{color:#c77dff;}
.nav a{
  display:inline-block;
  margin:.4rem;
  padding:.6rem 1.4rem;
  background:#c77dff;
  color:#1b1b2f;
  border-radius:999px;
  text-decoration:none;
  font-size:.9rem;
}
.character{
  position:absolute;
  bottom:0;
  width:120px;
  animation:float 3s ease-in-out infinite;
}
.bb{left:5%;}
.raven{right:5%; animation-delay:1.5s;}
@keyframes float{
  0%,100%{transform:translateY(0)}
  50%{transform:translateY(-15px)}
}
@keyframes fadeIn{
  from{opacity:0; transform:translateY(20px)}
  to{opacity:1}
}
</style>
</head>

<body>

<audio src="music.mp3" autoplay loop></audio>

<img src="bb.png" class="character bb">
<img src="raven.png" class="character raven">

<div class="card">
  <h1>Happy Birthday 💜</h1>
  <p>Made with love, chaos & Teen Titans magic ✨</p>

  <div class="nav">
    <a href="page1.html">💌 Message</a>
    <a href="page2.html">📸 Photos</a>
    <a href="page3.html">🎥 Videos</a>
    <a href="secret.html">🔐 Surprise</a>
  </div>
</div>

</body>
</html>
