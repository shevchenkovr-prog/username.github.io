<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Valeriia Shevchenko | Професійний перекладач</title>

<style>
:root{
--milk:#fff3f6;
--glass:rgba(255,255,255,0.55);
--pink:#f4b6c8;
--pink-deep:#d96a94;
--text:#4a2b33;
}

*{margin:0;padding:0;box-sizing:border-box;font-family:'Segoe UI',sans-serif;scroll-behavior:smooth;}

body{
background:linear-gradient(135deg,#fff3f6,#ffe9f0);
color:var(--text);
}

nav{
position:fixed;
top:0;
width:100%;
display:flex;
justify-content:center;
gap:20px;
padding:15px;
background:rgba(255,255,255,0.6);
backdrop-filter:blur(10px);
z-index:1000;
flex-wrap: wrap;
}

nav a{
text-decoration:none;
color:var(--text);
font-weight:600;
transition:0.3s;
}

nav a:hover{color:var(--pink-deep);}

header{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:linear-gradient(135deg,rgba(244,182,200,0.7),rgba(255,255,255,0.4));
animation:fadeIn 2s ease;
}

header h1{
font-size:50px;
margin-bottom:20px;
}

header p{
font-size:20px;
margin-bottom:10px;
}

.button{
display:inline-block;
margin-top:25px;
padding:15px 35px;
background:var(--pink);
color:white;
text-decoration:none;
border-radius:50px;
transition:0.3s;
text-align:center;
}

.button:hover{background:var(--pink-deep);transform:scale(1.05);}

section{
max-width:1100px;
margin:80px auto;
padding:40px 20px;
background:var(--glass);
border-radius:25px;
backdrop-filter:blur(12px);
box-shadow:0 10px 40px rgba(217,106,148,0.2);
animation:fadeUp 1.5s ease;
}

h2{
text-align:center;
margin-bottom:40px;
font-size:30px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.card{
padding:20px;
background:rgba(255,255,255,0.6);
border-radius:20px;
transition:0.3s;
text-align:center;
}

.card:hover{transform:translateY(-8px);}

footer{
text-align:center;
padding:30px 20px;
background:rgba(244,182,200,0.6);
margin-top:60px;
}

@keyframes fadeIn{
from{opacity:0;}
to{opacity:1;}
}

@keyframes fadeUp{
from{opacity:0;transform:translateY(40px);}
to{opacity:1;transform:translateY(0);}
}

@media(max-width:768px){
header h1{font-size:36px;}
header p{font-size:18px;}
nav a{font-size:14px;}
.button{padding:12px 25px;font-size:16px;}
.grid{grid-template-columns:repeat(auto-fit,minmax(180px,1fr));}
}
</style>
</head>

<body>

<nav>
<a href="#about">Про мене</a>
<a href="#services">Послуги</a>
<a href="#languages">Мови</a>
<a href="#portfolio">Портфоліо</a>
<a href="#contact">Контакти</a>
</nav>

<header>
<h1>Valeriia Shevchenko</h1>
<p>Професійний письмовий перекладач іноземних мов</p>
<p>Кременець</p>

<a href="https://docs.google.com/forms/d/e/1FAIpQLSeWOuh7wlF3ZQtnk1PuK-ouR58Mpzjj5NCBC0gDdmN-n5XwHw/viewform"
class="button"
target="_blank">
Замовити переклад
</a>

</header>

<section id="about">
<h2>Про мене</h2>
<p>
Я спеціалізуюся на точному письмовому перекладі документів, академічних і бізнес-текстів.
Працюю уважно до деталей, дотримуюся термінів і забезпечую конфіденційність.
</p>
</section>

<section id="services">
<h2>Послуги</h2>
<div class="grid">
<div class="card">📄 Офіційні документи</div>
<div class="card">📚 Академічні тексти</div>
<div class="card">💼 Бізнес-переклад</div>
<div class="card">🌍 Локалізація сайтів</div>
<div class="card">✍️ Редагування</div>
<div class="card">⚡ Термінові переклади</div>
</div>
</section>

<section id="languages">
<h2>Мови, з якими працюю</h2>
<div class="grid">
<div class="card">🇬🇧 Англійська</div>
<div class="card">🇩🇪 Німецька</div>
<div class="card">🇵🇱 Польська</div>
<div class="card">🇫🇷 Французька</div>
</div>
</section>

<section id="portfolio">
<h2>Портфоліо</h2>
<p>
Приклади виконаних робіт: переклад договорів, наукових статей,
веб-контенту та офіційних документів.
Деталі надаються за запитом.
</p>
</section>

<section id="contact">
<h2>Контакти</h2>
<p><strong>Місто:</strong> Кременець</p>
<p><strong>Телефон:</strong> <a href="tel:+380987637406">0987637406</a></p>

<a href="https://www.instagram.com/_vqlereex_/" target="_blank" class="button">
Instagram
</a>

</section>

<footer>
© 2026 Valeriia Shevchenko | Письмові переклади | Кременець
</footer>

</body>
</html>
<!-- modify this form HTML and place wherever you want your form -->
<form
  action="https://formspree.io/f/xpqjvwdd"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="email">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>
