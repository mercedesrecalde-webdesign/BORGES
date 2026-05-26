<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>El Jardín de Senderos que se Bifurcan — Archivo Onírico</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant:ital,wght@0,400;0,500;0,600;1,400;1,500&family=EB+Garamond:ital,wght@0,400;0,500;1,400&family=Cardo:ital@0;1&display=swap" rel="stylesheet">
<style>
  :root{
    --ink:#0d0d0f;          /* tinta casi negra */
    --paper:#e8e4da;        /* papel viejo */
    --paper-bright:#f4f1ea;
    --paper-dim:#b8b2a4;
    --paper-faint:#7a766c;
    --shadow:#1a1a1d;
    --line:#3a3833;
    --accent:#9b9388;       /* gris cálido */
    --glow:rgba(232,228,218,.5);
  }
  *{margin:0;padding:0;box-sizing:border-box}
  html,body{height:100%}
  body{
    background:var(--ink);
    color:var(--paper);
    font-family:'EB Garamond',Georgia,serif;
    font-weight:400;
    line-height:1.8;
    overflow-x:hidden;
    min-height:100vh;
    position:relative;
    cursor:none;
  }
  /* grano de grabado / aguafuerte */
  body::after{
    content:"";position:fixed;inset:0;pointer-events:none;z-index:9000;opacity:.07;mix-blend-mode:overlay;
    background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='180' height='180'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='4'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
  }
  body::before{
    content:"";position:fixed;inset:0;pointer-events:none;z-index:8000;
    background:radial-gradient(130% 120% at 50% 40%, transparent 50%, rgba(0,0,0,.6) 100%);
  }

  /* ===== cursor de tinta personalizado ===== */
  #cursor{position:fixed;width:14px;height:14px;border-radius:50%;background:var(--paper);
    pointer-events:none;z-index:9999;mix-blend-mode:difference;transform:translate(-50%,-50%);
    transition:width .25s, height .25s}
  #cursor.big{width:46px;height:46px;background:var(--paper-bright)}
  .ink-trail{position:fixed;border-radius:50%;background:var(--paper);pointer-events:none;z-index:9998;
    mix-blend-mode:difference;transform:translate(-50%,-50%);animation:dissolve 1.1s ease forwards}
  @keyframes dissolve{0%{opacity:.5}100%{opacity:0;transform:translate(-50%,-50%) scale(.2)}}

  .stage{max-width:820px;margin:0 auto;padding:0 28px;position:relative;z-index:10}
  .hidden{display:none!important}

  /* ====== PORTADA ====== */
  #title{min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:40px 24px;position:relative;overflow:hidden}
  /* fondo daliniano real */
  .horizon{position:absolute;inset:0;z-index:0;overflow:hidden;
    background-image:url("images/portada.png");background-size:cover;background-position:center;
    filter:grayscale(1) contrast(1.08) brightness(.5);transform:scale(1.06);animation:bgFloat 38s ease-in-out infinite alternate}
  @keyframes bgFloat{from{transform:scale(1.06) translateY(0)}to{transform:scale(1.12) translateY(-12px)}}
  .horizon::after{content:"";position:absolute;inset:0;background:radial-gradient(120% 110% at 50% 35%, rgba(13,13,15,.25) 0%, rgba(13,13,15,.72) 70%, var(--ink) 100%)}

  /* reloj derretido SVG */
  .melt-clock{position:absolute;z-index:1;opacity:.5;filter:drop-shadow(0 20px 30px rgba(0,0,0,.7));transition:transform .4s ease}
  #clock1{width:130px;top:20%;left:12%;transform:rotate(-8deg)}
  #clock2{width:90px;top:30%;right:14%;transform:rotate(6deg)}

  .title-kicker{font-family:'Cardo',serif;font-style:italic;font-size:1rem;letter-spacing:.5em;text-transform:uppercase;color:var(--paper-faint);z-index:3;opacity:0;animation:fadeUp 1.6s .3s forwards}
  h1.title-main{font-family:'Cormorant',serif;font-weight:500;font-size:clamp(2.4rem,7vw,5rem);line-height:1.02;letter-spacing:.01em;margin:.2em 0;z-index:3;opacity:0;animation:fadeUp 1.8s .55s forwards;text-shadow:0 2px 40px rgba(0,0,0,.8)}
  h1.title-main em{display:block;font-style:italic;font-size:.5em;color:var(--paper-dim);letter-spacing:.18em;margin-top:.4em;font-weight:400}
  .title-author{font-family:'Cardo',serif;font-size:1.05rem;letter-spacing:.22em;color:var(--paper-faint);margin-top:1.4em;z-index:3;opacity:0;animation:fadeUp 1.8s .85s forwards}
  @keyframes fadeUp{from{opacity:0;transform:translateY(26px)}to{opacity:1;transform:translateY(0)}}

  .enter-wrap{margin-top:2.8em;z-index:3;opacity:0;animation:fadeUp 1.8s 1.2s forwards;display:flex;flex-direction:column;align-items:center;gap:16px}
  .enter-wrap small{font-family:'Cardo',serif;font-size:.72rem;letter-spacing:.3em;text-transform:uppercase;color:var(--paper-faint);max-width:380px;line-height:2}

  /* ====== BOTONES (grabado) ====== */
  .btn{font-family:'Cormorant',serif;background:transparent;color:var(--paper);
    border:1px solid var(--paper-faint);padding:14px 38px;font-size:1.2rem;letter-spacing:.18em;
    text-transform:uppercase;cursor:none;position:relative;overflow:hidden;transition:.5s}
  .btn::before{content:"";position:absolute;inset:0;background:var(--paper);transform:translateY(101%);transition:transform .5s cubic-bezier(.6,0,.2,1);z-index:-1}
  .btn:hover:not(:disabled){color:var(--ink);border-color:var(--paper)}
  .btn:hover:not(:disabled)::before{transform:translateY(0)}
  .btn:disabled{opacity:.3;cursor:none}
  .btn.ghost{font-size:.95rem;padding:11px 26px;border-color:var(--line)}

  /* ====== LECTURA ====== */
  #reading{display:none;padding:90px 0 80px;animation:meltIn 1.1s ease}
  @keyframes meltIn{from{opacity:0;filter:blur(8px)}to{opacity:1;filter:blur(0)}}
  .read-chip{font-family:'Cardo',serif;font-style:italic;letter-spacing:.42em;text-transform:uppercase;color:var(--accent);font-size:.82rem;text-align:center;display:block;margin-bottom:10px}
  .read-title{font-family:'Cormorant',serif;font-weight:500;font-size:clamp(1.9rem,5.5vw,3.2rem);text-align:center;line-height:1.05;margin-bottom:34px}
  .read-body p{font-size:1.22rem;margin-bottom:1.4em;color:#d8d4c8}
  .read-body p.lead:first-letter{font-family:'Cormorant',serif;float:left;font-size:4.6rem;line-height:.7;padding:.05em .14em 0 0;color:var(--paper-bright);font-weight:600}
  .read-hero{display:block;width:100%;max-width:680px;margin:0 auto 34px;border:1px solid var(--line);border-radius:4px;
    filter:grayscale(1) contrast(1.06) brightness(.92);box-shadow:0 22px 60px rgba(0,0,0,.7)}
  .mission-hero{display:block;width:100%;max-width:600px;margin:0 auto 26px;border:1px solid var(--line);border-radius:4px;
    filter:grayscale(1) contrast(1.06) brightness(.9);box-shadow:0 18px 50px rgba(0,0,0,.7)}
  .read-body em{font-style:italic;color:var(--paper)}
  .frag{display:block;border-left:2px solid var(--line);padding:6px 0 6px 22px;margin:26px 0;font-family:'Cardo',serif;font-style:italic;font-size:1.3rem;color:var(--paper);line-height:1.6}
  .frag cite{display:block;font-style:normal;font-size:.78rem;letter-spacing:.2em;text-transform:uppercase;color:var(--paper-faint);margin-top:8px}

  .read-link{text-align:center;margin:40px 0;padding:26px;border:1px dashed var(--line);border-radius:4px}
  .read-link p{font-family:'Cardo',serif;font-style:italic;color:var(--paper-dim);margin-bottom:14px}

  .divider{display:flex;align-items:center;gap:18px;margin:48px 0;color:var(--line)}
  .divider::before,.divider::after{content:"";flex:1;height:1px;background:var(--line)}
  .divider span{font-family:'Cardo',serif;font-size:1.3rem}

  #readGate{position:sticky;bottom:0;background:linear-gradient(0deg,var(--ink) 35%,transparent);padding:34px 0 22px;text-align:center;margin-top:10px}
  #readGate .note{display:block;font-family:'Cardo',serif;color:var(--paper-faint);font-size:.8rem;letter-spacing:.22em;text-transform:uppercase;margin-bottom:16px}

  @media(max-width:560px){
    body{cursor:auto}#cursor,.ink-trail{display:none}
    .read-body p{font-size:1.12rem}.btn{cursor:pointer}
    .melt-clock{opacity:.3}
    .voice-map{height:auto}.drawers{grid-template-columns:1fr}
    #topbar{cursor:auto}
  }

  /* ===== TOP BAR ===== */
  #topbar{position:fixed;top:0;left:0;right:0;z-index:600;display:flex;align-items:center;gap:18px;
    padding:12px 24px;background:linear-gradient(180deg,rgba(13,13,15,.96),rgba(13,13,15,0));backdrop-filter:blur(3px)}
  .tb-item{display:flex;flex-direction:column;gap:1px;font-family:'Cardo',serif}
  .tb-label{font-size:.58rem;letter-spacing:.3em;text-transform:uppercase;color:var(--paper-faint)}
  .tb-val{font-size:1.05rem;letter-spacing:.06em;color:var(--paper)}
  #timer{color:var(--accent)}
  .tb-spacer{flex:1}
  .tb-btn{font-family:'Cardo',serif;background:none;border:1px solid var(--line);color:var(--paper-dim);
    padding:7px 14px;font-size:.82rem;letter-spacing:.12em;cursor:none;transition:.3s}
  .tb-btn:hover{border-color:var(--paper);color:var(--paper)}
  .sound-btn{width:36px;height:36px;border-radius:50%;display:grid;place-items:center;padding:0}

  /* ===== HUB de misiones ===== */
  #game{padding:96px 0 90px;animation:meltIn 1s ease}
  .missions{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px}
  .mission-card{position:relative;border:1px solid var(--line);background:linear-gradient(180deg,#141416,#0e0e10);
    padding:28px 22px;cursor:none;transition:.45s;overflow:hidden;min-height:200px;display:flex;flex-direction:column}
  .mission-card:hover:not(.locked){border-color:var(--paper-dim);transform:translateY(-5px)}
  .mission-card.locked{opacity:.4;cursor:none}
  .mission-card.done{border-color:var(--accent)}
  .mission-card .mnum{font-family:'Cormorant',serif;font-size:2.6rem;color:var(--paper-faint);line-height:1}
  .mission-card.done .mnum{color:var(--accent)}
  .mission-card .mname{font-family:'Cormorant',serif;font-size:1.5rem;color:var(--paper);margin:8px 0 6px;line-height:1.1}
  .mission-card .mdesc{font-size:.96rem;color:var(--paper-dim);font-style:italic;flex:1}
  .mission-card .mskill{font-family:'Cardo',serif;font-size:.66rem;letter-spacing:.16em;text-transform:uppercase;color:var(--accent);margin-top:14px;padding-top:12px;border-top:1px solid var(--line)}
  .mission-card .mlock{position:absolute;top:14px;right:16px;font-size:1rem;opacity:.6}

  /* ===== misión: preguntas / pasos ===== */
  #missionView{animation:meltIn .8s ease}
  .step{border:1px solid var(--line);background:rgba(20,20,22,.6);padding:24px 24px;margin-bottom:18px;transition:.4s}
  .step.solved{border-color:var(--accent);opacity:.92}
  .step .q{font-size:1.16rem;color:#d8d4c8;margin-bottom:6px;display:flex;gap:10px}
  .step .q .qn{font-family:'Cormorant',serif;color:var(--accent);font-style:italic}
  .step .kind{font-family:'Cardo',serif;font-size:.64rem;letter-spacing:.18em;text-transform:uppercase;color:var(--paper-faint);margin:0 0 16px 28px}
  .opt{display:block;width:100%;text-align:left;font-family:'EB Garamond',serif;background:#0e0e10;border:1px solid var(--line);
    color:var(--paper-dim);padding:12px 18px;margin-bottom:9px;cursor:none;font-size:1.04rem;transition:.25s}
  .opt:hover:not(:disabled){border-color:var(--paper-dim);color:var(--paper)}
  .opt.correct{border-color:var(--accent);background:rgba(155,147,136,.14);color:var(--paper-bright)}
  .opt.wrong{border-color:#6b3a3a;background:rgba(107,58,58,.16);color:#d8b8b8}
  .opt:disabled{cursor:none}
  .fb{margin-top:12px;font-style:italic;color:var(--accent);font-size:1rem;display:none;font-family:'Cardo',serif}
  .fb.show{display:block;animation:meltIn .5s}
  .mission-foot{display:flex;justify-content:space-between;align-items:center;margin-top:30px;gap:14px;flex-wrap:wrap}

  /* ===== Misión 2: cajones + mapa de voces ===== */
  .voices-intro{color:var(--paper-dim);font-style:italic;text-align:center;margin-bottom:26px}
  .drawers{display:grid;grid-template-columns:repeat(2,1fr);gap:16px;margin-bottom:30px}
  .drawer{border:1px solid var(--line);background:linear-gradient(180deg,#141416,#0d0d0f);position:relative;cursor:none;transition:.4s;overflow:hidden}
  .drawer .handle{height:48px;display:flex;align-items:center;justify-content:center;gap:10px;border-bottom:1px solid var(--line);font-family:'Cormorant',serif;font-size:1.2rem;color:var(--paper-dim);transition:.3s}
  .drawer .handle::before{content:"▭";font-size:.8rem;color:var(--paper-faint)}
  .drawer:hover .handle{color:var(--paper);letter-spacing:.04em}
  .drawer .content{max-height:0;opacity:0;transition:max-height .5s ease, opacity .5s ease, padding .5s ease;padding:0 20px;font-size:1rem;color:#d4d0c4}
  .drawer.open{border-color:var(--accent)}
  .drawer.open .content{max-height:320px;opacity:1;padding:18px 20px}
  .drawer.open .handle{color:var(--accent)}
  .drawer .content .role{font-family:'Cardo',serif;font-size:.66rem;letter-spacing:.18em;text-transform:uppercase;color:var(--accent);display:block;margin-bottom:8px}
  .drawer .content .frag-mini{font-family:'Cardo',serif;font-style:italic;color:var(--paper);margin-top:10px;font-size:.95rem;border-left:2px solid var(--line);padding-left:12px}

  .voice-map{border:1px solid var(--line);background:rgba(10,10,12,.5);margin-bottom:24px;border-radius:4px}
  .voice-map svg{width:100%;height:auto;display:block}
  .map-hint{text-align:center;font-family:'Cardo',serif;font-style:italic;color:var(--paper-faint);font-size:.9rem;margin-bottom:8px}

  /* ===== Misión 3: bifurcación ===== */
  .fork-intro{color:var(--paper-dim);font-style:italic;text-align:center;margin-bottom:28px}
  .paths{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:18px;margin-bottom:24px}
  .path{border:1px solid var(--line);background:linear-gradient(180deg,#141416,#0d0d0f);padding:22px 20px;cursor:none;transition:.4s;text-align:center}
  .path:hover{border-color:var(--paper-dim);transform:translateY(-4px)}
  .path.chosen{border-color:var(--accent);background:rgba(155,147,136,.1)}
  .path .pname{font-family:'Cormorant',serif;font-size:1.4rem;color:var(--paper);margin-bottom:8px}
  .path .pdesc{font-size:.94rem;color:var(--paper-dim);font-style:italic}
  .path-result{border-left:2px solid var(--accent);background:rgba(155,147,136,.07);padding:20px 22px;font-family:'Cardo',serif;font-style:italic;font-size:1.12rem;color:#e2ded2;display:none;line-height:1.7}
  .path-result.show{display:block;animation:meltIn .6s}

  /* ===== final ===== */
  #ending{animation:meltIn 1.1s ease;text-align:center;padding-top:20px}
  .diploma{border:1px solid var(--accent);background:linear-gradient(180deg,rgba(20,20,22,.7),rgba(13,13,15,.7));padding:44px 34px;margin:24px 0;position:relative}
  .diploma .seal{font-family:'Cardo',serif;font-style:italic;letter-spacing:.4em;text-transform:uppercase;color:var(--accent);font-size:.8rem}
  .diploma h3{font-family:'Cormorant',serif;font-weight:500;font-size:2.4rem;margin:14px 0;line-height:1.1}
  .stat-row{display:flex;justify-content:center;gap:46px;flex-wrap:wrap;margin:24px 0}
  .stat .sv{font-family:'Cormorant',serif;font-size:2.4rem;color:var(--paper)}
  .stat .sl{font-family:'Cardo',serif;font-size:.66rem;letter-spacing:.2em;text-transform:uppercase;color:var(--paper-faint)}
  .center{text-align:center}
  .credits{font-family:'Cardo',serif;color:var(--paper-faint);font-size:.8rem;letter-spacing:.08em;margin-top:40px;line-height:2}
  .ending-hero{display:block;width:100%;max-width:760px;margin:0 auto 30px;border:1px solid var(--line);border-radius:4px;
    filter:grayscale(1) contrast(1.06) brightness(.95);box-shadow:0 24px 70px rgba(0,0,0,.8)}
  .synthesis{border:1px solid var(--line);background:linear-gradient(180deg,rgba(20,20,22,.7),rgba(13,13,15,.7));padding:34px 30px;margin:30px 0;text-align:left;border-radius:4px}
  .synthesis h4{font-family:'Cormorant',serif;font-weight:500;font-size:1.8rem;color:var(--paper);margin-bottom:8px;text-align:center}
  .syn-intro{color:var(--paper-dim);font-style:italic;text-align:center;margin-bottom:24px;font-size:1.02rem}
  .syn-list{list-style:none;counter-reset:syn;margin-bottom:24px}
  .syn-list li{counter-increment:syn;position:relative;padding:14px 0 14px 48px;border-bottom:1px solid rgba(58,56,51,.5);color:#d4d0c4;font-size:1.06rem;line-height:1.6}
  .syn-list li:last-child{border-bottom:none}
  .syn-list li::before{content:counter(syn);position:absolute;left:0;top:12px;width:30px;height:30px;border:1px solid var(--accent);border-radius:50%;display:grid;place-items:center;font-family:'Cormorant',serif;color:var(--accent);font-size:1.1rem}
  .syn-list li b{color:var(--paper);font-weight:500}
  .synthesis textarea{width:100%;background:#0c0c0e;border:1px solid var(--line);color:var(--paper);border-radius:4px;padding:16px;font-family:'EB Garamond',serif;font-size:1.05rem;line-height:1.7;resize:vertical;min-height:180px}
  .synthesis textarea:focus{outline:none;border-color:var(--accent)}
  .syn-confirm{text-align:center;margin-top:14px;font-family:'Cardo',serif;font-style:italic;color:var(--accent);display:none}
  .syn-confirm.show{display:block;animation:meltIn .5s}

  @media(max-width:560px){
    .drawers{grid-template-columns:1fr}.melt-clock{opacity:.3}
  }
</style>
</head>
<body>

<div id="cursor"></div>

<!-- ====== PORTADA ====== -->
<section id="title">
  <div class="horizon"></div>

  <!-- relojes derretidos -->
  <span class="title-kicker">Archivo Onírico · Detective Textual</span>
  <h1 class="title-main">El Jardín de Senderos<br>que se Bifurcan<em>una experiencia de lectura laberíntica</em></h1>
  <p class="title-author">a partir del cuento de Jorge Luis Borges · 1941</p>

  <div class="enter-wrap">
    <button class="btn" onclick="startReading()">Entrar al archivo</button>
    <small>Necesitarás el cuento original a tu lado. Se recomienda usar audífonos.</small>
  </div>
</section>

<!-- ====== LECTURA ====== -->
<main id="reading" class="stage">
  <span class="read-chip">Antes de descender al laberinto</span>
  <h2 class="read-title">El umbral del archivo</h2>
  <img class="read-hero" src="images/umbral.png" alt="" onerror="this.remove()">
  <div class="read-body" id="readBody"></div>

  <div class="read-link">
    <p>El texto completo de Borges está protegido por derechos de autor.<br>Conseguilo a través de tu cátedra y tenelo abierto mientras jugás.</p>
    <a id="cuentoLink" class="btn ghost" href="#" onclick="return abrirCuento(event)">Leer el cuento original</a>
  </div>

  <div id="readGate">
    <span class="note">Cuando hayas leído el cuento, desciende</span>
    <button class="btn" id="toGame" onclick="enterGame()">Descender al laberinto →</button>
  </div>
</main>

<!-- ====== TOP BAR del juego ====== -->
<div id="topbar" class="hidden">
  <div class="tb-item"><span class="tb-label">Reloj</span><span class="tb-val" id="timer">00:00</span></div>
  <div class="tb-item"><span class="tb-label">Misiones</span><span class="tb-val"><span id="missionNum">0</span>/3</span></div>
  <div class="tb-spacer"></div>
  <button class="tb-btn" onclick="abrirCuento(event)">Cuento</button>
  <button class="tb-btn sound-btn" id="soundBtn" title="Sonido">♪</button>
</div>

<!-- ====== JUEGO ====== -->
<main id="game" class="stage" style="display:none">

  <!-- selector de misiones -->
  <section id="missionHub">
    <span class="read-chip">El archivo onírico · tres descensos</span>
    <h2 class="read-title">Las tres misiones</h2>
    <p style="text-align:center;color:var(--paper-dim);font-style:italic;max-width:560px;margin:0 auto 40px">Cada misión abre una capa más profunda del laberinto. Resolvé una para destrabar la siguiente.</p>
    <div class="missions" id="missionsGrid"></div>
    <div class="center" id="finalReady" style="display:none;margin-top:40px">
      <p class="frag" style="text-align:center;border:none">Has recorrido los tres senderos…</p>
      <button class="btn" onclick="showEnding()">Salir del laberinto</button>
    </div>
  </section>

  <!-- contenedor de una misión -->
  <section id="missionView" style="display:none">
    <span class="read-chip" id="mChip"></span>
    <h2 class="read-title" id="mTitle"></h2>
    <div id="mIntro"></div>
    <div id="mBody"></div>
    <div class="mission-foot">
      <button class="btn ghost" onclick="backToHub()">← Volver al archivo</button>
      <span id="mStatus" style="color:var(--paper-faint);font-style:italic"></span>
    </div>
  </section>

  <!-- final -->
  <section id="ending" style="display:none"></section>
</main>

<script>
/* ===== CONFIG: pegá acá el link del PDF del cuento (de tu cátedra) ===== */
const CUENTO_URL = "https://drive.google.com/file/d/1YdSqG8bdtLe5Swfj9TLPz3qRH4h6xS-l/view?usp=sharing";

function abrirCuento(e){
  e.preventDefault();
  if(CUENTO_URL){ window.open(CUENTO_URL,'_blank'); }
  else { alert("Pegá el enlace del PDF en la línea CUENTO_URL del archivo, o conseguí el cuento por tu cátedra."); }
  return false;
}

/* ===== TEXTO DE LA FASE DE LECTURA (escrito para la plataforma, no es el cuento) ===== */
const READING = [
  {lead:true, html:`Estás a punto de entrar en uno de los relatos más célebres de Jorge Luis Borges, publicado en <em>1941</em>. No es un cuento que se lea: es un cuento que se <em>recorre</em>, como quien atraviesa un laberinto sin saber si la salida existe.`},
  {html:`En la superficie, es una historia de espionaje durante la Primera Guerra Mundial. Un profesor chino, <em>Yu Tsun</em>, espía para Alemania y es perseguido por un agente irlandés. Pero debajo de esa trama late otra cosa: un libro infinito, un jardín que es un laberinto, y una teoría del tiempo que se ramifica en infinitas posibilidades.`},
  {html:`Borges construye el relato como una <em>mamushka</em>: una voz dentro de otra voz dentro de otra. Un editor presenta un documento; el documento es la confesión de Yu Tsun; dentro de su confesión, otro personaje le revela el secreto de un antepasado. Cada capa cambia lo que creías entender.`},
  {frag:`«Dejo a los varios porvenires (no a todos) mi jardín de senderos que se bifurcan.»`, cite:`— frase central del relato`},
  {html:`Tu misión como <em>detective textual</em> será descender por esas capas: identificar quién habla, mapear quién le dijo qué a quién, y descubrir por qué este texto puede leerse de varias maneras a la vez, todas válidas. No hay una única respuesta correcta. Eso es lo que vas a aprender a tolerar y a disfrutar.`},
  {html:`Antes de continuar, leé el cuento completo en tu copia. Esta plataforma no reemplaza la lectura: es el archivo secreto que te ayuda a descifrarla.`},
];

function renderReading(){
  const c=document.getElementById('readBody'); c.innerHTML='';
  READING.forEach(seg=>{
    if(seg.frag){ c.insertAdjacentHTML('beforeend', `<span class="frag">${seg.frag}${seg.cite?`<cite>${seg.cite}</cite>`:''}</span>`); }
    else { const p=document.createElement('p'); if(seg.lead)p.className='lead'; p.innerHTML=seg.html; c.appendChild(p); }
  });
}

function startReading(){
  document.getElementById('title').style.display='none';
  document.getElementById('reading').style.display='block';
  renderReading();
  window.scrollTo({top:0});
  window.addEventListener('scroll', checkGate, {passive:true});
}
function checkGate(){
  const g=document.getElementById('readGate').getBoundingClientRect();
  if(g.top < window.innerHeight + 40){
    const b=document.getElementById('toGame');
    if(b.disabled){ b.disabled=false; document.querySelector('#readGate .note').textContent='El archivo se abre. Desciende.'; }
  }
}
// el botón arranca habilitado tras un instante por si no hay scroll (texto corto)

/* ============================================================
   MOTOR DEL JUEGO
   ============================================================ */
const GAME = { solved:new Set(), startTime:null, timerInt:null, forkChosen:null };

/* ---- las tres misiones ---- */
const MISSIONS = [
  {
    id:0, name:"Romper la superficie", img:"mision1",
    desc:"Identificá quién habla en el prólogo y qué información falta.",
    skill:"Lectura crítica · voz narrativa y fuentes",
    chip:"Misión I",
    intro:"El relato no empieza por su protagonista. Antes de la confesión de Yu Tsun hay otra voz, y un dato que falta. Encontralos.",
    type:"steps",
    steps:[
      {q:"¿Quién presenta el documento al comienzo del relato, antes de la voz de Yu Tsun?", kind:"Comprensión literal",
        opts:["El propio Yu Tsun","Un editor / narrador externo que cita una declaración","El capitán Madden","Stephen Albert"], correct:1,
        fb:"Una voz editorial enmarca el texto: presenta la declaración de Yu Tsun como un documento. Esa es la capa más externa de la mamushka."},
      {q:"El relato se conecta con un hecho histórico (una ofensiva en la Primera Guerra). ¿Qué función cumple esa nota inicial?", kind:"Inferencia",
        opts:["Es decorativa, no aporta nada","Ancla la ficción en la historia y plantea un enigma: por qué se demoró el ataque","Es un error del editor","Resume todo el cuento"], correct:1,
        fb:"El marco histórico convierte la confesión en la 'explicación' de un hecho real: el texto se presenta como documento que llena un vacío."},
      {q:"Se menciona que faltan las dos primeras páginas de la declaración. ¿Qué efecto produce ese hueco?", kind:"Inferencia",
        opts:["Ninguno","Vuelve al narrador menos confiable y nos obliga a leer con sospecha","Demuestra que Yu Tsun mentía","Indica que el cuento está incompleto por error"], correct:1,
        fb:"El hiato (la información que falta) es clave: nos avisa que el testimonio está mutilado y que debemos desconfiar de la superficie."},
      {q:"Si la confesión es de un espía condenado a muerte, ¿con qué actitud conviene leer su versión de los hechos?", kind:"Pensamiento crítico",
        opts:["Como verdad objetiva y completa","Como un relato interesado, que debemos interpretar y no creer sin más","Como pura ficción sin valor","Como un informe neutral"], correct:1,
        fb:"Romper la superficie es exactamente esto: entender que detrás de un narrador hay intereses, omisiones y una situación (la condena) que tiñe todo lo que cuenta."},
    ]
  },
  {
    id:1, name:"El Laberinto de Voces", img:"mision2",
    desc:"Abrí los cajones y mapeá quién le dijo qué a quién.",
    skill:"Comprensión estructural · polifonía y discurso referido",
    chip:"Misión II",
    intro:"El secreto del cuento viaja de boca en boca. Abrí cada cajón para escuchar una voz; al abrirlos todos, verás el laberinto de la polifonía dibujarse.",
    type:"voices",
    drawers:[
      {who:"El Editor", role:"Voz que enmarca", text:"Presenta la declaración de Yu Tsun como un documento histórico. Es la voz más externa: no vivió los hechos, solo los transmite.", frag:"«La siguiente declaración… arroja una insospechada luz sobre el caso.»"},
      {who:"Yu Tsun", role:"Narrador-protagonista", text:"Espía condenado que confiesa. Todo lo que sabemos del jardín y del tiempo nos llega filtrado por su voz y su angustia.", frag:"«…sentí a mi alrededor y en mi oscuro cuerpo una invisible, intangible pululación.»"},
      {who:"Stephen Albert", role:"Voz que revela", text:"El sinólogo que, sin saber quién es Yu Tsun, le explica el secreto del laberinto y del libro de su antepasado. Su voz contiene a otra.", frag:"«El jardín de senderos que se bifurcan era la novela caótica…»"},
      {who:"Ts'ui Pên", role:"Voz ausente / origen", text:"El antepasado que construyó el laberinto-libro. Ya está muerto: habla solo a través de su obra, citada por Albert, narrada por Yu Tsun, transmitida por el editor.", frag:"«Dejo a los varios porvenires (no a todos) mi jardín…»"},
    ],
    finalQ:{q:"Entonces, ¿cómo nos llega la frase de Ts'ui Pên sobre los 'varios porvenires'?", 
      opts:["Directamente de Ts'ui Pên","Ts'ui Pên → Albert la cita → Yu Tsun la narra → el editor la transmite","La dice Yu Tsun","La inventa el editor"], correct:1,
      fb:"Esa es la polifonía: cuatro capas de voces. La verdad del cuento siempre llega mediada, nunca de primera mano. Por eso 'tolerar la ambigüedad' es leer a Borges."}
  },
  {
    id:2, name:"La Bifurcación", img:"mision3",
    desc:"Elegí una teoría del tiempo y mirá qué sostiene el texto.",
    skill:"Hipótesis de lectura · interpretaciones válidas",
    chip:"Misión III",
    intro:"El corazón del cuento es una idea del tiempo. No hay una sola lectura correcta: cada sendero se sostiene con evidencia. Elegí uno y descubrí su argumento. Podés explorar los tres.",
    type:"fork",
    paths:[
      {name:"Tiempo que se bifurca", desc:"Todos los futuros ocurren a la vez, en universos paralelos.",
        result:"Es la lectura central que propone Albert: el libro de Ts'ui Pên no elige entre alternativas, las realiza todas. En un tiempo Yu Tsun es enemigo de Albert; en otro, su amigo. El cuento abraza la simultaneidad de lo posible. Evidencia: la imagen de la red de tiempos que se acercan, se bifurcan, se cortan."},
      {name:"Tiempo laberinto", desc:"El tiempo es un laberinto invisible, no el espacio.",
        result:"Lectura igualmente válida: el 'laberinto' que todos buscaban no era físico sino temporal. El libro ES el laberinto. Apoya esta hipótesis el enigma resuelto por Albert: un laberinto cuyo tema secreto y prohibido es el tiempo. La estructura del relato (voces dentro de voces) imita ese laberinto."},
      {name:"Tiempo trágico y único", desc:"Pese a todo, Yu Tsun vive UNA sola línea: la del crimen.",
        result:"Lectura contrastante pero defendible: más allá de la teoría, en la trama Yu Tsun mata a Albert y es condenado. La infinitud de los porvenires no lo salva del 'innumerable arrepentimiento y cansancio' final. El texto sostiene a la vez la idea infinita y la condena concreta: ahí está su tensión."},
    ]
  }
];

function enterGame(){
  document.getElementById('reading').style.display='none';
  document.getElementById('game').style.display='block';
  document.getElementById('topbar').classList.remove('hidden');
  if(!GAME.startTime){ GAME.startTime=Date.now(); startTimer(); }
  if(!audio.on) toggleSound();
  renderHub();
  window.scrollTo({top:0,behavior:'smooth'});
}
function startTimer(){
  GAME.timerInt=setInterval(()=>{
    const s=Math.floor((Date.now()-GAME.startTime)/1000);
    document.getElementById('timer').textContent=String(Math.floor(s/60)).padStart(2,'0')+':'+String(s%60).padStart(2,'0');
  },500);
}
function renderHub(){
  document.getElementById('missionHub').style.display='block';
  document.getElementById('missionView').style.display='none';
  document.getElementById('ending').style.display='none';
  const g=document.getElementById('missionsGrid'); g.innerHTML='';
  MISSIONS.forEach((m,i)=>{
    const done=GAME.solved.has(m.id);
    const locked = i>0 && !GAME.solved.has(MISSIONS[i-1].id) && !done;
    const card=document.createElement('div');
    card.className='mission-card'+(done?' done':'')+(locked?' locked':'');
    card.innerHTML=`<div class="mlock">${done?'✦':(locked?'⊘':'◇')}</div>
      <div class="mnum">${['I','II','III'][i]}</div>
      <div class="mname">${m.name}</div>
      <div class="mdesc">${m.desc}</div>
      <div class="mskill">${m.skill}</div>`;
    if(!locked) card.onclick=()=>openMission(m.id);
    g.appendChild(card);
  });
  document.getElementById('missionNum').textContent=GAME.solved.size;
  document.getElementById('finalReady').style.display = GAME.solved.size===MISSIONS.length?'block':'none';
}
function backToHub(){ sfx('gear'); renderHub(); window.scrollTo({top:0,behavior:'smooth'}); }

function openMission(id){
  const m=MISSIONS[id]; GAME.current=id;
  sfx('gear');
  document.getElementById('missionHub').style.display='none';
  document.getElementById('missionView').style.display='block';
  document.getElementById('mChip').textContent=m.chip;
  document.getElementById('mTitle').textContent=m.name;
  document.getElementById('mIntro').innerHTML=`${m.img?`<img class="mission-hero" src="images/${m.img}.png" alt="" onerror="this.remove()">`:''}<p style="text-align:center;color:var(--paper-dim);font-style:italic;margin-bottom:30px">${m.intro}</p>`;
  const body=document.getElementById('mBody'); body.innerHTML='';
  if(m.type==='steps') renderSteps(m,body);
  else if(m.type==='voices') renderVoices(m,body);
  else if(m.type==='fork') renderFork(m,body);
  updateMStatus(id);
  window.scrollTo({top:0,behavior:'smooth'});
}
function updateMStatus(id){
  const m=MISSIONS[id];
  document.getElementById('mStatus').textContent = GAME.solved.has(id)? '✦ Misión completada' : 'En curso…';
}

/* ---- Misión tipo STEPS (preguntas) ---- */
function renderSteps(m,body){
  const prog={done:0};
  m.steps.forEach((st,si)=>{
    const div=document.createElement('div'); div.className='step';
    div.innerHTML=`<div class="q"><span class="qn">${si+1}.</span><span>${st.q}</span></div><div class="kind">${st.kind}</div>`;
    st.opts.forEach((opt,oi)=>{
      const b=document.createElement('button'); b.className='opt'; b.textContent=opt;
      b.onclick=()=>{
        if(div.dataset.done) return;
        if(oi===st.correct){
          div.dataset.done='1'; div.classList.add('solved'); sfx('gear');
          div.querySelectorAll('.opt').forEach((o,k)=>{o.disabled=true; if(k===st.correct)o.classList.add('correct');});
          const fb=div.querySelector('.fb'); fb.textContent='↳ '+st.fb; fb.classList.add('show');
          prog.done++;
          if(prog.done===m.steps.length) completeMission(m.id);
        } else { b.classList.add('wrong'); sfx('wrong'); setTimeout(()=>b.classList.remove('wrong'),800); }
      };
      div.appendChild(b);
    });
    const fb=document.createElement('div'); fb.className='fb'; div.appendChild(fb);
    body.appendChild(div);
  });
}

/* ---- Misión tipo VOICES (cajones + mapa) ---- */
function renderVoices(m,body){
  const opened=new Set();
  body.innerHTML=`<p class="voices-intro">Abrí los cuatro cajones. Cada uno guarda una voz del relato.</p>
    <div class="drawers" id="drawers"></div>
    <div class="map-hint">El laberinto de voces se dibuja a medida que abrís los cajones</div>
    <div class="voice-map" id="voiceMap"></div>
    <div id="voiceFinal"></div>`;
  const dr=body.querySelector('#drawers');
  m.drawers.forEach((d,di)=>{
    const el=document.createElement('div'); el.className='drawer';
    el.innerHTML=`<div class="handle">${d.who}</div>
      <div class="content"><span class="role">${d.role}</span>${d.text}<div class="frag-mini">${d.frag}</div></div>`;
    el.querySelector('.handle').onclick=()=>{
      if(!el.classList.contains('open')){ el.classList.add('open'); sfx('drawer'); opened.add(di); drawMap(opened.size); 
        if(opened.size===m.drawers.length) showVoiceFinal(m,body); }
    };
    dr.appendChild(el);
  });
  drawMap(0);
}
function drawMap(n){
  // dibuja progresivamente la cadena de voces: Editor -> Yu Tsun -> Albert -> Ts'ui Pên
  const nodes=[{x:90,y:60,l:"Editor"},{x:260,y:60,l:"Yu Tsun"},{x:430,y:60,l:"Albert"},{x:600,y:60,l:"Ts'ui Pên"}];
  let svg=`<svg viewBox="0 0 690 120" xmlns="http://www.w3.org/2000/svg">`;
  for(let i=0;i<nodes.length-1;i++){
    const on = i < n-1;
    svg+=`<line x1="${nodes[i].x+34}" y1="60" x2="${nodes[i+1].x-34}" y2="60" stroke="${on?'#9b9388':'#3a3833'}" stroke-width="1.5" stroke-dasharray="${on?'0':'4 5'}"/>`;
    if(on) svg+=`<polygon points="${nodes[i+1].x-34},60 ${nodes[i+1].x-42},56 ${nodes[i+1].x-42},64" fill="#9b9388"/>`;
  }
  nodes.forEach((nd,i)=>{
    const on = i < n;
    svg+=`<circle cx="${nd.x}" cy="60" r="30" fill="${on?'#16161a':'#101012'}" stroke="${on?'#9b9388':'#3a3833'}" stroke-width="1.5"/>
      <text x="${nd.x}" y="64" text-anchor="middle" font-family="Cardo, serif" font-size="12" fill="${on?'#e8e4da':'#5a564c'}">${nd.l}</text>`;
  });
  svg+=`</svg>`;
  document.getElementById('voiceMap').innerHTML=svg;
}
function showVoiceFinal(m,body){
  const wrap=body.querySelector('#voiceFinal');
  if(wrap.dataset.shown) return; wrap.dataset.shown='1';
  const st=m.finalQ;
  const div=document.createElement('div'); div.className='step'; div.style.marginTop='10px';
  div.innerHTML=`<div class="q"><span class="qn">✦</span><span>${st.q}</span></div><div class="kind">Síntesis estructural</div>`;
  st.opts.forEach((opt,oi)=>{
    const b=document.createElement('button'); b.className='opt'; b.textContent=opt;
    b.onclick=()=>{
      if(div.dataset.done) return;
      if(oi===st.correct){ div.dataset.done='1'; div.classList.add('solved'); sfx('gear');
        div.querySelectorAll('.opt').forEach((o,k)=>{o.disabled=true; if(k===st.correct)o.classList.add('correct');});
        const fb=div.querySelector('.fb'); fb.textContent='↳ '+st.fb; fb.classList.add('show');
        completeMission(m.id);
      } else { b.classList.add('wrong'); sfx('wrong'); setTimeout(()=>b.classList.remove('wrong'),800); }
    };
    div.appendChild(b);
  });
  const fb=document.createElement('div'); fb.className='fb'; div.appendChild(fb);
  wrap.appendChild(div);
  div.scrollIntoView({behavior:'smooth',block:'center'});
}

/* ---- Misión tipo FORK (bifurcación) ---- */
function renderFork(m,body){
  const explored=new Set();
  body.innerHTML=`<p class="fork-intro">No hay una sola respuesta correcta. Elegí un sendero para leer su argumento; explorá los que quieras. Cuando hayas recorrido al menos uno, la misión se completa.</p>
    <div class="paths" id="paths"></div>
    <div class="path-result" id="pathResult"></div>`;
  const ps=body.querySelector('#paths');
  m.paths.forEach((p,pi)=>{
    const el=document.createElement('div'); el.className='path';
    el.innerHTML=`<div class="pname">${p.name}</div><div class="pdesc">${p.desc}</div>`;
    el.onclick=()=>{
      ps.querySelectorAll('.path').forEach(x=>x.classList.remove('chosen'));
      el.classList.add('chosen'); sfx('gear');
      GAME.forkChosen=p.name;
      const r=body.querySelector('#pathResult'); r.innerHTML=`<strong style="font-family:'Cormorant',serif;font-size:1.3rem;color:var(--paper)">${p.name}</strong><br><br>${p.result}`;
      r.classList.add('show');
      explored.add(pi);
      if(!GAME.solved.has(m.id)) completeMission(m.id);
    };
    ps.appendChild(el);
  });
}

function completeMission(id){
  if(GAME.solved.has(id)) { updateMStatus(id); return; }
  GAME.solved.add(id);
  sfx('unlock');
  document.getElementById('missionNum').textContent=GAME.solved.size;
  updateMStatus(id);
}

/* ---- FINAL ---- */
function copySynthesis(){
  const t=document.getElementById('synText'); const v=(t&&t.value.trim())||'';
  const conf=document.getElementById('synConfirm');
  if(!v){ if(conf){conf.textContent='Escribí tu informe antes de copiarlo.'; conf.classList.add('show');} return; }
  const header='INFORME DE LECTURA — El jardín de senderos que se bifurcan (J. L. Borges)\nSendero elegido: '+(GAME.forkChosen||'—')+'\n\n';
  const full=header+v;
  if(navigator.clipboard&&navigator.clipboard.writeText){
    navigator.clipboard.writeText(full).then(()=>{ if(conf){conf.textContent='✦ Informe copiado. Pegalo en tu documento de entrega.'; conf.classList.add('show');} })
      .catch(()=>{ if(conf){conf.textContent='No se pudo copiar automáticamente; seleccioná el texto y copialo a mano.'; conf.classList.add('show');} });
  } else { if(conf){conf.textContent='Seleccioná el texto del recuadro y copialo (Ctrl+C).'; conf.classList.add('show');} }
}

function showEnding(){
  clearInterval(GAME.timerInt);
  const s=Math.floor((Date.now()-GAME.startTime)/1000);
  const time=String(Math.floor(s/60)).padStart(2,'0')+':'+String(s%60).padStart(2,'0');
  document.getElementById('missionHub').style.display='none';
  document.getElementById('missionView').style.display='none';
  const e=document.getElementById('ending'); e.style.display='block';
  e.innerHTML=`
    <img class="ending-hero" src="images/final.png" alt="" onerror="this.remove()">
    <div class="diploma">
      <div class="seal">Archivo Onírico · Lectura completada</div>
      <h3>Detective Textual</h3>
      <p style="color:var(--paper-dim);font-style:italic;max-width:580px;margin:0 auto">Recorriste las tres capas del laberinto: rompiste la superficie, mapeaste las voces y elegiste tu sendero entre los infinitos porvenires.</p>
      <div class="stat-row">
        <div class="stat"><div class="sv">${time}</div><div class="sl">Tiempo en el laberinto</div></div>
        <div class="stat"><div class="sv">${GAME.solved.size}/3</div><div class="sl">Misiones</div></div>
        <div class="stat"><div class="sv">${GAME.forkChosen||'—'}</div><div class="sl">Sendero elegido</div></div>
      </div>
    </div>

    <div class="synthesis">
      <h4>Tu informe de lectura</h4>
      <p class="syn-intro">El detective deja constancia. Respondé con tus palabras: estas consignas son la verdadera prueba de comprensión, y podés copiarlas para tu entrega.</p>
      <ol class="syn-list">
        <li><b>La estructura.</b> Explicá con tus palabras por qué el relato es una "mamushka" de voces. ¿Quién enmarca a quién? ¿Por qué Borges nos da la verdad siempre mediada y nunca directa?</li>
        <li><b>El narrador no confiable.</b> ¿Qué efecto produce que falten las dos primeras páginas de la declaración de Yu Tsun? ¿Cómo cambia tu lectura saber que el testimonio está mutilado?</li>
        <li><b>La idea del tiempo.</b> Reformulá, sin copiar el texto, qué propone Ts'ui Pên sobre el tiempo. ¿En qué se diferencia de la idea de tiempo a la que estamos acostumbrados?</li>
        <li><b>La bifurcación moral.</b> El cuento sostiene a la vez la infinitud de los porvenires y la condena concreta de Yu Tsun. ¿Cómo conviven esas dos ideas? ¿Cuál pesa más para vos, y por qué?</li>
        <li><b>Tu hipótesis.</b> De las tres lecturas del tiempo que exploraste, ¿cuál defenderías en una monografía? Escribí una tesis de una sola oración y un argumento que la sostenga con evidencia del cuento.</li>
      </ol>
      <textarea id="synText" placeholder="Escribí acá tu informe de lectura… (después podrás copiarlo)"></textarea>
      <div class="center" style="margin-top:16px;display:flex;gap:12px;justify-content:center;flex-wrap:wrap">
        <button class="btn ghost" onclick="copySynthesis()">Copiar mi informe</button>
        <button class="btn ghost" onclick="abrirCuento(event)">Releer el cuento</button>
      </div>
      <div class="syn-confirm" id="synConfirm"></div>
    </div>

    <p class="frag" style="text-align:center;border:none;font-size:1.4rem;margin-top:40px">«El jardín de senderos que se bifurcan es una imagen incompleta, pero no falsa, del universo.»</p>
    <div class="center" style="margin-top:30px"><button class="btn ghost" onclick="location.reload()">Volver a empezar</button></div>
    <div class="credits">El jardín de senderos que se bifurcan · Jorge Luis Borges, 1941<br>Plataforma de comprensión lectora · estética surrealista monocroma · sonido generado sin material con copyright<br>El texto del cuento no se reproduce: se lee desde la copia provista por la cátedra.</div>`;
  window.scrollTo({top:0,behavior:'smooth'});
}

/* ============================================================
   AUDIO — tic-tac de reloj + engranajes (Web Audio API)
   ============================================================ */
let audio={ctx:null,on:false,master:null,tickOn:true};
function initAudio(){
  if(audio.ctx) return;
  const Ctx=window.AudioContext||window.webkitAudioContext; if(!Ctx) return;
  const ctx=new Ctx(); audio.ctx=ctx;
  const master=ctx.createGain(); master.gain.value=0; master.connect(ctx.destination); audio.master=master;
  // dron onírico muy bajo
  const drone=ctx.createGain(); drone.gain.value=.05; drone.connect(master);
  [48,48.3].forEach(f=>{const o=ctx.createOscillator();o.type='sine';o.frequency.value=f;o.connect(drone);o.start();});
  // tic-tac de reloj
  function tick(high){
    if(!audio.ctx) return;
    const t=ctx.currentTime;
    const o=ctx.createOscillator(); o.type='square'; o.frequency.value=high?2200:1700;
    const f=ctx.createBiquadFilter(); f.type='bandpass'; f.frequency.value=high?2200:1700; f.Q.value=12;
    const g=ctx.createGain(); g.gain.setValueAtTime(0,t); g.gain.linearRampToValueAtTime(.08,t+.005); g.gain.exponentialRampToValueAtTime(.0001,t+.06);
    o.connect(f); f.connect(g); g.connect(master); o.start(t); o.stop(t+.07);
  }
  let hi=false;
  audio.tickInt=setInterval(()=>{ if(audio.on&&audio.tickOn){ tick(hi); hi=!hi; } },1000);
}
function toggleSound(){
  initAudio(); if(!audio.ctx) return; audio.ctx.resume(); audio.on=!audio.on;
  audio.master.gain.linearRampToValueAtTime(audio.on?.7:0, audio.ctx.currentTime+.8);
  const b=document.getElementById('soundBtn'); if(b){ b.textContent=audio.on?'♪':'🔇'; b.style.color=audio.on?'var(--paper)':'var(--paper-dim)'; }
}
function sfx(type){
  if(!audio.ctx||!audio.on) return; const ctx=audio.ctx, t=ctx.currentTime;
  if(type==='gear'){ // engranaje: serie de clics mecánicos
    [0,.05,.1,.15].forEach((d,i)=>{const nb=ctx.createBuffer(1,ctx.sampleRate*.03,ctx.sampleRate);const dd=nb.getChannelData(0);for(let j=0;j<dd.length;j++)dd[j]=(Math.random()*2-1)*Math.pow(1-j/dd.length,1.5);const n=ctx.createBufferSource();n.buffer=nb;const f=ctx.createBiquadFilter();f.type='bandpass';f.frequency.value=1800-i*150;f.Q.value=6;const g=ctx.createGain();g.gain.value=.18;n.connect(f);f.connect(g);g.connect(audio.master);n.start(t+d);}); }
  else if(type==='drawer'){ // cajón que se desliza: ruido filtrado que sube
    const nb=ctx.createBuffer(1,ctx.sampleRate*.4,ctx.sampleRate);const dd=nb.getChannelData(0);for(let j=0;j<dd.length;j++)dd[j]=(Math.random()*2-1)*Math.pow(1-j/dd.length,.6);
    const n=ctx.createBufferSource();n.buffer=nb;const f=ctx.createBiquadFilter();f.type='lowpass';f.frequency.setValueAtTime(300,t);f.frequency.linearRampToValueAtTime(900,t+.35);
    const g=ctx.createGain();g.gain.setValueAtTime(.0,t);g.gain.linearRampToValueAtTime(.12,t+.05);g.gain.exponentialRampToValueAtTime(.001,t+.4);
    n.connect(f);f.connect(g);g.connect(audio.master);n.start(t);
    const o=ctx.createOscillator();o.type='sine';o.frequency.setValueAtTime(180,t+.3);o.frequency.exponentialRampToValueAtTime(90,t+.42);const og=ctx.createGain();og.gain.setValueAtTime(.18,t+.3);og.gain.exponentialRampToValueAtTime(.001,t+.45);o.connect(og);og.connect(audio.master);o.start(t+.3);o.stop(t+.47);
  }
  else if(type==='unlock'){ // campana mecánica de logro
    [392,523,659].forEach((f,i)=>{const o=ctx.createOscillator();o.type='triangle';o.frequency.value=f;const g=ctx.createGain();g.gain.setValueAtTime(0,t+i*.12);g.gain.linearRampToValueAtTime(.14,t+i*.12+.03);g.gain.exponentialRampToValueAtTime(.001,t+i*.12+.7);o.connect(g);g.connect(audio.master);o.start(t+i*.12);o.stop(t+i*.12+.75);}); }
  else if(type==='wrong'){ const o=ctx.createOscillator();o.type='sawtooth';o.frequency.setValueAtTime(140,t);o.frequency.exponentialRampToValueAtTime(70,t+.25);const g=ctx.createGain();g.gain.setValueAtTime(.16,t);g.gain.exponentialRampToValueAtTime(.001,t+.3);o.connect(g);g.connect(audio.master);o.start(t);o.stop(t+.32); }
}
document.addEventListener('DOMContentLoaded',()=>{ const b=document.getElementById('soundBtn'); if(b) b.onclick=toggleSound; });
document.body.addEventListener('pointerdown',()=>{ if(audio.ctx) audio.ctx.resume(); });

/* ===== cursor de tinta ===== */
const cursor=document.getElementById('cursor');
let lastTrail=0;
window.addEventListener('mousemove',e=>{
  cursor.style.left=e.clientX+'px'; cursor.style.top=e.clientY+'px';
  const now=Date.now();
  if(now-lastTrail>40){
    lastTrail=now;
    const t=document.createElement('div'); t.className='ink-trail';
    const s=6+Math.random()*8; t.style.width=s+'px'; t.style.height=s+'px';
    t.style.left=e.clientX+'px'; t.style.top=e.clientY+'px';
    document.body.appendChild(t); setTimeout(()=>t.remove(),1100);
  }
});
document.querySelectorAll('button,a').forEach(el=>{
  el.addEventListener('mouseenter',()=>cursor.classList.add('big'));
  el.addEventListener('mouseleave',()=>cursor.classList.remove('big'));
});
</script>
</body>
</html>
