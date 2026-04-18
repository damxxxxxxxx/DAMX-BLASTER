<!DOCTYPE html>
<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>DAMX BLASTER V4 — WhatsApp Broadcast Bot</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500;600&family=Outfit:wght@400;600;700;800;900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<style>
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent}

/* ══ OCEAN (default) ══ */
:root{
  --a:#38BDF8;--a2:#0EA5E9;--a3:#7DD3FC;--ad:#0284C7;
  --glow:rgba(56,189,248,0.15);--glows:rgba(56,189,248,0.30);
  --bg:#0B1120;--bg2:#0F172A;
  --card:rgba(255,255,255,0.03);--card2:rgba(255,255,255,0.06);
  --bd:rgba(56,189,248,0.13);--bd2:rgba(56,189,248,0.06);
  --txt:#E0EEFF;--txt2:#6A91BC;--txt3:#3D5A7A;
  --code:rgba(0,0,0,0.30);
  --stripe:linear-gradient(90deg,#38BDF8,#0EA5E9);
  --grad:linear-gradient(135deg,#38BDF8,#0EA5E9 60%,#7DD3FC);
  --gbtn:linear-gradient(120deg,#38BDF8,#0EA5E9);
}

html{scroll-behavior:smooth}
body{
  font-family:'Inter',sans-serif;
  background:var(--bg);color:var(--txt);
  overflow-x:hidden;min-height:100vh;
  transition:background .5s,color .3s;
  -webkit-font-smoothing:antialiased;
}
body::before{
  content:'';position:fixed;inset:0;z-index:0;pointer-events:none;
  background:
    radial-gradient(ellipse 65% 45% at 85% -5%,var(--glow),transparent),
    radial-gradient(ellipse 45% 35% at -5% 85%,rgba(14,165,233,0.06),transparent);
  transition:background .6s;
}

/* ══ LOADING ══ */
#ls{position:fixed;inset:0;z-index:9999;background:var(--bg);display:flex;flex-direction:column;align-items:center;justify-content:center;gap:18px;transition:opacity .7s}
.ls-r{position:relative;width:68px;height:68px;display:flex;align-items:center;justify-content:center}
.ls-r::before{content:'';position:absolute;inset:0;border-radius:50%;border:1.5px solid var(--bd2);border-top-color:var(--a);animation:spin .9s linear infinite}
.ls-r::after{content:'';position:absolute;inset:7px;border-radius:50%;border:1px solid var(--bd2);border-bottom-color:var(--a3);animation:spin 1.6s linear infinite reverse}
@keyframes spin{to{transform:rotate(360deg)}}
.ls-logo{width:40px;height:40px;border-radius:11px;object-fit:cover;box-shadow:0 0 16px var(--glows)}
.ls-ti{font-family:'Outfit',sans-serif;font-size:1.45rem;font-weight:800;letter-spacing:3px;text-transform:uppercase;background:var(--grad);-webkit-background-clip:text;background-clip:text;color:transparent}
.ls-sub{font-family:'JetBrains Mono',monospace;font-size:.62rem;letter-spacing:2.5px;color:var(--txt3);text-transform:uppercase}
.ls-bar{width:190px;height:1.5px;background:var(--bd2);border-radius:2px;overflow:hidden}
.ls-fill{height:100%;width:0;background:var(--gbtn);border-radius:2px;transition:width .12s linear;position:relative}
.ls-fill::after{content:'';position:absolute;right:-1px;top:-3px;width:5px;height:7px;border-radius:3px;background:var(--a);box-shadow:0 0 8px var(--a)}

/* ══ NAV ══ */
nav{
  position:fixed;top:0;left:0;right:0;z-index:500;height:56px;
  display:flex;align-items:center;gap:7px;padding:0 12px;
  background:rgba(11,17,32,0.92);backdrop-filter:blur(18px);-webkit-backdrop-filter:blur(18px);
  border-bottom:1px solid var(--bd2);transition:background .5s,border-color .5s;
}
[data-theme="brown"] nav{background:rgba(14,10,7,0.92)}
[data-theme="forest"] nav{background:rgba(6,15,13,0.92)}
.nav-brand{display:flex;align-items:center;gap:8px;text-decoration:none;flex-shrink:0}
.nav-logo{width:28px;height:28px;border-radius:8px;object-fit:cover;box-shadow:0 0 10px var(--glows);transition:.3s}
.nav-logo:hover{box-shadow:0 0 16px var(--glows);transform:scale(1.07)}
.nav-nm{font-family:'Outfit',sans-serif;font-weight:800;font-size:.9rem;letter-spacing:1.5px;text-transform:uppercase}
.nav-nm span{background:var(--grad);-webkit-background-clip:text;background-clip:text;color:transparent}
.nav-sc{flex:1;overflow-x:auto;overflow-y:hidden;scrollbar-width:none}
.nav-sc::-webkit-scrollbar{display:none}
.nav-links{display:flex;align-items:center;gap:1px;padding:0 6px;white-space:nowrap}
.nl{padding:5px 10px;border-radius:6px;font-family:'JetBrains Mono',monospace;font-size:.7rem;font-weight:500;letter-spacing:.3px;color:var(--txt3);text-decoration:none;cursor:pointer;border:1px solid transparent;transition:all .18s;white-space:nowrap}
.nl:hover{color:var(--a);background:var(--glow)}
.nl.active{color:var(--a);background:var(--glow);border-color:var(--bd)}
.pal-btn{flex-shrink:0;width:32px;height:32px;display:flex;align-items:center;justify-content:center;background:var(--card2);border:1px solid var(--bd2);border-radius:7px;cursor:pointer;transition:all .18s;color:var(--txt2);font-size:.78rem}
.pal-btn:hover{border-color:var(--bd);color:var(--a);background:var(--glow)}

/* ══ TEMA POPUP ══ */
.pal-pop{position:fixed;top:62px;right:10px;z-index:600;background:var(--bg2);border:1px solid var(--bd);border-radius:13px;padding:9px;width:215px;display:none;flex-direction:column;gap:4px;box-shadow:0 14px 45px rgba(0,0,0,.65);animation:pop .2s cubic-bezier(.34,1.56,.64,1)}
.pal-pop.open{display:flex}
@keyframes pop{from{opacity:0;transform:scale(.9) translateY(-5px)}to{opacity:1;transform:scale(1) translateY(0)}}
.pal-lb{font-family:'JetBrains Mono',monospace;font-size:.59rem;letter-spacing:2px;text-transform:uppercase;color:var(--txt3);padding:2px 5px 6px;border-bottom:1px solid var(--bd2);margin-bottom:2px}
.t-opt{display:flex;align-items:center;gap:9px;padding:8px 9px;border-radius:8px;cursor:pointer;border:1px solid transparent;transition:all .16s}
.t-opt:hover{background:var(--card2);border-color:var(--bd2)}
.t-opt.sel{background:var(--glow);border-color:var(--bd)}
.t-dots{display:flex;gap:3px}
.t-dot{width:10px;height:10px;border-radius:50%}
.t-nm{font-size:.8rem;font-weight:600;color:var(--txt)}
.t-sb{font-size:.61rem;color:var(--txt3);font-family:'JetBrains Mono',monospace;letter-spacing:.2px}

/* ══ LAYOUT ══ */
.app{padding-top:56px;position:relative;z-index:1}
.page{display:none;animation:fu .4s cubic-bezier(.22,.61,.36,1)}
.page.active-page{display:block}
@keyframes fu{from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:translateY(0)}}
.wrap{max-width:1040px;margin:0 auto;padding:2.6rem 1.1rem 4.5rem}

/* ══ HERO ══ */
.hero-w{max-width:1040px;margin:0 auto;padding:2.8rem 1.1rem 1.2rem;display:grid;grid-template-columns:1fr 210px;gap:2.2rem;align-items:start}
@media(max-width:760px){.hero-w{grid-template-columns:1fr}.hero-cards{display:none}}

.badge{display:inline-flex;align-items:center;gap:7px;padding:4px 11px;border-radius:5px;border:1px solid var(--bd);background:var(--glow);font-family:'JetBrains Mono',monospace;font-size:.66rem;font-weight:500;letter-spacing:1px;color:var(--a);margin-bottom:1.2rem}
.bdot{width:5px;height:5px;border-radius:50%;background:var(--a);animation:blink 2s infinite;box-shadow:0 0 5px var(--a)}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.3}}
h1.htitle{font-family:'Outfit',sans-serif;font-size:clamp(2.3rem,7vw,4.4rem);font-weight:900;line-height:1.07;letter-spacing:-1px;margin-bottom:1rem}
.gtxt{background:var(--grad);-webkit-background-clip:text;background-clip:text;color:transparent}
.hsub{font-size:.93rem;color:var(--txt2);max-width:490px;line-height:1.75;margin-bottom:1.9rem}
.btns{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:2.3rem}
.btn{padding:9px 18px;border-radius:8px;border:none;cursor:pointer;font-family:'Outfit',sans-serif;font-size:.84rem;font-weight:700;letter-spacing:.3px;display:inline-flex;align-items:center;gap:7px;transition:all .22s cubic-bezier(.34,1.56,.64,1)}
.bp{background:var(--gbtn);color:#fff;box-shadow:0 4px 16px var(--glow)}
.bp:hover{transform:translateY(-2px);box-shadow:0 7px 24px var(--glows)}
.bs{background:transparent;color:var(--txt2);border:1px solid var(--bd)}
.bs:hover{border-color:var(--a);color:var(--a);background:var(--glow);transform:translateY(-2px)}
.stats{display:flex;gap:1.8rem;flex-wrap:wrap}
.sn{font-family:'Outfit',sans-serif;font-size:1.8rem;font-weight:800;line-height:1;background:var(--grad);-webkit-background-clip:text;background-clip:text;color:transparent}
.sl{font-family:'JetBrains Mono',monospace;font-size:.6rem;letter-spacing:1.5px;text-transform:uppercase;color:var(--txt3);margin-top:3px}
.sdiv{width:1px;background:var(--bd2);height:34px;margin-top:3px}

/* ── Hero mini cards ── */
.hero-cards{display:flex;flex-direction:column;gap:8px}
.mc{background:var(--card2);border:1px solid var(--bd2);border-radius:11px;padding:10px 12px;position:relative;overflow:hidden;transition:border-color .4s}
.mc::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:var(--stripe);opacity:.65}
.mc:nth-child(1){animation:fl 5s ease-in-out infinite}
.mc:nth-child(2){animation:fl 5s ease-in-out 1.8s infinite}
.mc:nth-child(3){animation:fl 5s ease-in-out 3.5s infinite}
@keyframes fl{0%,100%{transform:translateY(0)}50%{transform:translateY(-5px)}}
.mctag{font-family:'JetBrains Mono',monospace;font-size:.58rem;letter-spacing:.9px;text-transform:uppercase;padding:2px 7px;border-radius:3px;display:inline-block;margin-bottom:4px}
.mt1{background:var(--glow);color:var(--a)}.mt2{background:rgba(14,165,233,.1);color:var(--a2)}.mt3{background:rgba(125,211,252,.08);color:var(--a3)}
.mcti{font-size:.82rem;font-weight:600;color:var(--txt)}
.mcsb{font-family:'JetBrains Mono',monospace;font-size:.61rem;color:var(--txt3);margin-top:2px;letter-spacing:.2px}
.mcbar{height:2px;border-radius:2px;background:var(--bd2);margin-top:6px;overflow:hidden}
.mcfill{height:100%;border-radius:2px;background:var(--gbtn)}

