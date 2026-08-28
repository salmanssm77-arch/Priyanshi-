<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>For Priyanshi 🌸</title>

<style>

/* =====================================================
   RESET
===================================================== */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Georgia,"Times New Roman",serif;
    color:#613b4b;
    overflow-x:hidden;

    background:
        radial-gradient(circle at 10% 10%,#ffffff 0%,transparent 28%),
        radial-gradient(circle at 90% 20%,#ffe0eb 0%,transparent 30%),
        radial-gradient(circle at 50% 100%,#ffe8cc 0%,transparent 35%),
        linear-gradient(135deg,#fffafd,#ffedf4,#fff7ed);
}


/* =====================================================
   FLOATING PETALS
===================================================== */

#petals{
    position:fixed;
    inset:0;
    pointer-events:none;
    overflow:hidden;
    z-index:50;
}

.petal{
    position:absolute;
    top:-50px;
    animation:petalFall linear infinite;
    opacity:.55;
}

@keyframes petalFall{

    0%{
        transform:
            translateY(-60px)
            rotate(0deg);
    }

    100%{
        transform:
            translateY(110vh)
            rotate(420deg);
    }

}


/* =====================================================
   HERO
===================================================== */

.hero{

    min-height:100vh;

    position:relative;

    display:flex;
    align-items:center;
    justify-content:center;

    text-align:center;

    padding:40px 20px;

    overflow:hidden;

    background:
        radial-gradient(
            circle at 50% 40%,
            rgba(255,255,255,.95),
            transparent 33%
        );
}


.hero::before{

    content:"";

    position:absolute;

    width:650px;
    height:650px;

    border-radius:50%;

    background:
        radial-gradient(
            circle,
            rgba(255,166,198,.2),
            transparent 70%
        );

    animation:heroGlow 5s ease-in-out infinite;

}

@keyframes heroGlow{

    50%{
        transform:scale(1.12);
        opacity:.65;
    }

}


.hero-content{

    position:relative;
    z-index:2;

    max-width:900px;

}


.eyebrow{

    font-family:Arial,sans-serif;

    text-transform:uppercase;

    letter-spacing:6px;

    font-size:11px;

    color:#b46680;

    margin-bottom:28px;

    animation:fadeUp 1s ease;

}


.hero h1{

    font-size:
        clamp(65px,14vw,150px);

    line-height:.82;

    font-weight:normal;

    color:#a13e62;

    letter-spacing:-5px;

    margin-bottom:40px;

    text-shadow:
        0 12px 35px
        rgba(161,62,98,.12);

    animation:fadeUp 1.3s ease;

}


.hero h1 span{

    display:block;

    color:#d86f92;

    font-style:italic;

}


.hero p{

    max-width:650px;

    margin:auto;

    font-size:19px;

    line-height:2;

    color:#765061;

    animation:fadeUp 1.6s ease;

}


@keyframes fadeUp{

    from{
        opacity:0;
        transform:translateY(30px);
    }

    to{
        opacity:1;
        transform:translateY(0);
    }

}


.scroll{

    position:absolute;

    bottom:28px;

    left:50%;

    transform:translateX(-50%);

    font-family:Arial,sans-serif;

    font-size:10px;

    letter-spacing:4px;

    color:#a87688;

    animation:bounce 2s infinite;

}

@keyframes bounce{

    50%{
        transform:translate(-50%,8px);
    }

}


/* =====================================================
   GENERAL
===================================================== */

section{
    padding:120px 20px;
}

.inner{
    max-width:1050px;
    margin:auto;
}

.label{

    text-align:center;

    text-transform:uppercase;

    letter-spacing:5px;

    font-family:Arial,sans-serif;

    font-size:10px;

    color:#b76782;

    margin-bottom:18px;

}

.title{

    text-align:center;

    font-weight:normal;

    font-size:
        clamp(45px,8vw,85px);

    line-height:1;

    color:#9e3e60;

    margin-bottom:25px;

}

.description{

    max-width:680px;

    margin:0 auto 70px;

    text-align:center;

    font-size:18px;

    line-height:1.9;

    color:#795263;

}


/* =====================================================
   BRACELET / GIFT
===================================================== */

.gift{

    background:
        linear-gradient(
            180deg,
            #fff9fb,
            #fff0f5
        );

    min-height:100vh;
}


.gift-stage{

    height:480px;

    display:flex;

    justify-content:center;
    align-items:center;

    position:relative;

}


/* Bracelet */

.bracelet{

    width:310px;
    height:310px;

    position:relative;

    display:flex;

    justify-content:center;
    align-items:center;

    animation:
        braceletFloat 4s ease-in-out infinite;

}

@keyframes braceletFloat{

    50%{
        transform:
            translateY(-13px)
            rotate(2deg);
    }

}


.ring{

    position:absolute;

    width:285px;
    height:285px;

    border-radius:50%;

    border:
        13px solid transparent;

    border-top-color:#e6a04e;
    border-right-color:#e47b9b;
    border-bottom-color:#f0bd70;
    border-left-color:#c44d73;

    filter:
        drop-shadow(
            0 12px 20px
            rgba(181,72,105,.2)
        );

    transform:rotate(-25deg);

}


.ring::after{

    content:"";

    position:absolute;

    inset:-11px;

    border-radius:50%;

    border:
        2px dashed
        rgba(197,127,68,.35);

}


.center{

    width:155px;
    height:155px;

    border-radius:50%;

    display:flex;

    justify-content:center;
    align-items:center;

    position:relative;

    z-index:2;

    font-size:58px;

    color:white;

    background:

        radial-gradient(
            circle at 30% 25%,
            #fff9cf,
            #ffd1df 25%,
            #e27497 55%,
            #bd426a 100%
        );

    box-shadow:

        0 15px 45px
        rgba(189,66,106,.22),

        inset 0 0 25px
        rgba(255,255,255,.55);

}


.center::before{

    content:"✦";

    position:absolute;

    top:15px;
    left:20px;

    font-size:17px;

    opacity:.7;

}

.center::after{

    content:"✦";

    position:absolute;

    bottom:20px;
    right:18px;

    font-size:13px;

    opacity:.7;

}


.gift-caption{

    position:absolute;

    bottom:10px;

    width:100%;

    text-align:center;

    color:#a46c7e;

    font-style:italic;

    font-size:17px;

}


/* =====================================================
   LETTER
===================================================== */

.letter-section{

    background:

        radial-gradient(
            circle at 10% 30%,
            rgba(255,220,232,.7),
            transparent 25%
        ),

        #fffafc;

}


.letter{

    max-width:850px;

    margin:auto;

    padding:60px 55px;

    border-radius:35px;

    background:
        rgba(255,255,255,.8);

    border:
        1px solid
        rgba(173,78,110,.12);

    box-shadow:
        0 30px 80px
        rgba(135,56,83,.1);

    backdrop-filter:blur(10px);

}


.letter p{

    font-size:20px;

    line-height:2;

    color:#6e4657;

    margin-bottom:25px;

}


.highlight{

    color:#c24f76;

    font-weight:bold;

}


.signature{

    margin-top:40px;

    text-align:right;

    font-style:italic;

    color:#ae6980;

}


/* =====================================================
   PERSONAL DETAILS
===================================================== */

.details{

    background:
        linear-gradient(
            135deg,
            #fff5f8,
            #fff8ef
        );

}


.grid{

    display:grid;

    grid-template-columns:
        repeat(
            auto-fit,
            minmax(230px,1fr)
        );

    gap:24px;

}


.detail{

    min-height:300px;

    padding:35px 28px;

    border-radius:28px;

    background:
        rgba(255,255,255,.75);

    border:
        1px solid
        rgba(175,75,107,.1);

    box-shadow:
        0 15px 40px
        rgba(150,64,91,.07);

    transition:.35s;

}


.detail:hover{

    transform:
        translateY(-9px);

    box-shadow:
        0 25px 50px
        rgba(150,64,91,.13);

}


.icon{

    font-size:48px;

    margin-bottom:25px;

}


.detail h3{

    font-size:25px;

    color:#a14364;

    font-weight:normal;

    margin-bottom:15px;

}


.detail p{

    color:#795363;

    line-height:1.8;

}


/* =====================================================
   MEMORY SECTION
===================================================== */

.memories{

    background:#fff;

}


.memory{

    min-height:330px;

    padding:35px;

    border-radius:30px;

    display:flex;

    flex-direction:column;

    justify-content:flex-end;

    position:relative;

    overflow:hidden;

    background:
        linear-gradient(
            145deg,
            #ffe0eb,
            #fff0da
        );

    border:
        1px solid
        rgba(172,78,108,.1);

    box-shadow:
        0 15px 35px
        rgba(140,58,83,.08);

    transition:.35s;

}


.memory::before{

    content:"";

    position:absolute;

    width:180px;
    height:180px;

    border-radius:50%;

    background:
        rgba(255,255,255,.45);

    top:-80px;
    right:-50px;

}


.memory:hover{

    transform:
        scale(1.025)
        rotate(-.5deg);

}


.memory-icon{

    font-size:58px;

    margin-bottom:auto;

}


.memory h3{

    font-size:25px;

    color:#a04364;

    font-weight:normal;

    margin-bottom:12px;

}


.memory p{

    color:#765060;

    line-height:1.7;

}


/* =====================================================
   SURPRISE
===================================================== */

.surprise{

    min-height:100vh;

    display:flex;

    align-items:center;

    justify-content:center;

    text-align:center;

    background:

        radial-gradient(
            circle at center,
            #ffe4ee,
            #fff5ea 65%
        );

}


.surprise-content{

    max-width:850px;

}


.surprise h2{

    font-size:
        clamp(
            50px,
            10vw,
            105px
        );

    font-weight:normal;

    line-height:.9;

    color:#9e3d60;

    margin-bottom:35px;

}


.surprise h2 span{

    display:block;

    color:#d66f91;

    font-style:italic;

}


.surprise-description{

    font-size:19px;

    line-height:2;

    color:#765060;

}


button{

    margin-top:45px;

    padding:17px 35px;

    border:none;

    border-radius:999px;

    background:
        linear-gradient(
            135deg,
            #b8446c,
            #dc7899
        );

    color:white;

    font-family:Georgia,serif;

    font-size:17px;

    font-weight:bold;

    cursor:pointer;

    box-shadow:
        0 15px 35px
        rgba(180,65,105,.22);

    transition:.3s;

}


button:hover{

    transform:
        translateY(-4px)
        scale(1.03);

}


#secret{

    display:none;

    max-width:680px;

    margin:
        45px auto 0;

    padding:
        40px 30px;

    border-radius:28px;

    background:
        rgba(255,255,255,.76);

    border:
        1px solid
        rgba(175,75,107,.12);

    box-shadow:
        0 20px 50px
        rgba(130,55,80,.1);

    animation:
        reveal .8s ease;

}


#secret p{

    font-size:20px;

    line-height:2;

    color:#704657;

}


