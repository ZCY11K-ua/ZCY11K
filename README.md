<html lang="uk">
<head>
<meta charset="UTF-8">
<title>𝐙𝐂𝐘𝟏𝟏𝐊 Official!</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<script src="https://telegram.org/js/telegram-web-app.js"></script>
<style>
body{
  margin:0;
  font-family:Arial,sans-serif;
  background:radial-gradient(circle at top,#1b0f57,#000000);
  color:#fff;
  text-align:center;
  overflow-x:hidden;
}

.logo {
  font-size: 60px;
  font-weight: bold;
  display: flex;
  justify-content:center;
  gap:10px;
  color: #00c3ff;
}
.logo span{
  display:inline-block;
  opacity:0;
  transform: translateY(-100px) rotate(-20deg);
  animation: flyIn 0.8s forwards;
}
.logo span:nth-child(1){ animation-delay: 0s; }
.logo span:nth-child(2){ animation-delay: 0.1s; }
.logo span:nth-child(3){ animation-delay: 0.2s; }
.logo span:nth-child(4){ animation-delay: 0.3s; }
.logo span:nth-child(5){ animation-delay: 0.4s; }
.logo span:nth-child(6){ animation-delay: 0.5s; }

@keyframes flyIn{
  to{
    opacity:1;
    transform: translateY(0) rotate(0deg);
  }
}

/* ===== TABS ===== */
.tabs{
  display:flex;
  justify-content:center;
  gap:10px;
  flex-wrap:wrap;
  margin-bottom:15px;
}
.tab-btn{
  padding:10px 15px;
  border-radius:12px;
  background:#111;
  color:#fff;
  cursor:pointer;
  font-weight:bold;
  border:1px solid #00c3ff;
  transition:.2s;
}
.tab-btn.active{
  background:#00c3ff;
  color:#000;
}

/* ===== SECTIONS ===== */
.section{display:none;max-width:900px;margin:0 auto;padding:10px;}
.section.active{display:block;}

/* ===== BUTTONS ===== */
.links{display:flex;flex-direction:column;gap:10px;}
.button{
  padding:12px;
  border-radius:12px;
  text-decoration:none;
  color:#fff;
  font-weight:bold;
  transition:.2s;
}
.button:hover{transform:scale(1.05);}

/* ===== COLORS ===== */
.youtube{background:#ff0000;}
.tiktok{background:linear-gradient(45deg,#69C9D0,#EE1D52);}
.telegram,.bot{background:#0088cc;}
.discord{background:#7289da;}

/* ===== Сітка для ОТКС ===== */
.otks-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 40px; /* відстань між кнопками */
  max-width: 900px;
  margin: 20px auto;
}
.otks-grid .button {
  width: 100%;
  padding:15px;
  font-size:16px;
}

footer{margin:20px 0;opacity:.7; font-size:14px;}
</style>
</head>
<body>

<div class="tabs">
  <div class="tab-btn active" onclick="openTab(0)"> Канали 𝐙𝐂𝐘𝟏𝟏𝐊</div>
  <div class="tab-btn" onclick="openTab(1)"> Боти 𝐙𝐂𝐘𝟏𝟏𝐊</div>
  <div class="tab-btn" onclick="openTab(2)"> Соц мережі 𝐙𝐂𝐘𝟏𝟏𝐊</div>
  <div class="tab-btn" onclick="openTab(3)"> Магазин 𝐙𝐂𝐘𝟏𝟏𝐊</div>
  <div class="tab-btn" onclick="openTab(4)"> Правила чату:Telegram та Discord</div>
  <div class="tab-btn" onclick="openTab(5)"> ОТКС</div>
</div>

<!-- ===== SECTION: Канали ===== -->
<div class="section active">
  <div class="links">
    <a class="button youtube" href="https://www.youtube.com/@ZCY11K" target="_blank"> YouTube 𝐙𝐂𝐘𝟏𝟏𝐊</a>
    <a class="button youtube" href="https://youtube.com/@zcy11k2?si=-O3y8Ow3OwK12BZO" target="_blank"> YouTube 𝐙𝐂𝐘𝟏𝟏𝐊 2</a>
    <a class="button youtube" href="https://youtube.com/@zcy11k-official?si=M1bjkfkrNqqaPLdX" target="_blank"> YouTube 𝐙𝐂𝐘𝟏𝟏𝐊 3</a>
    <a class="button tiktok" href="https://www.tiktok.com/@ZCY11K" target="_blank"> TikTok 𝐙𝐂𝐘𝟏𝟏𝐊</a>
  </div>
</div>

<!-- ===== SECTION: Боти ===== -->
<div class="section">
  <div class="links">
    <a class="button bot" href="https://t.me/Minecraft111K_bot" target="_blank">Карти по Minecraft Реклама</a>
    <a class="button bot" href="https://t.me/Minecraft112K_bot" target="_blank">Карти по Minecraft Тех. Підтримка</a>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Тех. Підтримка каналу 𝐙𝐂𝐘𝟏𝟏𝐊</a>
    <a class="button bot" href="https://t.me/ZCY11K_bot" target="_blank">ZCY11K (Тестувальний бот)</a>
  </div>
</div>

<!-- ===== SECTION: Соц мережі ===== -->
<div class="section">
  <div class="links">
    <a class="button telegram" href="https://t.me/ZCY11K1" target="_blank"> Telegram канал</a>
    <a class="button discord" href="https://discord.gg/vyYm43K7S" target="_blank"> Discord канал</a>
  </div>
</div>

<!-- ===== SECTION: Магазин ===== -->
<div class="section">
  <div class="links">
    <p style="margin-bottom:10px; font-weight:bold; font-size:16px;">
      Щоб купити щось — пишіть боту: 
      <a href="https://t.me/ZCY11K4_bot" target="_blank">@ZCY11K4_bot</a>
    </p>
    <p>⭐️- це валюта Telegram, за яку можна купляти подарунки та NFT, ще подарунки можна подарувати друзям, цю валюту можно купити в telegram чи бескоштовно получити в ботах.</p>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Піар на YouTube = 25 ⭐️</a>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Піар на Telegram = 15 ⭐️</a>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Піар на TikTok = 25 ⭐️</a>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Піар на Discord = 15 ⭐️ </a>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Розмут в чаті = 25 ⭐️</a>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Розбан в чаті = 50 ⭐️</a>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Розбан в TikTok = 25 ⭐️</a>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Розбан в Discord = 25 ⭐️</a>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Розмут в Discord = 15 ⭐️</a>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Зробленя сайту = 25 ⭐️</a>
    <a class="button bot" href="https://t.me/ZCY11K4_bot" target="_blank">Зробленя Бота в (Telegram) = 15 ⭐️</a>
  </div>
</div>

<!-- ===== SECTION: Правила чату ===== -->
<div class="section">
  <div class="links">
    <h2>Правила чату:Telegram та Discord</h2>
    <ol style="text-align:left; max-width:600px; margin:0 auto; line-height:1.5;">
      <li>Реклама – мут на 1 годину</li>
      <li>Спам – мут на 4 години</li>
      <li>Хейтить 𝐙𝐂𝐘𝟏𝟏𝐊 – БАН назавжди</li>
      <li>Не погрожувати адмінам – мут+бан на 5 днів</li>
      <li>Не кидати російські силки – мут на 24 години</li>
      <li>Не відправляти 18+ – бан на 5 днів</li>
    </ol>
  </div>
</div>

<!-- ===== SECTION: ОТКС ===== -->
<div class="section">
  <p style="margin-bottom:10px; font-weight:bold; font-size:16px;">
      ТКБПИ/БСКИ/ТКБС/BENZ
      <p>Власник сообщества: <a href="https://t.me/pro48k"> PRO48K</a></p>
      <p>𝐙𝐂𝐘𝟏𝟏𝐊 тікі учасник в цьму сообществі telegram! </p>
  <div class="otks-grid">
    <a class="button telegram" href="https://t.me/pro48k_bs" target="_blank"> PRO48K</a>
    <a class="button telegram" href="https://t.me/ZCY11K1" target="_blank"> 𝐙𝐂𝐘𝟏𝟏𝐊</a>
    <a class="button telegram" href="https://t.me/Dom_SLENDER" target="_blank"> Дом Слендера</a>
    <a class="button telegram" href="https://t.me/+dons9m2ml181ODE6" target="_blank"> Король УПА</a>
    <a class="button telegram" href="https://t.me/TRAPS3A15CEK" target="_blank"> TRAPS</a>
    <a class="button telegram" href="https://t.me/Salam4ikBlockStrike" target="_blank"> Salam4ik</a>
    <a class="button telegram" href="https://t.me/+bhAvbEn-THg3ZWUy" target="_blank"> BLOCK STRIKE ВАЙБ</a>
    <a class="button telegram" href="https://t.me/TRIONOVICH" target="_blank"> TR1NOVICH</a>
    <a class="button telegram" href="https://t.me/pryfrozigrishei" target="_blank"> ВЫПЛАТЫ ПОЗИТИВА</a>
    <a class="button telegram" href="https://t.me/ChuKutop" target="_blank"> FAST1KBS_888</a>
    <a class="button telegram" href="https://t.me/MinecraftCards1" target="_blank"> Карти по Minecraft</a>
    <a class="button telegram" href="https://t.me/j5t5iiokhy" target="_blank"> Ukrainian_mapper</a>
    <a class="button telegram" href="https://t.me/+Qsp4-L8iSFNlNTNi" target="_blank"> Майнкрафт карти</a>
    <a class="button telegram" href="https://t.me/+5VU8Hy8PnVJkNTgy" target="_blank"> ПРО48К - БАЗА</a>
    <a class="button telegram" href="https://t.me/BunnyBlockStrikeTcbpiBsci" target="_blank"> Зᥲᥔчᥙκ</a>
    <a class="button telegram" href="https://t.me/PoZiTiv0905" target="_blank"> Позитивчик0905</a>
    <a class="button telegram" href="https://t.me/mellonty138" target="_blank"> fazel</a>
    <a class="button telegram" href="https://t.me/wwwwwwooooottttt" target="_blank"> Lime 889</a>
    <a class="button telegram" href="https://t.me/toksihni_888" target="_blank"> #позитив</a>
    <a class="button telegram" href="https://t.me/+Md-nIupvfYY2ODMy" target="_blank"> ЗГБС</a>
    <a class="button telegram" href="https://t.me/Zoko_Fog228" target="_blank"> Zoko block strike</a>
    <a class="button telegram" href="https://t.me/ZAGERAVKofficial" target="_blank"> ПРОСТО ЗВЕЗДЫ</a>
    <a class="button telegram" href="https://t.me/red77camera97" target="_blank"> B1BZ1INCH1IK</a>
    <a class="button telegram" href="https://t.me/+rvC8gi7mU0o5ZDJi" target="_blank"> UA Online</a>
    <a class="button telegram" href="https://t.me/MOPOE_17_ROBLOX" target="_blank"> МОРОЕ17_Robloх</a>
    <a class="button telegram" href="https://t.me/rozdacha_zvezd" target="_blank"> PROSTARS</a>
    <a class="button telegram" href="https://t.me/+EqENc-U1Ob1kNTAy" target="_blank"> Канал</a>
    <a class="button telegram" href="https://t.me/privatku_standoff2" target="_blank"> ПРИВАТКИ STANDOFF2</a>
    <a class="button telegram" href="https://t.me/+ym7RkTQpoxE5MzBi" target="_blank"> BIGTVMAN</a>
    
  </div>


<footer>© 2026 𝐙𝐂𝐘𝟏𝟏𝐊 • Всі права захищені • popitannami66@gmail.com</footer>
<footer>Неведіться на похожі канали 𝐙𝐂𝐘𝟏𝟏𝐊 та непідписуйтесь на них в цьому сайті тікі орегінальні соц мережі 𝐙𝐂𝐘𝟏𝟏𝐊! </footer>

<script>
function openTab(i){
  document.querySelectorAll('.section').forEach((s,idx)=>s.classList.toggle('active',idx===i));
  document.querySelectorAll('.tab-btn').forEach((b,idx)=>b.classList.toggle('active',idx===i));
}

// Telegram WebApp
if(window.Telegram?.WebApp){
  const tg = window.Telegram.WebApp;
  tg.expand();
  tg.MainButton.setText(" 𝐙𝐂𝐘𝟏𝟏𝐊");
  tg.MainButton.show();
}
</script>
