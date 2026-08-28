<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.5">
  <title>⭐ RPS · Star Battle ⭐</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', system-ui, sans-serif; }
    body {
      min-height: 100vh;
      background: radial-gradient(circle at 20% 30%, #1a1e2c, #0b0d16);
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 1.5rem;
      color: #f0f3fa;
    }
    .game-container {
      max-width: 850px;
      width: 100%;
      background: rgba(20, 25, 40, 0.65);
      backdrop-filter: blur(6px);
      border-radius: 3.5rem 3.5rem 2.5rem 2.5rem;
      padding: 2rem 1.8rem 2.2rem;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.7), 0 0 0 1px rgba(255, 255, 255, 0.04);
    }
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-bottom: 1.2rem;
    }
    .header h1 {
      font-size: 2rem;
      font-weight: 700;
      letter-spacing: 3px;
      background: linear-gradient(135deg, #f7e05e, #f9b042);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      text-shadow: 0 0 18px rgba(247, 224, 94, 0.3);
      display: inline-flex;
      align-items: center;
      gap: 0.6rem;
    }
    .header-controls { display: flex; align-items: center; gap: 0.8rem; }
    .sound-toggle {
      background: rgba(60, 70, 110, 0.3);
      border: 1px solid rgba(255, 255, 255, 0.08);
      border-radius: 40px;
      padding: 0.4rem 1rem;
      color: #d6defa;
      font-size: 1.2rem;
      cursor: pointer;
      transition: 0.2s;
      backdrop-filter: blur(4px);
      display: flex;
      align-items: center;
      gap: 0.4rem;
      font-weight: 500;
    }
    .sound-toggle:hover { background: rgba(80, 90, 140, 0.3); border-color: #f7b73155; transform: scale(1.03); }
    .sound-toggle.muted { opacity: 0.5; }
    .subtitle {
      font-size: 0.9rem;
      color: #a7b3d9;
      letter-spacing: 2px;
      font-weight: 300;
      width: 100%;
      text-align: center;
      margin-top: -0.2rem;
    }
    .subtitle i { font-style: normal; display: inline-block; animation: floatPulse 2.4s infinite ease-in-out; }
    @keyframes floatPulse { 0%,100% { transform: translateY(0); opacity: 0.8; } 50% { transform: translateY(-4px); opacity: 1; } }

    /* name section */
    .name-section {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 0.8rem;
      margin-bottom: 1rem;
      flex-wrap: wrap;
    }
    .name-section input {
      background: rgba(0,0,0,0.3);
      border: 1px solid rgba(255,255,255,0.1);
      border-radius: 40px;
      padding: 0.5rem 1.2rem;
      color: #f0f3fa;
      font-size: 1rem;
      outline: none;
      transition: 0.2s;
      width: 200px;
    }
    .name-section input:focus { border-color: #f7b731; box-shadow: 0 0 20px rgba(247,183,49,0.1); }
    .name-section input::placeholder { color: #6a77a0; }
    .name-section .name-btn {
      background: rgba(247,183,49,0.15);
      border: 1px solid rgba(247,183,49,0.3);
      border-radius: 40px;
      padding: 0.5rem 1.5rem;
      color: #f7e05e;
      font-weight: 600;
      cursor: pointer;
      transition: 0.2s;
      font-size: 0.95rem;
    }
    .name-section .name-btn:hover { background: rgba(247,183,49,0.3); transform: scale(1.02); }
    .player-name-display {
      font-weight: 600;
      color: #f7e05e;
      font-size: 1.1rem;
      min-width: 80px;
      text-align: center;
    }

    /* star health - 3 stars */
    .star-health {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 0.8rem;
      background: rgba(0, 0, 0, 0.25);
      border-radius: 60px;
      padding: 0.4rem 1rem;
      margin-bottom: 1.2rem;
      border: 1px solid rgba(255, 255, 255, 0.03);
      flex-wrap: wrap;
    }
    .health-side {
      display: flex;
      align-items: center;
      gap: 0.6rem;
      font-weight: 600;
      font-size: 1rem;
    }
    .health-side .label { color: #8d9ad0; font-weight: 400; }
    .stars {
      display: flex;
      gap: 0.2rem;
      font-size: 1.8rem;
      letter-spacing: 2px;
    }
    .star { transition: 0.25s; }
    .star.lost { opacity: 0.15; filter: grayscale(1); transform: scale(0.6); }
    .star.lose-anim { animation: starLose 0.5s ease; }
    @keyframes starLose {
      0% { transform: scale(1.4); opacity: 1; }
      50% { transform: scale(0.3); opacity: 0.2; }
      100% { transform: scale(0.6); opacity: 0.15; filter: grayscale(1); }
    }
    .vs-small { font-size: 1.2rem; color: #7c89b5; font-weight: 700; }

    /* scoreboard */
    .scoreboard {
      display: flex;
      justify-content: space-around;
      align-items: center;
      background: rgba(0, 0, 0, 0.3);
      border-radius: 60px;
      padding: 0.4rem 0.5rem;
      margin-bottom: 1.2rem;
      border: 1px solid rgba(255, 255, 255, 0.03);
      flex-wrap: wrap;
      gap: 0.2rem;
    }
    .score-item {
      display: flex;
      align-items: center;
      gap: 0.4rem;
      font-weight: 600;
      font-size: 0.95rem;
      background: rgba(255, 255, 255, 0.02);
      padding: 0.1rem 0.8rem;
      border-radius: 50px;
    }
    .score-item .label { color: #8d9ad0; font-weight: 400; }
    .score-number { min-width: 2rem; text-align: center; font-size: 1.3rem; font-weight: 700; color: #eef3ff; transition: 0.2s; }
    .score-number.pulse-glow { animation: scorePulse 0.5s ease; }
    @keyframes scorePulse { 0% { transform: scale(1); } 50% { transform: scale(1.35); color: #ffe484; } 100% { transform: scale(1); } }
    .stat-item {
      display: flex;
      align-items: center;
      gap: 0.3rem;
      font-size: 0.8rem;
      color: #a7b3d9;
      background: rgba(0,0,0,0.2);
      padding: 0.1rem 0.7rem;
      border-radius: 40px;
    }
    .stat-item strong { color: #f0f3fa; }

    /* arena - FIXED to show VS fully */
    .arena {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background: linear-gradient(145deg, rgba(0, 0, 0, 0.35), rgba(20, 25, 50, 0.5));
      border-radius: 4rem;
      padding: 1.5rem 0.8rem;
      margin-bottom: 1.8rem;
      border: 1px solid rgba(255, 255, 255, 0.02);
      position: relative;
      min-height: 200px;
      backdrop-filter: blur(2px);
      overflow: visible;
    }
    .arena::before {
      content: '';
      position: absolute;
      top: -50%;
      left: -50%;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle at 50% 50%, rgba(247,183,49,0.03), transparent 70%);
      animation: arenaGlow 8s infinite alternate;
      pointer-events: none;
    }
    @keyframes arenaGlow { 0% { transform: translate(0,0) scale(1); } 100% { transform: translate(5%,5%) scale(1.1); } }
    
    .player-side, .computer-side {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 0.3rem;
      flex: 1;
      position: relative;
      z-index: 1;
      min-width: 0;
    }
    .side-label { 
      font-size: 0.9rem; 
      font-weight: 500; 
      letter-spacing: 2px; 
      color: #7c89b5;
      text-align: center;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
      max-width: 100px;
    }
    .choice-icon {
      font-size: 5rem;
      line-height: 1;
      transition: 0.2s;
      filter: drop-shadow(0 4px 8px rgba(0,0,0,0.6));
      width: 90px;
      height: 90px;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 50%;
      background: rgba(255,255,255,0.02);
      transform: scale(1);
      position: relative;
    }
    .choice-icon[data-choice="rock"] { font-size: 5.5rem; text-shadow: 0 4px 20px rgba(139,119,101,0.4); }
    .choice-icon[data-choice="paper"] { font-size: 5.3rem; text-shadow: 0 4px 20px rgba(200,200,220,0.3); }
    .choice-icon[data-choice="scissors"] { font-size: 5.8rem; text-shadow: 0 4px 20px rgba(192,192,192,0.3); }
    .choice-icon.shake { animation: handShake 0.4s infinite alternate ease-in-out; }
    @keyframes handShake { 0% { transform: rotate(-12deg) scale(0.9); } 100% { transform: rotate(12deg) scale(1.1); } }
    .choice-icon.reveal { animation: revealPop 0.5s cubic-bezier(0.34, 1.56, 0.64, 1); }
    @keyframes revealPop { 0% { transform: scale(0.2) rotate(-20deg); opacity: 0; } 100% { transform: scale(1) rotate(0); opacity: 1; } }
    .choice-icon.glow-win { animation: glowWin 0.8s ease 2; box-shadow: 0 0 40px #5fca7a, 0 0 80px rgba(95,202,122,0.3); border-radius: 50%; }
    @keyframes glowWin { 0%,100% { box-shadow: 0 0 20px #5fca7a; } 50% { box-shadow: 0 0 70px #7ae99b; } }
    .choice-icon.glow-lose { animation: glowLose 0.8s ease 2; box-shadow: 0 0 40px #e05a5a, 0 0 80px rgba(224,90,90,0.3); border-radius: 50%; }
    @keyframes glowLose { 0%,100% { box-shadow: 0 0 20px #e05a5a; } 50% { box-shadow: 0 0 70px #ff7a7a; } }
    .choice-icon.pulse-draw { animation: pulseDraw 0.6s ease 2; }
    @keyframes pulseDraw { 0%,100% { transform: scale(1); box-shadow: 0 0 0 transparent; } 50% { transform: scale(1.15); box-shadow: 0 0 50px #f7b731; } }
    
    /* VS center - FIXED to show fully */
    .vs-center { 
      font-size: 1.8rem; 
      font-weight: 800; 
      color: #bcbde0; 
      text-shadow: 0 0 12px rgba(255,215,100,0.2); 
      animation: vsPulse 1.8s infinite ease-in-out; 
      letter-spacing: 2px; 
      position: relative; 
      z-index: 1;
      flex-shrink: 0;
      padding: 0 0.3rem;
      min-width: 70px;
      text-align: center;
    }
    @keyframes vsPulse { 0%,100% { transform: scale(1); opacity: 0.7; } 50% { transform: scale(1.1); opacity: 1; text-shadow: 0 0 30px #f7b731; } }
    
    .result-badge {
      position: absolute;
      bottom: -18px;
      left: 50%;
      transform: translateX(-50%);
      background: #1c2238;
      padding: 0.3rem 1.8rem;
      border-radius: 50px;
      font-weight: 700;
      font-size: 1.1rem;
      letter-spacing: 1px;
      border: 1px solid rgba(255,215,100,0.2);
      white-space: nowrap;
      box-shadow: 0 6px 14px rgba(0,0,0,0.6);
      transition: 0.2s;
      backdrop-filter: blur(8px);
      z-index: 2;
    }
    .result-badge.win { color: #9bffb0; border-color: #5fca7a; background: #1a2a1a; }
    .result-badge.lose { color: #ff9b9b; border-color: #e05a5a; background: #2a1a1a; }
    .result-badge.draw { color: #f7e05e; border-color: #d4b84a; background: #2a261a; }
    .result-badge.gameover { color: #ff6b6b; border-color: #ff3b3b; background: #2a1a1a; font-size: 1.3rem; }

    .choices {
      display: flex;
      justify-content: center;
      gap: 1.2rem;
      flex-wrap: wrap;
      margin-top: 0.8rem;
      margin-bottom: 1.2rem;
    }
    .choice-btn {
      background: rgba(28,35,60,0.7);
      backdrop-filter: blur(4px);
      border: 2px solid rgba(255,255,255,0.04);
      border-radius: 2rem;
      padding: 1rem 1.8rem;
      font-size: 1.8rem;
      font-weight: 600;
      color: #d6defa;
      display: inline-flex;
      align-items: center;
      gap: 0.8rem;
      cursor: pointer;
      transition: 0.3s ease;
      box-shadow: 0 8px 14px rgba(0,0,0,0.4);
      transform: scale(1);
      min-width: 130px;
      justify-content: center;
      letter-spacing: 1px;
      position: relative;
      overflow: hidden;
    }
    .choice-btn::before { content: ''; position: absolute; top: 0; left: 0; right: 0; bottom: 0; background: linear-gradient(135deg, rgba(255,255,255,0.05), transparent); opacity: 0; transition: 0.3s; }
    .choice-btn:hover::before { opacity: 1; }
    .choice-btn:hover { transform: scale(1.08); background: rgba(45,55,90,0.8); border-color: rgba(247,183,49,0.4); box-shadow: 0 0 40px rgba(247,183,49,0.15); }
    .choice-btn:active { transform: scale(0.92); transition: 0.05s; }
    .choice-btn:disabled { opacity: 0.4; transform: scale(0.96); pointer-events: none; filter: grayscale(0.4); }
    .choice-btn .btn-icon { font-size: 2.2rem; }
    .choice-btn .btn-label { font-size: 1rem; font-weight: 500; letter-spacing: 1px; }
    .choice-btn[data-choice="rock"] { border-color: rgba(139,119,101,0.3); }
    .choice-btn[data-choice="rock"]:hover { border-color: rgba(139,119,101,0.6); }
    .choice-btn[data-choice="paper"] { border-color: rgba(200,200,220,0.2); }
    .choice-btn[data-choice="paper"]:hover { border-color: rgba(200,200,220,0.5); }
    .choice-btn[data-choice="scissors"] { border-color: rgba(192,192,192,0.2); }
    .choice-btn[data-choice="scissors"]:hover { border-color: rgba(192,192,192,0.5); }

    .history-section { margin: 1.6rem 0 1.2rem; }
    .history-title { font-size: 0.9rem; text-transform: uppercase; letter-spacing: 2px; color: #707da5; margin-bottom: 0.5rem; display: flex; justify-content: space-between; align-items: center; }
    .history-list { display: flex; flex-wrap: wrap; gap: 0.5rem; min-height: 34px; padding: 0.2rem 0; }
    .history-item { background: rgba(0,0,0,0.25); padding: 0.2rem 0.8rem; border-radius: 30px; font-size: 0.9rem; border-left: 3px solid #3f4a70; animation: slideIn 0.3s ease; display: inline-flex; align-items: center; gap: 0.3rem; backdrop-filter: blur(2px); }
    .history-item .h-icon { font-size: 1.2rem; }
    .history-item.win { border-left-color: #5fca7a; background: rgba(95,202,122,0.05); }
    .history-item.lose { border-left-color: #e05a5a; background: rgba(224,90,90,0.05); }
    .history-item.draw { border-left-color: #f7b731; background: rgba(247,183,49,0.05); }
    @keyframes slideIn { 0% { opacity: 0; transform: translateX(-14px) scale(0.9); } 100% { opacity: 1; transform: translateX(0) scale(1); } }

    .reset-area { display: flex; justify-content: center; margin-top: 0.8rem; gap: 1rem; flex-wrap: wrap; }
    .reset-btn {
      background: rgba(60,70,110,0.3);
      border: 1px solid rgba(255,255,255,0.05);
      padding: 0.6rem 2.2rem;
      border-radius: 50px;
      font-weight: 600;
      color: #b7c3ed;
      letter-spacing: 2px;
      backdrop-filter: blur(4px);
      cursor: pointer;
      transition: 0.2s;
      font-size: 0.9rem;
    }
    .reset-btn:hover { background: rgba(80,90,140,0.3); border-color: #f7b73155; color: #f0f3fa; transform: scale(1.02); }
    .reset-btn:active { transform: scale(0.95); }

    .countdown-text { font-size: 2.6rem; font-weight: 800; letter-spacing: 6px; color: #fbeba0; text-shadow: 0 0 40px #f7b731, 0 0 80px #f7b73133; animation: countPop 0.35s cubic-bezier(0.34, 1.56, 0.64, 1); }
    @keyframes countPop { 0% { transform: scale(0.2); opacity: 0; } 100% { transform: scale(1); opacity: 1; } }

    .confetti-wrapper { position: fixed; top: 0; left: 0; width: 100%; height: 100%; pointer-events: none; z-index: 999; overflow: hidden; }
    .confetti-piece { position: absolute; width: 10px; height: 10px; opacity: 0.9; animation: confettiFall linear forwards; }
    @keyframes confettiFall { 0% { transform: translateY(-20px) rotate(0deg); opacity: 1; } 100% { transform: translateY(110vh) rotate(720deg); opacity: 0; } }

    .game-over-overlay {
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.7);
      backdrop-filter: blur(6px);
      border-radius: 4rem;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      z-index: 10;
      opacity: 0;
      pointer-events: none;
      transition: 0.4s;
    }
    .game-over-overlay.show { opacity: 1; pointer-events: auto; }
    .game-over-overlay h2 { font-size: 3rem; font-weight: 800; letter-spacing: 4px; text-shadow: 0 0 40px rgba(255,100,100,0.5); }
    .game-over-overlay .sub { font-size: 1.2rem; color: #a7b3d9; margin-top: 0.5rem; }
    .game-over-overlay .restart-btn {
      margin-top: 1.5rem;
      background: rgba(247,183,49,0.2);
      border: 2px solid #f7b731;
      padding: 0.6rem 2.5rem;
      border-radius: 50px;
      font-weight: 700;
      color: #f7e05e;
      cursor: pointer;
      transition: 0.2s;
      font-size: 1.2rem;
    }
    .game-over-overlay .restart-btn:hover { background: rgba(247,183,49,0.4); transform: scale(1.05); }

    .arena { position: relative; overflow: visible; }

    /* floating emojis */
    .floating-emoji {
      position: absolute;
      font-size: 1.5rem;
      animation: floatUp 3s ease-out forwards;
      pointer-events: none;
      z-index: 5;
    }
    @keyframes floatUp {
      0% { opacity: 1; transform: translateY(0) scale(1); }
      100% { opacity: 0; transform: translateY(-80px) scale(1.5); }
    }

    @media (max-width: 640px) {
      .game-container { padding: 1.2rem; }
      .header h1 { font-size: 1.4rem; }
      .choice-icon { font-size: 3.5rem; width: 70px; height: 70px; }
      .choice-icon[data-choice="rock"] { font-size: 4rem; }
      .choice-icon[data-choice="paper"] { font-size: 3.8rem; }
      .choice-icon[data-choice="scissors"] { font-size: 4.2rem; }
      .choice-btn { min-width: 90px; padding: 0.6rem 1rem; font-size: 1.4rem; }
      .choice-btn .btn-icon { font-size: 1.8rem; }
      .choice-btn .btn-label { font-size: 0.85rem; }
      .vs-center { font-size: 1.4rem; min-width: 50px; }
      .arena { padding: 1rem 0.3rem; min-height: 150px; }
      .result-badge { font-size: 0.8rem; padding: 0.2rem 1rem; bottom: -14px; }
      .stars { font-size: 1.4rem; }
      .health-side { font-size: 0.8rem; }
      .name-section input { width: 140px; font-size: 0.9rem; }
      .side-label { font-size: 0.7rem; max-width: 70px; }
    }
    @media (max-width: 440px) {
      .choice-btn { min-width: 70px; padding: 0.4rem 0.7rem; font-size: 1.1rem; gap: 0.4rem; }
      .choice-btn .btn-icon { font-size: 1.4rem; }
      .choice-btn .btn-label { font-size: 0.7rem; }
      .choice-icon { font-size: 2.8rem; width: 60px; height: 60px; }
      .choice-icon[data-choice="rock"] { font-size: 3.2rem; }
      .choice-icon[data-choice="paper"] { font-size: 3rem; }
      .choice-icon[data-choice="scissors"] { font-size: 3.4rem; }
      .game-over-overlay h2 { font-size: 2rem; }
      .stars { font-size: 1.2rem; }
      .vs-center { font-size: 1.1rem; min-width: 40px; }
      .side-label { font-size: 0.6rem; max-width: 60px; }
    }
  </style>
</head>
<body>
<div class="game-container" id="app">
  <header class="header">
    <h1><span>⚔️</span> RPS · STAR BATTLE</h1>
    <div class="header-controls">
      <button class="sound-toggle" id="soundToggle">🔊 <span id="soundLabel">ON</span></button>
    </div>
    <div class="subtitle"><i>⭐ 3 stars each · lose a star on defeat ⭐</i></div>
  </header>

  <!-- Name Input -->
  <div class="name-section">
    <input type="text" id="playerNameInput" placeholder="Enter your name..." maxlength="15">
    <button class="name-btn" id="setNameBtn">Set Name</button>
    <span class="player-name-display" id="playerNameDisplay">👤 Guest</span>
  </div>

  <!-- Star Health - 3 stars -->
  <div class="star-health">
    <div class="health-side"><span class="label" id="playerLabel">👤 YOU</span> <span class="stars" id="playerStars">⭐⭐⭐</span></div>
    <div class="vs-small">⚔️</div>
    <div class="health-side"><span class="label">💻 CPU</span> <span class="stars" id="computerStars">⭐⭐⭐</span></div>
  </div>

  <div class="scoreboard">
    <div class="score-item"><span class="label">🏆 WIN</span> <span class="score-number" id="winCount">0</span></div>
    <div class="score-item"><span class="label">🤝 DRAW</span> <span class="score-number" id="drawCount">0</span></div>
    <div class="stat-item">🔥 Streak: <strong id="streakDisplay">0</strong></div>
    <div class="stat-item">🏅 Win Rate: <strong id="winRate">0%</strong></div>
    <div class="stat-item">💫 Rounds: <strong id="roundCount">0</strong></div>
  </div>

  <div class="arena" id="arena">
    <div class="player-side">
      <span class="side-label" id="playerSideLabel">YOU</span>
      <div class="choice-icon" id="playerChoiceIcon">❓</div>
    </div>
    <div class="vs-center" id="vsText">⚡VS⚡</div>
    <div class="computer-side">
      <span class="side-label">COMPUTER</span>
      <div class="choice-icon" id="computerChoiceIcon">❓</div>
    </div>
    <div class="result-badge" id="resultBadge">⚡</div>
    <div class="game-over-overlay" id="gameOverOverlay">
      <h2 id="gameOverTitle">💀 GAME OVER</h2>
      <div class="sub" id="gameOverSub">You lost all stars!</div>
      <button class="restart-btn" id="restartFromOverlay">⟳ NEW GAME</button>
    </div>
  </div>

  <div class="choices" id="choiceButtons">
    <button class="choice-btn" data-choice="rock"><span class="btn-icon">🪨</span><span class="btn-label">Rock</span></button>
    <button class="choice-btn" data-choice="paper"><span class="btn-icon">📄</span><span class="btn-label">Paper</span></button>
    <button class="choice-btn" data-choice="scissors"><span class="btn-icon">✂️</span><span class="btn-label">Scissors</span></button>
  </div>

  <div class="history-section">
    <div class="history-title"><span>📜 ROUND HISTORY</span><span style="font-size:0.7rem; opacity:0.5;">last 8</span></div>
    <div class="history-list" id="historyList"></div>
  </div>

  <div class="reset-area">
    <button class="reset-btn" id="resetBtn">⟳ RESET GAME</button>
  </div>
</div>

<script>
  (function() {
    // ----- state -----
    let playerStars = 3, computerStars = 3;
    let winCount = 0, drawCount = 0;
    let history = [];
    let isPlaying = false;
    let gameOver = false;
    let timeoutIds = [];
    let soundEnabled = true;
    let currentStreak = 0;
    let playerName = 'Guest';
    let totalRounds = 0;

    const choiceMap = { rock: '🪨', paper: '📄', scissors: '✂️' };
    const winMap = { rock: 'scissors', scissors: 'paper', paper: 'rock' };
    const winEmojis = ['🎉', '🔥', '💪', '⭐', '🏆', '👑', '💯', '🚀'];
    const loseEmojis = ['😅', '💔', '😢', '🤔', '😤', '💀'];
    const drawEmojis = ['🤝', '⚖️', '😐', '🔄', '💫'];

    const playerIcon = document.getElementById('playerChoiceIcon');
    const computerIcon = document.getElementById('computerChoiceIcon');
    const resultBadge = document.getElementById('resultBadge');
    const vsText = document.getElementById('vsText');
    const winCountEl = document.getElementById('winCount');
    const drawCountEl = document.getElementById('drawCount');
    const historyList = document.getElementById('historyList');
    const choiceBtns = document.querySelectorAll('.choice-btn');
    const resetBtn = document.getElementById('resetBtn');
    const playerStarsEl = document.getElementById('playerStars');
    const computerStarsEl = document.getElementById('computerStars');
    const streakDisplay = document.getElementById('streakDisplay');
    const winRateEl = document.getElementById('winRate');
    const roundCountEl = document.getElementById('roundCount');
    const soundToggle = document.getElementById('soundToggle');
    const soundLabel = document.getElementById('soundLabel');
    const gameOverOverlay = document.getElementById('gameOverOverlay');
    const gameOverTitle = document.getElementById('gameOverTitle');
    const gameOverSub = document.getElementById('gameOverSub');
    const restartOverlayBtn = document.getElementById('restartFromOverlay');
    const playerNameInput = document.getElementById('playerNameInput');
    const setNameBtn = document.getElementById('setNameBtn');
    const playerNameDisplay = document.getElementById('playerNameDisplay');
    const playerLabel = document.getElementById('playerLabel');
    const playerSideLabel = document.getElementById('playerSideLabel');
    const arena = document.getElementById('arena');

    // ----- Audio (Web Audio) -----
    let audioCtx = null;
    function getAudioCtx() {
      if (!audioCtx) audioCtx = new (window.AudioContext || window.webkitAudioContext)();
      return audioCtx;
    }

    function playTone(freq, duration, type='sine', vol=0.25, delay=0) {
      if (!soundEnabled) return;
      try {
        const ctx = getAudioCtx();
        const osc = ctx.createOscillator();
        const gain = ctx.createGain();
        osc.type = type;
        osc.frequency.value = freq;
        gain.gain.setValueAtTime(vol, ctx.currentTime + delay);
        gain.gain.exponentialRampToValueAtTime(0.001, ctx.currentTime + delay + duration);
        osc.connect(gain);
        gain.connect(ctx.destination);
        osc.start(ctx.currentTime + delay);
        osc.stop(ctx.currentTime + delay + duration);
      } catch (_) {}
    }

    function sfxClick() { playTone(1000, 0.06, 'sine', 0.2); }
    function sfxCount() { playTone(800, 0.05, 'triangle', 0.15); }
    function sfxWin() { 
      playTone(1200, 0.1, 'sine', 0.3); 
      setTimeout(() => playTone(1500, 0.1, 'sine', 0.25), 100); 
      setTimeout(() => playTone(1800, 0.12, 'sine', 0.2), 200); 
    }
    function sfxLose() { 
      playTone(300, 0.2, 'sawtooth', 0.2); 
      setTimeout(() => playTone(250, 0.2, 'sawtooth', 0.15), 150); 
    }
    function sfxDraw() { 
      playTone(600, 0.08, 'sine', 0.2); 
      setTimeout(() => playTone(750, 0.08, 'sine', 0.2), 80); 
      setTimeout(() => playTone(900, 0.08, 'sine', 0.15), 160); 
    }
    function sfxStarLoss() { 
      playTone(200, 0.25, 'square', 0.15); 
      setTimeout(() => playTone(150, 0.25, 'square', 0.12), 120); 
    }
    function sfxGameOver() { 
      playTone(350, 0.3, 'sawtooth', 0.2); 
      setTimeout(() => playTone(280, 0.3, 'sawtooth', 0.18), 200); 
      setTimeout(() => playTone(200, 0.4, 'sawtooth', 0.2), 400); 
      setTimeout(() => playTone(150, 0.5, 'sawtooth', 0.25), 600); 
    }
    function sfxVictory() { 
      playTone(1000, 0.1, 'sine', 0.3); 
      setTimeout(() => playTone(1200, 0.1, 'sine', 0.3), 100); 
      setTimeout(() => playTone(1400, 0.1, 'sine', 0.3), 200); 
      setTimeout(() => playTone(1600, 0.15, 'sine', 0.35), 300); 
      setTimeout(() => playTone(1800, 0.2, 'sine', 0.3), 420); 
    }
    function sfxNewGame() { 
      playTone(900, 0.08, 'sine', 0.2); 
      setTimeout(() => playTone(1100, 0.08, 'sine', 0.2), 80); 
      setTimeout(() => playTone(1300, 0.1, 'sine', 0.2), 160); 
    }
    function sfxNameSet() { 
      playTone(1000, 0.06, 'sine', 0.2); 
      setTimeout(() => playTone(1200, 0.06, 'sine', 0.2), 60); 
      setTimeout(() => playTone(1400, 0.08, 'sine', 0.2), 120); 
    }

    // ----- helpers -----
    function clearTimeouts() { timeoutIds.forEach(id => clearTimeout(id)); timeoutIds = []; }

    function renderStars() {
      const playerStarStr = '⭐'.repeat(playerStars) + '☆'.repeat(3 - playerStars);
      const computerStarStr = '⭐'.repeat(computerStars) + '☆'.repeat(3 - computerStars);
      playerStarsEl.textContent = playerStarStr;
      computerStarsEl.textContent = computerStarStr;
    }

    function updateStats() {
      const totalRoundsCalc = winCount + drawCount + (3 - playerStars) + (3 - computerStars);
      const rate = totalRoundsCalc > 0 ? Math.round((winCount / totalRoundsCalc) * 100) : 0;
      winRateEl.textContent = Math.min(100, rate) + '%';
      streakDisplay.textContent = currentStreak;
      winCountEl.textContent = winCount;
      drawCountEl.textContent = drawCount;
      roundCountEl.textContent = totalRounds;
    }

    function updateStreak(win) {
      if (win) { currentStreak++; } 
      else { currentStreak = 0; }
      streakDisplay.textContent = currentStreak;
    }

    function addHistory(playerChoice, computerChoice, result) {
      history.push({ playerChoice, computerChoice, result });
      if (history.length > 8) history.shift();
      renderHistory();
    }

    function renderHistory() {
      historyList.innerHTML = '';
      history.forEach(h => {
        const el = document.createElement('span');
        el.className = `history-item ${h.result === 'win' ? 'win' : h.result === 'lose' ? 'lose' : 'draw'}`;
        const resultText = h.result === 'win' ? '✅ Win' : h.result === 'lose' ? '❌ Lose' : '⚖️ Draw';
        el.innerHTML = `<span class="h-icon">${choiceMap[h.playerChoice]}</span> vs <span class="h-icon">${choiceMap[h.computerChoice]}</span> — ${resultText}`;
        historyList.appendChild(el);
      });
    }

    function getComputerChoice() { return ['rock','paper','scissors'][Math.floor(Math.random()*3)]; }
    function determineWinner(p, c) { return p === c ? 'draw' : winMap[p] === c ? 'win' : 'lose'; }

    function spawnFloatingEmoji(emoji, x, y) {
      const el = document.createElement('div');
      el.className = 'floating-emoji';
      el.textContent = emoji;
      el.style.left = x + '%';
      el.style.top = y + '%';
      el.style.fontSize = (1.2 + Math.random() * 1.5) + 'rem';
      arena.appendChild(el);
      setTimeout(() => el.remove(), 3000);
    }

    function spawnCelebration() {
      const emojis = ['🎉', '⭐', '💪', '🔥', '👑', '🏆', '✨', '🌟'];
      for (let i = 0; i < 6; i++) {
        setTimeout(() => {
          const x = 10 + Math.random() * 80;
          const y = 10 + Math.random() * 60;
          spawnFloatingEmoji(emojis[Math.floor(Math.random() * emojis.length)], x, y);
        }, i * 200);
      }
    }

    function spawnDefeatEmojis() {
      const emojis = ['💔', '😢', '😤', '💀', '😅'];
      for (let i = 0; i < 4; i++) {
        setTimeout(() => {
          const x = 10 + Math.random() * 80;
          const y = 10 + Math.random() * 60;
          spawnFloatingEmoji(emojis[Math.floor(Math.random() * emojis.length)], x, y);
        }, i * 150);
      }
    }

    function fireConfetti() {
      const wrapper = document.createElement('div');
      wrapper.className = 'confetti-wrapper';
      const colors = ['#f7e05e','#ff7b7b','#6ad4ff','#9bffb0','#ff9cf5','#ff6b6b','#ffd93d','#a29bfe'];
      for (let i=0; i<60; i++) {
        const piece = document.createElement('div');
        piece.className = 'confetti-piece';
        const size = 5 + Math.random()*14;
        piece.style.width = size+'px';
        piece.style.height = size*0.6+'px';
        piece.style.left = Math.random()*100+'%';
        piece.style.top = '-10px';
        piece.style.background = colors[Math.floor(Math.random()*colors.length)];
        piece.style.borderRadius = Math.random()>0.5 ? '50%' : '2px';
        piece.style.animationDuration = (1.8+Math.random()*2.5)+'s';
        piece.style.animationDelay = Math.random()*0.8+'s';
        wrapper.appendChild(piece);
      }
      document.body.appendChild(wrapper);
      const tid = setTimeout(() => wrapper.remove(), 4500);
      timeoutIds.push(tid);
    }

    function checkGameOver() {
      if (playerStars <= 0) {
        gameOver = true;
        gameOverTitle.textContent = '💀 YOU LOSE!';
        gameOverSub.textContent = `${playerName} lost all stars. Computer wins!`;
        gameOverOverlay.classList.add('show');
        resultBadge.textContent = '💀 GAME OVER';
        resultBadge.className = 'result-badge gameover';
        sfxGameOver();
        spawnDefeatEmojis();
        choiceBtns.forEach(b => b.disabled = true);
        return true;
      } else if (computerStars <= 0) {
        gameOver = true;
        gameOverTitle.textContent = `🏆 ${playerName} WINS!`;
        gameOverSub.textContent = `${playerName} destroyed all CPU stars! Amazing!`;
        gameOverOverlay.classList.add('show');
        resultBadge.textContent = '🏆 VICTORY!';
        resultBadge.className = 'result-badge win';
        fireConfetti();
        spawnCelebration();
        sfxVictory();
        choiceBtns.forEach(b => b.disabled = true);
        return true;
      }
      return false;
    }

    function loseStar(side) {
      if (side === 'player') {
        if (playerStars > 0) {
          playerStars--;
          sfxStarLoss();
        }
      } else {
        if (computerStars > 0) {
          computerStars--;
          sfxStarLoss();
        }
      }
      renderStars();
    }

    // ----- main game flow -----
    function playRound(playerChoice) {
      if (isPlaying || gameOver) return;
      isPlaying = true;
      clearTimeouts();
      choiceBtns.forEach(b => b.disabled = true);
      totalRounds++;

      sfxClick();
      resultBadge.textContent = '⚡';
      resultBadge.className = 'result-badge';
      playerIcon.textContent = '❓';
      computerIcon.textContent = '❓';
      playerIcon.className = 'choice-icon shake';
      computerIcon.className = 'choice-icon shake';
      playerIcon.removeAttribute('data-choice');
      computerIcon.removeAttribute('data-choice');
      vsText.textContent = '⚡VS⚡';

      const steps = ['ROCK...', 'PAPER...', 'SCISSORS...', 'SHOOT!'];
      let idx = 0;
      const countdownInterval = setInterval(() => {
        if (idx < steps.length) {
          vsText.innerHTML = `<span class="countdown-text">${steps[idx]}</span>`;
          if (idx < 3) sfxCount();
          idx++;
        } else {
          clearInterval(countdownInterval);
          const computerChoice = getComputerChoice();
          const result = determineWinner(playerChoice, computerChoice);

          playerIcon.className = 'choice-icon reveal';
          computerIcon.className = 'choice-icon reveal';
          playerIcon.textContent = choiceMap[playerChoice];
          computerIcon.textContent = choiceMap[computerChoice];
          playerIcon.setAttribute('data-choice', playerChoice);
          computerIcon.setAttribute('data-choice', computerChoice);
          vsText.textContent = '⚡VS⚡';

          let highlight = null;
          let resultText = '';
          let resultEmoji = '';
          playerIcon.classList.remove('glow-win','glow-lose','pulse-draw');
          computerIcon.classList.remove('glow-win','glow-lose','pulse-draw');

          if (result === 'win') {
            winCount++;
            highlight = 'player';
            resultEmoji = winEmojis[Math.floor(Math.random() * winEmojis.length)];
            resultText = `${resultEmoji} ${playerName} WINS!`;
            resultBadge.className = 'result-badge win';
            playerIcon.classList.add('glow-win');
            sfxWin();
            updateStreak(true);
            loseStar('computer');
            fireConfetti();
            spawnCelebration();
          } else if (result === 'lose') {
            highlight = 'computer';
            resultEmoji = loseEmojis[Math.floor(Math.random() * loseEmojis.length)];
            resultText = `${resultEmoji} CPU WINS!`;
            resultBadge.className = 'result-badge lose';
            computerIcon.classList.add('glow-lose');
            sfxLose();
            updateStreak(false);
            loseStar('player');
            spawnDefeatEmojis();
          } else {
            drawCount++;
            highlight = 'draw';
            resultEmoji = drawEmojis[Math.floor(Math.random() * drawEmojis.length)];
            resultText = `${resultEmoji} DRAW!`;
            resultBadge.className = 'result-badge draw';
            playerIcon.classList.add('pulse-draw');
            computerIcon.classList.add('pulse-draw');
            sfxDraw();
            updateStreak(false);
          }

          resultBadge.textContent = resultText;
          addHistory(playerChoice, computerChoice, result);
          renderStars();
          updateStats();

          const gameEnded = checkGameOver();
          if (gameEnded) {
            isPlaying = false;
            return;
          }

          const tid = setTimeout(() => {
            isPlaying = false;
            if (!gameOver) choiceBtns.forEach(b => b.disabled = false);
            setTimeout(() => {
              playerIcon.classList.remove('glow-win','glow-lose','pulse-draw');
              computerIcon.classList.remove('glow-win','glow-lose','pulse-draw');
            }, 400);
          }, 500);
          timeoutIds.push(tid);
        }
      }, 460);
    }

    // ----- reset -----
    function resetGame() {
      if (isPlaying) return;
      clearTimeouts();
      playerStars = 3; computerStars = 3;
      winCount = 0; drawCount = 0;
      history = [];
      currentStreak = 0;
      totalRounds = 0;
      gameOver = false;
      gameOverOverlay.classList.remove('show');
      renderStars();
      updateStats();
      renderHistory();
      
      playerIcon.textContent = '❓';
      computerIcon.textContent = '❓';
      playerIcon.className = 'choice-icon';
      computerIcon.className = 'choice-icon';
      playerIcon.removeAttribute('data-choice');
      computerIcon.removeAttribute('data-choice');
      playerIcon.classList.remove('glow-win','glow-lose','pulse-draw');
      computerIcon.classList.remove('glow-win','glow-lose','pulse-draw');
      resultBadge.textContent = '⚡';
      resultBadge.className = 'result-badge';
      vsText.textContent = '⚡VS⚡';
      choiceBtns.forEach(b => b.disabled = false);
      isPlaying = false;
      sfxNewGame();
    }

    // ----- name setting -----
    function setPlayerName() {
      const name = playerNameInput.value.trim();
      if (name.length > 0) {
        playerName = name;
        playerNameDisplay.textContent = `👤 ${playerName}`;
        playerLabel.textContent = `👤 ${playerName}`;
        playerSideLabel.textContent = playerName.toUpperCase();
        sfxNameSet();
        playerNameInput.value = '';
        for (let i = 0; i < 3; i++) {
          setTimeout(() => {
            spawnFloatingEmoji('✨', 20 + Math.random() * 60, 20 + Math.random() * 40);
          }, i * 200);
        }
      } else {
        playerNameInput.focus();
        playerNameInput.style.borderColor = '#ff6b6b';
        setTimeout(() => playerNameInput.style.borderColor = '', 800);
      }
    }

    // ----- sound toggle -----
    function toggleSound() {
      soundEnabled = !soundEnabled;
      soundToggle.classList.toggle('muted', !soundEnabled);
      soundLabel.textContent = soundEnabled ? 'ON' : 'OFF';
      if (soundEnabled) sfxClick();
    }

    // ----- event listeners -----
    choiceBtns.forEach(btn => {
      btn.addEventListener('click', () => {
        if (gameOver) return;
        const choice = btn.dataset.choice;
        playRound(choice);
      });
    });

    resetBtn.addEventListener('click', resetGame);
    restartOverlayBtn.addEventListener('click', resetGame);
    soundToggle.addEventListener('click', toggleSound);
    setNameBtn.addEventListener('click', setPlayerName);
    playerNameInput.addEventListener('keypress', (e) => { if (e.key === 'Enter') setPlayerName(); });

    // Initialize
    renderStars();
    updateStats();
    renderHistory();
    playerNameDisplay.textContent = '👤 Guest';
    playerLabel.textContent = '👤 YOU';
    playerSideLabel.textContent = 'YOU';
  })();
</script>
</body>
</html>
