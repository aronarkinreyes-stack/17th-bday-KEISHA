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

/* Background Glow */
.glow{
    position:absolute;
    width:500px;
    height:500px;
    border-radius:50%;
    background:rgba(255,255,255,.2);
    filter:blur(90px);
    animation:moveGlow 12s ease-in-out infinite alternate;
}

@keyframes moveGlow{
    from{transform:translate(-100px,-50px);}
    to{transform:translate(100px,80px);}
}

/* Flowers */
.flower{
    position:absolute;
    font-size:50px;
    opacity:.75;
    animation:float linear infinite;
    filter:drop-shadow(0 0 10px rgba(255,255,255,.8));
}

@keyframes float{
    from{
        transform:translateY(110vh) rotate(0deg);
    }
    to{
        transform:translateY(-150px) rotate(360deg);
    }
}

/* Card */
.card{
    width:90%;
    max-width:850px;
    text-align:center;

    background:rgba(255,255,255,.22);
    backdrop-filter:blur(22px);

    border:1px solid rgba(255,255,255,.5);
    border-radius:35px;

    padding:60px;

    box-shadow:
    0 0 50px rgba(255,105,180,.25),
    0 0 100px rgba(255,182,193,.15);

    position:relative;
    overflow:hidden;
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
    rgba(255,255,255,.35),
    transparent);

    animation:shine 8s infinite;
}

@keyframes shine{
    to{
        left:150%;
    }
}

.heart{
    font-size:3.5rem;
    margin-bottom:15px;

    filter:
    drop-shadow(0 0 15px #ff5aa9)
    drop-shadow(0 0 30px #ff5aa9);

    animation:pulse 1.5s infinite;
}

@keyframes pulse{
    50%{
        transform:scale(1.15);
    }
}
h1{
    font-size:5rem;
    margin-bottom:10px;
    letter-spacing:3px;

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
    font-size:1.8rem;
    color:#a61e61;
    font-weight:normal;
    margin-bottom:30px;
}

p{
    font-size:1.2rem;
    color:#6b3050;
    line-height:1.9;
    max-width:650px;
    margin:0 auto 40px;
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

    padding:18px 40px;
    border-radius:50px;

    font-size:1.1rem;
    font-weight:bold;

    box-shadow:
    0 0 20px rgba(255,45,146,.5);

    transition:.4s;
}

.button:hover{
    transform:translateY(-5px) scale(1.05);

    box-shadow:
    0 0 30px rgba(255,45,146,.8),
    0 0 60px rgba(255,45,146,.4);
}

.button:hover{
    transform:translateY(-3px);
}

.signature{
    margin-top:30px;
    color:#a61e61;
    font-style:italic;
    font-size:1rem;
}
</style>
</head>
<body>

<div class="glow"></div>

<div class="flower" style="left:5%;animation-duration:18s;">🌷</div>
<div class="flower" style="left:15%;animation-duration:14s;">🌸</div>
<div class="flower" style="left:28%;animation-duration:20s;">🌷</div>
<div class="flower" style="left:42%;animation-duration:16s;">🌺</div>
<div class="flower" style="left:58%;animation-duration:22s;">🌸</div>
<div class="flower" style="left:72%;animation-duration:15s;">🌷</div>
<div class="flower" style="left:86%;animation-duration:19s;">🌺</div>
<div class="flower" style="left:5%; animation-duration:14s;">🌷</div>

<div class="flower" style="left:15%; animation-duration:18s;">🌸</div>

<div class="flower" style="left:25%; animation-duration:12s;">🌷</div>

<div class="flower" style="left:35%; animation-duration:16s;">🌺</div>

<div class="flower" style="left:45%; animation-duration:20s;">🌷</div>

<div class="flower" style="left:55%; animation-duration:15s;">🌸</div>

<div class="flower" style="left:65%; animation-duration:17s;">🌷</div>

<div class="flower" style="left:75%; animation-duration:13s;">🌺</div>

<div class="flower" style="left:85%; animation-duration:19s;">🌷</div>

<div class="flower" style="left:95%; animation-duration:15s;">🌸</div>
<div class="flower" style="left:2%; animation-duration:12s;">🌷</div>
<div class="flower" style="left:4%; animation-duration:15s;">🌸</div>
<div class="flower" style="left:6%; animation-duration:18s;">🌺</div>
<div class="flower" style="left:8%; animation-duration:13s;">🌷</div>
<div class="flower" style="left:10%; animation-duration:16s;">🌸</div>
<div class="flower" style="left:12%; animation-duration:14s;">🌺</div>
<div class="flower" style="left:14%; animation-duration:19s;">🌷</div>
<div class="flower" style="left:16%; animation-duration:11s;">🌸</div>
<div class="flower" style="left:18%; animation-duration:17s;">🌺</div>
<div class="flower" style="left:20%; animation-duration:15s;">🌷</div>

<div class="flower" style="left:22%; animation-duration:13s;">🌸</div>
<div class="flower" style="left:24%; animation-duration:18s;">🌺</div>
<div class="flower" style="left:26%; animation-duration:12s;">🌷</div>
<div class="flower" style="left:28%; animation-duration:16s;">🌸</div>
<div class="flower" style="left:30%; animation-duration:20s;">🌺</div>
<div class="flower" style="left:32%; animation-duration:14s;">🌷</div>
<div class="flower" style="left:34%; animation-duration:17s;">🌸</div>
<div class="flower" style="left:36%; animation-duration:13s;">🌺</div>
<div class="flower" style="left:38%; animation-duration:19s;">🌷</div>
<div class="flower" style="left:40%; animation-duration:15s;">🌸</div>

<div class="flower" style="left:42%; animation-duration:12s;">🌺</div>
<div class="flower" style="left:44%; animation-duration:18s;">🌷</div>
<div class="flower" style="left:46%; animation-duration:16s;">🌸</div>
<div class="flower" style="left:48%; animation-duration:14s;">🌺</div>
<div class="flower" style="left:50%; animation-duration:20s;">🌷</div>
<div class="flower" style="left:52%; animation-duration:13s;">🌸</div>
<div class="flower" style="left:54%; animation-duration:17s;">🌺</div>
<div class="flower" style="left:56%; animation-duration:11s;">🌷</div>
<div class="flower" style="left:58%; animation-duration:15s;">🌸</div>
<div class="flower" style="left:60%; animation-duration:19s;">🌺</div>

<div class="flower" style="left:62%; animation-duration:14s;">🌷</div>
<div class="flower" style="left:64%; animation-duration:18s;">🌸</div>
<div class="flower" style="left:66%; animation-duration:12s;">🌺</div>
<div class="flower" style="left:68%; animation-duration:16s;">🌷</div>
<div class="flower" style="left:70%; animation-duration:13s;">🌸</div>
<div class="flower" style="left:72%; animation-duration:20s;">🌺</div>
<div class="flower" style="left:76%; animation-duration:15s;">🌷</div>
<div class="flower" style="left:82%; animation-duration:17s;">🌸</div>
<div class="flower" style="left:88%; animation-duration:14s;">🌺</div>
<div class="flower" style="left:94%; animation-duration:19s;">🌷</div>


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
