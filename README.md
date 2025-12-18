<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Turkish Months – Practice Slides (Listening + Speaking)</title>
  <style>
    *{box-sizing:border-box;font-family:"Trebuchet MS",system-ui,sans-serif}
    html{scroll-behavior:smooth}
    body{
      margin:0;
      background:linear-gradient(135deg,#fff3e0,#e3f2fd);
      color:#263238;
    }
    header{padding:18px 12px 8px;text-align:center}
    h1{margin:0;font-size:2.25rem;color:#00695c;text-shadow:1px 1px 0 #fff}
    .subtitle{margin:8px 0 0;color:#455a64}

    .container{max-width:1000px;margin:0 auto 42px;padding:0 14px 30px}

    .nav{
      display:flex;flex-wrap:wrap;gap:10px;justify-content:center;align-items:center;
      margin:12px 0 14px;
    }
    .chip{
      background:#ffffffcc;border:1px solid #cfd8dc;border-radius:999px;
      padding:6px 10px;font-weight:800;color:#37474f
    }
    .btn{
      border:none;border-radius:18px;
      padding:10px 14px;font-size:0.98rem;font-weight:800;
      cursor:pointer;transition:transform .1s,box-shadow .1s,background .2s;
      margin:2px;
    }
    .btn:active{transform:translateY(1px)}
    .btn-primary{background:#42a5f5;color:#fff}
    .btn-primary:hover{background:#1e88e5;box-shadow:0 2px 6px rgba(0,0,0,.2)}
    .btn-secondary{background:#ab47bc;color:#fff}
    .btn-secondary:hover{background:#8e24aa;box-shadow:0 2px 6px rgba(0,0,0,.2)}
    .btn-warn{background:#ffca28;color:#263238}
    .btn-warn:hover{background:#ffc107;box-shadow:0 2px 6px rgba(0,0,0,.2)}
    .btn-ghost{background:#fff;border:2px solid #90a4ae;color:#37474f}
    .btn-ghost:hover{background:#eceff1}
    .btn-disabled{opacity:.45;cursor:default;box-shadow:none}

    .slide{
      display:none;
      padding:18px;
      border-radius:18px;
      background:rgba(255,255,255,0.96);
      box-shadow:0 6px 18px rgba(0,0,0,.14);
      min-height:380px;
    }
    .slide.active{display:block}
    .slide h2{margin:0 0 8px;color:#1565c0}
    .desc{margin:0 0 12px;color:#455a64}

    .grid{
      display:grid;
      grid-template-columns:repeat(2,1fr);
      gap:12px;
    }
    @media (max-width:780px){.grid{grid-template-columns:1fr}}

    .card{
      border-radius:16px;
      padding:12px 14px;
      background:#fff8e1;
      border:2px solid #ffd54f;
    }
    .card h3{margin:0 0 6px;color:#e65100}
    .row{display:flex;gap:10px;flex-wrap:wrap;align-items:center}
    .tag{
      display:inline-block;
      padding:4px 10px;border-radius:999px;
      font-size:.85rem;font-weight:800;
      background:#e3f2fd;color:#0d47a1;border:1px solid #bbdefb;
    }
    .mono{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace}

    .center{text-align:center}
    .question{
      font-size:1.25rem;
      text-align:center;
      margin:10px 0 10px;
      font-weight:900;
    }
    .options{
      display:flex;flex-wrap:wrap;gap:10px;justify-content:center;
      margin-top:10px;
    }
    .opt{
      background:#ffe082;color:#263238;
      border:0;border-radius:18px;padding:10px 14px;
      cursor:pointer;font-weight:900;
      transition:transform .1s, box-shadow .1s, background .2s;
    }
    .opt:hover{background:#ffd54f;transform:translateY(-1px);box-shadow:0 2px 6px rgba(0,0,0,.18)}
    .feedback{
      margin-top:10px;
      min-height:22px;
      text-align:center;
      font-weight:900;
    }
    .good{color:#2e7d32}
    .bad{color:#c62828}

    .box{
      margin-top:12px;
      padding:12px 14px;
      border-radius:16px;
      background:#e8f5e9;
      border:2px solid #a5d6a7;
      text-align:center;
    }
    .bigTR{font-size:1.6rem;font-weight:950;color:#1b5e20}
    .hint{color:#546e7a;font-size:.9rem;margin-top:6px}
    .small{font-size:.86rem;color:#607d8b}

    input[type="text"]{
      padding:10px 12px;border-radius:12px;border:2px solid #90caf9;
      font-size:1rem;min-width:240px;
    }
    input[type="text"]:focus{outline:none;border-color:#1e88e5;box-shadow:0 0 0 3px rgba(30,136,229,.15)}
    .hr{height:1px;background:#eceff1;margin:12px 0}

    .sentence{
      margin:10px 0;
      padding:10px 12px;
      border-radius:14px;
      background:#f1f8e9;
      border:2px solid #c5e1a5;
    }
    .sentence strong{color:#2e7d32}
    .markOk{border-color:#2e7d32;background:#e8f5e9}
    .markNo{border-color:#c62828;background:#ffebee}
  </style>
</head>
<body>
<header>
  <h1>Turkish Months – Practice Slides</h1>
  <p class="subtitle">Learn • Listen • Speak • Use months in Turkish (aylar) 🇹🇷</p>
</header>

<div class="container">
  <div class="nav">
    <button id="prev" class="btn btn-secondary">⬅ Previous</button>
    <span id="indicator" class="chip">Slide 1 / 5</span>
    <button id="next" class="btn btn-primary">Next ➡</button>

    <button class="btn btn-ghost" id="go1">Slide 1</button>
    <button class="btn btn-ghost" id="go2">Slide 2</button>
    <button class="btn btn-ghost" id="go3">Slide 3</button>
    <button class="btn btn-ghost" id="go4">Slide 4</button>
    <button class="btn btn-ghost" id="go5">Slide 5</button>
  </div>

  <!-- SLIDE 1 -->
  <section class="slide active" data-slide="0">
    <h2>Slide 1 – Learn the Months (English → Turkish) + Pronunciation</h2>
    <p class="desc">
      Read the pairs. Use <strong>Listen</strong> to hear Turkish pronunciation (best Turkish voice available on your device).
      Tips use Turkish letters: <strong>ş</strong> = “sh”, <strong>ç</strong> = “ch”, <strong>ı</strong> is a special vowel (not “i”).
    </p>

    <div class="row" style="justify-content:center;margin:8px 0 12px">
      <span class="tag">Voice</span>
      <select id="voiceSelect" style="padding:8px 10px;border-radius:12px;border:2px solid #ce93d8;min-width:300px;background:#fff;">
        <option value="">(auto) Best Turkish voice</option>
      </select>
      <button id="testVoice" class="btn btn-warn">Test voice 🔊</button>
    </div>

    <div class="grid" id="learnGrid"></div>

    <div class="box">
      <div class="small"><strong>Extra pronunciation notes</strong></div>
      <div class="hint">
        • <strong>Ağustos</strong>: the <strong>ğ</strong> is usually “soft” (it lengthens the vowel): roughly “aa-OO-stos”.<br>
        • <strong>Eylül</strong>: has <strong>ü</strong> (rounded sound).<br>
        • <strong>Kasım</strong>: has <strong>ı</strong> (dotless i).<br>
      </div>
    </div>
  </section>

  <!-- SLIDE 2 -->
  <section class="slide" data-slide="1">
    <h2>Slide 2 – Listening Flashcards</h2>
    <p class="desc">
      Press <strong>Listen</strong> and choose the correct Turkish month. (No English on the answer buttons!)
    </p>

    <div class="center">
      <button id="listenPlay" class="btn btn-warn">🔊 Listen</button>
      <button id="listenNew" class="btn btn-ghost">New card 🔁</button>
    </div>

    <div class="question" id="listenPrompt">Listen and choose the correct month</div>
    <div class="options" id="listenOptions"></div>
    <div class="feedback" id="listenFeedback"></div>

    <div class="box" id="listenReveal" style="display:none;">
      <div class="small">Correct answer was:</div>
      <div class="bigTR" id="listenCorrectTR">Ocak</div>
      <div class="small" id="listenCorrectEN">January</div>
      <div class="small">Tip: Say it out loud 3 times.</div>
    </div>
  </section>

  <!-- SLIDE 3 -->
  <section class="slide" data-slide="2">
    <h2>Slide 3 – English → Turkish (Hard Multiple Choice)</h2>
    <p class="desc">
      Choose the correct Turkish translation. Some options are “similar-looking” to increase challenge.
      You can press <strong>Listen Turkish</strong> to confirm pronunciation.
    </p>

    <div class="center">
      <button id="mcListen" class="btn btn-warn">🔊 Listen Turkish</button>
      <button id="mcNew" class="btn btn-ghost">New question 🔁</button>
    </div>

    <div class="question" id="mcQ">January → ?</div>
    <div class="options" id="mcOptions"></div>
    <div class="feedback" id="mcFeedback"></div>

    <div class="box" id="mcPron" style="display:none;">
      <div class="small">Pronunciation hint (Turkish-style):</div>
      <div class="bigTR" id="mcTR">Ocak</div>
      <div class="hint" id="mcTip">o-JAK</div>
    </div>
  </section>

  <!-- SLIDE 4 -->
  <section class="slide" data-slide="3">
    <h2>Slide 4 – Fill in the Blanks (Use Months in Sentences)</h2>
    <p class="desc">
      Type the missing <strong>Turkish month</strong>. Capital letter is optional here.
      Tip: Turkish months are usually written with a capital letter too.
    </p>

    <div id="fillList"></div>

    <div class="center" style="margin-top:10px">
      <button id="fillCheck" class="btn btn-primary">Check ✅</button>
      <button id="fillClear" class="btn btn-ghost">Clear ✨</button>
    </div>
    <div class="feedback" id="fillFeedback"></div>
  </section>

  <!-- SLIDE 5 -->
  <section class="slide" data-slide="4">
    <h2>Slide 5 – Speaking Challenge (Say the Month)</h2>
    <p class="desc">
      Press the mic and <strong>say the Turkish month</strong> to complete the sentence.
      If speech recognition isn’t supported, type the month instead.
    </p>

    <div class="question" id="speakSentence">My birthday is in March. In Turkish, it is ____.</div>

    <div class="center">
      <button id="speakListenCorrect" class="btn btn-warn">🔊 Listen correct answer</button>
    </div>

    <div class="center" style="margin-top:10px">
      <button id="micBtn" class="btn btn-primary">🎙 Start speaking</button>
      <button id="micStop" class="btn btn-secondary">⏹ Stop</button>
    </div>

    <div class="center" style="margin-top:10px">
      <input id="speechText" type="text" placeholder="Recognized text (or type your answer)..." />
      <button id="speakCheck" class="btn btn-warn">Check ✅</button>
      <button id="speakNew" class="btn btn-ghost">New sentence 🔁</button>
    </div>

    <div class="feedback" id="speakFeedback"></div>

    <div class="box" id="speakReveal" style="display:none;">
      <div class="small">Correct Turkish month:</div>
      <div class="bigTR" id="speakCorrectTR">Mart</div>
      <div class="hint" id="speakTip">MART (simple, like “mart”)</div>
    </div>

    <div class="hr"></div>
    <div class="small center" id="speechSupportNote"></div>
  </section>
</div>

<script>
  // ==========================
  // DATA: Months (English -> Turkish) + simple Turkish-style pronunciation hints
  // ==========================
  const MONTHS = [
    { en: "January",   tr: "Ocak",    tip: "o-JAK" },
    { en: "February",  tr: "Şubat",   tip: "shu-BAT (ş = sh)" },
    { en: "March",     tr: "Mart",    tip: "MART" },
    { en: "April",     tr: "Nisan",   tip: "ni-SAN" },
    { en: "May",       tr: "Mayıs",   tip: "ma-YIS (ı is dotless)" },
    { en: "June",      tr: "Haziran", tip: "ha-zi-RAN" },
    { en: "July",      tr: "Temmuz",  tip: "tem-MUZ" },
    { en: "August",    tr: "Ağustos", tip: "aa-OOS-tos (ğ is soft)" },
    { en: "September", tr: "Eylül",   tip: "ey-LÜL (ü sound)" },
    { en: "October",   tr: "Ekim",    tip: "e-KIM" },
    { en: "November",  tr: "Kasım",   tip: "ka-SIM (ı sound)" },
    { en: "December",  tr: "Aralık",  tip: "a-ra-LIK (ı sound)" }
  ];

  // “Tricky” distractors (near-looking spellings) to make MC harder
  const DISTRACTORS = [
    "Ocakkk","Subat","Mayis","Haziranı","Temmuzz","Agustos","Eylul","Ekım","Kasim","Aralik"
  ];

  // ==========================
  // HELPERS
  // ==========================
  function shuffle(arr){
    const a = arr.slice();
    for (let i = a.length - 1; i > 0; i--) {
      const j = Math.floor(Math.random() * (i + 1));
      [a[i], a[j]] = [a[j], a[i]];
    }
    return a;
  }

  function normalizeTR(s){
    return (s || "")
      .trim()
      .toLocaleLowerCase("tr-TR")
      .replace(/[’'".,!?]/g, "")
      .replace(/\s+/g, " ");
  }

  // ==========================
  // SLIDES NAV
  // ==========================
  const slides = [...document.querySelectorAll(".slide")];
  const prev = document.getElementById("prev");
  const next = document.getElementById("next");
  const indicator = document.getElementById("indicator");
  let slideIndex = 0;

  function showSlide(i){
    slideIndex = Math.max(0, Math.min(slides.length - 1, i));
    slides.forEach((s, k) => s.classList.toggle("active", k === slideIndex));
    indicator.textContent = `Slide ${slideIndex + 1} / ${slides.length}`;
    prev.classList.toggle("btn-disabled", slideIndex === 0);
    next.classList.toggle("btn-disabled", slideIndex === slides.length - 1);
  }

  prev.addEventListener("click", () => { if (slideIndex > 0) showSlide(slideIndex - 1); });
  next.addEventListener("click", () => { if (slideIndex < slides.length - 1) showSlide(slideIndex + 1); });

  document.getElementById("go1").addEventListener("click", () => showSlide(0));
  document.getElementById("go2").addEventListener("click", () => showSlide(1));
  document.getElementById("go3").addEventListener("click", () => showSlide(2));
  document.getElementById("go4").addEventListener("click", () => showSlide(3));
  document.getElementById("go5").addEventListener("click", () => showSlide(4));

  showSlide(0);

  // ==========================
  // TTS: pick Turkish voice if available
  // ==========================
  const voiceSelect = document.getElementById("voiceSelect");
  const testVoice = document.getElementById("testVoice");
  let cachedVoices = [];
  let chosenVoiceURI = "";

  function loadVoices(){
    cachedVoices = speechSynthesis.getVoices() || [];
    const current = voiceSelect.value;
    voiceSelect.innerHTML = `<option value="">(auto) Best Turkish voice</option>`;
    cachedVoices.forEach(v => {
      const opt = document.createElement("option");
      opt.value = v.voiceURI;
      opt.textContent = `${v.name} — ${v.lang}`;
      voiceSelect.appendChild(opt);
    });
    if (current) voiceSelect.value = current;
  }

  function getBestTurkishVoice(){
    const voices = cachedVoices;
    if (chosenVoiceURI) {
      const sel = voices.find(v => v.voiceURI === chosenVoiceURI);
      if (sel) return sel;
    }
    const tr = voices.filter(v => (v.lang || "").toLowerCase().startsWith("tr"));
    if (tr.length) return tr[0];
    return voices[0] || null;
  }

  function speakTR(text){
    const u = new SpeechSynthesisUtterance(text);
    u.lang = "tr-TR";
    u.rate = 0.92;
    u.pitch = 1;
    const v = getBestTurkishVoice();
    if (v) u.voice = v;
    speechSynthesis.cancel();
    speechSynthesis.speak(u);
  }

  voiceSelect.addEventListener("change", () => { chosenVoiceURI = voiceSelect.value || ""; });
  testVoice.addEventListener("click", () => { speakTR("Merhaba! Bugün Ağustos."); });

  loadVoices();
  if (typeof speechSynthesis !== "undefined") speechSynthesis.onvoiceschanged = loadVoices;

  // ==========================
  // SLIDE 1: learn grid
  // ==========================
  const learnGrid = document.getElementById("learnGrid");
  MONTHS.forEach(m => {
    const div = document.createElement("div");
    div.className = "card";
    div.innerHTML = `
      <h3>${m.en} → <span style="color:#1b5e20">${m.tr}</span></h3>
      <div class="row">
        <span class="tag">Hint</span>
        <span><strong>${m.tip}</strong></span>
      </div>
      <div class="row" style="margin-top:10px;justify-content:flex-end">
        <button class="btn btn-warn" data-say="${m.tr}">🔊 Listen</button>
      </div>
    `;
    div.querySelector("button").addEventListener("click", (e) => speakTR(e.currentTarget.dataset.say));
    learnGrid.appendChild(div);
  });

  // ==========================
  // SLIDE 2: Listening flashcards
  // ==========================
  const listenPlay = document.getElementById("listenPlay");
  const listenNew = document.getElementById("listenNew");
  const listenOptions = document.getElementById("listenOptions");
  const listenFeedback = document.getElementById("listenFeedback");
  const listenReveal = document.getElementById("listenReveal");
  const listenCorrectTR = document.getElementById("listenCorrectTR");
  const listenCorrectEN = document.getElementById("listenCorrectEN");
  let listenCurrent = null;

  function listenNewCard(){
    listenFeedback.textContent = "";
    listenFeedback.className = "feedback";
    listenReveal.style.display = "none";
    listenOptions.innerHTML = "";

    listenCurrent = MONTHS[Math.floor(Math.random() * MONTHS.length)];

    const others = shuffle(MONTHS.filter(x => x.tr !== listenCurrent.tr)).slice(0,3).map(x => x.tr);
    const opts = shuffle([listenCurrent.tr, ...others]);

    opts.forEach(t => {
      const b = document.createElement("button");
      b.className = "opt";
      b.textContent = t;
      b.addEventListener("click", () => {
        if (t === listenCurrent.tr) {
          listenFeedback.textContent = "Correct! 🎉";
          listenFeedback.className = "feedback good";
          listenReveal.style.display = "block";
          listenCorrectTR.textContent = listenCurrent.tr;
          listenCorrectEN.textContent = listenCurrent.en;
        } else {
          listenFeedback.textContent = "Try again 😅";
          listenFeedback.className = "feedback bad";
          listenReveal.style.display = "none";
        }
      });
      listenOptions.appendChild(b);
    });
  }

  listenPlay.addEventListener("click", () => {
    if (!listenCurrent) listenNewCard();
    speakTR(listenCurrent.tr);
  });
  listenNew.addEventListener("click", listenNewCard);
  listenNewCard();

  // ==========================
  // SLIDE 3: Hard MC English -> Turkish (+ distractor)
  // ==========================
  const mcListen = document.getElementById("mcListen");
  const mcNew = document.getElementById("mcNew");
  const mcQ = document.getElementById("mcQ");
  const mcOptions = document.getElementById("mcOptions");
  const mcFeedback = document.getElementById("mcFeedback");
  const mcPron = document.getElementById("mcPron");
  const mcTR = document.getElementById("mcTR");
  const mcTip = document.getElementById("mcTip");
  let mcCurrent = null;

  function mcNewQuestion(){
    mcFeedback.textContent = "";
    mcFeedback.className = "feedback";
    mcOptions.innerHTML = "";
    mcPron.style.display = "none";

    mcCurrent = MONTHS[Math.floor(Math.random() * MONTHS.length)];
    mcQ.textContent = `${mcCurrent.en} → ?`;

    const otherReal = shuffle(MONTHS.filter(x => x.tr !== mcCurrent.tr)).slice(0,2).map(x => x.tr);
    const distractor = DISTRACTORS[Math.floor(Math.random() * DISTRACTORS.length)];
    const opts = shuffle([mcCurrent.tr, ...otherReal, distractor]);

    opts.forEach(t => {
      const b = document.createElement("button");
      b.className = "opt";
      b.textContent = t;
      b.addEventListener("click", () => {
        if (t === mcCurrent.tr) {
          mcFeedback.textContent = "Correct! ✅";
          mcFeedback.className = "feedback good";
          mcPron.style.display = "block";
          mcTR.textContent = mcCurrent.tr;
          mcTip.textContent = mcCurrent.tip;
        } else {
          mcFeedback.textContent = "Nope — try again 😅";
          mcFeedback.className = "feedback bad";
          mcPron.style.display = "none";
        }
      });
      mcOptions.appendChild(b);
    });
  }

  mcListen.addEventListener("click", () => {
    if (!mcCurrent) mcNewQuestion();
    speakTR(mcCurrent.tr);
  });
  mcNew.addEventListener("click", mcNewQuestion);
  mcNewQuestion();

  // ==========================
  // SLIDE 4: Fill in the blanks
  // ==========================
  const fillList = document.getElementById("fillList");
  const fillCheck = document.getElementById("fillCheck");
  const fillClear = document.getElementById("fillClear");
  const fillFeedback = document.getElementById("fillFeedback");

  // Sentences: you fill Turkish month
  const fillExercises = [
    { prompt: "New Year is in <strong>January</strong>. In Turkish: ____", answer: "Ocak" },
    { prompt: "Valentine’s Day is in <strong>February</strong>. In Turkish: ____", answer: "Şubat" },
    { prompt: "My birthday is in <strong>May</strong>. In Turkish: ____", answer: "Mayıs" },
    { prompt: "Summer holiday often starts in <strong>June</strong>. In Turkish: ____", answer: "Haziran" },
    { prompt: "The hottest month is often <strong>August</strong>. In Turkish: ____", answer: "Ağustos" },
    { prompt: "School starts in <strong>September</strong>. In Turkish: ____", answer: "Eylül" },
    { prompt: "Halloween is in <strong>October</strong>. In Turkish: ____", answer: "Ekim" },
    { prompt: "Christmas is in <strong>December</strong>. In Turkish: ____", answer: "Aralık" }
  ];

  function renderFill(){
    fillList.innerHTML = "";
    fillExercises.forEach((ex, i) => {
      const div = document.createElement("div");
      div.className = "sentence";
      div.innerHTML = `
        <div><strong>${i+1})</strong> ${ex.prompt}</div>
        <div style="margin-top:8px;">
          <input type="text" data-answer="${ex.answer}" placeholder="Type Turkish month..." />
          <button class="btn btn-warn" data-say="${ex.answer}" style="padding:8px 12px;font-size:.9rem;">🔊 Listen</button>
        </div>
      `;
      div.querySelector("button").addEventListener("click", (e) => speakTR(e.currentTarget.dataset.say));
      fillList.appendChild(div);
    });
  }
  renderFill();

  fillCheck.addEventListener("click", () => {
    const items = [...fillList.querySelectorAll(".sentence")];
    let ok = 0;
    items.forEach(item => {
      const inp = item.querySelector("input");
      const ans = normalizeTR(inp.dataset.answer);
      const user = normalizeTR(inp.value);
      item.classList.remove("markOk","markNo");
      if (user && user === ans) {
        item.classList.add("markOk");
        ok++;
      } else {
        item.classList.add("markNo");
      }
    });
    if (ok === items.length) {
      fillFeedback.textContent = "Perfect! 🎉 All correct.";
      fillFeedback.className = "feedback good";
    } else {
      fillFeedback.textContent = `You got ${ok}/${items.length}. Fix the red ones and try again!`;
      fillFeedback.className = "feedback bad";
    }
  });

  fillClear.addEventListener("click", () => {
    [...fillList.querySelectorAll("input")].forEach(inp => inp.value = "");
    [...fillList.querySelectorAll(".sentence")].forEach(item => item.classList.remove("markOk","markNo"));
    fillFeedback.textContent = "";
    fillFeedback.className = "feedback";
  });

  // ==========================
  // SLIDE 5: Speaking challenge (SpeechRecognition optional)
  // ==========================
  const SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;
  const speechSupportNote = document.getElementById("speechSupportNote");

  function createRecognizer(){
    if (!SpeechRecognition) return null;
    const rec = new SpeechRecognition();
    rec.lang = "tr-TR";
    rec.interimResults = false;
    rec.maxAlternatives = 3;
    return rec;
  }

  const micBtn = document.getElementById("micBtn");
  const micStop = document.getElementById("micStop");
  const speechText = document.getElementById("speechText");
  const speakCheck = document.getElementById("speakCheck");
  const speakNew = document.getElementById("speakNew");
  const speakListenCorrect = document.getElementById("speakListenCorrect");
  const speakSentence = document.getElementById("speakSentence");
  const speakFeedback = document.getElementById("speakFeedback");
  const speakReveal = document.getElementById("speakReveal");
  const speakCorrectTR = document.getElementById("speakCorrectTR");
  const speakTip = document.getElementById("speakTip");

  let speakCurrent = null;
  let recognizer = createRecognizer();

  function newSpeakSentence(){
    speakFeedback.textContent = "";
    speakFeedback.className = "feedback";
    speakReveal.style.display = "none";
    speechText.value = "";

    speakCurrent = MONTHS[Math.floor(Math.random() * MONTHS.length)];

    const templates = [
      `My birthday is in ${speakCurrent.en}. In Turkish, it is ____.`,
      `We travel in ${speakCurrent.en}. Say the month in Turkish: ____.`,
      `Complete: "${speakCurrent.en} → ____" (Turkish)`,
      `In English: ${speakCurrent.en}. In Turkish: ____`
    ];
    speakSentence.textContent = templates[Math.floor(Math.random() * templates.length)];
  }

  function startRec(){
    if (!recognizer) return;
    try { recognizer.stop(); } catch(e) {}
    speakFeedback.textContent = "Listening… speak now! 🎙";
    speakFeedback.className = "feedback";

    recognizer.onresult = (event) => {
      speechText.value = event.results[0][0].transcript || "";
      speakFeedback.textContent = "Got it! Now press Check ✅";
      speakFeedback.className = "feedback";
    };
    recognizer.onerror = () => {
      speakFeedback.textContent = "Mic error. You can type the answer instead.";
      speakFeedback.className = "feedback bad";
    };
    recognizer.start();
  }

  function stopRec(){
    if (!recognizer) return;
    try { recognizer.stop(); } catch(e) {}
  }

  function isMatch(user, correct){
    const u = normalizeTR(user);
    const c = normalizeTR(correct);
    return u === c || u.includes(c);
  }

  micBtn.addEventListener("click", () => {
    if (!recognizer) {
      speakFeedback.textContent = "Speech recognition not supported here. Type the month instead 🙂";
      speakFeedback.className = "feedback bad";
      return;
    }
    startRec();
  });

  micStop.addEventListener("click", stopRec);

  speakListenCorrect.addEventListener("click", () => {
    if (!speakCurrent) newSpeakSentence();
    speakTR(speakCurrent.tr);
  });

  speakCheck.addEventListener("click", () => {
    if (!speakCurrent) newSpeakSentence();
    const user = speechText.value || "";
    if (!user.trim()) {
      speakFeedback.textContent = "Say it (or type it) first 🙂";
      speakFeedback.className = "feedback bad";
      return;
    }

    speakReveal.style.display = "block";
    speakCorrectTR.textContent = speakCurrent.tr;
    speakTip.textContent = speakCurrent.tip;

    if (isMatch(user, speakCurrent.tr)) {
      speakFeedback.textContent = "Correct! 🎉";
      speakFeedback.className = "feedback good";
    } else {
      speakFeedback.textContent = "Not quite — listen again and retry 😅";
      speakFeedback.className = "feedback bad";
    }
  });

  speakNew.addEventListener("click", newSpeakSentence);

  if (!SpeechRecognition) {
    speechSupportNote.textContent =
      "⚠️ Speech recognition is not available in this browser. You can still practice by typing + using Listen.";
  } else {
    speechSupportNote.textContent =
      "✅ Speech recognition available. Tip: speak clearly and close to the microphone.";
  }

  newSpeakSentence();
</script>
</body>
</html>
