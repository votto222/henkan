<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>謎文字機関</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;1,300;1,400&family=Shippori+Mincho:wght@400;500;600;700;800&family=Cinzel:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root {
  --ink: #d4c5a0;
  --ink-bright: #f0e4c5;
  --ink-mute: #8a7a5c;
  --paper: #1a1612;
  --paper-2: #0c0a08;
  --gold: #c8a951;
  --gold-bright: #e8c870;
  --gold-dim: #5a4a22;
}

* { box-sizing: border-box; margin: 0; padding: 0; }

html, body { 
  background: var(--paper-2); 
  min-height: 100vh; 
}

body {
  background-image: 
    radial-gradient(ellipse 80% 50% at 50% 0%, rgba(200,169,81,0.08) 0%, transparent 60%),
    radial-gradient(ellipse 60% 40% at 50% 100%, rgba(140,90,40,0.04) 0%, transparent 70%);
  color: var(--ink);
  font-family: 'Shippori Mincho', 'Cormorant Garamond', serif;
  padding: 1.25rem 1rem 4rem;
  position: relative;
  overflow-x: hidden;
}

body::before {
  content: '';
  position: fixed;
  inset: 0;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='180' height='180'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.92' numOctaves='3' stitchTiles='stitch'/%3E%3CfeColorMatrix values='0 0 0 0 0.78 0 0 0 0 0.66 0 0 0 0 0.32 0 0 0 0.5 0'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.4'/%3E%3C/svg%3E");
  opacity: 0.18;
  pointer-events: none;
  mix-blend-mode: overlay;
  z-index: 0;
}

.container {
  max-width: 580px;
  margin: 0 auto;
  position: relative;
  z-index: 1;
}

header {
  text-align: center;
  padding: 1.8rem 0 1.5rem;
}

.ornament {
  font-family: 'Cinzel', serif;
  color: var(--gold);
  font-size: 0.9rem;
  letter-spacing: 0.6em;
  margin-bottom: 1rem;
  opacity: 0.6;
  padding-left: 0.6em;
}

h1 {
  font-family: 'Shippori Mincho', serif;
  font-weight: 800;
  font-size: clamp(2.2rem, 9vw, 3rem);
  color: var(--ink-bright);
  letter-spacing: 0.18em;
  margin-bottom: 0.6rem;
  text-shadow: 0 0 24px rgba(200,169,81,0.18);
  padding-left: 0.18em;
}

.subtitle {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-weight: 300;
  font-size: 0.78rem;
  color: var(--gold);
  letter-spacing: 0.42em;
  text-transform: uppercase;
  opacity: 0.7;
  padding-left: 0.42em;
}

.divider {
  height: 1px;
  background: linear-gradient(90deg, transparent, var(--gold-dim) 30%, var(--gold) 50%, var(--gold-dim) 70%, transparent);
  margin: 1.4rem auto;
  max-width: 280px;
  position: relative;
}

.divider::after {
  content: '✦';
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: var(--paper-2);
  padding: 0 0.6rem;
  color: var(--gold);
  font-size: 0.7rem;
}

.mode-toggle {
  display: flex;
  border: 1px solid var(--gold-dim);
  margin-bottom: 1.5rem;
  background: rgba(0,0,0,0.35);
  position: relative;
}

.mode-btn {
  flex: 1;
  padding: 0.95rem 0.5rem;
  background: transparent;
  border: none;
  color: var(--ink-mute);
  font-family: 'Shippori Mincho', serif;
  font-size: 0.95rem;
  font-weight: 600;
  letter-spacing: 0.4em;
  cursor: pointer;
  transition: color 0.3s, background 0.3s;
  padding-left: 0.9em;
}

.mode-btn.active {
  background: linear-gradient(180deg, rgba(200,169,81,0.18), rgba(200,169,81,0.06));
  color: var(--ink-bright);
  box-shadow: inset 0 0 18px rgba(200,169,81,0.08);
}

.io-section {
  margin-bottom: 1.1rem;
}

.io-label {
  font-family: 'Cinzel', serif;
  font-size: 0.65rem;
  letter-spacing: 0.5em;
  color: var(--gold);
  text-transform: uppercase;
  margin-bottom: 0.5rem;
  display: flex;
  align-items: center;
  gap: 0.7rem;
  padding-left: 0.5em;
}

