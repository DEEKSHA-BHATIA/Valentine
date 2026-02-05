<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<title>Hey My Love 💖</title>  
  
<style>  
* {  
  box-sizing: border-box;  
}  
  
body {  
  margin: 0;  
  height: 100vh;  
  font-family: 'Poppins', sans-serif;  
  background: linear-gradient(135deg, #ff4f8b, #ff7bbf);  
  display: flex;  
  justify-content: center;  
  align-items: center;  
  overflow: hidden;  
}  
  
/* Floating hearts */  
.heart {  
  position: absolute;  
  color: rgba(255,255,255,0.7);  
  font-size: 20px;  
  animation: float 6s linear infinite;  
}  
  
@keyframes float {  
  0% { transform: translateY(100vh); opacity: 0; }  
  30% { opacity: 1; }  
  100% { transform: translateY(-10vh); opacity: 0; }  
}  
  
.card {  
  background: #ff6fae;  
  padding: 28px;  
  width: 330px;  
  border-radius: 22px;  
  text-align: center;  
  color: white;  
  position: relative;  
  box-shadow: 0 20px 40px rgba(0,0,0,0.25);  
}  
  
.card img {  
  width: 90px;  
  height: 90px;  
  border-radius: 50%;  
  border: 3px solid white;  
  object-fit: cover;  
  margin-bottom: 15px;  
}  
  
h2 {  
  margin: 10px 0;  
}  
  
p {  
  font-size: 14px;  
  line-height: 1.6;  
}  
  
.buttons {  
  margin-top: 22px;  
  position: relative;  
  height: 60px;  
}  
  
button {  
  padding: 10px 22px;  
  border: none;  
  border-radius: 20px;  
  font-size: 14px;  
  cursor: pointer;  
  position: absolute;  
  transition: 0.2s;  
}  
  
#yesBtn {  
  background: white;  
  color: #ff4f8b;  
  left: 40px;  
}  
  
#noBtn {  
  background: #333;  
  color: white;  
  left: 170px;  
}  
</style>  
</head>  
  
<body>  
  
<div class="card" id="card">  
  <img src="https://i.imgur.com/4Z7cZ0T.png">  
  <h2>Hey My Love 💖</h2>  
  <p>  
    Every smile of yours feels like home.    
    Every moment with you feels like magic.    
    And today… I just have one important question.  
  </p>  
  <strong>Will you be my Valentine? ❤️</strong>  
  
  <div class="buttons">  
    <button id="yesBtn" onclick="yesClicked()">Yes ❤️</button>  
    <button id="noBtn">No 💔</button>  
  </div>  
</div>  
  
<script>  
const noBtn = document.getElementById("noBtn");  
const card = document.getElementById("card");  
  
function moveNo() {  
  const maxX = card.offsetWidth - noBtn.offsetWidth;  
  const maxY = 40;  
  
  const x = Math.random() * maxX;  
  const y = Math.random() * maxY;  
  
  noBtn.style.left = x + "px";  
  noBtn.style.top = y + "px";  
}  
  
noBtn.addEventListener("mouseenter", moveNo);  
noBtn.addEventListener("click", moveNo);  
  
function yesClicked() {  
  document.body.innerHTML = `  
    <h1 style="color:white;text-align:center;font-family:Poppins;">  
      YAYYY! 🥰💖<br><br>  
      You just made my heart very happy 💕  
    </h1>  
  `;  
}  
  
/* Hearts generator */  
setInterval(() => {  
  const heart = document.createElement("div");  
  heart.className = "heart";  
  heart.innerHTML = "❤️";  
  heart.style.left = Math.random() * 100 + "vw";  
  heart.style.fontSize = Math.random() * 10 + 15 + "px";  
  document.body.appendChild(heart);  
  
  setTimeout(() => heart.remove(), 6000);  
}, 400);  
</script>  
  
</body>  
</html>  
