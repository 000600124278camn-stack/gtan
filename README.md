hirooka-suiran
html.index
html
<!DOCTYPE html>
<html lang="ja">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>横浜翠嵐高等学校 | 常識を超えろ。未来を創れ。</title>

<meta name="description"
content="横浜翠嵐高等学校公式サイト。探究・挑戦・自由な校風。未来を切り拓くリーダーを育成します。">

<meta property="og:title"
content="横浜翠嵐高等学校">

<meta property="og:description"
content="常識を超えろ。未来を創れ。">

<meta property="og:image"
content="images/ogp.jpg">

<link rel="preconnect"
href="https://fonts.googleapis.com">

<link rel="preconnect"
href="https://fonts.gstatic.com"
crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;500;700;900&display=swap"
rel="stylesheet">

<link rel="stylesheet"
href="css/style.css">

<link rel="stylesheet"
href="css/animations.css">

<link rel="stylesheet"
href="css/responsive.css">

<link rel="stylesheet"
href="https://cdn.jsdelivr.net/npm/pannellum/build/pannellum.css">

</head>

<body>

<!-- Loading -->

<div id="loader">

<div class="loader-logo">
横浜翠嵐高等学校
</div>

</div>

<!-- Header -->

<header id="header">

<div class="logo">

<img src="assets/logo.svg"
alt="横浜翠嵐高校">

</div>

<nav>

<ul>

<li><a href="#about">学校紹介</a></li>

<li><a href="#quest">翠嵐診断</a></li>

<li><a href="#tour">校内ツアー</a></li>

<li><a href="#clubs">部活動</a></li>

<li><a href="#festival">翠翔祭</a></li>

<li><a href="#news">NEWS</a></li>

</ul>

</nav>

<a href="admissions.html"
class="header-btn">

受験生向け

</a>

</header>

<!-- HERO -->

<section class="hero">

<video autoplay
muted
loop
playsinline
class="hero-video">

<source
src="video/hero.mp4"
type="video/mp4">

</video>

<div class="hero-overlay"></div>

<div class="hero-content">

<div class="hero-sub">

YOKOHAMA SUIRAN
HIGH SCHOOL

</div>

<h1>

常識を超えろ。<br>
未来を創れ。

</h1>

<p>

挑戦する力が、
未来を変える。

</p>

<div class="hero-buttons">

<a href="#about"
class="btn-primary">

学校を知る

</a>

<a href="admissions.html"
class="btn-secondary">

説明会情報

</a>

</div>

</div>

<div class="scroll-indicator">

SCROLL

</div>

</section>

<!-- ABOUT -->

<section id="about"
class="section">

<div class="container">

<h2 class="section-title">

数字で見る翠嵐

</h2>

<div class="stats-grid">

<div class="stat-card">

<div class="counter"
data-target="110">

0

</div>

<p>年の歴史</p>

</div>

<div class="stat-card">

<div class="counter"
data-target="95">

0

</div>

<p>分授業</p>

</div>

<div class="stat-card">

<div class="counter"
data-target="40">

0

</div>

<p>部活動</p>

</div>

<div class="stat-card">

<div class="counter"
data-target="100">

0

</div>

<p>%挑戦する姿勢</p>

</div>

</div>

</div>

</section>

<!-- QUEST -->

<section id="quest"
class="section bg-light">

<div class="container">

<h2 class="section-title">

SUIRAN QUEST

</h2>

<p class="section-lead">

あなたはどんな翠嵐生？

</p>

<div class="quest-card">

<h3>

難問に出会ったら？

</h3>

<div class="quest-buttons">

<button
data-result="研究者タイプ">

徹底分析する

</button>

<button
data-result="リーダータイプ">

仲間と議論する

</button>

<button
data-result="挑戦者タイプ">

まずやってみる

</button>

</div>

<div id="quest-result">

</div>

</div>

</div>

</section>

<!-- TOUR -->

<section id="tour"
class="section">

<div class="container">

<h2 class="section-title">

360° 校内ツアー

</h2>

<p class="section-lead">

翠嵐の空気を体験しよう

</p>

<div id="panorama">

</div>

<div class="tour-nav">

<button
onclick="loadScene('entrance')">

正門

</button>

<button
onclick="loadScene('library')">