#secret strong{

    color:#b4426b;

}


@keyframes reveal{

    from{
        opacity:0;
        transform:
            translateY(25px)
            scale(.96);
    }

    to{
        opacity:1;
        transform:
            translateY(0)
            scale(1);
    }

}


/* =====================================================
   FINAL
===================================================== */

.final{

    min-height:90vh;

    display:flex;

    justify-content:center;

    align-items:center;

    text-align:center;

    background:
        linear-gradient(
            180deg,
            #fff4f8,
            #ffe7ef
        );

}


.final-content{

    max-width:850px;

}


.final-heart{

    font-size:75px;

    margin-bottom:30px;

    animation:
        heartbeat 1.7s infinite;

}


@keyframes heartbeat{

    50%{
        transform:scale(1.14);
    }

}


.final h2{

    font-size:
        clamp(
            48px,
            9vw,
            100px
        );

    font-weight:normal;

    color:#9b3d60;

    line-height:.95;

    margin-bottom:35px;

}


.final p{

    font-size:20px;

    line-height:2;

    color:#765160;

}


.final strong{

    color:#c24d74;

}


/* =====================================================
   FOOTER
===================================================== */

footer{

    padding:45px 20px;

    text-align:center;

    background:#8f3c59;

    color:#ffeaf1;

    font-family:Arial,sans-serif;

    font-size:11px;

    letter-spacing:3px;

}


