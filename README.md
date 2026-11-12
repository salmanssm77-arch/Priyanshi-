<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#fff3f7">
<title>For Priyanshi 💗</title>

<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=DM+Sans:wght@400;500;600;700&family=Parisienne&display=swap" rel="stylesheet">

<style>
:root {
  --pink:#f6c9d8;
  --rose:#e99ab7;
  --lav:#dcd2f4;
  --cream:#fffaf7;
  --ink:#553d50;
  --muted:#8c7186;
}

* { box-sizing:border-box; }

html { scroll-behavior:smooth; }

body {
  margin:0;
  background:var(--cream);
  color:var(--ink);
  font-family:'DM Sans',sans-serif;
  overflow-x:hidden;
}

button { font:inherit; cursor:pointer; }

#progress {
  position:fixed;
  top:0;left:0;
  height:3px;width:0;
  background:linear-gradient(90deg,#e99ab7,#c9b8ec,#e8c78f);
  z-index:100;
}

#intro {
  position:fixed;
  inset:0;
  z-index:50;
  display:grid;
  place-items:center;
  text-align:center;
  padding:25px;
  background:radial-gradient(circle at top,#fff,#fff0f6 55%,#eee8fb);
  transition:1s;
}

#intro.hide {
  opacity:0;
  visibility:hidden;
}

.intro-title {
  font:600 clamp(2.7rem,9vw,5rem)/1 'Cormorant Garamond';
  color:#704d68;
}

.intro-title span {
  font-family:'Parisienne';
  color:#d47fa2;
}

.gift {
  font-size:90px;
  display:block;
  margin:30px;
  animation:bob 2s infinite;
}

@keyframes bob {
  50% { transform:translateY(-12px) rotate(5deg); }
}