図書館

</button>

<button
onclick="loadScene('classroom')">

教室

</button>

<button
onclick="loadScene('gym')">

体育館

</button>

</div>

</div>

</section>

<!-- CLUB -->

<section id="clubs"
class="section bg-dark">

<div class="container">

<h2 class="section-title white">

CLUB UNIVERSE

</h2>

<div class="cards-container">

<div class="card3d">

<div class="card-content">

<h3>⚽ サッカー部</h3>

<p>
全国を目指す挑戦者たち
</p>

</div>

</div>

<div class="card3d">

<div class="card-content">

<h3>🎺 吹奏楽部</h3>

<p>
感動を創る音楽
</p>

</div>

</div>

<div class="card3d">

<div class="card-content">

<h3>🧪 化学部</h3>

<p>
探究の最前線
</p>

</div>

</div>

<div class="card3d">

<div class="card-content">

<h3>🔭 天文部</h3>

<p>
宇宙への挑戦
</p>

</div>

</div>

</div>

</div>

</section>

<!-- FESTIVAL -->

<section id="festival"
class="section">

<div class="container">

<h2 class="section-title">

翠翔祭 COUNTDOWN

</h2>

<div class="countdown-wrapper">

<div id="days">0</div>

<span>

DAYS TO GO

</span>

</div>

</div>

</section>

<!-- NEWS -->

<section id="news"
class="section bg-light">

<div class="container">

<h2 class="section-title">

NEWS

</h2>

<div class="news-grid">

<article class="news-card">

<span>
2026.06.01
</span>

<h3>
学校説明会受付開始
</h3>

</article>

<article class="news-card">

<span>
2026.05.20
</span>

<h3>
翠翔祭特設ページ公開
</h3>

</article>

<article class="news-card">

<span>
2026.05.01
</span>

<h3>
探究成果発表会開催
</h3>

</article>

</div>

</div>

</section>

<!-- CTA -->

<section class="cta-section">

<h2>

未来は、待つものではない。<br>
創るものだ。

</h2>

<a href="admissions.html"
class="btn-primary">

説明会に申し込む

</a>

</section>

<!-- Footer -->

<footer>

<div class="footer-inner">

<h3>

横浜翠嵐高等学校

</h3>

<p>

〒221-0854
神奈川県横浜市神奈川区三ツ沢南町1-1

</p>

<p>

© Yokohama Suiran High School

</p>

</div>

</footer>

<script src="https://cdn.jsdelivr.net/npm/pannellum/build/pannellum.js"></script>

<script src="js/main.js"></script>

<script src="js/counter.js"></script>

<script src="js/quest.js"></script>

<script src="js/cards3d.js"></script>

<script src="js/countdown.js"></script>

<script src="js/panorama.js"></script>

</body>
</html>

css
/* ====================================
   Yokohama Suiran High School
   style.css
==================================== */

:root{

--green:#008b72;
--navy:#0f2747;
--gold:#f4c542;

--white:#ffffff;
--light:#f8fafc;
--gray:#64748b;

--shadow:
0 10px 30px rgba(0,0,0,.1);

--radius:20px;

}

/* Reset */

*{
margin:0;
padding:0;
box-sizing:border-box;
}

html{
scroll-behavior:smooth;
}

body{

font-family:
'Noto Sans JP',
sans-serif;

line-height:1.8;

color:#1f2937;

overflow-x:hidden;

background:white;

}

/* Loader */

#loader{

position:fixed;

top:0;
left:0;

width:100%;
height:100%;

background:var(--navy);

display:flex;

justify-content:center;
align-items:center;

z-index:9999;

transition:1s;

}

.loader-logo{

color:white;

font-size:2rem;

font-weight:900;

letter-spacing:2px;

}

/* Layout */

.container{

width:min(1200px,90%);

margin:auto;

}

.section{

padding:120px 0;

}

.bg-light{

background:var(--light);

}

.bg-dark{

background:
linear-gradient(
135deg,
#07162d,
#0f2747
);

}

.white{

color:white;

}

.section-title{

font-size:3rem;

font-weight:900;

text-align:center;

margin-bottom:20px;

color:var(--navy);

}

.bg-dark .section-title{

color:white;

}