/* =====================================================
   MOBILE
===================================================== */

@media(max-width:600px){

    section{
        padding:90px 18px;
    }

    .hero h1{
        letter-spacing:-3px;
    }

    .letter{
        padding:40px 25px;
    }

    .letter p{
        font-size:18px;
    }

    .bracelet{
        transform:scale(.82);
    }

    .gift-stage{
        height:420px;
    }

}

</style>

</head>


<body>


<div id="petals"></div>



<!-- =====================================================
     HERO
===================================================== -->

<section class="hero">

<div class="hero-content">

    <div class="eyebrow">
        A little Raksha Bandhan surprise
    </div>


    <h1>

        For

        <span>
            Priyanshi
        </span>

    </h1>


    <p>

        Today felt like the perfect excuse
        to remind one of my favorite people
        just how special she is.

        <br><br>

        So...

        I made you a little something. 🌸

    </p>

</div>


<div class="scroll">
    SCROLL DOWN ↓
</div>

</section>



<!-- =====================================================
     DIGITAL GIFT
===================================================== -->

<section class="gift">

<div class="inner">

    <div class="label">
        A little gift
    </div>


    <h2 class="title">
        Something For You
    </h2>


    <p class="description">

        A tiny reminder of a friendship
        that means a lot to me.

    </p>


    <div class="gift-stage">

        <div class="bracelet">

            <div class="ring"></div>

            <div class="center">
                ♡
            </div>

        </div>


        <div class="gift-caption">

            A little symbol for
            a friendship I really treasure. 💗

        </div>

    </div>

