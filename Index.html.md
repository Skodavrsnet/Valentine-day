# HTML(love)  
  
<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<title>For My Beautiful Wife Belina</title>  
<style>  
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Poppins:wght@300&display=swap');  
  
body {  
    margin: 0;  
    padding: 0;  
    height: 100vh;  
    overflow: hidden;  
    background: radial-gradient(circle at top, #ff9a9e, #ff758c, #ff7eb3);  
    display: flex;  
    justify-content: center;  
    align-items: center;  
    font-family: 'Poppins', sans-serif;  
}  
  
/* Floating hearts */  
.heart {  
    position: absolute;  
    color: rgba(255,255,255,0.7);  
    animation: floatUp 10s linear infinite;  
}  
  
@keyframes floatUp {  
    0% { transform: translateY(100vh) scale(0.5); opacity: 1; }  
    100% { transform: translateY(-10vh) scale(1.2); opacity: 0; }  
}  
  
/* Card */  
.card {  
    position: relative;  
    background: rgba(255, 255, 255, 0.15);  
    padding: 60px;  
    border-radius: 30px;  
    backdrop-filter: blur(15px);  
    text-align: center;  
    box-shadow: 0 0 60px rgba(255, 0, 100, 0.6);  
    animation: glow 3s infinite alternate;  
}  
  
@keyframes glow {  
    from { box-shadow: 0 0 30px rgba(255,0,120,0.4); }  
    to { box-shadow: 0 0 80px rgba(255,0,150,0.9); }  
}  
  
.title {  
    font-family: 'Dancing Script', cursive;  
    font-size: 60px;  
    color: white;  
    margin-bottom: 20px;  
    text-shadow: 0 0 20px #fff;  
}  
  
.valentine-link {  
    text-decoration: none;  
    font-size: 35px;  
    color: white;  
    padding: 20px 50px;  
    border-radius: 50px;  
    background: linear-gradient(45deg, #ff4b5c, #ff6f91, #ff85a2);  
    transition: 0.4s ease;  
    display: inline-block;  
    box-shadow: 0 0 25px #ff4b5c;  
}  
  
.valentine-link:hover {  
    transform: scale(1.15);  
    box-shadow: 0 0 40px #fff;  
}  
  
/* Hidden love message */  
.message {  
    margin-top: 25px;  
    font-size: 20px;  
    color: white;  
    opacity: 0;  
    transition: 1s ease;  
}  
  
.card:hover .message {  
    opacity: 1;  
}  
  
.roses {  
    font-size: 30px;  
    margin-bottom: 20px;  
}  
</style>  
</head>  
<body>  
  
<!-- Floating Hearts Script -->  
<script>  
for (let i = 0; i < 25; i++) {  
    let heart = document.createElement("div");  
    heart.className = "heart";  
    heart.innerHTML = "💖";  
    heart.style.left = Math.random() * 100 + "vw";  
    heart.style.fontSize = (Math.random() * 20 + 15) + "px";  
    heart.style.animationDuration = (Math.random() * 5 + 5) + "s";  
    document.body.appendChild(heart);  
}  
</script>  
  
<div class="card">  
    <div class="roses">🌹🌸💐🌷🌺</div>  
    <div class="title">My Perfect Wife Belina</div>  
  
    <a href="https://example.com" target="_blank" class="valentine-link">  
        💖 Happy Valentine's Day 💖  
    </a>  
  
    <div class="message">  
        You are my heart, my happiness, my forever love.    
        Every day with you feels like Valentine's Day. 💕✨  
    </div>  
  
    <div class="roses">🌺🌷💐🌸🌹</div>  
</div>  
  
</body>  
</html>  