.btn {
  border:0;
  border-radius:40px;
  padding:15px 25px;
  background:linear-gradient(120deg,#e99ab7,#c9b8ec);
  color:white;
  font-weight:700;
  box-shadow:0 10px 25px #d79ab74d;
  transition:.3s;
}

.btn:hover { transform:translateY(-3px); }

main {
  opacity:0;
  transition:1s;
}

main.ready { opacity:1; }

section {
  padding:90px 22px;
  position:relative;
}

.wrap {
  width:min(100%,1000px);
  margin:auto;
}

.center { text-align:center; }

.kicker {
  color:#b17c9b;
  font-size:12px;
  letter-spacing:4px;
  text-transform:uppercase;
}

h1,h2,h3 { font-family:'Cormorant Garamond',serif; }

h2 {
  font-size:clamp(2.5rem,6vw,4rem);
  line-height:1;
}

.lead {
  max-width:650px;
  margin:auto;
  color:var(--muted);
  line-height:1.9;
}

.hero {
  min-height:95vh;
  display:grid;
  place-items:center;
  text-align:center;
  background:radial-gradient(ellipse at top,#fff,#fff3f7 50%,#f0ebfb);
  overflow:hidden;
}

.hero h1 {
  font-size:clamp(3rem,10vw,7rem);
  line-height:.9;
  color:#714e68;
}

.hero h1 span {
  display:block;
  font-family:'Parisienne';
  color:#d77fa2;
  font-size:1.2em;
  line-height:1.3;
}

.hero-cake {
  font-size:75px;
  animation:bob 3s infinite;
}

.decor {
  position:absolute;
  font-size:30px;
  animation:float 7s infinite ease-in-out;
}

.decor.a { top:15%;left:9%; }
.decor.b { top:25%;right:10%; }
.decor.c { bottom:15%;left:15%; }

@keyframes float {
  50% { transform:translate(12px,-20px) rotate(15deg); }
}

.soft {
  background:linear-gradient(145deg,#fff7fa,#f5f0ff);
}

.card {
  background:#fffdfb;
  border:1px solid #f1dce5;
  border-radius:28px;
  padding:35px;
  box-shadow:0 20px 60px #b98ba31c;
  margin:35px auto;
  max-width:760px;
}

.envelope {
  font-size:60px;
  background:none;
  border:0;
  transition:.3s;
}

.envelope:hover { transform:rotate(-10deg) scale(1.1); }

.letter {
  display:none;
  font:22px/1.8 'Cormorant Garamond';
  white-space:pre-line;
  text-align:left;
}

.letter.show {
  display:block;
  animation:fade .8s;
}

@keyframes fade {
  from { opacity:0;transform:translateY(15px); }
  to { opacity:1;transform:none; }
}

.cards {
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:17px;
  margin-top:40px;
}

.reason {
  background:white;
  border:1px solid #f0dce5;
  border-radius:22px;
  padding:25px;
  transition:.3s;
}

.reason:hover {
  transform:translateY(-8px) rotate(-1deg);
  box-shadow:0 15px 35px #9e6b8320;
}

.reason .emoji { font-size:35px; }

.reason p {
  color:#806a7b;
  line-height:1.7;
}

.friendship {
  background:linear-gradient(135deg,#f8edf5,#f2effc);
}

.quote {
  font:600 clamp(1.7rem,4vw,2.7rem)/1.3 'Cormorant Garamond';
  color:#9b6485;
  margin-top:35px;
}

.wish-grid {
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:12px;
  margin:35px 0;
}

.wish {
  background:linear-gradient(145deg,#fff,#fff3f7);
  border:1px solid #f3e0e8;
  border-radius:16px;
  padding:15px;
  color:#866c7f;
  opacity:0;
  transform:translateY(10px);
  transition:.5s;
}

.wish.visible {
  opacity:1;
  transform:none;
}

.reminders {
  background:linear-gradient(140deg,#f9e8f0,#eee9fb);
}

.reminder-list {
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:12px;
  margin-top:35px;
}

.reminder {
  padding:15px 20px;
  background:#ffffffbb;
  border-radius:30px;
  color:#8c6481;
  font:600 20px 'Cormorant Garamond';
}

.cake-area {
  background:#fff8f4;
}

.cake {
  font-size:110px;
  margin:20px;
}

.candles {
  display:flex;
  justify-content:center;
  gap:20px;
}

.candle {
  height:55px;
  width:13px;
  border:0;
  border-radius:8px;
  background:#f6c5d7;
  position:relative;
}

.candle:before {
  content:'';
  position:absolute;
  width:12px;
  height:18px;
  top:-20px;
  left:0;
  border-radius:50%;
  background:radial-gradient(#fff5b4,#ffbf69,#f28c67);
  box-shadow:0 0 12px #ffbb66;
}

.candle.out:before { display:none; }

.gallery {
  background:#fcf7fb;
}

.gallery-grid {
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:20px;
  margin-top:40px;
}

.polaroid {
  background:white;
  padding:12px 12px 20px;
  box-shadow:0 12px 28px #88627d20;
  transform:rotate(-2deg);
  transition:.3s;
}

.polaroid:nth-child(even) { transform:rotate(3deg); }

.polaroid:hover { transform:rotate(0) translateY(-7px); }

.photo {
  aspect-ratio:1;
  background:linear-gradient(135deg,#f9dce7,#e9e3f8);
  display:grid;
  place-items:center;
  overflow:hidden;
  color:#9a7890;
}

.photo img {
  width:100%;
  height:100%;
  object-fit:cover;
}

.polaroid label {
  display:block;
  text-align:center;
  font:22px 'Parisienne';
  padding-top:12px;
}

.final {
  background:radial-gradient(ellipse at top,#634c68,#2e2739 75%);
  color:#fff4f8;
  text-align:center;
}

.final h2 { color:#fff4f8; }

.final p {
  max-width:680px;
  margin:20px auto;
  line-height:2;
  color:#e8d8e4;
}

.signature {
  font:32px 'Parisienne';
  color:#f2bad0;
  margin:30px;
}

.secret-note {
  display:none;
  padding:25px;
  margin:25px auto;
  max-width:550px;
  border:1px solid #94758f;
  border-radius:20px;
  line-height:1.8;
}

.secret-note.show { display:block; }

.music {
  position:fixed;
  bottom:15px;
  right:15px;
  z-index:10;
  background:#ffffffdf;
  padding:10px 15px;
  border-radius:30px;
  border:1px solid #f0dce6;
}

.music button {
  border:0;
  background:none;
  color:#986a86;
  font-size:20px;
}

#confetti {
  position:fixed;
  inset:0;
  pointer-events:none;
  z-index:100;
  overflow:hidden;
}

.piece {
  position:absolute;
  top:-20px;
  width:8px;
  height:13px;
  animation:fall 4s linear forwards;
}

@keyframes fall {
  to { transform:translateY(110vh) rotate(760deg); }
}

.heart {
  position:fixed;
  bottom:-30px;
  pointer-events:none;
  animation:rise 5s linear forwards;
}

@keyframes rise {
  to { transform:translateY(-110vh) rotate(25deg);opacity:0; }
}

@media(max-width:700px) {
  section { padding:70px 18px; }
  .cards { grid-template-columns:repeat(2,1fr); }
  .wish-grid { grid-template-columns:repeat(2,1fr); }
  .gallery-grid { grid-template-columns:repeat(2,1fr); }
}

@media(max-width:420px) {
  .cards { gap:10px; }
  .reason { padding:17px; }
}

@media(prefers-reduced-motion:reduce) {
  *,*:before,*:after {
    animation-duration:.01ms!important;
    scroll-behavior:auto!important;
    transition-duration:.01ms!important;
  }
}
</style>
</head>

<body>

<div id="progress"></div>
<div id="confetti"></div>

<!-- OPENING SURPRISE -->
<div id="intro">
  <div>
    <div class="kicker">A tiny world made just for you</div>
    <h1 class="intro-title">
      Heyyyyy<br><span>Priyanshiiiiii!</span> 💗
    </h1>
    <p>Someone very special has a birthdayyyy...</p>
    <span class="gift">🎁</span>
    <button class="btn" id="openGift">OPEN YOUR SURPRISE 🎀</button>
  </div>
</div>

<main id="main">

<!-- HERO -->
<section class="hero">
  <span class="decor a">✧</span>
  <span class="decor b">♡</span>
  <span class="decor c">🌸</span>

  <div class="wrap">
    <div class="kicker">Today is all about you</div>
    <div class="hero-cake">🎂</div>

    <h1>
      HAPPIEST
      <span>Birthdayyyyy</span>
      PRIYANSHIIII!!
    </h1>

    <p class="lead">
      To one of the most precious souls I've ever come across.
      Today, the world gets another reason to celebrate you. 💗
    </p>

    <p class="lead" style="margin-top:20px">
      I hope this year brings you everything your heart has ever
      wished for. You deserve endless happiness, beautiful surprises,
      genuine smiles, peaceful days and all the little things that
      make life wonderful.
    </p>

    <p style="margin-top:40px">SCROLL DOWN FOR YOUR SURPRISE ↓</p>
  </div>
</section>

<!-- LETTER -->
<section class="soft center">
  <div class="wrap">
    <div class="kicker">Something from the heart</div>
    <h2>A Little Letter For You 💌</h2>
    <p class="lead">Some things deserve more than a birthday text.</p>

    <div class="card">
      <button class="envelope" id="openLetter">💌</button>
      <p id="letterHint">TAP TO OPEN YOUR LETTER</p>
      <div class="letter" id="letter"></div>
    </div>
  </div>
</section>

<!-- SPECIAL THINGS -->
<section class="center">
  <div class="wrap">
    <div class="kicker">A few things worth celebrating</div>
    <h2>Why You're So Special 🌷</h2>

    <div class="cards">
      <div class="reason">
        <div class="emoji">🌸</div>
        <h3>Your Kindness</h3>
        <p>Your kindness makes a difference, even in ways you might not notice.</p>
      </div>

      <div class="reason">
        <div class="emoji">☀️</div>
        <h3>Your Smile</h3>
        <p>Your smile deserves to stay, especially on ordinary days.</p>
      </div>

      <div class="reason">
        <div class="emoji">🦋</div>
        <h3>Your Presence</h3>
        <p>You have a way of making things feel a little better.</p>
      </div>

      <div class="reason">
        <div class="emoji">💗</div>
        <h3>Your Realness</h3>
        <p>You're one of those rare, genuine people. Never lose that.</p>
      </div>

      <div class="reason">
        <div class="emoji">✨</div>
        <h3>Your Dreams</h3>
        <p>You deserve every beautiful thing life has waiting for you.</p>
      </div>

      <div class="reason">
        <div class="emoji">🌼</div>
        <h3>Simply You</h3>
        <p>Never stop being the wonderful person you are.</p>
      </div>
    </div>
  </div>
</section>

<!-- FRIENDSHIP -->
<section class="friendship center">
  <div class="wrap">
    <div class="kicker">Our little corner</div>
    <h2>Some People Just Become<br>Your Favourite People 🧸</h2>

    <div class="card">
      <p class="lead">
        It's the random conversations, the silly jokes, laughing at
        absolutely nothing, and those little moments that somehow
        become big memories.
      </p>

      <p class="lead" style="margin-top:20px">
        It's being comfortable enough to be completely yourself,
        and having someone genuine to talk to.
        I'm grateful for the laughs, conversations and all the
        little bits of friendship that make life nicer.
      </p>

      <div class="quote">
        "Not every beautiful connection needs a name.
        Some people simply become important, and you're one of those people."
      </div>
    </div>
  </div>
</section>

<!-- WISHES -->
<section class="center">
  <div class="wrap">
    <div class="kicker">A hundred little good things</div>
    <h2>100 Little Wishes For You ✨</h2>
    <p class="lead">One birthday wish could never be enough.</p>

    <button class="btn" id="unlock">UNLOCK YOUR WISHES 💗</button>

    <div class="wish-grid" id="wishGrid"></div>
  </div>
</section>

<!-- REMINDERS -->
<section class="reminders center">
  <div class="wrap">
    <div class="kicker">Save these in your heart</div>
    <h2>A Little Reminder 🌸</h2>

    <div class="reminder-list">
      <span class="reminder">You're enough.</span>
      <span class="reminder">You're appreciated.</span>
      <span class="reminder">You're important.</span>
      <span class="reminder">Dream big.</span>
      <span class="reminder">You deserve happiness.</span>
      <span class="reminder">Never dim your light.</span>
      <span class="reminder">Keep being YOU.</span>
    </div>
  </div>
</section>

<!-- CAKE -->
<section class="cake-area center">
  <div class="wrap">
    <div class="kicker">A birthday tradition</div>
    <h2>Make A Wish, Priyanshiiii! 🎂</h2>
    <p class="lead">Tap every candle to blow it out!</p>

    <div class="candles">
      <button class="candle"></button>
      <button class="candle"></button>
      <button class="candle"></button>
      <button class="candle"></button>
      <button class="candle"></button>
    </div>

    <div class="cake">🎂</div>

    <p id="cakeMessage">
      Five little candles. Five little wishes. 💕
    </p>
  </div>
</section>

<!-- GALLERY -->
<section class="gallery center">
  <div class="wrap">
    <div class="kicker">Little moments, lovely memories</div>
    <h2>A Scrapbook Of Us 📸</h2>

    <p class="lead">
      Add your actual pictures here to make this corner
      even more personal.
    </p>

    <div class="gallery-grid" id="gallery">
      <div class="polaroid">
        <div class="photo">Your favourite photo ✿</div>
        <label>A little moment</label>
      </div>

      <div class="polaroid">
        <div class="photo">Add a memory ♡</div>
        <label>Good times</label>
      </div>

      <div class="polaroid">
        <div class="photo">One for memories ✨</div>
        <label>Our kind of chaos</label>
      </div>
    </div>

    <br>

    <label class="btn" for="photos">＋ ADD YOUR PHOTOS</label>
    <input type="file" id="photos" accept="image/*" multiple hidden>
  </div>
</section>

<!-- FINAL MESSAGE -->
<section class="final">
  <div class="wrap">
    <div class="kicker">One last thing</div>

    <h2>One Last Thing,<br>Priyanshi...</h2>

    <p>
      Thank you for being one of the most genuine and beautiful
      parts of my life.
    </p>

    <p>
      I don't know what the future holds, but I genuinely hope
      it brings you everything you've been working and wishing for.
      I hope you laugh a little louder, smile a little more,
      achieve everything you dream of and never lose the beautiful
      spark that makes you YOU.
    </p>

    <p>
      And no matter how busy life gets, I hope we never lose
      this beautiful friendship.
    </p>

    <p>Stay happy. Stay blessed. Stay exactly the way you are.</p>

    <h2>Happiest Birthday Once Again,<br>Priyanshiiiiii!! 💗</h2>

    <div class="signature">
      With lots and lots of appreciation, care and friendship. 💗
    </div>

    <button class="btn" id="secretBtn">One More Thing... ♡</button>

    <div class="secret-note" id="secretNote">
      And if you ever forget how special you are,
      I hope this little page reminds you.

      The world is better with you in it.
      Keep shining, keep laughing, and please never stop being you. 🌷
    </div>
  </div>
</section>

<footer style="text-align:center;padding:25px;background:#2e2739;color:#cbb7c8">
  Made with care, a little sparkle, and lots of friendship. ♡
</footer>

</main>

<!-- MUSIC PLAYER -->
<div class="music">
  <button id="musicBtn">♫</button>
  <span id="musicLabel">Music: off</span>
</div>

<!-- Add your own royalty-free MP3 file here -->
<audio id="music" loop>
  <!-- <source src="your-music.mp3" type="audio/mpeg"> -->
</audio>

<script>

// OPENING SURPRISE
document.getElementById('openGift').onclick = () => {
  confetti(150);
  hearts(20);

  document.getElementById('intro').classList.add('hide');
  document.getElementById('main').classList.add('ready');

  setTimeout(() => {
    document.getElementById('intro').remove();
  }, 1000);
};


// BIRTHDAY LETTER
const letterText = `Dear Priyanshi,

I genuinely don't know where to start because some people are just difficult to describe in words. You're one of those people.

I'm honestly so grateful that I got to know you. In a world where genuine connections are becoming so rare, having someone like you is something I'll always appreciate.

You're not just another person I talk to. You're someone whose presence makes ordinary days a little better. Someone I can laugh with, share random things with, talk about absolutely nothing and somehow still have the best conversations.

I hope you never forget how special you are. Never let anyone make you question your worth or the beautiful person you are.

Thank you for being YOU. Thank you for all the little moments, laughs, conversations and memories.

I genuinely hope we create a million more memories together.

Happy birthday, Priyanshi. Always keep smilinggggg. 💗`;

let letterOpened = false;

document.getElementById('openLetter').onclick = () => {
  if(letterOpened) return;

  letterOpened = true;

  const box = document.getElementById('letter');
  document.getElementById('letterHint').textContent =
    'A LITTLE NOTE FOR YOU 💗';

  box.style.display = 'block';

  let i = 0;

  const timer = setInterval(() => {
    box.textContent = letterText.slice(0, i += 3);

    if(i >= letterText.length) clearInterval(timer);
  }, 16);
};


// 100 WISHES
const wishes = [
"May your days be full of sunshine ☀️",
"May your heart always feel at peace 🕊️",
"May every dream find its way to you ✨",
"May you always feel loved 💗",
"May laughter find you every day 😄",
"May good health stay by your side 🌿",
"May you be proud of how far you've come 🌷",
"May courage meet you at every turn 🦋",
"May new doors open for you 🚪",
"May your efforts bloom into success 🌼",
"May you find beauty in little things 🌸",
"May your confidence keep growing 🌟",
"May kind people surround you 🤍",
"May your worries feel lighter ☁️",
"May you get countless reasons to celebrate 🎉",
"May your favourite songs find you 🎶",
"May every new beginning be beautiful 🌅",
"May you travel to places you dream of 🌍",
"May you never run out of curiosity 🔎",
"May your confidence keep growing 💫",
"May your kindness return to you tenfold 💌",
"May you get peaceful nights 🌙",
"May you feel safe being yourself 🫶",
"May you make memories worth keeping 📸",
"May your hard work be rewarded 🏆",
"May you laugh until your cheeks hurt 😂",
"May you always have someone to call 🤗",
"May your future feel exciting 🌈",
"May you find time for what you love 🎨",
"May you be gentle with yourself 🌺",
"May every setback teach you something 🌱",
"May you always have hope 💛",
"May your plans work out beautifully 🗓️",
"May you discover something wonderful 📚",
"May you be surrounded by honesty 🧡",
"May your smile come easily 😊",
"May you feel appreciated every day 💐",
"May you keep your beautiful spark ✨",
"May your heart stay brave 🦁",
"May you enjoy the little victories 🥳",
"May you find calm in busy moments 🍃",
"May you always have reasons to dream 🌠",
"May opportunities find you 🚀",
"May your friendships stay genuine 🫂",
"May you feel proud of your journey 🛤️",
"May you have beautiful days 🌻",
"May you be protected from negativity 🧿",
"May your kindness never be taken for granted 🌷",
"May you have adventures to remember 🧳",
"May every season bring something lovely 🍂",
"May your voice always be heard 🎤",
"May you keep learning and growing 🌳",
"May your goals feel closer every day 🎯",
"May you always find a reason to smile 💕",
"May your home feel warm and safe 🏡",
"May you get surprises that make your day 🎁",
"May your creativity flourish 🎀",
"May you be surrounded by positive energy ☀️",
"May you never doubt your worth 💎",
"May you find magic in ordinary days 🪄",
"May your patience bring beautiful things 🌾",
"May you have courage 💪",
"May your favourite people stay close 💞",
"May you always feel understood 💬",
"May your future be kinder than you imagine 🌤️",
"May your talents take you far 🎓",
"May you never stop exploring 🧭",
"May you have time to breathe 🌬️",
"May your little wishes come true ⭐",
"May you find joy in unexpected places 🌼",
"May you keep choosing happiness 💗",
"May you be celebrated for being you 🎊",
"May your dreams grow bigger 🌙",
"May you always have something to look forward to 📅",
"May your days be colourful 🎨",
"May you feel stronger with every challenge 🦋",
"May you receive the same care you give 🤍",
"May every chapter bring growth 📖",
"May you keep making beautiful memories 🥰",
"May your laughter never fade 🌸",
"May you be blessed with peace and barakah 🤲",
"May your path be filled with goodness 🌿",
"May you always have hope after hard days 🌅",
"May you feel proud, not pressured 🌷",
"May you find beauty in who you're becoming 🪞",
"May your kindness change someone's day 💌",
"May your heart stay soft and strong 💖",
"May you celebrate yourself more often 🥂",
"May your next year be your happiest yet 🎂",
"May you always be surrounded by love 🫶",
"May every effort lead somewhere wonderful 🌱",
"May life surprise you in the sweetest ways 🎀",
"May you chase your biggest dreams 🚀",
"May your smile light up every room ☀️",
"May you never forget how special you are 💗",
"And may this birthday begin something beautiful ✨",
"May you always have reasons to smile 🌷",
"May you never stop believing in yourself 💕",
"May happiness follow you everywhere 🌸",
"May this year be unforgettable 🎂"
];

const wishGrid = document.getElementById('wishGrid');

wishes.forEach((wish, i) => {
  const div = document.createElement('div');
  div.className = 'wish';
  div.textContent = `${i+1}. ${wish}`;
  wishGrid.appendChild(div);
});

document.getElementById('unlock').onclick = () => {
  document.querySelectorAll('.wish').forEach((el, i) => {
    setTimeout(() => el.classList.add('visible'), i * 35);
  });
};


// CONFETTI
function confetti(count = 100) {
  const host = document.getElementById('confetti');
  const colors = ['#f2a9c4','#d6c5f1','#f6d99b','#fff'];

  for(let i=0; i<count; i++) {
    const piece = document.createElement('i');
    piece.className = 'piece';
    piece.style.left = Math.random()*100 + '%';
    piece.style.background =
      colors[Math.floor(Math.random()*colors.length)];

    piece.style.animationDuration = (2+Math.random()*3)+'s';

    host.appendChild(piece);
    setTimeout(() => piece.remove(), 5000);
  }
}


// FLOATING HEARTS
function hearts(count = 10) {
  for(let i=0; i<count; i++) {
    const heart = document.createElement('span');

    heart.className = 'heart';
    heart.textContent = ['♡','♥','✧','🌸'][Math.floor(Math.random()*4)];
    heart.style.left = Math.random()*100 + '%';
    heart.style.fontSize = (15+Math.random()*20)+'px';

    document.body.appendChild(heart);

    setTimeout(() => heart.remove(), 6000);
  }
}


// BLOW OUT CANDLES
document.querySelectorAll('.candle').forEach(candle => {
  candle.onclick = () => {
    if(candle.classList.contains('out')) return;

    candle.classList.add('out');

    const remaining =
      document.querySelectorAll('.candle:not(.out)').length;

    if(remaining === 0) {
      document.getElementById('cakeMessage').textContent =
        'May all your wishes come true! 💗';

      confetti(180);
      hearts(25);
    } else {
      document.getElementById('cakeMessage').textContent =
        `${remaining} little candles left. Keep wishing! ✨`;
    }
  };
});


// PHOTO UPLOAD
document.getElementById('photos').onchange = event => {
  const gallery = document.getElementById('gallery');

  [...event.target.files].forEach(file => {
    if(!file.type.startsWith('image/')) return;

    const url = URL.createObjectURL(file);

    const card = document.createElement('div');
    card.className = 'polaroid';

    const photo = document.createElement('div');
    photo.className = 'photo';

    const img = document.createElement('img');
    img.src = url;
    img.alt = 'Friendship memory';

    photo.appendChild(img);

    const caption = document.createElement('label');
    caption.textContent = 'A favourite memory ♡';

    card.append(photo, caption);
    gallery.appendChild(card);
  });
};


// SECRET MESSAGE
document.getElementById('secretBtn').onclick = () => {
  document.getElementById('secretNote').classList.toggle('show');
  hearts(12);
};


// OPTIONAL MUSIC
const audio = document.getElementById('music');

document.getElementById('musicBtn').onclick = async () => {
  if(!audio.querySelector('source')) {
    document.getElementById('musicLabel').textContent =
      'Add your-music.mp3 first';
    return;
  }

  if(audio.paused) {
    try {
      await audio.play();
      document.getElementById('musicBtn').textContent = 'Ⅱ';
      document.getElementById('musicLabel').textContent = 'Music on';
    } catch(e) {
      document.getElementById('musicLabel').textContent =
        'Could not play music';
    }
  } else {
    audio.pause();
    document.getElementById('musicBtn').textContent = '♫';
    document.getElementById('musicLabel').textContent = 'Music off';
  }
};


// READING PROGRESS
window.addEventListener('scroll', () => {
  const max = document.documentElement.scrollHeight-innerHeight;
  const progress = max > 0 ? scrollY/max*100 : 0;

  document.getElementById('progress').style.width =
    progress+'%';
});

</script>
</body>
</html>
