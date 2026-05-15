<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chronicles of Aethoria - RPG</title>
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
<style>
/* ===== RESET & VARS ===== */
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#07070f;--bg2:#0e0e1c;--bg3:#14142a;
  --panel:#0c0c20;--panel2:#10101e;
  --gold:#e8b84b;--gold2:#a07828;--gold3:#ffd700;
  --red:#c0392b;--red2:#e74c3c;--red3:#ff6b6b;
  --blue:#2980b9;--blue2:#3498db;
  --green:#27ae60;--green2:#2ecc71;
  --purple:#8e44ad;--purple2:#9b59b6;
  --gray:#7f8c8d;--gray2:#95a5a6;
  --text:#ddd8c0;--text2:#9a9080;--text3:#5a5040;
  --border:#1e1e18;--border2:#3a3020;--border3:#5a4828;
}

body{
  background:var(--bg);color:var(--text);
  font-family:'Press Start 2P',monospace;
  font-size:9px;line-height:1.6;
  min-height:100vh;overflow-x:hidden;
}

/* ===== SCREENS ===== */
.screen{display:none;animation:fadeIn 0.4s ease}
.screen.active{display:flex}
@keyframes fadeIn{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:translateY(0)}}

/* ===== TITLE ===== */
#title{
  flex-direction:column;align-items:center;justify-content:center;
  min-height:100vh;text-align:center;padding:30px 20px;
  background:radial-gradient(ellipse at 50% 40%,#14103a 0%,#07070f 65%);
}
.logo{
  font-size:clamp(14px,4.5vw,30px);color:var(--gold);
  text-shadow:0 0 40px rgba(232,184,75,0.55);
  letter-spacing:4px;margin-bottom:8px;
}
.logo-sub{
  font-size:clamp(6px,1.5vw,9px);color:var(--text2);
  letter-spacing:6px;margin-bottom:40px;
}
.title-deco{font-size:clamp(28px,8vw,60px);margin:14px 0;line-height:1.2}
.title-stars{color:var(--text3);font-size:8px;letter-spacing:4px;margin:10px 0 26px}
.title-story{
  color:var(--text2);font-size:8px;line-height:2.4;
  max-width:380px;margin-bottom:34px;
}

/* ===== BUTTONS ===== */
.btn{
  display:inline-block;padding:12px 22px;
  background:transparent;border:2px solid currentColor;
  font-family:'Press Start 2P',monospace;font-size:8px;
  cursor:pointer;letter-spacing:2px;transition:all 0.15s;
  text-transform:uppercase;margin:4px;
}
.btn:hover{filter:brightness(1.25);transform:translateY(-1px)}
.btn:active{transform:translateY(1px);filter:brightness(0.9)}
.btn:disabled{opacity:0.25;cursor:not-allowed;transform:none!important;filter:none!important}
.btn-gold{color:var(--gold)}
.btn-gold:hover{background:rgba(232,184,75,0.18);box-shadow:0 0 18px rgba(232,184,75,0.3)}
.btn-red{color:var(--red2)}
.btn-red:hover{background:rgba(231,76,60,0.18);box-shadow:0 0 18px rgba(231,76,60,0.3)}
.btn-blue{color:var(--blue2)}
.btn-blue:hover{background:rgba(52,152,219,0.18);box-shadow:0 0 18px rgba(52,152,219,0.3)}
.btn-green{color:var(--green2)}
.btn-green:hover{background:rgba(46,204,113,0.18)}
.btn-purple{color:var(--purple2)}
.btn-purple:hover{background:rgba(155,89,182,0.18)}
.btn-gray{color:var(--gray2)}
.btn-gray:hover{background:rgba(149,165,166,0.18)}
.btn-sm{padding:8px 14px;font-size:7px}

/* ===== STAT BARS ===== */
.bar{width:80px;height:10px;background:var(--border2);border:1px solid var(--border2);position:relative;overflow:hidden}
.bar-fill{height:100%;transition:width 0.35s ease;position:absolute;top:0;left:0}
.bar-hp .bar-fill{background:var(--red2)}
.bar-mp .bar-fill{background:var(--blue2)}
.bar-exp .bar-fill{background:var(--purple2)}

/* ===== EXPLORE SCREEN ===== */
#explore{flex-direction:column;min-height:100vh;background:var(--bg)}

.topbar{
  display:flex;align-items:center;justify-content:space-between;
  padding:8px 16px;background:var(--bg2);
  border-bottom:2px solid var(--border2);flex-shrink:0;
}
.topbar-title{color:var(--gold);font-size:9px;letter-spacing:3px}
.topbar-info{color:var(--text2);font-size:8px}

.stat-strip{
  display:flex;gap:14px;flex-wrap:wrap;align-items:center;
  padding:8px 16px;background:var(--bg3);
  border-bottom:2px solid var(--border);flex-shrink:0;
}
.si{display:flex;align-items:center;gap:6px}
.si-label{font-size:7px;color:var(--text2)}
.si-val{font-size:8px;color:var(--text);min-width:18px}
.si-num{font-size:7px;color:var(--text2)}

.explore-body{
  display:grid;grid-template-columns:auto 1fr;
  flex:1;overflow:hidden;min-height:0;
}