.io-label::before, .io-label::after {
  content: '';
  flex: 1;
  height: 1px;
  background: linear-gradient(90deg, transparent, var(--gold-dim));
}
.io-label::after {
  background: linear-gradient(90deg, var(--gold-dim), transparent);
}

textarea, .output-box {
  width: 100%;
  min-height: 130px;
  padding: 1rem 1.1rem;
  background: rgba(0,0,0,0.45);
  border: 1px solid var(--gold-dim);
  color: var(--ink-bright);
  font-family: 'Shippori Mincho', serif;
  font-size: 1.05rem;
  line-height: 1.75;
  resize: vertical;
  outline: none;
  transition: border-color 0.4s, box-shadow 0.4s;
  border-radius: 1px;
}

textarea:focus {
  border-color: var(--gold);
  box-shadow: 0 0 0 1px rgba(200,169,81,0.3), inset 0 0 24px rgba(200,169,81,0.04);
}

textarea::placeholder {
  color: var(--ink-mute);
  font-style: italic;
  opacity: 0.6;
}

.output-box {
  word-break: break-all;
  white-space: pre-wrap;
  font-size: 1.18rem;
  letter-spacing: 0.06em;
  min-height: 130px;
  position: relative;
}

.output-box:empty::before {
  content: '— ⋄ —';
  color: var(--gold-dim);
  font-style: italic;
  letter-spacing: 0.3em;
}

.convert-btn {
  width: 100%;
  padding: 1.1rem;
  background: linear-gradient(180deg, rgba(200,169,81,0.18), rgba(200,169,81,0.04));
  border: 1px solid var(--gold);
  color: var(--ink-bright);
  font-family: 'Shippori Mincho', serif;
  font-size: 1.1rem;
  font-weight: 700;
  letter-spacing: 0.6em;
  cursor: pointer;
  transition: all 0.4s;
  margin: 1.4rem 0;
  position: relative;
  overflow: hidden;
  padding-left: 0.6em;
}

.convert-btn::before {
  content: '';
  position: absolute;
  top: 0;
  left: -120%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255,220,140,0.22), transparent);
  transition: left 0.7s;
}

.convert-btn:hover::before { left: 120%; }
.convert-btn:hover {
  background: linear-gradient(180deg, rgba(200,169,81,0.28), rgba(200,169,81,0.1));
  box-shadow: 0 0 22px rgba(200,169,81,0.22);
}

.convert-btn:active {
  transform: translateY(1px);
}

.copy-btn {
  margin-top: 0.6rem;
  padding: 0.55rem 1.1rem;
  background: transparent;
  border: 1px solid var(--gold-dim);
  color: var(--gold);
  font-family: 'Cinzel', serif;
  font-size: 0.65rem;
  letter-spacing: 0.4em;
  cursor: pointer;
  transition: all 0.25s;
  padding-left: 0.4em;
}

.copy-btn:hover {
  background: rgba(200,169,81,0.08);
  border-color: var(--gold);
  color: var(--ink-bright);
}

.copy-btn.copied {
  background: rgba(200,169,81,0.22);
  color: var(--ink-bright);
  border-color: var(--gold);
}

.settings {
  margin-top: 1.5rem;
  border-top: 1px solid var(--gold-dim);
  padding-top: 1.2rem;
}

.settings summary {
  font-family: 'Cinzel', serif;
  font-size: 0.65rem;
  letter-spacing: 0.5em;
  color: var(--gold);
  text-transform: uppercase;
  cursor: pointer;
  padding: 0.4rem 0;
  list-style: none;
  display: flex;
  align-items: center;
  gap: 0.7rem;
  padding-left: 0.5em;
}

.settings summary::-webkit-details-marker { display: none; }

.settings summary::before {
  content: '✦';
  font-size: 0.55rem;
  transition: transform 0.3s;
  color: var(--gold);
}

.settings[open] summary::before {
  transform: rotate(180deg);
}

.setting-row {
  padding: 0.85rem 0.2rem;
  border-bottom: 1px solid rgba(90, 74, 34, 0.25);
}

.setting-row:last-child { border-bottom: none; }

.setting-row label.range-label {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 0.85rem;
  color: var(--ink);
  margin-bottom: 0.5rem;
  font-family: 'Shippori Mincho', serif;
}

.range-label span {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  color: var(--gold-bright);
  font-size: 0.95rem;
}

input[type="range"] {
  -webkit-appearance: none;
  appearance: none;
  width: 100%;
  height: 2px;
  background: var(--gold-dim);
  outline: none;
}

