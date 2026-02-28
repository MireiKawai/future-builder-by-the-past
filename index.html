<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>My Universe</title>

<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="default">
<meta name="apple-mobile-web-app-title" content="MyUniverse">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=DM+Mono:wght@300;400;500&display=swap" rel="stylesheet">
<style>
:root {
  --bg: #f9f7f4;
  --bg2: #f2ede6;
  --ink: #1c1a17;
  --muted: #8a8278;
  --faint: #e6e0d8;
  --accent: #b8935a;
  --accent2: #d4b896;
  --danger: #c0392b;
  --future: #5a8a72;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  background:var(--bg);color:var(--ink);
  font-family:'DM Mono',monospace;font-weight:300;
  font-size:13px;line-height:1.85;
  min-height:100vh;
}

/* ── SCROLLBAR ── */
::-webkit-scrollbar{width:4px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background:var(--faint)}

/* ── NAV ── */
nav{
  position:fixed;top:0;left:0;right:0;z-index:100;
  display:flex;justify-content:space-between;align-items:center;
  padding:15px 56px; /* Adjusted for mobile buttons */
  backdrop-filter:blur(12px);
  background:rgba(249,247,244,.88);
  border-bottom:1px solid transparent;
  transition:border-color .3s;
}
nav.scrolled{border-color:var(--faint)}
.nav-logo{
  font-family:'Cormorant Garamond',serif;
  font-size:19px;font-weight:300;letter-spacing:.06em;
  cursor:pointer;
}
.nav-logo span{font-style:italic;color:var(--accent)}
.nav-links{display:flex;gap:15px;align-items:center} /* Tightened for utility buttons */
.nav-links a{
  text-decoration:none;color:var(--muted);
  font-size:10px;letter-spacing:.12em;text-transform:uppercase;
  transition:color .2s;
}
.nav-links a:hover{color:var(--ink)}

/* Button Styles */
.nav-btn-util {
  font-size: 9px;
  letter-spacing: .1em;
  color: var(--muted);
  background: none;
  border: 1px solid var(--faint);
  padding: 4px 8px;
  cursor: pointer;
  transition: all .2s;
}
.nav-btn-util:hover { border-color: var(--accent2); color: var(--ink); }

