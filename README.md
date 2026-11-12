
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Priyanshi 💗</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;1,400;1,500&family=Poppins:wght@300;400;500;600;700&family=Dancing+Script:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>
:root {
 --pink:#ff8eaf;
 --light:#fff0f5;
 --rose:#ff5e91;
 --purple:#b9a0e8;
 --cream:#fffaf7;
 --text:#70495c;
 --dark:#513548;
}

* {margin:0;padding:0;box-sizing:border-box}
html {scroll-behavior:smooth}
body {
 font-family:'Poppins',sans-serif;
 background:var(--cream);
 color:var(--text);
 overflow-x:hidden;
}
button {font-family:inherit;cursor:pointer}
section {padding:85px 20px;position:relative;overflow:hidden}
.container {max-width:950px;margin:auto;text-align:center}
h1,h2 {font-family:'Playfair Display',serif}
h2 {font-size:clamp(2rem,6vw,3.4rem);color:var(--dark);margin-bottom:20px}
.subtitle {font-family:'Dancing Script',cursive;color:var(--rose);font-size:1.6rem;margin-bottom:12px}
p {line-height:1.9}
.btn {
 border:none;
 background:linear-gradient(135deg,#ff8eaf,#ff5e91);
 color:white;
 padding:15px 30px;
 border-radius:50px;
 font-size:15px;
 font-weight:600;
 box-shadow:0 8px 25px #ff8eaf55;
 transition:.3s;
}
.btn:hover {transform:translateY(-4px) scale(1.03)}
.hidden {display:none!important}

/* OPENING */
#opening {
 min-height:100svh;
 display:flex;
 align-items:center;
 justify-content:center;
 background:linear-gradient(145deg,#ffe5ed,#f9e7ff,#fff3e8);
 text-align:center;
}
.open-content {z-index:2;padding:25px}
.open-content .tiny {letter-spacing:4px;font-size:11px;color:#a66c8a}
.open-content h1 {
 font-size:clamp(3rem,10vw,6rem);
 color:#d94f83;
 margin:20px 0;
 line-height:1.2;
}
.open-content p {max-width:500px;margin:0 auto 30px}
.big-heart {font-size:65px;display:block;animation:heartbeat 1.4s infinite}
@keyframes heartbeat {50% {transform:scale(1.2)}}
.floating {position:absolute;animation:float 6s infinite ease-in-out;opacity:.7;pointer-events:none}
@keyframes float {
 0%,100% {transform:translateY(0) rotate(0)}
 50% {transform:translateY(-35px) rotate(15deg)}
}

/* NAV */
nav {
 position:sticky;
 top:0;
 z-index:20;
 display:flex;
 justify-content:center;
 flex-wrap:wrap;
 gap:8px;
 padding:13px;
 background:#fffaf0ef;
 backdrop-filter:blur(15px);
 border-bottom:1px solid #ffd8e5;
}
nav a {text-decoration:none;color:#a65b7b;font-size:11px;font-weight:600;padding:9px 12px;border-radius:30px}
nav a:hover {background:#ffe5ee}

/* HERO */
#home {background:linear-gradient(135deg,#fff0f5,#f5edff,#fff8ed);padding:100px 20px}
.hero-title {font-size:clamp(2.8rem,8vw,5.5rem);color:#d94f83;line-height:1.2}
.script {font-family:'Dancing Script',cursive;font-size:clamp(2rem,6vw,3.5rem);color:#ad80ca;margin:15px 0}
.hero-text {max-width:600px;margin:20px auto 30px}

/* LETTER */
#letter {background:#fffaf7}
.letter {
 max-width:750px;
 margin:35px auto 0;
 padding:clamp(25px,6vw,55px);
 background:white;
 border-radius:25px;
 box-shadow:0 15px 60px #a45d7620;
 border:1px solid #ffe3ed;
 text-align:left;
 position:relative;
}
.letter:before {content:'♡';position:absolute;right:25px;top:12px;font-size:45px;color:#ffb3c9}
.letter p {margin:17px 0;font-size:14px}
.signature {font-family:'Dancing Script',cursive;color:#e66b99;font-size:30px}

/* CARDS */
#special {background:linear-gradient(135deg,#fff0f5,#f9f0ff)}
.cards {display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:20px;margin-top:40px}
.card {
 padding:30px 22px;
 border-radius:22px;
 background:#ffffffd9;
 box-shadow:0 8px 30px #b77b9320;
 transition:.3s;
 border:1px solid #ffe1eb;
}
.card:hover {transform:translateY(-8px);box-shadow:0 15px 35px #b77b9340}
.card .emoji {font-size:38px;margin-bottom:15px}
.card h3 {font-family:'Playfair Display',serif;font-size:21px;color:#a64d77;margin-bottom:10px}
.card p {font-size:13px}

/* WISHES */
#wishes {background:linear-gradient(140deg,#fff6ed,#ffeaf2)}
.wish-list {max-width:700px;margin:35px auto;display:grid;gap:13px}
.wish {background:white;padding:19px;border-radius:15px;text-align:left;box-shadow:0 5px 20px #d89ab522;font-size:14px;transition:.3s}
.wish:hover {transform:translateX(7px)}
.wish span {margin-right:10px}

/* GAMES */
#games {background:linear-gradient(145deg,#f5eaff,#fff0f5)}
.game-card {
 background:#ffffffeb;
 padding:35px 22px;
 border-radius:25px;
 margin:25px auto;
 max-width:650px;
 box-shadow:0 10px 35px #a87db329;
 border:1px solid #f4d7eb;
}
.game-card h3 {font-family:'Playfair Display',serif;font-size:26px;color:#b35c87;margin-bottom:12px}
.game-card p {font-size:13px;margin-bottom:20px}
#heart-area {height:260px;background:linear-gradient(135deg,#fff0f5,#f3eaff);border-radius:20px;position:relative;overflow:hidden;margin:20px 0}
.heart-target {position:absolute;border:0;background:transparent;font-size:30px;animation:heartbeat 1s infinite}
.score {font-weight:700;color:#e65c91;font-size:19px}
.quiz-option {display:block;width:100%;margin:10px 0;padding:14px;border:1px solid #ffd0df;background:#fff5f8;color:#86546c;border-radius:12px;font-size:13px}
.quiz-option:hover {background:#ffe0eb}
#quiz-result {margin-top:15px;font-weight:600;color:#d94f83}
.wish-box {font-family:'Dancing Script',cursive;font-size:27px;color:#c45d91;padding:25px 10px;min-height:100px}

/* GIFTS */
#gifts {background:linear-gradient(135deg,#fff1f5,#fff8ed)}
.gift-grid {display:grid;grid-template-columns:repeat(3,1fr);gap:15px;max-width:650px;margin:35px auto}
.gift {background:white;padding:25px 10px;border-radius:20px;border:1px solid #ffdfeb;box-shadow:0 7px 25px #dca0b822;transition:.3s}
.gift:hover {transform:translateY(-7px)}
.gift div {font-size:45px}
.gift p {font-size:12px;margin-top:10px}
.gift-message {font-size:14px;color:#c35a87;margin-top:25px;min-height:55px;font-weight:500}

/* ENDING */
#ending {
 background:linear-gradient(145deg,#fce0ec,#edddff,#fff0e7);
 min-height:75vh;
 display:flex;
 align-items:center;
 justify-content:center;
}
.ending-card {max-width:700px;background:#ffffffc9;padding:45px 25px;border-radius:30px;box-shadow:0 15px 50px #9d67852b}
.ending-card p {font-size:14px;margin:20px 0}
footer {background:#fff7f8;text-align:center;padding:25px;font-size:12px;color:#bc7a98}

/* PARTICLES */
.particle {position:fixed;bottom:-30px;z-index:100;pointer-events:none;animation:rise 5s linear forwards}
@keyframes rise {to {transform:translateY(-110vh) rotate(360deg);opacity:0}}

/* REVEAL */
.reveal {opacity:0;transform:translateY(35px);transition:all .8s ease}
.reveal.show {opacity:1;transform:translateY(0)}

@media(max-width:500px) {
 nav {gap:2px;padding:9px 3px}
 nav a {font-size:9px;padding:8px}
 .gift-grid {gap:8px}
 .gift {padding:20px 5px}
 .game-card {padding:25px 15px}
}
</style>
</head>

<body>

<!-- OPENING SCREEN -->
<section id="opening">
 <div class="floating" style="top:10%;left:10%;font-size:30px">♡</div>
 <div class="floating" style="top:20%;right:10%;font-size:35px">✨</div>
 <div class="floating" style="bottom:15%;left:15%;font-size:25px">🌷</div>
 <div class="floating" style="bottom:20%;right:12%;font-size:30px">💗</div>

 <div class="open-content">
  <span class="big-heart">💗</span>
  <p class="tiny">A LITTLE SOMETHING MADE WITH LOVE</p>
  <h1>Heyyy<br>Priyanshiiii!</h1>
  <p>Someone has a very special birthday today... and this little world is all yours. 🥹</p>
  <button class="btn" onclick="startWebsite()">Open Your Surprise 🎀</button>
  <p style="margin-top:20px;font-size:11px">Psst... there's a lot of love waiting inside ♡</p>
 </div>
</section>

<div id="main" class="hidden">

<nav>
 <a href="#home">Home ♡</a>
 <a href="#letter">A Letter 💌</a>
 <a href="#special">You ✨</a>
 <a href="#wishes">Wishes 🌷</a>
 <a href="#games">Games 🎮</a>
 <a href="#gifts">Surprises 🎁</a>
</nav>

<!-- HERO -->
<section id="home">
 <div class="container">
  <div class="reveal">
   <p class="subtitle">The world is a little brighter today...</p>
   <h1 class="hero-title">HAPPY<br>BIRTHDAY!</h1>
   <p class="script">My dearest Priyanshi 💗</p>
   <p class="hero-text">
    Today isn't just another day. Today is the day someone as wonderful as you came into this world. And honestly, I'm really glad you did.
   </p>
   <div style="font-size:35px;margin:25px">🌸 🎀 🦋 🌷</div>
   <a href="#letter"><button class="btn">There's a letter for you 💌</button></a>
  </div>
 </div>
</section>

<!-- LETTER -->
<section id="letter">
 <div class="container reveal">
  <p class="subtitle">A little something from my heart</p>
  <h2>A Letter For You 💌</h2>

  <div class="letter">
   <p>Dearest Priyanshiiii, 💗</p>

   <p>First of all, HAPPIEST BIRTHDAYYYYY!! I hope today brings you a million reasons to smile, the kind of happiness that stays with you for a long, long time, and all the little things that make your heart happy.</p>

   <p>I honestly don't even know where to begin. Sometimes it's difficult to put into words how much a person means to you. And I guess you're one of those people for me.</p>

   <p>I just want you to know that I'm genuinely grateful to have you in my life. Out of all the people we meet, not everyone becomes someone we can call a true friend. But you're one of those rare people I genuinely cherish.</p>

   <p>You know what? It's the little things. The random conversations, the silly moments, the laughter, the unexpected talks, the stupid jokes and all those ordinary moments that somehow become special. I hope you know how much I appreciate every little part of our bond.</p>

   <p>I hope you never ever doubt your worth. You're important, you're appreciated, and you deserve so much happiness. Never let the world make you forget how special you are.</p>

   <p>I wish I could give you a lifetime supply of happiness, unlimited chocolates, endless hugs and a magical button that makes every bad day disappear. Because honestly, you deserve all of that and much more.</p>

   <p>I hope this new chapter brings you beautiful opportunities, unforgettable memories, genuine people, endless success and countless reasons to smile.</p>

   <p>And one more thing... I hope we keep making memories, keep laughing over the dumbest things, keep annoying each other and keep being there for one another. Because friendships like these are worth holding onto.</p>

   <p>Thank you for being YOU. Never change the beautiful little things that make you who you are.</p>

   <p>May Allah protect you from every sadness, bless your life with peace, keep you healthy and grant you everything your heart silently wishes for. Ameen. 🤍</p>

   <p>Happy birthday once again, my favourite human! 🥹</p>

   <p class="signature">With endless love & lots of hugs ♡</p>
  </div>
 </div>
</section>

<!-- SPECIAL -->
<section id="special">
 <div class="container">
  <div class="reveal">
   <p class="subtitle">Let's talk about someone...</p>
   <h2>Why You're So Special 🌷</h2>
   <p>Because being you is already enough of a reason.</p>
  </div>

  <div class="cards">
   <div class="card reveal">
    <div class="emoji">🌸</div>
    <h3>Your Smile</h3>
    <p>I hope you always have a reason to smile. The world needs more of that happiness.</p>
   </div>

   <div class="card reveal">
    <div class="emoji">🦋</div>
    <h3>Your Existence</h3>
    <p>Some people make life a little more beautiful simply by being in it. You're one of them.</p>
   </div>

   <div class="card reveal">
    <div class="emoji">💗</div>
    <h3>Your Heart</h3>
    <p>Never stop being the person you are. The little things about you matter.</p>
   </div>

   <div class="card reveal">
    <div class="emoji">🎀</div>
    <h3>Your Personality</h3>
    <p>There's only one Priyanshi, and that's honestly pretty wonderful.</p>
   </div>

   <div class="card reveal">
    <div class="emoji">🌙</div>
    <h3>Your Presence</h3>
    <p>Even an ordinary day can become better with a little conversation with you.</p>
   </div>

   <div class="card reveal">
    <div class="emoji">🫶</div>
    <h3>Our Friendship</h3>
    <p>One of those connections I'm genuinely thankful for. Always cherish it.</p>
   </div>

   <div class="card reveal">
    <div class="emoji">✨</div>
    <h3>Your Dreams</h3>
    <p>I hope you achieve everything you've ever dreamed of and even things you haven't imagined yet.</p>
   </div>

   <div class="card reveal">
    <div class="emoji">🌷</div>
    <h3>Simply YOU</h3>
    <p>No explanation needed. You're special just because you're YOU.</p>
   </div>
  </div>
 </div>
</section>

<!-- WISHES -->
<section id="wishes">
 <div class="container reveal">
  <p class="subtitle">A hundred wishes wouldn't be enough...</p>
  <h2>Things I Wish For You 🤍</h2>
  <div class="wish-list">
   <div class="wish"><span>🤍</span> May Allah protect you wherever you go.</div>
   <div class="wish"><span>🌸</span> May your smile never have a reason to disappear.</div>
   <div class="wish"><span>✨</span> May all your dreams find their way to reality.</div>
   <div class="wish"><span>🦋</span> May you always feel loved, valued and appreciated.</div>
   <div class="wish"><span>🌷</span> May every new chapter be better than the last.</div>
   <div class="wish"><span>💗</span> May you never have to question your worth.</div>
   <div class="wish"><span>🌙</span> May Allah fill your heart with peace and contentment.</div>
   <div class="wish"><span>🎀</span> May you meet people who appreciate your beautiful heart.</div>
   <div class="wish"><span>🧸</span> May your difficult days become easier and your happy days endless.</div>
   <div class="wish"><span>🥹</span> May you always have someone to laugh with, talk to and lean on.</div>
   <div class="wish"><span>🌻</span> May success follow you in everything you do.</div>
   <div class="wish"><span>💐</span> And may you receive all the happiness you deserve.</div>
  </div>
 </div>
</section>

<!-- GAMES -->
<section id="games">
 <div class="container">
  <div class="reveal">
   <p class="subtitle">Okay birthday girl, time to play!</p>
   <h2>Birthday Fun Zone 🎮</h2>
   <p>Because a birthday without a little fun isn't a birthday!</p>
  </div>

  <!-- GAME 1 -->
  <div class="game-card reveal">
   <h3>Game 1: Catch the Hearts 💗</h3>
   <p>Catch as many floating hearts as you can in 15 seconds! Let's see your score, birthday girl!</p>

   <div class="score">Score: <span id="score">0</span> 💗</div>
   <p>Time: <span id="timer">15</span> seconds</p>

   <div id="heart-area">
    <p id="game-start-text" style="padding-top:110px">Ready, Priyanshi? 🥹</p>
   </div>

   <button class="btn" onclick="startHeartGame()">Start Game 🎮</button>
   <p id="heart-result" style="margin-top:15px"></p>
  </div>

  <!-- GAME 2 -->
  <div class="game-card reveal">
   <h3>Game 2: How Special Is Our Bond? 🫶</h3>
   <p>Let's see what you think about this little friendship!</p>

   <div id="quiz">
    <h4 id="question" style="margin:20px 0;color:#a64d77">What makes a friendship special?</h4>
    <button class="quiz-option" onclick="answerQuiz(0)">Expensive gifts 🎁</button>
    <button class="quiz-option" onclick="answerQuiz(1)">Trust, laughter and genuine care 💗</button>
    <button class="quiz-option" onclick="answerQuiz(2)">Only talking when bored 😭</button>
   </div>

   <p id="quiz-result"></p>
   <button class="btn" style="margin-top:15px" onclick="nextQuestion()">Next Question →</button>
  </div>

  <!-- GAME 3 -->
  <div class="game-card reveal">
   <h3>Game 3: Make a Birthday Wish 🌠</h3>
   <p>Close your eyes, make a beautiful wish and tap the button below!</p>
   <div class="wish-box" id="wish-output">Your little magical moment awaits... ✨</div>
   <button class="btn" onclick="makeWish()">Make My Wish 🌷</button>
  </div>

  <!-- GAME 4 -->
  <div class="game-card reveal">
   <h3>Game 4: Your Compliment Machine 🎀</h3>
   <p>Feeling cute? You should! Tap below for your daily reminder.</p>
   <div class="wish-box" id="compliment">You are wonderful. Don't ever forget that. 💗</div>
   <button class="btn" onclick="compliment()">Tell Me Something Sweet 💌</button>
  </div>
 </div>
</section>

<!-- GIFTS -->
<section id="gifts">
 <div class="container reveal">
  <p class="subtitle">Three little surprises...</p>
  <h2>Open Your Gifts! 🎁</h2>
  <p>Choose any gift box. Each one has a little message just for you.</p>

  <div class="gift-grid">
   <button class="gift" onclick="openGift(0)">
    <div>🎁</div><p>Gift No. 1</p>
   </button>
   <button class="gift" onclick="openGift(1)">
    <div>🎀</div><p>Gift No. 2</p>
   </button>
   <button class="gift" onclick="openGift(2)">
    <div>💝</div><p>Gift No. 3</p>
   </button>
  </div>

  <div class="gift-message" id="gift-message">Your surprises are waiting... 💗</div>
 </div>
</section>

<!-- FINAL -->
<section id="ending">
 <div class="container reveal">
  <div class="ending-card">
   <div style="font-size:55px">💗🌷🦋</div>
   <p class="subtitle">One last thing before you go...</p>
   <h2>You're A Rare One, Priyanshi.</h2>

   <p>If there's one thing I want you to take away from this little surprise, it's that you genuinely matter.</p>

   <p>Life is full of people who come and go, but every once in a while, we meet someone whose friendship we truly want to keep.</p>

   <p>And I'm genuinely glad I got to know you.</p>

   <p>I hope this year gives you beautiful memories, unexpected happiness, endless opportunities and everything your heart has been wishing for.</p>

   <p>Never forget how special you are. Never settle for less than the happiness you deserve. And please, keep smiling.</p>

   <h2 style="font-size:35px;color:#df6797">HAPPY BIRTHDAYYYYY! 🎂</h2>

   <p class="signature">Your friend, always. ♡</p>

   <button class="btn" onclick="celebrate()">One Last Surprise! 🎉</button>
   <p id="final-message" style="margin-top:20px"></p>
  </div>
 </div>
</section>

<footer>
 Made with a whole lot of love, just for Priyanshi. 💗
 <br><br>
 Stay happy, birthday girl. Always. 🌷
</footer>

</div>

<script>

/* OPEN WEBSITE */
function startWebsite() {
 document.getElementById('opening').style.display='none';
 document.getElementById('main').classList.remove('hidden');
 window.scrollTo(0,0);
 setInterval(createParticle,700);
}

/* FLOATING HEARTS */
function createParticle() {
 const items=['💗','💕','♡','✨','🌸','🦋'];
 const el=document.createElement('div');
 el.className='particle';
 el.innerHTML=items[Math.floor(Math.random()*items.length)];
 el.style.left=Math.random()*100+'vw';
 el.style.fontSize=(15+Math.random()*20)+'px';
 el.style.animationDuration=(4+Math.random()*4)+'s';
 document.body.appendChild(el);
 setTimeout(()=>el.remove(),8000);
}

/* SCROLL ANIMATION */
const observer=new IntersectionObserver(entries=>{
 entries.forEach(entry=>{
  if(entry.isIntersecting) entry.target.classList.add('show');
 });
},{threshold:.1});

document.querySelectorAll('.reveal').forEach(el=>observer.observe(el));

/* GAME 1: CATCH HEARTS */
let score=0;
let time=15;
let heartInterval;
let timerInterval;
let playing=false;

function startHeartGame() {
 if(playing)return;

 playing=true;
 score=0;
 time=15;

 document.getElementById('score').innerText=score;
 document.getElementById('timer').innerText=time;
 document.getElementById('heart-result').innerText='';
 document.getElementById('game-start-text').style.display='none';

 const area=document.getElementById('heart-area');
 area.querySelectorAll('.heart-target').forEach(e=>e.remove());

 heartInterval=setInterval(()=>{
  if(!playing)return;

  const heart=document.createElement('button');
  heart.className='heart-target';
  heart.innerText=['💗','💖','💕','💝'][Math.floor(Math.random()*4)];
  heart.style.left=Math.random()*85+'%';
  heart.style.top=Math.random()*75+'%';

  heart.onclick=()=>{
   if(!playing)return;
   score++;
   document.getElementById('score').innerText=score;
   heart.remove();
  };

  area.appendChild(heart);
  setTimeout(()=>heart.remove(),1200);
 },450);

 timerInterval=setInterval(()=>{
  time--;
  document.getElementById('timer').innerText=time;
  if(time<=0)endHeartGame();
 },1000);
}

function endHeartGame() {
 playing=false;
 clearInterval(heartInterval);
 clearInterval(timerInterval);

 document.querySelectorAll('.heart-target').forEach(e=>e.remove());

 let message=score>=20?'WOWWWW! You are a heart-catching champion! 🏆':
 score>=10?'Awww! Look at you go, birthday girl! 💗':
 'Awwww! You still deserve a million hearts! 💝';

 document.getElementById('heart-result').innerText=
 'You caught '+score+' hearts! '+message;

 document.getElementById('game-start-text').style.display='block';
 document.getElementById('game-start-text').innerText='Game Over! 🎀';
}

/* GAME 2: FRIENDSHIP QUIZ */
const questions=[
 {
 q:'What makes a friendship truly special?',
 a:['Expensive gifts 🎁','Trust, laughter and genuine care 💗','Only talking when bored 😭'],
 correct:1,
 msg:'Exactlyyyy! A genuine bond is priceless! 🥹'
 },
 {
 q:'What should a true friend always bring?',
 a:['Drama 😭','Competition','Support and happiness 🫶'],
 correct:2,
 msg:'Yesssss! Always be there for each other! 💗'
 },
 {
 q:'What does Priyanshi deserve?',
 a:['Endless happiness 🌸','A million chocolates 🍫','ALL OF THE ABOVE! 🎀'],
 correct:2,
 msg:'CORRECT! SHE DESERVES EVERYTHINGGG! 💗'
 },
 {
 q:'What is the best part of a beautiful friendship?',
 a:['Making memories together 💕','Counting messages','Being strangers'],
 correct:0,
 msg:'Awww! Here is to a million more memories! 🦋'
 }
];

let qIndex=0;

function loadQuestion() {
 const q=questions[qIndex];
 document.getElementById('question').innerText=q.q;

 document.querySelectorAll('.quiz-option').forEach((btn,i)=>{
  btn.innerText=q.a[i];
  btn.style.display='block';
  btn.disabled=false;
  btn.style.opacity='1';
 });

 document.getElementById('quiz-result').innerText='';
}

function answerQuiz(index) {
 const q=questions[qIndex];
 document.querySelectorAll('.quiz-option').forEach(b=>b.disabled=true);

 document.getElementById('quiz-result').innerText=
 index===q.correct?q.msg:'Hehe, nice try! But here is another chance next time! 💗';
}

function nextQuestion() {
 qIndex=(qIndex+1)%questions.length;
 loadQuestion();
}

/* GAME 3: WISH GENERATOR */
const wishes=[
 'May your biggest dreams become your favourite memories. 🌠',
 'May Allah bless you with happiness beyond imagination. 🤍',
 'May your heart always find reasons to smile. 🌸',
 'May beautiful things find their way into your life. 🦋',
 'May this year be the beginning of something magical. ✨',
 'May you always be surrounded by people who genuinely care. 💗',
 'May every silent prayer of yours be answered. 🌙'
];

function makeWish() {
 const wish=wishes[Math.floor(Math.random()*wishes.length)];
 document.getElementById('wish-output').innerText=wish;
}

/* GAME 4: COMPLIMENT MACHINE */
const compliments=[
 'You are someone worth celebrating every single day. 💗',
 'Your existence makes this world a little sweeter. 🌸',
 'You deserve all the flowers, chocolates and happiness. 🎀',
 'Never forget how genuinely special you are. 🦋',
 'You are one of a kind, Priyanshi. ✨',
 'I hope you always see yourself as beautifully as the people who care about you do. 🥹',
 'A million stars could never outshine your uniqueness. 🌙',
 'Keep smiling, birthday girl. You look good being happy! 💕',
 'You deserve a lifetime of beautiful tomorrows. 🌷'
];

function compliment() {
 const c=compliments[Math.floor(Math.random()*compliments.length)];
 document.getElementById('compliment').innerText=c;
}

/* GIFT BOXES */
const gifts=[
 '🎁 Your first gift: A lifetime supply of hugs, happiness and endless reasons to smile. You deserve it all! 💗',
 '🎀 Your second gift: A promise that your friendship is genuinely appreciated. Thank you for being you! 🥹',
 '💝 Your third gift: A wish that every beautiful thing you dream of finds its way to you. May Allah bless you always! 🤍'
];

function openGift(index) {
 document.getElementById('gift-message').innerText=gifts[index];
}

/* FINAL SURPRISE */
function celebrate() {
 const msg=document.getElementById('final-message');
 msg.innerText='YOU ARE LOVED, APPRECIATED AND ABSOLUTELY ONE OF A KIND, PRIYANSHI!!! 💗🎂🎉';
 for(let i=0;i<80;i++) {
  setTimeout(createParticle,i*30);
 }
}

/* INITIAL QUIZ */
loadQuestion();

</script>
</body>
</html>
