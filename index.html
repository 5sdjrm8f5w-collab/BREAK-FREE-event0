<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<meta name="theme-color" content="#0a1208">
<title>Break Free — Discover More</title>

<!-- QR Code library (lightweight, ~10kb) -->
<script src="https://cdn.jsdelivr.net/npm/qrcodejs@1.0.0/qrcode.min.js"></script>

<style>
  /* ========== RESET & BASE ========== */
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --jungle-deep: #050a04;
    --jungle-dark: #0a1208;
    --jungle-mid: #14210d;
    --jungle-leaf: #1a3010;
    --neon-yellow: #e8ff1a;
    --neon-yellow-hover: #b8cc00;
    --neon-glow: rgba(232, 255, 26, 0.4);
    --text-white: #ffffff;
    --text-muted: rgba(255, 255, 255, 0.65);
    --success: #4ade80;
    --card-bg: rgba(255, 255, 255, 0.04);
    --card-border: rgba(232, 255, 26, 0.15);
  }

  @font-face {
    font-family: 'SystemSans';
    src: local('SF Pro Display'), local('Helvetica Neue'), local('Segoe UI');
  }

  html, body {
    height: 100%;
    overflow-x: hidden;
    background: var(--jungle-deep);
    color: var(--text-white);
    font-family: 'Space Grotesk', 'Inter', 'SF Pro Display', -apple-system, system-ui, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-rendering: optimizeLegibility;
  }

  /* ========== JUNGLE BACKGROUND ========== */
  body {
    position: relative;
    min-height: 100vh;
    min-height: 100dvh;
    background:
      radial-gradient(ellipse at 20% 0%, rgba(26, 48, 16, 0.6) 0%, transparent 50%),
      radial-gradient(ellipse at 80% 100%, rgba(20, 33, 13, 0.7) 0%, transparent 50%),
      linear-gradient(180deg, var(--jungle-dark) 0%, var(--jungle-deep) 100%);
  }

  /* Foliage SVG overlay */
  .foliage-bg {
    position: fixed;
    inset: 0;
    z-index: 0;
    pointer-events: none;
    opacity: 0.35;
    background-image:
      url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 400 400'><g fill='none' stroke='%231a3010' stroke-width='1.2' opacity='0.6'><path d='M50 350 Q 80 280 60 200 Q 40 140 90 100 Q 130 80 150 50'/><path d='M60 200 Q 30 180 20 220'/><path d='M60 200 Q 90 180 100 220'/><path d='M90 100 Q 70 90 50 110'/><path d='M90 100 Q 110 80 130 95'/><path d='M350 350 Q 320 280 340 210 Q 360 150 320 110 Q 290 85 280 60'/><path d='M340 210 Q 370 190 380 230'/><path d='M340 210 Q 310 190 300 230'/><path d='M200 380 Q 230 320 210 250 Q 190 200 220 160'/><path d='M210 250 Q 180 230 170 270'/><path d='M210 250 Q 240 230 250 270'/></g><g fill='%23234015' opacity='0.4'><ellipse cx='150' cy='50' rx='22' ry='8' transform='rotate(-25 150 50)'/><ellipse cx='130' cy='95' rx='18' ry='6' transform='rotate(15 130 95)'/><ellipse cx='50' cy='110' rx='20' ry='7' transform='rotate(-35 50 110)'/><ellipse cx='20' cy='220' rx='16' ry='5' transform='rotate(-15 20 220)'/><ellipse cx='100' cy='220' rx='17' ry='6' transform='rotate(20 100 220)'/><ellipse cx='280' cy='60' rx='20' ry='7' transform='rotate(30 280 60)'/><ellipse cx='380' cy='230' rx='18' ry='6' transform='rotate(15 380 230)'/><ellipse cx='300' cy='230' rx='16' ry='5' transform='rotate(-20 300 230)'/><ellipse cx='220' cy='160' rx='22' ry='8' transform='rotate(-10 220 160)'/><ellipse cx='170' cy='270' rx='17' ry='6' transform='rotate(-25 170 270)'/><ellipse cx='250' cy='270' rx='18' ry='6' transform='rotate(25 250 270)'/></g></svg>");
    background-size: 380px 380px;
    background-position: center;
  }

  /* Grain overlay */
  .grain {
    position: fixed;
    inset: 0;
    z-index: 1;
    pointer-events: none;
    opacity: 0.06;
    background-image: url("data:image/svg+xml;utf8,<svg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'><filter id='n'><feTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='3'/></filter><rect width='100%' height='100%' filter='url(%23n)'/></svg>");
  }

  /* Neon glow accents */
  .glow-orb {
    position: fixed;
    width: 280px;
    height: 280px;
    border-radius: 50%;
    filter: blur(80px);
    pointer-events: none;
    z-index: 0;
    opacity: 0.18;
  }
  .glow-orb.top { top: -100px; right: -80px; background: var(--neon-yellow); }
  .glow-orb.bottom { bottom: -120px; left: -80px; background: #2d5a1c; opacity: 0.4; }

  /* ========== APP CONTAINER ========== */
  .app {
    position: relative;
    z-index: 10;
    min-height: 100vh;
    min-height: 100dvh;
    max-width: 480px;
    margin: 0 auto;
    padding: 28px 22px 40px;
    display: flex;
    flex-direction: column;
  }

  /* Top brand bar */
  .topbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 28px;
    opacity: 0.9;
  }
  .topbar .badge {
    font-size: 10px;
    letter-spacing: 2px;
    font-weight: 600;
    color: var(--neon-yellow);
    text-transform: uppercase;
    padding: 5px 10px;
    border: 1px solid var(--neon-yellow);
    border-radius: 999px;
  }
  .topbar .live-dot {
    display: inline-block;
    width: 6px;
    height: 6px;
    background: var(--neon-yellow);
    border-radius: 50%;
    margin-right: 7px;
    box-shadow: 0 0 8px var(--neon-yellow);
    animation: pulse 1.6s infinite;
  }
  @keyframes pulse {
    0%, 100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.4; transform: scale(0.85); }
  }
  .topbar .logo-mini {
    height: 22px;
    opacity: 0.85;
  }

  /* ========== SECTIONS ========== */
  .section {
    display: none;
    flex: 1;
    flex-direction: column;
    animation: fadeIn 0.5s ease-out;
  }
  .section.active { display: flex; }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(12px); }
    to { opacity: 1; transform: translateY(0); }
  }

  /* ========== TYPOGRAPHY ========== */
  .display-title {
    font-size: clamp(38px, 11vw, 52px);
    font-weight: 800;
    line-height: 0.95;
    letter-spacing: -0.03em;
    margin-bottom: 14px;
  }
  .display-title .accent {
    color: var(--neon-yellow);
    font-style: italic;
    font-weight: 800;
    text-shadow: 0 0 30px var(--neon-glow);
  }
  .subtitle {
    font-size: 15px;
    line-height: 1.5;
    color: var(--text-muted);
    margin-bottom: 36px;
    max-width: 340px;
  }

  /* ========== SECTION 1: GATE ========== */
  .gate-hero {
    margin-top: 8px;
  }
  .gate-frame {
    position: relative;
    aspect-ratio: 1 / 1;
    width: 100%;
    max-width: 320px;
    margin: 0 auto 28px;
    border: 2px dashed var(--card-border);
    border-radius: 24px;
    background:
      radial-gradient(circle at center, rgba(232, 255, 26, 0.06) 0%, transparent 70%),
      var(--card-bg);
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    transition: all 0.3s ease;
  }
  .gate-frame.has-image {
    border-style: solid;
    border-color: var(--neon-yellow);
  }
  .gate-frame .preview-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  .gate-frame .corner {
    position: absolute;
    width: 24px;
    height: 24px;
    border-color: var(--neon-yellow);
    border-style: solid;
    border-width: 0;
  }
  .gate-frame .corner.tl { top: 12px; left: 12px; border-top-width: 2px; border-left-width: 2px; }
  .gate-frame .corner.tr { top: 12px; right: 12px; border-top-width: 2px; border-right-width: 2px; }
  .gate-frame .corner.bl { bottom: 12px; left: 12px; border-bottom-width: 2px; border-left-width: 2px; }
  .gate-frame .corner.br { bottom: 12px; right: 12px; border-bottom-width: 2px; border-right-width: 2px; }

  .gate-icon {
    width: 80px;
    height: 80px;
    color: var(--neon-yellow);
    opacity: 0.6;
  }

  /* Scan line animation when analyzing */
  .scan-line {
    position: absolute;
    left: 0;
    right: 0;
    height: 3px;
    background: linear-gradient(90deg, transparent, var(--neon-yellow), transparent);
    box-shadow: 0 0 12px var(--neon-yellow);
    display: none;
    animation: scan 1.6s ease-in-out infinite;
  }
  .gate-frame.scanning .scan-line { display: block; }
  @keyframes scan {
    0% { top: 0%; }
    50% { top: 100%; }
    100% { top: 0%; }
  }

  /* ========== UPLOAD BUTTON ========== */
  .upload-btn {
    position: relative;
    width: 100%;
    padding: 18px 24px;
    background: var(--neon-yellow);
    color: #000;
    border: none;
    border-radius: 16px;
    font-size: 16px;
    font-weight: 700;
    letter-spacing: 0.02em;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    transition: all 0.2s ease;
    box-shadow: 0 0 0 0 var(--neon-glow), 0 8px 24px rgba(232, 255, 26, 0.25);
    overflow: hidden;
  }
  .upload-btn::before {
    content: '';
    position: absolute;
    top: 0; left: -100%;
    width: 100%; height: 100%;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
    transition: left 0.6s ease;
  }
  .upload-btn:hover::before { left: 100%; }
  .upload-btn:hover {
    background: var(--neon-yellow-hover);
    transform: translateY(-2px);
    box-shadow: 0 0 0 6px rgba(232, 255, 26, 0.15), 0 12px 28px rgba(232, 255, 26, 0.35);
  }
  .upload-btn:active { transform: translateY(0); }
  .upload-btn svg { width: 20px; height: 20px; }

  .upload-btn input[type="file"] {
    position: absolute;
    inset: 0;
    opacity: 0;
    cursor: pointer;
  }

  /* ========== LOADER ========== */
  .loader-box {
    display: none;
    flex-direction: column;
    align-items: center;
    gap: 14px;
    padding: 20px;
    text-align: center;
  }
  .loader-box.active { display: flex; }

  .loader-ring {
    width: 44px;
    height: 44px;
    border: 3px solid rgba(232, 255, 26, 0.15);
    border-top-color: var(--neon-yellow);
    border-radius: 50%;
    animation: spin 0.8s linear infinite;
  }
  @keyframes spin { to { transform: rotate(360deg); } }

  .loader-text {
    font-size: 14px;
    color: var(--text-muted);
    letter-spacing: 0.02em;
  }

  /* ========== SUCCESS BOX ========== */
  .success-box {
    display: none;
    flex-direction: column;
    align-items: center;
    gap: 12px;
    padding: 20px;
    text-align: center;
    animation: popIn 0.5s cubic-bezier(0.34, 1.56, 0.64, 1);
  }
  .success-box.active { display: flex; }
  @keyframes popIn {
    0% { opacity: 0; transform: scale(0.7); }
    100% { opacity: 1; transform: scale(1); }
  }
  .success-check {
    width: 56px;
    height: 56px;
    background: var(--success);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 0 30px rgba(74, 222, 128, 0.4);
  }
  .success-check svg { width: 30px; height: 30px; color: #000; }
  .success-text {
    font-size: 16px;
    font-weight: 600;
    color: var(--text-white);
  }

  /* ========== SECTION 2: FORM ========== */
  .form-wrap {
    display: flex;
    flex-direction: column;
    gap: 18px;
    margin-top: 8px;
  }
  .field {
    display: flex;
    flex-direction: column;
    gap: 8px;
  }
  .field label {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    color: var(--neon-yellow);
  }
  .field input {
    background: var(--card-bg);
    border: 1px solid var(--card-border);
    border-radius: 12px;
    padding: 16px 18px;
    font-size: 16px;
    color: var(--text-white);
    font-family: inherit;
    transition: all 0.2s ease;
    -webkit-appearance: none;
    appearance: none;
  }
  .field input::placeholder { color: rgba(255,255,255,0.3); }
  .field input:focus {
    outline: none;
    border-color: var(--neon-yellow);
    background: rgba(232, 255, 26, 0.05);
    box-shadow: 0 0 0 3px rgba(232, 255, 26, 0.12);
  }

  .submit-btn {
    margin-top: 14px;
    width: 100%;
    padding: 18px 24px;
    background: var(--neon-yellow);
    color: #000;
    border: none;
    border-radius: 16px;
    font-size: 16px;
    font-weight: 700;
    letter-spacing: 0.04em;
    cursor: pointer;
    transition: all 0.2s ease;
    text-transform: uppercase;
  }
  .submit-btn:hover {
    background: var(--neon-yellow-hover);
    transform: translateY(-2px);
    box-shadow: 0 8px 24px rgba(232, 255, 26, 0.3);
  }
  .submit-btn:disabled {
    opacity: 0.4;
    cursor: not-allowed;
    transform: none;
  }

  /* ========== SECTION 3: TICKET ========== */
  .ticket-section {
    align-items: center;
    justify-content: flex-start;
    gap: 22px;
  }

  .ticket-intro {
    text-align: center;
    margin-bottom: 4px;
  }
  .ticket-intro h2 {
    font-size: 28px;
    font-weight: 800;
    letter-spacing: -0.02em;
    margin-bottom: 6px;
  }
  .ticket-intro p {
    font-size: 13px;
    color: var(--text-muted);
  }

  .wallet-ticket {
    width: 100%;
    max-width: 360px;
    background: linear-gradient(160deg, #1a2410 0%, #0d1606 100%);
    border-radius: 22px;
    overflow: hidden;
    box-shadow:
      0 30px 60px rgba(0,0,0,0.5),
      0 0 0 1px rgba(232, 255, 26, 0.2),
      inset 0 1px 0 rgba(255,255,255,0.05);
    position: relative;
    animation: ticketReveal 0.7s cubic-bezier(0.34, 1.36, 0.64, 1);
  }
  @keyframes ticketReveal {
    0% { opacity: 0; transform: translateY(40px) rotateX(20deg); }
    100% { opacity: 1; transform: translateY(0) rotateX(0); }
  }

  .wallet-ticket::before {
    content: '';
    position: absolute;
    inset: 0;
    background:
      radial-gradient(circle at 80% 0%, rgba(232, 255, 26, 0.12) 0%, transparent 50%),
      url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 200 200'><g fill='none' stroke='%23e8ff1a' stroke-width='0.5' opacity='0.08'><path d='M0 100 Q 50 50 100 100 T 200 100'/><path d='M0 150 Q 50 100 100 150 T 200 150'/><path d='M0 50 Q 50 0 100 50 T 200 50'/></g></svg>");
    background-size: cover, 200px 200px;
    pointer-events: none;
  }

  .ticket-header {
    padding: 20px 22px 16px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: relative;
    z-index: 2;
  }
  .ticket-header .event-label {
    font-size: 10px;
    letter-spacing: 2.5px;
    color: var(--text-muted);
    text-transform: uppercase;
    margin-bottom: 4px;
  }
  .ticket-header .event-name {
    font-size: 22px;
    font-weight: 800;
    letter-spacing: -0.02em;
    color: var(--text-white);
  }
  .ticket-header .event-name .yellow {
    color: var(--neon-yellow);
    font-style: italic;
  }
  .ticket-header .ticket-status {
    font-size: 10px;
    font-weight: 700;
    letter-spacing: 1.5px;
    color: var(--neon-yellow);
    padding: 5px 9px;
    border: 1px solid var(--neon-yellow);
    border-radius: 6px;
  }

  .ticket-divider {
    position: relative;
    height: 1px;
    margin: 0 22px;
    background: repeating-linear-gradient(90deg, rgba(232,255,26,0.25) 0, rgba(232,255,26,0.25) 4px, transparent 4px, transparent 8px);
  }
  .ticket-divider::before,
  .ticket-divider::after {
    content: '';
    position: absolute;
    top: 50%;
    width: 18px;
    height: 18px;
    background: var(--jungle-deep);
    border-radius: 50%;
    transform: translateY(-50%);
  }
  .ticket-divider::before { left: -31px; }
  .ticket-divider::after { right: -31px; }

  .ticket-body {
    padding: 22px 22px 18px;
    position: relative;
    z-index: 2;
  }
  .ticket-row {
    display: flex;
    justify-content: space-between;
    gap: 12px;
    margin-bottom: 16px;
  }
  .ticket-info-block .label {
    font-size: 9px;
    letter-spacing: 2px;
    color: var(--text-muted);
    text-transform: uppercase;
    margin-bottom: 4px;
  }
  .ticket-info-block .value {
    font-size: 15px;
    font-weight: 700;
    color: var(--text-white);
  }
  .ticket-info-block .value.highlight {
    color: var(--neon-yellow);
  }

  .ticket-attendee {
    text-align: left;
    margin-bottom: 18px;
  }
  .ticket-attendee .label {
    font-size: 9px;
    letter-spacing: 2px;
    color: var(--text-muted);
    text-transform: uppercase;
    margin-bottom: 5px;
  }
  .ticket-attendee .name {
    font-size: 26px;
    font-weight: 800;
    letter-spacing: -0.02em;
    color: var(--text-white);
    line-height: 1.1;
  }

  .qr-block {
    background: #fff;
    padding: 14px;
    border-radius: 12px;
    width: fit-content;
    margin: 4px auto 14px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  #qrcode img, #qrcode canvas {
    display: block;
    width: 140px !important;
    height: 140px !important;
  }

  .ticket-id {
    text-align: center;
    font-family: 'SF Mono', 'Courier New', monospace;
    font-size: 11px;
    letter-spacing: 1.5px;
    color: var(--text-muted);
    padding-bottom: 6px;
  }

  .ticket-footer {
    padding: 14px 22px 18px;
    border-top: 1px dashed rgba(232,255,26,0.15);
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 12px;
    position: relative;
    z-index: 2;
  }
  .ticket-footer .project-by {
    font-size: 9px;
    letter-spacing: 1.5px;
    color: var(--text-muted);
    text-transform: uppercase;
  }
  .ticket-footer .gdetails-logo {
    height: 14px;
    width: auto;
    filter: invert(1) brightness(1.5);
    opacity: 0.85;
  }

  /* Apple Wallet button */
  .wallet-btn {
    width: 100%;
    max-width: 360px;
    background: #000;
    color: #fff;
    border: 1px solid rgba(255,255,255,0.2);
    border-radius: 14px;
    padding: 14px 20px;
    font-size: 15px;
    font-weight: 500;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    transition: all 0.2s ease;
    font-family: -apple-system, system-ui, sans-serif;
  }
  .wallet-btn:hover {
    background: #1a1a1a;
    border-color: rgba(255,255,255,0.4);
    transform: translateY(-1px);
  }
  .wallet-btn:active { transform: translateY(0); }
  .wallet-btn svg { width: 22px; height: 22px; }

  /* ========== UTILITIES ========== */
  .hidden { display: none !important; }

  /* Mobile-specific tweaks */
  @media (max-width: 360px) {
    .app { padding: 22px 18px 30px; }
    .display-title { font-size: 36px; }
    .ticket-attendee .name { font-size: 22px; }
  }
</style>
</head>
<body>

  <!-- Decorative layers -->
  <div class="foliage-bg"></div>
  <div class="grain"></div>
  <div class="glow-orb top"></div>
  <div class="glow-orb bottom"></div>

  <div class="app">

    <!-- TOP BAR -->
    <header class="topbar">
      <div class="badge"><span class="live-dot"></span>LIVE EVENT</div>
      <!-- Mini g-details logo (SVG inline) -->
      <svg class="logo-mini" viewBox="0 0 200 32" xmlns="http://www.w3.org/2000/svg" fill="#e8ff1a">
        <text x="0" y="24" font-family="Arial Black, sans-serif" font-weight="900" font-size="22" letter-spacing="1">g·DETAILS</text>
      </svg>
    </header>

    <!-- ========================================== -->
    <!-- SECTION 1: THE GATE                         -->
    <!-- ========================================== -->
    <section class="section active" id="section-gate">
      <div class="gate-hero">
        <h1 class="display-title">
          Break <span class="accent">free.</span><br>
          Discover <span class="accent">more.</span>
        </h1>
        <p class="subtitle">
          Dimostra di essere pronto. Carica un selfie in cui indossi i tuoi occhiali per accedere.
        </p>

        <div class="gate-frame" id="gateFrame">
          <span class="corner tl"></span>
          <span class="corner tr"></span>
          <span class="corner bl"></span>
          <span class="corner br"></span>
          <div class="scan-line"></div>
          <svg class="gate-icon" id="gateIcon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
            <circle cx="6.5" cy="14" r="3.5"/>
            <circle cx="17.5" cy="14" r="3.5"/>
            <path d="M10 14 L 14 14"/>
            <path d="M3 10 L 4 9 M 21 10 L 20 9"/>
            <path d="M9 7 Q 12 5 15 7"/>
          </svg>
          <img class="preview-img hidden" id="previewImg" alt="">
        </div>

        <!-- Loader -->
        <div class="loader-box" id="loaderBox">
          <div class="loader-ring"></div>
          <div class="loader-text" id="loaderText">Analisi del volto in corso...</div>
        </div>

        <!-- Success -->
        <div class="success-box" id="successBox">
          <div class="success-check">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round">
              <polyline points="20 6 9 17 4 12"/>
            </svg>
          </div>
          <div class="success-text">Occhiali rilevati! Accesso consentito</div>
        </div>

        <!-- Upload button -->
        <label class="upload-btn" id="uploadBtn">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round">
            <path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/>
            <circle cx="12" cy="13" r="4"/>
          </svg>
          CARICA SELFIE
          <input type="file" id="fileInput" accept="image/*">
        </label>
      </div>
    </section>

    <!-- ========================================== -->
    <!-- SECTION 2: REGISTRATION                     -->
    <!-- ========================================== -->
    <section class="section" id="section-form">
      <h1 class="display-title">
        Sei <span class="accent">dentro.</span><br>
        Registrati.
      </h1>
      <p class="subtitle">
        Inseriti i tuoi dati per generare il tuo ticket digitale personale.
      </p>

      <form class="form-wrap" id="regForm" autocomplete="off">
        <div class="field">
          <label for="firstName">Nome</label>
          <input type="text" id="firstName" placeholder="Il tuo nome" required>
        </div>
        <div class="field">
          <label for="lastName">Cognome</label>
          <input type="text" id="lastName" placeholder="Il tuo cognome" required>
        </div>
        <div class="field">
          <label for="email">Email</label>
          <input type="email" id="email" placeholder="nome@email.com" required>
        </div>
        <div class="field">
          <label for="birthDate">Data di Nascita</label>
          <input type="date" id="birthDate" required>
        </div>
        <button type="submit" class="submit-btn">Genera il tuo Ticket</button>
      </form>
    </section>

    <!-- ========================================== -->
    <!-- SECTION 3: DIGITAL TICKET                   -->
    <!-- ========================================== -->
    <section class="section ticket-section" id="section-ticket">
      <div class="ticket-intro">
        <h2>Il tuo ticket è pronto</h2>
        <p>Mostralo all'ingresso per accedere all'evento</p>
      </div>

      <div class="wallet-ticket">
        <div class="ticket-header">
          <div>
            <div class="event-label">Evento</div>
            <div class="event-name">Break <span class="yellow">Free</span></div>
          </div>
          <div class="ticket-status">VALID</div>
        </div>

        <div class="ticket-divider"></div>

        <div class="ticket-body">
          <div class="ticket-attendee">
            <div class="label">Partecipante</div>
            <div class="name" id="attendeeName">—</div>
          </div>

          <div class="ticket-row">
            <div class="ticket-info-block">
              <div class="label">Data</div>
              <div class="value">25 GIU 2026</div>
            </div>
            <div class="ticket-info-block">
              <div class="label">Ora</div>
              <div class="value">21:00</div>
            </div>
            <div class="ticket-info-block">
              <div class="label">Posto</div>
              <div class="value highlight">VIP</div>
            </div>
          </div>

          <div class="qr-block">
            <div id="qrcode"></div>
          </div>

          <div class="ticket-id" id="ticketId">#BF-000000</div>
        </div>

        <div class="ticket-footer">
          <span class="project-by">A project by</span>
          <!-- g-details logo inline SVG -->
          <svg class="gdetails-logo" viewBox="0 0 280 50" xmlns="http://www.w3.org/2000/svg">
            <g fill="none" stroke="#000" stroke-width="3.5" stroke-linecap="square">
              <!-- letter g -->
              <circle cx="20" cy="28" r="13" fill="none"/>
              <line x1="33" y1="28" x2="33" y2="46"/>
              <line x1="33" y1="46" x2="20" y2="46"/>
              <!-- dot -->
              <circle cx="45" cy="38" r="2.5" fill="#000"/>
              <!-- D -->
              <line x1="55" y1="14" x2="55" y2="42"/>
              <line x1="55" y1="14" x2="68" y2="14"/>
              <line x1="55" y1="42" x2="68" y2="42"/>
              <path d="M68 14 Q 82 14 82 28 Q 82 42 68 42"/>
              <!-- E -->
              <line x1="90" y1="14" x2="90" y2="42"/>
              <line x1="90" y1="14" x2="108" y2="14"/>
              <line x1="90" y1="28" x2="104" y2="28"/>
              <line x1="90" y1="42" x2="108" y2="42"/>
              <!-- T -->
              <line x1="115" y1="14" x2="135" y2="14"/>
              <line x1="125" y1="14" x2="125" y2="42"/>
              <!-- A -->
              <line x1="142" y1="42" x2="152" y2="14"/>
              <line x1="152" y1="14" x2="162" y2="42"/>
              <line x1="146" y1="32" x2="158" y2="32"/>
              <!-- I -->
              <line x1="170" y1="14" x2="170" y2="42"/>
              <!-- L -->
              <line x1="180" y1="14" x2="180" y2="42"/>
              <line x1="180" y1="42" x2="196" y2="42"/>
              <!-- S -->
              <path d="M218 16 Q 204 16 204 24 Q 204 30 215 30 Q 226 30 226 36 Q 226 42 212 42"/>
              <!-- ® -->
              <circle cx="240" cy="18" r="6" stroke-width="1.5"/>
              <text x="237" y="22" font-family="Arial" font-size="9" fill="#000" stroke="none">R</text>
            </g>
          </svg>
        </div>
      </div>

      <button class="wallet-btn" id="walletBtn">
        <svg viewBox="0 0 24 24" fill="currentColor">
          <path d="M17.5 12.5c0-1.7.9-3.1 2.2-4-1-1.4-2.5-2.2-4.2-2.3-1.8-.2-3.5 1-4.4 1-.9 0-2.3-1-3.8-1-2 0-3.8 1.1-4.8 2.9-2 3.5-.5 8.7 1.5 11.6 1 1.4 2.1 3 3.6 2.9 1.5-.1 2-.9 3.7-.9 1.7 0 2.2.9 3.7.9 1.5 0 2.5-1.4 3.5-2.8.7-1 1.3-2 1.7-3.1-1.6-.7-2.7-2.3-2.7-4.2zM14.7 4.6c.8-1 1.4-2.3 1.3-3.6-1.1.1-2.4.7-3.2 1.7-.7.8-1.4 2.1-1.2 3.4 1.2.1 2.4-.6 3.1-1.5z"/>
        </svg>
        Aggiungi a Apple Wallet
      </button>
    </section>

  </div>

<script>
  // ============================================
  // STATE
  // ============================================
  const state = {
    firstName: '',
    lastName: '',
    email: '',
    birthDate: '',
    ticketId: ''
  };

  // ============================================
  // SECTION SWITCHING
  // ============================================
  function showSection(id) {
    document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
    document.getElementById(id).classList.add('active');
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  // ============================================
  // SECTION 1: GATE LOGIC
  // ============================================
  const fileInput = document.getElementById('fileInput');
  const uploadBtn = document.getElementById('uploadBtn');
  const gateFrame = document.getElementById('gateFrame');
  const gateIcon = document.getElementById('gateIcon');
  const previewImg = document.getElementById('previewImg');
  const loaderBox = document.getElementById('loaderBox');
  const successBox = document.getElementById('successBox');
  const loaderText = document.getElementById('loaderText');

  fileInput.addEventListener('change', (e) => {
    const file = e.target.files[0];
    if (!file) return;

    // Show preview
    const reader = new FileReader();
    reader.onload = (ev) => {
      previewImg.src = ev.target.result;
      previewImg.classList.remove('hidden');
      gateIcon.classList.add('hidden');
      gateFrame.classList.add('has-image');
    };
    reader.readAsDataURL(file);

    // Hide upload button, start "AI analysis"
    uploadBtn.style.display = 'none';
    loaderBox.classList.add('active');
    gateFrame.classList.add('scanning');

    // Step 1: face analysis
    loaderText.textContent = 'Analisi del volto in corso...';

    setTimeout(() => {
      loaderText.textContent = 'Verifica occhiali...';
    }, 1000);

    // Step 2: success after 2s
    setTimeout(() => {
      loaderBox.classList.remove('active');
      gateFrame.classList.remove('scanning');
      successBox.classList.add('active');

      // Auto-advance to section 2 after 1.5s
      setTimeout(() => {
        showSection('section-form');
      }, 1500);
    }, 2000);
  });

  // ============================================
  // SECTION 2: REGISTRATION FORM
  // ============================================
  const regForm = document.getElementById('regForm');
  regForm.addEventListener('submit', (e) => {
    e.preventDefault();
    state.firstName = document.getElementById('firstName').value.trim();
    state.lastName = document.getElementById('lastName').value.trim();
    state.email = document.getElementById('email').value.trim();
    state.birthDate = document.getElementById('birthDate').value;

    // Generate random ticket ID
    state.ticketId = '#BF-' + Math.random().toString(36).substring(2, 8).toUpperCase();

    // Populate ticket
    document.getElementById('attendeeName').textContent =
      `${state.firstName} ${state.lastName}`.toUpperCase();
    document.getElementById('ticketId').textContent = state.ticketId;

    // Generate QR code
    const qrContainer = document.getElementById('qrcode');
    qrContainer.innerHTML = ''; // clear if any
    new QRCode(qrContainer, {
      text: `BREAKFREE|${state.firstName} ${state.lastName}|${state.email}|${state.ticketId}`,
      width: 140,
      height: 140,
      colorDark: '#000000',
      colorLight: '#ffffff',
      correctLevel: QRCode.CorrectLevel.H
    });

    showSection('section-ticket');
  });

  // ============================================
  // SECTION 3: APPLE WALLET BUTTON
  // ============================================
  document.getElementById('walletBtn').addEventListener('click', () => {
    alert('Ticket salvato nel tuo Wallet!');
  });
</script>

</body>
</html>
