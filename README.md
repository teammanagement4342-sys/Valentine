<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Valentine</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body{
margin:0;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
background:linear-gradient(135deg,#fbc2eb,#a6c1ee);
font-family:Arial,sans-serif;
overflow:hidden
}
.card{
background:#fff;
padding:40px;
border-radius:25px;
text-align:center;
width:90%;
max-width:360px;
box-shadow:0 20px 40px rgba(0,0,0,.15);
animation:pop .5s ease
}
@keyframes pop{from{transform:scale(.5);opacity:0}to{transform:scale(1);opacity:1}}
.emoji{font-size:60px;animation:float 2s infinite}
@keyframes float{50%{transform:translateY(-10px)}}
.buttons{position:relative;height:70px}
button{
padding:12px 30px;
border:none;
border-radius:30px;
font-size:16px;
cursor:pointer
}
#yes{background:#ff4d6d;color:#fff}
#no{position:absolute;background:#ddd}
.hint{font-size:12px;color:#777;margin-top:10px}
</style>
</head>

<body>
<div class="card">
<div class="emoji">🐻💖</div>
<h2>nirali will you be my valentine?</h2>

<div class="buttons">
<button id="yes">Yes</button>
<button id="no">No</button>
</div>

<div class="hint">"No" is too shy 😈</div>
</div>

<script>
const no=document.getElementById("no");
no.onmouseover=no.ontouchstart=()=>{no.style.left=Math.random()*200+"px";no.style.top=Math.random()*40+"px"};

document.getElementById("yes").onclick=()=>{
document.body.innerHTML="<h1 style='color:white;font-size:3rem'>YAY 💘🥰</h1>";
for(let i=0;i<120;i++){
let c=document.createElement("div");
c.style.cssText=`position:fixed;width:8px;height:8px;background:hsl(${Math.random()*360},100%,50%);
left:${Math.random()*innerWidth}px;top:-10px;border-radius:50%;
animation:fall 3s linear`;
document.body.appendChild(c);
setTimeout(()=>c.remove(),3000)
}
};

const s=document.createElement("style");
s.innerHTML="@keyframes fall{to{transform:translateY(100vh) rotate(360deg);opacity:0}}";
document.head.appendChild(s);
</script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Valentine</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body{
margin:0;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
background:linear-gradient(135deg,#fbc2eb,#a6c1ee);
font-family:Arial,sans-serif;
overflow:hidden
}
.card{
background:#fff;
padding:40px;
border-radius:25px;
text-align:center;
width:90%;
max-width:360px;
box-shadow:0 20px 40px rgba(0,0,0,.15);
animation:pop .5s ease
}
@keyframes pop{from{transform:scale(.5);opacity:0}to{transform:scale(1);opacity:1}}
.emoji{font-size:60px;animation:float 2s infinite}
@keyframes float{50%{transform:translateY(-10px)}}
.buttons{position:relative;height:70px}
button{
padding:12px 30px;
border:none;
border-radius:30px;
font-size:16px;
cursor:pointer
}
#yes{background:#ff4d6d;color:#fff}
#no{position:absolute;background:#ddd}
.hint{font-size:12px;color:#777;margin-top:10px}
</style>
</head>

<body>
<div class="card">
<div class="emoji">🐻💖</div>
<h2>nirali will you be my valentine?</h2>

<div class="buttons">
<button id="yes">Yes</button>
<button id="no">No</button>
</div>

<div class="hint">"No" is too shy 😈</div>
</div>

<script>
const no=document.getElementById("no");
no.onmouseover=no.ontouchstart=()=>{no.style.left=Math.random()*200+"px";no.style.top=Math.random()*40+"px"};

document.getElementById("yes").onclick=()=>{
document.body.innerHTML="<h1 style='color:white;font-size:3rem'>YAY 💘🥰</h1>";
for(let i=0;i<120;i++){
let c=document.createElement("div");
c.style.cssText=`position:fixed;width:8px;height:8px;background:hsl(${Math.random()*360},100%,50%);
left:${Math.random()*innerWidth}px;top:-10px;border-radius:50%;
animation:fall 3s linear`;
document.body.appendChild(c);
setTimeout(()=>c.remove(),3000)
}
};

const s=document.createElement("style");
s.innerHTML="@keyframes fall{to{transform:translateY(100vh) rotate(360deg);opacity:0}}";
document.head.appendChild(s);
</script>
</body>
</html>