/* ══ SEC HEADING ══ */
.sh{margin-bottom:2rem}
.stag{font-family:'JetBrains Mono',monospace;font-size:.6rem;letter-spacing:2.5px;text-transform:uppercase;color:var(--a);margin-bottom:7px;display:flex;align-items:center;gap:7px}
.stag::before{content:'';width:14px;height:1px;background:var(--a);opacity:.6}
.sh h2{font-family:'Outfit',sans-serif;font-size:1.65rem;font-weight:800;letter-spacing:-.3px;line-height:1.2}
.sh p{color:var(--txt2);margin-top:6px;font-size:.86rem;line-height:1.65}

/* ══ FEAT GRID ══ */
.fg{display:grid;grid-template-columns:repeat(auto-fill,minmax(230px,1fr));gap:.85rem}
.fc{background:var(--card);border:1px solid var(--bd2);border-radius:13px;padding:1.3rem 1.2rem;transition:all .26s;position:relative;overflow:hidden}
.fc::before{content:'';position:absolute;inset:0;background:radial-gradient(circle at 0% 0%,var(--glow),transparent 55%);opacity:0;transition:opacity .28s}
.fc:hover{border-color:var(--bd);box-shadow:0 7px 24px var(--glow);transform:translateY(-3px)}
.fc:hover::before{opacity:1}
.fi{width:38px;height:38px;border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:.95rem;margin-bottom:.85rem;position:relative;z-index:1}
.fi1{background:var(--glow);color:var(--a)}.fi2{background:rgba(14,165,233,.1);color:var(--a2)}.fi3{background:rgba(125,211,252,.08);color:var(--a3)}
.fti{font-family:'Outfit',sans-serif;font-weight:700;font-size:.9rem;margin-bottom:4px;position:relative;z-index:1}
.fd{font-size:.8rem;color:var(--txt2);line-height:1.6;position:relative;z-index:1}

