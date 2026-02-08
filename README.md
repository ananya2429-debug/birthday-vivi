index.html
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
page1.html
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Message 💌</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500&display=swap" rel="stylesheet">

<style>
body{
  margin:0;
  min-height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  background:#1b1b2f;
  font-family:Poppins,sans-serif;
  color:white;
}
.card{
  background:#2f2f55;
  padding:2.5rem;
  border-radius:24px;
  width:90%;
  max-width:500px;
  text-align:center;
}
a{
  color:#c77dff;
  text-decoration:none;
  display:inline-block;
  margin-top:1.5rem;
}
</style>
</head>

<body>

<audio src="music.mp3" autoplay loop></audio>

<div class="card">
  <h1 style="color:#c77dff;">For You 💜</h1>

  <p>
    Happy Birthday my love 💕<br><br>
    This page is just for you. Thank you for making my life 10 times better, my comfort, for being my favorite person of all times, and my chaos all at once. You are the best thing that has every happend to me. I hope we can grow together and face all the hardships without falling apart (i wanna see how our kids turn out 😏😏so u better stick to me for life or else , ill kill you 😆😘)
  </p>

  <a href="index.html">← Back</a>
</div>
page2.html
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Photos 📸</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500&display=swap" rel="stylesheet">

<style>
body{
  margin:0;
  background:#1b1b2f;
  font-family:Poppins,sans-serif;
  color:white;
}
h1{text-align:center; color:#c77dff;}
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
  gap:1rem;
  padding:2rem;
}
.polaroid{
  background:white;
  color:#333;
  padding:.7rem;
  border-radius:12px;
  transform:rotate(-2deg);
}
.polaroid img{
  width:100%;
  border-radius:8px;
}
a{color:#c77dff; display:block; text-align:center; margin-bottom:1rem;}
</style>
</head>

<body>

<audio src="music.mp3" autoplay loop></audio>

<h1>Our Memories 📸</h1>

<div class="grid">
  <div class="polaroid">
    <img src="photo1.jpg">
    <p>Us 💜</p>
  </div>

  <div class="polaroid">
    <img src="photo2.jpg">
    <p>That day ✨</p>
  </div>
</div>

<a href="index.html">← Back</a>
page3.html
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Videos 🎥</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500&display=swap" rel="stylesheet">

<style>
body{
  margin:0;
  background:#1b1b2f;
  font-family:Poppins,sans-serif;
  color:white;
  text-align:center;
}
video{
  width:90%;
  max-width:500px;
  border-radius:16px;
  margin:1rem 0;
}
a{color:#c77dff; display:block; margin-bottom:1rem;}
</style>
</head>

<body>

<audio src="music.mp3" autoplay loop></audio>

<h1 style="color:#c77dff;">Videos 🎥</h1>

<video controls>
  <source src="video1.mp4" type="video/mp4">
</video>

<a href="index.html">← Back</a>
secret.html
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Surprise 🔐</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500&display=swap" rel="stylesheet">

<style>
body{
  margin:0;
  min-height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  background:#2a2a4f;
  font-family:Poppins,sans-serif;
  color:white;
}
.card{
  background:#1b1b2f;
  padding:2rem;
  border-radius:20px;
  text-align:center;
  width:90%;
  max-width:400px;
}
input{
  padding:.6rem;
  border-radius:10px;
  border:none;
  width:80%;
}
button{
  margin-top:1rem;
  padding:.6rem 1.4rem;
  border:none;
  border-radius:999px;
  background:#c77dff;
}
</style>

<script>
function unlock(){
  const pass = document.getElementById("p").value;
  if(pass === "love"){
    document.body.innerHTML =
    "<h1 style='color:#c77dff;text-align:center;'>I love you 💜<br>Happy Birthday 🎉</h1>";
  } else {
    alert("Wrong password 😈");
  }
}
</script>
</head>

<body>

<audio src="music.mp3" autoplay loop></audio>

<div class="card">
  <h2>Enter Password 🔐</h2>
  <input id="p" placeholder="hint: something cute">
  <br>
  <button onclick="unlock()">Unlock 💜</button>
</div>

</body>
</html>

