<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Feliz Cumpleaños</title>

<style>
body{
    margin:0;
    overflow:hidden;
    background:black;
    font-family: Arial, sans-serif;
}

/* TEXTO */
.mensaje{
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%, -50%);
    font-size:80px;
    font-weight:bold;
    color:#fff;
    text-align:center;
    text-shadow:
        0 0 10px #fff,
        0 0 30px #00ffff,
        0 0 60px #ff00ff,
        0 0 100px #ff00ff;
    animation: latido 1s infinite;
}

@keyframes latido{
    0%{ transform:translate(-50%, -50%) scale(1);}
    50%{ transform:translate(-50%, -50%) scale(1.35);}
    100%{ transform:translate(-50%, -50%) scale(1);}
}

/* EXPLOSION */
.particula{
    position:absolute;
    width:10px;
    height:10px;
    border-radius:50%;
    animation: explotar 1.5s linear forwards;
}

@keyframes explotar{
    from{
        opacity:1;
        transform:translate(0,0) scale(1);
    }
    to{
        opacity:0;
        transform:translate(var(--x), var(--y)) scale(0.3);
    }
}

/* CONFETI */
.confeti{
    position:absolute;
    width:8px;
    height:14px;
    top:-10px;
    animation: caer linear infinite;
}

@keyframes caer{
    0%{ transform:translateY(0) rotate(0);}
    100%{ transform:translateY(130vh) rotate(900deg);}
}

/* GLOBOS (SUBEN) */
.globo{
    position:absolute;
    bottom:-120px;
    width:50px;
    height:70px;
    border-radius:50%;
    animation: subir linear infinite;
}

.globo::after{
    content:'';
    position:absolute;
    width:2px;
    height:40px;
    background:white;
    left:50%;
    top:70px;
}

@keyframes subir{
    0%{ transform:translateY(0);}
    100%{ transform:translateY(-140vh);}
}

/* OBJETOS (BAJAN) */
.obj{
    position:absolute;
    top:-100px;
    font-size:50px;
    animation: bajar linear infinite;
}

@keyframes bajar{
    0%{ transform:translateY(0) rotate(0);}
    100%{ transform:translateY(140vh) rotate(720deg);}


}


@keyframes bajar{
    0%{ transform:translateY(0) rotate(0);}
    100%{ transform:translateY(140vh) rotate(720deg);}
}

/* IMAGENES QUE CAEN */
.img-drop{
    position:absolute;
    top:-120px;
    width:90px;
    pointer-events:none;
    animation: caerImg linear infinite;
}
@keyframes caerImg{
    0%{ transform:translateY(0) scale(1);}
    100%{ transform:translateY(150vh) scale(1);}
}
</style>
</head>

<body>

<div class="mensaje">🎉 FELIZ CUMPLEAÑOS DELEGEI 🎉</div>

<script>

/* EXPLOSION ULTRA INTENSA */
function explosion(){
    for(let i=0;i<400;i++){ // MÁS partículas
        let p = document.createElement("div");
        p.className="particula";

        let x = (Math.random()-0.5)*2000 + "px"; // MÁS expansión
        let y = (Math.random()-0.5)*2000 + "px";

        p.style.setProperty('--x', x);
        p.style.setProperty('--y', y);
        p.style.left="50%";
        p.style.top="50%";
        p.style.background="hsl(" + Math.random()*360 + ",100%,60%)";

        document.body.appendChild(p);

        setTimeout(()=>p.remove(),1500);
    }
}

/* CONFETI MASIVO */
for(let i=0;i<200;i++){
    let c = document.createElement("div");
    c.className="confeti";
    c.style.left = Math.random()*100+"vw";
    c.style.background = "hsl(" + Math.random()*360 + ",100%,50%)";
    c.style.animationDuration = (2 + Math.random()*3)+"s";
    document.body.appendChild(c);
}

/* GLOBOS SUBIENDO */
for(let i=0;i<60;i++){
    let g = document.createElement("div");
    g.className="globo";
    g.style.left = Math.random()*100+"vw";
    g.style.background = "hsl(" + Math.random()*360 + ",70%,60%)";
    g.style.animationDuration = (4 + Math.random()*5)+"s";
    document.body.appendChild(g);
}

/* OBJETOS BAJANDO */
let emojis = ["🍺","🍻","🍾","🥂","🎂","🍰"];

for(let i=0;i<80;i++){
    let o = document.createElement("div");
    o.className="obj";
    o.innerHTML = emojis[Math.floor(Math.random()*emojis.length)];

    o.style.left = Math.random()*100+"vw";
    o.style.fontSize = (40 + Math.random()*40)+"px";
    o.style.animationDuration = (4 + Math.random()*6)+"s";

    document.body.appendChild(o);
}

/* EXPLOSIONES CONTINUAS MÁS RÁPIDAS */
explosion();
setInterval(explosion, 1500);



/* IMAGENES QUE CAEN (des.png y des2.png) */
let imgs = ["img/des.png", "img/des2.png"];

function crearImagenes(){
    for(let i=0;i<3;i++){ // 3-4 imágenes por ciclo
        let img = document.createElement("img");
        img.src = imgs[Math.floor(Math.random()*imgs.length)];
        img.className = "img-drop";

        img.style.left = Math.random()*100+"vw";
        img.style.width = (120 + Math.random()*100)+"px";
        img.style.animationDuration = (4 + Math.random()*4)+"s";

        document.body.appendChild(img);

        setTimeout(()=>img.remove(),8000);
    }
}

/* repetir cada cierto tiempo */
crearImagenes();
setInterval(crearImagenes, 2000);

</script>

</body>
</html>