/* ══ COMMANDS ══ */
.cmd-tabs{display:flex;gap:5px;flex-wrap:wrap;margin-bottom:1.3rem}
.ctab{padding:4px 11px;border-radius:5px;font-family:'JetBrains Mono',monospace;font-size:.65rem;font-weight:500;letter-spacing:.8px;text-transform:uppercase;color:var(--txt3);background:var(--card2);border:1px solid var(--bd2);cursor:pointer;transition:all .16s}
.ctab:hover,.ctab.active{background:var(--glow);color:var(--a);border-color:var(--bd)}
.cg{display:grid;grid-template-columns:repeat(auto-fill,minmax(270px,1fr));gap:.85rem}
.cc{background:var(--card);border:1px solid var(--bd2);border-radius:12px;padding:1.2rem;transition:all .22s;position:relative;overflow:hidden}
.cc::before{content:'';position:absolute;top:0;left:0;right:0;height:2px}
.s1::before{background:linear-gradient(90deg,var(--a),var(--a2))}
.s2::before{background:linear-gradient(90deg,var(--a2),var(--a3))}
.s3::before{background:linear-gradient(90deg,var(--a3),var(--a))}
.cc:hover{border-color:var(--bd);box-shadow:0 5px 20px var(--glow);transform:translateY(-3px)}
.ch{display:flex;align-items:center;justify-content:space-between;margin-bottom:.55rem}
.cn{font-family:'JetBrains Mono',monospace;font-size:.9rem;font-weight:600;color:var(--a);letter-spacing:.3px}
.ccat{font-family:'JetBrains Mono',monospace;font-size:.58rem;font-weight:600;letter-spacing:.8px;padding:2px 7px;border-radius:4px;text-transform:uppercase}
.ca{background:var(--glow);color:var(--a)}.cb{background:rgba(14,165,233,.1);color:var(--a2)}.cc2{background:rgba(125,211,252,.08);color:var(--a3)}
.cd{font-size:.8rem;color:var(--txt2);line-height:1.56;margin-bottom:.85rem}
.ce{background:var(--code);border:1px solid var(--bd2);border-radius:8px;padding:8px 10px;font-family:'JetBrains Mono',monospace;font-size:.67rem;color:var(--txt2);line-height:1.75}
.ce b{color:var(--txt)}
code{font-family:'JetBrains Mono',monospace;background:var(--code);border:1px solid var(--bd2);padding:1px 5px;border-radius:3px;font-size:.8em}

/* ══ SYSTEM ══ */
.syl{display:flex;flex-direction:column;gap:.8rem}
.sy{background:var(--card);border:1px solid var(--bd2);border-radius:12px;padding:1.1rem 1.3rem;display:flex;align-items:flex-start;gap:.95rem;transition:all .2s}
.sy:hover{border-color:var(--bd);box-shadow:0 4px 18px var(--glow);transform:translateX(4px)}
.syic{width:38px;height:38px;border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:.95rem;flex-shrink:0}
.sy h4{font-family:'Outfit',sans-serif;font-weight:700;font-size:.88rem;margin-bottom:3px}
.sy p{font-size:.79rem;color:var(--txt2);line-height:1.54}

/* ══ ABOUT ══ */
.abanner{background:linear-gradient(135deg,var(--card2),var(--glow));border:1px solid var(--bd);border-radius:16px;padding:2rem;margin-bottom:1.6rem;position:relative;overflow:hidden}
.abanner::after{content:'';position:absolute;top:-50px;right:-50px;width:180px;height:180px;border-radius:50%;background:var(--glows);filter:blur(55px);pointer-events:none}
.abanner h2{font-family:'Outfit',sans-serif;font-size:1.55rem;font-weight:800;margin-bottom:.8rem;position:relative;z-index:1}
.abanner p{color:var(--txt2);line-height:1.68;max-width:610px;font-size:.87rem;position:relative;z-index:1}
.pills{display:flex;flex-wrap:wrap;gap:5px;margin-top:1.2rem;position:relative;z-index:1}
.pill{display:inline-flex;align-items:center;gap:5px;background:var(--code);border:1px solid var(--bd2);padding:4px 10px;border-radius:5px;font-family:'JetBrains Mono',monospace;font-size:.66rem;font-weight:500;letter-spacing:.2px;color:var(--txt2);transition:all .18s}
.pill:hover{border-color:var(--a);color:var(--a);transform:translateY(-1px)}
.pill i{color:var(--a);font-size:.62rem}

/* ══ KREDIT ══ */
.og{display:flex;flex-wrap:wrap;gap:.85rem;margin-bottom:1.6rem}
.oc{background:var(--card);border:1px solid var(--bd2);border-radius:13px;padding:1.6rem;text-align:center;flex:1;min-width:145px;transition:all .26s;position:relative;overflow:hidden}
.oc::before{content:'';position:absolute;top:0;left:0;right:0;height:1.5px;background:var(--stripe);opacity:.75}
.oc:hover{transform:translateY(-4px);border-color:var(--bd);box-shadow:0 9px 28px var(--glow)}
.oav{width:50px;height:50px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:1.15rem;margin:0 auto .85rem;border:1px solid var(--bd)}
.av1{background:var(--glow);color:var(--a)}.av2{background:rgba(14,165,233,.1);color:var(--a2)}.av3{background:rgba(125,211,252,.08);color:var(--a3)}
.onm{font-family:'Outfit',sans-serif;font-weight:800;font-size:.96rem;margin-bottom:2px}
.orl{font-family:'JetBrains Mono',monospace;font-size:.59rem;letter-spacing:1.5px;text-transform:uppercase;color:var(--txt3);margin-bottom:.85rem}
.tg{display:inline-flex;align-items:center;gap:5px;background:var(--glow);color:var(--a);border:1px solid var(--bd);padding:5px 11px;border-radius:6px;font-family:'JetBrains Mono',monospace;font-size:.68rem;font-weight:600;letter-spacing:.2px;text-decoration:none;transition:all .18s}
.tg:hover{background:var(--a);color:var(--bg)}
.rg{display:flex;flex-wrap:wrap;gap:6px;margin:1rem 0 1.6rem}
.rc{display:inline-flex;align-items:center;gap:6px;background:var(--card2);border:1px solid var(--bd2);padding:5px 12px;border-radius:6px;font-family:'JetBrains Mono',monospace;font-size:.7rem;letter-spacing:.2px;color:var(--txt2);transition:all .16s}
.rc:hover{border-color:var(--bd);color:var(--a)}
.rc::before{content:'◈';color:var(--a);font-size:.62rem}
.tqg{display:grid;grid-template-columns:repeat(auto-fill,minmax(190px,1fr));gap:.85rem}
.tqc{background:var(--card);border:1px solid var(--bd2);border-radius:12px;padding:1.2rem;transition:all .2s}
.tqc:hover{border-color:var(--bd);box-shadow:0 4px 16px var(--glow);transform:translateY(-3px)}
.tqic{width:42px;height:42px;border-radius:11px;display:flex;align-items:center;justify-content:center;font-size:1rem;margin:0 auto .65rem}
.tqc h4{font-family:'Outfit',sans-serif;font-weight:700;font-size:.84rem;margin-bottom:3px;text-align:center}
.tqc p{font-size:.77rem;color:var(--txt2);line-height:1.52;text-align:center}

