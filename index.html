<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>congresso de jovens · inscrição</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Anton&family=Space+Mono:wght@400;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
<style>
  :root{
    --paper:#F2ECE0;
    --paper-2:#EBE3D3;
    --ink:#2B2A28;
    --ink-soft:#6B675E;
    --line:#C9C1AE;
    --terracota:#CB5A3B;
    --teal:#4C7C8A;
    --ochre:#C1902E;
    --plum:#8A4A42;
    --font-display:'Anton', sans-serif;
    --font-mono:'Space Mono', monospace;
    --font-body:'Inter', sans-serif;
  }
  *{ box-sizing:border-box; }
  html,body{ margin:0; padding:0; }
  body{
    background-color:var(--paper);
    background-image:
      radial-gradient(circle at 20% 15%, rgba(203,90,59,0.05), transparent 45%),
      radial-gradient(circle at 85% 80%, rgba(76,124,138,0.06), transparent 45%),
      url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='120' height='120'><filter id='n'><feTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2' stitchTiles='stitch'/><feColorMatrix type='matrix' values='0 0 0 0 0  0 0 0 0 0  0 0 0 0 0  0 0 0 0.035 0'/></filter><rect width='100%' height='100%' filter='url(%23n)'/></svg>");
    color:var(--ink);
    font-family:var(--font-body);
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    padding:28px 16px;
    -webkit-font-smoothing:antialiased;
  }
  button, input{ font-family:inherit; }
  button{ cursor:pointer; }
  ::selection{ background:var(--terracota); color:var(--paper); }
  :focus-visible{ outline:2px solid var(--terracota); outline-offset:3px; border-radius:4px; }

  .card{
    width:100%;
    max-width:440px;
    background:var(--paper-2);
    border:1px solid var(--line);
    border-radius:6px;
    padding:36px 30px 30px;
    position:relative;
  }

  /* divider with squiggle */
  .divider{
    display:flex; align-items:center; gap:10px;
    margin:16px 0 22px;
  }
  .divider .rule{ flex:1; height:1px; background:var(--line); }
  .divider svg{ flex-shrink:0; opacity:0.85; }

  .eyebrow{
    font-family:var(--font-mono);
    font-size:11px;
    font-weight:700;
    letter-spacing:3.5px;
    text-transform:uppercase;
    color:var(--ink);
    text-align:center;
    margin:0;
  }

  h1.headline{
    font-family:var(--font-display);
    font-weight:400;
    text-transform:uppercase;
    text-align:center;
    line-height:0.98;
    letter-spacing:0.5px;
    margin:0;
  }
  h1.headline .l1{
    display:block;
    font-size:38px;
    color:var(--terracota);
  }
  h1.headline .l2{
    display:block;
    font-size:38px;
    color:var(--teal);
  }

  p.sub{
    font-size:13px;
    color:var(--ink-soft);
    text-align:center;
    line-height:1.55;
    margin:14px 0 0;
  }

  .field{ margin-bottom:16px; }
  .field label{
    display:block;
    font-family:var(--font-mono);
    font-size:10.5px;
    font-weight:700;
    letter-spacing:1.5px;
    text-transform:uppercase;
    color:var(--ink-soft);
    margin-bottom:7px;
  }
  .field input{
    width:100%;
    background:var(--paper);
    border:1px solid var(--line);
    color:var(--ink);
    font-size:15px;
    padding:13px 14px;
    border-radius:4px;
    transition:border-color .15s ease;
  }
  .field input:focus{ border-color:var(--terracota); }
  .field input::placeholder{ color:#A9A190; }

  .submit-btn{
    width:100%;
    margin-top:6px;
    background:var(--terracota);
    color:var(--paper);
    border:none;
    border-radius:4px;
    padding:14px;
    font-family:var(--font-mono);
    font-weight:700;
    font-size:13px;
    letter-spacing:2px;
    text-transform:uppercase;
    transition:background .15s ease, transform .12s ease;
  }
  .submit-btn:hover{ background:#B34A2E; }
  .submit-btn:active{ transform:scale(0.98); }
  .submit-btn:disabled{ opacity:0.55; cursor:default; }

  .error-msg{
    font-size:12.5px;
    color:var(--plum);
    text-align:center;
    margin:-6px 0 14px;
  }

  .hint{
    font-size:11px;
    color:#A9A190;
    text-align:center;
    margin-top:18px;
    line-height:1.5;
  }

  /* dial */
  .dial-wrap{ display:flex; justify-content:center; margin:6px 0 4px; }
  .dial-status{
    font-family:var(--font-mono);
    font-size:11px;
    letter-spacing:2px;
    text-transform:uppercase;
    color:var(--ink-soft);
    text-align:center;
    margin-top:10px;
  }

  .result-note{
    font-size:13px;
    color:var(--ink-soft);
    text-align:center;
    line-height:1.55;
    margin:12px 0 4px;
  }
  .again-btn{
    width:100%;
    background:transparent;
    border:1px solid var(--line);
    color:var(--ink-soft);
    border-radius:4px;
    padding:11px;
    font-family:var(--font-mono);
    font-size:11.5px;
    letter-spacing:1.5px;
    text-transform:uppercase;
    margin-top:18px;
  }
  .again-btn:hover{ color:var(--ink); border-color:var(--ink-soft); }

  .verse{
    font-size:12.5px;
    font-style:italic;
    text-align:center;
    color:var(--ink-soft);
    line-height:1.6;
    margin:0 0 6px;
    text-transform:uppercase;
    letter-spacing:0.3px;
  }
  .verse-ref{
    font-family:var(--font-mono);
    font-size:11px;
    font-weight:700;
    letter-spacing:2px;
    color:var(--terracota);
    text-align:center;
    text-transform:uppercase;
  }

  /* admin */
  .admin-title{
    font-family:var(--font-display);
    font-size:24px;
    text-transform:uppercase;
    color:var(--ink);
    text-align:center;
    margin:0;
  }
  .admin-sub{
    font-size:12px;
    color:var(--ink-soft);
    text-align:center;
    margin:8px 0 0;
  }
  .total-hero{
    text-align:center;
    margin:22px 0;
    padding:20px 10px;
    border:1px solid var(--line);
    border-radius:4px;
    background:var(--paper);
  }
  .total-num{
    font-family:var(--font-display);
    font-size:52px;
    color:var(--terracota);
    line-height:1;
  }
  .total-label{
    font-family:var(--font-mono);
    font-size:11px;
    letter-spacing:2.5px;
    text-transform:uppercase;
    color:var(--ink-soft);
    margin-top:6px;
  }
  .qr-box{
    background:#fff;
    border:1px solid var(--line);
    border-radius:4px;
    padding:14px;
    display:flex;
    align-items:center;
    justify-content:center;
    margin-bottom:22px;
  }
  .bars{ margin:18px 0 6px; }
  .bar-row{ margin-bottom:14px; }
  .bar-label{
    display:flex;
    justify-content:space-between;
    font-family:var(--font-mono);
    font-size:11.5px;
    letter-spacing:1px;
    text-transform:uppercase;
    margin-bottom:6px;
    color:var(--ink);
  }
  .bar-track{
    height:9px;
    background:var(--paper);
    border:1px solid var(--line);
    border-radius:5px;
    overflow:hidden;
  }
  .bar-fill{ height:100%; border-radius:5px; transition:width .4s ease; }

  .list-toggle-row{ display:flex; gap:10px; margin-top:6px; }
  .list-toggle-row button{
    flex:1;
    background:transparent;
    border:1px solid var(--line);
    color:var(--ink-soft);
    border-radius:4px;
    padding:11px;
    font-family:var(--font-mono);
    font-size:10.5px;
    letter-spacing:1.5px;
    text-transform:uppercase;
  }
  .list-toggle-row button:hover{ color:var(--ink); }

  .people-list{
    margin-top:16px;
    max-height:320px;
    overflow-y:auto;
    border:1px solid var(--line);
    border-radius:4px;
    background:var(--paper);
  }
  .person-row{
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:10px;
    padding:11px 13px;
    border-bottom:1px solid var(--line);
  }
  .person-row:last-child{ border-bottom:none; }
  .person-main{ min-width:0; }
  .person-name{
    font-size:13px;
    color:var(--ink);
    white-space:nowrap;
    overflow:hidden;
    text-overflow:ellipsis;
  }
  .person-whats{
    font-family:var(--font-mono);
    font-size:11px;
    color:var(--ink-soft);
    margin-top:2px;
  }
  .person-team{
    flex-shrink:0;
    font-family:var(--font-mono);
    font-size:10px;
    font-weight:700;
    letter-spacing:1px;
    text-transform:uppercase;
    padding:4px 8px;
    border-radius:3px;
    white-space:nowrap;
  }
  .list-empty{
    padding:20px;
    text-align:center;
    font-size:12.5px;
    color:var(--ink-soft);
  }
  .list-loading{
    padding:20px;
    text-align:center;
    font-family:var(--font-mono);
    font-size:11px;
    letter-spacing:1.5px;
    text-transform:uppercase;
    color:var(--ink-soft);
  }

  .admin-actions{ display:flex; gap:10px; margin-top:20px; }
  .admin-actions button{
    flex:1;
    background:transparent;
    border:1px solid var(--line);
    color:var(--ink-soft);
    border-radius:4px;
    padding:11px;
    font-family:var(--font-mono);
    font-size:10.5px;
    letter-spacing:1.5px;
    text-transform:uppercase;
  }
  .admin-actions button.danger{ color:var(--plum); border-color:var(--plum); }
  .admin-actions button:hover{ color:var(--ink); }

  @media (prefers-reduced-motion: reduce){
    *{ transition:none !important; animation:none !important; }
  }
</style>
</head>
<body>
<div class="card" id="card"></div>

<script>
(function(){
  var TEAMS = {
    onda:       { label: "Onda",        freq: "88.3",  color: "#4C7C8A" },
    pulso:      { label: "Pulso",       freq: "94.7",  color: "#CB5A3B" },
    sinal:      { label: "Sinal",       freq: "101.5", color: "#C1902E" },
    frequencia: { label: "Frequência",  freq: "107.9", color: "#8A4A42" }
  };
  var TEAM_KEYS = Object.keys(TEAMS);
  var ADMIN_PIN = '1027';
  var reducedMotion = window.matchMedia && window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  var isAdmin = new URLSearchParams(window.location.search).get('admin') === '1';
  var card = document.getElementById('card');

  function squiggleSvg(color, w){
    color = color || '#CB5A3B';
    w = w || 34;
    return '<svg width="' + w + '" height="14" viewBox="0 0 34 14" fill="none">' +
      '<path d="M0 7 L4 7 L6 2 L9 12 L12 4 L15 10 L18 5 L21 9 L24 7 L34 7" stroke="' + color + '" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"/>' +
    '</svg>';
  }

  function dividerHtml(color){
    return '<div class="divider"><span class="rule"></span>' + squiggleSvg(color) + '<span class="rule"></span></div>';
  }

  function hexToRgba(hex, alpha){
    var h = hex.replace('#','');
    var r = parseInt(h.substring(0,2),16);
    var g = parseInt(h.substring(2,4),16);
    var b = parseInt(h.substring(4,6),16);
    return 'rgba(' + r + ',' + g + ',' + b + ',' + alpha + ')';
  }

  function slugify(str){
    return str.toString().normalize('NFD').replace(/[\u0300-\u036f]/g,'')
      .toLowerCase().trim().replace(/[^a-z0-9]+/g,'-').replace(/(^-+|-+$)/g,'');
  }
  function digitsOnly(str){ return (str || '').replace(/\D/g,''); }

  async function getShared(key){
    try{
      var r = await window.storage.get(key, true);
      return r ? r.value : null;
    }catch(e){ return null; }
  }
  async function setShared(key, value){
    try{ return await window.storage.set(key, value, true); }catch(e){ return null; }
  }
  async function deleteShared(key){
    try{ return await window.storage.delete(key, true); }catch(e){ return null; }
  }

  async function getCounts(){
    var raw = await getShared('gincana-counts');
    if (raw){ try{ return JSON.parse(raw); }catch(e){} }
    var init = {}; TEAM_KEYS.forEach(function(k){ init[k]=0; });
    await setShared('gincana-counts', JSON.stringify(init));
    return init;
  }

  function pickTeam(counts){
    var min = Math.min.apply(null, TEAM_KEYS.map(function(k){ return counts[k] || 0; }));
    var candidates = TEAM_KEYS.filter(function(k){ return (counts[k]||0) === min; });
    return candidates[Math.floor(Math.random() * candidates.length)];
  }

  // ---------- SVG dial (matches the poster's tuning dial) ----------
  function buildTicks(cx, cy, rOuter){
    var out = '';
    for (var deg = 0; deg < 360; deg += 6){
      var major = (deg % 30 === 0);
      var rInner = major ? rOuter - 9 : rOuter - 5;
      var rad = (deg - 90) * Math.PI / 180;
      var x1 = cx + rOuter * Math.cos(rad);
      var y1 = cy + rOuter * Math.sin(rad);
      var x2 = cx + rInner * Math.cos(rad);
      var y2 = cy + rInner * Math.sin(rad);
      out += '<line x1="' + x1.toFixed(1) + '" y1="' + y1.toFixed(1) + '" x2="' + x2.toFixed(1) + '" y2="' + y2.toFixed(1) + '" stroke="#2B2A28" stroke-width="' + (major ? 1.4 : 0.8) + '" opacity="' + (major ? 0.55 : 0.3) + '"/>';
    }
    return out;
  }

  function dialSvg(freq, teamLabel, color, pulse){
    var cx = 110, cy = 110, r = 96;
    return '<svg width="230" height="230" viewBox="0 0 220 220">' +
      '<circle cx="' + cx + '" cy="' + cy + '" r="' + r + '" fill="none" stroke="#2B2A28" stroke-width="1.5" opacity="0.7"/>' +
      buildTicks(cx, cy, r) +
      '<line x1="' + cx + '" y1="' + (cy - r - 2) + '" x2="' + cx + '" y2="' + (cy - r + 11) + '" stroke="' + color + '" stroke-width="3" stroke-linecap="round"' + (pulse ? ' class="needle"' : '') + '/>' +
      '<text x="' + cx + '" y="' + (cy - 22) + '" text-anchor="middle" font-family="Space Mono" font-weight="700" font-size="10.5" letter-spacing="2" fill="#2B2A28">SINTONIZE</text>' +
      '<text x="' + cx + '" y="' + (cy + 16) + '" text-anchor="middle" font-family="Anton" font-size="34" fill="' + color + '">' + freq + '</text>' +
      '<text x="' + cx + '" y="' + (cy + 38) + '" text-anchor="middle" font-family="Space Mono" font-weight="700" font-size="9.5" letter-spacing="1.5" fill="#6B675E">EQUIPE ' + teamLabel.toUpperCase() + '</text>' +
    '</svg>';
  }

  // ---------- FORM VIEW ----------
  function renderPinPrompt(){
    card.innerHTML =
      dividerHtml() +
      '<p class="eyebrow">Acesso do organizador</p>' +
      '<p class="sub" style="margin-top:14px;">Digite o código de acesso para ver as inscrições.</p>' +
      '<div style="height:18px"></div>' +
      '<div class="field">' +
        '<label for="pinInput">Código</label>' +
        '<input id="pinInput" type="password" inputmode="numeric" placeholder="••••">' +
      '</div>' +
      '<button class="submit-btn" id="pinBtn">Entrar</button>' +
      '<button class="again-btn" id="pinBackBtn" style="margin-top:10px;">Voltar</button>';

    document.getElementById('pinBtn').addEventListener('click', checkPin);
    document.getElementById('pinInput').addEventListener('keydown', function(e){
      if (e.key === 'Enter') checkPin();
    });
    document.getElementById('pinBackBtn').addEventListener('click', function(){ renderForm(); });
    document.getElementById('pinInput').focus();
  }

  function checkPin(){
    var val = document.getElementById('pinInput').value.trim();
    if (val === ADMIN_PIN){
      renderAdmin();
    } else {
      renderPinPrompt();
      var err = document.createElement('p');
      err.className = 'error-msg';
      err.textContent = 'Código incorreto.';
      document.querySelector('.sub').insertAdjacentElement('afterend', err);
    }
  }

  function renderForm(errorMsg){
    card.innerHTML =
      dividerHtml() +
      '<p class="eyebrow">Congresso de Jovens</p>' +
      '<h1 class="headline"><span class="l1">Uma Geração,</span><span class="l2">Uma Voz</span></h1>' +
      dividerHtml() +
      '<p class="sub">Faça sua inscrição no congresso e descubra, na hora, sua equipe da gincana.</p>' +
      '<div style="height:22px"></div>' +
      (errorMsg ? '<p class="error-msg">' + errorMsg + '</p>' : '') +
      '<div class="field">' +
        '<label for="fname">Nome completo</label>' +
        '<input id="fname" type="text" placeholder="Seu nome" autocomplete="name">' +
      '</div>' +
      '<div class="field">' +
        '<label for="fwhats">WhatsApp</label>' +
        '<input id="fwhats" type="tel" inputmode="tel" placeholder="(00) 00000-0000" autocomplete="tel">' +
      '</div>' +
      '<button class="submit-btn" id="submitBtn">Confirmar inscrição</button>' +
      '<p class="hint">Seus dados só servem para te reconhecer caso escaneie de novo.</p>' +
      '<p class="hint" style="margin-top:14px;"><a href="#" id="adminLink" style="color:inherit; text-decoration:underline;">acesso do organizador</a></p>';

    document.getElementById('adminLink').addEventListener('click', function(e){
      e.preventDefault();
      renderPinPrompt();
    });

    document.getElementById('submitBtn').addEventListener('click', handleSubmit);
    ['fname','fwhats'].forEach(function(id){
      document.getElementById(id).addEventListener('keydown', function(e){
        if (e.key === 'Enter') handleSubmit();
      });
    });
  }

  async function handleSubmit(){
    var name = document.getElementById('fname').value.trim();
    var whats = document.getElementById('fwhats').value.trim();
    var digits = digitsOnly(whats);

    if (name.length < 3){ renderForm('Digite seu nome completo.'); return; }
    if (digits.length < 8){ renderForm('Digite um WhatsApp válido, com DDD.'); return; }

    var btn = document.getElementById('submitBtn');
    btn.disabled = true;
    btn.textContent = 'Sintonizando...';

    var slug = slugify(name) + '-' + digits;
    var personKey = 'gincana-person-' + slug;

    try{
      var existingRaw = await getShared(personKey);
      if (existingRaw){
        var existing = JSON.parse(existingRaw);
        renderTuning(existing.team, true);
        return;
      }

      var counts = await getCounts();
      var team = pickTeam(counts);
      counts[team] = (counts[team] || 0) + 1;
      await setShared('gincana-counts', JSON.stringify(counts));

      var record = { name: name, whatsapp: digits, team: team, ts: Date.now() };
      await setShared(personKey, JSON.stringify(record));

      var indexRaw = await getShared('gincana-index');
      var index = [];
      try{ index = indexRaw ? JSON.parse(indexRaw) : []; }catch(e){ index = []; }
      if (index.indexOf(personKey) === -1) index.push(personKey);
      await setShared('gincana-index', JSON.stringify(index));

      renderTuning(team, false);
    }catch(e){
      renderForm('Algo saiu do ar. Tenta de novo.');
    }
  }

  // ---------- TUNING / RESULT VIEW ----------
  function renderTuning(team, alreadyRegistered){
    card.innerHTML =
      dividerHtml() +
      '<p class="eyebrow">Sintonizando</p>' +
      '<div class="dial-wrap" id="dialWrap">' + dialSvg('--- . -', '', '#6B675E', false) + '</div>' +
      '<p class="dial-status" id="status">Localizando sua frequência</p>';

    var target = TEAMS[team].freq;
    var label = TEAMS[team].label;
    var color = TEAMS[team].color;
    var dialWrap = document.getElementById('dialWrap');

    function finish(){
      dialWrap.innerHTML = dialSvg(target, label, color, true);
      document.getElementById('status').textContent = 'Sinal encontrado';
      setTimeout(function(){ renderResult(team, alreadyRegistered); }, reducedMotion ? 200 : 650);
    }

    if (reducedMotion){ finish(); return; }

    var ticks = 0, maxTicks = 14;
    var iv = setInterval(function(){
      ticks++;
      var rnd = (80 + Math.random() * 40).toFixed(1);
      dialWrap.innerHTML = dialSvg(rnd, '', '#A9A190', false);
      if (ticks >= maxTicks){ clearInterval(iv); finish(); }
    }, 75);
  }

  function renderResult(team, alreadyRegistered){
    var t = TEAMS[team];
    card.innerHTML =
      dividerHtml(t.color) +
      '<p class="eyebrow">' + (alreadyRegistered ? 'Você já está sintonizado' : 'Inscrição confirmada') + '</p>' +
      '<div class="dial-wrap">' + dialSvg(t.freq, t.label, t.color, false) + '</div>' +
      '<p class="result-note">' +
        (alreadyRegistered
          ? 'Bem-vindo de volta. Sua equipe continua a mesma até o encerramento.'
          : 'Guarda essa frequência. É nela que você joga até o encerramento.') +
      '</p>' +
      dividerHtml(t.color) +
      '<p class="verse">"As minhas ovelhas ouvem a minha voz,<br>e eu as conheço, e elas me seguem."</p>' +
      '<p class="verse-ref">João 10:27</p>' +
      '<button class="again-btn" id="backBtn">Inscrever outra pessoa</button>';

    document.getElementById('backBtn').addEventListener('click', function(){ renderForm(); });
  }

  // ---------- ADMIN VIEW ----------
  async function renderAdmin(){
    card.innerHTML =
      dividerHtml() +
      '<p class="eyebrow">Painel do organizador</p>' +
      '<h2 class="admin-title">Congresso<br>de Jovens</h2>' +
      '<p class="admin-sub">Imprima o QR code abaixo para o check-in.</p>' +
      '<div class="qr-box" id="qrBox" style="margin-top:20px;"></div>' +
      '<div class="total-hero"><div class="total-num" id="totalNum">0</div><div class="total-label">Inscritos no congresso</div></div>' +
      dividerHtml() +
      '<p class="eyebrow" style="margin-bottom:14px;">Equipes da gincana</p>' +
      '<div class="bars" id="bars"></div>' +
      '<div class="list-toggle-row">' +
        '<button id="listToggleBtn">Ver inscritos</button>' +
        '<button id="csvBtn">Baixar CSV</button>' +
      '</div>' +
      '<div id="peopleListWrap"></div>' +
      '<div class="admin-actions">' +
        '<button id="refreshBtn">Atualizar</button>' +
        '<button class="danger" id="resetBtn">Resetar tudo</button>' +
      '</div>' +
      '<p class="hint">Contagens podem variar em 1 no caso raro de dois escaneamentos simultâneos.</p>' +
      '<p class="hint" style="margin-top:10px;"><a href="#" id="backToFormLink" style="color:inherit; text-decoration:underline;">voltar ao cadastro</a></p>';

    var qrUrl = window.location.origin + window.location.pathname;
    new QRCode(document.getElementById('qrBox'), {
      text: qrUrl, width: 176, height: 176,
      colorDark: '#2B2A28', colorLight: '#ffffff',
      correctLevel: QRCode.CorrectLevel.M
    });

    await refreshCounts();
    document.getElementById('refreshBtn').addEventListener('click', function(){
      refreshCounts();
      if (listVisible) loadAndRenderPeople();
    });
    document.getElementById('resetBtn').addEventListener('click', confirmReset);
    document.getElementById('listToggleBtn').addEventListener('click', toggleList);
    document.getElementById('csvBtn').addEventListener('click', downloadCsv);
    document.getElementById('backToFormLink').addEventListener('click', function(e){
      e.preventDefault();
      renderForm();
    });
  }

  var listVisible = false;

  async function loadPeople(){
    var indexRaw = await getShared('gincana-index');
    var index = [];
    try{ index = indexRaw ? JSON.parse(indexRaw) : []; }catch(e){ index = []; }
    var people = [];
    for (var i = 0; i < index.length; i++){
      var raw = await getShared(index[i]);
      if (raw){
        try{ people.push(JSON.parse(raw)); }catch(e){}
      }
    }
    people.sort(function(a,b){ return (a.ts||0) - (b.ts||0); });
    return people;
  }

  function formatWhats(digits){
    if (!digits) return '';
    if (digits.length === 11) return '(' + digits.slice(0,2) + ') ' + digits.slice(2,7) + '-' + digits.slice(7);
    if (digits.length === 10) return '(' + digits.slice(0,2) + ') ' + digits.slice(2,6) + '-' + digits.slice(6);
    return digits;
  }

  async function toggleList(){
    var btn = document.getElementById('listToggleBtn');
    var wrap = document.getElementById('peopleListWrap');
    if (listVisible){
      listVisible = false;
      btn.textContent = 'Ver inscritos';
      wrap.innerHTML = '';
      return;
    }
    listVisible = true;
    btn.textContent = 'Ocultar inscritos';
    await loadAndRenderPeople();
  }

  async function loadAndRenderPeople(){
    var wrap = document.getElementById('peopleListWrap');
    wrap.innerHTML = '<div class="people-list"><div class="list-loading">Carregando...</div></div>';
    var people = await loadPeople();
    if (people.length === 0){
      wrap.innerHTML = '<div class="people-list"><div class="list-empty">Ninguém inscrito ainda.</div></div>';
      return;
    }
    var rows = people.map(function(p){
      var t = TEAMS[p.team] || { label: p.team, color: '#6B675E' };
      return '<div class="person-row">' +
        '<div class="person-main">' +
          '<div class="person-name">' + escapeHtml(p.name || '') + '</div>' +
          '<div class="person-whats">' + formatWhats(p.whatsapp) + '</div>' +
        '</div>' +
        '<div class="person-team" style="background:' + hexToRgba(t.color, 0.15) + '; color:' + t.color + ';">' + t.label + '</div>' +
      '</div>';
    }).join('');
    wrap.innerHTML = '<div class="people-list">' + rows + '</div>';
  }

  function escapeHtml(str){
    var d = document.createElement('div');
    d.textContent = str;
    return d.innerHTML;
  }

  async function downloadCsv(){
    var btn = document.getElementById('csvBtn');
    var originalText = btn.textContent;
    btn.textContent = 'Gerando...';
    var people = await loadPeople();
    var lines = ['Nome;WhatsApp;Equipe'];
    people.forEach(function(p){
      var t = TEAMS[p.team] || { label: p.team };
      var name = (p.name || '').replace(/;/g, ',');
      lines.push(name + ';' + (p.whatsapp || '') + ';' + t.label);
    });
    var csv = '\uFEFF' + lines.join('\r\n');
    var blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
    var url = URL.createObjectURL(blob);
    var a = document.createElement('a');
    a.href = url;
    a.download = 'inscritos-congresso.csv';
    document.body.appendChild(a);
    a.click();
    document.body.removeChild(a);
    URL.revokeObjectURL(url);
    btn.textContent = originalText;
  }

  async function refreshCounts(){
    var counts = await getCounts();
    var total = TEAM_KEYS.reduce(function(sum,k){ return sum + (counts[k]||0); }, 0);
    var maxVal = Math.max(1, Math.max.apply(null, TEAM_KEYS.map(function(k){ return counts[k]||0; })));

    document.getElementById('totalNum').textContent = total;

    var barsHtml = TEAM_KEYS.map(function(k){
      var t = TEAMS[k];
      var val = counts[k] || 0;
      var pct = Math.round((val / maxVal) * 100);
      return '<div class="bar-row">' +
        '<div class="bar-label"><span>' + t.label + ' · ' + t.freq + '</span><span>' + val + '</span></div>' +
        '<div class="bar-track"><div class="bar-fill" style="width:' + pct + '%; background:' + t.color + ';"></div></div>' +
      '</div>';
    }).join('');
    document.getElementById('bars').innerHTML = barsHtml;
  }

  var resetArmed = false;
  function confirmReset(){
    var btn = document.getElementById('resetBtn');
    if (!resetArmed){
      resetArmed = true;
      btn.textContent = 'Confirmar reset';
      setTimeout(function(){ resetArmed = false; btn.textContent = 'Resetar tudo'; }, 4000);
      return;
    }
    resetArmed = false;
    doReset();
  }

  async function doReset(){
    var btn = document.getElementById('resetBtn');
    btn.textContent = 'Resetando...';
    try{
      var indexRaw = await getShared('gincana-index');
      var index = indexRaw ? JSON.parse(indexRaw) : [];
      for (var i = 0; i < index.length; i++){ await deleteShared(index[i]); }
      await deleteShared('gincana-index');
      var init = {}; TEAM_KEYS.forEach(function(k){ init[k]=0; });
      await setShared('gincana-counts', JSON.stringify(init));
    }catch(e){}
    btn.textContent = 'Resetar tudo';
    refreshCounts();
  }

  // ---------- boot ----------
  if (isAdmin){ renderAdmin(); } else { renderForm(); }
})();
</script>
</body>
</html>