.section-lead{

text-align:center;

font-size:1.2rem;

color:var(--gray);

margin-bottom:60px;

}

/* Header */

header{

position:fixed;

top:0;
left:0;

width:100%;

padding:20px 5%;

display:flex;

justify-content:space-between;

align-items:center;

z-index:1000;

transition:.3s;

}

header.scrolled{

background:white;

box-shadow:var(--shadow);

}

.logo img{

height:50px;

}

nav ul{

display:flex;

list-style:none;

gap:30px;

}

nav a{

text-decoration:none;

font-weight:700;

color:white;

transition:.3s;

}

header.scrolled nav a{

color:var(--navy);

}

.header-btn{

padding:12px 25px;

background:var(--green);

color:white;

border-radius:40px;

text-decoration:none;

font-weight:700;

}

/* HERO */

.hero{

height:100vh;

position:relative;

display:flex;

align-items:center;

justify-content:center;

overflow:hidden;

}

.hero-video{

position:absolute;

width:100%;
height:100%;

object-fit:cover;

}

.hero-overlay{

position:absolute;

inset:0;

background:
linear-gradient(
rgba(0,0,0,.5),
rgba(0,0,0,.6)
);

}

.hero-content{

position:relative;

z-index:10;

text-align:center;

color:white;

}

.hero-sub{

letter-spacing:5px;

margin-bottom:20px;

font-weight:700;

}

.hero h1{

font-size:5rem;

line-height:1.2;

font-weight:900;

margin-bottom:20px;

}

.hero p{

font-size:1.3rem;

margin-bottom:40px;

}

.hero-buttons{

display:flex;

justify-content:center;

gap:20px;

}

/* Buttons */

.btn-primary{

display:inline-block;

padding:15px 35px;

background:var(--green);

color:white;

border-radius:50px;

text-decoration:none;

font-weight:700;

transition:.3s;

}

.btn-primary:hover{

transform:translateY(-5px);

}

.btn-secondary{

display:inline-block;

padding:15px 35px;

border:2px solid white;

color:white;

border-radius:50px;

text-decoration:none;

font-weight:700;

}

/* Scroll */

.scroll-indicator{

position:absolute;

bottom:40px;

left:50%;

transform:translateX(-50%);

color:white;

font-size:.8rem;

letter-spacing:3px;

animation:
bounce 2s infinite;

}

@keyframes bounce{

0%,100%{
transform:
translateX(-50%)
translateY(0);
}

50%{
transform:
translateX(-50%)
translateY(10px);
}

}

/* Stats */

.stats-grid{

display:grid;

grid-template-columns:
repeat(auto-fit,minmax(250px,1fr));

gap:30px;

}

.stat-card{

background:white;

padding:40px;

border-radius:var(--radius);

text-align:center;

box-shadow:var(--shadow);

}

.counter{

font-size:4rem;

font-weight:900;

color:var(--green);

}

/* QUEST */

.quest-card{

background:white;

max-width:800px;

margin:auto;

padding:50px;

border-radius:var(--radius);

box-shadow:var(--shadow);

text-align:center;

}

.quest-buttons{

margin-top:30px;

display:flex;

gap:15px;

justify-content:center;

flex-wrap:wrap;

}

.quest-buttons button{

padding:12px 20px;

border:none;

background:var(--navy);

color:white;

border-radius:30px;

cursor:pointer;

}

#quest-result{

margin-top:30px;

font-size:1.5rem;

font-weight:700;

color:var(--green);

}

/* Panorama */

#panorama{

height:600px;

border-radius:20px;

overflow:hidden;

box-shadow:var(--shadow);

}

.tour-nav{

text-align:center;

margin-top:25px;

}

.tour-nav button{

padding:12px 25px;

margin:5px;

border:none;

border-radius:30px;

background:var(--green);

color:white;

cursor:pointer;

}

/* 3D Cards */

.cards-container{

display:grid;

grid-template-columns:
repeat(auto-fit,minmax(280px,1fr));

gap:30px;

perspective:1200px;

}

.card3d{

height:300px;

border-radius:25px;

background:
linear-gradient(
135deg,
var(--green),
var(--navy)
);

display:flex;

justify-content:center;

align-items:center;

text-align:center;

color:white;

box-shadow:var(--shadow);

transition:.2s;

transform-style:preserve-3d;

}