/* ══ NOTE ══ */
.note{display:flex;gap:9px;align-items:flex-start;background:var(--glow);border:1px solid var(--bd);border-radius:9px;padding:.9rem 1rem;margin-top:1.2rem;font-family:'JetBrains Mono',monospace;font-size:.69rem;color:var(--a);line-height:1.7}
.note i{flex-shrink:0;margin-top:1px}

/* ══ FOOTER ══ */
footer{border-top:1px solid var(--bd2);padding:1.6rem 1.1rem;text-align:center;font-family:'JetBrains Mono',monospace;font-size:.62rem;letter-spacing:1.5px;text-transform:uppercase;color:var(--txt3);position:relative;z-index:1}
.fb{display:flex;align-items:center;gap:7px;justify-content:center;margin-bottom:.5rem}
.fb img{width:21px;height:21px;border-radius:6px;object-fit:cover}
.fb strong{font-family:'Outfit',sans-serif;font-weight:800;font-size:.8rem;letter-spacing:2px;color:var(--txt)}

/* ══ MOBILE ══ */
@media(max-width:580px){
  .hero-w{padding:2rem .9rem .9rem}
  .wrap{padding:1.8rem .9rem 3.5rem}
  h1.htitle{font-size:2.1rem;letter-spacing:-.3px}
  .hsub{font-size:.84rem}
  .btn{padding:8px 14px;font-size:.8rem}
  .fg,.cg{grid-template-columns:1fr}
  .og{flex-direction:column}
  .stats{gap:1.3rem}
  .pal-pop{right:.7rem;left:.7rem;width:auto}
}
</style>
</head>
<body>

<!-- LOADING -->
<div id="ls">
  <div class="ls-r">
    <img class="ls-logo" src="https://o.uguu.se/bCEXWPTO.jpg" alt="Logo" onerror="this.style.display='none'">
  </div>
  <div class="ls-ti">DAMX BLASTER</div>
  <div class="ls-sub">Initializing v4.0...</div>
  <div class="ls-bar"><div class="ls-fill" id="lsFill"></div></div>
</div>

<!-- NAV -->
<nav>
  <a class="nav-brand" href="#">
    <img class="nav-logo" src="https://o.uguu.se/bCEXWPTO.jpg" alt="Logo" onerror="this.style.display='none'">
    <span class="nav-nm">DAMX <span>BLASTER</span></span>
  </a>
  <div class="nav-sc">
    <div class="nav-links">
      <a class="nl active" data-page="home">Home</a>
      <a class="nl" data-page="commands">Commands</a>
      <a class="nl" data-page="system">Sistem</a>
      <a class="nl" data-page="about">Tentang</a>
      <a class="nl" data-page="kredit">Kredit</a>
    </div>
  </div>
  <button class="pal-btn" id="palBtn" title="Tukar Tema"><i class="fa-solid fa-swatchbook"></i></button>
</nav>

<!-- TEMA POPUP -->
<div class="pal-pop" id="palPop">
  <div class="pal-lb">// Pilih Tema</div>

  <div class="t-opt sel" data-theme="ocean">
    <div class="t-dots">
      <div class="t-dot" style="background:#38BDF8"></div>
      <div class="t-dot" style="background:#0EA5E9"></div>
      <div class="t-dot" style="background:#7DD3FC"></div>
    </div>
    <div>
      <div class="t-nm">🌊 Ocean</div>
      <div class="t-sb">Biru muda · Biru tua</div>
    </div>
  </div>

</div>
<!-- END POPUP -->

<div class="app">

<!-- ══════════ HOME ══════════ -->
<div id="home-page" class="page active-page">
  <div class="hero-w">
    <div>
      <div class="badge"><div class="bdot"></div> WhatsApp Broadcast Bot &nbsp;·&nbsp; v4.0</div>
      <h1 class="htitle">Damx<br><span class="gtxt">Broadcast</span><br>Automatik Bot</h1>
      <p class="hsub">Sistem broadcast WhatsApp profesional dengan real-time tracking, auto retry engine 3-lapisan, dan panel seller-customer terintegrasi untuk agensi digital.</p>
      <div class="btns">
        <button class="btn bp" id="goCmds"><i class="fa-solid fa-terminal"></i> Lihat Commands</button>
        <button class="btn bs" id="goSys"><i class="fa-solid fa-microchip"></i> Seni Bina</button>
      </div>
      <div class="stats">
        <div><div class="sn">786+</div><div class="sl">Kumpulan / Batch</div></div>
        <div class="sdiv"></div>
        <div><div class="sn">v4.0</div><div class="sl">Versi Semasa</div></div>
        <div class="sdiv"></div>
        <div><div class="sn">24/7</div><div class="sl">Uptime Engine</div></div>
      </div>
    </div>
    <div class="hero-cards">
      <div class="mc"><div class="mctag mt3">✦ SELESAI</div><div class="mcti">Broadcast Berjaya</div><div class="mcsb">779 / 786 kumpulan terhantar</div><div class="mcbar"><div class="mcfill" style="width:96%"></div></div></div>
      <div class="mc"><div class="mctag mt1">⏱ ETA</div><div class="mcti">Masa Tinggal: 18s</div><div class="mcsb">Batch 3/3 aktif · FAST mode</div><div class="mcbar"><div class="mcfill" style="width:72%"></div></div></div>
      <div class="mc"><div class="mctag mt2">🔄 AUTO RETRY</div><div class="mcti">7 kumpulan gagal</div><div class="mcsb">Cuba semula dalam 30s</div></div>
    </div>
  </div>

  <div class="wrap" style="padding-top:.8rem">
    <div class="sh"><div class="stag">Ciri-ciri Utama</div><h2>Kenapa DAMX BLASTER?</h2></div>
    <div class="fg">
      <div class="fc"><div class="fi fi1"><i class="fa-solid fa-tower-broadcast"></i></div><div class="fti">Broadcast Selari</div><div class="fd">Concurrent batch engine — hantar ke ratusan kumpulan serentak dengan laporan progres, ETA, dan statistik masa nyata terus dalam WhatsApp.</div></div>
      <div class="fc"><div class="fi fi2"><i class="fa-solid fa-arrows-rotate"></i></div><div class="fti">Auto Retry 3-Lapisan</div><div class="fd">Per-kumpulan backoff semasa broadcast, retry automatik pasca-broadcast, dan retry manual dengan <code>.retrybc</code>. Tiada kumpulan tertinggal.</div></div>
      <div class="fc"><div class="fi fi3"><i class="fa-solid fa-chart-column"></i></div><div class="fti">Real-time Tracker</div><div class="fd">Pantau progres, ETA, berjaya/gagal, dan 10 rekod history broadcast. Semua visible terus dalam WhatsApp.</div></div>
      <div class="fc"><div class="fi fi1"><i class="fa-solid fa-clock"></i></div><div class="fti">Cron Scheduler</div><div class="fd">Jadual broadcast pada masa tertentu dengan <code>.bcgcsmart</code>. Tetapkan waktu, bot broadcast automatik bila masa tiba. 24/7.</div></div>
      <div class="fc"><div class="fi fi2"><i class="fa-solid fa-shield-halved"></i></div><div class="fti">Blacklist Dinamik</div><div class="fd">Urus blacklist kumpulan secara fleksibel — tambah/buang mengikut nombor index atau JID. Tersimpan kekal, dikecualikan dari semua broadcast.</div></div>
      <div class="fc"><div class="fi fi3"><i class="fa-solid fa-bolt"></i></div><div class="fti">Mod FAST / BRUTAL</div><div class="fd">FAST: 20 batch, 3 concurrent, timeout 8s — kestabilan tinggi. BRUTAL: 35 batch, 5 concurrent, timeout 5s — kelajuan maksimum. Tukar dalam config.</div></div>
    </div>
  </div>