</div>

</section>



<!-- =====================================================
     PERSONAL LETTER
===================================================== -->

<section class="letter-section">

<div class="inner">

    <div class="label">
        A little note
    </div>


    <h2 class="title">
        Priyanshi, Read This
    </h2>


    <div class="letter">

        <p>
            Priyanshi,
        </p>


        <p>

            There are some people who have
            this effortless way of becoming
            important to you.

            You don't even notice it happening.

            One day they're just someone
            you talk to...

            and then suddenly,
            their messages are something
            you genuinely look forward to.

        </p>


        <p>

            And that's you.

        </p>


        <p>

            I really love all the little things
            you do.

            Like how you somehow always manage
            to find the <span class="highlight">
            perfect song for whatever situation
            I'm in.</span>

        </p>


        <p>

            If I mess something up,
            do something stupid,
            or end up in some completely
            ridiculous situation...

            somehow you have a song for it. 😭

            And the worst part is that
            it's always ridiculously accurate.

        </p>


        <p>

            And then there's the fact that you
            literally wake yourself up in the morning
            just to greet me before I get busy
            with college and can't talk to you much.

        </p>


        <p>

            You don't have to do that.

            That's exactly why it means so much.

            It's such a small thing,
            but knowing that you make that effort
            just to get a little time with me
            before my day starts...

            I genuinely appreciate it.

        </p>


        <p>

            Those are the things I notice.

            The little things.

            The random songs.
            The early mornings.
            The stupid conversations.
            The jokes.
            The tiny efforts.

        </p>


        <p>

            You might not think much of them,

            but they mean more to me
            than you probably realize.

        </p>


        <p>

            And I hope you know that
            <span class="highlight">
            you're genuinely special.</span>

            Not because of one big thing,

            but because of all those little
            pieces of you that make you...

            you.

        </p>


        <p>

            I'm really glad I got to know you,
            Priyanshi.

        </p>


        <div class="signature">

            — From someone who's
            really glad you're here. ❤️

        </div>

    </div>

</div>

</section>



<!-- =====================================================
     APPRECIATION
===================================================== -->

<section class="details">

<div class="inner">

    <div class="label">
        The little things
    </div>


    <h2 class="title">
        Things I Notice
    </h2>


    <p class="description">

        Because sometimes the smallest
        things say the most.

    </p>


    <div class="grid">


        <div class="detail">

            <div class="icon">
                🎵
            </div>

            <h3>
                Your Perfect Songs
            </h3>

            <p>

                Somehow every situation gets
                its own soundtrack when you're around.

                And somehow you always manage
                to find the perfect one.

            </p>

        </div>



        <div class="detail">

            <div class="icon">
                🌅
            </div>

            <h3>
                Your Morning Messages
            </h3>

            <p>

                You waking yourself up just to
                say good morning before college
                takes up my day...

                that's something I'll always
                appreciate.

            </p>

        </div>



        <div class="detail">

            <div class="icon">
                😂
            </div>

            <h3>
                Your Chaos
            </h3>

            <p>

                Somehow even the most ordinary
                conversation can turn completely
                ridiculous with you.

            </p>

        </div>



        <div class="detail">

            <div class="icon">
                🌷
            </div>

            <h3>
                Your Little Efforts
            </h3>

            <p>

                You probably don't realize
                how many little things you do
                that actually mean a lot.

            </p>

        </div>

    </div>

</div>

</section>



<!-- =====================================================
     MEMORIES
===================================================== -->

<section class="memories">

