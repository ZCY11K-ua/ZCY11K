<html lang="uk">
<head>
<meta charset="UTF-8">
<title>ZCY11K</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<script src="https://telegram.org/js/telegram-web-app.js"></script>

<style>
body{
  margin:0;
  font-family:Arial,sans-serif;
  background:radial-gradient(circle at top,#0b1d2a,#050505);
  color:#fff;
  text-align:center;
  overflow-x:hidden;
}

/* ===== LOGO INTRO ===== */
#logo-intro{
  position:fixed;
  inset:0;
  background:radial-gradient(circle,#0b1d2a,#000);
  display:flex;
  align-items:center;
  justify-content:center;
  z-index:9999;
  animation:fadeOut 1s ease forwards;
  animation-delay:3.5s;
}

.logo{
  font-size:52px;
  font-weight:bold;
  letter-spacing:6px;
}

.logo span{
  opacity:0;
  color:#00c3ff;
  text-shadow:0 0 15px #00c3ff,0 0 30px #00c3ff;
  animation:logoIn .6s forwards;
}

.logo span:nth-child(1){animation-delay:.1s}
.logo span:nth-child(2){animation-delay:.3s}
.logo span:nth-child(3){animation-delay:.5s}
.logo span:nth-child(4){animation-delay:.7s}
.logo span:nth-child(5){animation-delay:.9s}
.logo span:nth-child(6){animation-delay:1.1s}

@keyframes logoIn{
  from{transform:translateY(30px) scale(.8);opacity:0}
  to{transform:translateY(0) scale(1);opacity:1}
}

@keyframes fadeOut{
  to{opacity:0;visibility:hidden}
}

/* ===== HEADER ===== */
header h1{
  margin:40px 0;
  font-size:56px;
  color:#00c3ff;
  text-shadow:0 0 15px #00c3ff,0 0 30px #00c3ff,0 0 45px #00c3ff;
  animation:neonPulse 1.5s infinite alternate;
}

@keyframes neonPulse{
  from{text-shadow:0 0 10px #00c3ff,0 0 20px #00c3ff;}
  to{text-shadow:0 0 25px #00c3ff,0 0 50px #00c3ff;}
}

/* ===== TABS ===== */
.tabs{
  display:flex;
  justify-content:center;
  gap:10px;
  flex-wrap:wrap;
  margin-bottom:25px;
}
.tab-btn{
  padding:12px 18px;
  border-radius:12px;
  background:#111;
  color:#fff;
  cursor:pointer;
  font-weight:bold;
  border:1px solid #00c3ff;
  transition:.3s;
}
.tab-btn.active{
  background:#00c3ff;
  color:#000;
}

/* ===== SECTIONS ===== */
.section{display:none;max-width:900px;margin:0 auto;padding:20px;}
.section.active{display:block;}

/* ===== BUTTONS ===== */
.links{display:flex;flex-direction:column;gap:15px;}
.button{
  padding:15px;
  border-radius:14px;
  text-decoration:none;
  color:#fff;
  font-weight:bold;
  transition:.25s;
}
.button:hover{transform:scale(1.05);}

/* ===== COLORS + LED ===== */
.youtube{background:#ff0000;animation:ledRed 1.6s infinite alternate;}
@keyframes ledRed{from{box-shadow:0 0 10px #ff000088}to{box-shadow:0 0 25px #ff0000}}

.tiktok{background:linear-gradient(45deg,#69C9D0,#EE1D52);animation:ledTik 1.6s infinite alternate;}
@keyframes ledTik{from{box-shadow:0 0 10px #69C9D0}to{box-shadow:0 0 25px #EE1D52}}

.telegram,.bot{background:#0088cc;animation:ledTG 1.6s infinite alternate;}
@keyframes ledTG{from{box-shadow:0 0 10px #0088cc88}to{box-shadow:0 0 25px #00ccff}}

.discord{background:#7289da;animation:ledDis 1.6s infinite alternate;}
@keyframes ledDis{from{box-shadow:0 0 10px #7289da88}to{box-shadow:0 0 25px #99a9ff}}

footer{margin:30px 0 15px;opacity:.5; font-size:14px;}

/* ===== MOBILE ===== */
@media(max-width:500px){
  header h1{font-size:42px;}
  .button{padding:12px;}
  .logo{font-size:42px;}
}
</style>
</head>

<body>

<!-- 🔥 LOGO INTRO -->
<div id="logo-intro">
  <div class="logo">
    <span>Z</span><span>C</span><span>Y</span><span>1</span><span>1</span><span>K</span>
  </div>
</div>

<header>
<h1>ZCY11K</h1>
</header>

<div class="tabs">
  <div class="tab-btn active" onclick="openTab(0)"> Канали</div>
  <div class="tab-btn" onclick="openTab(1)"> Боти</div>
  <div class="tab-btn" onclick="openTab(2)"> Соц мережі</div>
  <div class="tab-btn" onclick="openTab(3)"> Магазин</div>
  <div class="tab-btn" onclick="openTab(4)"> Правила чату</div>
</div>

<!-- ===== SECTION: Канали ===== -->
<div class="section active">
<div class="links">
<a class="button youtube" href="https://www.youtube.com/@ZCY11K" target="_blank"> YouTube ZCY11K</a>
<a class="button youtube" href="https://youtube.com/@zcy11k2?si=-O3y8Ow3OwK12BZO" target="_blank"> YouTube ZCY11K 2</a>
<a class="button youtube" href="https://youtube.com/@zcy11k-official?si=M1bjkfkrNqqaPLdX" target="_blank"> YouTube ZCY11K 3</a>
<a class="button tiktok" href="https://www.tiktok.com/@ZCY11K" target="_blank"> TikTok ZCY11K</a>
</div>
</div>

<!-- ===== SECTION: Боти ===== -->
<div class="section">
<div class="links">
<a class="button bot" href="https://t.me/Minecraft111K_bot" target="_blank">@Minecraft111K_bot</a>
<a class="button bot" href="https://t.me/Minecraft112K_bot" target="_blank">@Minecraft112K_bot</a>
<a class="button bot" href="https://t.me/ZCY11K5_bot" target="_blank">@ZCY11K5_bot</a>
<a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">@ZCY11K4_bot</a>
<a class="button bot" href="https://t.me/ZCY11K_bot" target="_blank">@ZCY11K_bot</a>
</div>
</div>

<!-- ===== SECTION: Соц мережі ===== -->
<div class="section">
<div class="links">
<a class="button telegram" href="https://t.me/ZCY11K" target="_blank"> Telegram канал</a>
<a class="button discord" href="https://discord.gg/ZCY11K" target="_blank"> Discord канал</a>
</div>
</div>

<!-- ===== SECTION: Магазин ===== -->
<div class="section">
<div class="links">
<p style="margin-bottom:20px; font-weight:bold; font-size:18px;">
  Щоб купити щось — пишіть боту: 
  <a href="https://t.me/ZCY11K4_bot" target="_blank">@ZCY11K4_bot</a>
</p>

<h2>Піар:</h2>
<a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Піар на YouTube каналі = 25 ⭐️</a>
<a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Піар на Telegram каналі = 15 ⭐️</a>
<a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Піар в чаті = 15 ⭐️</a>
<a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Піар в TikTok = 25 ⭐️</a>
<a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Піар в Discord каналі = 15 ⭐️</a>

<h2>Розбан / Розмут:</h2>
<a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Розмут в чаті = 50 ⭐️</a>
<a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Розбан в чаті = 100 ⭐️</a>
<a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Розбан в TikTok = 25 ⭐️</a>
<a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Розбан в Discord каналі = 15 ⭐️</a>
</div>
</div>

<!-- ===== SECTION: Правила чату ===== -->
<div class="section">
<div class="links">
<h2>Правила чату Discord та Telegram:</h2>
<ol style="text-align:left; max-width:600px; margin:0 auto; line-height:1.8;">
<li>Реклама – мут на 1 годину</li>
<li>Спам – мут на 4 години</li>
<li>Хейтить ZCY11K – БАН назавжди</li>
<li>Не погрожувати адмінам – мут+бан на 5 днів (перший бан після бана мут)</li>
<li>Не кидати в чат російські силки – мут на 24 години</li>
<li>Не відправляти 18+ – бан на 5 днів</li>
</ol>
</div>
</div>

<footer>© 2026 ZCY11K • Всі права захищені</footer>
<footer>popitannami66@gmail.com</footer>

<audio id="clickSound" preload="auto">
  <source src="https://actions.google.com/sounds/v1/ui/click.ogg">
</audio>

<script>
function openTab(i){
  playClick();
  document.querySelectorAll('.section').forEach((s,idx)=>s.classList.toggle('active',idx===i));
  document.querySelectorAll('.tab-btn').forEach((b,idx)=>b.classList.toggle('active',idx===i));
}

const clickSound=document.getElementById("clickSound");
function playClick(){clickSound.currentTime=0;clickSound.play();}
document.querySelectorAll(".button").forEach(b=>b.addEventListener("click", playClick));

if(window.Telegram?.WebApp){
  const tg = window.Telegram.WebApp;
  tg.expand();
  tg.MainButton.setText(" ZCY11K");
  tg.MainButton.show();
}
</script>