</div>

<!-- ══════════ COMMANDS ══════════ -->
<div id="commands-page" class="page">
  <div class="wrap">
    <div class="sh">
      <div class="stag">Command Library</div>
      <h2>Senarai Arahan Bot</h2>
      <p>Prefix: <code>.</code> atau <code>#</code> &nbsp;·&nbsp; Semua command beri feedback real-time dalam WhatsApp. Versi 4.0.</p>
    </div>
    <div class="cmd-tabs">
      <div class="ctab active" data-filter="all">Semua</div>
      <div class="ctab" data-filter="broadcast">Broadcast</div>
      <div class="ctab" data-filter="auto">Auto</div>
      <div class="ctab" data-filter="pengurusan">Pengurusan</div>
      <div class="ctab" data-filter="utiliti">Utiliti</div>
    </div>
    <div class="cg" id="cg">

      <div class="cc s1" data-cat="broadcast">
        <div class="ch"><div class="cn">.bcgc</div><span class="ccat ca">Broadcast</span></div>
        <p class="cd">Broadcast ke <strong style="color:var(--txt)">semua kumpulan</strong> — teks, gambar, atau video. Concurrent batch dengan laporan progres, ETA, statistik berjaya/gagal masa nyata. Mode: FAST / BRUTAL.</p>
        <div class="ce"><b>Reply mesej →</b> .bcgc<br><b>Teks terus →</b> .bcgc Teks promosi anda<br><b>Status →</b> .bcgc status</div>
      </div>

      <div class="cc s2" data-cat="broadcast">
        <div class="ch"><div class="cn">.bcgccustom</div><span class="ccat cb">Terpilih</span></div>
        <p class="cd">Broadcast ke <strong style="color:var(--txt)">N kumpulan rawak</strong> dari senarai. Bot pilih secara rawak ikut jumlah ditetapkan. Kumpulan blacklisted dikecualikan automatik.</p>
        <div class="ce"><b>N kumpulan →</b> .bcgccustom 40<br><b>Dengan teks →</b> .bcgccustom 40 Teks promo<br><b>Reply mesej →</b> .bcgccustom 40 (reply)<br><b>Semak list →</b> .bcgccustom list</div>
      </div>

      <div class="cc s3" data-cat="broadcast">
        <div class="ch"><div class="cn">.bcgcsmart</div><span class="ccat cc2">Berjadual</span></div>
        <p class="cd">Broadcast <strong style="color:var(--txt)">berjadual pada masa tertentu</strong> menggunakan node-cron. Set waktu dalam format 24-jam, bot broadcast automatik bila masa tiba. Boleh berbilang jadual.</p>
        <div class="ce"><b>Tetap masa →</b> .bcgcsmart 14:30<br><b>Dengan teks →</b> .bcgcsmart 09:00 Teks<br><b>Papar jadual →</b> .bcgcsmart list<br><b>Batal →</b> .bcgcsmart cancel</div>
      </div>

      <div class="cc s1" data-cat="broadcast">
        <div class="ch"><div class="cn">.retrybc</div><span class="ccat ca">Retry</span></div>
        <p class="cd">Retry lapisan ke-3 — cuba semula broadcast yang <strong style="color:var(--txt)">gagal</strong> kepada kumpulan dalam retry log. Reply mesej asal untuk hantar semula kandungan sama.</p>
        <div class="ce"><b>Retry →</b> .retrybc (reply mesej asal)<br><b>Senarai gagal →</b> .retrybc list<br><b>Kosongkan log →</b> .retrybc clear</div>
      </div>

      <div class="cc s2" data-cat="broadcast">
        <div class="ch"><div class="cn">.pushkontak</div><span class="ccat cb">Personal</span></div>
        <p class="cd">Hantar mesej secara <strong style="color:var(--txt)">peribadi</strong> kepada semua ahli dalam kumpulan tertentu. Gunakan nombor index dari <code>.listgc</code>. Concurrent batch dengan retry.</p>
        <div class="ce"><b>Guna →</b> .pushkontak 2<br><b>Reply mesej →</b> .pushkontak 2 (reply)</div>
      </div>

      <div class="cc s3" data-cat="auto">
        <div class="ch"><div class="cn">.autobcgc</div><span class="ccat cc2">Auto Loop</span></div>
        <p class="cd">Broadcast <strong style="color:var(--txt)">automatik berulang</strong> mengikut selang masa. Jeda, hidetag, dan bilangan putaran boleh dikonfigurasi. Auto-restart selepas setiap putaran.</p>
        <div class="ce"><b>Hidupkan →</b> .autobcgc on (reply mesej)<br><b>Matikan →</b> .autobcgc off<br><b>Status →</b> .ping</div>
      </div>

      <div class="cc s1" data-cat="auto">
        <div class="ch"><div class="cn">.setjeda</div><span class="ccat ca">Konfigurasi</span></div>
        <p class="cd">Ubah <strong style="color:var(--txt)">jeda putaran AutoBCGC</strong>. Sokong unit saat (s), minit (m), dan jam (h). Minimum 1 minit, maksimum 24 jam. Jeda baru guna pada putaran seterusnya.</p>
        <div class="ce"><b>30 minit →</b> .setjeda 30m<br><b>1 jam →</b> .setjeda 1h<br><b>90 saat →</b> .setjeda 90s<br><b>1.5 jam →</b> .setjeda 1.5h</div>
      </div>

      <div class="cc s2" data-cat="auto">
        <div class="ch"><div class="cn">.autoreply</div><span class="ccat cb">Auto</span></div>
        <p class="cd">Balas mesej private secara <strong style="color:var(--txt)">automatik</strong>. Bot balas sekali sahaja bagi setiap pengguna per sesi. Set teks, aktif/nyahaktif bila-bila masa.</p>
        <div class="ce"><b>Aktifkan →</b> .autoreply on<br><b>Nyahaktif →</b> .autoreply off<br><b>Set teks →</b> .autoreply set Teks anda<br><b>Status →</b> .autoreply status<br><b>Reset →</b> .autoreply clear</div>
      </div>

      <div class="cc s3" data-cat="pengurusan">
        <div class="ch"><div class="cn">.listgc</div><span class="ccat cc2">Pengurusan</span></div>
        <p class="cd">Papar <strong style="color:var(--txt)">semua kumpulan</strong> — index, nama, jumlah ahli, status terbuka/tertutup, dan tag blacklist. Senarai diisih automatik mengikut saiz ahli (terbesar dahulu).</p>
        <div class="ce"><b>Guna →</b> .listgc</div>
      </div>

      <div class="cc s1" data-cat="pengurusan">
        <div class="ch"><div class="cn">.blbcgc</div><span class="ccat ca">Blacklist</span></div>
        <p class="cd">Urus <strong style="color:var(--txt)">blacklist kumpulan</strong> broadcast. Tambah menggunakan nombor index, JID penuh, atau gabungan kedua-dua. Blacklist tersimpan kekal dalam JSON.</p>
        <div class="ce"><b>Tambah (index) →</b> .blbcgc 2,5<br><b>Tambah (JID) →</b> .blbcgc 120363xxx@g.us<br><b>Gabung →</b> .blbcgc 1,120363xxx@g.us<br><b>Buang →</b> .blbcgc remove 2<br><b>Senarai →</b> .blbcgc list</div>
      </div>

      <div class="cc s2" data-cat="utiliti">
        <div class="ch"><div class="cn">.autojoin</div><span class="ccat cb">Utiliti</span></div>
        <p class="cd">Auto join ke <strong style="color:var(--txt)">N kumpulan</strong> menggunakan link dari database <code>data_grub.json</code>. Masukkan jumlah kumpulan yang ingin disertai.</p>
        <div class="ce"><b>Join 3 kumpulan →</b> .autojoin 3</div>
      </div>

      <div class="cc s3" data-cat="utiliti">
        <div class="ch"><div class="cn">.getlink</div><span class="ccat cc2">Eksport</span></div>
        <p class="cd">Ekstrak semua <strong style="color:var(--txt)">link kumpulan</strong> dari database <code>data_grub.json</code> dan eksport ke fail <code>.txt</code>. Bot hantar fail terus ke WhatsApp.</p>
        <div class="ce"><b>Eksport fail →</b> .getlink file</div>
      </div>

      <div class="cc s1" data-cat="utiliti">
        <div class="ch"><div class="cn">.backup</div><span class="ccat ca">Backup</span></div>
        <p class="cd">Backup <strong style="color:var(--txt)">penuh sistem</strong> — plugins, lib, database, blacklist, config, index kumpulan. Bot zip dan hantar fail <code>.zip</code> terus ke WhatsApp.</p>
        <div class="ce"><b>Guna →</b> .backup</div>
      </div>

      <div class="cc s2" data-cat="utiliti">
        <div class="ch"><div class="cn">.ping</div><span class="ccat cb">Dashboard</span></div>
        <p class="cd">Dashboard penuh sistem — uptime, response time, RAM usage, CPU cores, jumlah kumpulan (terbuka/tertutup/blacklist/aktif), status AutoBCGC, Auto Reply, prefix, dan jeda BC.</p>
        <div class="ce"><b>Guna →</b> .ping</div>
      </div>

      <div class="cc s3" data-cat="utiliti">
        <div class="ch"><div class="cn">.x</div><span class="ccat cc2">History</span></div>
        <p class="cd">Papar <strong style="color:var(--txt)">10 rekod broadcast terkini</strong> — tarikh, preview teks, statistik berjaya/gagal, kadar kejayaan (%), dan masa durasi setiap sesi.</p>
        <div class="ce"><b>Lihat rekod →</b> .x<br><b>Padam semua →</b> .x clear</div>
      </div>

      <div class="cc s1" data-cat="utiliti">
        <div class="ch"><div class="cn">.restart</div><span class="ccat ca">Sistem</span></div>
        <p class="cd">Restart bot dengan <strong style="color:var(--txt)">pengesahan 2-langkah</strong>. Bot stop semua proses aktif, disconnect WhatsApp, dan reconnect semula dalam 3 saat.</p>
        <div class="ce"><b>Minta restart →</b> .restart<br><b>Sahkan →</b> .restart yes<br><b>Batal →</b> .restart no</div>
      </div>

      <div class="cc s2" data-cat="utiliti">
        <div class="ch"><div class="cn">.tqto</div><span class="ccat cb">Kredit</span></div>
        <p class="cd">Papar <strong style="color:var(--txt)">penghargaan</strong> kepada semua pihak — owner, reseller, dan buyer. Disertakan gambar banner dari catbox.</p>
        <div class="ce"><b>Guna →</b> .tqto</div>
      </div>

      <div class="cc s3" data-cat="utiliti">
        <div class="ch"><div class="cn">.menu</div><span class="ccat cc2">Info</span></div>
        <p class="cd">Papar <strong style="color:var(--txt)">menu bot</strong> lengkap — info versi, owner, bahasa, dan senarai semua command. Disertakan audio signature <code>d4mxor.mp3</code>.</p>
        <div class="ce"><b>Guna →</b> .menu</div>
      </div>

    </div>
    <div class="note">
      <i class="fa-solid fa-circle-info"></i>
      <div><strong>Contoh Sesi:</strong> .bcgc + reply gambar → 48 kumpulan, 3 batch concurrent → ETA ~25s → Berjaya 46, gagal 2 → Auto-retry lapisan 2 → .retrybc jika masih gagal.</div>
    </div>
  </div>