input[type="range"]::-webkit-slider-thumb {
  -webkit-appearance: none;
  appearance: none;
  width: 14px;
  height: 14px;
  background: var(--gold);
  border-radius: 50%;
  cursor: pointer;
  box-shadow: 0 0 12px rgba(200,169,81,0.5);
}

input[type="range"]::-moz-range-thumb {
  width: 14px;
  height: 14px;
  background: var(--gold);
  border-radius: 50%;
  cursor: pointer;
  border: none;
  box-shadow: 0 0 12px rgba(200,169,81,0.5);
}

.checkbox-label {
  display: flex;
  align-items: center;
  gap: 0.7rem;
  font-size: 0.88rem;
  cursor: pointer;
  font-family: 'Shippori Mincho', serif;
  color: var(--ink);
}

.checkbox-label input[type="checkbox"] {
  appearance: none;
  -webkit-appearance: none;
  width: 16px;
  height: 16px;
  border: 1px solid var(--gold-dim);
  background: rgba(0,0,0,0.4);
  cursor: pointer;
  position: relative;
  transition: all 0.2s;
  flex-shrink: 0;
}

.checkbox-label input[type="checkbox"]:checked {
  border-color: var(--gold);
  background: rgba(200,169,81,0.15);
}

.checkbox-label input[type="checkbox"]:checked::after {
  content: '✦';
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: var(--gold);
  font-size: 9px;
}

.note {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-size: 0.78rem;
  color: var(--gold-dim);
  text-align: center;
  margin-top: 2.2rem;
  letter-spacing: 0.04em;
  line-height: 1.7;
}

.char {
  display: inline-block;
  animation: appear 0.5s both;
}

@keyframes appear {
  from { opacity: 0; transform: translateY(3px); filter: blur(4px); }
  to { opacity: 1; transform: none; filter: none; }
}

.warning {
  font-family: 'Shippori Mincho', serif;
  font-size: 0.78rem;
  color: #c89060;
  text-align: center;
  padding: 0.5rem 0.8rem;
  margin-bottom: 0.8rem;
  border: 1px solid rgba(200, 144, 96, 0.3);
  background: rgba(200, 144, 96, 0.05);
  display: none;
}

.warning.show { display: block; }
</style>
</head>
<body>
<div class="container">
  <header>
    <div class="ornament">✦ ✦ ✦</div>
    <h1>謎文字機関</h1>
    <p class="subtitle">apocrypha</p>
    <div class="divider"></div>
  </header>

  <div class="mode-toggle">
    <button class="mode-btn active" data-mode="encode">封　印</button>
    <button class="mode-btn" data-mode="decode">解　読</button>
  </div>

  <div class="io-section">
    <div class="io-label" id="inLabel">原 文</div>
    <textarea id="input" placeholder="ここに ひらがなで かいてください..."></textarea>
    <div class="warning" id="warning"></div>
  </div>

  <button class="convert-btn" id="convert">変　換</button>

  <div class="io-section">
    <div class="io-label" id="outLabel">封 印 文</div>
    <div class="output-box" id="output"></div>
    <button class="copy-btn" id="copy">複　写</button>
  </div>

  <details class="settings">
    <summary>儀 式 の 設 定</summary>
    <div class="setting-row">
      <label class="range-label">ノイズ密度<span id="noiseVal">25%</span></label>
      <input type="range" id="noise" min="0" max="60" value="25">
    </div>
    <div class="setting-row">
      <label class="checkbox-label">
        <input type="checkbox" id="preserveSpace" checked>
        空白と改行を保つ
      </label>
    </div>
    <div class="setting-row">
      <label class="checkbox-label">
        <input type="checkbox" id="autoConvert">
        入力に応じて自動変換
      </label>
    </div>
  </details>

  <p class="note">— カタカナは ひらがなに 変換され、漢字は そのまま 残ります —</p>
</div>

<script>
// ====== ひらがな順序（変換マップの基準）======
const KANA = "あいうえおかきくけこがぎぐげごさしすせそざじずぜぞたちつてとだぢづでどなにぬねのはひふへほばびぶべぼぱぴぷぺぽまみむめもやゆよらりるれろわをんゃゅょっぁぃぅぇぉー";

