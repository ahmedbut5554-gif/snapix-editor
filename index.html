<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Snapix AI</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap');
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
:root{--bg:#07070c;--card:#12121c;--card2:#1a1a28;--line:rgba(255,255,255,.08);--txt:#f2f2f7;--dim:#8b8b9e;--dim2:#5c5c70;--grad:linear-gradient(135deg,#7c5cff 0%,#c04dff 55%,#ff4d9d 100%);--green:#22c55e;--gold:#ffc53d}
body{background:#0b0b12;font-family:'Inter',system-ui,sans-serif;color:var(--txt)}
.stage{width:700px;display:flex;flex-direction:column;align-items:center;gap:22px;padding:26px 0 34px;background:radial-gradient(120% 80% at 50% 0%,#1a1030 0%,#0b0b12 55%);border-radius:22px}
.phone{position:relative;width:372px;height:790px;border-radius:46px;background:#000;box-shadow:0 0 0 2px #26263a,0 0 0 10px #0d0d15,0 40px 90px -20px rgba(124,92,255,.45),0 20px 50px rgba(0,0,0,.7);overflow:hidden;isolation:isolate}
.notch{position:absolute;top:12px;left:50%;transform:translateX(-50%);width:112px;height:30px;background:#000;border-radius:20px;z-index:60;box-shadow:inset 0 0 0 1px #1c1c2a}
.notch::after{content:"";position:absolute;right:16px;top:9px;width:9px;height:9px;border-radius:50%;background:#101024}
.viewport{position:absolute;inset:0;overflow:hidden;border-radius:46px}
.page{position:absolute;inset:0;display:flex;flex-direction:column;transition:transform .42s cubic-bezier(.4,0,.2,1),opacity .34s ease;will-change:transform,opacity;background:var(--bg)}
.page.right{transform:translateX(102%);opacity:.3}
.page.left{transform:translateX(-28%);opacity:.15}
.page.active{transform:translateX(0);opacity:1}
.scroll{flex:1;overflow-y:auto;overflow-x:hidden;padding:0 20px 26px}
.scroll::-webkit-scrollbar{width:0}
.statusbar{display:flex;justify-content:space-between;align-items:center;padding:14px 24px 4px;font-size:12.5px;font-weight:600;position:relative;z-index:5}
.sb-icons{display:flex;gap:5px;align-items:center;font-size:11px}
.sb-icons .b{width:18px;height:9px;border:1.4px solid var(--txt);border-radius:3px;position:relative}
.sb-icons .b::after{content:"";position:absolute;inset:1.4px;width:60%;background:var(--txt);border-radius:1px}
.topbar{display:flex;justify-content:space-between;align-items:center;padding:10px 0 16px}
.hello{font-size:12px;color:var(--dim);font-weight:500}
.brand{font-size:23px;font-weight:900;letter-spacing:-.6px;margin-top:1px}
.brand span{background:var(--grad);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent}
.avatar{width:40px;height:40px;border-radius:14px;background:var(--grad);display:grid;place-items:center;font-weight:800;font-size:15px}
.banner{border-radius:18px;padding:13px 15px;display:flex;align-items:center;gap:11px;font-size:12.5px;font-weight:600;margin-bottom:20px;border:1px solid var(--line);cursor:pointer}
.banner .ic{width:32px;height:32px;border-radius:10px;display:grid;place-items:center;flex:none;font-size:15px}
.banner.trial{background:linear-gradient(120deg,rgba(124,92,255,.16),rgba(255,77,157,.10))}
.banner.trial .ic{background:rgba(124,92,255,.28)}
.banner.free{background:linear-gradient(120deg,rgba(34,197,94,.14),rgba(255,197,61,.08))}
.banner.free .ic{background:rgba(34,197,94,.26)}
.banner.over{background:linear-gradient(120deg,rgba(255,77,157,.18),rgba(255,197,61,.10))}
.banner.over .ic{background:rgba(255,77,157,.3)}
.banner.prem{background:linear-gradient(120deg,rgba(255,197,61,.16),rgba(124,92,255,.12))}
.banner.prem .ic{background:rgba(255,197,61,.28)}
.banner b{color:#fff}
.banner .sub{font-weight:500;color:var(--dim);font-size:11px;margin-top:2px}
.banner .go{margin-left:auto;font-size:11px;font-weight:700;color:#fff;background:var(--grad);padding:7px 12px;border-radius:11px;flex:none}
.sect{display:flex;justify-content:space-between;align-items:baseline;margin:0 0 12px}
.sect h3{font-size:14.5px;font-weight:800}
.sect a{font-size:11.5px;color:var(--dim);font-weight:600;cursor:pointer}
.tools{display:grid;grid-template-columns:repeat(3,1fr);gap:11px;margin-bottom:24px}
.tool{background:var(--card);border:1px solid var(--line);border-radius:19px;padding:14px 8px 12px;display:flex;flex-direction:column;align-items:center;gap:9px;cursor:pointer;text-align:center;transition:transform .15s}
.tool:active{transform:scale(.96)}
.tool .tic{width:40px;height:40px;border-radius:13px;display:grid;place-items:center;color:#fff}
.tool svg{width:21px;height:21px}
.tool .nm{font-size:11px;font-weight:700;line-height:1.25}
.tool .dsc{font-size:9.5px;color:var(--dim2);font-weight:500}
.g1{background:linear-gradient(135deg,#7c5cff,#c04dff)}
.g2{background:linear-gradient(135deg,#ff7a45,#ff4d9d)}
.g3{background:linear-gradient(135deg,#22c55e,#0ea5a5)}
.g5{background:linear-gradient(135deg,#ffc53d,#ff7a45)}
.g6{background:linear-gradient(135deg,#c04dff,#0ea5e9)}
.g7{background:linear-gradient(135deg,#ff4d9d,#7c5cff)}
.presets{display:flex;gap:11px;overflow-x:auto;padding-bottom:6px}
.presets::-webkit-scrollbar{height:0}
.preset{flex:none;width:88px;cursor:pointer}
.preset .thumb{height:88px;border-radius:16px;position:relative;overflow:hidden;border:1px solid var(--line)}
.preset .thumb::after{content:"";position:absolute;inset:0;background:linear-gradient(180deg,transparent 40%,rgba(0,0,0,.55))}
.preset .lbl{position:absolute;left:8px;bottom:7px;font-size:10px;font-weight:700;z-index:2}
.preset .nm{font-size:10.5px;font-weight:600;color:var(--dim);margin-top:7px;text-align:center}
.tag{position:absolute;top:7px;left:7px;font-size:8px;font-weight:800;padding:3px 6px;border-radius:7px;background:rgba(0,0,0,.5);z-index:3}
.ed-head{display:flex;align-items:center;gap:12px;padding:8px 0 14px}
.back{width:36px;height:36px;border-radius:12px;background:var(--card);border:1px solid var(--line);display:grid;place-items:center;cursor:pointer}
.ed-head h3{font-size:16px;font-weight:800}
.ed-head .sub{font-size:11px;color:var(--dim);font-weight:500}
.mtabs{display:flex;gap:6px;background:var(--card);border:1px solid var(--line);padding:5px;border-radius:15px;margin-bottom:14px}
.mtabs button{flex:1;border:none;background:transparent;color:var(--dim);font-family:inherit;font-size:12.5px;font-weight:700;padding:10px;border-radius:11px;cursor:pointer;display:flex;align-items:center;justify-content:center;gap:7px}
.mtabs button.on{background:var(--grad);color:#fff}
.mtabs svg{width:15px;height:15px}
.canvas{height:280px;border-radius:22px;position:relative;overflow:hidden;border:1px solid var(--line);background:linear-gradient(160deg,#2a1d4a,#0f1024 60%,#3a1533)}
.canvas .scene{position:absolute;inset:0;background:radial-gradient(60% 55% at 30% 30%,rgba(255,180,120,.45),transparent 70%),radial-gradient(50% 50% at 78% 70%,rgba(120,180,255,.4),transparent 70%),linear-gradient(160deg,#241a44,#0d0e1f)}
#preview,#previewVid{position:absolute;inset:0;width:100%;height:100%;object-fit:contain;z-index:2;background:#000}
#preview{transition:filter .3s}
.uploader{position:absolute;inset:0;z-index:3;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:9px;cursor:pointer}
.uploader .uic{width:54px;height:54px;border-radius:18px;background:var(--grad);display:grid;place-items:center;font-size:26px;font-weight:300}
.uploader .ut{font-size:13px;font-weight:700}
.uploader .us{font-size:10.5px;color:var(--dim)}
.vdur{position:absolute;top:12px;right:12px;font-size:10px;font-weight:700;background:rgba(0,0,0,.6);padding:4px 9px;border-radius:9px;z-index:4;display:none}
.timeline{position:absolute;left:14px;right:14px;bottom:12px;height:5px;border-radius:4px;background:rgba(255,255,255,.22);z-index:4;display:none}
.timeline .fill{width:38%;height:100%;border-radius:4px;background:var(--grad)}
.facelock{display:flex;align-items:center;gap:9px;font-size:11px;font-weight:600;color:#cfe9d6;background:rgba(34,197,94,.1);border:1px solid rgba(34,197,94,.28);padding:10px 12px;border-radius:14px;margin-top:12px}
.facelock .dot{width:8px;height:8px;border-radius:50%;background:var(--green);flex:none}
.etime{margin-left:auto;font-size:10.5px;color:var(--dim);font-weight:600}
.chips{display:flex;gap:9px;overflow-x:auto;padding:14px 0 4px}
.chips::-webkit-scrollbar{height:0}
.chip{flex:none;padding:9px 15px;border-radius:13px;background:var(--card);border:1px solid var(--line);font-size:12px;font-weight:600;cursor:pointer;white-space:nowrap}
.chip.on{background:var(--grad);border-color:transparent}
.btn{width:100%;padding:16px;border:none;border-radius:18px;background:var(--grad);color:#fff;font-family:inherit;font-size:14.5px;font-weight:800;cursor:pointer;box-shadow:0 14px 30px -12px rgba(192,77,255,.85)}
.foot{padding:14px 20px 24px;border-top:1px solid var(--line)}
.pw-top{text-align:center;padding:20px 0 8px}
.crown{width:64px;height:64px;border-radius:22px;background:var(--grad);display:grid;place-items:center;margin:0 auto 16px;font-size:28px}
.pw-top h2{font-size:24px;font-weight:900}
.pw-top p{font-size:12.5px;color:var(--dim);margin-top:7px;font-weight:500}
.perks{display:flex;flex-direction:column;gap:10px;margin:20px 0}
.perk{display:flex;gap:11px;align-items:center;font-size:12.5px;font-weight:600;color:#dcdce8}
.perk .tick{width:21px;height:21px;border-radius:50%;background:rgba(34,197,94,.18);color:var(--green);display:grid;place-items:center;flex:none;font-size:11px;font-weight:900}
.plans{display:flex;flex-direction:column;gap:11px;margin-bottom:8px}
.plan{border:1.6px solid var(--line);border-radius:19px;padding:15px 16px;display:flex;align-items:center;gap:13px;cursor:pointer;background:var(--card);position:relative}
.plan.sel{border-color:#c04dff;background:linear-gradient(120deg,rgba(124,92,255,.14),rgba(255,77,157,.08))}
.radio{width:21px;height:21px;border-radius:50%;border:2px solid #3a3a52;flex:none;display:grid;place-items:center}
.plan.sel .radio{border-color:#c04dff}
.plan.sel .radio::after{content:"";width:11px;height:11px;border-radius:50%;background:var(--grad)}
.plan .info{flex:1}
.plan .t{font-size:14px;font-weight:800}
.plan .s{font-size:11px;color:var(--dim);font-weight:500;margin-top:2px}
.plan .price{text-align:right}
.plan .price .amt{font-size:17px;font-weight:900}
.plan .price .per{font-size:10px;color:var(--dim);font-weight:600}
.badge{position:absolute;top:-9px;right:14px;font-size:9px;font-weight:800;padding:4px 9px;border-radius:8px;background:var(--grad)}
.badge.gold{background:linear-gradient(135deg,#ffc53d,#ff7a45);color:#1a1200}
.fine{font-size:10.5px;color:var(--dim2);text-align:center;margin-top:14px;font-weight:500}
.payamt{background:var(--card);border:1px solid var(--line);border-radius:20px;padding:18px;text-align:center;margin-bottom:20px}
.payamt .l{font-size:11.5px;color:var(--dim);font-weight:600}
.payamt .v{font-size:30px;font-weight:900;margin-top:4px}
.payamt .p{font-size:11px;color:#ff4d9d;font-weight:700;margin-top:3px}
.meths{display:flex;flex-direction:column;gap:10px}
.meth{display:flex;align-items:center;gap:13px;padding:14px 15px;border:1.6px solid var(--line);border-radius:17px;cursor:pointer;background:var(--card)}
.meth.sel{border-color:#c04dff;background:linear-gradient(120deg,rgba(124,92,255,.13),rgba(255,77,157,.07))}
.meth .logo{width:42px;height:42px;border-radius:13px;display:grid;place-items:center;font-size:11px;font-weight:900;flex:none;color:#fff}
.meth .nm{font-size:13.5px;font-weight:700}
.meth .rg{font-size:10.5px;color:var(--dim);font-weight:500;margin-top:1px}
.meth .chk{margin-left:auto;width:20px;height:20px;border-radius:50%;border:2px solid #3a3a52}
.meth.sel .chk{border-color:#c04dff;background:var(--grad)}
.secure{display:flex;align-items:center;justify-content:center;gap:7px;font-size:10.5px;color:var(--dim2);margin-top:16px;font-weight:600}
.succ{flex:1;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:0 30px}
.bigcheck{width:104px;height:104px;border-radius:50%;background:var(--grad);display:grid;place-items:center;font-size:48px;color:#fff;animation:pop .55s cubic-bezier(.34,1.56,.64,1)}
@keyframes pop{0%{transform:scale(.3);opacity:0}100%{transform:scale(1);opacity:1}}
.succ h2{font-size:24px;font-weight:900;margin:24px 0 9px}
.succ p{font-size:13px;color:var(--dim);line-height:1.6;font-weight:500}
.toast{position:absolute;left:50%;bottom:34px;transform:translate(-50%,20px);background:rgba(20,20,32,.95);border:1px solid var(--line);padding:12px 18px;border-radius:15px;font-size:12.5px;font-weight:700;opacity:0;transition:all .3s;pointer-events:none;z-index:80;white-space:nowrap;max-width:90%}
.toast.show{opacity:1;transform:translate(-50%,0)}
.overlay{position:absolute;inset:0;background:rgba(5,5,10,.88);display:flex;flex-direction:column;align-items:center;justify-content:center;gap:18px;z-index:70;opacity:0;pointer-events:none;transition:opacity .3s}
.overlay.show{opacity:1;pointer-events:auto}
.spin{width:56px;height:56px;border-radius:50%;border:4px solid rgba(255,255,255,.12);border-top-color:#c04dff;animation:spin .8s linear infinite}
@keyframes spin{to{transform:rotate(360deg)}}
.overlay .ot{font-size:14px;font-weight:800}
.overlay .os{font-size:11.5px;color:var(--dim);margin-top:4px}
.pbar{width:200px;height:5px;border-radius:4px;background:rgba(255,255,255,.14);overflow:hidden}
.pbar i{display:block;height:100%;width:0;background:var(--grad);transition:width .4s}
.demo{display:flex;gap:8px;align-items:center;background:#12121c;border:1px solid #22223a;padding:9px 12px;border-radius:15px;flex-wrap:wrap;justify-content:center;max-width:640px}
.demo .lb{font-size:11px;color:#8b8b9e;font-weight:700}
.demo button{background:#1c1c2c;border:1px solid #2a2a42;color:#c8c8d8;font-family:inherit;font-size:11px;font-weight:700;padding:7px 12px;border-radius:10px;cursor:pointer}
.demo button.on{background:var(--grad);border-color:transparent;color:#fff}
.hint{font-size:11px;color:#5c5c70;text-align:center;max-width:520px;line-height:1.6}
@media(max-width:760px){.stage{width:100%;border-radius:0}.phone{transform:scale(.92)}}
</style>
</head>
<body>

<div class="stage">
<div class="phone"><div class="notch"></div><div class="viewport" id="vp">

<!-- HOME -->
<div class="page active" id="p-home">
<div class="statusbar"><span>9:41</span><span class="sb-icons">●●● <span class="b"></span></span></div>
<div class="scroll">
<div class="topbar"><div><div class="hello">Welcome back</div><div class="brand">Snapix <span>AI</span></div></div><div class="avatar">S</div></div>
<div class="banner" id="banner" onclick="bannerTap()"></div>
<div class="sect"><h3>AI Tools</h3><a onclick="toast('Saare tools upar hain')">See all</a></div>
<div class="tools" id="tools"></div>
<div class="sect"><h3>Signature Looks</h3><a onclick="toast('Looks jald aa rahe hain')">All</a></div>
<div class="presets" id="presets"></div>
</div></div>

<!-- EDITOR -->
<div class="page right" id="p-edit">
<div class="statusbar"><span>9:41</span><span class="sb-icons">●●● <span class="b"></span></span></div>
<div class="scroll">
<div class="ed-head"><div class="back" onclick="go('home')">←</div><div><h3 id="edTitle">AI Extend</h3><div class="sub" id="edSub">Expand canvas</div></div></div>
<div class="mtabs">
<button id="tab-photo" onclick="setMedia('photo')"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="16" rx="2"/><circle cx="8.5" cy="9.5" r="1.5"/><path d="M21 15l-5-5-9 9"/></svg>Photo</button>
<button id="tab-video" onclick="setMedia('video')"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="5" width="14" height="14" rx="2"/><path d="M16 10l6-3v10l-6-3z"/></svg>Video</button>
</div>
<div class="canvas">
<div class="scene"></div>
<img id="preview" style="display:none" alt="">
<video id="previewVid" style="display:none" muted loop playsinline></video>
<div class="uploader" id="uploader" onclick="pickFile()"><div class="uic">+</div><div class="ut" id="upT">Tap to upload photo</div><div class="us" id="upS">JPG or PNG</div></div>
<div class="vdur" id="vdur">00:12</div>
<div class="timeline" id="vtime"><div class="fill"></div></div>
</div>
<div class="facelock"><span class="dot"></span>Face Lock ON — face &amp; identity preserved<span class="etime" id="etime">~10 sec</span></div>
<div class="chips" id="chips"></div>
</div>
<div class="foot"><button class="btn" onclick="applyEdit()" id="applyBtn">Apply &amp; Save</button></div>
</div>

<!-- PAYWALL -->
<div class="page right" id="p-paywall">
<div class="statusbar"><span>9:41</span><span class="sb-icons">●●● <span class="b"></span></span></div>
<div class="scroll">
<div class="pw-top"><div class="crown">✨</div><h2>Unlimited Edits</h2><p>Daily limit hata dein — unlimited photos aur videos.</p></div>
<div class="perks">
<div class="perk"><span class="tick">✓</span> Unlimited photo + video edits</div>
<div class="perk"><span class="tick">✓</span> AI Extend, Deblur HD &amp; 4K upscale</div>
<div class="perk"><span class="tick">✓</span> Face Lock — faces never change</div>
<div class="perk"><span class="tick">✓</span> No watermark, priority speed</div>
</div>
<div class="plans" id="plans"></div>
<button class="btn" style="margin-top:18px" onclick="go('payment')">Continue</button>
<div class="fine">Cancel anytime. Auto-renewal on.</div>
</div></div>

<!-- PAYMENT -->
<div class="page right" id="p-payment">
<div class="statusbar"><span>9:41</span><span class="sb-icons">●●● <span class="b"></span></span></div>
<div class="scroll">
<div class="ed-head"><div class="back" onclick="go('paywall')">←</div><div><h3>Payment</h3><div class="sub">Payment method chunein</div></div></div>
<div class="payamt"><div class="l">Total Amount</div><div class="v" id="payVal">Rs 1200</div><div class="p" id="payPlan">1 Year plan</div></div>
<div class="meths" id="meths"></div>
<div class="secure">🔒 100% secure · Opens secure checkout</div>
</div>
<div class="foot"><button class="btn" onclick="doPay()">Pay Now</button></div>
</div>

<!-- SUCCESS -->
<div class="page right" id="p-success">
<div class="statusbar"><span>9:41</span><span class="sb-icons">●●● <span class="b"></span></span></div>
<div class="succ"><div class="bigcheck">✓</div><h2>Premium Unlocked!</h2><p>Your <b id="sPlan">1 Year</b> plan is active.<br>Ab unlimited editing enjoy karein.</p><button class="btn" style="margin-top:30px" onclick="go('home')">Start Editing</button></div>
</div>

<div class="overlay" id="overlay"><div class="spin"></div><div style="text-align:center"><div class="ot" id="ovTitle">Enhancing with AI...</div><div class="os" id="ovSub">Please wait</div></div><div class="pbar" id="pbar"><i></i></div></div>
<div class="toast" id="toast"></div>

</div></div>

<div class="demo"><span class="lb">DEMO:</span><button id="m-trial" onclick="setMode('trial')">Trial</button><button id="m-free" onclick="setMode('free')">Free (2/day)</button><button id="m-prem" onclick="setMode('premium')">Premium</button><button onclick="resetAll()">↺ Reset</button></div>
<div class="hint">Photo upload karein → option chunein → Apply. Limit localStorage me save hoti hai.</div>
</div>

<input type="file" id="fileIn" accept="image/*" hidden>
<input type="file" id="vidIn" accept="video/*" hidden>

<script>
/* ============================================================
   SNAPIX AI - app logic   (sab kuch self-contained, no crash)
   ============================================================ */

/* ---------- 1. CONFIG (yahan naam / key / links badlein) ---------- */
var CFG = {
  APP: 'Snapix AI',
  TRIAL_DAYS: 7,
  TRIAL_PER_DAY: 5,
  FREE_PER_DAY: 2,
  REPLICATE_KEY: '',                 // optional, abhi khali
  PAY_LINKS: { month: '', four: '', year: '' }   // yahan apne checkout links daalein
};

/* ---------- 2. ICONS ---------- */
var ICON = {
  extend: '<path d="M15 3h6v6"/><path d="M9 21H3v-6"/><path d="M21 3l-6.5 6
