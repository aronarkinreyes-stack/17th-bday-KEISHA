<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Keisha</title>

<style>
body::after{
    content:"";
    position:fixed;
    inset:0;
    pointer-events:none;
    background:
    radial-gradient(
        circle,
        transparent 35%,
        rgba(255,182,217,.15) 60%,
        rgba(120,20,80,.45) 100%
    );
}
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Georgia, serif;
}

body{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    overflow:hidden;
    position:relative;

    background:
    radial-gradient(circle at top left,#ffd6ea,transparent 35%),
    radial-gradient(circle at bottom right,#ffc3df,transparent 35%),
    linear-gradient(135deg,#ffb6d9,#ffe2ef,#fff5fa);
}

/* Background Glow Optimized */
.glow{
    position:absolute;
    width:400px;
    height:400px;
    border-radius:50%;
    background:rgba(255,255,255,.25);
    filter:blur(60px); /* Reduced blur radius for performance */
    animation:moveGlow 12s ease-in-out infinite alternate;
    will-change: transform; /* Signals GPU acceleration */
}

@keyframes moveGlow{
    from{transform:translate(-50px,-30px);}
    to{transform:translate(50px,50px);}
}

/* Flowers Optimized */
.flower{
    position:absolute;
    font-size:42px;
    opacity:.8;
    animation:float linear infinite;
    text-shadow: 0 0 10px rgba(255,255,255,0.6); /* Swapped from filter: drop-shadow for speed */
    will-change: transform;
}

@keyframes float{
    from{
        transform:translateY(105vh) rotate(0deg);
    }
    to{
        transform:translateY(-120px) rotate(360deg);
    }
}

/* Card Optimized */
.card{
    width:90%;
    max-width:650px;
    text-align:center;

    /* Slightly more opaque background handles lower blur perfectly */
    background:rgba(255,255,255,.4); 
    backdrop-filter:blur(10px); /* Lowered from 22px to make it smooth on mobile */
    -webkit-backdrop-filter:blur(10px);

    border:1px solid rgba(255,255,255,.6);
    border-radius:30px;
    padding:40px 30px;

    box-shadow:
    0 15px 35px rgba(255,105,180,.15);
    position:relative;
    overflow:hidden;
    z-index: 2;
}

.card::before{
    content:"";
    position:absolute;
    top:0;
    left:-120%;
    width:60%;
    height:100%;
    background:
    linear-gradient(
    90deg,
    transparent,
    rgba(255,255,255,.25),
    transparent);

    animation:shine 7s infinite;
}

@keyframes shine{
    to{
        left:150%;
    }
}

.heart{
    font-size:3rem;
    margin-bottom:15px;
    filter: drop-shadow(0 0 10px #ff5aa9);
    animation:pulse 1.5s infinite;
}

@keyframes pulse{
    50%{
        transform:scale(1.1);
    }
}
h1{
    font-size:3.5rem;
    margin-bottom:10px;
    letter-spacing:2px;

    background:
    linear-gradient(
    90deg,
    #ff2d92,
    #ff75bd,
    #ff2d92);

    background-size:300% 300%;
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
    animation:titleGlow 6s linear infinite;
}

@keyframes titleGlow{
    0%{background-position:0%;}
    100%{background-position:300%;}
}

h2{
    font-size:1.5rem;
    color:#a61e61;
    font-weight:normal;
    margin-bottom:25px;
}

p{
    font-size:1.1rem;
    color:#6b3050;
    line-height:1.7;
    max-width:550px;
    margin:0 auto 30px;
}

.button{
    display:inline-block;
    text-decoration:none;
    color:white;

    background:
    linear-gradient(
    135deg,
    #ff5aa9,
    #ff2d92);

    padding:15px 35px;
    border-radius:50px;
    font-size:1.05rem;
    font-weight:bold;
    box-shadow:0 8px 20px rgba(255,45,146,.3);
    transition:.3s ease;
}

.button:hover{
    transform:translateY(-3px);
    box-shadow:0 12px 25px rgba(255,45,146,.5);
}

.signature{
    margin-top:25px;
    color:#a61e61;
    font-style:italic;
    font-size:0.95rem;
}
</style>
</head>
<body>

<div class="glow"></div>

<div class="flower" style="left:5%;  animation-duration:15s; animation-delay:0s;">🌷</div>
<div class="flower" style="left:15%; animation-duration:12s; animation-delay:3s;">🌸</div>
<div class="flower" style="left:25%; animation-duration:18s; animation-delay:1s;">🌷</div>
<div class="flower" style="left:38%; animation-duration:14s; animation-delay:5s;">🌺</div>
<div class="flower" style="left:50%; animation-duration:16s; animation-delay:2s;">🌸</div>
<div class="flower" style="left:63%; animation-duration:13s; animation-delay:4s;">🌷</div>
<div class="flower" style="left:75%; animation-duration:17s; animation-delay:1s;">🌺</div>
<div class="flower" style="left:88%; animation-duration:15s; animation-delay:6s;">🌸</div>
<div class="flower" style="left:95%; animation-duration:11s; animation-delay:2s;">🌷</div>

<div class="card">
    <div class="heart">💖</div>
    <h1>Keisha</h1>
    <h2>My Darling</h2>
    <p>
        Every flower drifting across this page reminds me of you.
        Your smile brightens ordinary days, your kindness brings warmth,
        and every moment shared with you becomes a memory worth keeping.
    </p>

    <a class="button"
       href="https://drive.google.com/drive/u/0/folders/1bp173NV8xT_ntRlYoSc7tfArjFQ7Xmrb"
       target="_blank">
       Open Your Surprise
    </a>

    <div class="signature">
        Made with love, for Keisha.
    </div>
</div>

</body>
</html>