.card-content{

padding:30px;

transform:translateZ(50px);

}

.card-content h3{

font-size:1.8rem;

margin-bottom:15px;

}

/* Countdown */

.countdown-wrapper{

text-align:center;

}

#days{

font-size:7rem;

font-weight:900;

color:var(--green);

line-height:1;

}

/* News */

.news-grid{

display:grid;

gap:20px;

}

.news-card{

background:white;

padding:30px;

border-radius:20px;

box-shadow:var(--shadow);

}

.news-card span{

color:var(--green);

font-weight:700;

}

/* CTA */

.cta-section{

padding:150px 10%;

text-align:center;

background:
linear-gradient(
135deg,
var(--green),
var(--navy)
);

color:white;

}

.cta-section h2{

font-size:3rem;

margin-bottom:40px;

}

/* Footer */

footer{

background:#07162d;

color:white;

padding:60px 20px;

text-align:center;

}

.footer-inner{

max-width:1000px;

margin:auto;

}

/* Responsive */

@media(max-width:768px){

.hero h1{

font-size:3rem;

}

.section-title{

font-size:2rem;

}

nav{

display:none;

}

.hero-buttons{

flex-direction:column;

align-items:center;

}

#days{

font-size:4rem;

}

}
```
```javascript id="6m1y7a"
/* ====================================
   Yokohama Suiran High School
   main.js
==================================== */

document.addEventListener(
'DOMContentLoaded',
() => {

initLoader();
initHeader();
initSmoothScroll();
initFadeAnimations();
initParallaxHero();

});

/* ====================================
   Loader
==================================== */

function initLoader(){

const loader =
document.getElementById('loader');

window.addEventListener('load',()=>{

setTimeout(()=>{

loader.style.opacity='0';
loader.style.visibility='hidden';

},800);

});

}

/* ====================================
   Header Scroll
==================================== */

function initHeader(){

const header =
document.getElementById('header');

window.addEventListener('scroll',()=>{

if(window.scrollY > 50){

header.classList.add('scrolled');

}else{

header.classList.remove('scrolled');

}

});

}

/* ====================================
   Smooth Scroll
==================================== */

function initSmoothScroll(){

const links =
document.querySelectorAll(
'a[href^="#"]'
);

links.forEach(link=>{

link.addEventListener(
'click',
function(e){

const targetId =
this.getAttribute('href');

if(targetId === '#') return;

const target =
document.querySelector(targetId);

if(!target) return;

e.preventDefault();

target.scrollIntoView({

behavior:'smooth',
block:'start'

});

});

});

}

/* ====================================
   Fade In Animation
==================================== */

function initFadeAnimations(){

const animatedElements =
document.querySelectorAll(

'.section-title,' +
'.section-lead,' +
'.stat-card,' +
'.quest-card,' +
'.card3d,' +
'.news-card,' +
'.countdown-wrapper'

);

animatedElements.forEach(el=>{

el.style.opacity='0';

el.style.transform=
'translateY(40px)';

el.style.transition=
'all .8s ease';

});

const observer =
new IntersectionObserver(

(entries)=>{

entries.forEach(entry=>{

if(entry.isIntersecting){

entry.target.style.opacity='1';

entry.target.style.transform=
'translateY(0)';

}

});

},

{
threshold:0.15
}

);

animatedElements.forEach(el=>{

observer.observe(el);

});

}

/* ====================================
   Hero Parallax
==================================== */

function initParallaxHero(){

const heroVideo =
document.querySelector(
'.hero-video'
);

if(!heroVideo) return;

window.addEventListener(
'scroll',
()=>{

const scrollY =
window.pageYOffset;

heroVideo.style.transform =
`translateY(${scrollY * 0.2}px)`;

}

);

}

/* ====================================
   Counter Trigger Event
==================================== */

window.dispatchEvent(

new CustomEvent(
'mainReady'
)

);

/* ====================================
   Utility
==================================== */

function debounce(
func,
wait = 100
){

let timeout;

return (...args)=>{

clearTimeout(timeout);

timeout = setTimeout(()=>{

func.apply(
null,
args
);

},wait);

};

}

/* ====================================
   Resize Handler
==================================== */

window.addEventListener(

'resize',

debounce(()=>{

console.log(
'viewport resized'
);

},200)

);