</div>

<!-- ══════════ SISTEM ══════════ -->
<div id="system-page" class="page">
  <div class="wrap">
    <div class="sh"><div class="stag">Infrastruktur</div><h2>Seni Bina Sistem</h2><p>Concurrent batch engine, retry 3-lapisan, JSON storage dengan atomic write, dan cron scheduler untuk broadcast berjadual.</p></div>
    <div class="syl">
      <div class="sy"><div class="syic fi1"><i class="fa-solid fa-layer-group"></i></div><div><h4>Concurrent Batch Engine</h4><p>FAST: 20 kumpulan/batch, 3 batch concurrent, timeout 8s, jitter 200ms. BRUTAL: 35/batch, 5 concurrent, timeout 5s, jitter 80ms. Setiap batch selari dengan delay automatik untuk elak flood WhatsApp.</p></div></div>
      <div class="sy"><div class="syic fi2"><i class="fa-solid fa-arrows-rotate"></i></div><div><h4>Retry Engine 3-Lapisan</h4><p>Lapisan 1: per-kumpulan backoff semasa broadcast (2 retries, 3000ms). Lapisan 2: retry automatik pasca-broadcast kepada semua yang gagal. Lapisan 3: retry manual dengan .retrybc. Retry log tersimpan dalam JSON.</p></div></div>
      <div class="sy"><div class="syic fi3"><i class="fa-solid fa-database"></i></div><div><h4>JSON Storage + Atomic Write</h4><p>Semua data disimpan dalam JSON — blacklist, group index, retry log, history broadcast, autobcgc status, autoreply config. Atomic write dengan backup sebelum simpan untuk elak korupsi data.</p></div></div>
      <div class="sy"><div class="syic fi1"><i class="fa-solid fa-clock"></i></div><div><h4>Cron Scheduler (bcgcsmart)</h4><p>Broadcast berjadual menggunakan node-cron. Tetapkan masa dalam format 24-jam, bot broadcast automatik. Boleh set berbilang jadual serentak. Jadual tersimpan dalam <code>bcgcsmart.json</code>.</p></div></div>
      <div class="sy"><div class="syic fi2"><i class="fa-solid fa-shield-halved"></i></div><div><h4>Whitelist & Blacklist Dinamik</h4><p>Blacklist tersimpan kekal dalam JSON. Tambah/buang mengikut nombor index dari .listgc, JID penuh, atau gabungan. Dikecualikan automatik dari semua jenis broadcast termasuk bcgccustom dan autobcgc.</p></div></div>
      <div class="sy"><div class="syic fi3"><i class="fa-solid fa-chart-line"></i></div><div><h4>Broadcast Tracker & History</h4><p>Rekod setiap sesi broadcast — tarikh, preview kandungan, total/berjaya/gagal, kadar kejayaan (%), durasi. 10 rekod terkini boleh disemak dengan .x. History boleh dipadam bila-bila masa.</p></div></div>
      <div class="sy"><div class="syic fi1"><i class="fa-solid fa-bolt"></i></div><div><h4>Mod FAST / BRUTAL</h4><p>Boleh ditukar dalam <code>config.js</code> tanpa restart. FAST: kestabilan tinggi untuk penggunaan harian. BRUTAL: kelajuan maksimum untuk keperluan urgent. Setiap plugin ada konfigurasi mod tersendiri.</p></div></div>
      <div class="sy"><div class="syic fi2"><i class="fa-solid fa-reply"></i></div><div><h4>Auto Reply (Private)</h4><p>Bot balas mesej private secara automatik dengan teks yang ditetapkan. Setiap pengguna hanya terima satu reply per sesi untuk elak spam. Boleh reset senarai dengan .autoreply clear.</p></div></div>
    </div>
  </div>
