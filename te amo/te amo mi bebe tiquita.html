<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Te Amo Mi Bebe Hermosa</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body { background-color: black; overflow: hidden; }

    .terminal {
      position: fixed;
      top: 0; left: 0;
      width: 100vw; height: 100vh;
      overflow: hidden;
      z-index: 1;
    }

    .text-container {
      position: absolute;
      width: 100%;
      color: #ff1493;
      font-family: 'Courier New', monospace;
      font-size: 24px;
      text-shadow: 0 0 15px #ff69b4;
      line-height: 1.2;
      opacity: 0.9;
      animation: matrixGlow 2s infinite;
      mix-blend-mode: screen;
    }

    @keyframes matrixGlow {
      0%, 100% { opacity: 0.7; text-shadow: 0 0 15px #ff69b4; }
      50%       { opacity: 1;   text-shadow: 0 0 25px #ff1493; }
    }

    @keyframes scroll {
      0%   { transform: translateY(100vh); }
      100% { transform: translateY(-100%); }
    }

    .love-container {
      position: fixed;
      top: 0; left: 0;
      width: 100vw; height: 100vh;
      z-index: 2;
      pointer-events: none;
    }

    .love-text {
      position: absolute;
      color: #ffd7ff;
      font-size: 1.8rem;
      opacity: 0;
      text-shadow: 0 0 25px rgba(255,105,180,0.8);
      animation: caidaHolografica 10s cubic-bezier(0.17,0.67,0.45,0.99) infinite;
      mix-blend-mode: screen;
    }

    @keyframes caidaHolografica {
      0%   { transform: translate3d(-50%,-120vh,100px)  rotate3d(1,0.2,0.5,15deg)  scale(1.2); opacity: 0; }
      20%  { opacity: 1; filter: hue-rotate(0deg); }
      80%  { opacity: 0.8; }
      100% { transform: translate3d(50%,120vh,-200px)   rotate3d(0.5,1,0.2,-15deg) scale(0.8); opacity: 0; }
    }

    .centro {
      position: fixed;
      text-align: center;
      top: 50%; left: 50%;
      transform: translate(-50%, -50%);
      font-size: 5rem;
      color: transparent;
      background: linear-gradient(45deg, #ff69b4 20%, #ffd700 45%, #ff69b4 70%);
      -webkit-background-clip: text;
      background-clip: text;
      text-shadow: 0 0 60px rgba(255,105,180,0.6);
      animation: brilloPerpetuo 3s ease-in-out infinite;
      font-family: 'Courier New', monospace;
      z-index: 3;
      padding: 20px 40px;
      border: 2px solid rgba(255,215,0,0.3);
      border-radius: 15px;
      backdrop-filter: blur(12px);
      cursor: pointer;
      transition: transform 0.5s;
      white-space: nowrap;
    }

    .centro:hover { transform: translate(-50%, -50%) scale(1.05); }

    .centro span {
      font-size: 3rem;
      color: red;
      -webkit-text-fill-color: red;
    }

    @keyframes brilloPerpetuo {
      0%, 100% { filter: drop-shadow(0 0 15px #ff1493); }
      50%       { filter: drop-shadow(0 0 40px #ff69b4); }
    }

    .efecto-bloom {
      position: fixed;
      width: 100%; height: 100%;
      background: radial-gradient(circle at 50% 50%, rgba(255,105,180,0.1) 0%, transparent 60%);
      mix-blend-mode: overlay;
      animation: pulsacionBloom 8s infinite;
      z-index: 1;
    }

    @keyframes pulsacionBloom {
      0%, 100% { opacity: 0.6; transform: scale(1); }
      50%       { opacity: 0.8; transform: scale(1.2); }
    }

    .hidden-image {
      position: fixed;
      top: 50%; left: 50%;
      transform: translate(-50%, -50%) rotate(0deg);
      max-width: 80vw; max-height: 80vh;
      opacity: 0;
      visibility: hidden;
      transition: all 0.8s cubic-bezier(0.68,-0.55,0.27,1.55);
      z-index: 4;
      border-radius: 15px;
      box-shadow: 0 0 50px rgba(255,105,180,0.5);
    }

    .hidden-image.active {
      visibility: visible;
      opacity: 1;
      transform: translate(-50%, -50%) rotate(360deg);
    }

    @media (max-width: 768px) {
      .centro {
        font-size: 2.2rem;
        padding: 15px 20px;
        white-space: normal;
        width: 90vw;
      }
      .centro span { font-size: 1.8rem; }
      .hidden-image { max-width: 90vw; }
    }
  </style>
</head>
<body>

  <audio id="backgroundAudio" loop>
    <source src="https://raw.githubusercontent.com/AnteroTeobaldo/BCodeProyectos/main/Detalles_3_bcode/audio/audio.mp3" type="audio/mpeg">
  </audio>

  <div class="efecto-bloom"></div>
  <div class="terminal" id="terminal"></div>
  <div class="love-container" id="loveContainer"></div>

  <img src="https://raw.githubusercontent.com/AnteroTeobaldo/BCodeProyectos/main/Detalles_3_bcode/img/img.gif" alt="Imagen especial" class="hidden-image" id="hiddenImage">

  <div class="centro" id="centro">TE AMO <span>❤</span> MI BEBE HERMOSA</div>

  <script>
    const LINE_COUNT  = 30;
    const MATRIX_TEXT = "TE AMO ";
    const LOVE_CHARS  = ["❤","💖","💕","💞","💝"];

    const centro      = document.getElementById('centro');
    const hiddenImage = document.getElementById('hiddenImage');
    const audio       = document.getElementById('backgroundAudio');

    centro.addEventListener('click', () => {
      hiddenImage.classList.toggle('active');
    });

    function initMatrix() {
      const container = document.getElementById('terminal');
      container.innerHTML = '';
      for (let i = 0; i < LINE_COUNT; i++) {
        const line = document.createElement('div');
        line.className = 'text-container';
        line.style.animation = `scroll ${5 + i / 2}s linear infinite`;
        line.style.animationDelay = `${i * 0.3}s`;
        line.textContent = MATRIX_TEXT.repeat(Math.ceil(window.innerWidth / 50));
        container.appendChild(line);
      }
    }

    function initLoveEffect() {
      const container = document.getElementById('loveContainer');
      setInterval(() => {
        const love = document.createElement('div');
        love.className = 'love-text';
        love.style.left = `${Math.random() * 95}vw`;
        love.style.animationDuration = `${Math.random() * 4 + 6}s`;
        love.textContent = LOVE_CHARS[Math.floor(Math.random() * LOVE_CHARS.length)];
        container.appendChild(love);
        setTimeout(() => love.remove(), 10000);
      }, 100);
    }

    function handleResize() {
      document.querySelectorAll('.text-container').forEach(line => {
        line.textContent = MATRIX_TEXT.repeat(Math.ceil(window.innerWidth / 50));
      });
      centro.style.fontSize = `${Math.min(window.innerWidth, window.innerHeight) * 0.07}px`;
    }

    window.addEventListener('load', () => {
      initMatrix();
      initLoveEffect();
      handleResize();
      document.body.addEventListener('click', () => {
        audio.play().catch(() => {});
      }, { once: true });
    });

    window.addEventListener('resize', handleResize);
  </script>
</body>
</html>