/* ====================================
   Scroll Progress Bar
==================================== */

const progressBar =
document.createElement('div');

progressBar.id =
'scroll-progress';

document.body.appendChild(
progressBar
);

Object.assign(
progressBar.style,
{
position:'fixed',
top:'0',
left:'0',
height:'4px',
width:'0%',
zIndex:'9999',
background:
'linear-gradient(90deg,#008b72,#f4c542)'
}
);

window.addEventListener(
'scroll',
()=>{

const winScroll =
document.documentElement
.scrollTop;

const height =
document.documentElement
.scrollHeight -
document.documentElement
.clientHeight;

const progress =
(winScroll / height) * 100;

progressBar.style.width =
progress + '%';

}
);

/* ====================================
   Back To Top Button
==================================== */

const topBtn =
document.createElement('button');

topBtn.innerHTML = '↑';

topBtn.id = 'topBtn';

document.body.appendChild(
topBtn
);

Object.assign(
topBtn.style,
{
position:'fixed',
right:'20px',
bottom:'20px',
width:'50px',
height:'50px',
border:'none',
borderRadius:'50%',
background:'#008b72',
color:'#fff',
fontSize:'20px',
cursor:'pointer',
display:'none',
zIndex:'999'
}
);

window.addEventListener(
'scroll',
()=>{

if(window.scrollY > 600){

topBtn.style.display='block';

}else{

topBtn.style.display='none';

}

}
);

topBtn.addEventListener(
'click',
()=>{

window.scrollTo({

top:0,
behavior:'smooth'

});

}
);

/* ====================================
   Console Message
==================================== */

console.log(
'%c Yokohama Suiran High School ',
'background:#008b72;color:white;padding:8px;font-size:16px;font-weight:bold'
);

console.log(
'未来は、待つものではない。創るものだ。'
);
```javascript id="f3o7ke"
/* ====================================
   Yokohama Suiran High School
   counter.js
==================================== */

document.addEventListener(
'DOMContentLoaded',
() => {

initCounters();

});

/* ====================================
   Counter Animation
==================================== */

function initCounters(){

const counters =
document.querySelectorAll(
'.counter'
);

if(!counters.length) return;

const observer =
new IntersectionObserver(

(entries)=>{

entries.forEach(entry=>{

if(entry.isIntersecting){

animateCounter(
entry.target
);

observer.unobserve(
entry.target
);

}

});

},

{
threshold:0.5
}

);

counters.forEach(counter=>{

observer.observe(counter);

});

}

/* ====================================
   Animate Single Counter
==================================== */

function animateCounter(
element
){

const target =
parseInt(
element.dataset.target,
10
);

const duration =
2000;

const startTime =
performance.now();

function update(
currentTime
){

const elapsed =
currentTime -
startTime;

const progress =
Math.min(
elapsed /
duration,
1
);

const eased =
easeOutCubic(
progress
);

const value =
Math.floor(
eased * target
);

element.textContent =
formatNumber(
value
);

if(progress < 1){

requestAnimationFrame(
update
);

}else{

element.textContent =
formatNumber(
target
);

}

}

requestAnimationFrame(
update
);

}

/* ====================================
   Easing
==================================== */

function easeOutCubic(
t
){

return 1 -
Math.pow(
1 - t,
3
);

}

/* ====================================
   Number Format
==================================== */

function formatNumber(
number
){

return number.toLocaleString(
'ja-JP'
);

}

/* ====================================
   Optional Suffix Support

   data-suffix="%"
   data-suffix="+"
==================================== */

function animateCounterWithSuffix(
element
){

const target =
parseInt(
element.dataset.target,
10
);

const suffix =
element.dataset.suffix || '';

const duration =
2000;

const startTime =
performance.now();

function update(
currentTime
){

const elapsed =
currentTime -
startTime;

const progress =
Math.min(
elapsed /
duration,
1
);

const eased =
easeOutCubic(
progress
);

const value =
Math.floor(
eased * target
);

element.textContent =
value + suffix;

if(progress < 1){

requestAnimationFrame(
update
);

}

}

requestAnimationFrame(
update
);

}

/* ====================================
   Debug
==================================== */

console.log(
'counter.js loaded'
);