</div>

<!-- ══════════ TENTANG ══════════ -->
<div id="about-page" class="page">
  <div class="wrap">
    <div class="sh"><div class="stag">Tentang Produk</div><h2>DAMX BLASTER V4.0</h2></div>
    <div class="abanner">
      <h2>Bot WhatsApp Broadcast Premium 🚀</h2>
      <p>DAMX BLASTER adalah bot WhatsApp premium untuk broadcast masif dan automasi pemasaran digital. Dibina dengan Baileys (Node.js ESM) dan digunakan oleh agensi, reseller, dan pengurus komuniti di seluruh Malaysia.</p>
      <p style="margin-top:.7rem">Sesuai untuk pengurusan ratusan kumpulan dengan kestabilan tinggi. Dilengkapi mod FAST dan BRUTAL, sistem retry 3-lapisan, cron scheduler, dan anti-flood dengan jitter delay automatik.</p>
      <div class="pills">
        <div class="pill"><i class="fa-solid fa-check"></i> Broadcast Berjadual (bcgcsmart)</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Laporan Real-time</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Retry 3-Lapisan</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Panel Seller Terkawal</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Blacklist Dinamik</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Push Kontak Personal</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Auto Join Kumpulan</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Eksport Link & Data</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Auto Reply Private</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Backup Sistem Penuh</div>
        <div class="pill"><i class="fa-solid fa-check"></i> History Broadcast</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Mod Fast / Brutal</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Atomic Write Storage</div>
        <div class="pill"><i class="fa-solid fa-check"></i> Concurrent Batch Engine</div>
      </div>
    </div>
    <div class="fg">
      <div class="fc"><div class="fi fi1"><i class="fa-solid fa-rocket"></i></div><div class="fti">Kelajuan Tinggi</div><div class="fd">Concurrent batch engine — penghantaran ke ratusan kumpulan dalam masa singkat dengan jitter delay untuk kestabilan maksimum.</div></div>
      <div class="fc"><div class="fi fi2"><i class="fa-solid fa-lock"></i></div><div class="fti">Stabil & Selamat</div><div class="fd">Kawalan anti-flood terbina, jitter delay boleh dikonfigurasi, dan mod sesuai untuk keperluan berbeza.</div></div>
      <div class="fc"><div class="fi fi3"><i class="fa-solid fa-gears"></i></div><div class="fti">Mudah Dikonfigurasi</div><div class="fd">Jeda, mod, hidetag boleh diubah terus dari WhatsApp dengan command. Tanpa perlu edit config secara manual.</div></div>
      <div class="fc"><div class="fi fi1"><i class="fa-brands fa-node-js"></i></div><div class="fti">Node.js ESM + Baileys</div><div class="fd">Dibina dengan ESM Node.js dan Baileys untuk sambungan WhatsApp stabil. Atomic write protection untuk semua storage.</div></div>
    </div>
  </div>