/* MAP */
.map-panel{
  padding:14px;background:var(--bg2);
  border-right:2px solid var(--border2);
  overflow:auto;flex-shrink:0;
}
.map-label{color:var(--gold);font-size:7px;letter-spacing:3px;margin-bottom:10px}
.map-grid{display:grid;gap:2px}
.cell{
  width:26px;height:26px;display:flex;align-items:center;justify-content:center;
  font-size:12px;background:var(--bg3);border:1px solid var(--border);
  user-select:none;
}
.cell.fog{background:var(--bg);border-color:transparent}
.cell.c-player{background:#12183a;border-color:var(--blue2)}
.cell.c-enemy{background:#2a1010;border-color:var(--red)}
.cell.c-chest{background:#2a2010;border-color:var(--gold2)}
.cell.c-boss{background:#2a0a2a;border-color:var(--purple)}
.cell.c-stairs{background:#0e2a0e;border-color:var(--green)}
.cell.c-empty{background:var(--bg3)}

/* SIDEBAR */
.explore-side{
  display:flex;flex-direction:column;padding:14px;overflow-y:auto;gap:14px;
}

/* DPAD */
.dpad-wrap{display:flex;flex-direction:column;align-items:flex-start;gap:6px}
.dpad-label{font-size:7px;color:var(--text2);letter-spacing:2px}
.dpad{display:grid;grid-template-columns:repeat(3,38px);gap:3px}
.dpad .btn{width:38px;height:38px;padding:0;font-size:13px;display:flex;align-items:center;justify-content:center;margin:0}
.kbd-hint{font-size:7px;color:var(--text3);margin-top:4px}

/* ITEMS (explore) */
.items-wrap{display:flex;flex-direction:column;gap:6px}
.items-label{font-size:7px;color:var(--text2);letter-spacing:2px}
.item-row{display:flex;gap:6px;flex-wrap:wrap}

/* LEGEND */
.legend{font-size:7px;color:var(--text2);line-height:2.2}

/* LOG */
.log-wrap{flex:1;display:flex;flex-direction:column;min-height:0}
.log-label{font-size:7px;color:var(--text2);letter-spacing:2px;margin-bottom:4px}
.log-box{
  flex:1;background:var(--bg2);border:1px solid var(--border2);
  padding:8px;overflow-y:auto;min-height:120px;max-height:220px;
}
.log-entry{padding:2px 0;border-bottom:1px solid var(--border);font-size:7px;color:var(--text2)}
.log-event{color:var(--gold)}
.log-battle{color:var(--red3)}
.log-item{color:var(--green2)}
.log-level{color:var(--purple2)}
.log-ok{color:var(--blue2)}

/* ===== BATTLE SCREEN ===== */
#battle{
  flex-direction:column;min-height:100vh;
  background:var(--bg);padding:14px;gap:12px;
}
.battle-top{
  text-align:center;color:var(--gold);font-size:10px;letter-spacing:4px;
  padding:8px;border-bottom:2px solid var(--border2);flex-shrink:0;
}
.battle-arena{display:grid;grid-template-columns:1fr 1fr;gap:12px;flex-shrink:0}

/* ENEMY CARD */
.enemy-card{
  background:var(--bg2);border:2px solid var(--red);
  padding:14px;text-align:center;
}
.e-name{color:var(--red2);font-size:10px;letter-spacing:2px;margin-bottom:4px}
.e-type{color:var(--text2);font-size:7px;letter-spacing:3px;margin-bottom:10px}
.e-art{font-size:clamp(24px,7vw,52px);margin:8px 0;display:block;animation:bob 2.2s ease-in-out infinite}
@keyframes bob{0%,100%{transform:translateY(0)}50%{transform:translateY(-7px)}}

/* PLAYER CARD */
.player-card{
  background:var(--bg2);border:2px solid var(--blue2);
  padding:14px;
}
.p-name{color:var(--blue2);font-size:10px;letter-spacing:2px;margin-bottom:3px}
.p-lv{color:var(--text2);font-size:7px;letter-spacing:3px;margin-bottom:10px}
.b-stat{display:flex;align-items:center;gap:8px;margin:5px 0}
.b-stat-lbl{font-size:7px;width:24px}
.b-stat-bar{flex:1;height:11px;background:var(--border2);position:relative;overflow:hidden}
.b-stat-fill{height:100%;transition:width 0.35s ease;position:absolute;top:0;left:0}
.bhp{background:var(--red2)}
.bmp{background:var(--blue2)}
.b-stat-num{font-size:7px;color:var(--text);min-width:66px;text-align:right}
.p-misc{margin-top:10px;font-size:7px;color:var(--text2);line-height:2.2}

/* ACTIONS */
.actions{
  display:grid;grid-template-columns:repeat(3,1fr);gap:7px;
  padding:10px;background:var(--bg3);border:2px solid var(--border2);
  flex-shrink:0;
}
.act-btn{padding:9px 6px;font-size:7px;text-align:center;width:100%;margin:0}
.act-name{display:block;margin-bottom:5px;font-size:8px}
.act-cost{display:block;font-size:6px;color:var(--text2)}

/* BATTLE LOG */
.blog-wrap{flex:1;display:flex;flex-direction:column;min-height:0}
.blog-lbl{font-size:7px;color:var(--text2);letter-spacing:2px;margin-bottom:4px}
.blog-box{
  flex:1;background:var(--bg2);border:1px solid var(--border2);
  padding:8px;overflow-y:auto;min-height:100px;max-height:160px;
}
.blog-entry{padding:2px 0;border-bottom:1px solid var(--border);font-size:7px}
.bt-player{color:var(--blue2)}
.bt-enemy{color:var(--red3)}
.bt-info{color:var(--gold)}
.bt-item{color:var(--green2)}

/* FLASH ANIMATIONS */
.flash-red{animation:fRed 0.45s ease}
.flash-blue{animation:fBlue 0.45s ease}
@keyframes fRed{0%,100%{background:var(--bg2)}50%{background:#3a0a0a}}
@keyframes fBlue{0%,100%{background:var(--bg2)}50%{background:#0a1240}}

/* ===== GAMEOVER / WIN ===== */
#gameover,#win{
  flex-direction:column;align-items:center;justify-content:center;
  min-height:100vh;text-align:center;padding:30px 20px;
}
.go-title{font-size:clamp(14px,4vw,28px);color:var(--red2);margin-bottom:18px;
  text-shadow:0 0 30px rgba(231,76,60,0.6)}
.win-title{font-size:clamp(13px,3.5vw,24px);color:var(--gold);margin-bottom:18px;
  text-shadow:0 0 30px rgba(232,184,75,0.6)}
.res-art{font-size:54px;margin:14px 0}
.res-text{color:var(--text2);font-size:8px;line-height:2.5;margin:16px 0}
.res-hl{color:var(--gold)}

/* ===== LEVEL UP OVERLAY ===== */
#lvl-overlay{
  position:fixed;inset:0;background:rgba(0,0,0,0.82);
  display:none;align-items:center;justify-content:center;z-index:200;
}
#lvl-overlay.show{display:flex}
.lvl-box{
  background:var(--bg2);border:3px solid var(--gold);
  padding:28px 32px;text-align:center;max-width:380px;width:90%;
  animation:lvlPop 0.4s ease;
}
@keyframes lvlPop{from{transform:scale(0.4);opacity:0}to{transform:scale(1);opacity:1}}
.lvl-title{color:var(--gold);font-size:14px;letter-spacing:3px;margin-bottom:18px}
.lvl-gains{color:var(--green2);font-size:8px;line-height:2.8;margin-bottom:18px}

/* ===== SCROLLBAR ===== */
::-webkit-scrollbar{width:5px}
::-webkit-scrollbar-track{background:var(--bg2)}
::-webkit-scrollbar-thumb{background:var(--border2)}

/* ===== RESPONSIVE ===== */
@media(max-width:560px){
  .explore-body{grid-template-columns:1fr}
  .map-panel{display:none}
  .battle-arena{grid-template-columns:1fr}
  .actions{grid-template-columns:repeat(2,1fr)}
}
</style>
</head>
<body>

<!-- ======== TITLE SCREEN ======== -->
<div id="title" class="screen active">
  <div class="logo">⚔ CHRONICLES ⚔</div>
  <div class="logo-sub">OF &nbsp; AETHORIA</div>
  <div class="title-deco">🏰</div>
  <div class="title-stars">✦ &nbsp; ✦ &nbsp; ✦ &nbsp; ✦ &nbsp; ✦</div>
  <p class="title-story">
    Kegelapan menyelimuti negeri Aethoria.<br>
    Raja Iblis Malphas telah bangkit dari neraka.<br>
    Seorang pahlawan pemberani turun ke bawah<br>
    untuk mengakhiri kutukan abadi ini...
  </p>
  <button class="btn btn-gold" onclick="startGame()">▶ &nbsp; MULAI PETUALANGAN</button>
  <p style="color:var(--text3);font-size:7px;margin-top:20px">
    WASD / Arrow Keys untuk bergerak &nbsp;|&nbsp; 1-6 untuk aksi battle
  </p>
</div>

<!-- ======== EXPLORE SCREEN ======== -->
<div id="explore" class="screen">
  <div class="topbar">
    <span class="topbar-title">⚔ LANTAI DUNGEON <span id="floor-num">1</span></span>
    <span class="topbar-info">💰 <span id="gold-disp">0</span> Koin</span>
  </div>

  <div class="stat-strip">
    <div class="si">
      <span class="si-label" style="color:var(--red2)">❤ HP</span>
      <div class="bar bar-hp"><div class="bar-fill" id="e-hp-bar"></div></div>
      <span class="si-num" id="e-hp-txt">100/100</span>
    </div>
    <div class="si">
      <span class="si-label" style="color:var(--blue2)">✦ MP</span>
      <div class="bar bar-mp"><div class="bar-fill" id="e-mp-bar"></div></div>
      <span class="si-num" id="e-mp-txt">50/50</span>
    </div>
    <div class="si">
      <span class="si-label" style="color:var(--purple2)">★ EXP</span>
      <div class="bar bar-exp"><div class="bar-fill" id="e-exp-bar"></div></div>
      <span class="si-num" id="e-exp-txt">0/100</span>
    </div>
    <div class="si">
      <span class="si-label" style="color:var(--gold)">LV</span>
      <span class="si-val" id="e-lv">1</span>
    </div>
    <div class="si">
      <span class="si-label" style="color:var(--text2)">⚔</span>
      <span class="si-val" id="e-atk">15</span>
    </div>
    <div class="si">
      <span class="si-label" style="color:var(--text2)">🛡</span>
      <span class="si-val" id="e-def">8</span>
    </div>
  </div>

  <div class="explore-body">
    <!-- MAP PANEL -->
    <div class="map-panel">
      <div class="map-label">📍 PETA DUNGEON</div>
      <div id="map-grid" class="map-grid"></div>
      <div style="margin-top:10px;font-size:7px;color:var(--text3);line-height:2">
        🧙 Kamu &nbsp; ⚔ Musuh<br>
        💎 Peti &nbsp; 👑 Boss<br>
        🔽 Tangga &nbsp; ▪ Jelajahi
      </div>
    </div>

    <!-- SIDE PANEL -->
    <div class="explore-side">
      <!-- D-PAD -->
      <div class="dpad-wrap">
        <div class="dpad-label">GERAK</div>
        <div class="dpad">
          <div></div>
          <button class="btn btn-gold dpad" id="btn-n" onclick="move(0,-1)">▲</button>
          <div></div>
          <button class="btn btn-gold dpad" id="btn-w" onclick="move(-1,0)">◀</button>
          <button class="btn btn-gray dpad" disabled style="font-size:9px">●</button>
          <button class="btn btn-gold dpad" id="btn-e" onclick="move(1,0)">▶</button>
          <div></div>
          <button class="btn btn-gold dpad" id="btn-s" onclick="move(0,1)">▼</button>
          <div></div>
        </div>
        <div class="kbd-hint">[ WASD / Arrow Keys ]</div>
      </div>

      <!-- ITEMS -->
      <div class="items-wrap">
        <div class="items-label">🎒 ITEM</div>
        <div class="item-row">
          <button class="btn btn-green btn-sm" onclick="useItem('potion')" id="ex-potion">
            ❤ Potion (<span id="ex-pot-n">3</span>)
          </button>
          <button class="btn btn-blue btn-sm" onclick="useItem('mana')" id="ex-mana">
            ✦ Mana (<span id="ex-man-n">2</span>)
          </button>
        </div>
      </div>

      <!-- LOG -->
      <div class="log-wrap">
        <div class="log-label">CATATAN</div>
        <div class="log-box" id="explore-log"></div>
      </div>
    </div>
  </div>
</div>

<!-- ======== BATTLE SCREEN ======== -->
<div id="battle" class="screen">
  <div class="battle-top">⚔ &nbsp; PERTEMPURAN &nbsp; ⚔</div>

  <div class="battle-arena">
    <!-- ENEMY -->
    <div class="enemy-card" id="enemy-card">
      <div class="e-name" id="b-ename">—</div>
      <div class="e-type" id="b-etype">TIPE: ???</div>
      <span class="e-art" id="b-eart">👾</span>
      <div class="b-stat">
        <span class="b-stat-lbl" style="color:var(--red2)">HP</span>
        <div class="b-stat-bar"><div class="b-stat-fill bhp" id="b-ehp-bar"></div></div>
        <span class="b-stat-num" id="b-ehp-num">0/0</span>
      </div>
    </div>

    <!-- PLAYER -->
    <div class="player-card" id="player-card">
      <div class="p-name" id="b-pname">PAHLAWAN</div>
      <div class="p-lv" id="b-plv">LEVEL 1</div>
      <div class="b-stat">
        <span class="b-stat-lbl" style="color:var(--red2)">HP</span>
        <div class="b-stat-bar"><div class="b-stat-fill bhp" id="b-php-bar"></div></div>
        <span class="b-stat-num" id="b-php-num">0/0</span>
      </div>
      <div class="b-stat">
        <span class="b-stat-lbl" style="color:var(--blue2)">MP</span>
        <div class="b-stat-bar"><div class="b-stat-fill bmp" id="b-pmp-bar"></div></div>
        <span class="b-stat-num" id="b-pmp-num">0/0</span>
      </div>
      <div class="p-misc">
        ⚔ ATK: <span id="b-patk">0</span> &nbsp; 🛡 DEF: <span id="b-pdef">0</span><br>
        ❤ Potion: <span id="b-ppot">0</span> &nbsp; ✦ Mana Pot: <span id="b-pman">0</span>
      </div>
    </div>
  </div>

  <!-- ACTIONS -->
  <div class="actions">
    <button class="btn btn-red act-btn" id="ba-atk" onclick="battleAct('attack')">
      <span class="act-name">⚔ SERANG</span>
      <span class="act-cost">[1] Serangan Dasar</span>
    </button>
    <button class="btn btn-gold act-btn" id="ba-fire" onclick="battleAct('fire')">
      <span class="act-name">🔥 FIREBALL</span>
      <span class="act-cost">[2] 15 MP</span>
    </button>
    <button class="btn btn-purple act-btn" id="ba-thunder" onclick="battleAct('thunder')">
      <span class="act-name">⚡ THUNDER</span>
      <span class="act-cost">[3] 20 MP</span>
    </button>
    <button class="btn btn-green act-btn" id="ba-heal" onclick="battleAct('heal')">
      <span class="act-name">✦ PULIHKAN</span>
      <span class="act-cost">[4] 18 MP</span>
    </button>
    <button class="btn btn-green act-btn" id="ba-pot" onclick="battleAct('potion')">
      <span class="act-name">❤ POTION</span>
      <span class="act-cost">[5] Pakai Item</span>
    </button>
    <button class="btn btn-gray act-btn" id="ba-run" onclick="battleAct('run')">
      <span class="act-name">🏃 KABUR</span>
      <span class="act-cost">[6] 50% Peluang</span>
    </button>
  </div>

  <!-- BATTLE LOG -->
  <div class="blog-wrap">
    <div class="blog-lbl">LOG PERTEMPURAN</div>
    <div class="blog-box" id="battle-log"></div>
  </div>
</div>

<!-- ======== GAME OVER ======== -->
<div id="gameover" class="screen">
  <div class="res-art">💀</div>
  <div class="go-title">KAU TELAH GUGUR</div>
  <div class="res-art" style="font-size:30px">— ✦ —</div>
  <div class="res-text">
    Kegelapan telah menelanmu...<br>
    Level Dicapai: <span class="res-hl" id="go-lv">1</span><br>
    Lantai Dicapai: <span class="res-hl" id="go-fl">1</span><br>
    Koin Terkumpul: <span class="res-hl" id="go-gold">0</span>
  </div>
  <button class="btn btn-gold" onclick="restartGame()">↩ &nbsp; MAIN LAGI</button>
</div>

<!-- ======== WIN ======== -->
<div id="win" class="screen">
  <div class="res-art">👑</div>
  <div class="win-title">KEMENANGAN TOTAL!</div>
  <div class="res-art" style="font-size:34px">🌟 ⚔ 🌟</div>
  <div class="res-text">
    Raja Iblis Malphas telah dikalahkan!<br>
    Negeri Aethoria akhirnya bebas dari kutukan!<br><br>
    Level Akhir: <span class="res-hl" id="win-lv">1</span><br>
    Koin Terkumpul: <span class="res-hl" id="win-gold">0</span>
  </div>
  <button class="btn btn-gold" onclick="restartGame()">↩ &nbsp; MAIN LAGI</button>
</div>

<!-- ======== LEVEL UP OVERLAY ======== -->
<div id="lvl-overlay">
  <div class="lvl-box">
    <div class="lvl-title">⭐ NAIK LEVEL! ⭐</div>
    <div class="lvl-gains" id="lvl-gains"></div>
    <button class="btn btn-gold" onclick="closeLevelUp()">LANJUTKAN ▶</button>
  </div>
</div>

<!-- ======================================================== -->
<script>
/* ============================================================
   GAME DATA
============================================================ */

const ENEMIES = [
  {name:'Slime',    type:'BEAST',  art:'🟢', hp:35,  atk:9,  def:2,  exp:18,  gold:[4,10],  floor:1},
  {name:'Goblin',   type:'HUMANOID',art:'👺',hp:50,  atk:13, def:4,  exp:28,  gold:[6,14],  floor:1},
  {name:'Kerangka', type:'UNDEAD', art:'💀', hp:60,  atk:17, def:6,  exp:42,  gold:[9,20],  floor:2},
  {name:'Orc',      type:'BEAST',  art:'👹', hp:75,  atk:20, def:9,  exp:55,  gold:[12,24], floor:2},
  {name:'Dark Mage',type:'SIHIR',  art:'🧙', hp:65,  atk:24, def:5,  exp:68,  gold:[16,30], floor:3},
  {name:'Vampir',   type:'UNDEAD', art:'🧛', hp:85,  atk:22, def:11, exp:80,  gold:[20,36], floor:3},
  {name:'Ksatria Iblis',type:'IBLIS',art:'😈',hp:110,atk:30, def:16, exp:110, gold:[28,50], floor:4},
  {name:'Lich',     type:'UNDEAD', art:'☠️', hp:95,  atk:32, def:13, exp:120, gold:[30,55], floor:4},
  {name:'RAJA IBLIS MALPHAS',type:'★ BOSS ★',art:'👿',hp:220,atk:38,def:22,exp:600,gold:[120,160],floor:4,isBoss:true},
];

const MAP_SIZE = 7;
const FLOOR_CFG = [
  null,
  {eRate:0.32, cRate:0.13},
  {eRate:0.38, cRate:0.11},
  {eRate:0.40, cRate:0.10},
  {eRate:0.42, cRate:0.08, hasBoss:true},
];

/* ============================================================
   GAME STATE
============================================================ */

let G = {};
let curEnemy = null;
let pTurn = true;
let busy = false;

function newState() {
  return {
    floor: 1,
    player: {
      hp:100, maxHp:100,
      mp:50,  maxMp:50,
      atk:15, def:8,
      lv:1, exp:0, nextExp:100,
      gold:0,
      pot:3, manPot:2,
    },
    map:[], rev:[],
    px:3, py:3,
  };
}

/* ============================================================
   MAP
============================================================ */

function genMap(fl) {
  const cfg = FLOOR_CFG[fl];
  const map=[], rev=[];
  for(let y=0;y<MAP_SIZE;y++){
    map.push([]); rev.push([]);
    for(let x=0;x<MAP_SIZE;x++){
      rev[y].push(false);
      const r=Math.random();
      if(r<cfg.eRate)       map[y].push('E');
      else if(r<cfg.eRate+cfg.cRate) map[y].push('C');
      else                  map[y].push('.');
    }
  }
  // Start
  map[3][3]='S'; rev[3][3]=true;
  revealAround(rev,3,3);

  // Stairs / Boss – at least 4 steps away
  let placed=false;
  let tries=0;
  while(!placed && tries<200){
    tries++;
    const ex=Math.floor(Math.random()*MAP_SIZE);
    const ey=Math.floor(Math.random()*MAP_SIZE);
    if(Math.abs(ex-3)+Math.abs(ey-3)>=4 && map[ey][ex]!=='S'){
      map[ey][ex] = cfg.hasBoss ? 'B' : 'X';
      placed=true;
    }
  }
  G.map=map; G.rev=rev; G.px=3; G.py=3;
}

function revealAround(rev,x,y){
  for(let dy=-1;dy<=1;dy++) for(let dx=-1;dx<=1;dx++){
    const nx=x+dx, ny=y+dy;
    if(nx>=0&&nx<MAP_SIZE&&ny>=0&&ny<MAP_SIZE) rev[ny][nx]=true;
  }
}

/* ============================================================
   SCREENS
============================================================ */

function show(id){
  document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
  document.getElementById(id).classList.add('active');
}

function startGame(){
  G=newState();
  genMap(1);
  show('explore');
  updateExploreUI();
  elog('Kamu memasuki dungeon. Angin dingin berhembus...','event');
  elog('Temukan tangga untuk turun ke lantai berikutnya!','ok');
}

function restartGame(){ startGame(); }

/* ============================================================
   EXPLORE
============================================================ */

function move(dx,dy){
  const nx=G.px+dx, ny=G.py+dy;
  if(nx<0||nx>=MAP_SIZE||ny<0||ny>=MAP_SIZE){
    elog('Tidak bisa ke sana.','');
    return;
  }
  G.px=nx; G.py=ny;
  revealAround(G.rev,nx,ny);

  const cell=G.map[ny][nx];
  if(cell==='E'){     startBattle(nx,ny);    return; }
  else if(cell==='B'){ startBossBattle(nx,ny); return; }
  else if(cell==='C'){ openChest(nx,ny); }
  else if(cell==='X'){ goNextFloor();          return; }
  else if(cell==='S'){ elog('Titik awal dungeon.',''); }
  else {
    const flavor=['Lorong ini sunyi...','Batu berlumut di sekitarmu.','Kamu mendengar suara aneh.','Angin dingin berhembus dari kejauhan.'];
    elog(flavor[Math.floor(Math.random()*flavor.length)],'');
  }
  updateExploreUI();
}

function openChest(x,y){
  G.map[y][x]='.';
  const r=Math.random();
  if(r<0.35){ G.player.pot++; elog('💎 Menemukan Health Potion!','item'); }
  else if(r<0.6){ G.player.manPot++; elog('💎 Menemukan Mana Potion!','item'); }
  else {
    const g=10+Math.floor(Math.random()*15*G.floor);
    G.player.gold+=g;
    elog(`💎 Menemukan ${g} Koin!`,'item');
  }
}

function goNextFloor(){
  if(G.floor>=4){ elog('Jalan terblokir. Kalahkan Raja Iblis dulu!','event'); return; }
  G.floor++;
  elog(`▼ Kamu turun ke Lantai ${G.floor}...`,'event');
  genMap(G.floor);
  updateExploreUI();
  elog(`Lantai ${G.floor}: Bahaya semakin meningkat.`,'event');
}

function useItem(type){
  const p=G.player;
  if(type==='potion'){
    if(p.pot<=0){ elog('Tidak ada potion tersisa!',''); return; }
    const h=Math.min(p.maxHp-p.hp, 40+p.lv*5);
    p.hp+=h; p.pot--;
    elog(`❤ Minum Health Potion. Pulihkan ${h} HP.`,'item');
  } else {
    if(p.manPot<=0){ elog('Tidak ada Mana Potion tersisa!',''); return; }
    const m=Math.min(p.maxMp-p.mp, 30);
    p.mp+=m; p.manPot--;
    elog(`✦ Minum Mana Potion. Pulihkan ${m} MP.`,'item');
  }
  updateExploreUI();
}

function elog(msg, cls=''){
  const box=document.getElementById('explore-log');
  if(!box) return;
  const d=document.createElement('div');
  d.className='log-entry'+(cls?' log-'+cls:'');
  d.textContent=msg;
  box.appendChild(d);
  box.scrollTop=box.scrollHeight;
  while(box.children.length>35) box.removeChild(box.firstChild);
}

/* ============================================================
   EXPLORE UI
============================================================ */

function updateExploreUI(){
  const p=G.player;
  setBar('e-hp-bar',p.hp,p.maxHp);
  setBar('e-mp-bar',p.mp,p.maxMp);
  setBar('e-exp-bar',p.exp,p.nextExp);
  setText('e-hp-txt',p.hp+'/'+p.maxHp);
  setText('e-mp-txt',p.mp+'/'+p.maxMp);
  setText('e-exp-txt',p.exp+'/'+p.nextExp);
  setText('e-lv',p.lv);
  setText('e-atk',p.atk);
  setText('e-def',p.def);
  setText('gold-disp',p.gold);
  setText('floor-num',G.floor);
  setText('ex-pot-n',p.pot);
  setText('ex-man-n',p.manPot);
  document.getElementById('btn-n').disabled=G.py<=0;
  document.getElementById('btn-s').disabled=G.py>=MAP_SIZE-1;
  document.getElementById('btn-w').disabled=G.px<=0;
  document.getElementById('btn-e').disabled=G.px>=MAP_SIZE-1;
  renderMap();
}

function renderMap(){
  const grid=document.getElementById('map-grid');
  grid.style.gridTemplateColumns=`repeat(${MAP_SIZE},26px)`;
  grid.innerHTML='';
  for(let y=0;y<MAP_SIZE;y++) for(let x=0;x<MAP_SIZE;x++){
    const d=document.createElement('div');
    d.className='cell';
    if(!G.rev[y][x]){ d.classList.add('fog'); }
    else if(G.px===x&&G.py===y){ d.classList.add('c-player'); d.textContent='🧙'; }
    else {
      const c=G.map[y][x];
      if(c==='E')     { d.classList.add('c-enemy');  d.textContent='⚔'; }
      else if(c==='C'){ d.classList.add('c-chest');  d.textContent='💎'; }
      else if(c==='B'){ d.classList.add('c-boss');   d.textContent='👑'; }
      else if(c==='X'){ d.classList.add('c-stairs'); d.textContent='🔽'; }
      else            { d.classList.add('c-empty');  d.textContent='▪'; }
    }
    grid.appendChild(d);
  }
}

/* ============================================================
   BATTLE
============================================================ */

function pickEnemy(fl){
  const pool=ENEMIES.filter(e=>e.floor===fl&&!e.isBoss);
  return pool[Math.floor(Math.random()*pool.length)];
}

function startBattle(x,y){
  const base=pickEnemy(G.floor);
  curEnemy={...base, curHp:base.hp, bx:x, by:y};
  elog(`⚔ ${curEnemy.name} muncul!`,'battle');
  enterBattle();
}

function startBossBattle(x,y){
  const boss=ENEMIES.find(e=>e.isBoss);
  curEnemy={...boss, curHp:boss.hp, bx:x, by:y};
  elog('👿 RAJA IBLIS MALPHAS TELAH BANGKIT!','battle');
  enterBattle();
}

function enterBattle(){
  pTurn=true; busy=false;
  document.getElementById('battle-log').innerHTML='';
  show('battle');
  updateBattleUI();
  blog(`⚔ ${curEnemy.name} siap bertarung!`,'info');
  setBtns(true);
}

function blog(msg,cls=''){
  const box=document.getElementById('battle-log');
  const d=document.createElement('div');
  d.className='blog-entry'+(cls?' bt-'+cls:'');
  d.textContent=msg;
  box.appendChild(d);
  box.scrollTop=box.scrollHeight;
  while(box.children.length>35) box.removeChild(box.firstChild);
}

function updateBattleUI(){
  const p=G.player, e=curEnemy;
  setText('b-ename',e.name);
  setText('b-etype','TIPE: '+e.type);
  setText('b-eart',e.art);
  setBar('b-ehp-bar',Math.max(0,e.curHp),e.hp);
  setText('b-ehp-num',Math.max(0,e.curHp)+'/'+e.hp);
  setText('b-pname','PAHLAWAN');
  setText('b-plv','LEVEL '+p.lv);
  setBar('b-php-bar',p.hp,p.maxHp);
  setBar('b-pmp-bar',p.mp,p.maxMp);
  setText('b-php-num',p.hp+'/'+p.maxHp);
  setText('b-pmp-num',p.mp+'/'+p.maxMp);
  setText('b-patk',p.atk);
  setText('b-pdef',p.def);
  setText('b-ppot',p.pot);
  setText('b-pman',p.manPot);
}

function setBtns(enabled){
  const p=G.player;
  const off=!enabled||busy;
  setDis('ba-atk',    off);
  setDis('ba-fire',   off||p.mp<15);
  setDis('ba-thunder',off||p.mp<20);
  setDis('ba-heal',   off||p.mp<18);
  setDis('ba-pot',    off||p.pot<=0);
  setDis('ba-run',    off);
}

function battleAct(action){
  if(!pTurn||busy) return;
  busy=true; setBtns(false);

  const p=G.player, e=curEnemy;
  let skipEnemyTurn=false;

  switch(action){
    case 'attack':{
      const dmg=calcDmg(p.atk,e.def,1.0,6);
      e.curHp-=dmg;
      blog(`⚔ Kamu menyerang ${e.name} sebesar ${dmg} damage!`,'player');
      flash('enemy-card','flash-red');
      break;
    }
    case 'fire':{
      p.mp-=15;
      const dmg=calcDmg(p.atk*1.7,e.def*0.4,1.2,8);
      e.curHp-=dmg;
      blog(`🔥 Fireball! ${e.name} terkena ${dmg} magic damage!`,'player');
      flash('enemy-card','flash-red');
      break;
    }
    case 'thunder':{
      p.mp-=20;
      const dmg=calcDmg(p.atk*2.0,e.def*0.3,1.0,10);
      e.curHp-=dmg;
      blog(`⚡ Thunder Strike! ${e.name} terkena ${dmg} damage!`,'player');
      flash('enemy-card','flash-red');
      break;
    }
    case 'heal':{
      p.mp-=18;
      const h=Math.floor(p.maxHp*0.28+p.lv*4);
      p.hp=Math.min(p.maxHp,p.hp+h);
      blog(`✦ Kamu memulihkan ${h} HP!`,'player');
      flash('player-card','flash-blue');
      break;
    }
    case 'potion':{
      if(p.pot<=0){ busy=false; setBtns(true); return; }
      p.pot--;
      const h=40+p.lv*5;
      p.hp=Math.min(p.maxHp,p.hp+h);
      blog(`❤ Minum Potion! Pulihkan ${h} HP.`,'item');
      flash('player-card','flash-blue');
      break;
    }
    case 'run':{
      if(Math.random()<0.5){
        blog('🏃 Berhasil melarikan diri!','info');
        setTimeout(()=>{ show('explore'); updateExploreUI(); elog('Kamu melarikan diri dari pertempuran!',''); },700);
        return;
      } else {
        blog('❌ Gagal melarikan diri!','info');
      }
      break;
    }
  }

  updateBattleUI();

  if(e.curHp<=0){
    setTimeout(()=>endBattle(true), 600);
    return;
  }

  // Enemy turn after delay
  setTimeout(()=>enemyTurn(), 900);
}

function enemyTurn(){
  const p=G.player, e=curEnemy;
  const roll=Math.random();
  let dmg=0;

  if(roll<0.12){
    blog(`💨 ${e.name} menyerang tapi meleset!`,'enemy');
  } else if(roll<0.2&&e.isBoss){
    dmg=Math.max(2,Math.floor(e.atk*1.6)-Math.floor(p.def*0.5)+rnd(8));
    blog(`💥 ${e.name} menggunakan DARK BLAST! Kamu terkena ${dmg} damage!`,'enemy');
  } else {
    dmg=Math.max(1,e.atk-Math.floor(p.def*0.75)+rnd(6)-2);
    blog(`💢 ${e.name} menyerang! Kamu terkena ${dmg} damage!`,'enemy');
  }

  if(dmg>0){ p.hp=Math.max(0,p.hp-dmg); flash('player-card','flash-red'); }

  pTurn=true; busy=false;
  updateBattleUI();
  setBtns(true);

  if(p.hp<=0) setTimeout(()=>endBattle(false),600);
}

function endBattle(won){
  if(won){
    G.map[curEnemy.by][curEnemy.bx]='.';
    const g=curEnemy.gold[0]+Math.floor(Math.random()*(curEnemy.gold[1]-curEnemy.gold[0]));
    G.player.gold+=g;
    G.player.exp+=curEnemy.exp;
    blog(`🌟 Menang! +${curEnemy.exp} EXP, +${g} Koin!`,'info');

    if(curEnemy.isBoss){
      setTimeout(()=>{
        setText('win-lv',G.player.lv);
        setText('win-gold',G.player.gold);
        show('win');
      },1000);
      return;
    }

    const leveled=checkLevelUp();
    setTimeout(()=>{
      if(!leveled){ show('explore'); updateExploreUI(); }
      elog(`⚔ Mengalahkan ${curEnemy.name}! +${curEnemy.exp} EXP, +${g} Koin`,'battle');
    }, leveled?100:700);

  } else {
    setTimeout(()=>{
      setText('go-lv',G.player.lv);
      setText('go-fl',G.floor);
      setText('go-gold',G.player.gold);
      show('gameover');
    },800);
  }
}

/* ============================================================
   LEVEL UP
============================================================ */

function checkLevelUp(){
  const p=G.player;
  if(p.exp<p.nextExp) return false;
  p.exp-=p.nextExp;
  p.lv++;
  p.nextExp=Math.floor(p.nextExp*1.6);

  const hg=12+rnd(10), mg=7+rnd(5), ag=2+rnd(3), dg=1+rnd(2);
  p.maxHp+=hg; p.hp=Math.min(p.maxHp,p.hp+Math.floor(hg/2));
  p.maxMp+=mg; p.mp=Math.min(p.maxMp,p.mp+Math.floor(mg/2));
  p.atk+=ag; p.def+=dg;

  document.getElementById('lvl-gains').innerHTML=
    `Level ${p.lv}!<br><br>`+
    `❤ Max HP +${hg}<br>`+
    `✦ Max MP +${mg}<br>`+
    `⚔ ATK +${ag}<br>`+
    `🛡 DEF +${dg}`;
  document.getElementById('lvl-overlay').classList.add('show');
  return true;
}

function closeLevelUp(){
  document.getElementById('lvl-overlay').classList.remove('show');
  show('explore');
  updateExploreUI();
  elog(`⭐ NAIK LEVEL! Sekarang Level ${G.player.lv}!`,'level');
  if(G.player.exp>=G.player.nextExp) checkLevelUp();
}

/* ============================================================
   HELPERS
============================================================ */

function calcDmg(atk,def,mult,variance){
  return Math.max(1, Math.floor(atk*mult) - Math.floor(def) + rnd(variance) - Math.floor(variance/2));
}
function rnd(n){ return Math.floor(Math.random()*n); }
function setBar(id,cur,max){ const el=document.getElementById(id); if(el) el.style.width=Math.max(0,cur/max*100)+'%'; }
function setText(id,val){ const el=document.getElementById(id); if(el) el.textContent=val; }
function setDis(id,v){ const el=document.getElementById(id); if(el) el.disabled=v; }
function flash(id,cls){
  const el=document.getElementById(id);
  if(!el) return;
  el.classList.remove(cls);
  void el.offsetWidth;
  el.classList.add(cls);
  setTimeout(()=>el.classList.remove(cls),500);
}

/* ============================================================
   KEYBOARD
============================================================ */

document.addEventListener('keydown',e=>{
  if(document.getElementById('explore').classList.contains('active')){
    if(e.key==='ArrowUp'   ||e.key==='w'||e.key==='W') move(0,-1);
    if(e.key==='ArrowDown' ||e.key==='s'||e.key==='S') move(0,1);
    if(e.key==='ArrowLeft' ||e.key==='a'||e.key==='A') move(-1,0);
    if(e.key==='ArrowRight'||e.key==='d'||e.key==='D') move(1,0);
  }
  if(document.getElementById('battle').classList.contains('active')){
    if(e.key==='1') battleAct('attack');
    if(e.key==='2') battleAct('fire');
    if(e.key==='3') battleAct('thunder');
    if(e.key==='4') battleAct('heal');
    if(e.key==='5') battleAct('potion');
    if(e.key==='6') battleAct('run');
  }
});
</script>
</body>
</html>
