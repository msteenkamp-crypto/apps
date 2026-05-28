<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>🌟 Fun Learning Apps! 🌟</title>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet" />
  <style>
    /* ── BASE ── */
    :root{--card-bg:rgba(255,255,255,0.92);--shadow:0 8px 32px rgba(0,0,0,0.18);--r:28px;--purple:#7c3aed;--pink:#f472b6;--sky:#38bdf8;}
    *,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
    body{font-family:'Nunito',sans-serif;min-height:100vh;overflow-x:hidden;background:linear-gradient(160deg,#a8edea 0%,#fed6e3 50%,#ffecd2 100%);}

    /* ── BG BLOBS ── */
    .bg-blobs{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden;}
    .blob{position:absolute;border-radius:50%;opacity:.35;animation:floatBlob 8s ease-in-out infinite alternate;}
    .blob-1{width:320px;height:320px;background:#fbbf24;top:-80px;left:-80px;}
    .blob-2{width:260px;height:260px;background:#f472b6;top:30%;right:-60px;animation-delay:1.5s;}
    .blob-3{width:200px;height:200px;background:#818cf8;bottom:10%;left:5%;animation-delay:3s;}
    .blob-4{width:180px;height:180px;background:#4ade80;bottom:-40px;right:20%;animation-delay:2s;}
    .blob-5{width:140px;height:140px;background:#38bdf8;top:55%;left:40%;animation-delay:4s;}
    @keyframes floatBlob{from{transform:translate(0,0)scale(1);}to{transform:translate(20px,30px)scale(1.08);}}
    .stars{position:fixed;inset:0;pointer-events:none;z-index:0;}
    .star{position:absolute;animation:twinkle 3s ease-in-out infinite alternate;}
    @keyframes twinkle{from{opacity:.2;transform:scale(.8)rotate(-10deg);}to{opacity:.9;transform:scale(1.2)rotate(10deg);}}

    /* ── PAGE ── */
    .page{position:relative;z-index:1;display:flex;flex-direction:column;align-items:center;padding:32px 16px 80px;min-height:100vh;}
    header{text-align:center;margin-bottom:40px;animation:popIn .6s cubic-bezier(.34,1.56,.64,1) both;}
    @keyframes popIn{from{opacity:0;transform:scale(.6)translateY(-30px);}to{opacity:1;transform:scale(1)translateY(0);}}
    .header-emoji{font-size:5rem;display:block;animation:bounce 2s ease-in-out infinite;filter:drop-shadow(0 4px 12px rgba(0,0,0,.15));}
    @keyframes bounce{0%,100%{transform:translateY(0);}50%{transform:translateY(-14px);}}
    h1{font-family:'Fredoka One',cursive;font-size:clamp(2.2rem,6vw,4rem);background:linear-gradient(135deg,#f472b6,#a78bfa,#38bdf8);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;line-height:1.1;margin-top:8px;}
    .subtitle{font-size:1.25rem;font-weight:700;color:#6d4c8f;margin-top:8px;}

    /* ── STATES ── */
    #loading{display:flex;flex-direction:column;align-items:center;gap:16px;margin-top:60px;}
    .spinner{width:64px;height:64px;border:6px solid rgba(167,139,250,.2);border-top-color:#a78bfa;border-radius:50%;animation:spin .8s linear infinite;}
    @keyframes spin{to{transform:rotate(360deg);}}
    #loading p{font-family:'Fredoka One',cursive;font-size:1.4rem;color:var(--purple);}
    #empty-msg{display:none;background:var(--card-bg);border-radius:var(--r);padding:32px 40px;text-align:center;box-shadow:var(--shadow);max-width:480px;margin-top:40px;}
    #empty-msg h2{font-family:'Fredoka One',cursive;font-size:1.8rem;color:var(--purple);margin-bottom:10px;}
    #empty-msg p{color:#555;font-size:1rem;line-height:1.6;}

    /* ── CAROUSEL ── */
    #carousel-section{display:none;width:100%;max-width:900px;flex-direction:column;align-items:center;}
    .app-count{font-family:'Fredoka One',cursive;font-size:1.1rem;color:var(--purple);margin-bottom:16px;background:rgba(255,255,255,.7);padding:6px 20px;border-radius:100px;box-shadow:0 2px 8px rgba(0,0,0,.08);}
    .carousel-outer{width:100%;display:flex;align-items:center;gap:12px;justify-content:center;}
    .arrow-btn{flex-shrink:0;width:60px;height:60px;border-radius:50%;border:none;cursor:pointer;font-size:1.8rem;display:flex;align-items:center;justify-content:center;transition:transform .15s,box-shadow .15s;box-shadow:0 4px 18px rgba(0,0,0,.18);background:linear-gradient(135deg,#f472b6,#a78bfa);color:white;user-select:none;}
    .arrow-btn:hover{transform:scale(1.12);box-shadow:0 8px 28px rgba(0,0,0,.24);}
    .arrow-btn:active{transform:scale(.96);}
    .arrow-btn:disabled{background:#d1d5db;cursor:default;transform:none;box-shadow:none;opacity:.5;}
    .carousel-viewport{flex:1;overflow:hidden;border-radius:var(--r);}
    .carousel-track{display:flex;transition:transform .45s cubic-bezier(.34,1.12,.64,1);will-change:transform;}
    .app-card{flex:0 0 100%;display:flex;flex-direction:column;align-items:center;background:var(--card-bg);border-radius:var(--r);overflow:hidden;box-shadow:var(--shadow);}
    .card-header{width:100%;padding:20px 28px 16px;display:flex;align-items:center;gap:14px;}
    .card-emoji{font-size:2.2rem;flex-shrink:0;}
    .card-title{font-family:'Fredoka One',cursive;font-size:clamp(1.4rem,4vw,2rem);color:#1e1b4b;line-height:1.1;}
    .card-filename{font-size:.8rem;color:#9ca3af;margin-top:2px;font-family:monospace;}
    .card-preview{width:100%;position:relative;overflow:hidden;height:320px;border-top:3px solid rgba(167,139,250,.3);border-bottom:3px solid rgba(167,139,250,.3);background:#f0f4ff;display:flex;align-items:center;justify-content:center;}
    .card-preview img.preview-img{width:100%;height:100%;object-fit:cover;object-position:top;display:block;}
    .preview-placeholder{display:flex;flex-direction:column;align-items:center;justify-content:center;gap:12px;width:100%;height:100%;background:linear-gradient(135deg,#ede9fe,#fce7f3);}
    .preview-placeholder .ph-emoji{font-size:4rem;animation:bounce 2s ease-in-out infinite;}
    .preview-placeholder .ph-title{font-family:'Fredoka One',cursive;font-size:1.3rem;color:var(--purple);}
    .preview-placeholder .ph-hint{font-size:.78rem;color:#9ca3af;text-align:center;max-width:240px;line-height:1.5;background:rgba(255,255,255,.7);border-radius:12px;padding:6px 14px;}
    .preview-overlay{position:absolute;inset:0;cursor:pointer;}
    .card-footer{width:100%;padding:20px 28px;display:flex;align-items:center;justify-content:center;}
    .launch-btn{font-family:'Fredoka One',cursive;font-size:1.3rem;padding:14px 40px;border:none;border-radius:100px;cursor:pointer;color:white;background:linear-gradient(135deg,#f472b6 0%,#a78bfa 60%,#38bdf8 100%);background-size:200% 200%;box-shadow:0 6px 24px rgba(167,139,250,.45);transition:transform .18s,box-shadow .18s;animation:gradMove 4s ease infinite alternate;text-decoration:none;display:inline-flex;align-items:center;gap:10px;}
    @keyframes gradMove{from{background-position:0% 50%;}to{background-position:100% 50%;}}
    .launch-btn:hover{transform:scale(1.07)translateY(-2px);box-shadow:0 12px 36px rgba(167,139,250,.55);}
    .dots{display:flex;gap:10px;margin-top:24px;}
    .dot{width:12px;height:12px;border-radius:50%;background:rgba(167,139,250,.3);border:2px solid rgba(167,139,250,.4);cursor:pointer;transition:background .25s,transform .25s;}
    .dot.active{background:#a78bfa;transform:scale(1.35);border-color:var(--purple);}

    /* ── TEACHER KEY HINT ── */
    .teacher-hint{position:fixed;bottom:18px;right:22px;font-size:.75rem;color:rgba(100,80,140,.45);font-weight:600;letter-spacing:.03em;user-select:none;z-index:10;}

    /* ══════════════════════════════════════
       ADMIN MODAL OVERLAY
    ══════════════════════════════════════ */
    #admin-overlay{display:none;position:fixed;inset:0;z-index:100;background:rgba(15,5,40,.75);backdrop-filter:blur(6px);align-items:center;justify-content:center;padding:16px;}
    #admin-overlay.open{display:flex;}

    /* Login panel */
    #admin-login{background:#fff;border-radius:24px;padding:40px 36px;max-width:380px;width:100%;box-shadow:0 24px 80px rgba(0,0,0,.35);text-align:center;animation:popIn .4s cubic-bezier(.34,1.56,.64,1) both;}
    #admin-login h2{font-family:'Fredoka One',cursive;font-size:2rem;color:var(--purple);margin-bottom:6px;}
    #admin-login p{font-size:.92rem;color:#6b7280;margin-bottom:24px;}
    #pw-input{width:100%;padding:12px 18px;font-size:1rem;font-family:'Nunito',sans-serif;border:2px solid #e5e7eb;border-radius:12px;outline:none;transition:border-color .2s;}
    #pw-input:focus{border-color:#a78bfa;}
    #pw-error{color:#e11d48;font-size:.85rem;margin-top:8px;min-height:20px;}
    .btn-login{margin-top:16px;width:100%;padding:13px;font-family:'Fredoka One',cursive;font-size:1.2rem;background:linear-gradient(135deg,#f472b6,#a78bfa);color:white;border:none;border-radius:12px;cursor:pointer;transition:transform .15s,box-shadow .15s;box-shadow:0 4px 18px rgba(167,139,250,.4);}
    .btn-login:hover{transform:translateY(-2px);box-shadow:0 8px 28px rgba(167,139,250,.5);}

    /* Admin panel */
    #admin-panel{display:none;background:#fff;border-radius:24px;max-width:620px;width:100%;max-height:90vh;overflow-y:auto;box-shadow:0 24px 80px rgba(0,0,0,.35);animation:popIn .4s cubic-bezier(.34,1.56,.64,1) both;flex-direction:column;}
    #admin-panel.open{display:flex;}
    .admin-header{padding:24px 28px 16px;display:flex;align-items:center;justify-content:space-between;border-bottom:2px solid #f3f0ff;position:sticky;top:0;background:#fff;z-index:2;border-radius:24px 24px 0 0;}
    .admin-header h2{font-family:'Fredoka One',cursive;font-size:1.7rem;color:var(--purple);}
    .btn-close{background:none;border:none;font-size:1.6rem;cursor:pointer;color:#9ca3af;line-height:1;transition:color .15s,transform .15s;}
    .btn-close:hover{color:#e11d48;transform:scale(1.15);}
    .admin-body{padding:20px 28px 28px;display:flex;flex-direction:column;gap:24px;}

    /* Token section */
    .section-label{font-weight:800;color:#374151;font-size:.88rem;text-transform:uppercase;letter-spacing:.06em;margin-bottom:8px;}
    .token-row{display:flex;gap:8px;align-items:center;}
    .token-input{flex:1;padding:10px 14px;font-size:.88rem;font-family:monospace;border:2px solid #e5e7eb;border-radius:10px;outline:none;transition:border-color .2s;}
    .token-input:focus{border-color:#a78bfa;}
    .token-info{font-size:.78rem;color:#9ca3af;line-height:1.5;margin-top:6px;}
    .token-info a{color:#a78bfa;text-decoration:none;}
    .token-info a:hover{text-decoration:underline;}
    .token-status{font-size:.82rem;font-weight:700;padding:3px 10px;border-radius:100px;}
    .token-status.ok{background:#d1fae5;color:#065f46;}
    .token-status.bad{background:#fee2e2;color:#991b1b;}

    /* App list */
    #app-list{display:flex;flex-direction:column;gap:8px;min-height:48px;}
    .app-row{display:flex;align-items:center;gap:10px;background:#f9f7ff;border:2px solid #ede9fe;border-radius:12px;padding:10px 14px;transition:box-shadow .2s;}
    .app-row:hover{box-shadow:0 2px 12px rgba(167,139,250,.2);}
    .app-row-drag{cursor:grab;color:#c4b5fd;font-size:1.1rem;flex-shrink:0;}
    .app-row-drag:active{cursor:grabbing;}
    .app-row-name{flex:1;font-size:.92rem;font-weight:700;color:#3730a3;font-family:monospace;}
    .app-row-title{font-size:.8rem;color:#6b7280;margin-top:1px;}
    .btn-remove{background:none;border:none;cursor:pointer;font-size:1.2rem;color:#fca5a5;transition:color .15s,transform .15s;flex-shrink:0;}
    .btn-remove:hover{color:#e11d48;transform:scale(1.2);}
    .drag-over{border:2px dashed #a78bfa!important;background:#f5f0ff!important;}
    .empty-list{text-align:center;color:#9ca3af;font-size:.9rem;padding:20px;font-style:italic;}

    /* Add form */
    .add-form{display:flex;gap:8px;align-items:center;}
    .add-input{flex:1;padding:11px 16px;font-size:.95rem;font-family:'Nunito',sans-serif;border:2px solid #e5e7eb;border-radius:12px;outline:none;transition:border-color .2s;}
    .add-input:focus{border-color:#a78bfa;}
    .btn-add{padding:11px 20px;font-family:'Fredoka One',cursive;font-size:1rem;background:linear-gradient(135deg,#4ade80,#38bdf8);color:white;border:none;border-radius:12px;cursor:pointer;white-space:nowrap;transition:transform .15s,box-shadow .15s;box-shadow:0 3px 12px rgba(56,189,248,.3);}
    .btn-add:hover{transform:translateY(-1px);box-shadow:0 6px 20px rgba(56,189,248,.4);}
    .add-hint{font-size:.78rem;color:#9ca3af;margin-top:5px;}

    /* Save button */
    .btn-save{width:100%;padding:15px;font-family:'Fredoka One',cursive;font-size:1.3rem;background:linear-gradient(135deg,#f472b6,#a78bfa);color:white;border:none;border-radius:14px;cursor:pointer;transition:transform .15s,box-shadow .15s,opacity .2s;box-shadow:0 6px 24px rgba(167,139,250,.4);}
    .btn-save:hover:not(:disabled){transform:translateY(-2px);box-shadow:0 10px 32px rgba(167,139,250,.5);}
    .btn-save:disabled{opacity:.5;cursor:not-allowed;}
    .save-status{text-align:center;font-size:.88rem;font-weight:700;min-height:22px;margin-top:4px;}
    .save-status.ok{color:#059669;}
    .save-status.err{color:#e11d48;}
    .save-status.working{color:#7c3aed;}

    /* GitHub config */
    .config-row{display:grid;grid-template-columns:1fr 1fr;gap:8px;}
    .config-field{display:flex;flex-direction:column;gap:4px;}
    .config-field label{font-size:.78rem;font-weight:700;color:#6b7280;text-transform:uppercase;letter-spacing:.05em;}
    .config-field input{padding:9px 12px;font-size:.88rem;font-family:'Nunito',sans-serif;border:2px solid #e5e7eb;border-radius:10px;outline:none;transition:border-color .2s;}
    .config-field input:focus{border-color:#a78bfa;}

    /* Divider */
    .divider{height:1px;background:linear-gradient(90deg,transparent,#e5e7eb,transparent);margin:0;}

    @media(max-width:600px){
      .arrow-btn{width:48px;height:48px;font-size:1.4rem;}
      .card-preview{height:200px;}
      .card-header,.card-footer{padding:16px 18px;}
      #admin-login,#admin-panel{border-radius:18px;}
      .admin-body{padding:16px 18px 22px;}
      .config-row{grid-template-columns:1fr;}
    }
  </style>
</head>
<body>

<div class="bg-blobs">
  <div class="blob blob-1"></div><div class="blob blob-2"></div>
  <div class="blob blob-3"></div><div class="blob blob-4"></div><div class="blob blob-5"></div>
</div>
<div class="stars" id="stars"></div>

<!-- ── MAIN PAGE ── -->
<div class="page">
  <header>
    <span class="header-emoji">🚀</span>
    <h1>Fun Learning Apps!</h1>
    <p class="subtitle">✨ Pick an app and start exploring! ✨</p>
  </header>

  <div id="loading"><div class="spinner"></div><p>Loading your apps… 🎉</p></div>

  <div id="empty-msg">
    <h2>📂 No Apps Yet!</h2>
    <p>Open the Teacher Panel to add your first app!</p>
  </div>

  <section id="carousel-section" role="region" aria-label="App carousel">
    <div class="app-count" id="app-count"></div>
    <div class="carousel-outer">
      <button class="arrow-btn" id="prev-btn" aria-label="Previous" disabled>‹</button>
      <div class="carousel-viewport">
        <div class="carousel-track" id="carousel-track"></div>
      </div>
      <button class="arrow-btn" id="next-btn" aria-label="Next">›</button>
    </div>
    <div class="dots" id="dots" role="tablist"></div>
  </section>
</div>

<div class="teacher-hint">Press <kbd style="background:rgba(120,80,200,.12);border-radius:4px;padding:1px 5px;font-family:monospace;">T</kbd> for teacher panel</div>

<!-- ══════════════════════════════════════
     ADMIN MODAL
══════════════════════════════════════ -->
<div id="admin-overlay" role="dialog" aria-modal="true" aria-label="Teacher panel">

  <!-- Step 1: Login -->
  <div id="admin-login">
    <div style="font-size:3rem;margin-bottom:8px;">🔑</div>
    <h2>Teacher Panel</h2>
    <p>Enter your teacher password to manage apps</p>
    <input id="pw-input" type="password" placeholder="Password" autocomplete="current-password" />
    <div id="pw-error"></div>
    <button class="btn-login" onclick="doLogin()">Unlock ✨</button>
  </div>

  <!-- Step 2: Management panel -->
  <div id="admin-panel">
    <div class="admin-header">
      <h2>🛠️ Manage Apps</h2>
      <button class="btn-close" onclick="closeAdmin()" title="Close">✕</button>
    </div>

    <div class="admin-body">

      <!-- GitHub config -->
      <div>
        <div class="section-label">⚙️ GitHub Settings</div>
        <div class="config-row">
          <div class="config-field">
            <label>Username</label>
            <input id="cfg-user" type="text" placeholder="aitips4teacherz-stack" />
          </div>
          <div class="config-field">
            <label>Repository</label>
            <input id="cfg-repo" type="text" placeholder="ClarksApps" />
          </div>
        </div>
      </div>

      <div class="divider"></div>

      <!-- GitHub Token -->
      <div>
        <div class="section-label">🔐 GitHub Token <span id="token-status-badge"></span></div>
        <div class="token-row">
          <input id="token-input" class="token-input" type="password" placeholder="ghp_xxxxxxxxxxxxxxxxxxxx" />
          <button onclick="saveToken()" style="padding:10px 16px;font-family:'Fredoka One',cursive;font-size:.95rem;background:linear-gradient(135deg,#a78bfa,#7c3aed);color:white;border:none;border-radius:10px;cursor:pointer;white-space:nowrap;">Save</button>
        </div>
        <div class="token-info">
          Needed to save changes to GitHub. Create a free token at
          <a href="https://github.com/settings/tokens/new?scopes=repo&description=ClassApps" target="_blank">github.com/settings/tokens</a>
          — tick the <strong>repo</strong> scope. Stored only in this browser session.
        </div>
      </div>

      <div class="divider"></div>

      <!-- Current apps list -->
      <div>
        <div class="section-label">📋 Current Apps <span style="color:#9ca3af;font-size:.78rem;font-weight:400;text-transform:none;letter-spacing:0">(drag to reorder)</span></div>
        <div id="app-list"></div>
      </div>

      <div class="divider"></div>

      <!-- Add new app -->
      <div>
        <div class="section-label">➕ Add an App</div>
        <div class="add-form">
          <input id="add-input" class="add-input" type="text" placeholder="my-new-game.html" />
          <button class="btn-add" onclick="addApp()">Add 🎉</button>
        </div>
        <div class="add-hint">Type the filename exactly as uploaded to your <code style="background:#f3f0ff;padding:1px 5px;border-radius:4px;font-size:.8rem;">embed_files/</code> folder</div>
      </div>

      <div class="divider"></div>

      <!-- Save to GitHub -->
      <div>
        <button class="btn-save" id="save-btn" onclick="saveToGitHub()">💾 Save Changes to GitHub</button>
        <div class="save-status" id="save-status"></div>
      </div>

    </div>
  </div>
</div>

<!-- ══════════════════════════════════════
     SCRIPT
══════════════════════════════════════ -->
<script>
// ══════════════════════════
//  CONFIG — edit these if needed as defaults
// ══════════════════════════
const DEFAULT_USER = 'aitips4teacherz-stack';
const DEFAULT_REPO = 'ClarksApps';
const ADMIN_PASSWORD = 'teacher123';   // ← CHANGE THIS to your own password!
const EMBED       = 'embed_files/';
const SCREENSHOTS = 'screenshots/';

// ══════════════════════════
//  STATE
// ══════════════════════════
const BASE_URL = window.location.origin + window.location.pathname.replace(/\/[^/]*$/,'/');
let appList = [];   // current list of filenames
let ghToken = '';   // GitHub PAT (session only, never stored)
let dragSrc = null;

const CARD_EMOJIS  = ['🎮','🧩','🔢','🔬','🌍','🎨','📚','🦄','🚀','⭐','🎵','🦋','🐉','🏆','🍎','🧠'];
const PLACEHOLDERS = ['🎮','🧩','🌈','🚀','⭐','🎨','🧠','🦄'];
const GRADIENTS    = [
  'linear-gradient(135deg,#f472b6,#a78bfa)',
  'linear-gradient(135deg,#38bdf8,#4ade80)',
  'linear-gradient(135deg,#fbbf24,#fb923c)',
  'linear-gradient(135deg,#a78bfa,#38bdf8)',
  'linear-gradient(135deg,#4ade80,#fbbf24)',
];

function fileToTitle(n){return n.replace(/\.html?$/i,'').replace(/[-_]/g,' ').replace(/\b\w/g,c=>c.toUpperCase());}
function getUser(){return (document.getElementById('cfg-user').value||DEFAULT_USER).trim();}
function getRepo(){return (document.getElementById('cfg-repo').value||DEFAULT_REPO).trim();}

// ══════════════════════════
//  STARS
// ══════════════════════════
const starsEl=document.getElementById('stars');
['⭐','✨','🌟','💫','🌈','❤️','💜','💙'].forEach(ch=>{
  for(let i=0;i<3;i++){
    const s=document.createElement('span');
    s.className='star';s.textContent=ch;
    s.style.cssText=`left:${Math.random()*100}vw;top:${Math.random()*100}vh;font-size:${Math.random()*1.2+.8}rem;animation-duration:${Math.random()*3+2}s;animation-delay:${Math.random()*4}s`;
    starsEl.appendChild(s);
  }
});

// ══════════════════════════
//  CAROUSEL
// ══════════════════════════
let current=0,total=0;
const track  =document.getElementById('carousel-track');
const dotsEl =document.getElementById('dots');
const prevBtn=document.getElementById('prev-btn');
const nextBtn=document.getElementById('next-btn');
const countEl=document.getElementById('app-count');

function goTo(i){
  current=Math.max(0,Math.min(i,total-1));
  track.style.transform=`translateX(-${current*100}%)`;
  document.querySelectorAll('.dot').forEach((d,idx)=>d.classList.toggle('active',idx===current));
  prevBtn.disabled=current===0;
  nextBtn.disabled=current===total-1;
  countEl.textContent=`App ${current+1} of ${total} 🎉`;
}
prevBtn.onclick=()=>goTo(current-1);
nextBtn.onclick=()=>goTo(current+1);
document.addEventListener('keydown',e=>{
  if(e.key==='ArrowLeft'&&!adminOpen())goTo(current-1);
  if(e.key==='ArrowRight'&&!adminOpen())goTo(current+1);
  if(e.key.toLowerCase()==='t'&&!adminOpen()&&document.activeElement.tagName!=='INPUT'){openAdmin();}
  if(e.key==='Escape'&&adminOpen())closeAdmin();
});
let tx=0;
track.addEventListener('touchstart',e=>{tx=e.touches[0].clientX;},{passive:true});
track.addEventListener('touchend',e=>{const dx=tx-e.changedTouches[0].clientX;if(Math.abs(dx)>40)dx>0?goTo(current+1):goTo(current-1);});

function buildCard(filename,index){
  const title  =fileToTitle(filename);
  const emoji  =CARD_EMOJIS[index%CARD_EMOJIS.length];
  const phEmoji=PLACEHOLDERS[index%PLACEHOLDERS.length];
  const grad   =GRADIENTS[index%GRADIENTS.length];
  const appUrl =BASE_URL+EMBED+filename;
  const shotName=filename.replace(/\.html?$/i,'.png');
  const shotUrl=BASE_URL+SCREENSHOTS+shotName;
  const card=document.createElement('div');
  card.className='app-card';
  card.innerHTML=`
    <div class="card-header" style="background:${grad}">
      <span class="card-emoji">${emoji}</span>
      <div><div class="card-title">${title}</div><div class="card-filename">${filename}</div></div>
    </div>
    <div class="card-preview">
      <img class="preview-img" id="shot-${index}" alt="${title}" style="display:none" src="${shotUrl}" />
      <div class="preview-placeholder" id="ph-${index}">
        <span class="ph-emoji">${phEmoji}</span>
        <span class="ph-title">${title}</span>
        <span class="ph-hint">Upload <code style="background:#ede9fe;padding:1px 5px;border-radius:4px;color:#6d28d9;font-size:.75rem">${shotName}</code> to <code style="background:#ede9fe;padding:1px 5px;border-radius:4px;color:#6d28d9;font-size:.75rem">screenshots/</code> for a preview</span>
      </div>
      <div class="preview-overlay" onclick="window.open('${appUrl}','_blank')"></div>
    </div>
    <div class="card-footer">
      <a class="launch-btn" href="${appUrl}" target="_blank" rel="noopener">🚀 Play ${title}!</a>
    </div>`;
  const img=card.querySelector(`#shot-${index}`);
  const ph =card.querySelector(`#ph-${index}`);
  img.onload=()=>{img.style.display='block';ph.style.display='none';};
  img.onerror=()=>{img.style.display='none';ph.style.display='flex';};
  return card;
}

function renderCarousel(filenames){
  track.innerHTML='';
  dotsEl.innerHTML='';
  total=0;current=0;
  const htmlFiles=filenames.filter(f=>/\.html?$/i.test(f));
  const loadingEl=document.getElementById('loading');
  const emptyEl=document.getElementById('empty-msg');
  const sectionEl=document.getElementById('carousel-section');
  loadingEl.style.display='none';
  if(htmlFiles.length===0){emptyEl.style.display='block';sectionEl.style.display='none';return;}
  emptyEl.style.display='none';
  htmlFiles.forEach((filename,i)=>{
    track.appendChild(buildCard(filename,i));
    const dot=document.createElement('button');
    dot.className='dot'+(i===0?' active':'');
    dot.setAttribute('role','tab');
    dot.setAttribute('aria-label',`App ${i+1}: ${fileToTitle(filename)}`);
    dot.onclick=()=>goTo(i);
    dotsEl.appendChild(dot);
  });
  total=htmlFiles.length;
  sectionEl.style.display='flex';
  goTo(0);
}

async function loadApps(){
  try{
    const res=await fetch(`${BASE_URL}files.json?_=${Date.now()}`,{cache:'no-store'});
    if(!res.ok)throw new Error('files.json not found');
    const filenames=await res.json();
    appList=[...filenames];
    renderCarousel(appList);
  }catch{
    document.getElementById('loading').style.display='none';
    document.getElementById('empty-msg').style.display='block';
    appList=[];
  }
}

// ══════════════════════════
//  ADMIN — open / close / login
// ══════════════════════════
function adminOpen(){return document.getElementById('admin-overlay').classList.contains('open');}

function openAdmin(){
  const ov=document.getElementById('admin-overlay');
  ov.classList.add('open');
  document.getElementById('admin-login').style.display='block';
  document.getElementById('admin-panel').classList.remove('open');
  document.getElementById('pw-input').value='';
  document.getElementById('pw-error').textContent='';
  setTimeout(()=>document.getElementById('pw-input').focus(),50);
}

function closeAdmin(){
  document.getElementById('admin-overlay').classList.remove('open');
  document.getElementById('save-status').textContent='';
}

// Click outside panel closes it
document.getElementById('admin-overlay').addEventListener('click',e=>{
  if(e.target===document.getElementById('admin-overlay'))closeAdmin();
});

function doLogin(){
  const pw=document.getElementById('pw-input').value;
  if(pw===ADMIN_PASSWORD){
    document.getElementById('admin-login').style.display='none';
    document.getElementById('admin-panel').classList.add('open');
    // Pre-fill config
    document.getElementById('cfg-user').value=DEFAULT_USER;
    document.getElementById('cfg-repo').value=DEFAULT_REPO;
    renderAppList();
  }else{
    document.getElementById('pw-error').textContent='Wrong password — try again!';
    document.getElementById('pw-input').select();
  }
}
document.getElementById('pw-input').addEventListener('keydown',e=>{if(e.key==='Enter')doLogin();});

// ══════════════════════════
//  TOKEN
// ══════════════════════════
function saveToken(){
  ghToken=document.getElementById('token-input').value.trim();
  const badge=document.getElementById('token-status-badge');
  if(ghToken.length>10){
    badge.className='token-status ok';badge.textContent='✓ Token saved';
  }else{
    badge.className='token-status bad';badge.textContent='✗ Too short';ghToken='';
  }
}
document.getElementById('token-input').addEventListener('keydown',e=>{if(e.key==='Enter')saveToken();});

// ══════════════════════════
//  APP LIST UI
// ══════════════════════════
function renderAppList(){
  const listEl=document.getElementById('app-list');
  listEl.innerHTML='';
  if(appList.length===0){
    listEl.innerHTML='<div class="empty-list">No apps yet — add one below!</div>';
    return;
  }
  appList.forEach((filename,i)=>{
    const row=document.createElement('div');
    row.className='app-row';
    row.draggable=true;
    row.dataset.index=i;
    row.innerHTML=`
      <span class="app-row-drag" title="Drag to reorder">⠿</span>
      <div style="flex:1;min-width:0;">
        <div class="app-row-name">${filename}</div>
        <div class="app-row-title">${fileToTitle(filename)}</div>
      </div>
      <button class="btn-remove" title="Remove" onclick="removeApp(${i})">✕</button>`;

    // Drag-and-drop reordering
    row.addEventListener('dragstart',e=>{
      dragSrc=i;
      e.dataTransfer.effectAllowed='move';
      setTimeout(()=>row.style.opacity='.4',0);
    });
    row.addEventListener('dragend',()=>{row.style.opacity='1';});
    row.addEventListener('dragover',e=>{e.preventDefault();row.classList.add('drag-over');});
    row.addEventListener('dragleave',()=>row.classList.remove('drag-over'));
    row.addEventListener('drop',e=>{
      e.preventDefault();row.classList.remove('drag-over');
      if(dragSrc===null||dragSrc===i)return;
      const moved=appList.splice(dragSrc,1)[0];
      appList.splice(i,0,moved);
      renderAppList();
    });

    listEl.appendChild(row);
  });
}

function addApp(){
  let val=document.getElementById('add-input').value.trim();
  if(!val)return;
  if(!/\.html?$/i.test(val))val+='.html';
  val=val.toLowerCase().replace(/\s+/g,'-');
  if(appList.includes(val)){alert(`"${val}" is already in the list!`);return;}
  appList.push(val);
  document.getElementById('add-input').value='';
  renderAppList();
  setSaveStatus('','');
}
document.getElementById('add-input').addEventListener('keydown',e=>{if(e.key==='Enter')addApp();});

function removeApp(i){
  if(!confirm(`Remove "${appList[i]}" from the list?`))return;
  appList.splice(i,1);
  renderAppList();
  setSaveStatus('','');
}

// ══════════════════════════
//  SAVE TO GITHUB
// ══════════════════════════
function setSaveStatus(msg,type){
  const el=document.getElementById('save-status');
  el.textContent=msg;el.className='save-status '+(type||'');
}

async function saveToGitHub(){
  const user=getUser(),repo=getRepo();
  if(!ghToken){setSaveStatus('⚠️ Please enter and save your GitHub token first.','err');return;}
  if(!user||!repo){setSaveStatus('⚠️ Please fill in your GitHub username and repo.','err');return;}

  const btn=document.getElementById('save-btn');
  btn.disabled=true;
  setSaveStatus('Saving to GitHub…','working');

  try{
    const apiBase=`https://api.github.com/repos/${user}/${repo}/contents/files.json`;

    // Get current SHA (needed to update existing file)
    let sha='';
    try{
      const existing=await fetch(apiBase,{headers:{Authorization:`token ${ghToken}`}});
      if(existing.ok){const j=await existing.json();sha=j.sha;}
    }catch{}

    const content=btoa(JSON.stringify(appList,null,2)+'\n');
    const body={message:'Update files.json via Teacher Panel',content};
    if(sha)body.sha=sha;

    const res=await fetch(apiBase,{
      method:'PUT',
      headers:{'Authorization':`token ${ghToken}`,'Content-Type':'application/json'},
      body:JSON.stringify(body)
    });

    if(!res.ok){
      const err=await res.json();
      throw new Error(err.message||`HTTP ${res.status}`);
    }

    setSaveStatus('✅ Saved! Page will update in a few seconds…','ok');
    // Refresh carousel after a brief delay (GitHub Pages propagation)
    setTimeout(async()=>{await loadApps();setSaveStatus('✅ Done! Carousel updated.','ok');},3500);

  }catch(err){
    setSaveStatus(`❌ Error: ${err.message}`,'err');
  }finally{
    btn.disabled=false;
  }
}

// ══════════════════════════
//  INIT
// ══════════════════════════
loadApps();
</script>
</body>
</html>