.nav-edit-toggle{
  font-size:10px;letter-spacing:.12em;text-transform:uppercase;
  color:var(--accent);background:none;border:1px solid var(--accent2);
  padding:5px 14px;cursor:pointer;transition:all .2s;
}
.nav-edit-toggle:hover{background:var(--accent);color:#fff;border-color:var(--accent)}
.nav-edit-toggle.active{background:var(--accent);color:#fff;border-color:var(--accent)}

/* ── LAYOUT ── */
.wrap{max-width:900px;margin:0 auto;padding:0 56px}

section{padding:88px 0;border-bottom:1px solid var(--faint)}
section:last-child{border-bottom:none}

/* ── HERO ── */
#hero{padding-top:172px;padding-bottom:108px;border-bottom:1px solid var(--faint)}
.hero-tag{
  font-size:10px;letter-spacing:.22em;text-transform:uppercase;
  color:var(--muted);margin-bottom:20px;
  opacity:0;animation:rise .7s .1s both;
}
.hero-name{
  font-family:'Cormorant Garamond',serif;
  font-size:clamp(58px,9vw,100px);
  font-weight:300;line-height:1;
  letter-spacing:-.02em;margin-bottom:12px;
  opacity:0;animation:rise .8s .2s both;
}
.hero-name em{font-style:italic;color:var(--accent)}
.hero-subtitle{
  font-size:13px;color:var(--muted);
  max-width:480px;line-height:2;margin-bottom:36px;
  opacity:0;animation:rise .8s .35s both;
}
.hero-meta{
  display:flex;flex-wrap:wrap;gap:10px;
  opacity:0;animation:rise .8s .5s both;
}
.chip{
  border:1px solid var(--faint);background:var(--bg2);
  padding:5px 14px;font-size:10px;letter-spacing:.08em;
  color:var(--muted);border-radius:0;
}

/* ── SECTION HEADING ── */
.sh{
  font-size:10px;letter-spacing:.25em;text-transform:uppercase;
  color:var(--accent);margin-bottom:44px;
  display:flex;align-items:center;gap:18px;
}
.sh::after{content:'';flex:1;height:1px;background:var(--faint)}

/* ── ADD BUTTON ── */
.add-btn{
  display:none;align-items:center;gap:6px;
  font-family:'DM Mono',monospace;font-size:10px;
  letter-spacing:.12em;text-transform:uppercase;
  color:var(--muted);background:none;border:1px dashed var(--faint);
  padding:10px 20px;cursor:pointer;margin-top:24px;
  transition:all .2s;width:100%;justify-content:center;
}
.add-btn:hover{border-color:var(--accent);color:var(--accent)}
.edit-mode .add-btn{display:flex}

/* ── CAREER TIMELINE ── */
.timeline{display:flex;flex-direction:column}
.tl-item{
  display:grid;grid-template-columns:110px 1fr;
  gap:0 36px;padding:30px 0;
  border-bottom:1px solid var(--faint);
  position:relative;
}
.tl-item:last-child{border-bottom:none}
.tl-year{
  font-size:11px;letter-spacing:.06em;color:var(--muted);
  padding-top:3px;font-style:italic;
}
.tl-title{
  font-family:'Cormorant Garamond',serif;
  font-size:22px;font-weight:400;margin-bottom:3px;
}
.tl-org{color:var(--muted);font-size:11px;margin-bottom:8px;letter-spacing:.04em}
.tl-desc{color:var(--muted);font-size:12px;line-height:2}
.item-actions{
  display:none;position:absolute;top:28px;right:0;
  gap:8px;
}
.edit-mode .item-actions{display:flex}
.ia-btn{
  font-size:10px;letter-spacing:.1em;color:var(--muted);
  background:none;border:1px solid var(--faint);
  padding:4px 10px;cursor:pointer;transition:all .2s;
}
.ia-btn:hover{border-color:var(--ink);color:var(--ink)}
.ia-btn.del:hover{border-color:var(--danger);color:var(--danger)}

/* ── SKILLS ── */
.skills-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.skill-card{
  border:1px solid var(--faint);padding:24px;
  background:var(--bg2);position:relative;
}

/* ── PROJECTS ── */
.projects-list{display:flex;flex-direction:column}
.proj-item{
  display:grid;grid-template-columns:1fr auto;
  gap:24px;align-items:start;
  padding:30px 0;border-bottom:1px solid var(--faint);
  position:relative;
}
.proj-item:last-child{border-bottom:none}
.proj-title{
  font-family:'Cormorant Garamond',serif;
  font-size:22px;font-weight:400;margin-bottom:6px;
}
.proj-desc{color:var(--muted);font-size:12px;line-height:2;margin-bottom:10px}
.proj-tags{display:flex;flex-wrap:wrap;gap:6px}
.ptag{
  font-size:9px;letter-spacing:.1em;text-transform:uppercase;
  border:1px solid var(--faint);padding:3px 10px;color:var(--muted);
}
.proj-link{
  font-size:10px;letter-spacing:.1em;text-transform:uppercase;
  color:var(--muted);text-decoration:none;
  border-bottom:1px solid var(--faint);
  transition:all .2s;white-space:nowrap;padding-top:4px;
}
.proj-link:hover{color:var(--accent);border-color:var(--accent)}

/* ── FUTURE ── */
.future-list{display:flex;flex-direction:column}
.fut-item{
  display:grid;grid-template-columns:36px 1fr;
  gap:0 24px;padding:24px 0;
  border-bottom:1px solid var(--faint);position:relative;
}
.fut-item:last-child{border-bottom:none}
.fut-num{
  font-family:'Cormorant Garamond',serif;
  font-size:32px;color:var(--faint);line-height:1;
  margin-top:-2px;
}
.fut-title{font-size:13px;margin-bottom:4px;letter-spacing:.02em}
.fut-desc{color:var(--muted);font-size:12px;line-height:1.9}
.fut-horizon{
  display:inline-block;font-size:9px;letter-spacing:.15em;
  text-transform:uppercase;color:var(--future);
  margin-top:8px;
}

/* ── BOOKS ── */
.books-list{display:flex;flex-direction:column}
.book-item{
  display:grid;grid-template-columns:44px 1fr auto;
  gap:0 20px;padding:22px 0;
  border-bottom:1px solid var(--faint);align-items:start;
  position:relative;
}
.book-item:last-child{border-bottom:none}
.book-n{
  font-family:'Cormorant Garamond',serif;
  font-size:26px;color:var(--faint);line-height:1;padding-top:2px;
}
.book-title{
  font-family:'Cormorant Garamond',serif;
  font-size:19px;font-weight:400;margin-bottom:3px;
}
.book-author{color:var(--muted);font-size:11px;margin-bottom:6px}
.book-note{color:var(--muted);font-size:12px;line-height:1.9}
.book-kind{
  font-size:8px;letter-spacing:.15em;text-transform:uppercase;
  padding:4px 10px;margin-top:2px;
  background:var(--bg2);border:1px solid var(--faint);
  color:var(--muted);white-space:nowrap;height:fit-content;
}
.book-kind.paper{color:var(--future);border-color:var(--future);background:none}

/* ── PHOTOS ── */
.photos-intro{color:var(--muted);font-size:12px;margin-bottom:28px;line-height:2}
.photos-grid{
  display:grid;grid-template-columns:repeat(3,1fr);
  gap:3px;
}
.photo-slot{
  aspect-ratio:1;background:var(--bg2);
  border:1px solid var(--faint);
  display:flex;align-items:center;justify-content:center;
  position:relative;overflow:hidden;cursor:pointer;
  transition:border-color .2s;
}
.photo-slot:hover{border-color:var(--accent2)}
.photo-slot img{
  width:100%;height:100%;object-fit:cover;
  display:none;
}
.photo-slot.filled img{display:block}
.photo-slot.filled .ph-empty{display:none}
.ph-empty{text-align:center;color:var(--muted);pointer-events:none}
.ph-empty .plus{font-size:20px;display:block;margin-bottom:6px;color:var(--faint)}
.ph-empty span{font-size:9px;letter-spacing:.12em;text-transform:uppercase}
.ph-cap{
  position:absolute;bottom:0;left:0;right:0;
  background:rgba(28,26,23,.75);color:#fff;
  font-size:10px;padding:7px 10px;
  transform:translateY(100%);transition:transform .22s;
}
.photo-slot:hover .ph-cap{transform:none}
.ph-del{
  position:absolute;top:6px;right:6px;
  background:rgba(28,26,23,.6);color:#fff;
  border:none;width:22px;height:22px;
  font-size:12px;cursor:pointer;
  display:none;align-items:center;justify-content:center;
}
.edit-mode .ph-del{display:flex}

/* ── MODAL ── */
.overlay{
  display:none;position:fixed;inset:0;
  background:rgba(28,26,23,.55);z-index:200;
  align-items:center;justify-content:center;
  padding:24px;
}
.overlay.open{display:flex}
.modal{
  background:var(--bg);border:1px solid var(--faint);
  padding:40px;width:520px;max-width:100%;
  max-height:90vh;overflow-y:auto;
  animation:slideUp .25s both;
}
@keyframes slideUp{from{opacity:0;transform:translateY(16px)}to{opacity:1;transform:none}}
.modal h3{
  font-family:'Cormorant Garamond',serif;
  font-size:24px;font-weight:300;margin-bottom:28px;
}
.field{margin-bottom:18px}
.field label{
  display:block;font-size:9px;letter-spacing:.2em;
  text-transform:uppercase;color:var(--muted);margin-bottom:6px;
}
.field input,.field textarea,.field select{
  width:100%;background:none;border:1px solid var(--faint);
  padding:10px 14px;font-family:'DM Mono',monospace;
  font-size:12px;color:var(--ink);outline:none;
  transition:border-color .2s;appearance:none;
}
.field input:focus,.field textarea:focus,.field select:focus{border-color:var(--accent)}
.field textarea{min-height:80px;resize:vertical;line-height:1.8}
.field-row{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.modal-actions{display:flex;gap:12px;margin-top:28px;justify-content:flex-end}
.btn{
  padding:10px 24px;font-family:'DM Mono',monospace;
  font-size:10px;letter-spacing:.12em;text-transform:uppercase;
  cursor:pointer;border:1px solid var(--ink);background:none;
  color:var(--ink);transition:all .2s;
}
.btn:hover{background:var(--ink);color:var(--bg)}
.btn-ghost{border-color:var(--faint);color:var(--muted)}
.btn-ghost:hover{background:var(--faint);color:var(--ink)}
.checkbox-row{display:flex;align-items:center;gap:10px;margin-top:4px}
.checkbox-row input[type=checkbox]{width:auto;border:none}

/* ── EMPTY STATE ── */
.empty-state{
  text-align:center;padding:48px 24px;
  color:var(--muted);font-size:12px;
  border:1px dashed var(--faint);
}
.empty-state .es-icon{font-size:28px;margin-bottom:12px;opacity:.4}

/* ── ANIMATIONS ── */
@keyframes rise{from{opacity:0;transform:translateY(18px)}to{opacity:1;transform:none}}
.reveal{opacity:0;transform:translateY(14px);transition:opacity .6s,transform .6s}
.reveal.in{opacity:1;transform:none}

/* ── EDIT MODE INDICATOR ── */
.edit-banner{
  display:none;position:fixed;bottom:0;left:0;right:0;z-index:99;
  background:var(--accent);color:#fff;
  text-align:center;font-size:10px;letter-spacing:.18em;
  text-transform:uppercase;padding:8px;
}
.edit-mode .edit-banner{display:block}

/* ── PROFILE SECTION ── */
.profile-grid{display:grid;grid-template-columns:140px 1fr;gap:40px;align-items:start}
.profile-img-wrap{
  aspect-ratio:1;background:var(--bg2);border:1px solid var(--faint);
  display:flex;align-items:center;justify-content:center;
  cursor:pointer;position:relative;overflow:hidden;
}
.profile-img-wrap img{width:100%;height:100%;object-fit:cover;display:none}
.profile-img-wrap.filled img{display:block}
.profile-img-wrap.filled .profile-ph{display:none}
.profile-ph{color:var(--muted);font-size:10px;text-align:center;letter-spacing:.1em}
.profile-info{}
.profile-name{
  font-family:'Cormorant Garamond',serif;
  font-size:36px;font-weight:300;margin-bottom:6px;
}
.profile-name em{font-style:italic;color:var(--accent)}
.profile-tagline{color:var(--muted);font-size:12px;line-height:2;margin-bottom:16px}
.profile-chips{display:flex;flex-wrap:wrap;gap:8px}

/* RESPONSIVE */
@media(max-width:640px){
  nav{padding:10px 15px}
  .nav-logo{font-size:14px}
  .nav-links{gap:8px}
  .nav-links a:not([id="editToggle"]){display:none} /* Hide anchors on mobile to save space */
  .wrap{padding:0 24px}
  .skills-grid{grid-template-columns:1fr}
  .profile-grid{grid-template-columns:1fr;gap:24px}
  .tl-item{grid-template-columns:1fr;gap:4px}
  .book-item{grid-template-columns:36px 1fr;gap:0 14px}
  .book-kind{display:none}
}
</style>
</head>
<body>

<div class="edit-banner">✎ 編集モード — 各項目の ✎ ボタンで編集 · ＋ ボタンで追加</div>

<nav id="mainnav">
  <span class="nav-logo" onclick="window.scrollTo({top:0,behavior:'smooth'})">My <em>Universe</em></span>
  <div class="nav-links">
    <button class="nav-btn-util" onclick="exportData()" title="Backup">↓ 保存</button>
    <button class="nav-btn-util" onclick="document.getElementById('importFile').click()" title="Restore">↑ 読込</button>
    <input type="file" id="importFile" style="display:none" onchange="importData(event)">
    <button class="nav-edit-toggle" id="editToggle" onclick="toggleEditMode()">✎ 編集</button>
  </div>
</nav>

<div class="wrap">

  <section id="about">
    <div class="sh">About</div>
    <div class="profile-grid">
      <div class="profile-img-wrap" id="profileImgWrap" onclick="triggerProfileImg()">
        <img id="profileImg" src="" alt="">
        <div class="profile-ph">
          <div style="font-size:28px;margin-bottom:6px;opacity:.3">◯</div>
          <span>写真を追加</span>
        </div>
      </div>
      <div class="profile-info">
        <div class="profile-name" id="profileName">Your <em>Name</em></div>
        <div class="profile-tagline" id="profileTagline">ここに自己紹介を書いてください。</div>
        <div class="profile-chips" id="profileChips"></div>
        <div style="margin-top:20px;display:none" id="profileEditBtn">
          <button class="add-btn" style="width:auto;padding:8px 18px;display:inline-flex" onclick="openProfileModal()">✎ プロフィールを編集</button>
        </div>
      </div>
    </div>
  </section>

  <section id="career">
    <div class="sh">経歴 / Career & Skills</div>
    <div class="timeline" id="timeline"></div>
    <button class="add-btn" onclick="openModal('career')">＋ 経歴・資格を追加</button>
  </section>

  <section id="projects">
    <div class="sh">Projects / Portfolio</div>
    <div class="projects-list" id="projectsList"></div>
    <button class="add-btn" onclick="openModal('project')">＋ プロジェクトを追加</button>
  </section>

  <section id="future">
    <div class="sh">Future / 未来の目標・計画</div>
    <div class="future-list" id="futureList"></div>
    <button class="add-btn" onclick="openModal('future')">＋ 目標・計画を追加</button>
  </section>

  <section id="books">
    <div class="sh">Books & Papers / 読書・論文リスト</div>
    <div class="books-list" id="booksList"></div>
    <button class="add-btn" onclick="openModal('book')">＋ 本・論文を追加</button>
  </section>

  <section id="photos">
    <div class="sh">Photos / 日々のかけら</div>
    <p class="photos-intro">写真はブラウザのLocalStorageに保存され、外部には送信されません。</p>
    <div class="photos-grid" id="photosGrid"></div>
    <button class="add-btn" onclick="addPhotoSlot()">＋ 写真スロットを追加</button>
  </section>

</div><div style="text-align:center;padding:48px 24px;color:var(--muted);font-size:10px;letter-spacing:.1em;border-top:1px solid var(--faint)">
  My Private Universe — Local Persistence Mode
</div>

<div class="overlay" id="overlay" onclick="overlayClick(event)">
  <div class="modal" id="modal"></div>
</div>

<input type="file" id="photoInput" accept="image/*" style="display:none">
<input type="file" id="profileImgInput" accept="image/*" style="display:none">

<script>
/* ════════════════════════════════════════
   STATE
════════════════════════════════════════ */
let state = {
  profile: {
    name: 'Your Name',
    nameItalic: '',
    tagline: 'ここに自己紹介を書いてください。\n研究テーマ、関心事、大切にしていることなど。',
    chips: [],
    img: ''
  },
  career: [],
  projects: [],
  future: [],
  books: [],
  photos: []
};

let editMode = false;
let editingId = null;
let editingSection = null;
let photoSlotTarget = null;

/* ════════════════════════════════════════
   STORAGE & BACKUP
════════════════════════════════════════ */
function save() {
  try { localStorage.setItem('myuniverse_state', JSON.stringify(state)); } catch(e){
    if(e.name === 'QuotaExceededError') {
      alert('保存容量がいっぱいです。大きな画像などを削除してください。');
    }
  }
}

function load() {
  try {
    const s = localStorage.getItem('myuniverse_state');
    if (s) state = JSON.parse(s);
  } catch(e){}
}

function exportData() {
  const dataStr = JSON.stringify(state, null, 2);
  const blob = new Blob([dataStr], {type: "application/json"});
  const url = URL.createObjectURL(blob);
  const link = document.createElement('a');
  link.href = url;
  link.download = `my_universe_backup_${new Date().toISOString().slice(0,10)}.json`;
  link.click();
  URL.revokeObjectURL(url);
}

function importData(event) {
  const file = event.target.files[0];
  if (!file) return;
  const reader = new FileReader();
  reader.onload = function(e) {
    try {
      const imported = JSON.parse(e.target.result);
      if (confirm('データを上書きして復元しますか？')) {
        state = imported;
        save();
        renderAll();
      }
    } catch (err) { alert('ファイルの読み込みに失敗しました。'); }
  };
  reader.readAsText(file);
  event.target.value = '';
}

/* ════════════════════════════════════════
   EDIT MODE
════════════════════════════════════════ */
function toggleEditMode() {
  editMode = !editMode;
  document.body.classList.toggle('edit-mode', editMode);
  const btn = document.getElementById('editToggle');
  btn.textContent = editMode ? '✓ 完了' : '✎ 編集';
  btn.classList.toggle('active', editMode);
  document.getElementById('profileEditBtn').style.display = editMode ? 'block' : 'none';
  renderAll(); // Re-render to show/hide action buttons
}

/* ════════════════════════════════════════
   RENDER ENGINE
════════════════════════════════════════ */
function uid() { return Date.now().toString(36) + Math.random().toString(36).slice(2); }

function renderAll() {
  renderProfile();
  renderCareer();
  renderProjects();
  renderFuture();
  renderBooks();
  renderPhotos();
}

function renderProfile() {
  const p = state.profile;
  document.getElementById('profileName').innerHTML = p.name + (p.nameItalic ? ` <em>${p.nameItalic}</em>` : '');
  document.getElementById('profileTagline').innerHTML = p.tagline.replace(/\n/g,'<br>');
  document.getElementById('profileChips').innerHTML = p.chips.map(c=>`<span class="chip">${c}</span>`).join('');
  const imgEl = document.getElementById('profileImg');
  const wrap = document.getElementById('profileImgWrap');
  if (p.img) { imgEl.src = p.img; wrap.classList.add('filled'); }
  else { wrap.classList.remove('filled'); }
}

function renderCareer() {
  const el = document.getElementById('timeline');
  if (!state.career.length) { el.innerHTML = `<div class="empty-state">経歴がありません</div>`; return; }
  el.innerHTML = state.career.map(item => `
    <div class="tl-item ${item.future?'future':''} reveal in">
      <div class="tl-year">${item.year||'—'}</div>
      <div class="tl-body">
        <div class="tl-title">${item.title}</div>
        ${item.org?`<div class="tl-org">${item.org}</div>`:''}
        ${item.desc?`<div class="tl-desc">${item.desc.replace(/\n/g,'<br>')}</div>`:''}
      </div>
      <div class="item-actions">
        <button class="ia-btn" onclick="openModal('career','${item.id}')">✎</button>
        <button class="ia-btn del" onclick="deleteItem('career','${item.id}')">✕</button>
      </div>
    </div>
  `).join('');
}

function renderProjects() {
  const el = document.getElementById('projectsList');
  if (!state.projects.length) { el.innerHTML = `<div class="empty-state">プロジェクトがありません</div>`; return; }
  el.innerHTML = state.projects.map(item => `
    <div class="proj-item reveal in">
      <div>
        <div class="proj-title">${item.title}</div>
        <div class="proj-desc">${item.desc.replace(/\n/g,'<br>')}</div>
        <div class="proj-tags">${(item.tags||[]).map(t=>`<span class="ptag">${t}</span>`).join('')}</div>
      </div>
      <div style="display:flex;flex-direction:column;align-items:flex-end;gap:8px">
        ${item.link?`<a class="proj-link" href="${item.link}" target="_blank">→ LINK</a>`:''}
        <div class="item-actions" style="position:static; display:${editMode?'flex':'none'}">
          <button class="ia-btn" onclick="openModal('project','${item.id}')">✎</button>
          <button class="ia-btn del" onclick="deleteItem('project','${item.id}')">✕</button>
        </div>
      </div>
    </div>
  `).join('');
}

function renderFuture() {
  const el = document.getElementById('futureList');
  el.innerHTML = state.future.map((item,i) => `
    <div class="fut-item reveal in">
      <div class="fut-num">${i+1}</div>
      <div>
        <div class="fut-title">${item.title}</div>
        <div class="fut-desc">${item.desc}</div>
        <div class="fut-horizon">${item.horizon}</div>
      </div>
      <div class="item-actions">
        <button class="ia-btn" onclick="openModal('future','${item.id}')">✎</button>
        <button class="ia-btn del" onclick="deleteItem('future','${item.id}')">✕</button>
      </div>
    </div>
  `).join('');
}

function renderBooks() {
  const el = document.getElementById('booksList');
  el.innerHTML = state.books.map(item => `
    <div class="book-item reveal in">
      <div class="book-n">#</div>
      <div>
        <div class="book-title">${item.title}</div>
        <div class="book-author">${item.author}</div>
        <div class="book-note">${item.note}</div>
      </div>
      <div class="item-actions" style="position:static; display:${editMode?'flex':'none'}">
        <button class="ia-btn" onclick="openModal('book','${item.id}')">✎</button>
        <button class="ia-btn del" onclick="deleteItem('book','${item.id}')">✕</button>
      </div>
    </div>
  `).join('');
}

function renderPhotos() {
  const grid = document.getElementById('photosGrid');
  grid.innerHTML = state.photos.map((p,i) => `
    <div class="photo-slot ${p.img?'filled':''}" onclick="handlePhotoClick(${i})">
      <img src="${p.img||''}">
      <div class="ph-empty">＋</div>
      ${p.cap?`<div class="ph-cap">${p.cap}</div>`:''}
      <button class="ph-del" onclick="deletePhoto(event,${i})">✕</button>
    </div>
  `).join('');
}

/* ════════════════════════════════════════
   MODALS
════════════════════════════════════════ */
function openModal(section, id) {
  editingSection = section;
  editingId = id || null;
  const list = (section==='career'?state.career : section==='project'?state.projects : section==='future'?state.future : state.books);
  const existing = id ? list.find(x=>x.id===id) : null;

  let html = `<h3>編集</h3>`;
  if(section==='career') {
    html += `
      <div class="field"><label>年</label><input id="f_year" value="${existing?.year||''}"></div>
      <div class="field"><label>タイトル</label><input id="f_title" value="${existing?.title||''}"></div>
      <div class="field"><label>組織</label><input id="f_org" value="${existing?.org||''}"></div>
      <div class="field"><label>詳細</label><textarea id="f_desc">${existing?.desc||''}</textarea></div>
      <div class="modal-actions"><button class="btn" onclick="saveCareer()">保存</button></div>
    `;
  } else if(section==='project') {
    html += `
      <div class="field"><label>タイトル</label><input id="f_title" value="${existing?.title||''}"></div>
      <div class="field"><label>説明</label><textarea id="f_desc">${existing?.desc||''}</textarea></div>
      <div class="field"><label>タグ (カンマ区切り)</label><input id="f_tags" value="${(existing?.tags||[]).join(',')}"></div>
      <div class="field"><label>URL</label><input id="f_link" value="${existing?.link||''}"></div>
      <div class="modal-actions"><button class="btn" onclick="saveProject()">保存</button></div>
    `;
  } else if(section==='future') {
    html += `
      <div class="field"><label>目標</label><input id="f_title" value="${existing?.title||''}"></div>
      <div class="field"><label>詳細</label><textarea id="f_desc">${existing?.desc||''}</textarea></div>
      <div class="field"><label>時期</label><input id="f_horizon" value="${existing?.horizon||''}"></div>
      <div class="modal-actions"><button class="btn" onclick="saveFuture()">保存</button></div>
    `;
  } else if(section==='book') {
    html += `
      <div class="field"><label>タイトル</label><input id="f_title" value="${existing?.title||''}"></div>
      <div class="field"><label>著者</label><input id="f_author" value="${existing?.author||''}"></div>
      <div class="field"><label>メモ</label><textarea id="f_note">${existing?.note||''}</textarea></div>
      <div class="modal-actions"><button class="btn" onclick="saveBook()">保存</button></div>
    `;
  }

  document.getElementById('modal').innerHTML = html;
  document.getElementById('overlay').classList.add('open');
}

function openProfileModal() {
  const p = state.profile;
  document.getElementById('modal').innerHTML = `
    <h3>プロフィール編集</h3>
    <div class="field"><label>名前</label><input id="f_name" value="${p.name}"></div>
    <div class="field"><label>名前(イタリック)</label><input id="f_nameitalic" value="${p.nameItalic||''}"></div>
    <div class="field"><label>自己紹介</label><textarea id="f_tagline">${p.tagline}</textarea></div>
    <div class="field"><label>タグ</label><input id="f_chips" value="${p.chips.join(',')}"></div>
    <div class="modal-actions"><button class="btn" onclick="saveProfile()">保存</button></div>
  `;
  document.getElementById('overlay').classList.add('open');
}

function closeModal() { document.getElementById('overlay').classList.remove('open'); }
function overlayClick(e) { if(e.target.id==='overlay') closeModal(); }

/* ════════════════════════════════════════
   SAVE LOGIC
════════════════════════════════════════ */
function saveProfile() {
  state.profile.name = document.getElementById('f_name').value;
  state.profile.nameItalic = document.getElementById('f_nameitalic').value;
  state.profile.tagline = document.getElementById('f_tagline').value;
  state.profile.chips = document.getElementById('f_chips').value.split(',').map(s=>s.trim()).filter(Boolean);
  save(); renderProfile(); closeModal();
}

function saveCareer() {
  const data = {
    id: editingId || uid(),
    year: document.getElementById('f_year').value,
    title: document.getElementById('f_title').value,
    org: document.getElementById('f_org').value,
    desc: document.getElementById('f_desc').value
  };
  if(editingId) { const idx = state.career.findIndex(x=>x.id===editingId); state.career[idx] = data; }
  else { state.career.push(data); }
  save(); renderCareer(); closeModal();
}

function saveProject() {
  const data = {
    id: editingId || uid(),
    title: document.getElementById('f_title').value,
    desc: document.getElementById('f_desc').value,
    tags: document.getElementById('f_tags').value.split(',').map(s=>s.trim()).filter(Boolean),
    link: document.getElementById('f_link').value
  };
  if(editingId) { const idx = state.projects.findIndex(x=>x.id===editingId); state.projects[idx] = data; }
  else { state.projects.push(data); }
  save(); renderProjects(); closeModal();
}

function saveFuture() {
  const data = {
    id: editingId || uid(),
    title: document.getElementById('f_title').value,
    desc: document.getElementById('f_desc').value,