<div class="inner">

    <div class="label">
        Our little moments
    </div>


    <h2 class="title">
        Things Worth Keeping
    </h2>


    <p class="description">

        A few little spaces for the memories
        that belong to you two.

    </p>


    <div class="grid">


        <div class="memory">

            <div class="memory-icon">
                💬
            </div>

            <h3>
                The Random Talks
            </h3>

            <p>

                Those conversations that were
                supposed to be short and somehow
                turned into hours.

            </p>

        </div>



        <div class="memory">

            <div class="memory-icon">
                😭
            </div>

            <h3>
                The Absolutely Stupid Moments
            </h3>

            <p>

                The moments that made absolutely
                no sense but somehow became
                unforgettable.

            </p>

        </div>



        <div class="memory">

            <div class="memory-icon">
                🌸
            </div>

            <h3>
                The Little Things
            </h3>

            <p>

                Small messages,
                random songs,
                morning greetings,
                and everything in between.

            </p>

        </div>

    </div>

</div>

</section>



<!-- =====================================================
     SURPRISE
===================================================== -->

<section class="surprise">

<div class="surprise-content">

    <div class="label">
        One last thing
    </div>


    <h2>

        This one's

        <span>
            just for you.
        </span>

    </h2>


    <p class="surprise-description">

        You've made it this far.

        <br><br>

        So I saved one final little message
        for you.

    </p>


    <button onclick="openMessage()">

        Open Your Message 💌

    </button>


    <div id="secret">

        <p>

            Priyanshi,

            <br><br>

            Happy Raksha Bandhan. 🌷

            <br><br>

            I hope today reminds you
            of something you should already know:

            <br><br>

            <strong>
                You're incredibly special.
            </strong>

            <br><br>

            Never underestimate the little
            things you do or the way you make
            the people around you feel.

            <br><br>

            Keep being you.

            Keep being chaotic.

            Keep sending those suspiciously
            accurate songs. 😭

            And please keep waking up
            to say good morning.

            <br><br>

            Because those little things
            mean more than you know.

            <br><br>

            <strong>
                Happy Raksha Bandhan,
                Priyanshi. ❤️
            </strong>

        </p>

    </div>

</div>

</section>



<!-- =====================================================
     FINAL
===================================================== -->

<section class="final">

<div class="final-content">

    <div class="final-heart">
        💗
    </div>


    <h2>

        Happy Raksha
        <strong>Bandhan</strong>

    </h2>


    <p>

        To one of the most wonderful people
        I've had the chance to know.

        <br><br>

        I hope you have a beautiful day.

        <br><br>

        And I hope you always remember...

        <br><br>

        <strong>
            I'm really glad you're in my life,
            Priyanshi. 🌸
        </strong>

    </p>

</div>

</section>



<footer>

    MADE ESPECIALLY FOR PRIYANSHI
    • HAPPY RAKSHA BANDHAN 💗

</footer>



<script>

/* =====================================================
   FLOATING PETALS
===================================================== */

const petalBox =
    document.getElementById("petals");


const symbols = [
    "🌸",
    "🌷",
    "✿",
    "♡",
    "✦",
    "✨"
];


for(let i=0;i<40;i++){

    const petal =
        document.createElement("div");

    petal.className =
        "petal";

    petal.innerText =
        symbols[
            Math.floor(
                Math.random() *
                symbols.length
            )
        ];

    petal.style.left =
        Math.random()*100+"%";

    petal.style.fontSize =
        (10+Math.random()*17)+"px";

    petal.style.animationDuration =
        (7+Math.random()*10)+"s";

    petal.style.animationDelay =
        (-Math.random()*15)+"s";

    petalBox.appendChild(
        petal
    );

}


/* =====================================================
   SURPRISE MESSAGE
===================================================== */

function openMessage(){

    const secret =
        document.getElementById("secret");

    secret.style.display =
        "block";


    const symbols = [

        "💗",
        "💖",
        "🌸",
        "🌷",
        "✨",
        "♡",
        "🫶"

    ];


    for(let i=0;i<55;i++){

        const p =
            document.createElement("div");

        p.className =
            "petal";

        p.innerText =
            symbols[
                Math.floor(
                    Math.random() *
                    symbols.length
                )
            ];

        p.style.left =
            "50%";

        p.style.top =
            "50%";

        p.style.fontSize =
            (15+Math.random()*25)+"px";

        p.style.animation =
            "none";

        p.style.transition =
            "all 1.5s ease-out";

        document.body.appendChild(p);


        setTimeout(()=>{

            p.style.transform =

                `
                translate(
                    ${Math.random()*850-425}px,
                    ${Math.random()*650-325}px
                )
                rotate(360deg)
                `;

            p.style.opacity =
                "0";

        },50);


        setTimeout(()=>{

            p.remove();

        },1600);

    }

}

</script>


</body>
</html>