// ====== 記号プールの構築 ======
function rangeChars(start, end) {
  const result = [];
  for (let i = start; i <= end; i++) {
    const c = String.fromCodePoint(i);
    // 結合文字（マーク）と空白系を除外
    if (!/\p{M}/u.test(c) && c.trim() !== '') {
      result.push(c);
    }
  }
  return result;
}

// 複数のスクリプトから記号を集める（順序は固定なので毎回同じマップになる）
const allSymbols = [
  ...rangeChars(0x0460, 0x04FF),  // キリル文字補助
  ...rangeChars(0x2C00, 0x2C5E),  // グラゴル文字
  ...rangeChars(0x2C80, 0x2CEE),  // コプト文字
  ...rangeChars(0x0531, 0x0556),  // アルメニア大文字
  ...rangeChars(0x0561, 0x0587),  // アルメニア小文字
  ...rangeChars(0x10A0, 0x10C5),  // ジョージア・アソムタヴルリ
  ...rangeChars(0x10D0, 0x10FA),  // ジョージア・ムヘドルリ
  ...rangeChars(0x16A0, 0x16EA),  // ルーン文字
  ...rangeChars(0x0905, 0x0939),  // デーヴァナーガリー（独立子音・母音）
  ...rangeChars(0x0E01, 0x0E2E),  // タイ文字（子音）
  ...rangeChars(0x03DA, 0x03FF),  // ギリシャ拡張
  ...rangeChars(0x0250, 0x02AF),  // IPA拡張
];

// 各ひらがなに6つの記号を割り当て（ストライド方式で多様性を確保）
const SYMBOLS_PER_KANA = 6;
const cipherMap = {};
const reverseMap = {};

for (let i = 0; i < KANA.length; i++) {
  const kana = KANA[i];
  const symbols = [];
  for (let j = 0; j < SYMBOLS_PER_KANA; j++) {
    const idx = j * KANA.length + i;
    if (idx < allSymbols.length) {
      const sym = allSymbols[idx];
      symbols.push(sym);
      reverseMap[sym] = kana;
    }
  }
  cipherMap[kana] = symbols;
}

// ====== ノイズ用記号プール（暗号本体と重複しない別ブロック）======
const NOISE_POOL = [
  '※','⁂','◊','◇','◈','⋄','◎','⊛','⊕','⊗','⊘','⊙','⊚','⊜',
  '☉','☽','☿','♀','♁','♂','♃','♄','♅','♆',
  '☆','★','✦','✧','✱','✲','✳','✴','✶','✷','✸','✹','✺','✻','✼','✽','✾',
  '❖','❉','❊','❋','❅','❆','❀','❁',
  '⌘','⌬','⌽','⌾','⏁','⏂',
  '⚘','⚛','⚚','⚙','⚜','⚹','⚸','⚷',
  '∂','∇','∑','∏','∮','∰','∃','∀','∈','∋','∝','∞','∰','∱','∲','∳',
  '⊞','⊟','⊠','⊡','⊢','⊣','⊤','⊥',
  '⌗','⌜','⌝','⌞','⌟','⌐','⌒','⌓','⌖',
  '◐','◑','◒','◓','◔','◕','◖','◗','◘','◙',
];
const noiseSet = new Set(NOISE_POOL);

// ====== カタカナ → ひらがな ======
function katakanaToHiragana(text) {
  return text.replace(/[\u30a1-\u30f6]/g, c =>
    String.fromCharCode(c.charCodeAt(0) - 0x60)
  );
}

// ====== 暗号化 ======
function encode(text, noiseLevel, preserveSpace) {
  const normalized = katakanaToHiragana(text);
  const result = [];
  for (const c of normalized) {
    if (cipherMap[c]) {
      const options = cipherMap[c];
      result.push(options[Math.floor(Math.random() * options.length)]);
      // ノイズを確率的に挿入
      if (Math.random() < noiseLevel / 100) {
        result.push(NOISE_POOL[Math.floor(Math.random() * NOISE_POOL.length)]);
      }
    } else if (c === ' ' || c === '\n' || c === '\t' || c === '　') {
      if (preserveSpace) result.push(c);
    } else {
      // 漢字や記号などはそのまま通す
      result.push(c);
    }
  }
  return result.join('');
}

// ====== 復号 ======
function decode(text) {
  const result = [];
  for (const c of text) {
    if (reverseMap[c]) {
      result.push(reverseMap[c]);
    } else if (noiseSet.has(c)) {
      // ノイズは削除
      continue;
    } else {
      // それ以外（空白・漢字など）はそのまま
      result.push(c);
    }
  }
  return result.join('');
}

