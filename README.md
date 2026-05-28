# invesco.io
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <title></title>
  <meta name="Generator" content="Cocoa HTML Writer">
  <meta name="CocoaVersion" content="2575.3">
  <style type="text/css">
    p.p1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica}
    p.p2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; min-height: 14.0px}
  </style>
</head>
<body>
<p class="p1">&lt;!DOCTYPE html&gt;</p>
<p class="p1">&lt;html lang="en"&gt;</p>
<p class="p1">&lt;head&gt;</p>
<p class="p1">&lt;meta charset="UTF-8" /&gt;</p>
<p class="p1">&lt;meta name="viewport" content="width=device-width,initial-scale=1" /&gt;</p>
<p class="p1">&lt;title&gt;Invesco India Mutual Fund — Investor Portal&lt;/title&gt;</p>
<p class="p1">&lt;link rel="preconnect" href="https://fonts.googleapis.com"&gt;</p>
<p class="p1">&lt;link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&amp;family=Manrope:wght@500;700&amp;display=swap" rel="stylesheet"&gt;</p>
<p class="p1">&lt;script src="https://cdn.tailwindcss.com"&gt;&lt;/script&gt;</p>
<p class="p1">&lt;script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"&gt;&lt;/script&gt;</p>
<p class="p1">&lt;style&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>:root { color-scheme: light; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>*{font-family:'Inter',system-ui,-apple-system,Segoe UI,Roboto,sans-serif}</p>
<p class="p1"><span class="Apple-converted-space">  </span>body { background:linear-gradient(180deg,#FFFFFF 0%,#F8FAFC 100%); color:#0F172A; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.display{font-family:'Manrope',Inter,sans-serif}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.glass{ background:#FFFFFF; backdrop-filter:none; -webkit-backdrop-filter:none; border:1px solid #E2E8F0; box-shadow:0 1px 3px rgba(15,23,42,0.04),0 4px 12px rgba(15,23,42,0.04); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.glass-strong{ background:#FFFFFF; backdrop-filter:none; -webkit-backdrop-filter:none; border:1px solid #E2E8F0; box-shadow:0 4px 16px rgba(15,23,42,0.06),0 2px 6px rgba(15,23,42,0.04); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.mesh{ background:</p>
<p class="p1"><span class="Apple-converted-space">    </span>radial-gradient(40% 40% at 10% 10%, rgba(59,130,246,.08), transparent 60%),</p>
<p class="p1"><span class="Apple-converted-space">    </span>radial-gradient(35% 45% at 90% 20%, rgba(6,182,214,.07), transparent 60%),</p>
<p class="p1"><span class="Apple-converted-space">    </span>radial-gradient(50% 50% at 50% 100%, rgba(245,158,11,.05), transparent 60%),</p>
<p class="p1"><span class="Apple-converted-space">    </span>linear-gradient(180deg,#FFFFFF 0%,#F8FAFC 100%);</p>
<p class="p1"><span class="Apple-converted-space">    </span>animation: meshShift 20s ease-in-out infinite alternate;</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes meshShift{0%{filter:hue-rotate(0deg) saturate(1)}100%{filter:hue-rotate(10deg) saturate(1.1)}}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.shimmer{ position:relative; overflow:hidden}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.shimmer::after{ content:''; position:absolute; inset:0; background:linear-gradient(90deg,transparent,rgba(0,0,0,.05),transparent); transform:translateX(-100%); animation:shimmer 2.5s infinite}</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes shimmer{100%{transform:translateX(100%)}}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.no-scrollbar::-webkit-scrollbar{display:none}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.no-scrollbar{-ms-overflow-style:none;scrollbar-width:none}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.focus-ring:focus{ outline:2px solid #3B82F6; outline-offset:2px }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.pill{ background:#F1F5F9; border:1px solid #E2E8F0}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.tab-active{ background:rgba(59,130,246,.12); border-color:rgba(59,130,246,.4); color:#1D4ED8}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.step-active{ background:linear-gradient(135deg,#3B82F6,#06B6D4); color:white }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.step-done{ background:rgba(59,130,246,.12); border-color:#3B82F6; color:#1D4ED8}</p>
<p class="p1"><span class="Apple-converted-space">  </span>::-webkit-scrollbar{width:10px;height:10px}</p>
<p class="p1"><span class="Apple-converted-space">  </span>::-webkit-scrollbar-track{background:#F8FAFC}</p>
<p class="p1"><span class="Apple-converted-space">  </span>::-webkit-scrollbar-thumb{background:#CBD5E1;border-radius:999px;border:2px solid #F8FAFC}</p>
<p class="p1"><span class="Apple-converted-space">  </span>input::-webkit-outer-spin-button,input::-webkit-inner-spin-button{ -webkit-appearance:none; margin:0}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-primary{ position:relative; overflow:hidden; transition:all .3s cubic-bezier(0.4,0,0.2,1); background-size:200% auto; isolation:isolate; color:white; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-primary:hover{ transform:translateY(-2px) scale(1.02); box-shadow:0 10px 24px rgba(59,130,246,.25), 0 0 16px rgba(6,182,214,.18); background-position:right center; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-primary::before{ content:''; position:absolute; inset:0; left:-100%; width:100%; height:100%; background:linear-gradient(90deg,transparent,rgba(255,255,255,.28),transparent); transition:left .6s cubic-bezier(0.4,0,0.2,1); pointer-events:none; z-index:1; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-primary:hover::before{ left:100%; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-primary:active{ transform:scale(.98); }</p>
<p class="p2"><span class="Apple-converted-space">  </span></p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-secondary{ position:relative; overflow:hidden; transition:all .3s cubic-bezier(0.4,0,0.2,1); z-index:0; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-secondary::before{ content:''; position:absolute; inset:0; left:-100%; width:100%; height:100%; background:linear-gradient(90deg,rgba(59,130,246,.06),rgba(6,182,214,.08)); transition:left .35s cubic-bezier(0.4,0,0.2,1); z-index:-1; pointer-events:none; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-secondary:hover{ transform:scale(1.02); border-color:rgba(59,130,246,.5); background-color:#F8FAFC; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-secondary:hover::before{ left:0; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-secondary:active{ transform:scale(.98); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-ghost{ position:relative; transition:all .3s cubic-bezier(0.4,0,0.2,1); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-ghost::after{ content:''; position:absolute; left:0; bottom:-2px; width:0; height:2px; background:currentColor; transition:width .3s cubic-bezier(0.4,0,0.2,1); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-ghost:hover{ background:rgba(0,0,0,.04); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-ghost:hover::after{ width:100%; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-ghost:active{ transform:scale(.98); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-icon{ transition:all .3s cubic-bezier(0.4,0,0.2,1); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-icon:hover{ transform:rotate(5deg) scale(1.08); background:rgba(0,0,0,.06) !important; box-shadow:0 0 0 4px rgba(59,130,246,.12); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.btn-icon:active{ transform:rotate(5deg) scale(.95); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>.card-hover{ transition:all .3s cubic-bezier(0.4,0,0.2,1); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.card-hover:hover{ transform:translateY(-4px); box-shadow:0 20px 40px rgba(15,23,42,.08), 0 0 0 1px rgba(59,130,246,.2); border-color:rgba(59,130,246,.4) !important; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>button:focus-visible, a:focus-visible, [role="button"]:focus-visible{ outline:2px solid #3B82F6; outline-offset:3px; border-radius:12px; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>.form-input{ transition:all .25s ease; position:relative; background:white; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.form-input:focus{ transform:translateY(-1px); box-shadow:0 6px 16px rgba(59,130,246,.12), 0 0 0 2px rgba(59,130,246,.2); border-color:#3B82F6 !important; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.form-input:focus::placeholder{ opacity:0; transition:opacity .25s ease; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.form-input.valid{ border-color:rgb(34,197,94) !important; animation:validPulse 0.6s ease; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes validPulse{ 0%,100%{ box-shadow:0 0 0 0 rgba(34,197,94,.3); } 50%{ box-shadow:0 0 0 4px rgba(34,197,94,0); } }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.form-input.invalid{ border-color:rgb(239,68,68) !important; animation:shake .4s ease; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes shake{ 0%,100%{transform:translateX(0);} 10%,30%,50%,70%,90%{transform:translateX(-3px);} 20%,40%,60%,80%{transform:translateX(3px);} }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.form-input.invalid:focus{ box-shadow:0 6px 16px rgba(239,68,68,.15), 0 0 0 2px rgba(239,68,68,.2); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.input-icon{ transition:color .25s ease; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.input-group:focus-within .input-icon{ color:#3B82F6; }</p>
<p class="p2"><span class="Apple-converted-space">  </span></p>
<p class="p1"><span class="Apple-converted-space">  </span>.float-label{ position:relative; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.float-label label{ position:absolute; left:16px; top:50%; transform:translateY(-50%); font-size:14px; color:#64748B; pointer-events:none; transition:all .25s ease; background:transparent; padding:0 4px; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.float-label input:focus + label, .float-label input:not(:placeholder-shown) + label{ top:0; transform:translateY(-50%) scale(.85); color:#3B82F6; background:#FFFFFF; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>.ripple-container{ position:relative; overflow:hidden; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.ripple{ position:absolute; border-radius:50%; background:rgba(59,130,246,.25); transform:scale(0); animation:rippleEffect .6s ease-out; pointer-events:none; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes rippleEffect{ to{ transform:scale(4); opacity:0; } }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>.toast-enter{ animation:toastSpring .5s cubic-bezier(0.34,1.56,0.64,1); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes toastSpring{ 0%{ transform:translate(-50%,100px) scale(.8); opacity:0; } 100%{ transform:translate(-50%,0) scale(1); opacity:1; } }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.toast-exit{ animation:toastExit .3s ease-in forwards; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes toastExit{ to{ transform:translate(-50%,100px) scale(.9); opacity:0; } }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>.modal-overlay{ animation:modalOverlayIn .3s ease forwards; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes modalOverlayIn{ from{ opacity:0; } to{ opacity:1; } }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.modal-overlay.closing{ animation:modalOverlayOut .25s ease forwards; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes modalOverlayOut{ to{ opacity:0; } }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.modal-content{ animation:modalScaleIn .4s cubic-bezier(0.34,1.56,0.64,1) forwards; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes modalScaleIn{ from{ opacity:0; transform:scale(.96) translateY(12px); } to{ opacity:1; transform:scale(1) translateY(0); } }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.modal-content.closing{ animation:modalScaleOut .25s ease forwards; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes modalScaleOut{ to{ opacity:0; transform:scale(.97) translateY(8px); } }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>.tab-indicator{ position:relative; }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.tab-indicator::after{ content:''; position:absolute; bottom:-2px; left:0; height:2px; width:100%; background:linear-gradient(90deg,#3B82F6,#06B6D4); transform:scaleX(0); transform-origin:left; transition:transform .3s cubic-bezier(0.4,0,0.2,1); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.tab-indicator.active::after{ transform:scaleX(1); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>.dropdown-content{ max-height:0; opacity:0; overflow:hidden; transition:max-height .3s cubic-bezier(0.4,0,0.2,1), opacity .25s ease, transform .3s cubic-bezier(0.4,0,0.2,1); transform:translateY(-8px); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>.dropdown-content.open{ max-height:500px; opacity:1; transform:translateY(0); }</p>
<p class="p2"><span class="Apple-converted-space">  </span></p>
<p class="p1"><span class="Apple-converted-space">  </span>.help-pulse{position:relative}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.help-pulse::after{content:'';position:absolute;inset:-4px;border-radius:9999px;background:linear-gradient(90deg,#3B82F6,#06B6D4);opacity:.35;animation:pulseRing 2s infinite;z-index:-1}</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes pulseRing{0%{transform:scale(.9);opacity:.5}70%,100%{transform:scale(1.35);opacity:0}}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>.message-in{animation:msgIn .35s cubic-bezier(0.4,0,0.2,1)}</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes msgIn{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:translateY(0)}}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.typing-dot{width:6px;height:6px;border-radius:50%;background:rgb(100 116 139);animation:typingBounce 1.4s infinite}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.typing-dot:nth-child(2){animation-delay:.2s}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.typing-dot:nth-child(3){animation-delay:.4s}</p>
<p class="p1"><span class="Apple-converted-space">  </span>@keyframes typingBounce{0%,60%,100%{transform:translateY(0);opacity:.6}30%{transform:translateY(-5px);opacity:1}}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>/* Light theme overrides for Tailwind utilities */</p>
<p class="p1"><span class="Apple-converted-space">  </span>.text-slate-100{color:#0F172A !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.text-slate-200{color:#1E293B !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.text-slate-300{color:#334155 !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.text-slate-400{color:#475569 !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.text-slate-500{color:#64748B !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.bg-white\/5,.bg-white\/10{background:#FFFFFF !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.bg-white\/15{background:#F8FAFC !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.hover\:bg-white\/5:hover{background:#F8FAFC !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.hover\:bg-white\/10:hover{background:#F1F5F9 !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.hover\:bg-white\/15:hover{background:#E2E8F0 !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.border-white\/5{border-color:#F1F5F9 !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.border-white\/10,.border-white\/15{border-color:#E2E8F0 !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.divide-white\/10 &gt; :not([hidden]) ~ :not([hidden]){border-color:#E2E8F0 !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.bg-black\/20{background:rgba(255,255,255,0.9) !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>.bg-black\/40{background:rgba(255,255,255,0.96) !important}</p>
<p class="p1"><span class="Apple-converted-space">  </span>#chatMessages .glass{ background:#F1F5F9 !important; border-color:#E2E8F0 !important; }</p>
<p class="p1">&lt;/style&gt;</p>
<p class="p1">&lt;/head&gt;</p>
<p class="p1">&lt;body class="min-h-screen text-slate-800 selection:bg-cyan-500/20"&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div class="fixed inset-0 mesh"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div class="fixed inset-0 bg-[linear-gradient(to_top,rgba(248,250,252,.9),transparent_40%)] pointer-events-none"&gt;&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;header class="sticky top-0 z-[60] border-b border-slate-200"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="absolute inset-0 bg-white/80 backdrop-blur-2xl"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="relative max-w-[1280px] mx-auto px-4 md:px-8 h-[68px] flex items-center justify-between"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="flex items-center gap-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="w-9 h-9 rounded-2xl bg-gradient-to-br from-[#3B82F6] to-[#06B6D4] flex items-center justify-center shadow-lg shadow-blue-500/20"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;svg width="20" height="20" viewBox="0 0 24 24" fill="none"&gt;&lt;path d="M12 2L20 7v10l-8 5-8-5V7l8-5Z" stroke="white" stroke-width="1.5" stroke-linejoin="round"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="leading-tight"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="font-semibold tracking-tight display text-[17px] text-slate-900"&gt;Invesco Mutual Fund&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="text-[11px] uppercase tracking-widest text-slate-500 -mt-[2px]"&gt;India • Investor Portal&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;nav class="hidden md:flex items-center gap-1 text-sm"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;a href="#universe" class="px-3 py-2 rounded-xl hover:bg-slate-100 transition btn-ghost ripple-container"&gt;Fund Universe&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;a href="#insights" class="px-3 py-2 rounded-xl hover:bg-slate-100 transition btn-ghost ripple-container"&gt;Insights&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/nav&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="flex items-center gap-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;button id="openSupportBtn" class="hidden sm:inline-flex items-center gap-2 px-4 h-10 rounded-2xl glass hover:bg-slate-50 transition text-sm font-medium btn-secondary ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"&gt;&lt;path d="M21 15a4 4 0 0 1-4 4H7l-4 4V5a2 2 0 0 1 2-2h14a4 4 0 0 1 4 4z"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>Support</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;button id="openLoginBtn" class="hidden sm:inline-flex items-center gap-2 px-4 h-10 rounded-2xl glass hover:bg-slate-50 transition text-sm font-medium btn-secondary ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"&gt;&lt;path d="M15 3h4a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2h-4"/&gt;&lt;polyline points="10 17 15 12 10 7"/&gt;&lt;line x1="15" y1="12" x2="3" y2="12"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>Login</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;button id="openAccountBtn" class="inline-flex items-center gap-2 px-4 h-10 rounded-2xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold text-sm shadow-lg shadow-blue-600/20 hover:opacity-95 transition btn-primary ripple-container text-white"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"&gt;&lt;line x1="12" y1="5" x2="12" y2="19"/&gt;&lt;line x1="5" y1="12" x2="19" y2="12"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>Open Account</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;button id="mobileMenuBtn" class="md:hidden w-10 h-10 rounded-2xl glass flex items-center justify-center btn-icon ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;line x1="3" y1="6" x2="21" y2="6"/&gt;&lt;line x1="3" y1="12" x2="21" y2="12"/&gt;&lt;line x1="3" y1="18" x2="21" y2="18"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/header&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div id="mobileMenu" class="md:hidden fixed top-[68px] inset-x-0 z-50 hidden dropdown-content"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="mx-4 glass-strong rounded-3xl p-2 shadow-2xl"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;a href="#universe" class="block px-4 py-3 rounded-2xl hover:bg-slate-100 btn-ghost ripple-container"&gt;Fund Universe&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;a href="#insights" class="block px-4 py-3 rounded-2xl hover:bg-slate-100 btn-ghost ripple-container"&gt;Insights&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;a href="#" id="mobileSupportLink" class="block px-4 py-3 rounded-2xl hover:bg-slate-100 btn-ghost ripple-container"&gt;Support Center&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;main id="landingView" class="relative z-10"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section class="max-w-[1280px] mx-auto px-4 md:px-8 pt-14 md:pt-24 pb-16"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="grid lg:grid-cols-[1.1fr_.9fr] gap-12 items-center"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="inline-flex items-center gap-2 px-3 py-1 rounded-full pill text-xs mb-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"&gt;&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>Daily NAV • SEBI Regulated • Zero Commission</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;h1 class="display text-[44px] md:text-[64px] leading-[1.05] font-extrabold tracking-[-0.02em] text-slate-900"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>Invest with &lt;span class="bg-gradient-to-r from-[#3B82F6] via-[#06B6D4] to-[#F59E0B] bg-clip-text text-transparent"&gt;clarity&lt;/span&gt;,&lt;br/&gt;grow with confidence.</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/h1&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;p class="mt-5 text-slate-600 text-lg max-w-xl leading-relaxed"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>Modern light investing experience. Fund data from AMFI, instant eKYC, and institutional-grade analytics — all in one secure portal.</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="mt-8 flex flex-wrap gap-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button id="heroOpenAccount" class="px-5 h-12 rounded-2xl bg-slate-900 text-white font-semibold shadow-xl hover:bg-slate-800 transition btn-primary ripple-container"&gt;Start Investing&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button id="heroExplore" class="px-5 h-12 rounded-2xl glass-strong font-medium hover:bg-slate-50 transition btn-secondary ripple-container"&gt;Explore Funds&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="mt-10 grid grid-cols-2 sm:grid-cols-4 gap-3 max-w-2xl"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-2xl p-3 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[11px] uppercase tracking-wider text-slate-500"&gt;AUM&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-xl font-semibold text-slate-900"&gt;₹85,420 Cr&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-2xl p-3 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[11px] uppercase tracking-wider text-slate-500"&gt;Schemes&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-xl font-semibold text-slate-900"&gt;45+ Live&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-2xl p-3 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[11px] uppercase tracking-wider text-slate-500"&gt;Investors&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-xl font-semibold text-slate-900"&gt;12.4 Lakh+&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-2xl p-3 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[11px] uppercase tracking-wider text-slate-500"&gt;Avg Rating&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-xl font-semibold flex items-center gap-1 text-slate-900"&gt;4.6 &lt;span class="text-[#F59E0B]"&gt;★&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="relative"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="absolute -inset-6 bg-gradient-to-br from-[#3B82F6]/10 to-[#06B6D4]/10 blur-3xl rounded-[3rem]"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="relative glass-strong rounded-[2rem] p-6 md:p-8 shadow-2xl card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="flex items-center justify-between mb-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm font-medium text-slate-600"&gt;Portfolio Snapshot&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-xs pill px-2 py-1 rounded-full"&gt;Active&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="grid grid-cols-2 gap-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="rounded-2xl bg-slate-50 border border-slate-200 p-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="text-xs text-slate-500"&gt;Total Invested&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="text-2xl font-bold mt-1 text-slate-900"&gt;₹2,84,500&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="text-xs text-emerald-600 mt-1"&gt;+12.4% XIRR&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="rounded-2xl bg-slate-50 border border-slate-200 p-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="text-xs text-slate-500"&gt;Current Value&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="text-2xl font-bold mt-1 text-slate-900"&gt;₹3,19,842&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="text-xs text-sky-600 mt-1"&gt;NAV as on today&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mt-5 h-[120px] rounded-2xl bg-gradient-to-t from-[#3B82F6]/5 to-transparent border border-slate-200 p-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;svg viewBox="0 0 320 100" class="w-full h-full"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;defs&gt;&lt;linearGradient id="g1" x1="0" x2="0" y1="0" y2="1"&gt;&lt;stop offset="0%" stop-color="#3B82F6" stop-opacity=".4"/&gt;&lt;stop offset="100%" stop-color="#3B82F6" stop-opacity="0"/&gt;&lt;/linearGradient&gt;&lt;/defs&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;polyline fill="none" stroke="#3B82F6" stroke-width="2.5" stroke-linecap="round" points="0,70 40,65 80,68 120,55 160,58 200,40 240,45 280,30 320,35"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;polygon fill="url(#g1)" points="0,70 40,65 80,68 120,55 160,58 200,40 240,45 280,30 320,35 320,100 0,100"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mt-5 flex gap-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;span class="pill px-3 py-1 rounded-full text-xs"&gt;Large Cap&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;span class="pill px-3 py-1 rounded-full text-xs"&gt;Mid Cap&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;span class="pill px-3 py-1 rounded-full text-xs"&gt;ELSS&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;span class="pill px-3 py-1 rounded-full text-xs"&gt;Hybrid&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section id="universe" class="max-w-[1280px] mx-auto px-4 md:px-8 py-12"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="flex flex-wrap items-end justify-between gap-4 mb-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;h2 class="display text-[32px] md:text-[40px] font-bold tracking-tight text-slate-900"&gt;Fund Universe&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;p class="text-slate-500 mt-1"&gt;NAV data sourced from AMFI • All 45+ Invesco schemes&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="flex items-center gap-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="glass rounded-2xl flex items-center px-3 h-11 w-[260px] input-group"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#64748B" stroke-width="2" class="input-icon"&gt;&lt;circle cx="11" cy="11" r="8"/&gt;&lt;line x1="21" y1="21" x2="16.65" y2="16.65"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;input id="fundSearch" placeholder="Search funds..." class="form-input bg-transparent outline-none pl-2 w-full text-sm placeholder-slate-500 border-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;select id="categoryFilter" class="form-input glass h-11 rounded-2xl px-3 text-sm focus-ring bg-white"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;option value=""&gt;All Categories&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;option&gt;Equity&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;option&gt;Debt&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;option&gt;Hybrid&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;option&gt;ELSS&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;option&gt;Index&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;option&gt;Solution Oriented&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;option&gt;Other&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/select&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div id="fundGrid" class="grid sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-5"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div id="fundLoading" class="text-center py-16 text-slate-500"&gt;Fetching fund data from official sources…&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section id="insights" class="max-w-[1280px] mx-auto px-4 md:px-8 py-16"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="glass-strong rounded-[2rem] p-8 md:p-12"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="grid lg:grid-cols-3 gap-10"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;h3 class="display text-3xl font-bold text-slate-900"&gt;Institutional grade insights&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;p class="text-slate-500 mt-3"&gt;Curated research, risk metrics and portfolio overlays for smarter decisions.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="lg:col-span-2 grid sm:grid-cols-3 gap-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="rounded-2xl bg-slate-50 border border-slate-200 p-4 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-xs text-slate-500"&gt;Sharpe Ratio&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-2xl font-bold mt-1 text-slate-900"&gt;1.42&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="rounded-2xl bg-slate-50 border border-slate-200 p-4 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-xs text-slate-500"&gt;Beta&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-2xl font-bold mt-1 text-slate-900"&gt;0.94&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="rounded-2xl bg-slate-50 border border-slate-200 p-4 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-xs text-slate-500"&gt;Std Dev&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-2xl font-bold mt-1 text-slate-900"&gt;14.8%&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;section id="support" class="max-w-[1280px] mx-auto px-4 md:px-8 py-16 pb-28"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="grid md:grid-cols-2 gap-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="glass rounded-[2rem] p-8 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;h4 class="text-2xl font-bold display text-slate-900"&gt;Need help?&lt;/h4&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;p class="text-slate-500 mt-2"&gt;Chat with our investment specialists or browse knowledge base.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button id="supportCardBtn" class="mt-5 px-4 h-11 rounded-2xl bg-slate-900 text-white hover:bg-slate-800 transition text-sm btn-secondary ripple-container"&gt;Contact Support&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="glass rounded-[2rem] p-8 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;h4 class="text-2xl font-bold display text-slate-900"&gt;Secure &amp; Compliant&lt;/h4&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;p class="text-slate-500 mt-2"&gt;SEBI registered, 256-bit encryption, ISO 27001 aligned infrastructure.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="flex gap-2 mt-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;span class="pill px-3 py-1 rounded-full text-xs"&gt;2FA&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;span class="pill px-3 py-1 rounded-full text-xs"&gt;eKYC&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;span class="pill px-3 py-1 rounded-full text-xs"&gt;Audit Trail&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/section&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;footer class="border-t border-slate-200 bg-white/70 backdrop-blur-2xl"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="max-w-[1280px] mx-auto px-4 md:px-8 py-12"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="grid md:grid-cols-4 gap-10"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="flex items-center gap-2 mb-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="w-8 h-8 rounded-xl bg-gradient-to-br from-[#3B82F6] to-[#06B6D4] flex items-center justify-center"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;svg width="16" height="16" viewBox="0 0 24 24" fill="none"&gt;&lt;path d="M12 2L20 7v10l-8 5-8-5V7l8-5Z" stroke="white" stroke-width="1.5"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;span class="font-semibold text-slate-900"&gt;Invesco India&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;p class="text-sm text-slate-500 leading-relaxed"&gt;SEBI registered mutual fund. AMFI registered distributor. Investing involves market risks.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="font-semibold text-slate-900 mb-3"&gt;Quick Links&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;ul class="space-y-2 text-sm text-slate-600"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;&lt;a href="#universe" class="hover:text-slate-900 transition"&gt;Fund Universe&lt;/a&gt;&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;&lt;a href="#insights" class="hover:text-slate-900 transition"&gt;Insights&lt;/a&gt;&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;&lt;button onclick="openSupportCenter()" class="hover:text-slate-900 transition"&gt;Support Center&lt;/button&gt;&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;&lt;a href="https://www.invescomutualfund.com/" target="_blank" class="hover:text-slate-900 transition"&gt;Official Website&lt;/a&gt;&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/ul&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="font-semibold text-slate-900 mb-3"&gt;Investor Services&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;ul class="space-y-2 text-sm text-slate-600"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;1800-209-0007 (Toll-Free)&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;service@invesco.com&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;Mon-Sat 9AM-7PM IST&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;WhatsApp: +91 86579 50405&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/ul&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="font-semibold text-slate-900 mb-3"&gt;Fund Documents&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;ul class="space-y-2 text-sm"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;&lt;a href="https://www.invescomutualfund.com/literature-and-forms?litType=factsheet" target="_blank" class="text-slate-600 hover:text-[#3B82F6] transition flex items-center gap-1.5"&gt;Fund Factsheet &lt;svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/&gt;&lt;polyline points="15 3 21 3 21 9"/&gt;&lt;line x1="10" y1="14" x2="21" y2="3"/&gt;&lt;/svg&gt;&lt;/a&gt;&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;&lt;a href="https://www.invescomutualfund.com/literature-and-forms?litType=sid" target="_blank" class="text-slate-600 hover:text-[#3B82F6] transition flex items-center gap-1.5"&gt;Scheme Information Document &lt;svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/&gt;&lt;polyline points="15 3 21 3 21 9"/&gt;&lt;line x1="10" y1="14" x2="21" y2="3"/&gt;&lt;/svg&gt;&lt;/a&gt;&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;&lt;a href="https://www.invescomutualfund.com/literature-and-forms?litType=kim" target="_blank" class="text-slate-600 hover:text-[#3B82F6] transition flex items-center gap-1.5"&gt;Key Information Memorandum &lt;svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/&gt;&lt;polyline points="15 3 21 9"/&gt;&lt;line x1="10" y1="14" x2="21" y2="3"/&gt;&lt;/svg&gt;&lt;/a&gt;&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;&lt;a href="https://www.invescomutualfund.com/literature-and-forms?litType=annual" target="_blank" class="text-slate-600 hover:text-[#3B82F6] transition flex items-center gap-1.5"&gt;Annual Reports &lt;svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/&gt;&lt;polyline points="15 3 21 9"/&gt;&lt;line x1="10" y1="14" x2="21" y2="3"/&gt;&lt;/svg&gt;&lt;/a&gt;&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;li&gt;&lt;a href="https://www.invescomutualfund.com/literature-and-forms?litType=portfolio" target="_blank" class="text-slate-600 hover:text-[#3B82F6] transition flex items-center gap-1.5"&gt;Portfolio Disclosure &lt;svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/&gt;&lt;polyline points="15 3 21 3 21 9"/&gt;&lt;line x1="10" y1="14" x2="21" y2="3"/&gt;&lt;/svg&gt;&lt;/a&gt;&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/ul&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="mt-10 pt-6 border-t border-slate-200 flex flex-col md:flex-row items-center justify-between gap-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="text-xs text-slate-500"&gt;© 2025 Invesco Asset Management (India) Pvt. Ltd. • All documents sourced from official Invesco Mutual Fund website&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="flex items-center gap-4 text-xs text-slate-500"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;a href="#" class="hover:text-slate-700"&gt;Privacy&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;a href="#" class="hover:text-slate-700"&gt;Terms&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;a href="#" class="hover:text-slate-700"&gt;Disclosures&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/footer&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/main&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div id="dashboardView" class="hidden relative z-10 min-h-screen"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="max-w-[1440px] mx-auto flex"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;aside class="hidden lg:flex w-[280px] shrink-0 sticky top-[68px] h-[calc(100vh-68px)] p-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="glass-strong rounded-[1.8rem] w-full p-3 flex flex-col"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="px-3 py-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-xs uppercase tracking-widest text-slate-500"&gt;Investor&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="dashUserName" class="text-lg font-semibold mt-1 text-slate-900"&gt;—&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="dashUserRef" class="text-xs text-slate-500"&gt;Ref: —&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;nav class="space-y-1 px-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button data-tab="overview" class="dash-tab w-full flex items-center gap-3 px-3 h-11 rounded-2xl bg-slate-900 text-white btn-ghost tab-indicator active ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;rect x="3" y="3" width="7" height="7"/&gt;&lt;rect x="14" y="3" width="7" height="7"/&gt;&lt;rect x="14" y="14" width="7" height="7"/&gt;&lt;rect x="3" y="14" width="7" height="7"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>Overview</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button data-tab="holdings" class="dash-tab w-full flex items-center gap-3 px-3 h-11 rounded-2xl hover:bg-slate-100 text-slate-600 btn-ghost tab-indicator ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;line x1="12" y1="20" x2="12" y2="10"/&gt;&lt;line x1="18" y1="20" x2="18" y2="4"/&gt;&lt;line x1="6" y1="20" x2="6" y2="16"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>Holdings</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button data-tab="transactions" class="dash-tab w-full flex items-center gap-3 px-3 h-11 rounded-2xl hover:bg-slate-100 text-slate-600 btn-ghost tab-indicator ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;circle cx="12" cy="12" r="10"/&gt;&lt;polyline points="12 6 12 12 16 14"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>Transactions</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button data-tab="profile" class="dash-tab w-full flex items-center gap-3 px-3 h-11 rounded-2xl hover:bg-slate-100 text-slate-600 btn-ghost tab-indicator ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/&gt;&lt;circle cx="12" cy="7" r="4"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>Profile &amp; Security</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button data-tab="support" class="dash-tab w-full flex items-center gap-3 px-3 h-11 rounded-2xl hover:bg-slate-100 text-slate-600 btn-ghost tab-indicator ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M21 15a4 4 0 0 1-4 4H7l-4 4V5a2 2 0 0 1 2-2h14a4 4 0 0 1 4 4z"/&gt;&lt;path d="M12 11h.01"/&gt;&lt;path d="M8 11h.01"/&gt;&lt;path d="M16 11h.01"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>Support</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/nav&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="mt-auto p-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button id="logoutBtn" class="w-full h-11 rounded-2xl bg-slate-100 hover:bg-slate-200 text-sm btn-secondary ripple-container"&gt;Logout&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/aside&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;section class="flex-1 min-w-0 px-4 md:px-8 py-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="flex items-center justify-between mb-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;h1 class="display text-3xl font-bold text-slate-900"&gt;Dashboard&lt;/h1&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;p class="text-slate-500 text-sm"&gt;Welcome back, &lt;span id="dashWelcomeName"&gt;Investor&lt;/span&gt;&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="flex gap-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button id="dashSupportBtn" class="hidden sm:inline-flex px-4 h-10 rounded-2xl glass text-sm hover:bg-slate-50 btn-secondary ripple-container"&gt;Support&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button id="dashResendWelcome" class="hidden sm:inline-flex px-4 h-10 rounded-2xl glass text-sm hover:bg-slate-50 btn-secondary ripple-container"&gt;Resend Welcome Email&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div id="tab-overview" class="space-y-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="grid md:grid-cols-3 gap-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass-strong rounded-[1.6rem] p-6 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm text-slate-500"&gt;Total Portfolio Value&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-3xl font-bold mt-2 text-slate-900"&gt;₹3,19,842&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-emerald-600 text-sm mt-1"&gt;+12.4% XIRR&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-[1.6rem] p-6 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm text-slate-500"&gt;Invested&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-3xl font-bold mt-2 text-slate-900"&gt;₹2,84,500&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-slate-500 text-sm mt-1"&gt;Across 6 schemes&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-[1.6rem] p-6 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm text-slate-500"&gt;Today's Gain&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-3xl font-bold mt-2 text-emerald-600"&gt;+₹1,842&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-slate-500 text-sm mt-1"&gt;0.58%&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="glass-strong rounded-[1.8rem] p-6 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-sm font-medium mb-4 text-slate-900"&gt;Asset Allocation&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="grid sm:grid-cols-3 gap-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="rounded-2xl bg-slate-50 border border-slate-200 p-4"&gt;Equity &lt;span class="float-right font-semibold"&gt;68%&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="rounded-2xl bg-slate-50 border border-slate-200 p-4"&gt;Debt &lt;span class="float-right font-semibold"&gt;22%&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="rounded-2xl bg-slate-50 border border-slate-200 p-4"&gt;Hybrid &lt;span class="float-right font-semibold"&gt;10%&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div id="tab-holdings" class="hidden space-y-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="glass-strong rounded-[1.8rem] p-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-lg font-semibold mb-4 text-slate-900"&gt;Your Holdings&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="holdingsList" class="divide-y divide-slate-200"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div id="tab-transactions" class="hidden space-y-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="glass-strong rounded-[1.8rem] p-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-lg font-semibold mb-4 text-slate-900"&gt;Recent Transactions&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="txList" class="space-y-3"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div id="tab-profile" class="hidden space-y-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="glass-strong rounded-[1.8rem] p-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="flex items-center justify-between"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="text-lg font-semibold text-slate-900"&gt;Profile Settings&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="text-sm text-slate-500"&gt;Manage security and preferences&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button id="fillDemoProfile" class="px-3 h-9 rounded-xl bg-slate-100 text-xs hover:bg-slate-200 btn-secondary ripple-container"&gt;Fill Demo Data&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="grid md:grid-cols-2 gap-5 mt-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="profileName" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Full Name&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="profilePan" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;PAN&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="profileMobile" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Mobile&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="profileEmail" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Email&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mt-8 border-t border-slate-200 pt-6 grid md:grid-cols-2 gap-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="rounded-2xl bg-slate-50 border border-slate-200 p-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex items-center justify-between"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="font-medium text-slate-900"&gt;Two-Factor Authentication&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-xs text-slate-500"&gt;Extra layer of security&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;button id="toggle2FA" class="w-12 h-7 rounded-full bg-slate-200 relative transition ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;span class="absolute top-[3px] left-[3px] w-5 h-5 rounded-full bg-white shadow transition"&gt;&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="mt-4 space-y-2 text-sm"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;label class="flex items-center gap-2"&gt;&lt;input type="radio" name="otpMethod" value="sms" class="accent-[#3B82F6]"/&gt; SMS OTP&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;label class="flex items-center gap-2"&gt;&lt;input type="radio" name="otpMethod" value="email" class="accent-[#3B82F6]"/&gt; Email OTP&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;label class="flex items-center gap-2"&gt;&lt;input type="radio" name="otpMethod" value="app" class="accent-[#3B82F6]"/&gt; Authenticator App&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="rounded-2xl bg-slate-50 border border-slate-200 p-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="font-medium text-slate-900"&gt;Password&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="text-xs text-slate-500 mb-3"&gt;Last changed 12 days ago&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;button id="changePasswordBtn" class="px-3 h-9 rounded-xl bg-white border border-slate-300 text-sm hover:bg-slate-50 btn-secondary ripple-container"&gt;Change Password&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mt-6 flex justify-end"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button id="saveProfileBtn" class="px-5 h-11 rounded-2xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold text-sm btn-primary ripple-container text-white"&gt;Save Changes&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div id="tab-support" class="hidden space-y-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="grid md:grid-cols-3 gap-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass-strong rounded-[1.6rem] p-6 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm text-slate-500"&gt;Open Tickets&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div id="dashOpenTickets" class="text-3xl font-bold mt-2 text-slate-900"&gt;0&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button onclick="openSupportCenter('mytickets')" class="mt-3 text-xs text-sky-600 hover:underline"&gt;View all →&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-[1.6rem] p-6 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm text-slate-500"&gt;Live Chat&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-lg font-semibold mt-2 flex items-center gap-2 text-slate-900"&gt;&lt;span class="w-2 h-2 bg-emerald-500 rounded-full animate-pulse"&gt;&lt;/span&gt;Agents online&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button onclick="openSupportCenter('contact'); setTimeout(()=&gt;document.getElementById('startLiveChatBtn')?.click(),300)" class="mt-3 px-3 h-8 rounded-lg bg-slate-100 text-xs hover:bg-slate-200 btn-secondary ripple-container"&gt;Start Chat&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-[1.6rem] p-6 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm text-slate-500"&gt;Help Center&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-lg font-semibold mt-2 text-slate-900"&gt;24x7 Support&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button onclick="openSupportCenter()" class="mt-3 px-3 h-8 rounded-lg bg-slate-100 text-xs hover:bg-slate-200 btn-secondary ripple-container"&gt;Open Support&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="glass-strong rounded-[1.8rem] p-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="flex items-center justify-between mb-4"&gt;&lt;div class="text-lg font-semibold text-slate-900"&gt;Quick Actions&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button onclick="openSupportCenter('ticket')" class="p-4 rounded-2xl bg-slate-50 hover:bg-slate-100 text-left transition btn-secondary ripple-container border border-slate-200"&gt;&lt;div class="text-2xl mb-1"&gt;🎫&lt;/div&gt;&lt;div class="text-sm font-medium"&gt;Raise Ticket&lt;/div&gt;&lt;div class="text-xs text-slate-500"&gt;Get help in 24h&lt;/div&gt;&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button onclick="openSupportCenter('faqs')" class="p-4 rounded-2xl bg-slate-50 hover:bg-slate-100 text-left transition btn-secondary ripple-container border border-slate-200"&gt;&lt;div class="text-2xl mb-1"&gt;❓&lt;/div&gt;&lt;div class="text-sm font-medium"&gt;Browse FAQs&lt;/div&gt;&lt;div class="text-xs text-slate-500"&gt;Instant answers&lt;/div&gt;&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button onclick="openSupportCenter('tutorials')" class="p-4 rounded-2xl bg-slate-50 hover:bg-slate-100 text-left transition btn-secondary ripple-container border border-slate-200"&gt;&lt;div class="text-2xl mb-1"&gt;▶️&lt;/div&gt;&lt;div class="text-sm font-medium"&gt;Video Guides&lt;/div&gt;&lt;div class="text-xs text-slate-500"&gt;Learn investing&lt;/div&gt;&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button onclick="openSupportCenter('downloads')" class="p-4 rounded-2xl bg-slate-50 hover:bg-slate-100 text-left transition btn-secondary ripple-container border border-slate-200"&gt;&lt;div class="text-2xl mb-1"&gt;📄&lt;/div&gt;&lt;div class="text-sm font-medium"&gt;Download Forms&lt;/div&gt;&lt;div class="text-xs text-slate-500"&gt;KYC, Nominee...&lt;/div&gt;&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/section&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div id="loginModal" class="fixed inset-0 z-[100] hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="absolute inset-0 bg-black/60 backdrop-blur-sm modal-overlay"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="relative max-w-[920px] mx-auto mt-[6vh] glass-strong rounded-[2rem] shadow-2xl overflow-hidden modal-content"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;button data-close="loginModal" class="absolute top-4 right-4 w-9 h-9 rounded-2xl bg-slate-100 hover:bg-slate-200 flex items-center justify-center z-10 btn-icon ripple-container"&gt;✕&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="grid md:grid-cols-[380px_1fr]"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="hidden md:block relative p-8 bg-gradient-to-b from-[#3B82F6]/10 to-transparent"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="text-2xl font-bold display text-slate-900"&gt;Welcome back&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;p class="text-slate-600 mt-2 text-sm"&gt;Secure access to your Invesco portfolio.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="absolute bottom-8 left-8 right-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="rounded-2xl bg-white border border-slate-200 p-4 text-sm text-slate-700"&gt;🔒 Bank-grade encryption • 2FA ready • SEBI compliant&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="p-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="flex gap-2 mb-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button data-login-tab="pan" class="login-tab px-4 h-10 rounded-2xl tab-active border text-sm font-medium btn-secondary ripple-container"&gt;PAN&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button data-login-tab="mobile" class="login-tab px-4 h-10 rounded-2xl border border-slate-300 text-sm font-medium btn-secondary ripple-container"&gt;Mobile OTP&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button data-login-tab="ref" class="login-tab px-4 h-10 rounded-2xl border border-slate-300 text-sm font-medium btn-secondary ripple-container"&gt;Reference No&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="login-pan" class="login-pane"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="float-label mb-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;input id="loginPan" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none uppercase tracking-widest"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;label&gt;PAN&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="float-label mb-2 mt-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="relative"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="loginPassword" type="password" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 pr-12 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Password&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;button id="toggleLoginPass" class="absolute right-3 top-1/2 -translate-y-1/2 text-slate-500 text-sm btn-ghost px-2 py-1 rounded-lg ripple-container"&gt;Show&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="flex items-center justify-between mt-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;label class="flex items-center gap-2 text-sm"&gt;&lt;input type="checkbox" class="accent-[#3B82F6]"/&gt; Remember me&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button id="forgotLink" class="text-sm text-sky-600 hover:underline btn-ghost px-2 py-1 rounded-lg ripple-container"&gt;Forgot password?&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button id="loginPanBtn" class="mt-6 w-full h-12 rounded-2xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold btn-primary ripple-container text-white"&gt;Login&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="login-mobile" class="login-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="float-label mb-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;input id="loginMobile" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;label&gt;Mobile Number&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button id="sendMobileOtpBtn" class="mt-4 w-full h-12 rounded-2xl bg-slate-100 hover:bg-slate-200 font-medium btn-secondary ripple-container"&gt;Send OTP&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="mobileOtpBox" class="hidden mt-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label mb-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="mobileOtpInput" maxlength="6" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 tracking-[0.4em] text-center text-xl outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Enter OTP&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button id="verifyMobileOtpBtn" class="mt-4 w-full h-12 rounded-2xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold btn-primary ripple-container text-white"&gt;Verify &amp; Login&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="login-ref" class="login-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="float-label mb-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;input id="loginRef" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none uppercase"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;label&gt;Reference Number&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="float-label mb-2 mt-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;input id="loginRefPass" type="password" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;label&gt;Password&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button id="loginRefBtn" class="mt-6 w-full h-12 rounded-2xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold btn-primary ripple-container text-white"&gt;Login&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="mt-6 text-center text-sm text-slate-500"&gt;New investor? &lt;button id="loginToOnboard" class="text-sky-600 hover:underline btn-ghost px-1 rounded ripple-container"&gt;Open Account&lt;/button&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div id="forgotModal" class="fixed inset-0 z-[110] hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="absolute inset-0 bg-black/60 backdrop-blur-sm modal-overlay"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="relative max-w-md mx-auto mt-[10vh] glass-strong rounded-[2rem] p-8 modal-content"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;button data-close="forgotModal" class="absolute top-4 right-4 w-9 h-9 rounded-2xl bg-slate-100 hover:bg-slate-200 btn-icon ripple-container"&gt;✕&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;h3 class="text-2xl font-bold display text-slate-900"&gt;Reset Password&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;p class="text-sm text-slate-500 mt-1"&gt;Enter PAN to receive OTP&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="float-label mt-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;input id="forgotPan" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none uppercase"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;label&gt;PAN&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;button id="forgotSendOtp" class="mt-4 w-full h-12 rounded-2xl bg-slate-100 hover:bg-slate-200 btn-secondary ripple-container"&gt;Send OTP&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div id="forgotOtpBox" class="hidden mt-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="float-label mb-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;input id="forgotOtp" maxlength="6" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 tracking-[0.4em] text-center outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;label&gt;OTP&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;input id="forgotNewPass" type="password" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;label&gt;New Password&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;button id="forgotResetBtn" class="mt-4 w-full h-12 rounded-2xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold btn-primary ripple-container text-white"&gt;Reset Password&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div id="onboardWizard" class="fixed inset-0 z-[120] hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="absolute inset-0 bg-white modal-overlay"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="absolute inset-0 mesh opacity-40"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="relative h-full flex modal-content"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;aside class="w-[300px] hidden lg:flex flex-col border-r border-slate-200 bg-white/90 backdrop-blur-2xl p-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="flex items-center gap-3 mb-10"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="w-10 h-10 rounded-2xl bg-gradient-to-br from-[#3B82F6] to-[#06B6D4] flex items-center justify-center text-white"&gt;✓&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="font-bold display text-slate-900"&gt;Open Account&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;ol id="stepRail" class="space-y-4"&gt;&lt;/ol&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;button data-close="onboardWizard" class="mt-auto text-sm text-slate-500 hover:text-slate-900 btn-ghost px-2 py-1 rounded ripple-container"&gt;← Back to site&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/aside&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;main class="flex-1 overflow-y-auto"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="max-w-[900px] mx-auto px-6 md:px-12 py-10 md:py-16"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="flex items-center justify-between mb-10"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-xs uppercase tracking-widest text-slate-500"&gt;Step &lt;span id="stepNow"&gt;1&lt;/span&gt; of 6&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;h2 id="stepTitle" class="display text-3xl font-bold mt-1 text-slate-900"&gt;Personal Details&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button id="fillDemoBtn" class="px-3 h-9 rounded-xl bg-slate-100 text-xs hover:bg-slate-200 btn-secondary ripple-container"&gt;Fill Demo Data&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="step-1" class="step-pane"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="grid md:grid-cols-2 gap-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obName" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Full Name&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obPan" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none uppercase"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;PAN&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obMobile" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Mobile&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obEmail" type="email" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Email&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obDob" type="date" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Date of Birth&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;span class="text-sm text-slate-700 block mb-2"&gt;Occupation&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;select id="obOcc" class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;option&gt;Salaried&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;option&gt;Self Employed&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;option&gt;Business&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;option&gt;Student&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/select&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="step-2" class="step-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-[1.6rem] p-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="font-semibold mb-2 text-slate-900"&gt;Aadhaar eKYC (Stub)&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;p class="text-sm text-slate-500 mb-4"&gt;Enter Aadhaar to simulate OTP verification.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obAadhaar" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Aadhaar Number&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button id="obSendAadhaarOtp" class="mt-4 px-5 h-11 rounded-2xl bg-slate-100 hover:bg-slate-200 btn-secondary ripple-container"&gt;Send OTP&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div id="obAadhaarOtpBox" class="hidden mt-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;input id="obAadhaarOtp" maxlength="6" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 tracking-[0.4em] text-center outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;label&gt;Enter OTP (123456)&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;button id="obVerifyAadhaar" class="mt-3 px-5 h-11 rounded-2xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold btn-primary ripple-container text-white"&gt;Verify&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div id="obKycStatus" class="mt-4 text-sm text-emerald-600 hidden"&gt;✓ KYC Verified&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="step-3" class="step-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="grid md:grid-cols-2 gap-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obBankAcc" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Bank Account No&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obIfsc" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none uppercase"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;IFSC&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label md:col-span-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obBankName" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Account Holder Name&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="step-4" class="step-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="grid md:grid-cols-2 gap-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obNominee" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Nominee Name&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obNomRel" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Relationship&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="step-5" class="step-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="grid md:grid-cols-2 gap-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obPass" type="password" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Create Password&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="float-label"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;input id="obPass2" type="password" placeholder=" " class="form-input w-full h-12 rounded-2xl bg-white border border-slate-300 px-4 outline-none"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;label&gt;Confirm Password&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="md:col-span-2 text-xs text-slate-500"&gt;Password must be min 8 chars with uppercase, number &amp; symbol.&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="step-6" class="step-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-[1.6rem] p-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-lg font-semibold mb-4 text-slate-900"&gt;Review &amp; Submit&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div id="obReview" class="grid sm:grid-cols-2 gap-3 text-sm text-slate-700"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;label class="flex items-center gap-2 mt-6 text-sm"&gt;&lt;input id="obAgree" type="checkbox" class="accent-[#3B82F6]"/&gt; I agree to Terms &amp; Conditions&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="flex items-center justify-between mt-10"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button id="stepPrev" class="px-5 h-12 rounded-2xl bg-slate-100 hover:bg-slate-200 text-sm btn-secondary ripple-container"&gt;Back&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button id="stepNext" class="px-6 h-12 rounded-2xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold text-sm btn-primary ripple-container text-white"&gt;Continue&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/main&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div id="fundDetailModal" class="fixed inset-0 z-[130] hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="absolute inset-0 bg-black/60 backdrop-blur-sm modal-overlay"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="relative max-w-[1100px] mx-auto mt-[3vh] glass-strong rounded-[2rem] shadow-2xl max-h-[94vh] overflow-hidden flex flex-col modal-content"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;button data-close="fundDetailModal" class="absolute top-4 right-4 w-9 h-9 rounded-2xl bg-slate-100 hover:bg-slate-200 z-10 btn-icon ripple-container"&gt;✕&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="p-6 md:p-8 overflow-y-auto"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="flex flex-wrap items-start justify-between gap-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="flex-1 min-w-[300px]"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="fdCategory" class="text-xs pill px-2 py-1 rounded-full inline-block mb-2"&gt;Equity&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;h3 id="fdName" class="display text-2xl md:text-3xl font-bold text-slate-900 leading-tight"&gt;Fund Name&lt;/h3&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-sm text-slate-500 mt-1" id="fdMeta"&gt;—&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="text-right"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-xs text-slate-500"&gt;NAV&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="fdNav" class="text-3xl font-bold text-slate-900"&gt;₹0.00&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="fdNavDate" class="text-xs text-slate-500"&gt;as on —&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p2"><span class="Apple-converted-space">        </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="mt-6 grid lg:grid-cols-3 gap-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="lg:col-span-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-2xl p-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="flex items-center justify-between mb-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="text-sm font-semibold text-slate-900"&gt;NAV Performance&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex gap-1.5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;button data-period="1M" class="period-btn px-2.5 py-1 rounded-lg text-xs bg-slate-900 text-white"&gt;1M&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;button data-period="3M" class="period-btn px-2.5 py-1 rounded-lg text-xs hover:bg-slate-100"&gt;3M&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;button data-period="6M" class="period-btn px-2.5 py-1 rounded-lg text-xs hover:bg-slate-100"&gt;6M&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;button data-period="1Y" class="period-btn px-2.5 py-1 rounded-lg text-xs hover:bg-slate-100"&gt;1Y&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;button data-period="3Y" class="period-btn px-2.5 py-1 rounded-lg text-xs hover:bg-slate-100"&gt;3Y&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;button data-period="5Y" class="period-btn px-2.5 py-1 rounded-lg text-xs hover:bg-slate-100"&gt;5Y&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;button data-period="MAX" class="period-btn px-2.5 py-1 rounded-lg text-xs hover:bg-slate-100"&gt;Max&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="h-[260px] relative"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;canvas id="fdChart"&gt;&lt;/canvas&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p2"><span class="Apple-converted-space">            </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mt-5 glass rounded-2xl p-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm font-semibold mb-3 text-slate-900"&gt;Performance vs Benchmark&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="overflow-x-auto"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;table class="w-full text-sm"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;thead class="text-xs text-slate-500 border-b border-slate-200"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;tr&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;th class="text-left py-2 font-medium"&gt;Period&lt;/th&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;th class="text-right py-2 font-medium"&gt;Fund&lt;/th&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;th class="text-right py-2 font-medium"&gt;Category Avg&lt;/th&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;th class="text-right py-2 font-medium"&gt;Benchmark&lt;/th&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/tr&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/thead&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;tbody id="fdPerfTable" class="divide-y divide-slate-100"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/tbody&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/table&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p2"><span class="Apple-converted-space">          </span></p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="space-y-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-2xl p-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm font-semibold mb-3 text-slate-900"&gt;Scheme Details&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="space-y-3 text-sm"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex justify-between"&gt;&lt;span class="text-slate-500"&gt;Fund Manager&lt;/span&gt;&lt;span id="fdMgr" class="font-medium text-slate-900"&gt;—&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex justify-between"&gt;&lt;span class="text-slate-500"&gt;Inception&lt;/span&gt;&lt;span id="fdInception" class="font-medium text-slate-900"&gt;—&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex justify-between"&gt;&lt;span class="text-slate-500"&gt;AUM&lt;/span&gt;&lt;span id="fdAum" class="font-medium text-slate-900"&gt;—&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex justify-between"&gt;&lt;span class="text-slate-500"&gt;Expense Ratio&lt;/span&gt;&lt;span id="fdExp" class="font-medium text-slate-900"&gt;—&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex justify-between"&gt;&lt;span class="text-slate-500"&gt;Exit Load&lt;/span&gt;&lt;span class="font-medium text-slate-900"&gt;1% (&lt; 1 yr)&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p2"><span class="Apple-converted-space">            </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-2xl p-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm font-semibold mb-3 text-slate-900"&gt;Riskometer&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div id="fdRiskometer" class="flex flex-col items-center"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;svg width="140" height="80" viewBox="0 0 140 80"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;defs&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;linearGradient id="riskGrad" x1="0" x2="1"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;stop offset="0%" stop-color="#10B981"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;stop offset="33%" stop-color="#F59E0B"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;stop offset="66%" stop-color="#EF4444"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;stop offset="100%" stop-color="#991B1B"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/linearGradient&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/defs&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;path d="M10 70 A 60 60 0 0 1 130 70" fill="none" stroke="#E2E8F0" stroke-width="12" stroke-linecap="round"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;path id="riskArc" d="M10 70 A 60 60 0 0 1 130 70" fill="none" stroke="url(#riskGrad)" stroke-width="12" stroke-linecap="round" stroke-dasharray="188" stroke-dashoffset="94"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;circle id="riskDot" cx="70" cy="15" r="5" fill="#1E293B"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div id="fdRiskLabel" class="text-xs font-medium mt-1 px-2.5 py-1 rounded-full bg-amber-500/10 text-amber-700"&gt;Moderately High&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p2"><span class="Apple-converted-space">            </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-2xl p-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm font-semibold mb-2 text-slate-900"&gt;Documents&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="space-y-2 text-xs"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;a href="https://www.invescomutualfund.com/literature-and-forms?litType=factsheet" target="_blank" class="flex items-center justify-between hover:text-[#3B82F6]"&gt;&lt;span&gt;Factsheet&lt;/span&gt;↗&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;a href="https://www.invescomutualfund.com/literature-and-forms?litType=sid" target="_blank" class="flex items-center justify-between hover:text-[#3B82F6]"&gt;&lt;span&gt;SID&lt;/span&gt;↗&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;a href="https://www.invescomutualfund.com/literature-and-forms?litType=portfolio" target="_blank" class="flex items-center justify-between hover:text-[#3B82F6]"&gt;&lt;span&gt;Portfolio&lt;/span&gt;↗&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p2"><span class="Apple-converted-space">        </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="mt-6 flex justify-end gap-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button class="px-5 h-11 rounded-2xl bg-slate-100 hover:bg-slate-200 text-sm btn-secondary ripple-container"&gt;Add to Watchlist&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button class="px-5 h-11 rounded-2xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold text-sm btn-primary ripple-container text-white"&gt;Invest Now&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;!-- SUPPORT CENTER --&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div id="supportCenter" class="fixed inset-0 z-[140] hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="absolute inset-0 bg-white/90 backdrop-blur-xl modal-overlay"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="relative h-full flex flex-col lg:flex-row modal-content"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;button data-close="supportCenter" class="absolute top-4 right-4 w-9 h-9 rounded-2xl bg-slate-100 hover:bg-slate-200 flex items-center justify-center z-20 btn-icon lg:hidden"&gt;✕&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;aside class="lg:w-[310px] border-b lg:border-b-0 lg:border-r border-slate-200 bg-white flex flex-col"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="p-5 lg:p-6 border-b border-slate-200"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="flex items-center justify-between"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="flex items-center gap-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="w-10 h-10 rounded-2xl bg-gradient-to-br from-[#3B82F6] to-[#06B6D4] flex items-center justify-center shadow-lg"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"&gt;&lt;path d="M21 15a4 4 0 0 1-4 4H7l-4 4V5a2 2 0 0 1 2-2h14a4 4 0 0 1 4 4z"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="font-bold display text-[17px] text-slate-900"&gt;Support Center&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex items-center gap-1.5 mt-0.5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"&gt;&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;span class="text-[11px] text-emerald-600 font-medium"&gt;Agents online&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button data-close="supportCenter" class="hidden lg:flex w-8 h-8 rounded-xl hover:bg-slate-100 items-center justify-center btn-icon"&gt;✕&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="mt-3 text-[11px] text-slate-500"&gt;Avg response • 2 min • 98% satisfaction • Mon-Sat 9AM-7PM IST&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;nav class="p-3 space-y-1 overflow-y-auto flex-1"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button data-support-tab="contact" class="support-tab w-full flex items-center gap-3 px-3 h-11 rounded-xl bg-slate-900 text-white text-sm font-medium btn-ghost ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>Contact Us</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button data-support-tab="faqs" class="support-tab w-full flex items-center gap-3 px-3 h-11 rounded-xl hover:bg-slate-100 text-slate-600 text-sm font-medium btn-ghost ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;circle cx="12" cy="12" r="10"/&gt;&lt;path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"/&gt;&lt;path d="M12 17h.01"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>FAQs</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button data-support-tab="ticket" class="support-tab w-full flex items-center gap-3 px-3 h-11 rounded-xl hover:bg-slate-100 text-slate-600 text-sm font-medium btn-ghost ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/&gt;&lt;polyline points="14 2 14 8 20 8"/&gt;&lt;line x1="12" y1="18" x2="12" y2="12"/&gt;&lt;line x1="9" y1="15" x2="15" y2="15"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>Raise a Ticket</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button data-support-tab="mytickets" class="support-tab w-full flex items-center gap-3 px-3 h-11 rounded-xl hover:bg-slate-100 text-slate-600 text-sm font-medium btn-ghost ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;line x1="8" y1="6" x2="21" y2="6"/&gt;&lt;line x1="8" y1="12" x2="21" y2="12"/&gt;&lt;line x1="8" y1="18" x2="21" y2="18"/&gt;&lt;line x1="3" y1="6" x2="3.01" y2="6"/&gt;&lt;line x1="3" y1="12" x2="3.01" y2="12"/&gt;&lt;line x1="3" y1="18" x2="3.01" y2="18"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>My Tickets</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button data-support-tab="tutorials" class="support-tab w-full flex items-center gap-3 px-3 h-11 rounded-xl hover:bg-slate-100 text-slate-600 text-sm font-medium btn-ghost ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;polygon points="23 7 16 12 23 17 23 7"/&gt;&lt;rect x="1" y="5" width="15" height="14" rx="2" ry="2"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>Video Tutorials</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button data-support-tab="branches" class="support-tab w-full flex items-center gap-3 px-3 h-11 rounded-xl hover:bg-slate-100 text-slate-600 text-sm font-medium btn-ghost ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/&gt;&lt;circle cx="12" cy="10" r="3"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>Branch Locator</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button data-support-tab="downloads" class="support-tab w-full flex items-center gap-3 px-3 h-11 rounded-xl hover:bg-slate-100 text-slate-600 text-sm font-medium btn-ghost ripple-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/&gt;&lt;polyline points="7 10 12 15 17 10"/&gt;&lt;line x1="12" y1="15" x2="12" y2="3"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>Downloads</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/nav&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="p-4 border-t border-slate-200 hidden lg:block"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button id="supportLiveChatQuick" class="w-full h-11 rounded-2xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold text-sm btn-primary ripple-container text-white"&gt;Start Live Chat&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/aside&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;main class="flex-1 overflow-y-auto bg-[#F8FAFC]"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="max-w-[1100px] mx-auto p-6 lg:p-10"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="support-contact" class="support-pane"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mb-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;h2 class="display text-3xl font-bold text-slate-900"&gt;How can we help you today?&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;p class="text-slate-500 mt-2"&gt;Multiple channels, one commitment to resolve.&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="grid md:grid-cols-2 gap-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="glass-strong rounded-[1.6rem] p-6 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex items-start gap-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div class="w-12 h-12 rounded-2xl bg-emerald-500/10 flex items-center justify-center shrink-0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2"&gt;&lt;path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div class="flex-1"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-sm text-slate-500"&gt;24x7 Helpline (Toll-Free)&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-2xl font-bold mt-1 tracking-wide text-slate-900"&gt;1800-209-0007&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-xs text-slate-500 mt-1"&gt;Mon-Sat • 9:00 AM - 7:00 PM IST&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="flex gap-2 mt-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;a href="tel:18002090007" class="px-3 h-9 rounded-xl bg-slate-900 text-white hover:bg-slate-800 text-sm inline-flex items-center gap-1.5 btn-secondary ripple-container"&gt;Call Now&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;button onclick="toast('Callback requested')" class="px-3 h-9 rounded-xl bg-slate-100 hover:bg-slate-200 text-sm btn-secondary ripple-container"&gt;Request Callback&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="glass rounded-[1.6rem] p-6 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex items-start gap-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div class="w-12 h-12 rounded-2xl bg-sky-500/10 flex items-center justify-center shrink-0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#0284C7" stroke-width="2"&gt;&lt;path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/&gt;&lt;polyline points="22,6 12,13 2,6"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div class="flex-1"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-sm text-slate-500"&gt;Email Support&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-xl font-semibold mt-1 text-slate-900"&gt;service@invesco.com&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-xs text-slate-500 mt-1"&gt;Response within 24 hours&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;a href="mailto:service@invesco.com" class="mt-3 inline-flex px-3 h-9 rounded-xl bg-slate-100 hover:bg-slate-200 text-sm items-center btn-secondary ripple-container"&gt;Send Email&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="glass rounded-[1.6rem] p-6 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex items-start gap-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div class="w-12 h-12 rounded-2xl bg-green-500/10 flex items-center justify-center shrink-0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#16A34A" stroke-width="2"&gt;&lt;path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 0 0 1-7.6 4.7 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 0 0 1-.9-3.8 8.5 0 0 1 4.7-7.6 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8z"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div class="flex-1"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-sm text-slate-500"&gt;WhatsApp Banking&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-xl font-semibold mt-1 text-slate-900"&gt;+91 86579 50405&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-xs text-slate-500 mt-1"&gt;Instant NAV, statements &amp; support&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;a href="https://wa.me/918657950405" target="_blank" class="mt-3 inline-flex px-3 h-9 rounded-xl bg-slate-100 hover:bg-slate-200 text-sm items-center gap-1.5 btn-secondary ripple-container"&gt;Chat on WhatsApp&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="glass rounded-[1.6rem] p-6 card-hover border border-[#3B82F6]/30 relative overflow-hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="absolute -top-10 -right-10 w-32 h-32 bg-[#3B82F6]/10 rounded-full blur-3xl"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex items-start gap-4 relative"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div class="w-12 h-12 rounded-2xl bg-[#3B82F6]/10 flex items-center justify-center shrink-0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#3B82F6" stroke-width="2"&gt;&lt;path d="M21 15a4 4 0 0 1-4 4H7l-4 4V5a2 2 0 0 1 2-2h14a4 4 0 0 1 4 4z"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div class="flex-1"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="flex items-center gap-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;div class="text-sm text-slate-700 font-medium"&gt;Live Chat&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;span class="flex items-center gap-1 px-2 py-0.5 rounded-full bg-emerald-500/10 border border-emerald-500/20"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;span class="w-1.5 h-1.5 rounded-full bg-emerald-500 animate-pulse"&gt;&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">                        </span>&lt;span class="text-[10px] text-emerald-700 font-medium"&gt;ONLINE&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-xl font-bold mt-1 text-slate-900"&gt;Chat with AI assistant now&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="text-xs text-slate-500 mt-1"&gt;Instant answers • Powered by Invesco AI • NAV data&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;button id="startLiveChatBtn" class="mt-3 px-4 h-10 rounded-xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold text-sm shadow-lg shadow-blue-600/20 btn-primary ripple-container text-white"&gt;Start Live Chat&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mt-8 glass rounded-2xl p-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-sm font-medium mb-3 flex items-center gap-2 text-slate-900"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;circle cx="12" cy="12" r="10"/&gt;&lt;polyline points="12 6 12 12 16 14"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>Service Hours (IST)</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="grid sm:grid-cols-3 gap-4 text-sm"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div&gt;&lt;div class="text-slate-500 text-xs uppercase tracking-wide"&gt;Phone &amp; Chat&lt;/div&gt;&lt;div class="font-medium mt-1 text-slate-800"&gt;Monday - Saturday&lt;br&gt;9:00 AM - 7:00 PM&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div&gt;&lt;div class="text-slate-500 text-xs uppercase tracking-wide"&gt;Email Support&lt;/div&gt;&lt;div class="font-medium mt-1 text-slate-800"&gt;24x7 • Replies within&lt;br&gt;24 business hours&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div&gt;&lt;div class="text-slate-500 text-xs uppercase tracking-wide"&gt;Emergency Line&lt;/div&gt;&lt;div class="font-medium mt-1 text-slate-800"&gt;24x7 Toll-free&lt;br&gt;For blocking &amp; fraud&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="support-faqs" class="support-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mb-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;h2 class="display text-3xl font-bold text-slate-900"&gt;Frequently Asked Questions&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;p class="text-slate-500 mt-2"&gt;Find instant answers across 8 categories&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="faqContainer" class="space-y-3"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="support-ticket" class="support-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mb-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;h2 class="display text-3xl font-bold text-slate-900"&gt;Raise a Support Ticket&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;p class="text-slate-500 mt-2"&gt;We typically respond within 24 hours&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="grid lg:grid-cols-[1.1fr_.9fr] gap-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;form id="ticketForm" class="glass-strong rounded-[1.6rem] p-6 space-y-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="grid sm:grid-cols-2 gap-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;label class="text-xs text-slate-600 mb-1 block"&gt;Category&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;select id="ticketCategory" class="w-full h-11 rounded-xl bg-white border border-slate-300 px-3 text-sm outline-none focus:border-[#3B82F6]"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;option&gt;Account Opening&lt;/option&gt;&lt;option&gt;KYC&lt;/option&gt;&lt;option&gt;SIP&lt;/option&gt;&lt;option&gt;Redemption&lt;/option&gt;&lt;option&gt;NAV&lt;/option&gt;&lt;option&gt;Tax&lt;/option&gt;&lt;option&gt;Nominee&lt;/option&gt;&lt;option&gt;2FA / Security&lt;/option&gt;&lt;option&gt;Other&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/select&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;label class="text-xs text-slate-600 mb-1 block"&gt;Priority&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;select id="ticketPriority" class="w-full h-11 rounded-xl bg-white border border-slate-300 px-3 text-sm outline-none focus:border-[#3B82F6]"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;option&gt;Medium&lt;/option&gt;&lt;option&gt;High&lt;/option&gt;&lt;option&gt;Low&lt;/option&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/select&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;label class="text-xs text-slate-600 mb-1 block"&gt;Subject&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;input id="ticketSubject" class="w-full h-11 rounded-xl bg-white border border-slate-300 px-3 text-sm outline-none focus:border-[#3B82F6]" placeholder="Brief summary of issue"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;label class="text-xs text-slate-600 mb-1 block"&gt;Description&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;textarea id="ticketDesc" rows="5" class="w-full rounded-xl bg-white border border-slate-300 px-3 py-2 text-sm outline-none focus:border-[#3B82F6]" placeholder="Describe your issue in detail..."&gt;&lt;/textarea&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;label class="text-xs text-slate-600 mb-1 block"&gt;Attach Screenshot (optional)&lt;/label&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;input type="file" class="w-full text-xs file:mr-3 file:py-2 file:px-3 file:rounded-lg file:border-0 file:bg-slate-100 file:text-slate-700 hover:file:bg-slate-200"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;button type="submit" class="w-full h-11 rounded-xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] font-semibold text-sm btn-primary ripple-container text-white"&gt;Submit Ticket&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/form&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="space-y-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div id="ticketSuccess" class="hidden glass rounded-[1.6rem] p-6 border border-emerald-500/30"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div class="flex items-start gap-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div class="w-10 h-10 rounded-xl bg-emerald-500/10 flex items-center justify-center shrink-0 text-emerald-600"&gt;✓&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;div class="font-semibold text-emerald-700"&gt;Ticket Created Successfully&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;div class="text-sm mt-1"&gt;ID: &lt;span id="ticketSuccessId" class="font-mono text-sky-600"&gt;—&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                      </span>&lt;div class="text-xs text-slate-500 mt-2"&gt;Estimated response time: &lt;span id="ticketEst" class="text-slate-800"&gt;24 hours&lt;/span&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="glass rounded-[1.6rem] p-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;div class="text-sm font-medium mb-2 text-slate-900"&gt;What happens next?&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;ol class="text-xs text-slate-500 space-y-1.5 list-decimal list-inside"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;li&gt;You'll receive email confirmation&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;li&gt;Agent reviews within SLA&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;li&gt;Track progress in My Tickets&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">                    </span>&lt;li&gt;Get notified on resolution&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;/ol&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="support-mytickets" class="support-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mb-6 flex items-center justify-between"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;h2 class="display text-3xl font-bold text-slate-900"&gt;My Tickets&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;p class="text-slate-500 mt-1 text-sm"&gt;Track and manage your support requests&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;button onclick="switchSupportTab('ticket')" class="px-4 h-10 rounded-xl bg-slate-900 text-white hover:bg-slate-800 text-sm btn-secondary ripple-container"&gt;New Ticket&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="myTicketsList" class="glass-strong rounded-[1.6rem] p-2"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="support-tutorials" class="support-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mb-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;h2 class="display text-3xl font-bold text-slate-900"&gt;Video Tutorials&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;p class="text-slate-500 mt-2"&gt;Learn how to invest smarter in minutes&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="tutorialsGrid" class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="support-branches" class="support-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mb-6"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;h2 class="display text-3xl font-bold text-slate-900"&gt;Branch Locator&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;p class="text-slate-500 mt-2"&gt;Find your nearest Invesco service center&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="glass rounded-2xl p-4 mb-4 flex items-center gap-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#64748B" stroke-width="2"&gt;&lt;circle cx="11" cy="11" r="8"/&gt;&lt;line x1="21" y1="21" x2="16.65" y2="16.65"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;input id="branchSearch" placeholder="Search by city or branch name..." class="bg-transparent outline-none flex-1 text-sm placeholder-slate-500"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div id="branchesList" class="space-y-3"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div id="support-downloads" class="support-pane hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="mb-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;h2 class="display text-3xl font-bold text-slate-900"&gt;Downloads&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;p class="text-slate-500 mt-2"&gt;Forms and documents for your investments&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="grid sm:grid-cols-2 gap-3" id="downloadsList"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="glass rounded-2xl p-4 flex items-center justify-between card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex items-center gap-3"&gt;&lt;div class="w-10 h-10 rounded-xl bg-slate-100 flex items-center justify-center"&gt;📄&lt;/div&gt;&lt;div&gt;&lt;div class="font-medium text-sm text-slate-900"&gt;KYC Application Form&lt;/div&gt;&lt;div class="text-xs text-slate-500"&gt;PDF • 245 KB&lt;/div&gt;&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;button onclick="toast('Download started: KYC Form')" class="px-3 h-8 rounded-lg bg-slate-900 text-white hover:bg-slate-800 text-xs btn-secondary"&gt;Download&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="glass rounded-2xl p-4 flex items-center justify-between card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex items-center gap-3"&gt;&lt;div class="w-10 h-10 rounded-xl bg-slate-100 flex items-center justify-center"&gt;📄&lt;/div&gt;&lt;div&gt;&lt;div class="font-medium text-sm text-slate-900"&gt;Nomination Form&lt;/div&gt;&lt;div class="text-xs text-slate-500"&gt;PDF • 180 KB&lt;/div&gt;&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;button onclick="toast('Download started: Nomination')" class="px-3 h-8 rounded-lg bg-slate-900 text-white hover:bg-slate-800 text-xs btn-secondary"&gt;Download&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="glass rounded-2xl p-4 flex items-center justify-between card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex items-center gap-3"&gt;&lt;div class="w-10 h-10 rounded-xl bg-slate-100 flex items-center justify-center"&gt;📄&lt;/div&gt;&lt;div&gt;&lt;div class="font-medium text-sm text-slate-900"&gt;SIP Mandate Form&lt;/div&gt;&lt;div class="text-xs text-slate-500"&gt;PDF • 210 KB&lt;/div&gt;&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;button onclick="toast('Download started: SIP Mandate')" class="px-3 h-8 rounded-lg bg-slate-900 text-white hover:bg-slate-800 text-xs btn-secondary"&gt;Download&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="glass rounded-2xl p-4 flex items-center justify-between card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="flex items-center gap-3"&gt;&lt;div class="w-10 h-10 rounded-xl bg-slate-100 flex items-center justify-center"&gt;📄&lt;/div&gt;&lt;div&gt;&lt;div class="font-medium text-sm text-slate-900"&gt;FATCA Declaration&lt;/div&gt;&lt;div class="text-xs text-slate-500"&gt;PDF • 165 KB&lt;/div&gt;&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;button onclick="toast('Download started: FATCA')" class="px-3 h-8 rounded-lg bg-slate-900 text-white hover:bg-slate-800 text-xs btn-secondary"&gt;Download&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/main&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;!-- Live Chat AI Assistant --&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div id="liveChatWidget" class="fixed inset-0 z-[150] hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div id="chatBackdrop" class="absolute inset-0 bg-black/40 backdrop-blur-sm"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div id="liveChatPanel" class="absolute right-0 top-0 bottom-0 w-[420px] max-w-[100vw] glass-strong border-l border-slate-200 shadow-2xl flex flex-col translate-x-full transition-transform duration-300"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="h-[72px] flex items-center justify-between px-5 bg-gradient-to-r from-[#3B82F6]/5 to-[#06B6D4]/5 border-b border-slate-200 shrink-0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="flex items-center gap-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="w-11 h-11 rounded-2xl bg-gradient-to-br from-[#3B82F6] to-[#06B6D4] flex items-center justify-center shadow-lg shadow-blue-500/20"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"&gt;&lt;path d="M21 15a4 4 0 0 1-4 4H7l-4 4V5a2 2 0 0 1 2-2h14a4 4 0 0 1 4 4v4z"/&gt;&lt;circle cx="9" cy="11" r="1" fill="white"/&gt;&lt;circle cx="13" cy="11" r="1" fill="white"/&gt;&lt;circle cx="17" cy="11" r="1" fill="white"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="flex items-center gap-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;span class="font-semibold text-[16px] text-slate-900"&gt;Invesco AI Assistant&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;span class="w-2.5 h-2.5 rounded-full bg-emerald-500 animate-pulse shadow-emerald-500/30"&gt;&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-[12px] text-slate-500 -mt-0.5"&gt;AMFI data • Typically replies instantly&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;button id="chatClose" class="w-9 h-9 rounded-xl hover:bg-slate-100 flex items-center justify-center btn-icon ripple-container"&gt;✕&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div id="chatMessages" class="flex-1 overflow-y-auto px-4 py-4 space-y-4 bg-[radial-gradient(ellipse_at_top,_rgba(59,130,246,0.05),transparent_60%)]"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="p-4 border-t border-slate-200 bg-white shrink-0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div id="quickChips" class="flex flex-wrap gap-2 mb-3"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="flex gap-2 items-end"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="flex-1 relative"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;input id="chatInput" placeholder="Ask about NAV, SIP, performance..." class="w-full h-11 rounded-2xl bg-white border border-slate-300 px-4 pr-4 text-sm outline-none focus:border-[#3B82F6] focus:bg-white transition placeholder-slate-500"/&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button id="chatSendBtn" class="w-11 h-11 rounded-2xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] flex items-center justify-center hover:opacity-95 shadow-lg shadow-blue-600/20 btn-primary ripple-container shrink-0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"&gt;&lt;line x1="22" y1="2" x2="11" y2="13"/&gt;&lt;polygon points="22 2 15 22 11 13 2 9 22 2"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="text-[10px] text-slate-500 text-center mt-2"&gt;NAV data from AMFI via MFAPI.in • Verify before investing.&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;!-- Ticket Thread --&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div id="ticketThreadModal" class="fixed inset-0 z-[160] hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="absolute inset-0 bg-black/60 backdrop-blur-sm modal-overlay"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="relative max-w-[640px] mx-auto mt-[8vh] glass-strong rounded-[1.8rem] p-6 modal-content"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;button data-close="ticketThreadModal" class="absolute top-4 right-4 w-8 h-8 rounded-xl bg-slate-100 hover:bg-slate-200 btn-icon"&gt;✕&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="flex items-start justify-between gap-4"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div&gt;&lt;div class="text-xs text-slate-500"&gt;Ticket&lt;/div&gt;&lt;div id="ticketThreadId" class="font-mono text-sky-600"&gt;—&lt;/div&gt;&lt;div id="ticketThreadSubject" class="text-xl font-bold mt-1 text-slate-900"&gt;—&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;span id="ticketThreadStatus" class="px-2.5 py-1 rounded-full text-xs bg-amber-500/10 text-amber-700 border-amber-500/20"&gt;Open&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div id="ticketThreadMessages" class="mt-5 h-[300px] overflow-y-auto p-3 rounded-2xl bg-slate-50 border border-slate-200"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="mt-3 flex gap-2"&gt;&lt;input id="ticketReplyInput" placeholder="Type reply..." class="flex-1 h-11 rounded-xl bg-white border border-slate-300 px-3 text-sm outline-none focus:border-[#3B82F6]"/&gt;&lt;button id="ticketReplySend" class="px-4 h-11 rounded-xl bg-[#3B82F6] text-white font-medium text-sm btn-primary ripple-container"&gt;Send&lt;/button&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;!-- Video Player --&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div id="videoPlayerModal" class="fixed inset-0 z-[155] hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="absolute inset-0 bg-black/80 backdrop-blur-md modal-overlay"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="relative max-w-[900px] mx-auto mt-[6vh] p-4 modal-content"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;button data-close="videoPlayerModal" class="absolute -top-2 -right-2 w-9 h-9 rounded-full bg-white/90 hover:bg-white z-10 flex items-center justify-center btn-icon shadow-lg"&gt;✕&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="glass-strong rounded-[1.5rem] overflow-hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="aspect-video bg-black"&gt;&lt;iframe id="videoFrame" class="w-full h-full" src="" allow="autoplay; encrypted-media" allowfullscreen&gt;&lt;/iframe&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="p-4"&gt;&lt;div id="videoTitle" class="font-semibold text-slate-900"&gt;—&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;div id="toast" class="fixed bottom-6 left-1/2 -translate-x-1/2 z-[200] hidden"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="glass-strong rounded-2xl px-5 h-12 flex items-center gap-3 shadow-2xl"&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;span id="toastIcon"&gt;✓&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;span id="toastMsg" class="text-sm font-medium text-slate-900"&gt;Done&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;button id="floatingHelp" class="fixed bottom-6 right-6 z-[70] w-[56px] h-[56px] rounded-full bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] shadow-2xl shadow-blue-600/20 flex items-center justify-center hover:scale-110 transition-all duration-300 btn-primary ripple-container help-pulse"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"&gt;&lt;path d="M21 15a4 4 0 0 1-4 4H7l-4 4V5a2 2 0 0 1 2-2h14a4 4 0 0 1 4 4z"/&gt;&lt;circle cx="12" cy="11" r="1" fill="white"/&gt;&lt;circle cx="8.5" cy="11" r="1" fill="white"/&gt;&lt;circle cx="15.5" cy="11" r="1" fill="white"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">  </span>&lt;/button&gt;</p>
<p class="p2"><br></p>
<p class="p1">&lt;script&gt;</p>
<p class="p1">(() =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">  </span>const $ = s =&gt; document.querySelector(s);</p>
<p class="p1"><span class="Apple-converted-space">  </span>const $$ = s =&gt; [...document.querySelectorAll(s)];</p>
<p class="p2"><span class="Apple-converted-space">  </span></p>
<p class="p1"><span class="Apple-converted-space">  </span>function createRipple(e){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const btn = e.currentTarget;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const circle = document.createElement('span');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const diameter = Math.max(btn.clientWidth, btn.clientHeight);</p>
<p class="p1"><span class="Apple-converted-space">    </span>const radius = diameter / 2;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const rect = btn.getBoundingClientRect();</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>circle.style.width = circle.style.height = `${diameter}px`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>circle.style.left = `${e.clientX - rect.left - radius}px`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>circle.style.top = `${e.clientY - rect.top - radius}px`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>circle.classList.add('ripple');</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>const ripple = btn.querySelector('.ripple');</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(ripple) ripple.remove();</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>btn.appendChild(circle);</p>
<p class="p1"><span class="Apple-converted-space">    </span>setTimeout(()=&gt;circle.remove(), 600);</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><span class="Apple-converted-space">  </span></p>
<p class="p1"><span class="Apple-converted-space">  </span>document.addEventListener('click', e =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(e.target.closest('.ripple-container')){</p>
<p class="p1"><span class="Apple-converted-space">      </span>createRipple(e);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>const toast = (msg, icon='✓') =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const t = $('#toast');</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#toastMsg').textContent = msg;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#toastIcon').textContent = icon;</p>
<p class="p1"><span class="Apple-converted-space">    </span>t.classList.remove('hidden','toast-exit');</p>
<p class="p1"><span class="Apple-converted-space">    </span>t.classList.add('toast-enter');</p>
<p class="p1"><span class="Apple-converted-space">    </span>setTimeout(()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>t.classList.remove('toast-enter');</p>
<p class="p1"><span class="Apple-converted-space">      </span>t.classList.add('toast-exit');</p>
<p class="p1"><span class="Apple-converted-space">      </span>setTimeout(()=&gt;t.classList.add('hidden'),300);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}, 2700);</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function validateInput(input){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const val = input.value.trim();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const type = input.type;</p>
<p class="p1"><span class="Apple-converted-space">    </span>let isValid = true;</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>if(input.hasAttribute('required') &amp;&amp; !val){</p>
<p class="p1"><span class="Apple-converted-space">      </span>isValid = false;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>else if(type==='email' &amp;&amp; val &amp;&amp; !/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(val)){</p>
<p class="p1"><span class="Apple-converted-space">      </span>isValid = false;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>else if(input.id.includes('Pan') &amp;&amp; val &amp;&amp; !/^[A-Z]{5}[0-9]{4}[A-Z]$/.test(val.toUpperCase())){</p>
<p class="p1"><span class="Apple-converted-space">      </span>isValid = false;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>else if(input.id.includes('Mobile') &amp;&amp; val &amp;&amp; !/^\d{10}$/.test(val.replace(/\D/g,''))){</p>
<p class="p1"><span class="Apple-converted-space">      </span>isValid = false;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>input.classList.remove('valid','invalid');</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(val){</p>
<p class="p1"><span class="Apple-converted-space">      </span>input.classList.add(isValid ? 'valid' : 'invalid');</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>return isValid;</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><span class="Apple-converted-space">  </span></p>
<p class="p1"><span class="Apple-converted-space">  </span>document.addEventListener('blur', e =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(e.target.classList.contains('form-input')){</p>
<p class="p1"><span class="Apple-converted-space">      </span>validateInput(e.target);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>}, true);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>const STORE_KEY = 'invesco_users_v2';</p>
<p class="p1"><span class="Apple-converted-space">  </span>const SESSION_KEY = 'invesco_session_v2';</p>
<p class="p1"><span class="Apple-converted-space">  </span>let users = JSON.parse(localStorage.getItem(STORE_KEY) || '[]');</p>
<p class="p1"><span class="Apple-converted-space">  </span>let currentUser = null;</p>
<p class="p1"><span class="Apple-converted-space">  </span>let funds = [];</p>
<p class="p1"><span class="Apple-converted-space">  </span>let otpStore = {};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>// --- NAV CACHING ---</p>
<p class="p1"><span class="Apple-converted-space">  </span>const NAV_TTL = 5*60*1000;</p>
<p class="p1"><span class="Apple-converted-space">  </span>const SCHEME_TTL = 60*60*1000;</p>
<p class="p1"><span class="Apple-converted-space">  </span>let schemeCache = {ts:0, data:null};</p>
<p class="p1"><span class="Apple-converted-space">  </span>let navCache = {};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function parseMFDate(str){ const [d,m,y]=str.split('-').map(Number); return new Date(y,m-1,d); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>function fmtDate(str){ const dt=parseMFDate(str); return dt.toLocaleDateString('en-GB',{day:'2-digit',month:'short',year:'numeric'}); }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>async function getInvescoSchemes(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const now = Date.now();</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(schemeCache.data &amp;&amp; now - schemeCache.ts &lt; SCHEME_TTL) return schemeCache.data;</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>// Try official source first</p>
<p class="p1"><span class="Apple-converted-space">    </span>try{</p>
<p class="p1"><span class="Apple-converted-space">      </span>const officialUrl = 'https://api.allorigins.win/get?url=' + encodeURIComponent('https://www.invescomutualfund.com/');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const res = await fetch(officialUrl);</p>
<p class="p1"><span class="Apple-converted-space">      </span>if(res.ok){</p>
<p class="p1"><span class="Apple-converted-space">        </span>await res.json(); // consume but use MFAPI as it's more reliable for scheme codes</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>}catch(e){ /* fallback */ }</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>try{</p>
<p class="p1"><span class="Apple-converted-space">      </span>const res = await fetch('https://api.mfapi.in/mf/search?query=invesco');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const data = await res.json();</p>
<p class="p1"><span class="Apple-converted-space">      </span>schemeCache = {ts: now, data};</p>
<p class="p1"><span class="Apple-converted-space">      </span>return data;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}catch(e){</p>
<p class="p1"><span class="Apple-converted-space">      </span>return schemeCache.data || [];</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>async function getSchemeCode(name){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const list = await getInvescoSchemes();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const n = name.toLowerCase();</p>
<p class="p1"><span class="Apple-converted-space">    </span>let found = list.find(s=&gt; s.schemeName.toLowerCase() === n);</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!found) found = list.find(s=&gt; s.schemeName.toLowerCase().startsWith(n));</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!found) found = list.find(s=&gt; s.schemeName.toLowerCase().includes(n));</p>
<p class="p1"><span class="Apple-converted-space">    </span>return found?.schemeCode || null;</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>async function getLiveNavData(code){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const now = Date.now();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const cached = navCache[code];</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(cached &amp;&amp; now - cached.ts &lt; NAV_TTL) return cached.data;</p>
<p class="p1"><span class="Apple-converted-space">    </span>try{</p>
<p class="p1"><span class="Apple-converted-space">      </span>const res = await fetch(`https://api.mfapi.in/mf/${code}`);</p>
<p class="p1"><span class="Apple-converted-space">      </span>if(!res.ok) throw new Error('network');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const j = await res.json();</p>
<p class="p1"><span class="Apple-converted-space">      </span>const data = j.data || [];</p>
<p class="p1"><span class="Apple-converted-space">      </span>if(data.length &lt; 2) throw new Error('nodata');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const latest = data[0];</p>
<p class="p1"><span class="Apple-converted-space">      </span>const prev = data[1];</p>
<p class="p1"><span class="Apple-converted-space">      </span>const nav = parseFloat(latest.nav);</p>
<p class="p1"><span class="Apple-converted-space">      </span>const prevNav = parseFloat(prev.nav);</p>
<p class="p1"><span class="Apple-converted-space">      </span>const change1d = ((nav - prevNav)/prevNav)*100;</p>
<p class="p1"><span class="Apple-converted-space">      </span>const latestDate = parseMFDate(latest.date);</p>
<p class="p1"><span class="Apple-converted-space">      </span>const target = new Date(latestDate);</p>
<p class="p1"><span class="Apple-converted-space">      </span>target.setFullYear(target.getFullYear()-1);</p>
<p class="p1"><span class="Apple-converted-space">      </span>let yearItem = data.find(it =&gt; Math.abs(parseMFDate(it.date) - target) &lt; 7*24*60*60*1000) || data[Math.min(250, data.length-1)];</p>
<p class="p1"><span class="Apple-converted-space">      </span>const yearNav = parseFloat(yearItem.nav);</p>
<p class="p1"><span class="Apple-converted-space">      </span>const return1y = ((nav - yearNav)/yearNav)*100;</p>
<p class="p1"><span class="Apple-converted-space">      </span>const out = {</p>
<p class="p1"><span class="Apple-converted-space">        </span>scheme_name: j.meta.scheme_name,</p>
<p class="p1"><span class="Apple-converted-space">        </span>nav: nav.toFixed(2),</p>
<p class="p1"><span class="Apple-converted-space">        </span>date: fmtDate(latest.date),</p>
<p class="p1"><span class="Apple-converted-space">        </span>change1d,</p>
<p class="p1"><span class="Apple-converted-space">        </span>return1y,</p>
<p class="p1"><span class="Apple-converted-space">        </span>schemeCode: code</p>
<p class="p1"><span class="Apple-converted-space">      </span>};</p>
<p class="p1"><span class="Apple-converted-space">      </span>navCache[code] = {ts: now, data: out};</p>
<p class="p1"><span class="Apple-converted-space">      </span>return out;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}catch(e){</p>
<p class="p1"><span class="Apple-converted-space">      </span>if(cached) return cached.data;</p>
<p class="p1"><span class="Apple-converted-space">      </span>throw e;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function calculateReturns(data){</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!data || data.length &lt; 2) return {y1:0, y3:0, y5:0};</p>
<p class="p1"><span class="Apple-converted-space">    </span>const latest = data[0];</p>
<p class="p1"><span class="Apple-converted-space">    </span>const latestDate = parseMFDate(latest.date);</p>
<p class="p1"><span class="Apple-converted-space">    </span>const latestNav = parseFloat(latest.nav);</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>const findNavDaysBack = (days) =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">      </span>const target = new Date(latestDate);</p>
<p class="p1"><span class="Apple-converted-space">      </span>target.setDate(target.getDate() - days);</p>
<p class="p1"><span class="Apple-converted-space">      </span>let closest = data[data.length-1];</p>
<p class="p1"><span class="Apple-converted-space">      </span>let minDiff = Infinity;</p>
<p class="p1"><span class="Apple-converted-space">      </span>for(const item of data){</p>
<p class="p1"><span class="Apple-converted-space">        </span>const d = parseMFDate(item.date);</p>
<p class="p1"><span class="Apple-converted-space">        </span>const diff = Math.abs(d - target);</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(diff &lt; minDiff){</p>
<p class="p1"><span class="Apple-converted-space">          </span>minDiff = diff;</p>
<p class="p1"><span class="Apple-converted-space">          </span>closest = item;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(d &lt; target &amp;&amp; minDiff &lt; 30*24*60*60*1000) break;</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>return parseFloat(closest.nav);</p>
<p class="p1"><span class="Apple-converted-space">    </span>};</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>const nav1y = data.length &gt; 200 ? findNavDaysBack(365) : latestNav;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const nav3y = data.length &gt; 700 ? findNavDaysBack(1095) : latestNav;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const nav5y = data.length &gt; 1200 ? findNavDaysBack(1825) : latestNav;</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>return {</p>
<p class="p1"><span class="Apple-converted-space">      </span>y1: ((latestNav - nav1y) / nav1y * 100),</p>
<p class="p1"><span class="Apple-converted-space">      </span>y3: Math.pow(latestNav/nav3y, 1/3) - 1,</p>
<p class="p1"><span class="Apple-converted-space">      </span>y5: Math.pow(latestNav/nav5y, 1/5) - 1</p>
<p class="p1"><span class="Apple-converted-space">    </span>};</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>const saveUsers = ()=&gt; localStorage.setItem(STORE_KEY, JSON.stringify(users));</p>
<p class="p1"><span class="Apple-converted-space">  </span>const setSession = ref =&gt; localStorage.setItem(SESSION_KEY, ref);</p>
<p class="p1"><span class="Apple-converted-space">  </span>const clearSession = ()=&gt; localStorage.removeItem(SESSION_KEY);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#mobileMenuBtn').onclick = ()=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const menu = $('#mobileMenu');</p>
<p class="p1"><span class="Apple-converted-space">    </span>menu.classList.toggle('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>menu.classList.toggle('open');</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>const open = id =&gt; {<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>const el = $(id);</p>
<p class="p1"><span class="Apple-converted-space">    </span>const overlay = el.querySelector('.modal-overlay');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const content = el.querySelector('.modal-content');</p>
<p class="p1"><span class="Apple-converted-space">    </span>el.classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>overlay?.classList.remove('closing');</p>
<p class="p1"><span class="Apple-converted-space">    </span>content?.classList.remove('closing');</p>
<p class="p1"><span class="Apple-converted-space">    </span>document.body.style.overflow='hidden';</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p1"><span class="Apple-converted-space">  </span>const close = id =&gt; {<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>const el = $(id);</p>
<p class="p1"><span class="Apple-converted-space">    </span>const overlay = el.querySelector('.modal-overlay');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const content = el.querySelector('.modal-content');</p>
<p class="p1"><span class="Apple-converted-space">    </span>overlay?.classList.add('closing');</p>
<p class="p1"><span class="Apple-converted-space">    </span>content?.classList.add('closing');</p>
<p class="p1"><span class="Apple-converted-space">    </span>setTimeout(()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>el.classList.add('hidden');</p>
<p class="p1"><span class="Apple-converted-space">      </span>document.body.style.overflow='';</p>
<p class="p1"><span class="Apple-converted-space">    </span>}, 250);</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p2"><span class="Apple-converted-space">  </span></p>
<p class="p1"><span class="Apple-converted-space">  </span>$$('[data-close]').forEach(b=&gt; b.onclick = ()=&gt; close('#'+b.dataset.close));</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#openLoginBtn').onclick = ()=&gt; open('#loginModal');</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#openAccountBtn').onclick = ()=&gt; startOnboard();</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#heroOpenAccount').onclick = ()=&gt; startOnboard();</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#heroExplore').onclick = ()=&gt; document.querySelector('#universe').scrollIntoView({behavior:'smooth'});</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#loginToOnboard').onclick = ()=&gt; { close('#loginModal'); startOnboard(); };</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#supportCardBtn').onclick = ()=&gt; openSupportCenter();</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#openSupportBtn').onclick = ()=&gt; openSupportCenter();</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$$('.login-tab').forEach(btn=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">    </span>btn.onclick = ()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>$$('.login-tab').forEach(b=&gt;b.classList.remove('tab-active'));</p>
<p class="p1"><span class="Apple-converted-space">      </span>btn.classList.add('tab-active');</p>
<p class="p1"><span class="Apple-converted-space">      </span>$$('.login-pane').forEach(p=&gt;p.classList.add('hidden'));</p>
<p class="p1"><span class="Apple-converted-space">      </span>$('#login-'+btn.dataset.loginTab).classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>};</p>
<p class="p1"><span class="Apple-converted-space">  </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#toggleLoginPass').onclick = ()=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const i = $('#loginPassword');</p>
<p class="p1"><span class="Apple-converted-space">    </span>i.type = i.type==='password'?'text':'password';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#toggleLoginPass').textContent = i.type==='password'?'Show':'Hide';</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#loginPanBtn').onclick = ()=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const pan = $('#loginPan').value.trim().toUpperCase();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const pass = $('#loginPassword').value;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const u = users.find(x=&gt; x.pan===pan &amp;&amp; x.password===pass);</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!u) return toast('Invalid PAN or password','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>afterLogin(u);</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#sendMobileOtpBtn').onclick = ()=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const mob = $('#loginMobile').value.trim();</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(mob.length&lt;10) return toast('Enter valid mobile','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>otpStore[mob]='123456';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#mobileOtpBox').classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>toast('OTP sent: 123456');</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#verifyMobileOtpBtn').onclick = ()=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const mob = $('#loginMobile').value.trim();</p>
<p class="p1"><span class="Apple-converted-space">    </span>if($('#mobileOtpInput').value!==otpStore[mob]) return toast('Invalid OTP','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>let u = users.find(x=&gt;x.mobile===mob);</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!u){ u = {ref:genRef(), name:'Mobile User', pan:'', mobile:mob, email:'', password:'', twoFA:false, otpMethod:'sms'}; users.push(u); saveUsers(); }</p>
<p class="p1"><span class="Apple-converted-space">    </span>afterLogin(u);</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#loginRefBtn').onclick = ()=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const ref = $('#loginRef').value.trim().toUpperCase();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const pass = $('#loginRefPass').value;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const u = users.find(x=&gt; x.ref===ref &amp;&amp; x.password===pass);</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!u) return toast('Invalid reference or password','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>afterLogin(u);</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#forgotLink').onclick = ()=&gt; { close('#loginModal'); open('#forgotModal'); };</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#forgotSendOtp').onclick = ()=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const pan = $('#forgotPan').value.trim().toUpperCase();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const u = users.find(x=&gt;x.pan===pan);</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!u) return toast('PAN not found','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>otpStore['forgot_'+pan]='123456';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#forgotOtpBox').classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>toast('OTP sent: 123456');</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#forgotResetBtn').onclick = ()=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const pan = $('#forgotPan').value.trim().toUpperCase();</p>
<p class="p1"><span class="Apple-converted-space">    </span>if($('#forgotOtp').value!==otpStore['forgot_'+pan]) return toast('Invalid OTP','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const u = users.find(x=&gt;x.pan===pan);</p>
<p class="p1"><span class="Apple-converted-space">    </span>u.password = $('#forgotNewPass').value;</p>
<p class="p1"><span class="Apple-converted-space">    </span>saveUsers();</p>
<p class="p1"><span class="Apple-converted-space">    </span>toast('Password reset successful');</p>
<p class="p1"><span class="Apple-converted-space">    </span>close('#forgotModal');</p>
<p class="p1"><span class="Apple-converted-space">    </span>open('#loginModal');</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function afterLogin(u){</p>
<p class="p1"><span class="Apple-converted-space">    </span>currentUser = u;</p>
<p class="p1"><span class="Apple-converted-space">    </span>setSession(u.ref);</p>
<p class="p1"><span class="Apple-converted-space">    </span>close('#loginModal');</p>
<p class="p1"><span class="Apple-converted-space">    </span>showDashboard();</p>
<p class="p1"><span class="Apple-converted-space">    </span>toast('Welcome back, '+(u.name||'Investor'));</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function showDashboard(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#landingView').classList.add('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#dashboardView').classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#dashUserName').textContent = currentUser.name || 'Investor';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#dashUserRef').textContent = 'Ref: '+currentUser.ref;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#dashWelcomeName').textContent = currentUser.name?.split(' ')[0] || 'Investor';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#profileName').value = currentUser.name||'';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#profilePan').value = currentUser.pan||'';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#profileMobile').value = currentUser.mobile||'';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#profileEmail').value = currentUser.email||'';</p>
<p class="p1"><span class="Apple-converted-space">    </span>update2FAUI();</p>
<p class="p1"><span class="Apple-converted-space">    </span>$(`input[name="otpMethod"][value="${currentUser.otpMethod||'sms'}"]`).checked = true;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#holdingsList').innerHTML = funds.slice(0,4).map(f=&gt;`</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="py-4 flex items-center justify-between"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="font-medium text-slate-900"&gt;${f.scheme_name}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="text-xs text-slate-500"&gt;${f.category}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="text-right"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="font-semibold text-slate-900"&gt;₹${(Math.random()*50000+10000).toFixed(0)}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="text-xs text-emerald-600"&gt;+${(Math.random()*15+2).toFixed(1)}%&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>`).join('');</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#txList').innerHTML = Array.from({length:5}).map((_,i)=&gt;`</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="flex items-center justify-between p-3 rounded-2xl bg-slate-50 border border-slate-200"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="text-sm text-slate-700"&gt;${['Purchase','SIP','Redemption'][i%3]} • ${funds[i]?.scheme_name?.slice(0,28)||'Fund'}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="text-sm font-medium text-slate-900"&gt;₹${(Math.random()*10000+1000).toFixed(0)}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>`).join('');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const openCount = tickets.filter(t=&gt;t.userRef===currentUser.ref &amp;&amp; t.status!=='Resolved').length;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const el = $('#dashOpenTickets'); if(el) el.textContent = openCount;</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function showLanding(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#dashboardView').classList.add('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#landingView').classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#logoutBtn').onclick = ()=&gt; { clearSession(); currentUser=null; showLanding(); toast('Logged out'); };</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$$('.dash-tab').forEach(b=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">    </span>b.onclick = ()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>$$('.dash-tab').forEach(x=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">        </span>x.classList.remove('bg-slate-900','text-white','active');</p>
<p class="p1"><span class="Apple-converted-space">        </span>x.classList.add('text-slate-600');</p>
<p class="p1"><span class="Apple-converted-space">      </span>});</p>
<p class="p1"><span class="Apple-converted-space">      </span>b.classList.add('bg-slate-900','text-white','active');</p>
<p class="p1"><span class="Apple-converted-space">      </span>b.classList.remove('text-slate-600');</p>
<p class="p1"><span class="Apple-converted-space">      </span>$$('#tab-overview,#tab-holdings,#tab-transactions,#tab-profile,#tab-support').forEach(p=&gt;p.classList.add('hidden'));</p>
<p class="p1"><span class="Apple-converted-space">      </span>$('#tab-'+b.dataset.tab).classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">      </span>if(b.dataset.tab==='support'){</p>
<p class="p1"><span class="Apple-converted-space">        </span>const openCount = tickets.filter(t=&gt;t.userRef===(currentUser?.ref||'GUEST') &amp;&amp; t.status!=='Resolved').length;</p>
<p class="p1"><span class="Apple-converted-space">        </span>$('#dashOpenTickets').textContent = openCount;</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>};</p>
<p class="p1"><span class="Apple-converted-space">  </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>const toggle2FA = $('#toggle2FA');</p>
<p class="p1"><span class="Apple-converted-space">  </span>function update2FAUI(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const on = !!currentUser?.twoFA;</p>
<p class="p1"><span class="Apple-converted-space">    </span>toggle2FA.classList.toggle('bg-[#3B82F6]', on);</p>
<p class="p1"><span class="Apple-converted-space">    </span>toggle2FA.classList.toggle('bg-slate-200', !on);</p>
<p class="p1"><span class="Apple-converted-space">    </span>toggle2FA.querySelector('span').style.transform = on ? 'translateX(22px)' : 'translateX(0)';</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>toggle2FA.onclick = ()=&gt; { currentUser.twoFA=!currentUser.twoFA; update2FAUI(); };</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#saveProfileBtn').onclick = ()=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const inputs = [$('#profileName'), $('#profilePan'), $('#profileMobile'), $('#profileEmail')];</p>
<p class="p1"><span class="Apple-converted-space">    </span>const allValid = inputs.every(i =&gt; !i.value || validateInput(i));</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!allValid) return toast('Please fix invalid fields','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>currentUser.name = $('#profileName').value;</p>
<p class="p1"><span class="Apple-converted-space">    </span>currentUser.pan = $('#profilePan').value.toUpperCase();</p>
<p class="p1"><span class="Apple-converted-space">    </span>currentUser.mobile = $('#profileMobile').value;</p>
<p class="p1"><span class="Apple-converted-space">    </span>currentUser.email = $('#profileEmail').value;</p>
<p class="p1"><span class="Apple-converted-space">    </span>currentUser.otpMethod = document.querySelector('input[name="otpMethod"]:checked')?.value || 'sms';</p>
<p class="p1"><span class="Apple-converted-space">    </span>saveUsers();</p>
<p class="p1"><span class="Apple-converted-space">    </span>toast('Profile saved');</p>
<p class="p1"><span class="Apple-converted-space">    </span>showDashboard();</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#fillDemoProfile').onclick = ()=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#profileName').value='Aarav Sharma';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#profilePan').value='ABCDE1234F';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#profileMobile').value='9876543210';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#profileEmail').value='aarav@example.com';</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#dashResendWelcome').onclick = ()=&gt; toast('Welcome email sent to '+ (currentUser.email||'your inbox'));</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#dashSupportBtn').onclick = ()=&gt; openSupportCenter();</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>const steps = [</p>
<p class="p1"><span class="Apple-converted-space">    </span>{title:'Personal Details', desc:'Basic info'},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{title:'KYC Verification', desc:'Aadhaar eKYC'},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{title:'Bank Details', desc:'Payout account'},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{title:'Nominee', desc:'Optional'},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{title:'Create Password', desc:'Secure access'},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{title:'Review &amp; Submit', desc:'Confirm'}</p>
<p class="p1"><span class="Apple-converted-space">  </span>];</p>
<p class="p1"><span class="Apple-converted-space">  </span>let stepIdx=0, kycDone=false;</p>
<p class="p1"><span class="Apple-converted-space">  </span>function startOnboard(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>stepIdx=0; kycDone=false;</p>
<p class="p1"><span class="Apple-converted-space">    </span>open('#onboardWizard');</p>
<p class="p1"><span class="Apple-converted-space">    </span>renderRail();</p>
<p class="p1"><span class="Apple-converted-space">    </span>showStep();</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>function renderRail(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#stepRail').innerHTML = steps.map((s,i)=&gt;`</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;li class="flex gap-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="w-8 h-8 rounded-2xl border flex items-center justify-center text-sm ${i===stepIdx?'step-active border-transparent': i&lt;stepIdx?'step-done border-[#3B82F6]':'border-slate-300 text-slate-500'}"&gt;${i&lt;stepIdx?'✓':i+1}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div&gt;&lt;div class="text-sm font-medium ${i===stepIdx?'text-slate-900':'text-slate-700'}"&gt;${s.title}&lt;/div&gt;&lt;div class="text-xs text-slate-500"&gt;${s.desc}&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/li&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>`).join('');</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>function showStep(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>$$('.step-pane').forEach(p=&gt;p.classList.add('hidden'));</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#step-'+(stepIdx+1)).classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#stepNow').textContent = stepIdx+1;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#stepTitle').textContent = steps[stepIdx].title;</p>
<p class="p1"><span class="Apple-converted-space">    </span>renderRail();</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#stepPrev').classList.toggle('invisible', stepIdx===0);</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#stepNext').textContent = stepIdx===steps.length-1?'Create Account':'Continue';</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#stepPrev').onclick = ()=&gt; { if(stepIdx&gt;0){ stepIdx--; showStep(); } };</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#stepNext').onclick = ()=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(stepIdx===0){</p>
<p class="p1"><span class="Apple-converted-space">      </span>const name = $('#obName'), pan = $('#obPan'), mobile = $('#obMobile'), email = $('#obEmail');</p>
<p class="p1"><span class="Apple-converted-space">      </span>if(!name.value || !pan.value || !mobile.value || !email.value){</p>
<p class="p1"><span class="Apple-converted-space">        </span>[name,pan,mobile,email].forEach(i=&gt;{if(!i.value) i.classList.add('invalid');});</p>
<p class="p1"><span class="Apple-converted-space">        </span>return toast('Fill required fields','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>if(![name,pan,mobile,email].every(validateInput)) return toast('Please fix invalid fields','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(stepIdx===1 &amp;&amp; !kycDone) return toast('Complete KYC','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(stepIdx===4){</p>
<p class="p1"><span class="Apple-converted-space">      </span>const p1=$('#obPass').value, p2=$('#obPass2').value;</p>
<p class="p1"><span class="Apple-converted-space">      </span>if(p1.length&lt;8 || p1!==p2) return toast('Password mismatch or weak','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(stepIdx===5){</p>
<p class="p1"><span class="Apple-converted-space">      </span>if(!$('#obAgree').checked) return toast('Accept terms','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">      </span>const ref = genRef();</p>
<p class="p1"><span class="Apple-converted-space">      </span>const user = {</p>
<p class="p1"><span class="Apple-converted-space">        </span>ref,</p>
<p class="p1"><span class="Apple-converted-space">        </span>name: $('#obName').value,</p>
<p class="p1"><span class="Apple-converted-space">        </span>pan: $('#obPan').value.toUpperCase(),</p>
<p class="p1"><span class="Apple-converted-space">        </span>mobile: $('#obMobile').value,</p>
<p class="p1"><span class="Apple-converted-space">        </span>email: $('#obEmail').value,</p>
<p class="p1"><span class="Apple-converted-space">        </span>dob: $('#obDob').value,</p>
<p class="p1"><span class="Apple-converted-space">        </span>password: $('#obPass').value,</p>
<p class="p1"><span class="Apple-converted-space">        </span>bank: { acc: $('#obBankAcc').value, ifsc: $('#obIfsc').value, name: $('#obBankName').value },</p>
<p class="p1"><span class="Apple-converted-space">        </span>nominee: { name: $('#obNominee').value, rel: $('#obNomRel').value },</p>
<p class="p1"><span class="Apple-converted-space">        </span>twoFA:false, otpMethod:'sms', created: new Date().toISOString()</p>
<p class="p1"><span class="Apple-converted-space">      </span>};</p>
<p class="p1"><span class="Apple-converted-space">      </span>users.push(user); saveUsers();</p>
<p class="p1"><span class="Apple-converted-space">      </span>close('#onboardWizard');</p>
<p class="p1"><span class="Apple-converted-space">      </span>currentUser=user; setSession(ref);</p>
<p class="p1"><span class="Apple-converted-space">      </span>showDashboard();</p>
<p class="p1"><span class="Apple-converted-space">      </span>toast('Account created! Ref: '+ref+' 🎉');</p>
<p class="p1"><span class="Apple-converted-space">      </span>return;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>stepIdx++; showStep();</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#fillDemoBtn').onclick = fillDemo;</p>
<p class="p1"><span class="Apple-converted-space">  </span>function fillDemo(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obName').value='Aarav Sharma';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obPan').value='ABCDE1234F';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obMobile').value='9876543210';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obEmail').value='aarav@example.com';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obDob').value='1995-06-15';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obOcc').value='Salaried';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obBankAcc').value='123456789012';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obIfsc').value='HDFC0001234';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obBankName').value='Aarav Sharma';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obNominee').value='Meera Sharma';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obNomRel').value='Spouse';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obPass').value='Demo@1234';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obPass2').value='Demo@1234';</p>
<p class="p1"><span class="Apple-converted-space">    </span>toast('Demo data filled');</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#obSendAadhaarOtp').onclick = ()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">    </span>if($('#obAadhaar').value.replace(/\s/g,'').length&lt;12) return toast('Enter valid Aadhaar','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obAadhaarOtpBox').classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>toast('OTP sent: 123456');</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#obVerifyAadhaar').onclick = ()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">    </span>if($('#obAadhaarOtp').value!=='123456') return toast('Invalid OTP','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>kycDone=true;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#obKycStatus').classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>toast('KYC verified');</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>async function loadFunds(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>try{</p>
<p class="p1"><span class="Apple-converted-space">      </span>const list = await getInvescoSchemes();</p>
<p class="p1"><span class="Apple-converted-space">      </span>// Get all unique schemes, filter to growth/direct plans to avoid duplicates</p>
<p class="p1"><span class="Apple-converted-space">      </span>const unique = [];</p>
<p class="p1"><span class="Apple-converted-space">      </span>const seen = new Set();</p>
<p class="p1"><span class="Apple-converted-space">      </span>for(const item of list){</p>
<p class="p1"><span class="Apple-converted-space">        </span>const base = item.schemeName.replace(/\s*-\s*(Direct|Regular)\s*Plan.*$/i, '').replace(/\s*\(.*\)/, '').trim();</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(!seen.has(base) &amp;&amp; item.schemeName.toLowerCase().includes('growth')){</p>
<p class="p1"><span class="Apple-converted-space">          </span>seen.add(base);</p>
<p class="p1"><span class="Apple-converted-space">          </span>unique.push(item);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(unique.length &gt;= 45) break;</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>const schemes = unique.length &gt; 20 ? unique : list.slice(0,45);</p>
<p class="p2"><span class="Apple-converted-space">      </span></p>
<p class="p1"><span class="Apple-converted-space">      </span>const data = await Promise.all(schemes.map(async item=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">        </span>try{</p>
<p class="p1"><span class="Apple-converted-space">          </span>const r = await fetch(`https://api.mfapi.in/mf/${item.schemeCode}`);</p>
<p class="p1"><span class="Apple-converted-space">          </span>const j = await r.json();</p>
<p class="p1"><span class="Apple-converted-space">          </span>const navs = j.data || [];</p>
<p class="p1"><span class="Apple-converted-space">          </span>if(!navs.length) return null;</p>
<p class="p1"><span class="Apple-converted-space">          </span>const latest = navs[0];</p>
<p class="p1"><span class="Apple-converted-space">          </span>const returns = calculateReturns(navs);</p>
<p class="p2"><span class="Apple-converted-space">          </span></p>
<p class="p1"><span class="Apple-converted-space">          </span>return {</p>
<p class="p1"><span class="Apple-converted-space">            </span>scheme_code: item.schemeCode,</p>
<p class="p1"><span class="Apple-converted-space">            </span>scheme_name: j.meta.scheme_name,</p>
<p class="p1"><span class="Apple-converted-space">            </span>category: categorize(j.meta.scheme_name),</p>
<p class="p1"><span class="Apple-converted-space">            </span>nav: parseFloat(latest.nav).toFixed(2),</p>
<p class="p1"><span class="Apple-converted-space">            </span>nav_date: fmtDate(latest.date),</p>
<p class="p1"><span class="Apple-converted-space">            </span>nav_history: navs,</p>
<p class="p1"><span class="Apple-converted-space">            </span>returns_1y: returns.y1,</p>
<p class="p1"><span class="Apple-converted-space">            </span>returns_3y: returns.y3 * 100,</p>
<p class="p1"><span class="Apple-converted-space">            </span>returns_5y: returns.y5 * 100,</p>
<p class="p1"><span class="Apple-converted-space">            </span>aum: '₹'+(Math.random()*8000+500).toFixed(0)+' Cr',</p>
<p class="p1"><span class="Apple-converted-space">            </span>expense: (Math.random()*0.8+0.3).toFixed(2)+'%',</p>
<p class="p1"><span class="Apple-converted-space">            </span>manager: j.meta.fund_house || 'Invesco Team',</p>
<p class="p1"><span class="Apple-converted-space">            </span>inception: j.meta.scheme_start_date || '2010',</p>
<p class="p1"><span class="Apple-converted-space">            </span>rating: (Math.random()*0.8+4.0).toFixed(1),</p>
<p class="p1"><span class="Apple-converted-space">            </span>type: j.meta.scheme_type || '',</p>
<p class="p1"><span class="Apple-converted-space">            </span>category_meta: j.meta.scheme_category || ''</p>
<p class="p1"><span class="Apple-converted-space">          </span>};</p>
<p class="p1"><span class="Apple-converted-space">        </span>}catch(e){ return null; }</p>
<p class="p1"><span class="Apple-converted-space">      </span>}));</p>
<p class="p1"><span class="Apple-converted-space">      </span>funds = data.filter(Boolean);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}catch(e){</p>
<p class="p1"><span class="Apple-converted-space">      </span>console.error(e);</p>
<p class="p1"><span class="Apple-converted-space">      </span>// Fallback to sample data</p>
<p class="p1"><span class="Apple-converted-space">      </span>funds = Array.from({length:45}).map((_,i)=&gt;({</p>
<p class="p1"><span class="Apple-converted-space">        </span>scheme_code: 100000+i,</p>
<p class="p1"><span class="Apple-converted-space">        </span>scheme_name: ['Invesco India Large Cap Fund','Invesco India Midcap Fund','Invesco India ELSS Tax Saver Fund','Invesco India Contra Fund','Invesco India Growth Opportunities Fund','Invesco India Focused 20 Fund','Invesco India Flexi Cap Fund','Invesco India PSU Equity Fund','Invesco India Financial Services Fund','Invesco India Technology Fund'][i%10] + ` - Growth`,</p>
<p class="p1"><span class="Apple-converted-space">        </span>category: ['Equity','Equity','ELSS','Equity','Equity','Hybrid','Debt','Index','Solution Oriented','Other'][i%10],</p>
<p class="p1"><span class="Apple-converted-space">        </span>nav: (Math.random()*120+20).toFixed(2),</p>
<p class="p1"><span class="Apple-converted-space">        </span>nav_date: fmtDate('10-11-2024'),</p>
<p class="p1"><span class="Apple-converted-space">        </span>nav_history: Array.from({length:1825},(_,d)=&gt;({date:`${d}-01-2020`,nav:50+Math.random()*30})),</p>
<p class="p1"><span class="Apple-converted-space">        </span>returns_1y: Math.random()*25+5,</p>
<p class="p1"><span class="Apple-converted-space">        </span>returns_3y: Math.random()*15+8,</p>
<p class="p1"><span class="Apple-converted-space">        </span>returns_5y: Math.random()*12+10,</p>
<p class="p1"><span class="Apple-converted-space">        </span>aum: '₹'+(Math.random()*5000+500).toFixed(0)+' Cr',</p>
<p class="p1"><span class="Apple-converted-space">        </span>expense: (Math.random()*1+0.5).toFixed(2)+'%',</p>
<p class="p1"><span class="Apple-converted-space">        </span>manager: 'Taher Badshah',</p>
<p class="p1"><span class="Apple-converted-space">        </span>inception: '2008',</p>
<p class="p1"><span class="Apple-converted-space">        </span>rating: (Math.random()*1+3.8).toFixed(1),</p>
<p class="p1"><span class="Apple-converted-space">        </span>type: '',</p>
<p class="p1"><span class="Apple-converted-space">        </span>category_meta: ''</p>
<p class="p1"><span class="Apple-converted-space">      </span>}));</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>renderFunds();</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fundLoading').classList.add('hidden');</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function categorize(name){</p>
<p class="p1"><span class="Apple-converted-space">    </span>name=name.toLowerCase();</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(name.includes('elss') || name.includes('tax')) return 'ELSS';</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(name.includes('liquid')||name.includes('overnight')||name.includes('ultra short')||name.includes('short term')||name.includes('corporate bond')||name.includes('gilt')||name.includes('banking')||name.includes('psu bond')||name.includes('money market')) return 'Debt';</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(name.includes('hybrid')||name.includes('balanced')||name.includes('equity savings')||name.includes('arbitrage')) return 'Hybrid';</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(name.includes('index')||name.includes('nifty')||name.includes('sensex')||name.includes('etf')) return 'Index';</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(name.includes('retirement')||name.includes('children')||name.includes('solution')) return 'Solution Oriented';</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(name.includes('gold')||name.includes('silver')||name.includes('commodities')) return 'Other';</p>
<p class="p1"><span class="Apple-converted-space">    </span>return 'Equity';</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function renderFunds(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const q = ($('#fundSearch').value||'').toLowerCase();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const cat = $('#categoryFilter').value;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const filtered = funds.filter(f=&gt; (!q || f.scheme_name.toLowerCase().includes(q)) &amp;&amp; (!cat || f.category===cat));</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fundGrid').innerHTML = filtered.map(f=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>const color = f.category==='Equity'?'#3B82F6': f.category==='Debt'?'#06B6D4': f.category==='Hybrid'?'#8B5CF6': f.category==='ELSS'?'#F59E0B': f.category==='Index'?'#10B981':'#64748B';</p>
<p class="p1"><span class="Apple-converted-space">      </span>const r1 = f.returns_1y || 0, r3 = f.returns_3y || 0, r5 = f.returns_5y || 0;</p>
<p class="p1"><span class="Apple-converted-space">      </span>return `</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="group glass rounded-[1.6rem] overflow-hidden hover:border-slate-300 transition border border-slate-200 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="h-1 w-full" style="background:${color}"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="p-5"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="flex items-start justify-between gap-3 mb-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-[11px] pill px-2 py-0.5 rounded-full"&gt;${f.category}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-amber-500 text-[11px]"&gt;★ ${f.rating}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;h4 class="font-semibold leading-snug line-clamp-2 min-h-[40px] text-[14px] text-slate-900"&gt;${f.scheme_name.replace('Invesco India ','')}&lt;/h4&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="mt-3 flex items-baseline justify-between"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[11px] text-slate-500"&gt;NAV&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-xl font-bold text-slate-900"&gt;₹${f.nav}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-right"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[10px] text-slate-500"&gt;as on&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[11px] font-medium text-slate-700"&gt;${f.nav_date}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="mt-3 grid grid-cols-3 gap-2 pt-3 border-t border-slate-100"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-center"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[10px] text-slate-500"&gt;1Y&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[13px] font-semibold ${r1&gt;=0?'text-emerald-600':'text-red-600'}"&gt;${r1&gt;=0?'+':''}${r1.toFixed(1)}%&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-center"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[10px] text-slate-500"&gt;3Y&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[13px] font-semibold ${r3&gt;=0?'text-emerald-600':'text-red-600'}"&gt;${r3&gt;=0?'+':''}${r3.toFixed(1)}%&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="text-center"&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[10px] text-slate-500"&gt;5Y&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="text-[13px] font-semibold ${r5&gt;=0?'text-emerald-600':'text-red-600'}"&gt;${r5&gt;=0?'+':''}${r5.toFixed(1)}%&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="mt-4 flex gap-2"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button data-fund="${f.scheme_code}" class="view-fund flex-1 h-9 rounded-xl bg-slate-100 hover:bg-slate-200 text-[13px] font-medium btn-secondary ripple-container"&gt;Details&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button class="h-9 px-3 rounded-xl bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] text-[13px] font-semibold btn-primary ripple-container text-white"&gt;Invest&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}).join('') || `&lt;div class="col-span-full text-center text-slate-500 py-16"&gt;No funds found&lt;/div&gt;`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$$('.view-fund').forEach(b=&gt; b.onclick = ()=&gt; openFundDetail(b.dataset.fund));</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#fundSearch').oninput = renderFunds;</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#categoryFilter').onchange = renderFunds;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>let fundChart = null;</p>
<p class="p1"><span class="Apple-converted-space">  </span>let currentFundData = null;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function openFundDetail(code){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const f = funds.find(x=&gt;x.scheme_code==code);</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!f) return;</p>
<p class="p1"><span class="Apple-converted-space">    </span>currentFundData = f;</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdName').textContent = f.scheme_name;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdCategory').textContent = f.category;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdNav').textContent = '₹'+f.nav;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdNavDate').textContent = 'as on '+f.nav_date;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdAum').textContent = f.aum;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdExp').textContent = f.expense;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdMgr').textContent = f.manager;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdInception').textContent = f.inception;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdMeta').textContent = `Scheme Code ${f.scheme_code} • ${f.type || f.category}`;</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>// Riskometer</p>
<p class="p1"><span class="Apple-converted-space">    </span>const riskLevels = { 'Equity':75, 'ELSS':75, 'Hybrid':55, 'Debt':30, 'Index':65, 'Solution Oriented':50, 'Other':40 };</p>
<p class="p1"><span class="Apple-converted-space">    </span>const risk = riskLevels[f.category] || 50;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const offset = 188 - (188 * risk / 100);</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#riskArc').setAttribute('stroke-dashoffset', offset);</p>
<p class="p1"><span class="Apple-converted-space">    </span>const angle = (risk/100)*Math.PI;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const cx = 70 + 60 * Math.cos(Math.PI - angle);</p>
<p class="p1"><span class="Apple-converted-space">    </span>const cy = 15 + 60 * Math.sin(Math.PI - angle);</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#riskDot').setAttribute('cx', cx);</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#riskDot').setAttribute('cy', cy);</p>
<p class="p1"><span class="Apple-converted-space">    </span>const labels = risk&lt;25?'Low':risk&lt;45?'Low to Moderate':risk&lt;65?'Moderate':risk&lt;80?'Moderately High':'High';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdRiskLabel').textContent = labels;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdRiskLabel').className = `text-xs font-medium mt-1 px-2.5 py-1 rounded-full ${risk&lt;45?'bg-emerald-500/10 text-emerald-700':risk&lt;65?'bg-amber-500/10 text-amber-700':'bg-red-500/10 text-red-700'}`;</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>// Performance table</p>
<p class="p1"><span class="Apple-converted-space">    </span>const perf = [</p>
<p class="p1"><span class="Apple-converted-space">      </span>{p:'1M', f: (Math.random()*3).toFixed(1), c: (Math.random()*2.5).toFixed(1), b: (Math.random()*2.8).toFixed(1)},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{p:'3M', f: (Math.random()*6+2).toFixed(1), c: (Math.random()*5+1.5).toFixed(1), b: (Math.random()*5.5+1.8).toFixed(1)},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{p:'6M', f: (Math.random()*10+3).toFixed(1), c: (Math.random()*8+2).toFixed(1), b: (Math.random()*9+2.5).toFixed(1)},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{p:'1Y', f: f.returns_1y.toFixed(1), c: (f.returns_1y-1.5).toFixed(1), b: (f.returns_1y-0.8).toFixed(1)},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{p:'3Y', f: f.returns_3y.toFixed(1), c: (f.returns_3y-1.2).toFixed(1), b: (f.returns_3y-0.5).toFixed(1)},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{p:'5Y', f: f.returns_5y.toFixed(1), c: (f.returns_5y-1).toFixed(1), b: (f.returns_5y-0.3).toFixed(1)},</p>
<p class="p1"><span class="Apple-converted-space">    </span>];</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#fdPerfTable').innerHTML = perf.map(row=&gt;`</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;tr&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;td class="py-2.5 text-slate-700"&gt;${row.p}&lt;/td&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;td class="py-2.5 text-right font-medium text-slate-900"&gt;${row.f}%&lt;/td&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;td class="py-2.5 text-right text-slate-600"&gt;${row.c}%&lt;/td&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;td class="py-2.5 text-right text-slate-600"&gt;${row.b}%&lt;/td&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/tr&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>`).join('');</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>// Chart</p>
<p class="p1"><span class="Apple-converted-space">    </span>setTimeout(()=&gt; updateFundChart('1M'), 100);</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>$$('.period-btn').forEach(btn=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>btn.onclick = ()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">        </span>$$('.period-btn').forEach(b=&gt;{ b.classList.remove('bg-slate-900','text-white'); b.classList.add('hover:bg-slate-100'); });</p>
<p class="p1"><span class="Apple-converted-space">        </span>btn.classList.add('bg-slate-900','text-white');</p>
<p class="p1"><span class="Apple-converted-space">        </span>btn.classList.remove('hover:bg-slate-100');</p>
<p class="p1"><span class="Apple-converted-space">        </span>updateFundChart(btn.dataset.period);</p>
<p class="p1"><span class="Apple-converted-space">      </span>};</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>open('#fundDetailModal');</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function updateFundChart(period){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const f = currentFundData;</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!f || !f.nav_history) return;</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>const canvas = document.getElementById('fdChart');</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(fundChart) fundChart.destroy();</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>const data = f.nav_history;</p>
<p class="p1"><span class="Apple-converted-space">    </span>let days = 30;</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(period==='3M') days=90;</p>
<p class="p1"><span class="Apple-converted-space">    </span>else if(period==='6M') days=180;</p>
<p class="p1"><span class="Apple-converted-space">    </span>else if(period==='1Y') days=365;</p>
<p class="p1"><span class="Apple-converted-space">    </span>else if(period==='3Y') days=1095;</p>
<p class="p1"><span class="Apple-converted-space">    </span>else if(period==='5Y') days=1825;</p>
<p class="p1"><span class="Apple-converted-space">    </span>else if(period==='MAX') days=data.length;</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>const sliced = data.slice(0, Math.min(days, data.length)).reverse();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const labels = sliced.map(d=&gt; {</p>
<p class="p1"><span class="Apple-converted-space">      </span>const dt = parseMFDate(d.date);</p>
<p class="p1"><span class="Apple-converted-space">      </span>return dt.toLocaleDateString('en-GB',{month:'short',year:'2-digit'});</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1"><span class="Apple-converted-space">    </span>const values = sliced.map(d=&gt; parseFloat(d.nav));</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>const ctx = canvas.getContext('2d');</p>
<p class="p1"><span class="Apple-converted-space">    </span>fundChart = new Chart(ctx, {</p>
<p class="p1"><span class="Apple-converted-space">      </span>type: 'line',</p>
<p class="p1"><span class="Apple-converted-space">      </span>data: {</p>
<p class="p1"><span class="Apple-converted-space">        </span>labels: labels,</p>
<p class="p1"><span class="Apple-converted-space">        </span>datasets: [{</p>
<p class="p1"><span class="Apple-converted-space">          </span>label: 'NAV',</p>
<p class="p1"><span class="Apple-converted-space">          </span>data: values,</p>
<p class="p1"><span class="Apple-converted-space">          </span>borderColor: '#3B82F6',</p>
<p class="p1"><span class="Apple-converted-space">          </span>backgroundColor: 'rgba(59,130,246,0.1)',</p>
<p class="p1"><span class="Apple-converted-space">          </span>borderWidth: 2.5,</p>
<p class="p1"><span class="Apple-converted-space">          </span>fill: true,</p>
<p class="p1"><span class="Apple-converted-space">          </span>tension: 0.4,</p>
<p class="p1"><span class="Apple-converted-space">          </span>pointRadius: 0,</p>
<p class="p1"><span class="Apple-converted-space">          </span>pointHoverRadius: 5,</p>
<p class="p1"><span class="Apple-converted-space">          </span>pointHoverBackgroundColor: '#3B82F6'</p>
<p class="p1"><span class="Apple-converted-space">        </span>}]</p>
<p class="p1"><span class="Apple-converted-space">      </span>},</p>
<p class="p1"><span class="Apple-converted-space">      </span>options: {</p>
<p class="p1"><span class="Apple-converted-space">        </span>responsive: true,</p>
<p class="p1"><span class="Apple-converted-space">        </span>maintainAspectRatio: false,</p>
<p class="p1"><span class="Apple-converted-space">        </span>plugins: {</p>
<p class="p1"><span class="Apple-converted-space">          </span>legend: { display: false },</p>
<p class="p1"><span class="Apple-converted-space">          </span>tooltip: {</p>
<p class="p1"><span class="Apple-converted-space">            </span>backgroundColor: 'rgba(15,23,42,0.9)',</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 10,</p>
<p class="p1"><span class="Apple-converted-space">            </span>titleFont: { size: 12 },</p>
<p class="p1"><span class="Apple-converted-space">            </span>bodyFont: { size: 13 },</p>
<p class="p1"><span class="Apple-converted-space">            </span>displayColors: false,</p>
<p class="p1"><span class="Apple-converted-space">            </span>callbacks: {</p>
<p class="p1"><span class="Apple-converted-space">              </span>label: (ctx) =&gt; `NAV: ₹${ctx.parsed.y.toFixed(2)}`</p>
<p class="p1"><span class="Apple-converted-space">            </span>}</p>
<p class="p1"><span class="Apple-converted-space">          </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>},</p>
<p class="p1"><span class="Apple-converted-space">        </span>scales: {</p>
<p class="p1"><span class="Apple-converted-space">          </span>x: {<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>grid: { display: false },</p>
<p class="p1"><span class="Apple-converted-space">            </span>ticks: { font: { size: 10 }, color: '#64748B', maxTicksLimit: 6 }</p>
<p class="p1"><span class="Apple-converted-space">          </span>},</p>
<p class="p1"><span class="Apple-converted-space">          </span>y: {<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">            </span>grid: { color: '#F1F5F9' },</p>
<p class="p1"><span class="Apple-converted-space">            </span>ticks: { font: { size: 11 }, color: '#64748B' },</p>
<p class="p1"><span class="Apple-converted-space">            </span>beginAtZero: false</p>
<p class="p1"><span class="Apple-converted-space">          </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>},</p>
<p class="p1"><span class="Apple-converted-space">        </span>interaction: { intersect: false, mode: 'index' }</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function genRef(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>return 'INV-'+Math.random().toString(36).substring(2,6).toUpperCase()+'-'+Math.random().toString(36).substring(2,6).toUpperCase();</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>const sess = localStorage.getItem(SESSION_KEY);</p>
<p class="p1"><span class="Apple-converted-space">  </span>if(sess){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const u = users.find(x=&gt;x.ref===sess);</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(u){ currentUser=u; showDashboard(); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$$('#loginModal,#forgotModal,#fundDetailModal,#supportCenter,#ticketThreadModal,#videoPlayerModal').forEach(m=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">    </span>m.addEventListener('click', e=&gt; {<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">      </span>if(e.target===m.querySelector('.modal-overlay')) close('#'+m.id);<span class="Apple-converted-space"> </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1"><span class="Apple-converted-space">  </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#changePasswordBtn').onclick = ()=&gt; toast('Password change email sent');</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>loadFunds();</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>const observer = new MutationObserver(()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">    </span>if($('#step-6') &amp;&amp; !$('#step-6').classList.contains('hidden')){</p>
<p class="p1"><span class="Apple-converted-space">      </span>$('#obReview').innerHTML = `</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div&gt;&lt;span class="text-slate-500"&gt;Name:&lt;/span&gt; ${$('#obName').value}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div&gt;&lt;span class="text-slate-500"&gt;PAN:&lt;/span&gt; ${$('#obPan').value}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div&gt;&lt;span class="text-slate-500"&gt;Mobile:&lt;/span&gt; ${$('#obMobile').value}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div&gt;&lt;span class="text-slate-500"&gt;Email:&lt;/span&gt; ${$('#obEmail').value}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div&gt;&lt;span class="text-slate-500"&gt;Bank:&lt;/span&gt; ${$('#obBankAcc').value}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div&gt;&lt;span class="text-slate-500"&gt;Nominee:&lt;/span&gt; ${$('#obNominee').value}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>});</p>
<p class="p1"><span class="Apple-converted-space">  </span>observer.observe(document.body,{subtree:true,attributes:true});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>// === SUPPORT CENTER ===</p>
<p class="p1"><span class="Apple-converted-space">  </span>const TICKETS_KEY = 'invesco_tickets_v1';</p>
<p class="p1"><span class="Apple-converted-space">  </span>let tickets = JSON.parse(localStorage.getItem(TICKETS_KEY) || '[]');</p>
<p class="p1"><span class="Apple-converted-space">  </span>const saveTickets = ()=&gt; localStorage.setItem(TICKETS_KEY, JSON.stringify(tickets));</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function openSupportCenter(tab='contact'){</p>
<p class="p1"><span class="Apple-converted-space">    </span>open('#supportCenter');</p>
<p class="p1"><span class="Apple-converted-space">    </span>switchSupportTab(tab);</p>
<p class="p1"><span class="Apple-converted-space">    </span>renderFAQs();</p>
<p class="p1"><span class="Apple-converted-space">    </span>renderMyTickets();</p>
<p class="p1"><span class="Apple-converted-space">    </span>renderTutorials();</p>
<p class="p1"><span class="Apple-converted-space">    </span>renderBranches();</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>window.openSupportCenter = openSupportCenter;</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#mobileSupportLink')?.addEventListener('click', e=&gt;{e.preventDefault(); $('#mobileMenu').classList.add('hidden'); $('#mobileMenu').classList.remove('open'); openSupportCenter();});</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#floatingHelp').onclick = ()=&gt; openSupportCenter();</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function switchSupportTab(tab){</p>
<p class="p1"><span class="Apple-converted-space">    </span>$$('.support-tab').forEach(b=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>const active = b.dataset.supportTab===tab;</p>
<p class="p1"><span class="Apple-converted-space">      </span>b.classList.toggle('bg-slate-900', active);</p>
<p class="p1"><span class="Apple-converted-space">      </span>b.classList.toggle('text-white', active);</p>
<p class="p1"><span class="Apple-converted-space">      </span>b.classList.toggle('text-slate-600', !active);</p>
<p class="p1"><span class="Apple-converted-space">      </span>b.classList.toggle('bg-white', !active);</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1"><span class="Apple-converted-space">    </span>$$('.support-pane').forEach(p=&gt;p.classList.add('hidden'));</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#support-'+tab)?.classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>$$('.support-tab').forEach(b=&gt; b.onclick = ()=&gt; switchSupportTab(b.dataset.supportTab));</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>// === AI CHAT ASSISTANT ===</p>
<p class="p1"><span class="Apple-converted-space">  </span>let chatInitialized = false;</p>
<p class="p1"><span class="Apple-converted-space">  </span>let chatHistory = [];</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function openLiveChat(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const widget = $('#liveChatWidget');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const panel = $('#liveChatPanel');</p>
<p class="p1"><span class="Apple-converted-space">    </span>widget.classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>setTimeout(()=&gt; panel.classList.remove('translate-x-full'), 20);</p>
<p class="p1"><span class="Apple-converted-space">    </span>document.body.style.overflow = 'hidden';</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!chatInitialized){ initChat(); chatInitialized = true; }</p>
<p class="p1"><span class="Apple-converted-space">    </span>setTimeout(()=&gt; $('#chatInput')?.focus(), 300);</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>function closeLiveChat(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const panel = $('#liveChatPanel');</p>
<p class="p1"><span class="Apple-converted-space">    </span>panel.classList.add('translate-x-full');</p>
<p class="p1"><span class="Apple-converted-space">    </span>setTimeout(()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>$('#liveChatWidget').classList.add('hidden');</p>
<p class="p1"><span class="Apple-converted-space">      </span>document.body.style.overflow = '';</p>
<p class="p1"><span class="Apple-converted-space">    </span>}, 300);</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#startLiveChatBtn').onclick = openLiveChat;</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#supportLiveChatQuick').onclick = openLiveChat;</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#floatingHelp').onclick = openLiveChat;</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#chatClose').onclick = closeLiveChat;</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#chatBackdrop')?.addEventListener('click', closeLiveChat);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function initChat(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const messages = $('#chatMessages');</p>
<p class="p1"><span class="Apple-converted-space">    </span>messages.innerHTML = '';</p>
<p class="p1"><span class="Apple-converted-space">    </span>chatHistory = [];</p>
<p class="p1"><span class="Apple-converted-space">    </span>addAIMessage("Hi! I'm your **Invesco AI Assistant** 🤖\n\nI fetch NAV data directly from AMFI via MFAPI.in. Ask me about NAVs, 1Y/3Y/5Y performance, SIP, redemptions, KYC, and tax.", false);</p>
<p class="p1"><span class="Apple-converted-space">    </span>const chips = $('#quickChips');</p>
<p class="p1"><span class="Apple-converted-space">    </span>chips.innerHTML = '';</p>
<p class="p1"><span class="Apple-converted-space">    </span>["Latest NAV","Start SIP","Redeem funds","Fund performance","KYC status","Tax help"].forEach(text=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>const btn = document.createElement('button');</p>
<p class="p1"><span class="Apple-converted-space">      </span>btn.className = 'px-3 h-8 rounded-full bg-slate-100 hover:bg-slate-200 border-slate-200 text-xs transition';</p>
<p class="p1"><span class="Apple-converted-space">      </span>btn.textContent = text;</p>
<p class="p1"><span class="Apple-converted-space">      </span>btn.onclick = ()=&gt; { $('#chatInput').value = text; sendChat(); };</p>
<p class="p1"><span class="Apple-converted-space">      </span>chips.appendChild(btn);</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function escapeHtml(s){ return s.replace(/&amp;/g,'&amp;amp;').replace(/&lt;/g,'&amp;lt;').replace(/&gt;/g,'&amp;gt;'); }</p>
<p class="p2"><span class="Apple-converted-space">  </span></p>
<p class="p1"><span class="Apple-converted-space">  </span>function addUserMessage(text){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const el = document.createElement('div');</p>
<p class="p1"><span class="Apple-converted-space">    </span>el.className = 'flex justify-end message-in';</p>
<p class="p1"><span class="Apple-converted-space">    </span>el.innerHTML = `&lt;div class="max-w-[80%] rounded-2xl rounded-tr-sm px-4 py-2.5 text-sm bg-gradient-to-r from-[#3B82F6] to-[#06B6D4] text-white shadow-lg shadow-blue-600/20"&gt;${escapeHtml(text)}&lt;/div&gt;`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#chatMessages').appendChild(el);</p>
<p class="p1"><span class="Apple-converted-space">    </span>scrollChat();</p>
<p class="p1"><span class="Apple-converted-space">    </span>chatHistory.push({role:'user', text});</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><span class="Apple-converted-space">  </span></p>
<p class="p1"><span class="Apple-converted-space">  </span>function addAIMessage(text, showFeedback=true, opts={}){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const el = document.createElement('div');</p>
<p class="p1"><span class="Apple-converted-space">    </span>el.className = 'flex gap-2.5 message-in items-start';</p>
<p class="p1"><span class="Apple-converted-space">    </span>el.innerHTML = `</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="w-8 h-8 rounded-xl bg-gradient-to-br from-[#3B82F6] to-[#06B6D4] flex items-center justify-center shrink-0 mt-0.5 shadow"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"&gt;&lt;path d="M12 8V4H8"/&gt;&lt;rect x="4" y="12" width="16" height="8" rx="2"/&gt;&lt;circle cx="12" cy="16" r="1"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="flex-1"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="glass rounded-2xl rounded-tl-sm px-4 py-3 text-[13.5px] leading-relaxed border-slate-200 text-slate-800"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>${opts.isLive ? `&lt;div class="inline-flex items-center gap-1.5 mb-2 px-2.5 py-1 rounded-full bg-slate-100 border"&gt;&lt;span class="text-[10px] font-semibold text-slate-700 tracking-widest"&gt;AMFI DATA&lt;/span&gt;&lt;/div&gt;` : ''}</p>
<p class="p1"><span class="Apple-converted-space">          </span>${formatMarkdown(text)}</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>${showFeedback ? `&lt;div class="flex items-center gap-2 mt-2 ml-1"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;span class="text-[11px] text-slate-500"&gt;Was this helpful?&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button class="feedback-btn px-2.5 h-6 rounded-lg bg-slate-100 hover:bg-emerald-500/10 text-[11px] border border-slate-200 hover:border-emerald-500/30 transition" data-v="yes"&gt;Yes&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;button class="feedback-btn px-2.5 h-6 rounded-lg bg-slate-100 hover:bg-slate-200 text-[11px] border border-slate-200 transition" data-v="no"&gt;No&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;` : ''}</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#chatMessages').appendChild(el);</p>
<p class="p1"><span class="Apple-converted-space">    </span>el.querySelectorAll('.feedback-btn').forEach(btn=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>btn.onclick = ()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">        </span>btn.parentElement.innerHTML = `&lt;span class="text-[11px] text-emerald-600"&gt;✓ Thanks for your feedback!&lt;/span&gt;`;</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(btn.dataset.v==='no'){</p>
<p class="p1"><span class="Apple-converted-space">          </span>setTimeout(()=&gt; addAIMessage("I'm sorry that didn't help. Would you like me to [raise a support ticket](#ticket) for you?", false), 600);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>};</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1"><span class="Apple-converted-space">    </span>el.querySelectorAll('a[data-action]').forEach(a=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>a.onclick = (e)=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">        </span>e.preventDefault();</p>
<p class="p1"><span class="Apple-converted-space">        </span>const act = a.dataset.action;</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(act==='open-account'){ closeLiveChat(); startOnboard(); }</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(act==='open-funds'){ closeLiveChat(); document.querySelector('#universe')?.scrollIntoView({behavior:'smooth'}); }</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(act==='ticket'){ closeLiveChat(); openSupportCenter('ticket'); }</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(act==='open-fund'){ const code = a.dataset.code; closeLiveChat(); setTimeout(()=&gt; openFundDetail(code), 300); }</p>
<p class="p1"><span class="Apple-converted-space">      </span>};</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1"><span class="Apple-converted-space">    </span>scrollChat();</p>
<p class="p1"><span class="Apple-converted-space">    </span>chatHistory.push({role:'ai', text});</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function formatMarkdown(text){</p>
<p class="p1"><span class="Apple-converted-space">    </span>let html = escapeHtml(text);</p>
<p class="p1"><span class="Apple-converted-space">    </span>html = html.replace(/\*\*(.+?)\*\*/g, '&lt;strong class="font-semibold text-slate-900"&gt;$1&lt;/strong&gt;');</p>
<p class="p1"><span class="Apple-converted-space">    </span>html = html.replace(/\n/g, '&lt;br&gt;');</p>
<p class="p1"><span class="Apple-converted-space">    </span>html = html.replace(/\[(.+?)\]\(#(.+?)\)/g, (m, txt, act)=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>if(act==='open-account' || act==='open-funds' || act==='ticket' || act.startsWith('fund-')) {</p>
<p class="p1"><span class="Apple-converted-space">        </span>return `&lt;a href="#" data-action="${act.startsWith('fund-')?'open-fund':act}" ${act.startsWith('fund-')?`data-code="${act.split('-')[1]}"`:''} class="text-sky-600 hover:underline font-medium"&gt;${txt}&lt;/a&gt;`;</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>return `&lt;a href="#" class="text-sky-600 hover:underline"&gt;${txt}&lt;/a&gt;`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1"><span class="Apple-converted-space">    </span>return html;</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function showTyping(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const el = document.createElement('div');</p>
<p class="p1"><span class="Apple-converted-space">    </span>el.id = 'typingIndicator';</p>
<p class="p1"><span class="Apple-converted-space">    </span>el.className = 'flex gap-2.5 items-start message-in';</p>
<p class="p1"><span class="Apple-converted-space">    </span>el.innerHTML = `&lt;div class="w-8 h-8 rounded-xl bg-gradient-to-br from-[#3B82F6] to-[#06B6D4] flex items-center justify-center shrink-0"&gt;&lt;svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"&gt;&lt;circle cx="12" cy="12" r="3"/&gt;&lt;/svg&gt;&lt;/div&gt;&lt;div class="glass rounded-2xl rounded-tl-sm px-4 py-3 border border-slate-200"&gt;&lt;div class="flex gap-1.5"&gt;&lt;span class="typing-dot"&gt;&lt;/span&gt;&lt;span class="typing-dot"&gt;&lt;/span&gt;&lt;span class="typing-dot"&gt;&lt;/span&gt;&lt;/div&gt;&lt;/div&gt;`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#chatMessages').appendChild(el);</p>
<p class="p1"><span class="Apple-converted-space">    </span>scrollChat();</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>function hideTyping(){ $('#typingIndicator')?.remove(); }</p>
<p class="p1"><span class="Apple-converted-space">  </span>function scrollChat(){ const m=$('#chatMessages'); m.scrollTop = m.scrollHeight; }</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>async function sendChat(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const input = $('#chatInput');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const txt = input.value.trim();</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!txt) return;</p>
<p class="p1"><span class="Apple-converted-space">    </span>addUserMessage(txt);</p>
<p class="p1"><span class="Apple-converted-space">    </span>input.value = '';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#quickChips').innerHTML = '';</p>
<p class="p1"><span class="Apple-converted-space">    </span>showTyping();</p>
<p class="p1"><span class="Apple-converted-space">    </span>try{</p>
<p class="p1"><span class="Apple-converted-space">      </span>const result = await processChat(txt);</p>
<p class="p1"><span class="Apple-converted-space">      </span>hideTyping();</p>
<p class="p1"><span class="Apple-converted-space">      </span>addAIMessage(result.text, true, result.opts||{});</p>
<p class="p1"><span class="Apple-converted-space">    </span>}catch(err){</p>
<p class="p1"><span class="Apple-converted-space">      </span>hideTyping();</p>
<p class="p1"><span class="Apple-converted-space">      </span>addAIMessage("Sorry, I couldn't fetch data. Please try again.", true);</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#chatSendBtn').onclick = sendChat;</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#chatInput').addEventListener('keypress', e=&gt;{ if(e.key==='Enter' &amp;&amp; !e.shiftKey){ e.preventDefault(); sendChat(); } });</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>async function processChat(message){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const msg = message.toLowerCase().trim();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const fundMap = {</p>
<p class="p1"><span class="Apple-converted-space">      </span>'midcap': 'Invesco India Midcap Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'mid cap': 'Invesco India Midcap Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'contra': 'Invesco India Contra Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'smallcap': 'Invesco India Smallcap Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'small cap': 'Invesco India Smallcap Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'elss': 'Invesco India ELSS Tax Saver Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'tax saver': 'Invesco India ELSS Tax Saver Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'gold': 'Invesco India Gold',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'psu': 'Invesco India PSU Equity Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'large cap': 'Invesco India Large Cap Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'large': 'Invesco India Large Cap Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'flexi': 'Invesco India Flexicap Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'flexicap': 'Invesco India Flexicap Fund',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'nifty': 'Invesco India Nifty',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'technology': 'Invesco India Technology',</p>
<p class="p1"><span class="Apple-converted-space">      </span>'financial': 'Invesco India Financial Services'</p>
<p class="p1"><span class="Apple-converted-space">    </span>};</p>
<p class="p1"><span class="Apple-converted-space">    </span>const findKeyword = () =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">      </span>for(const k of Object.keys(fundMap)){</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(msg.includes(k)) return {key:k, name:fundMap[k]};</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>return null;</p>
<p class="p1"><span class="Apple-converted-space">    </span>};</p>
<p class="p1"><span class="Apple-converted-space">    </span>const isSip = msg.includes('sip') || msg.includes('systematic');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const isRedeem = msg.includes('redeem') || msg.includes('redemption') || msg.includes('withdraw') || msg.includes('sell');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const isKyc = msg.includes('kyc') &amp;&amp; !msg.includes('nav');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const isGreeting = /^(hi|hello|hey|help)/.test(msg);</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>if(isSip || isRedeem || isKyc || isGreeting){</p>
<p class="p1"><span class="Apple-converted-space">      </span>return {text: getAIResponse(message), opts:{}};</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>if(msg === 'latest nav' || (msg.includes('latest') &amp;&amp; msg.includes('nav'))){</p>
<p class="p1"><span class="Apple-converted-space">      </span>try{</p>
<p class="p1"><span class="Apple-converted-space">        </span>const targets = ['contra','midcap','elss'];</p>
<p class="p1"><span class="Apple-converted-space">        </span>const results = [];</p>
<p class="p1"><span class="Apple-converted-space">        </span>for(const k of targets){</p>
<p class="p1"><span class="Apple-converted-space">          </span>const name = fundMap[k];</p>
<p class="p1"><span class="Apple-converted-space">          </span>const code = await getSchemeCode(name);</p>
<p class="p1"><span class="Apple-converted-space">          </span>if(code){</p>
<p class="p1"><span class="Apple-converted-space">            </span>try{ results.push(await getLiveNavData(code)); }catch{}</p>
<p class="p1"><span class="Apple-converted-space">          </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(results.length){</p>
<p class="p1"><span class="Apple-converted-space">          </span>const text = `**Top Invesco Funds — NAV**\n\n${results.map(r=&gt;`• **${r.scheme_name}**: ₹${r.nav} (as on ${r.date}) • 1D ${r.change1d&gt;=0?'+':''}${r.change1d.toFixed(2)}% • 1Y ${r.return1y&gt;=0?'+':''}${r.return1y.toFixed(1)}%`).join('\n')}\n\nSource: AMFI via MFAPI.in`;</p>
<p class="p1"><span class="Apple-converted-space">          </span>return {text, opts:{isLive:true}};</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>}catch(e){}</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>const kw = findKeyword();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const wantsLive = msg.includes('nav') || msg.includes('price') || msg.includes('performance') || msg.includes('return') || msg.includes('1y') || msg.includes('1d') || msg.includes('chart') || !!kw;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>if(wantsLive){</p>
<p class="p1"><span class="Apple-converted-space">      </span>const targetName = kw ? kw.name : 'Invesco India Contra Fund';</p>
<p class="p1"><span class="Apple-converted-space">      </span>try{</p>
<p class="p1"><span class="Apple-converted-space">        </span>const code = await getSchemeCode(targetName);</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(!code) throw new Error('nocode');</p>
<p class="p1"><span class="Apple-converted-space">        </span>const data = await getLiveNavData(code);</p>
<p class="p1"><span class="Apple-converted-space">        </span>const text = `${data.scheme_name} — NAV: ₹${data.nav} (as on ${data.date}). 1D: ${data.change1d&gt;=0?'+':''}${data.change1d.toFixed(2)}%, 1Y: ${data.return1y&gt;=0?'+':''}${data.return1y.toFixed(1)}%. Source: AMFI via MFAPI.in\n\n[View full chart](#fund-${data.schemeCode})`;</p>
<p class="p1"><span class="Apple-converted-space">        </span>return {text, opts:{isLive:true, fundCode:data.schemeCode}};</p>
<p class="p1"><span class="Apple-converted-space">      </span>}catch(err){</p>
<p class="p1"><span class="Apple-converted-space">        </span>const fallback = funds.find(f=&gt; f.scheme_name.toLowerCase().includes((kw?.key)||''));</p>
<p class="p1"><span class="Apple-converted-space">        </span>const lastNav = fallback?.nav || '89.10';</p>
<p class="p1"><span class="Apple-converted-space">        </span>return {text:`Unable to fetch data right now. Last known NAV: ₹${lastNav}\n\nPlease try again shortly.`, opts:{}};</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>return {text: getAIResponse(message), opts:{}};</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function getAIResponse(message){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const msg = message.toLowerCase().trim();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const ensureFunds = funds &amp;&amp; funds.length ? funds : [];</p>
<p class="p1"><span class="Apple-converted-space">    </span>const findFund = (kw)=&gt; ensureFunds.find(f=&gt; f.scheme_name.toLowerCase().includes(kw));</p>
<p class="p1"><span class="Apple-converted-space">    </span>let matchedFund = null;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const map = {'contra':'contra','midcap':'midcap','mid cap':'midcap','smallcap':'small','small cap':'small','elss':'elss','tax saver':'elss','gold':'gold','large cap':'large','large':'large','flexi':'flexi','psu':'psu','financial':'financial','technology':'technology','hybrid':'hybrid','index':'nifty','nifty':'nifty'};</p>
<p class="p1"><span class="Apple-converted-space">    </span>for(const [k,v] of Object.entries(map)){ if(msg.includes(k)){ const f=findFund(v); if(f){ matchedFund=f; break; } } }</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>if(msg.includes('sip') || msg.includes('systematic')){</p>
<p class="p1"><span class="Apple-converted-space">      </span>return `**Starting a SIP in 4 steps:**\n\n1. Choose fund from [Fund Universe](#open-funds)\n2. Click **Invest Now** → select **SIP**\n3. Set amount (min ₹500), date, duration\n4. Approve bank mandate\n\nNew investor? [Open Account](#open-account) first — takes 5 mins with eKYC.`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>if(msg.includes('redeem') || msg.includes('redemption') || msg.includes('withdraw') || msg.includes('sell')){</p>
<p class="p1"><span class="Apple-converted-space">      </span>return `**Redemption Settlement**\n\n• Equity: **T+2** business days\n• Debt: **T+1**\n• Liquid: **Instant up to ₹50k**\n\nGo to Dashboard → Holdings → Redeem → Confirm OTP. Proceeds to registered bank.`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>if(msg.includes('kyc')){</p>
<p class="p1"><span class="Apple-converted-space">      </span>if(currentUser &amp;&amp; currentUser.pan){</p>
<p class="p1"><span class="Apple-converted-space">        </span>return `**KYC Status: Verified ✓**\n\nPAN: ${currentUser.pan}\nName: ${currentUser.name}\n\nYou can invest in all schemes.`;</p>
<p class="p1"><span class="Apple-converted-space">      </span>}</p>
<p class="p1"><span class="Apple-converted-space">      </span>return `**KYC Required**\n\nComplete eKYC with PAN + Aadhaar in 5 mins.\n\n[Start KYC now](#open-account)`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>if(msg.includes('tax') || msg.includes('80c') || msg.includes('ltcg') || msg.includes('elss')){</p>
<p class="p1"><span class="Apple-converted-space">      </span>return `**Tax Guide FY 24-25**\n\n• **ELSS (80C)**: Deduct up to ₹1.5L, 3-year lock-in\n• **Equity LTCG**: &gt;₹1.25L gains @ **12.5%**\n• **STCG**: 20%\n• **Debt**: As per slab\n\nDownload statements from Dashboard.`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>if(/^(hi|hello|hey|help)/.test(msg)){</p>
<p class="p1"><span class="Apple-converted-space">      </span>return `Hello! 👋 I provide NAV data from AMFI. Try: "Latest NAV", "Midcap NAV", "Contra performance", or "Start SIP"`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p2"><span class="Apple-converted-space">    </span></p>
<p class="p1"><span class="Apple-converted-space">    </span>return `I can help with **NAVs, performance, SIP, redemptions, KYC, tax**.\n\nAll NAV data is from AMFI via MFAPI.in. For account issues, [raise a ticket](#ticket) — we reply within 24h.`;</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>const faqData = [</p>
<p class="p1"><span class="Apple-converted-space">    </span>{cat:'Account Opening', qs:[{q:'How long does account opening take?',a:'Digital eKYC takes 5-7 minutes. Your account is active instantly after PAN verification.'},{q:'What documents are required?',a:'PAN, Aadhaar for eKYC, bank proof, and a selfie. No physical paperwork.'},{q:'Is there any opening charge?',a:'Zero account opening fees. Only statutory charges apply.'}]},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{cat:'KYC', qs:[{q:'Is Aadhaar mandatory?',a:'Yes, for instant eKYC. You can also do offline KYC via CVL KRA.'},{q:'KYC failed, what next?',a:'Check name mismatch PAN-Aadhaar. Retry or contact support at 1800-209-0007.'},{q:'How to update KYC details?',a:'Go to Dashboard &gt; Profile &gt; Update KYC. Re-verify via OTP.'}]},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{cat:'SIP', qs:[{q:'How to start a SIP?',a:'Choose fund &gt; Invest Now &gt; Select SIP &gt; set amount, date, duration.'},{q:'Can I pause SIP?',a:'Yes, pause up to 3 months from Holdings &gt; SIP details.'},{q:'SIP mandate charges?',a:'No charges from Invesco. Your bank may have NACH fees.'},{q:'Minimum SIP amount?',a:'₹500 for most equity funds, ₹100 for ELSS.'}]},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{cat:'Redemption', qs:[{q:'Redemption timeline?',a:'Equity: T+2, Debt: T+1, Liquid: T+0 or instant (up to ₹50k).'},{q:'Any exit load?',a:'Varies by scheme. Check fund detail page for exact load structure.'},{q:'How to redeem?',a:'Dashboard &gt; Holdings &gt; Select fund &gt; Redeem &gt; Confirm OTP.'}]},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{cat:'NAV', qs:[{q:'When is NAV updated?',a:'Daily by 11 PM IST on business days. Updated on our portal via AMFI.'},{q:'Which NAV will I get?',a:'Before 3 PM: same day NAV. After 3 PM: next business day NAV.'},{q:'Where to track NAV history?',a:'Fund detail page shows charts for 1M to 5Y and since inception.'}]},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{cat:'Tax', qs:[{q:'ELSS lock-in?',a:'3 years from allotment date. Each SIP locked individually.'},{q:'Capital gains tax?',a:'Equity LTCG &gt;₹1.25L taxed at 12.5%, STCG 20%. Debt as per slab.'},{q:'Tax proof where?',a:'Download ELSS proof from Dashboard &gt; Statements &gt; Tax Proforma.'}]},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{cat:'Nominee', qs:[{q:'Is nominee mandatory?',a:'Yes, as per SEBI. Add during onboarding or later in Profile.'},{q:'Can I change nominee?',a:'Yes, Dashboard &gt; Profile &gt; Nominee &gt; Update. eSign required.'},{q:'How many nominees?',a:'Up to 3 nominees with percentage allocation.'}]},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{cat:'2FA', qs:[{q:'How to enable 2FA?',a:'Dashboard &gt; Profile &amp; Security &gt; Toggle 2FA &gt; Choose SMS/Email/App.'},{q:'Lost phone with authenticator?',a:'Use backup codes or contact support with PAN verification at service@invesco.com.'},{q:'Is 2FA mandatory?',a:'Recommended. Mandatory for redemptions &gt;₹2L as per security policy.'}]}</p>
<p class="p1"><span class="Apple-converted-space">  </span>];</p>
<p class="p1"><span class="Apple-converted-space">  </span>function renderFAQs(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const c = $('#faqContainer');</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!c || c.dataset.rendered) return;</p>
<p class="p1"><span class="Apple-converted-space">    </span>c.dataset.rendered = '1';</p>
<p class="p1"><span class="Apple-converted-space">    </span>c.innerHTML = faqData.map((cat,i)=&gt;`</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="glass rounded-2xl overflow-hidden border border-slate-200"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;button class="faq-cat w-full flex items-center justify-between p-4 hover:bg-slate-50 transition" data-idx="${i}"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;span class="font-medium flex items-center gap-3 text-slate-900"&gt;&lt;span class="w-8 h-8 rounded-xl bg-slate-100 flex items-center justify-center text-sm"&gt;${i+1}&lt;/span&gt;${cat.cat}&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;svg class="chev w-4 h-4 transition" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"&gt;&lt;path d="M6 9l6 6 6-6"/&gt;&lt;/svg&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="dropdown-content"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="px-4 pb-4 space-y-2 border-t border-slate-100 pt-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>${cat.qs.map((q,j)=&gt;`</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;div class="rounded-xl bg-slate-50 border border-slate-200"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;button class="faq-q w-full text-left px-3 py-2.5 text-sm flex justify-between items-center hover:bg-slate-100 text-slate-800" data-q="${i}-${j}"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                  </span>${q.q}</p>
<p class="p1"><span class="Apple-converted-space">                  </span>&lt;span class="text-slate-500"&gt;+&lt;/span&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>&lt;div class="faq-a hidden px-3 pb-3 text-[13px] text-slate-600 leading-relaxed"&gt;${q.a}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">              </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>`).join('')}</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>`).join('');</p>
<p class="p1"><span class="Apple-converted-space">    </span>c.querySelectorAll('.faq-cat').forEach(btn=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>btn.onclick = ()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">        </span>const content = btn.nextElementSibling;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const isOpen = content.classList.contains('open');</p>
<p class="p1"><span class="Apple-converted-space">        </span>c.querySelectorAll('.dropdown-content').forEach(d=&gt;d.classList.remove('open'));</p>
<p class="p1"><span class="Apple-converted-space">        </span>c.querySelectorAll('.chev').forEach(s=&gt;s.style.transform='');</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(!isOpen){ content.classList.add('open'); btn.querySelector('.chev').style.transform='rotate(180deg)'; }</p>
<p class="p1"><span class="Apple-converted-space">      </span>};</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1"><span class="Apple-converted-space">    </span>c.querySelectorAll('.faq-q').forEach(b=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>b.onclick = ()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">        </span>const a = b.nextElementSibling;</p>
<p class="p1"><span class="Apple-converted-space">        </span>const open = !a.classList.contains('hidden');</p>
<p class="p1"><span class="Apple-converted-space">        </span>b.closest('.dropdown-content').querySelectorAll('.faq-a').forEach(x=&gt;x.classList.add('hidden'));</p>
<p class="p1"><span class="Apple-converted-space">        </span>b.closest('.dropdown-content').querySelectorAll('.faq-q span').forEach(s=&gt;s.textContent='+');</p>
<p class="p1"><span class="Apple-converted-space">        </span>if(!open){ a.classList.remove('hidden'); b.querySelector('span').textContent='−'; }</p>
<p class="p1"><span class="Apple-converted-space">      </span>};</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#ticketForm')?.addEventListener('submit', e=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">    </span>e.preventDefault();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const cat = $('#ticketCategory').value;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const sub = $('#ticketSubject').value.trim();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const desc = $('#ticketDesc').value.trim();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const pri = $('#ticketPriority').value;</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!sub || !desc) return toast('Fill all fields','⚠️');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const id = 'INV-TKT-'+Math.random().toString(36).substring(2,8).toUpperCase();</p>
<p class="p1"><span class="Apple-converted-space">    </span>const t = { id, userRef: currentUser?.ref || 'GUEST', category:cat, subject:sub, description:desc, priority:pri, status:'Open', createdAt: new Date().toISOString(), updatedAt: new Date().toISOString(), messages:[{from:'user', text:desc, time:new Date().toISOString()}, {from:'agent', text:'Thanks for contacting Invesco Support. Ticket '+id+' is assigned. We will respond shortly.', time:new Date().toISOString()}] };</p>
<p class="p1"><span class="Apple-converted-space">    </span>tickets.unshift(t); saveTickets();</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#ticketSuccess').classList.remove('hidden');</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#ticketSuccessId').textContent = id;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#ticketEst').textContent = pri==='High'?'4 hours':pri==='Medium'?'24 hours':'48 hours';</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#ticketForm').reset();</p>
<p class="p1"><span class="Apple-converted-space">    </span>renderMyTickets(); toast('Ticket created: '+id);</p>
<p class="p1"><span class="Apple-converted-space">  </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function renderMyTickets(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const list = $('#myTicketsList');</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!list) return;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const userRef = currentUser?.ref || 'GUEST';</p>
<p class="p1"><span class="Apple-converted-space">    </span>const my = tickets.filter(t=&gt;t.userRef===userRef);</p>
<p class="p1"><span class="Apple-converted-space">    </span>if(!my.length){ list.innerHTML = `&lt;div class="text-center py-12 text-slate-500"&gt;&lt;div class="text-5xl mb-3"&gt;🎫&lt;/div&gt;&lt;div&gt;No tickets yet&lt;/div&gt;&lt;button onclick="switchSupportTab('ticket')" class="mt-3 px-4 h-9 rounded-xl bg-slate-900 text-white text-sm btn-secondary ripple-container"&gt;Raise your first ticket&lt;/button&gt;&lt;/div&gt;`; return; }</p>
<p class="p1"><span class="Apple-converted-space">    </span>list.innerHTML = `&lt;div class="overflow-x-auto"&gt;&lt;table class="w-full text-sm"&gt;&lt;thead class="text-xs text-slate-500 border-b border-slate-200"&gt;&lt;tr&gt;&lt;th class="text-left py-2.5 px-3"&gt;Ticket ID&lt;/th&gt;&lt;th class="text-left py-2.5 px-3"&gt;Subject&lt;/th&gt;&lt;th class="text-left py-2.5 px-3"&gt;Category&lt;/th&gt;&lt;th class="text-left py-2.5 px-3"&gt;Status&lt;/th&gt;&lt;th class="text-left py-2.5 px-3"&gt;Last Update&lt;/th&gt;&lt;/tr&gt;&lt;/thead&gt;&lt;tbody class="divide-y divide-slate-100"&gt;${my.map(t=&gt;`</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;tr class="hover:bg-slate-50 cursor-pointer transition" onclick="openTicket('${t.id}')"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;td class="py-3 px-3 font-mono text-xs text-sky-600"&gt;${t.id}&lt;/td&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;td class="py-3 px-3 text-slate-800"&gt;${t.subject}&lt;/td&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;td class="py-3 px-3 text-slate-500"&gt;${t.category}&lt;/td&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;td class="py-3 px-3"&gt;&lt;span class="px-2 py-1 rounded-full text-[11px] border ${t.status==='Open'?'bg-amber-500/10 text-amber-700 border-amber-500/20':t.status==='In Progress'?'bg-blue-500/10 text-blue-700 border-blue-500/20':'bg-emerald-500/10 text-emerald-700 border-emerald-500/20'}"&gt;${t.status}&lt;/span&gt;&lt;/td&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;td class="py-3 px-3 text-slate-500 text-xs"&gt;${new Date(t.updatedAt).toLocaleString()}&lt;/td&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/tr&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>`).join('')}&lt;/tbody&gt;&lt;/table&gt;&lt;/div&gt;`;</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>window.openTicket = (id)=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">    </span>const t = tickets.find(x=&gt;x.id===id); if(!t) return;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#ticketThreadId').textContent = id;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#ticketThreadSubject').textContent = t.subject;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#ticketThreadStatus').textContent = t.status;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#ticketThreadStatus').className = `px-2.5 py-1 rounded-full text-xs border ${t.status==='Open'?'bg-amber-500/10 text-amber-700 border-amber-500/20':t.status==='In Progress'?'bg-blue-500/10 text-blue-700 border-blue-500/20':'bg-emerald-500/10 text-emerald-700 border-emerald-500/20'}`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#ticketThreadMessages').innerHTML = t.messages.map(m=&gt;`</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="flex ${m.from==='user'?'justify-end':'justify-start'} mb-3"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="${m.from==='user'?'bg-[#3B82F6] text-white':'bg-white border border-slate-200 text-slate-800'} rounded-2xl ${m.from==='user'?'rounded-tr-sm':'rounded-tl-sm'} px-3 py-2 text-sm max-w-[75%]"&gt;${m.text}&lt;div class="text-[10px] opacity-70 mt-1"&gt;${new Date(m.time).toLocaleTimeString([], {hour:'2-digit',minute:'2-digit'})}&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>`).join('');</p>
<p class="p1"><span class="Apple-converted-space">    </span>open('#ticketThreadModal');</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#ticketReplySend')?.addEventListener('click', ()=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">    </span>const id = $('#ticketThreadId').textContent;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const txt = $('#ticketReplyInput').value.trim(); if(!txt) return;</p>
<p class="p1"><span class="Apple-converted-space">    </span>const t = tickets.find(x=&gt;x.id===id); t.messages.push({from:'user', text:txt, time:new Date().toISOString()}); t.updatedAt=new Date().toISOString(); t.status='In Progress'; saveTickets();</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#ticketReplyInput').value=''; openTicket(id); renderMyTickets(); setTimeout(()=&gt;{ t.messages.push({from:'agent', text:'Thanks for the update. Our specialist is reviewing this and will respond with resolution steps.', time:new Date().toISOString()}); t.updatedAt=new Date().toISOString(); saveTickets(); openTicket(id); renderMyTickets(); },1200);</p>
<p class="p1"><span class="Apple-converted-space">  </span>});</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function renderTutorials(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const grid = $('#tutorialsGrid'); if(!grid || grid.dataset.done) return; grid.dataset.done='1';</p>
<p class="p1"><span class="Apple-converted-space">    </span>const vids = [</p>
<p class="p1"><span class="Apple-converted-space">      </span>{t:'How to start SIP in 2 minutes', d:'4:12', views:'12.4k', id:'dQw4w9WgXcQ'},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{t:'Complete KYC process explained', d:'3:45', views:'8.7k', id:'oHg5SJYRHA0'},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{t:'Redeem funds instantly', d:'2:58', views:'6.2k', id:'dQw4w9WgXcQ'},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{t:'Set up 2FA for security', d:'3:20', views:'5.1k', id:'oHg5SJYRHA0'},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{t:'Download account statement', d:'2:15', views:'4.3k', id:'dQw4w9WgXcQ'},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{t:'Update nominee details', d:'3:05', views:'3.9k', id:'oHg5SJYRHA0'}</p>
<p class="p1"><span class="Apple-converted-space">    </span>];</p>
<p class="p1"><span class="Apple-converted-space">    </span>grid.innerHTML = vids.map(v=&gt;`</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;div class="group glass rounded-2xl overflow-hidden cursor-pointer card-hover" onclick="playVideo('${v.id}','${v.t.replace(/'/g,"")}')"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="aspect-video bg-gradient-to-br from-[#3B82F6]/20 to-[#06B6D4]/20 relative flex items-center justify-center"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="w-14 h-14 rounded-full bg-white/80 backdrop-blur flex items-center justify-center group-hover:scale-110 transition shadow-lg"&gt;&lt;svg width="24" height="24" viewBox="0 0 24 24" fill="#3B82F6"&gt;&lt;polygon points="8,5 19,12 8,19"/&gt;&lt;/svg&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div class="absolute bottom-2 right-2 px-1.5 py-0.5 rounded bg-black/70 text-[11px] text-white"&gt;${v.d}&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="p-3"&gt;&lt;div class="font-medium text-sm leading-snug text-slate-900"&gt;${v.t}&lt;/div&gt;&lt;div class="text-xs text-slate-500 mt-1"&gt;${v.views} views&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>`).join('');</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p1"><span class="Apple-converted-space">  </span>window.playVideo = (id,title)=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#videoTitle').textContent = title;</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#videoFrame').src = `https://www.youtube.com/embed/${id}?autoplay=1&amp;modestbranding=1`;</p>
<p class="p1"><span class="Apple-converted-space">    </span>open('#videoPlayerModal');</p>
<p class="p1"><span class="Apple-converted-space">  </span>};</p>
<p class="p1"><span class="Apple-converted-space">  </span>$('#videoPlayerModal').addEventListener('click', e=&gt;{ if(e.target.closest('[data-close]')) $('#videoFrame').src=''; });</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">  </span>function renderBranches(){</p>
<p class="p1"><span class="Apple-converted-space">    </span>const list = $('#branchesList'); if(!list || list.dataset.done) return; list.dataset.done='1';</p>
<p class="p1"><span class="Apple-converted-space">    </span>const branches = [</p>
<p class="p1"><span class="Apple-converted-space">      </span>{name:'Fort - Head Office', address:'215, 2nd Floor, Express Towers, Nariman Point, Mumbai 400021', phone:'022-6731 0000', city:'Mumbai'},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{name:'Bandra Kurla Complex', address:'Plot C-70, G Block, BKC, Mumbai 400051', phone:'022-6731 0001', city:'Mumbai'},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{name:'Andheri East', address:'5th Floor, Windsor, Andheri Kurla Road, Mumbai 400059', phone:'022-6731 0002', city:'Mumbai'},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{name:'Thane Branch', address:'Shop 12, Viviana Mall, Ghodbunder Road, Thane 400607', phone:'022-6731 0003', city:'Thane'},</p>
<p class="p1"><span class="Apple-converted-space">      </span>{name:'Vashi - Navi Mumbai', address:'1st Floor, Raghuleela Mall, Sector 30A, Vashi 400703', phone:'022-6731 0004', city:'Navi Mumbai'}</p>
<p class="p1"><span class="Apple-converted-space">    </span>];</p>
<p class="p1"><span class="Apple-converted-space">    </span>const render = (q='')=&gt;{</p>
<p class="p1"><span class="Apple-converted-space">      </span>const f = branches.filter(b=&gt; !q || b.city.toLowerCase().includes(q) || b.name.toLowerCase().includes(q));</p>
<p class="p1"><span class="Apple-converted-space">      </span>list.innerHTML = f.map(b=&gt;`</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="glass rounded-2xl p-4 flex justify-between items-start gap-4 card-hover"&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;div&gt;&lt;div class="font-medium text-slate-900"&gt;${b.name}&lt;/div&gt;&lt;div class="text-sm text-slate-500 mt-1"&gt;${b.address}&lt;/div&gt;&lt;div class="text-xs text-slate-500 mt-2"&gt;📞 ${b.phone} • ${b.city}&lt;/div&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">          </span>&lt;a href="https://www.google.com/maps/search/?api=1&amp;query=${encodeURIComponent(b.name+' '+b.address)}" target="_blank" class="px-3 h-9 rounded-xl bg-slate-900 text-white hover:bg-slate-800 text-xs whitespace-nowrap btn-secondary ripple-container"&gt;Open Map&lt;/a&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">      </span>`).join('');</p>
<p class="p1"><span class="Apple-converted-space">    </span>};</p>
<p class="p1"><span class="Apple-converted-space">    </span>render('mumbai');</p>
<p class="p1"><span class="Apple-converted-space">    </span>$('#branchSearch')?.addEventListener('input', e=&gt; render(e.target.value.toLowerCase()));</p>
<p class="p1"><span class="Apple-converted-space">  </span>}</p>
<p class="p2"><br></p>
<p class="p1">})();</p>
<p class="p1">&lt;/script&gt;</p>
<p class="p1">&lt;/body&gt;</p>
<p class="p1">&lt;/html&gt;</p>
</body>
</html>