</div>

<!-- ══════════ KREDIT ══════════ -->
<div id="kredit-page" class="page">
  <div class="wrap">
    <div class="sh"><div class="stag">Pasukan & Komuniti</div><h2>Penghargaan & Pemilik</h2><p>Dibangunkan oleh pasukan berdedikasi dan disokong oleh komuniti reseller serta pembeli setia.</p></div>

    <div class="og">
      <div class="oc"><div class="oav av1"><i class="fa-solid fa-crown"></i></div><div class="onm">DAMX</div><div class="orl">Pengasas / Dev</div><a href="https://t.me/D4mxorx" target="_blank" class="tg"><i class="fa-brands fa-telegram"></i> @D4mxorx</a></div>
      <div class="oc"><div class="oav av2"><i class="fa-solid fa-user-tie"></i></div><div class="onm">SHAH</div><div class="orl">Pemilik Blaster</div><a href="https://t.me/Shahoffcial" target="_blank" class="tg"><i class="fa-brands fa-telegram"></i> @Shahoffcial</a></div>
      <div class="oc"><div class="oav av3"><i class="fa-solid fa-code"></i></div><div class="onm">NISH</div><div class="orl">Owner Blaster</div><a href="https://t.me/NishOnlyyy" target="_blank" class="tg"><i class="fa-brands fa-telegram"></i> @NishOnlyyy</a></div>
    </div>

    <div class="sh" style="margin-top:1.8rem"><div class="stag">Reseller & Sokongan</div><h2>Thanks To</h2></div>
    <div class="rg">
      <div class="rc">Fanzz <span style="color:var(--txt3);font-size:.63rem;margin-left:4px">Reseller</span></div>
      <div class="rc">Cokiz <span style="color:var(--txt3);font-size:.63rem;margin-left:4px">Reseller</span></div>
      <div class="rc">Yik Fann <span style="color:var(--txt3);font-size:.63rem;margin-left:4px">Reseller</span></div>
      <div class="rc">Fiquee <span style="color:var(--txt3);font-size:.63rem;margin-left:4px">Reseller</span></div>
      <div class="rc">Hamzuki <span style="color:var(--txt3);font-size:.63rem;margin-left:4px">Reseller</span></div>
      <div class="rc">Mih <span style="color:var(--txt3);font-size:.63rem;margin-left:4px">Reseller</span></div>
      <div class="rc">All Buyer <span style="color:var(--txt3);font-size:.63rem;margin-left:4px">Pembeli</span></div>
      <div class="rc">All Support <span style="color:var(--txt3);font-size:.63rem;margin-left:4px">Sokongan</span></div>
    </div>
    <div class="tqg">
      <div class="tqc"><div class="tqic fi1"><i class="fa-solid fa-handshake"></i></div><h4>Semua Reseller</h4><p>Terima kasih atas kepercayaan dan pengembangan ekosistem DAMX BLASTER.</p></div>
      <div class="tqc"><div class="tqic fi2"><i class="fa-solid fa-users"></i></div><h4>Semua Pembeli</h4><p>Setiap sokongan anda menjadikan DAMX BLASTER semakin berkembang dan stabil.</p></div>
      <div class="tqc"><div class="tqic fi3"><i class="fa-brands fa-telegram"></i></div><h4>Hubungi Kami</h4><p>Hubungi owner untuk lesen, sokongan teknikal, atau maklumat lanjut produk.</p></div>
    </div>
  </div>
</div>

<footer>
  <div class="fb">
    <img src="https://o.uguu.se/bCEXWPTO.jpg" alt="Logo" onerror="this.style.display='none'">
    <strong>DAMX BLASTER V4</strong>
  </div>
  SECURE PROFESSIONAL SYSTEM &nbsp;·&nbsp; 2025 © ALL RIGHTS RESERVED
</footer>

</div><!-- .app -->

<script>
/* LOADING */
let p=0;const f=document.getElementById('lsFill'),ls=document.getElementById('ls');
const t=setInterval(()=>{p+=Math.floor(Math.random()*11)+4;if(p>100)p=100;f.style.width=p+'%'},115);
setTimeout(()=>{clearInterval(t);f.style.width='100%';setTimeout(()=>{ls.style.opacity='0';ls.style.pointerEvents='none';setTimeout(()=>ls.style.display='none',700)},280)},1850);

/* PAGES */
const PG=['home','commands','system','about','kredit'];
function show(id){
  PG.forEach(p=>document.getElementById(p+'-page')?.classList.remove('active-page'));
  document.getElementById(id+'-page')?.classList.add('active-page');
  document.querySelectorAll('.nl').forEach(a=>a.classList.toggle('active',a.dataset.page===id));
  const al=document.querySelector('.nl.active');
  if(al)al.scrollIntoView({behavior:'smooth',block:'nearest',inline:'center'});
  window.scrollTo({top:0,behavior:'smooth'});
}
document.querySelectorAll('.nl').forEach(a=>a.addEventListener('click',e=>{e.preventDefault();show(a.dataset.page)}));
document.getElementById('goCmds')?.addEventListener('click',()=>show('commands'));
document.getElementById('goSys')?.addEventListener('click',()=>show('system'));

/* TEMA */
const pb=document.getElementById('palBtn'),pp=document.getElementById('palPop');
pb.addEventListener('click',e=>{e.stopPropagation();pp.classList.toggle('open')});
document.addEventListener('click',()=>pp.classList.remove('open'));
pp.addEventListener('click',e=>e.stopPropagation());
document.querySelectorAll('.t-opt').forEach(o=>{
  o.addEventListener('click',()=>{
    const th=o.dataset.theme;
    document.documentElement.dataset.theme=th==='ocean'?'':th;
    document.querySelectorAll('.t-opt').forEach(x=>x.classList.remove('sel'));
    o.classList.add('sel');pp.classList.remove('open');
  });
});

/* CMD FILTER */
document.querySelectorAll('.ctab').forEach(tab=>{
  tab.addEventListener('click',()=>{
    document.querySelectorAll('.ctab').forEach(t=>t.classList.remove('active'));
    tab.classList.add('active');
    const fl=tab.dataset.filter;
    document.querySelectorAll('#cg .cc').forEach(c=>{
      c.style.display=(fl==='all'||c.dataset.cat===fl)?'':'none';
    });
  });
});

</script>
</body>
</html>
