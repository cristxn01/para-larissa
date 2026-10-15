
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#170811">
  <meta name="description" content="Uma declaração especial de Cristiano para Larissa.">
  <title>Cristiano ♥ Larissa | Uma declaração especial</title>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=DM+Sans:wght@400;500;600;700&family=Great+Vibes&display=swap');

    :root {
      --bg: #10070d;
      --bg-light: #1d0b17;
      --wine: #641b3b;
      --pink: #f5a9c8;
      --pink-light: #ffdce9;
      --gold: #e8c28b;
      --white: #fff8fb;
      --muted: #c9aebc;
      --glass: rgba(255, 238, 246, 0.055);
      --border: rgba(255, 218, 235, 0.15);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
      scroll-padding-top: 80px;
    }

    body {
      min-height: 100vh;
      overflow-x: hidden;
      color: var(--white);
      background:
        radial-gradient(ellipse at 15% 10%, #3b1028 0, transparent 35%),
        radial-gradient(ellipse at 90% 45%, #2c1023 0, transparent 32%),
        linear-gradient(160deg, #10070d, #1b0915 55%, #10070d);
      font-family: "DM Sans", sans-serif;
    }

    body::before {
      content: "";
      position: fixed;
      inset: 0;
      z-index: -1;
      pointer-events: none;
      opacity: 0.12;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 180 180' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.9' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='.2'/%3E%3C/svg%3E");
    }

    button {
      font: inherit;
    }

    button:focus-visible,
    a:focus-visible {
      outline: 2px solid var(--gold);
      outline-offset: 5px;
    }

    button,
    a {
      -webkit-tap-highlight-color: transparent;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .stars,
    .hearts-layer {
      position: fixed;
      inset: 0;
      z-index: 0;
      overflow: hidden;
      pointer-events: none;
    }

    .star {
      position: absolute;
      width: 2px;
      height: 2px;
      border-radius: 50%;
      background: #fff;
      opacity: 0.4;
      animation: twinkle var(--duration, 3s) ease-in-out infinite alternate;
    }

    @keyframes twinkle {
      from { opacity: 0.15; transform: scale(0.7); }
      to { opacity: 0.85; transform: scale(1.4); }
    }

    .floating-heart {
      position: absolute;
      bottom: -40px;
      color: var(--pink);
      opacity: 0;
      animation: floatUp 8s linear forwards;
    }

    @keyframes floatUp {
      0% { transform: translateY(0) rotate(0deg); opacity: 0; }
      15% { opacity: 0.4; }
      85% { opacity: 0.3; }
      100% { transform: translateY(-110vh) rotate(30deg); opacity: 0; }
    }

    .site-header,
    main,
    footer {
      position: relative;
      z-index: 1;
    }

    .site-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 20px;
      max-width: 1180px;
      padding: 26px 28px;
      margin: auto;
    }

    .brand {
      font-family: "Cormorant Garamond", serif;
      font-size: 1.25rem;
      letter-spacing: 1px;
    }

    .brand span {
      color: var(--pink);
    }

    .header-note {
      color: var(--muted);
      font-size: 0.76rem;
      letter-spacing: 2px;
      text-transform: uppercase;
    }

    .hero {
      min-height: 85vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 65px 24px 100px;
    }

    .eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      color: var(--gold);
      font-size: 0.7rem;
      letter-spacing: 3px;
      text-transform: uppercase;
      margin-bottom: 25px;
    }

    .eyebrow::before,
    .eyebrow::after {
      content: "";
      display: block;
      width: 30px;
      height: 1px;
      background: var(--gold);
      opacity: 0.65;
    }

    .hero h1 {
      font-family: "Cormorant Garamond", serif;
      font-weight: 400;
      font-size: clamp(3.3rem, 9vw, 7.6rem);
      line-height: 0.96;
      letter-spacing: -2px;
      text-wrap: balance;
    }

    .hero h1 .name {
      display: block;
      color: var(--pink-light);
      text-shadow: 0 0 45px rgba(245, 169, 200, 0.16);
    }

    .hero h1 .ampersand {
      display: block;
      color: var(--gold);
      font-family: "Great Vibes", cursive;
      font-size: clamp(3rem, 8vw, 6rem);
      line-height: 1.25;
      letter-spacing: 0;
    }

    .hero-subtitle {
      max-width: 510px;
      color: var(--muted);
      font-size: clamp(0.92rem, 2vw, 1.08rem);
      line-height: 1.9;
      margin-top: 28px;
    }

    .hero-subtitle strong {
      color: var(--pink-light);
      font-weight: 500;
    }

    .hero-actions {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 13px;
      margin-top: 34px;
    }

    .button {
      min-height: 49px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 9px;
      padding: 13px 23px;
      border: 1px solid var(--border);
      border-radius: 999px;
      color: var(--white);
      background: rgba(255, 255, 255, 0.035);
      cursor: pointer;
      transition: transform 0.25s ease, background 0.25s ease,
        border-color 0.25s ease, box-shadow 0.25s ease;
    }

    .button:hover {
      transform: translateY(-3px);
      border-color: rgba(255, 218, 235, 0.4);
      background: rgba(255, 255, 255, 0.08);
    }

    .button-primary {
      color: #260c19;
      border-color: transparent;
      background: linear-gradient(135deg, #ffe2ed, #e9a0bd);
      box-shadow: 0 8px 30px rgba(226, 123, 166, 0.15);
      font-weight: 700;
    }

    .button-primary:hover {
      background: linear-gradient(135deg, #fff0f6, #f5b5cf);
      box-shadow: 0 10px 35px rgba(226, 123, 166, 0.25);
    }

    .scroll-hint {
      position: absolute;
      bottom: 26px;
      display: grid;
      justify-items: center;
      gap: 9px;
      color: #b79aaa;
      font-size: 0.68rem;
      letter-spacing: 2px;
      text-transform: uppercase;
    }

    .scroll-hint span {
      animation: bob 1.6s ease-in-out infinite;
      font-size: 1.15rem;
    }

    @keyframes bob {
      50% { transform: translateY(5px); }
    }

    .section {
      width: min(100% - 40px, 900px);
      margin: 0 auto;
      padding: 95px 0;
    }

    .section-heading {
      text-align: center;
      margin-bottom: 40px;
    }

    .section-heading .eyebrow {
      margin-bottom: 16px;
    }

    .section-heading h2 {
      font-family: "Cormorant Garamond", serif;
      font-weight: 500;
      font-size: clamp(2.4rem, 6vw, 4rem);
      line-height: 1.1;
    }

    .section-heading p {
      max-width: 510px;
      color: var(--muted);
      margin: 14px auto 0;
      line-height: 1.8;
      font-size: 0.95rem;
    }

    .letter-card {
      position: relative;
      overflow: hidden;
      padding: clamp(25px, 6vw, 58px);
      border: 1px solid var(--border);
      border-radius: 25px;
      background: linear-gradient(145deg, rgba(255,255,255,0.065), rgba(255,255,255,0.018));
      box-shadow: 0 20px 80px rgba(0,0,0,0.18);
    }

    .letter-card::before {
      content: "♡";
      position: absolute;
      right: 17px;
      top: -33px;
      color: rgba(245, 169, 200, 0.07);
      font-family: Georgia, serif;
      font-size: 12rem;
      line-height: 1;
      pointer-events: none;
    }

    .letter-top {
      display: flex;
      align-items: center;
      gap: 10px;
      color: var(--gold);
      font-size: 0.75rem;
      letter-spacing: 2px;
      text-transform: uppercase;
      margin-bottom: 30px;
    }

    .letter-content {
      position: relative;
      color: #e7d4df;
      font-family: "Cormorant Garamond", serif;
      font-size: clamp(1.2rem, 3vw, 1.55rem);
      line-height: 1.9;
    }

    .letter-content p + p {
      margin-top: 18px;
    }

    .letter-content strong {
      color: var(--pink-light);
      font-weight: 600;
    }

    .letter-signature {
      color: var(--pink);
      font-family: "Great Vibes", cursive;
      font-size: 2.8rem;
      margin-top: 28px;
      text-align: right;
    }

    .reasons-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 16px;
    }

    .reason-card {
      min-height: 195px;
      padding: 26px 21px;
      border: 1px solid var(--border);
      border-radius: 20px;
      background: var(--glass);
      transition: transform 0.3s ease, border-color 0.3s ease,
        background 0.3s ease;
    }

    .reason-card:hover {
      transform: translateY(-6px);
      border-color: rgba(245, 169, 200, 0.38);
      background: rgba(255, 238, 246, 0.085);
    }

    .reason-icon {
      display: block;
      font-size: 1.65rem;
      margin-bottom: 20px;
    }

    .reason-card h3 {
      font-family: "Cormorant Garamond", serif;
      color: var(--pink-light);
      font-size: 1.45rem;
      font-weight: 600;
      margin-bottom: 9px;
    }

    .reason-card p {
      color: var(--muted);
      font-size: 0.87rem;
      line-height: 1.7;
    }

    .quote-section {
      width: min(100% - 40px, 1000px);
      margin: 35px auto;
      padding: 75px 25px;
      text-align: center;
      border-top: 1px solid var(--border);
      border-bottom: 1px solid var(--border);
    }

    .quote-mark {
      color: var(--gold);
      font-family: Georgia, serif;
      font-size: 4rem;
      line-height: 0.8;
      opacity: 0.8;
    }

    .quote-text {
      max-width: 790px;
      margin: 22px auto;
      font-family: "Cormorant Garamond", serif;
      font-size: clamp(2rem, 5.5vw, 3.7rem);
      line-height: 1.25;
      color: var(--pink-light);
    }

    .quote-credit {
      color: var(--muted);
      font-size: 0.78rem;
      letter-spacing: 2px;
      text-transform: uppercase;
    }

    .surprise-box {
      padding: clamp(30px, 6vw, 60px) 24px;
      text-align: center;
      border: 1px solid rgba(232, 194, 139, 0.2);
      border-radius: 26px;
      background:
        radial-gradient(ellipse at top, rgba(232,194,139,0.08), transparent 70%),
        rgba(255,255,255,0.025);
    }

    .surprise-icon {
      font-size: 2.8rem;
      margin-bottom: 15px;
      display: block;
    }

    .surprise-box h2 {
      font-family: "Cormorant Garamond", serif;
      font-size: clamp(2.3rem, 6vw, 3.6rem);
      font-weight: 500;
    }

    .surprise-box > p {
      max-width: 470px;
      margin: 14px auto 25px;
      color: var(--muted);
      line-height: 1.8;
    }

    .surprise-message {
      display: none;
      max-width: 590px;
      margin: 28px auto 0;
      padding: 25px;
      border-radius: 18px;
      border: 1px solid var(--border);
      background: rgba(0,0,0,0.15);
      animation: reveal 0.7s ease both;
    }

    .surprise-message.visible {
      display: block;
    }

    .surprise-message p {
      color: var(--pink-light);
      font-family: "Cormorant Garamond", serif;
      font-size: clamp(1.35rem, 3.5vw, 1.8rem);
      line-height: 1.7;
    }

    .surprise-message .final-heart {
      display: block;
      margin-top: 17px;
      font-size: 1.7rem;
    }

    @keyframes reveal {
      from { opacity: 0; transform: translateY(15px) scale(0.98); }
      to { opacity: 1; transform: translateY(0) scale(1); }
    }

    .closing {
      padding: 105px 24px 90px;
      text-align: center;
    }

    .closing .small-heart {
      display: block;
      color: var(--pink);
      font-size: 1.7rem;
      margin-bottom: 22px;
      animation: heartbeat 1.7s ease-in-out infinite;
    }

    @keyframes heartbeat {
      0%, 100% { transform: scale(1); }
      15% { transform: scale(1.15); }
      30% { transform: scale(1); }
      45% { transform: scale(1.1); }
    }

    .closing h2 {
      font-family: "Cormorant Garamond", serif;
      font-size: clamp(2.7rem, 8vw, 5.8rem);
      line-height: 1.1;
      font-weight: 400;
    }

    .closing h2 span {
      display: block;
      color: var(--pink);
      font-family: "Great Vibes", cursive;
      font-size: clamp(4rem, 12vw, 8rem);
      margin-top: 8px;
    }

    .closing p {
      max-width: 490px;
      margin: 25px auto 0;
      color: var(--muted);
      line-height: 1.9;
    }

    footer {
      padding: 25px 20px 32px;
      text-align: center;
      border-top: 1px solid rgba(255,255,255,0.07);
      color: #9d8291;
      font-size: 0.78rem;
      line-height: 1.8;
    }

    footer span {
      color: var(--pink);
    }

    .sound-toggle {
      position: fixed;
      right: 20px;
      bottom: 20px;
      z-index: 5;
      display: flex;
      align-items: center;
      gap: 9px;
      padding: 12px 16px;
      color: var(--white);
      border: 1px solid var(--border);
      border-radius: 999px;
      background: rgba(29, 11, 23, 0.88);
      backdrop-filter: blur(12px);
      cursor: pointer;
      font-size: 0.8rem;
      box-shadow: 0 5px 25px rgba(0,0,0,0.2);
    }

    .sound-toggle:hover {
      background: rgba(77, 26, 51, 0.95);
    }

    .sound-toggle .sound-icon {
      font-size: 1rem;
    }

    .toast {
      position: fixed;
      z-index: 10;
      left: 50%;
      bottom: 85px;
      width: max-content;
      max-width: calc(100% - 32px);
      padding: 13px 20px;
      border: 1px solid var(--border);
      border-radius: 999px;
      color: var(--white);
      background: #321325;
      box-shadow: 0 8px 35px rgba(0,0,0,0.3);
      text-align: center;
      font-size: 0.86rem;
      opacity: 0;
      pointer-events: none;
      transform: translate(-50%, 12px);
      transition: opacity 0.3s ease, transform 0.3s ease;
    }

    .toast.show {
      opacity: 1;
      transform: translate(-50%, 0);
    }

    .reveal-on-scroll {
      opacity: 0;
      transform: translateY(24px);
      transition: opacity 0.8s ease, transform 0.8s ease;
    }

    .reveal-on-scroll.revealed {
      opacity: 1;
      transform: translateY(0);
    }

    @media (max-width: 700px) {
      .site-header {
        padding: 20px 19px;
      }

      .header-note {
        font-size: 0.61rem;
        letter-spacing: 1px;
      }

      .hero {
        min-height: 82svh;
        padding: 55px 20px 100px;
      }

      .hero h1 {
        letter-spacing: -1px;
      }

      .section {
        width: min(100% - 32px, 900px);
        padding: 70px 0;
      }

      .reasons-grid {
        grid-template-columns: 1fr;
      }

      .reason-card {
        min-height: 0;
        padding: 23px;
      }

      .reason-icon {
        margin-bottom: 12px;
      }

      .quote-section {
        width: calc(100% - 32px);
        padding: 60px 12px;
      }

      .closing {
        padding: 80px 20px 70px;
      }

      .sound-toggle {
        right: 12px;
        bottom: 12px;
        padding: 11px 13px;
      }

      .toast {
        bottom: 72px;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      *,
      *::before,
      *::after {
        scroll-behavior: auto !important;
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: 0.01ms !important;
      }

      .reveal-on-scroll {
        opacity: 1;
        transform: none;
      }
    }
  </style>
</head>

<body>
  <div class="stars" id="stars" aria-hidden="true"></div>
  <div class="hearts-layer" id="heartsLayer" aria-hidden="true"></div>

  <header class="site-header">
    <a class="brand" href="#inicio" aria-label="Cristiano e Larissa, início">
      C <span>♥</span> L
    </a>
    <p class="header-note">Feito com carinho, para você</p>
  </header>

  <main>
    <!-- ABERTURA -->
    <section class="hero" id="inicio">
      <div class="eyebrow">Uma pequena declaração</div>

      <h1>
        <span class="name">Cristiano</span>
        <span class="ampersand">e</span>
        <span class="name">Larissa</span>
      </h1>

      <p class="hero-subtitle">
        Algumas pessoas tornam o mundo mais bonito
        simplesmente por existirem. <strong>Você é uma delas, Larissa.</strong>
        E estas palavras são para você.
      </p>

      <div class="hero-actions">
        <a class="button button-primary" href="#carta">
          Ler minha carta <span aria-hidden="true">♡</span>
        </a>
        <button class="button" id="surpriseTop" type="button">
          Uma surpresa ✨
        </button>
      </div>

      <a class="scroll-hint" href="#carta">
        Continue lendo
        <span aria-hidden="true">⌄</span>
      </a>
    </section>

    <!-- CARTA -->
    <section class="section reveal-on-scroll" id="carta">
      <div class="section-heading">
        <div class="eyebrow">Palavras do coração</div>
        <h2>Uma carta para você</h2>
        <p>Larissa, existe algo que eu queria te dizer de um jeito especial.</p>
      </div>

      <article class="letter-card">
        <div class="letter-top">
          <span aria-hidden="true">✉</span>
          Uma carta escrita com carinho
        </div>

        <div class="letter-content">
          <p>Minha querida <strong>Larissa</strong>,</p>

          <p>
            Talvez eu não consiga encontrar as palavras perfeitas para
            explicar tudo o que sinto, mas queria que você soubesse que
            é alguém muito especial.
          </p>

          <p>
            Às vezes, são os pequenos detalhes que tornam uma pessoa
            inesquecível: o jeito de falar, o sorriso, a presença e a
            maneira como ela consegue deixar um momento comum mais bonito.
          </p>

          <p>
            Eu não sei o que o futuro reserva, mas sei que quero aproveitar
            as oportunidades de te conhecer melhor, compartilhar momentos
            bons e construir lembranças que façam a gente sorrir.
          </p>

          <p>
            Não quero que estas palavras sejam apenas bonitas.
            Quero que elas transmitam algo verdadeiro:
            <strong>você merece carinho, respeito, sinceridade e felicidade.</strong>
          </p>

          <p>
            Então, se eu pudesse resumir tudo em poucas palavras, diria
            que fico feliz por você existir e por ter a oportunidade
            de te dizer o quanto você é especial.
          </p>

          <p>Com muito carinho,</p>
        </div>

        <div class="letter-signature">Cristiano ♥</div>
      </article>
    </section>

    <!-- PEQUENOS DETALHES -->
    <section class="section reveal-on-scroll" id="detalhes">
      <div class="section-heading">
        <div class="eyebrow">Pequenas grandes coisas</div>
        <h2>O que torna você especial</h2>
        <p>Porque uma declaração bonita também está nas coisas simples.</p>
      </div>

      <div class="reasons-grid">
        <article class="reason-card">
          <span class="reason-icon" aria-hidden="true">🌷</span>
          <h3>Seu jeito</h3>
          <p>
            Existe algo único em cada pessoa. Seu jeito de ser é parte
            daquilo que faz você ser você.
          </p>
        </article>

        <article class="reason-card">
          <span class="reason-icon" aria-hidden="true">✨</span>
          <h3>Seus detalhes</h3>
          <p>
            São os pequenos momentos, os gestos espontâneos e as
            conversas que podem se tornar lembranças especiais.
          </p>
        </article>

        <article class="reason-card">
          <span class="reason-icon" aria-hidden="true">💗</span>
          <h3>O carinho</h3>
          <p>
            Você merece alguém que demonstre afeto com sinceridade,
            respeite seu tempo e valorize quem você é.
          </p>
        </article>
      </div>
    </section>

    <!-- FRASE -->
    <section class="quote-section reveal-on-scroll">
      <div class="quote-mark" aria-hidden="true">“</div>
      <p class="quote-text">
        Se cada estrela fosse uma palavra, ainda faltaria o céu inteiro
        para dizer o quanto alguém pode ser especial.
      </p>
      <p class="quote-credit">Para Larissa, com carinho</p>
    </section>

    <!-- SURPRESA -->
    <section class="section reveal-on-scroll" id="surpresa">
      <div class="surprise-box">
        <span class="surprise-icon" aria-hidden="true">🎁</span>
        <h2>Tem mais uma coisinha...</h2>
        <p>
          Larissa, toque no botão abaixo. Cristiano preparou mais algumas
          palavras especialmente para você.
        </p>

        <button class="button button-primary" id="surpriseButton" type="button">
          Revelar minha surpresa 💌
        </button>

        <div class="surprise-message" id="surpriseMessage" aria-live="polite">
          <p>
            Larissa, eu queria que você pudesse enxergar por alguns
            instantes o quanto é especial. Espero que a vida te dê muitos
            motivos para sorrir e que eu possa fazer parte de alguns desses
            momentos. Obrigado por ser quem você é. 💗
          </p>
          <span class="final-heart" aria-hidden="true">♡</span>
          <p style="margin-top: 12px; font-size: 1.2rem;">
            Com carinho, Cristiano.
          </p>
        </div>
      </div>
    </section>

    <!-- FINAL -->
    <section class="closing reveal-on-scroll" id="final">
      <span class="small-heart" aria-hidden="true">♥</span>
      <div class="eyebrow">De mim para você</div>
      <h2>
        Uma última coisa,
        <span>Larissa...</span>
      </h2>
      <p>
        Independentemente de como seja o amanhã, espero que você nunca
        se esqueça de como é importante e de como merece ser feliz.
        Esta página é uma pequena forma de demonstrar meu carinho por você.
      </p>

      <div style="margin-top: 30px;">
        <button class="button button-primary" id="loveButton" type="button">
          Cristiano ❤️ Larissa
        </button>
      </div>
    </section>
  </main>

  <footer>
    Criado especialmente por <span>Cristiano</span>, para <span>Larissa</span>.
    <br>
    Um pequeno site, um carinho enorme. ♥
  </footer>

  <button class="sound-toggle" id="soundButton" type="button"
          aria-pressed="false" aria-label="Ativar som ambiente">
    <span class="sound-icon" id="soundIcon" aria-hidden="true">♫</span>
    <span id="soundLabel">Som ambiente</span>
  </button>

  <div class="toast" id="toast" role="status" aria-live="polite"></div>

  <script>
    "use strict";

    // ELEMENTOS
    const stars = document.getElementById("stars");
    const heartsLayer = document.getElementById("heartsLayer");
    const surpriseButton = document.getElementById("surpriseButton");
    const surpriseTop = document.getElementById("surpriseTop");
    const surpriseMessage = document.getElementById("surpriseMessage");
    const soundButton = document.getElementById("soundButton");
    const soundLabel = document.getElementById("soundLabel");
    const soundIcon = document.getElementById("soundIcon");
    const loveButton = document.getElementById("loveButton");
    const toast = document.getElementById("toast");

    // ESTRELAS DO FUNDO
    function createStars() {
      const fragment = document.createDocumentFragment();
      const total = window.innerWidth < 600 ? 65 : 110;

      for (let i = 0; i < total; i++) {
        const star = document.createElement("span");
        star.className = "star";
        star.style.left = Math.random() * 100 + "%";
        star.style.top = Math.random() * 100 + "%";
        star.style.setProperty("--duration", (2 + Math.random() * 4) + "s");
        star.style.animationDelay = (Math.random() * 4) + "s";

        const size = Math.random() > 0.88 ? 3 : 2;
        star.style.width = size + "px";
        star.style.height = size + "px";

        fragment.appendChild(star);
      }

      stars.replaceChildren(fragment);
    }

    createStars();

    // CORAÇÕES FLUTUANTES
    function createFloatingHeart() {
      if (document.hidden) return;

      const heart = document.createElement("span");
      heart.className = "floating-heart";
      heart.textContent = Math.random() > 0.5 ? "♡" : "♥";
      heart.style.left = Math.random() * 100 + "%";
      heart.style.fontSize = (12 + Math.random() * 18) + "px";
      heart.style.animationDuration = (6 + Math.random() * 5) + "s";

      heartsLayer.appendChild(heart);

      heart.addEventListener("animationend", () => heart.remove(), {
        once: true
      });
    }

    const heartInterval = window.setInterval(createFloatingHeart, 1100);

    // MENSAGEM TEMPORÁRIA
    let toastTimeout;

    function showToast(message) {
      toast.textContent = message;
      toast.classList.add("show");

      window.clearTimeout(toastTimeout);
      toastTimeout = window.setTimeout(() => {
        toast.classList.remove("show");
      }, 3000);
    }

    // REVELAR A SURPRESA
    function revealSurprise() {
      surpriseMessage.classList.add("visible");
      surpriseButton.textContent = "Surpresa revelada ♥";
      surpriseButton.setAttribute("aria-expanded", "true");

      surpriseMessage.scrollIntoView({
        behavior: window.matchMedia("(prefers-reduced-motion: reduce)").matches
          ? "auto"
          : "smooth",
        block: "center"
      });

      burstHearts(18);
    }

    surpriseButton.addEventListener("click", revealSurprise);

    surpriseTop.addEventListener("click", () => {
      document.getElementById("surpresa").scrollIntoView({
        behavior: "smooth"
      });
      window.setTimeout(revealSurprise, 350);
    });

    // EFEITO DE CORAÇÕES AO CLICAR
    function burstHearts(amount = 12) {
      const symbols = ["♥", "♡", "✦", "❤"];

      for (let i = 0; i < amount; i++) {
        const heart = document.createElement("span");
        heart.className = "floating-heart";
        heart.textContent = symbols[Math.floor(Math.random() * symbols.length)];
        heart.style.left = (15 + Math.random() * 70) + "%";
        heart.style.bottom = "15%";
        heart.style.fontSize = (14 + Math.random() * 20) + "px";
        heart.style.animationDuration = (3 + Math.random() * 3) + "s";

        heartsLayer.appendChild(heart);

        heart.addEventListener("animationend", () => heart.remove(), {
          once: true
        });
      }
    }

    loveButton.addEventListener("click", () => {
      burstHearts(28);
      showToast("Cristiano ❤️ Larissa — feito com carinho!");
    });

    // ANIMAÇÕES AO ROLAR A PÁGINA
    const revealElements = document.querySelectorAll(".reveal-on-scroll");

    if ("IntersectionObserver" in window) {
      const observer = new IntersectionObserver((entries, currentObserver) => {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            entry.target.classList.add("revealed");
            currentObserver.unobserve(entry.target);
          }
        });
      }, {
        threshold: 0.12
      });

      revealElements.forEach(element => observer.observe(element));
    } else {
      revealElements.forEach(element => element.classList.add("revealed"));
    }

    // SOM AMBIENTE GERADO PELO NAVEGADOR
    // O som começa somente depois que a pessoa toca no botão.
    let audioContext = null;
    let masterGain = null;
    let soundEnabled = false;
    let notesTimer = null;
    let nextNoteTime = 0;
    let noteIndex = 0;

    const melody = [
      261.63, 329.63, 392.00, 329.63,
      293.66, 349.23, 440.00, 349.23,
      261.63, 329.63, 392.00, 523.25
    ];

    function playNote(frequency, startTime, duration = 1.5) {
      if (!audioContext || !masterGain) return;

      const oscillator = audioContext.createOscillator();
      const gain = audioContext.createGain();

      oscillator.type = "sine";
      oscillator.frequency.setValueAtTime(frequency, startTime);

      gain.gain.setValueAtTime(0.0001, startTime);
      gain.gain.exponentialRampToValueAtTime(0.045, startTime + 0.12);
      gain.gain.exponentialRampToValueAtTime(0.0001, startTime + duration);

      oscillator.connect(gain);
      gain.connect(masterGain);

      oscillator.start(startTime);
      oscillator.stop(startTime + duration + 0.05);
    }

    function scheduleNotes() {
      if (!audioContext || !soundEnabled) return;

      while (nextNoteTime < audioContext.currentTime + 1.5) {
        playNote(melody[noteIndex % melody.length], nextNoteTime, 1.3);
        noteIndex++;
        nextNoteTime += 0.72;
      }
    }

    async function toggleSound() {
      try {
        if (!soundEnabled) {
          const AudioContextClass =
            window.AudioContext || window.webkitAudioContext;

          if (!AudioContextClass) {
            showToast("Seu navegador não oferece suporte a som ambiente.");
            return;
          }

          if (!audioContext) {
            audioContext = new AudioContextClass();
            masterGain = audioContext.createGain();
            masterGain.gain.value = 0.35;
            masterGain.connect(audioContext.destination);
          }

          if (audioContext.state === "suspended") {
            await audioContext.resume();
          }

          soundEnabled = true;
          nextNoteTime = audioContext.currentTime + 0.1;
          scheduleNotes();
          notesTimer = window.setInterval(scheduleNotes, 250);

          soundLabel.textContent = "Desativar som";
          soundIcon.textContent = "♫";
          soundButton.setAttribute("aria-pressed", "true");
          soundButton.setAttribute("aria-label", "Desativar som ambiente");
        } else {
          soundEnabled = false;

          if (notesTimer !== null) {
            window.clearInterval(notesTimer);
            notesTimer = null;
          }

          if (audioContext && masterGain) {
            masterGain.gain.setTargetAtTime(
              0.0001,
              audioContext.currentTime,
              0.05
            );
          }

          soundLabel.textContent = "Som ambiente";
          soundIcon.textContent = "♪";
          soundButton.setAttribute("aria-pressed", "false");
          soundButton.setAttribute("aria-label", "Ativar som ambiente");
        }
      } catch (error) {
        soundEnabled = false;
        soundLabel.textContent = "Som ambiente";
        soundButton.setAttribute("aria-pressed", "false");
        showToast("Não foi possível iniciar o som neste navegador.");
      }
    }

    soundButton.addEventListener("click", toggleSound);

    // REDUZ TRABALHO QUANDO A ABA NÃO ESTÁ VISÍVEL
    document.addEventListener("visibilitychange", () => {
      if (document.hidden) {
        window.clearInterval(heartInterval);
      }
    });
  </script>
</body>
</html>