// ====== UI ======
const inputEl = document.getElementById('input');
const outputEl = document.getElementById('output');
const convertBtn = document.getElementById('convert');
const copyBtn = document.getElementById('copy');
const noiseInput = document.getElementById('noise');
const noiseValEl = document.getElementById('noiseVal');
const preserveSpaceEl = document.getElementById('preserveSpace');
const autoConvertEl = document.getElementById('autoConvert');
const inLabelEl = document.getElementById('inLabel');
const outLabelEl = document.getElementById('outLabel');
const warningEl = document.getElementById('warning');
const modeBtns = document.querySelectorAll('.mode-btn');

let currentMode = 'encode';

function updateLabels() {
  if (currentMode === 'encode') {
    inLabelEl.textContent = '原 文';
    outLabelEl.textContent = '封 印 文';
    inputEl.placeholder = 'ここに ひらがなで かいてください...';
  } else {
    inLabelEl.textContent = '封 印 文';
    outLabelEl.textContent = '原 文';
    inputEl.placeholder = '謎の文字を ここに はりつけてください...';
  }
}

modeBtns.forEach(btn => {
  btn.addEventListener('click', () => {
    modeBtns.forEach(b => b.classList.remove('active'));
    btn.classList.add('active');
    currentMode = btn.dataset.mode;
    updateLabels();
    outputEl.innerHTML = '';
    warningEl.classList.remove('show');
    if (autoConvertEl.checked && inputEl.value) doConvert();
  });
});

function checkKanji(text) {
  // 漢字検出（封印モードのみ警告）
  if (currentMode === 'encode' && /[\u4e00-\u9fff]/.test(text)) {
    warningEl.textContent = '⚠ 漢字が含まれています。漢字は変換されず、そのまま残ります。';
    warningEl.classList.add('show');
  } else {
    warningEl.classList.remove('show');
  }
}

function renderOutput(text) {
  outputEl.innerHTML = '';
  const chars = [...text];
  // 長すぎるとアニメーション重いので制限
  if (chars.length > 200) {
    outputEl.textContent = text;
    return;
  }
  chars.forEach((c, i) => {
    const span = document.createElement('span');
    span.className = 'char';
    span.textContent = c;
    span.style.animationDelay = (i * 0.012) + 's';
    outputEl.appendChild(span);
  });
}

function doConvert() {
  const text = inputEl.value;
  if (!text) {
    outputEl.innerHTML = '';
    warningEl.classList.remove('show');
    return;
  }
  checkKanji(text);
  const noiseLevel = parseInt(noiseInput.value);
  const preserveSpace = preserveSpaceEl.checked;
  let result;
  if (currentMode === 'encode') {
    result = encode(text, noiseLevel, preserveSpace);
  } else {
    result = decode(text);
  }
  renderOutput(result);
}

convertBtn.addEventListener('click', doConvert);

inputEl.addEventListener('input', () => {
  checkKanji(inputEl.value);
  if (autoConvertEl.checked) doConvert();
});

noiseInput.addEventListener('input', () => {
  noiseValEl.textContent = noiseInput.value + '%';
  if (autoConvertEl.checked && inputEl.value && currentMode === 'encode') doConvert();
});

preserveSpaceEl.addEventListener('change', () => {
  if (autoConvertEl.checked && inputEl.value) doConvert();
});

copyBtn.addEventListener('click', async () => {
  const text = outputEl.textContent;
  if (!text || text === '— ⋄ —') return;
  try {
    await navigator.clipboard.writeText(text);
    copyBtn.classList.add('copied');
    copyBtn.textContent = '完　了';
    setTimeout(() => {
      copyBtn.classList.remove('copied');
      copyBtn.textContent = '複　写';
    }, 1400);
  } catch (e) {
    // フォールバック
    const ta = document.createElement('textarea');
    ta.value = text;
    document.body.appendChild(ta);
    ta.select();
    document.execCommand('copy');
    document.body.removeChild(ta);
    copyBtn.classList.add('copied');
    copyBtn.textContent = '完　了';
    setTimeout(() => {
      copyBtn.classList.remove('copied');
      copyBtn.textContent = '複　写';
    }, 1400);
  }
});

// 初期化
updateLabels();
</script>
</body>
</html>
