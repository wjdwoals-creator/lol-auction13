<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>밴들시티 경매 내전</title>
  <link href="https://fonts.googleapis.com/css2?family=Black+Han+Sans&family=Noto+Sans+KR:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    
    :root {
      --primary: #00D9FF;
      --primary-dark: #00A8CC;
      --secondary: #FF6B35;
      --accent: #FFE66D;
      --success: #4ADE80;
      --warning: #FBBF24;
      --danger: #F87171;
      --dark-1: #0a0a0f;
      --dark-2: #12121a;
      --dark-3: #1a1a25;
      --dark-4: #252532;
      --text-primary: #ffffff;
      --text-secondary: #a0a0b0;
      --glass: rgba(255, 255, 255, 0.05);
      --glass-border: rgba(255, 255, 255, 0.1);
    }
    
    body {
      font-family: 'Noto Sans KR', sans-serif;
      background: var(--dark-1);
      color: var(--text-primary);
      min-height: 100vh;
      position: relative;
      overflow-x: hidden;
    }
    
    body::before {
      content: '';
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: 
        radial-gradient(ellipse at 20% 20%, rgba(0, 217, 255, 0.15) 0%, transparent 50%),
        radial-gradient(ellipse at 80% 80%, rgba(255, 107, 53, 0.1) 0%, transparent 50%);
      pointer-events: none;
      z-index: 0;
    }
    
    .container { max-width: 1400px; margin: 0 auto; padding: 20px; position: relative; z-index: 1; }
    
    /* 화면 전환 */
    .screen { display: none; }
    .screen.active { display: block; animation: fadeIn 0.3s ease; }
    
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }
    
    /* 홈 화면 */
    .home-screen {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      position: relative;
      z-index: 1;
    }
    
    .logo-icon { 
      font-size: 100px; 
      margin-bottom: 24px; 
      filter: drop-shadow(0 0 40px rgba(0, 217, 255, 0.5));
      animation: float 3s ease-in-out infinite;
    }
    
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    
    .logo { 
      font-family: 'Black Han Sans', sans-serif; 
      font-size: 48px; 
      background: linear-gradient(135deg, var(--primary) 0%, var(--accent) 50%, var(--secondary) 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-bottom: 12px;
    }
    
    .subtitle { 
      font-size: 13px; 
      color: var(--text-secondary); 
      letter-spacing: 6px; 
      margin-bottom: 50px;
      text-transform: uppercase;
    }
    
    .btn-group { display: flex; flex-direction: column; gap: 16px; width: 100%; max-width: 340px; }
    
    .btn {
      padding: 20px 40px;
      font-size: 16px;
      font-weight: 700;
      border-radius: 16px;
      cursor: pointer;
      transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
      font-family: inherit;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 12px;
    }
    
    .btn-primary {
      background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
      border: none;
      color: var(--dark-1);
      box-shadow: 0 10px 40px rgba(0, 217, 255, 0.3);
    }
    
    .btn-primary:hover {
      transform: translateY(-3px);
      box-shadow: 0 15px 50px rgba(0, 217, 255, 0.4);
    }
    
    .btn-secondary {
      background: var(--glass);
      border: 2px solid var(--glass-border);
      color: var(--text-primary);
      backdrop-filter: blur(10px);
    }
    
    .btn-secondary:hover {
      background: rgba(255, 255, 255, 0.1);
      border-color: var(--primary);
      transform: translateY(-3px);
    }
    
    .btn:disabled { opacity: 0.5; cursor: not-allowed; transform: none !important; }
    
    .connection-status {
      position: fixed;
      bottom: 30px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      align-items: center;
      gap: 10px;
      padding: 12px 24px;
      background: var(--glass);
      border: 1px solid var(--glass-border);
      border-radius: 50px;
      backdrop-filter: blur(10px);
      font-size: 13px;
      color: var(--success);
    }
    
    .connection-dot {
      width: 8px;
      height: 8px;
      background: var(--success);
      border-radius: 50%;
      animation: pulse 2s infinite;
      box-shadow: 0 0 10px var(--success);
    }
    
    @keyframes pulse { 0%, 100% { opacity: 1; transform: scale(1); } 50% { opacity: 0.5; transform: scale(1.2); } }
    
    /* 폼 스타일 */
    .form-container {
      width: 100%;
      max-width: 420px;
      margin: 0 auto;
    }
    
    .form-group { margin-bottom: 24px; }
    .form-label { 
      display: block; 
      margin-bottom: 10px; 
      color: var(--text-secondary); 
      font-size: 12px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
    
    .form-input {
      width: 100%;
      padding: 18px 20px;
      font-size: 16px;
      color: var(--text-primary);
      background: var(--dark-3);
      border: 2px solid var(--dark-4);
      border-radius: 12px;
      font-family: inherit;
      transition: all 0.3s;
    }
    
    .form-input:focus { 
      outline: none; 
      border-color: var(--primary);
      box-shadow: 0 0 0 4px rgba(0, 217, 255, 0.1);
    }
    
    .form-input.room-code { 
      text-align: center; 
      font-size: 32px; 
      letter-spacing: 12px; 
      text-transform: uppercase;
      font-weight: 700;
    }
    
    .back-btn {
      position: fixed;
      top: 30px;
      left: 30px;
      padding: 12px 24px;
      background: var(--glass);
      border: 1px solid var(--glass-border);
      color: var(--text-primary);
      border-radius: 50px;
      cursor: pointer;
      font-family: inherit;
      font-size: 14px;
      font-weight: 600;
      backdrop-filter: blur(10px);
      transition: all 0.3s;
      z-index: 100;
    }
    
    .back-btn:hover {
      background: rgba(255, 255, 255, 0.1);
      transform: translateX(-5px);
    }
    
    /* 방 코드 표시 */
    .room-code-display {
      background: linear-gradient(135deg, rgba(0, 217, 255, 0.1) 0%, rgba(255, 107, 53, 0.1) 100%);
      border: 2px solid var(--primary);
      border-radius: 20px;
      padding: 20px 32px;
      text-align: center;
      margin-bottom: 30px;
    }
    
    .room-code-label { 
      font-size: 11px; 
      color: var(--text-secondary); 
      margin-bottom: 8px;
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    
    .room-code-value { 
      font-family: 'Black Han Sans', sans-serif; 
      font-size: 42px; 
      background: linear-gradient(135deg, var(--primary), var(--accent));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      letter-spacing: 10px;
    }
    
    .room-code-copy { 
      margin-top: 16px; 
      padding: 10px 24px; 
      font-size: 13px;
      background: var(--dark-3);
      border: 1px solid var(--dark-4);
      color: var(--text-primary);
      border-radius: 50px;
      cursor: pointer;
      font-family: inherit;
      transition: all 0.3s;
    }
    
    .room-code-copy:hover {
      background: var(--dark-4);
    }
    
    /* 로비 레이아웃 */
    .lobby-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 24px 30px;
      background: var(--dark-2);
      border-bottom: 1px solid var(--glass-border);
      margin-bottom: 30px;
      flex-wrap: wrap;
      gap: 20px;
      border-radius: 0 0 20px 20px;
    }
    
    .room-info { display: flex; gap: 24px; flex-wrap: wrap; }
    .info-item { 
      font-size: 14px; 
      color: var(--text-secondary);
      display: flex;
      align-items: center;
      gap: 8px;
    }
    
    .info-item span:last-child {
      color: var(--text-primary);
      font-weight: 700;
    }
    
    .role-badge {
      padding: 10px 20px;
      border-radius: 50px;
      font-size: 13px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
    
    .role-admin { 
      background: linear-gradient(135deg, var(--secondary), #ff8c5a);
      color: white;
    }
    
    .role-captain { 
      background: linear-gradient(135deg, var(--success), #6ee7a0);
      color: var(--dark-1);
    }
    
    /* 팀 그리드 */
    .teams-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 20px;
      margin-bottom: 30px;
    }
    
    .team-card {
      background: var(--dark-2);
      border-radius: 20px;
      padding: 24px;
      border: 2px solid var(--dark-4);
      transition: all 0.3s;
      position: relative;
      overflow: hidden;
    }
    
    .team-card::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      height: 4px;
      background: var(--team-color, var(--dark-4));
    }
    
    .team-card.my-team { 
      border-color: var(--primary); 
      box-shadow: 0 0 30px rgba(0, 217, 255, 0.2);
    }
    
    .team-card.empty { border-style: dashed; opacity: 0.4; }
    
    .team-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 16px; }
    .team-name { font-size: 22px; font-weight: 900; }
    .team-budget { font-size: 28px; color: var(--accent); font-weight: 900; }
    .team-captain { font-size: 14px; color: var(--text-secondary); margin-bottom: 12px; }
    
    .online-indicator { 
      display: inline-flex; 
      align-items: center; 
      gap: 6px; 
      font-size: 12px; 
      color: var(--success);
      background: rgba(74, 222, 128, 0.1);
      padding: 4px 12px;
      border-radius: 20px;
    }
    
    .online-dot { width: 6px; height: 6px; background: var(--success); border-radius: 50%; animation: pulse 2s infinite; }
    
    .team-players-list { margin-top: 16px; padding-top: 16px; border-top: 1px solid var(--dark-4); }
    .team-player-row { display: flex; justify-content: space-between; padding: 8px 0; font-size: 14px; color: var(--text-secondary); }
    .team-player-row span:last-child { color: var(--accent); font-weight: 700; }
    
    /* 선수 관리 */
    .player-section {
      background: var(--dark-2);
      border-radius: 20px;
      padding: 24px;
      margin-bottom: 24px;
      border: 1px solid var(--dark-4);
    }
    
    .section-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 20px;
    }
    
    .section-title { font-size: 18px; color: var(--primary); font-weight: 700; }
    
    .add-player-form {
      display: grid;
      grid-template-columns: 2fr 1fr 1fr 1.5fr auto;
      gap: 12px;
      align-items: end;
    }
    
    @media (max-width: 900px) {
      .add-player-form { grid-template-columns: 1fr 1fr; }
    }
    
    .position-select, .tier-select {
      padding: 14px 16px;
      font-size: 14px;
      background: var(--dark-3);
      border: 2px solid var(--dark-4);
      border-radius: 12px;
      color: var(--text-primary);
      font-family: inherit;
      cursor: pointer;
      transition: all 0.3s;
    }
    
    .position-select:focus, .tier-select:focus {
      outline: none;
      border-color: var(--primary);
    }
    
    .player-list { max-height: 400px; overflow-y: auto; }
    
    .player-item {
      display: flex;
      align-items: center;
      gap: 16px;
      padding: 16px;
      background: var(--dark-3);
      border-radius: 12px;
      margin-bottom: 10px;
      transition: all 0.3s;
    }
    
    .player-item:hover {
      background: var(--dark-4);
    }
    
    .player-pos {
      padding: 8px 14px;
      border-radius: 8px;
      font-size: 12px;
      font-weight: 700;
      min-width: 70px;
      text-align: center;
      text-transform: uppercase;
    }
    
    .pos-top { background: rgba(255, 107, 53, 0.2); color: #FF6B35; }
    .pos-jungle { background: rgba(74, 222, 128, 0.2); color: #4ADE80; }
    .pos-mid { background: rgba(167, 139, 250, 0.2); color: #A78BFA; }
    .pos-adc { background: rgba(248, 113, 113, 0.2); color: #F87171; }
    .pos-support { background: rgba(0, 217, 255, 0.2); color: #00D9FF; }
    
    .player-name { flex: 1; font-size: 16px; font-weight: 600; }
    .player-tier { 
      font-size: 13px; 
      font-weight: 700;
      padding: 6px 12px;
      border-radius: 6px;
      background: var(--dark-4);
    }
    
    .player-remove { 
      width: 32px; 
      height: 32px; 
      border-radius: 8px; 
      border: 1px solid var(--danger); 
      background: transparent; 
      color: var(--danger); 
      cursor: pointer; 
      font-size: 16px;
      transition: all 0.3s;
    }
    
    .player-remove:hover {
      background: var(--danger);
      color: white;
    }
    
    .tier-챌린저 { color: #F4C874; background: rgba(244, 200, 116, 0.15); }
    .tier-그랜드마스터 { color: #CD4545; background: rgba(205, 69, 69, 0.15); }
    .tier-마스터 { color: #9D48E0; background: rgba(157, 72, 224, 0.15); }
    .tier-다이아 { color: #576BCE; background: rgba(87, 107, 206, 0.15); }
    .tier-에메랄드 { color: #50C878; background: rgba(80, 200, 120, 0.15); }
    .tier-플래티넘 { color: #4E9996; background: rgba(78, 153, 150, 0.15); }
    .tier-골드 { color: #FFB900; background: rgba(255, 185, 0, 0.15); }
    .tier-실버 { color: #80989D; background: rgba(128, 152, 157, 0.15); }
    .tier-브론즈 { color: #8C4A2F; background: rgba(140, 74, 47, 0.15); }
    .tier-아이언 { color: #5E5E5E; background: rgba(94, 94, 94, 0.15); }
    
    /* 경매 화면 */
    .auction-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 24px 30px;
      background: var(--dark-2);
      border-bottom: 1px solid var(--glass-border);
      margin-bottom: 30px;
      flex-wrap: wrap;
      gap: 20px;
      border-radius: 0 0 20px 20px;
    }
    
    .auction-progress { font-size: 24px; color: var(--text-primary); font-weight: 900; }
    
    .player-status-summary {
      display: flex;
      gap: 16px;
      margin-bottom: 20px;
      flex-wrap: wrap;
    }
    
    .status-badge {
      padding: 10px 20px;
      border-radius: 50px;
      font-size: 14px;
      font-weight: 600;
    }
    
    .status-available { background: rgba(0, 217, 255, 0.15); color: var(--primary); }
    .status-passed { background: rgba(251, 191, 36, 0.15); color: var(--warning); }
    .status-sold { background: rgba(74, 222, 128, 0.15); color: var(--success); }
    
    /* 타이머 스타일 */
    .timer-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 8px;
    }
    
    .timer-display {
      font-family: 'Black Han Sans', sans-serif;
      font-size: 64px;
      line-height: 1;
      background: linear-gradient(135deg, var(--primary), var(--accent));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }
    
    .timer-display.warning { 
      background: linear-gradient(135deg, var(--warning), var(--secondary));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }
    
    .timer-display.danger { 
      background: var(--danger);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      animation: timerPulse 0.5s infinite;
    }
    
    @keyframes timerPulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.1); }
    }
    
    .timer-bar {
      width: 200px;
      height: 6px;
      background: var(--dark-4);
      border-radius: 3px;
      overflow: hidden;
    }
    
    .timer-bar-fill {
      height: 100%;
      background: linear-gradient(90deg, var(--primary), var(--accent));
      transition: width 1s linear;
      border-radius: 3px;
    }
    
    .timer-bar-fill.warning { background: linear-gradient(90deg, var(--warning), var(--secondary)); }
    .timer-bar-fill.danger { background: var(--danger); }
    
    .auction-phase {
      padding: 12px 24px;
      border-radius: 50px;
      font-size: 14px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
    
    .phase-bidding { 
      background: rgba(248, 113, 113, 0.2); 
      color: var(--danger);
      animation: phasePulse 2s infinite;
    }
    
    @keyframes phasePulse {
      0%, 100% { box-shadow: 0 0 0 0 rgba(248, 113, 113, 0.4); }
      50% { box-shadow: 0 0 0 10px rgba(248, 113, 113, 0); }
    }
    
    .phase-sold { background: rgba(74, 222, 128, 0.2); color: var(--success); }
    
    .current-player-card {
      background: linear-gradient(135deg, var(--dark-2) 0%, var(--dark-3) 100%);
      border: 2px solid var(--dark-4);
      border-radius: 24px;
      padding: 50px;
      text-align: center;
      margin-bottom: 30px;
      position: relative;
      overflow: hidden;
    }
    
    .current-player-card::before {
      content: '';
      position: absolute;
      top: -50%;
      left: -50%;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle, rgba(0, 217, 255, 0.1) 0%, transparent 50%);
      animation: rotate 20s linear infinite;
    }
    
    @keyframes rotate {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }
    
    .current-player-pos {
      display: inline-block;
      padding: 12px 32px;
      border-radius: 50px;
      font-size: 14px;
      font-weight: 700;
      margin-bottom: 24px;
      text-transform: uppercase;
      letter-spacing: 2px;
      position: relative;
    }
    
    .current-player-name {
      font-family: 'Black Han Sans', sans-serif;
      font-size: 64px;
      color: var(--text-primary);
      margin-bottom: 16px;
      position: relative;
    }
    
    .current-player-tier { font-size: 24px; font-weight: 700; position: relative; }
    .current-player-note { margin-top: 16px; color: var(--text-secondary); font-size: 16px; position: relative; }
    
    /* 실시간 입찰 현황 */
    .bid-status-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
      gap: 16px;
      margin-bottom: 30px;
    }
    
    .bid-status-card {
      background: var(--dark-3);
      border: 2px solid var(--dark-4);
      border-radius: 16px;
      padding: 20px;
      transition: all 0.3s;
      position: relative;
    }
    
    .bid-status-card.leading { 
      border-color: var(--accent); 
      background: rgba(255, 230, 109, 0.05);
      box-shadow: 0 0 30px rgba(255, 230, 109, 0.2);
    }
    
    .bid-status-card.my-team { 
      border-color: var(--primary);
      box-shadow: 0 0 20px rgba(0, 217, 255, 0.2);
    }
    
    .bid-team-name { font-size: 18px; font-weight: 700; margin-bottom: 8px; }
    .bid-team-budget { font-size: 12px; color: var(--text-secondary); margin-bottom: 16px; }
    
    .bid-amount-display {
      font-size: 32px;
      font-weight: 900;
      color: var(--accent);
    }
    
    .bid-amount-display.no-bid { color: var(--text-secondary); font-size: 16px; font-weight: 600; }
    .bid-amount-display.pass { color: var(--text-secondary); }
    
    .leading-badge {
      position: absolute;
      top: -12px;
      right: 16px;
      background: linear-gradient(135deg, var(--accent), var(--secondary));
      color: var(--dark-1);
      padding: 6px 16px;
      border-radius: 20px;
      font-size: 11px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
    
    .full-badge {
      position: absolute;
      top: -12px;
      left: 16px;
      background: var(--danger);
      color: white;
      padding: 6px 16px;
      border-radius: 20px;
      font-size: 11px;
      font-weight: 700;
    }
    
    .bid-status-card.full {
      opacity: 0.4;
      border-color: var(--dark-4) !important;
    }
    
    /* 입찰 컨트롤 */
    .bid-controls {
      background: var(--dark-2);
      border-radius: 24px;
      padding: 40px;
      text-align: center;
      border: 1px solid var(--dark-4);
    }
    
    .bid-controls.disabled { opacity: 0.5; pointer-events: none; }
    
    .my-team-info {
      margin-bottom: 24px;
      padding: 16px 28px;
      background: rgba(0, 217, 255, 0.1);
      border: 1px solid rgba(0, 217, 255, 0.2);
      border-radius: 50px;
      display: inline-block;
      font-size: 15px;
    }
    
    .my-team-info strong {
      color: var(--accent);
      font-size: 18px;
    }
    
    .bid-input-row {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 24px;
      margin-bottom: 24px;
    }
    
    .bid-adjust-btn {
      width: 64px;
      height: 64px;
      font-size: 32px;
      border: 2px solid var(--dark-4);
      border-radius: 50%;
      background: var(--dark-3);
      color: var(--text-primary);
      cursor: pointer;
      transition: all 0.2s;
    }
    
    .bid-adjust-btn:hover { 
      background: var(--primary);
      border-color: var(--primary);
      color: var(--dark-1);
      transform: scale(1.1);
    }
    
    .bid-value {
      font-family: 'Black Han Sans', sans-serif;
      font-size: 72px;
      background: linear-gradient(135deg, var(--primary), var(--accent));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      min-width: 180px;
    }
    
    .bid-unit { font-size: 24px; color: var(--text-secondary); font-weight: 700; }
    
    .quick-bid-row {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin-bottom: 28px;
      flex-wrap: wrap;
    }
    
    .quick-bid-btn {
      padding: 12px 20px;
      font-size: 14px;
      border: 1px solid var(--dark-4);
      border-radius: 50px;
      background: var(--dark-3);
      color: var(--text-secondary);
      cursor: pointer;
      font-family: inherit;
      font-weight: 600;
      transition: all 0.3s;
    }
    
    .quick-bid-btn:hover { 
      background: var(--primary);
      border-color: var(--primary);
      color: var(--dark-1);
    }
    
    .bid-action-row {
      display: flex;
      justify-content: center;
      gap: 16px;
    }
    
    .btn-pass {
      padding: 18px 48px;
      font-size: 16px;
      font-weight: 700;
      border: 2px solid var(--dark-4);
      border-radius: 16px;
      background: transparent;
      color: var(--text-secondary);
      cursor: pointer;
      font-family: inherit;
      transition: all 0.3s;
    }
    
    .btn-pass:hover {
      border-color: var(--danger);
      color: var(--danger);
    }
    
    .btn-bid {
      padding: 18px 64px;
      font-size: 16px;
      font-weight: 700;
      border: none;
      border-radius: 16px;
      background: linear-gradient(135deg, var(--primary), var(--primary-dark));
      color: var(--dark-1);
      cursor: pointer;
      font-family: inherit;
      transition: all 0.3s;
      box-shadow: 0 10px 30px rgba(0, 217, 255, 0.3);
    }
    
    .btn-bid:hover {
      transform: translateY(-3px);
      box-shadow: 0 15px 40px rgba(0, 217, 255, 0.4);
    }
    
    .current-bid-info {
      margin-top: 20px;
      color: var(--text-secondary);
      font-size: 14px;
    }
    
    .current-bid-info strong {
      color: var(--accent);
      font-size: 16px;
    }
    
    /* 관리자 컨트롤 */
    .admin-controls {
      margin-top: 24px;
      padding: 24px;
      background: rgba(255, 107, 53, 0.1);
      border-radius: 16px;
      border: 1px solid rgba(255, 107, 53, 0.2);
    }
    
    .admin-title { 
      font-size: 13px; 
      color: var(--secondary); 
      margin-bottom: 20px;
      text-transform: uppercase;
      letter-spacing: 2px;
      font-weight: 700;
    }
    
    /* 타이머 설정 */
    .timer-setting {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 12px;
      margin-bottom: 16px;
      padding: 12px;
      background: rgba(0,0,0,0.2);
      border-radius: 8px;
      flex-wrap: wrap;
    }
    
    .timer-setting label {
      color: var(--text-secondary);
      font-size: 14px;
    }
    
    .timer-setting input {
      width: 80px;
      padding: 8px;
      font-size: 16px;
      text-align: center;
      background: var(--dark-3);
      border: 1px solid var(--dark-4);
      border-radius: 8px;
      color: var(--text-primary);
      font-family: inherit;
    }
    
    /* 기록 */
    .history-section {
      background: var(--dark-2);
      border-radius: 20px;
      padding: 24px;
      margin-top: 30px;
      border: 1px solid var(--dark-4);
    }
    
    .history-item {
      display: flex;
      align-items: center;
      gap: 16px;
      padding: 16px;
      background: var(--dark-3);
      border-radius: 12px;
      margin-bottom: 10px;
    }
    
    .history-player { flex: 1; font-weight: 600; }
    .history-arrow { color: var(--text-secondary); }
    .history-winner { color: var(--success); font-weight: 700; }
    .history-price { color: var(--accent); font-weight: 700; }
    
    /* 푸터 버튼 */
    .footer-actions {
      padding: 24px;
      background: var(--dark-2);
      border-top: 1px solid var(--dark-4);
      text-align: center;
      position: sticky;
      bottom: 0;
      z-index: 10;
      border-radius: 20px 20px 0 0;
      margin-top: 20px;
    }
    
    /* 토스트 */
    .toast {
      position: fixed;
      top: 30px;
      left: 50%;
      transform: translateX(-50%);
      padding: 16px 32px;
      border-radius: 50px;
      font-weight: 700;
      z-index: 9999;
      animation: slideDown 0.3s ease;
      box-shadow: 0 10px 40px rgba(0, 0, 0, 0.3);
    }
    
    .toast-success { background: var(--success); color: var(--dark-1); }
    .toast-error { background: var(--danger); color: white; }
    .toast-info { background: var(--primary); color: var(--dark-1); }
    
    @keyframes slideDown { 
      from { transform: translateX(-50%) translateY(-100%); opacity: 0; } 
      to { transform: translateX(-50%) translateY(0); opacity: 1; } 
    }
    
    /* 카운트다운 오버레이 */
    .countdown-overlay {
      position: fixed;
      top: 30px;
      left: 50%;
      transform: translateX(-50%);
      background: var(--danger);
      padding: 20px 50px;
      border-radius: 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      z-index: 9998;
      pointer-events: none;
      box-shadow: 0 20px 60px rgba(248, 113, 113, 0.5);
    }
    
    .countdown-number {
      font-family: 'Black Han Sans', sans-serif;
      font-size: 72px;
      color: white;
      animation: countdownPulse 1s ease-in-out;
    }
    
    .countdown-text {
      font-size: 14px;
      color: rgba(255, 255, 255, 0.8);
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    
    @keyframes countdownPulse {
      0% { transform: scale(1.5); opacity: 0; }
      50% { transform: scale(1); opacity: 1; }
      100% { transform: scale(0.9); opacity: 0.8; }
    }
    
    /* 스크롤바 */
    ::-webkit-scrollbar { width: 8px; }
    ::-webkit-scrollbar-track { background: var(--dark-2); }
    ::-webkit-scrollbar-thumb { background: var(--dark-4); border-radius: 4px; }
    ::-webkit-scrollbar-thumb:hover { background: var(--primary); }
    
    /* 반응형 */
    @media (max-width: 768px) {
      .logo { font-size: 32px; }
      .current-player-name { font-size: 42px; }
      .bid-value { font-size: 56px; }
      .room-code-value { font-size: 28px; letter-spacing: 6px; }
      .timer-display { font-size: 48px; }
    }
    
    .empty-state {
      text-align: center;
      padding: 40px;
      color: var(--text-secondary);
    }
  </style>
</head>
<body>
  <div id="app">
    <!-- 홈 화면 -->
    <div id="homeScreen" class="screen active">
      <div class="home-screen">
        <div class="logo-icon">🏰</div>
        <h1 class="logo">밴들시티 경매 내전</h1>
        <p class="subtitle">REALTIME AUCTION SYSTEM</p>
        
        <div class="btn-group">
          <button class="btn btn-primary" onclick="showScreen('createScreen')">
            🏰 방 만들기 (관리자)
          </button>
          <button class="btn btn-secondary" onclick="showScreen('joinScreen')">
            🚪 방 참가하기 (팀장)
          </button>
        </div>
        
        <div class="connection-status">
          <div class="connection-dot"></div>
          <span>실시간 연결됨</span>
        </div>
      </div>
    </div>
    
    <!-- 방 만들기 화면 -->
    <div id="createScreen" class="screen">
      <button class="back-btn" onclick="showScreen('homeScreen')">← 뒤로</button>
      <div class="home-screen">
        <h2 class="logo" style="font-size: 36px; margin-bottom: 40px;">⚙️ 방 설정</h2>
        
        <div class="form-container">
          <div class="form-group">
            <label class="form-label">팀 수</label>
            <select id="createTeamCount" class="form-input">
              <option value="4">4팀</option>
              <option value="5">5팀</option>
              <option value="6">6팀</option>
              <option value="7">7팀</option>
              <option value="8">8팀</option>
            </select>
          </div>
          
          <div class="form-group">
            <label class="form-label">초기 예산</label>
            <input type="number" id="createBudget" class="form-input" value="1000" step="100">
          </div>
          
          <div class="form-group">
            <label class="form-label">최소 입찰가</label>
            <input type="number" id="createMinBid" class="form-input" value="5" step="5">
          </div>
          
          <div class="form-group">
            <label class="form-label">입찰 단위</label>
            <input type="number" id="createBidIncrement" class="form-input" value="5" step="5">
          </div>
          
          <div class="form-group">
            <label class="form-label">⏱️ 입찰 제한 시간 (초)</label>
            <input type="number" id="createTimeLimit" class="form-input" value="8" min="3" max="120" step="1">
          </div>
          
          <button class="btn btn-primary" onclick="createRoom()" style="width: 100%; margin-top: 20px;">
            🎮 방 생성하기
          </button>
        </div>
      </div>
    </div>
    
    <!-- 방 참가 화면 -->
    <div id="joinScreen" class="screen">
      <button class="back-btn" onclick="showScreen('homeScreen')">← 뒤로</button>
      <div class="home-screen">
        <h2 class="logo" style="font-size: 36px; margin-bottom: 40px;">🚪 방 참가</h2>
        
        <div class="form-container">
          <div class="form-group">
            <label class="form-label">방 코드</label>
            <input type="text" id="joinRoomCode" class="form-input room-code" placeholder="XXXXXX" maxlength="6">
          </div>
          
          <div class="form-group">
            <label class="form-label">팀 이름</label>
            <input type="text" id="joinTeamName" class="form-input" placeholder="예: T1, Gen.G, DRX...">
          </div>
          
          <div class="form-group">
            <label class="form-label">팀장 닉네임</label>
            <input type="text" id="joinCaptainName" class="form-input" placeholder="소환사명">
          </div>
          
          <button class="btn btn-primary" onclick="joinRoom()" style="width: 100%; margin-top: 20px;">
            🎯 참가하기
          </button>
        </div>
      </div>
    </div>
    
    <!-- 로비 화면 -->
    <div id="lobbyScreen" class="screen">
      <div class="lobby-header">
        <div class="room-code-display" style="margin-bottom: 0; padding: 12px 24px;">
          <span class="room-code-label">방 코드</span>
          <span class="room-code-value" id="lobbyRoomCode">XXXXXX</span>
          <button class="btn btn-secondary room-code-copy" onclick="copyRoomCode()">📋 복사</button>
        </div>
        
        <div class="room-info">
          <span class="info-item">💰 예산: <span id="lobbyBudget">1000</span>P</span>
          <span class="info-item">📊 단위: <span id="lobbyIncrement">5</span>P</span>
          <span class="info-item">⏱️ 시간: <span id="lobbyTimeLimit">30</span>초</span>
        </div>
        
        <span class="role-badge" id="lobbyRoleBadge">👑 관리자</span>
      </div>
      
      <div class="container">
        <!-- 팀 목록 -->
        <div class="section-header">
          <span class="section-title">🏆 참가 팀 (<span id="lobbyTeamCount">0</span>/<span id="lobbyMaxTeams">4</span>)</span>
        </div>
        
        <div class="teams-grid" id="lobbyTeamsGrid"></div>
        
        <!-- 선수 관리 (관리자만) -->
        <div id="playerManagement" class="player-section">
          <div class="section-header">
            <span class="section-title">➕ 선수 추가</span>
          </div>
          
          <div class="add-player-form">
            <input type="text" id="addPlayerName" class="form-input" placeholder="소환사명" style="padding: 12px;">
            <select id="addPlayerPos" class="position-select">
              <option value="top">⚔️ 탑</option>
              <option value="jungle">🌲 정글</option>
              <option value="mid">✨ 미드</option>
              <option value="adc">🏹 원딜</option>
              <option value="support">🛡️ 서폿</option>
            </select>
            <select id="addPlayerTier" class="tier-select">
              <option value="챌린저">챌린저</option>
              <option value="그랜드마스터">그랜드마스터</option>
              <option value="마스터">마스터</option>
              <option value="다이아">다이아</option>
              <option value="에메랄드">에메랄드</option>
              <option value="플래티넘">플래티넘</option>
              <option value="골드" selected>골드</option>
              <option value="실버">실버</option>
              <option value="브론즈">브론즈</option>
              <option value="아이언">아이언</option>
            </select>
            <input type="text" id="addPlayerNote" class="form-input" placeholder="메모 (선택)" style="padding: 12px;">
            <button class="btn btn-primary" onclick="addPlayer()" style="padding: 12px 24px;">추가</button>
          </div>
        </div>
        
        <!-- 선수 목록 - 세분화 -->
        <div class="player-section">
          <div class="section-header">
            <span class="section-title">⏳ 대기 선수 (<span id="lobbyAvailableCount">0</span>명)</span>
          </div>
          <div class="player-list" id="lobbyAvailableList"></div>
        </div>
        
        <div class="player-section" id="passedSection" style="display: none;">
          <div class="section-header">
            <span class="section-title" style="color: #E67E22;">🔄 유찰 선수 - 재경매 대기 (<span id="lobbyPassedCount">0</span>명)</span>
          </div>
          <div class="player-list" id="lobbyPassedList"></div>
        </div>
        
        <div class="player-section" id="soldSection" style="display: none;">
          <div class="section-header">
            <span class="section-title" style="color: #1E9B6C;">✅ 낙찰 완료 (<span id="lobbySoldCount">0</span>명)</span>
          </div>
          <div class="player-list" id="lobbySoldList"></div>
        </div>
      </div>
      
      <!-- 경매 시작 버튼 -->
      <div class="footer-actions" id="lobbyFooter">
        <button class="btn btn-primary" id="startAuctionBtn" onclick="startAuction()" style="padding: 18px 60px; font-size: 20px;">
          🎯 경매 시작
        </button>
        <p id="startAuctionHint" style="margin-top: 12px; color: #E74C3C; font-size: 14px;"></p>
      </div>
    </div>
    
    <!-- 경매 화면 -->
    <div id="auctionScreen" class="screen">
      <div class="auction-header">
        <div class="auction-progress">
          <span id="auctionRound" style="color: #C89B3C; font-weight: 700;">1라운드</span> · 
          경매 <span id="auctionCurrent">1</span>/<span id="auctionTotal">10</span>
        </div>
        
        <!-- 타이머 -->
        <div class="timer-container">
          <div class="timer-display" id="timerDisplay">30</div>
          <div class="timer-bar">
            <div class="timer-bar-fill" id="timerBarFill" style="width: 100%"></div>
          </div>
        </div>
        
        <span class="auction-phase phase-bidding" id="auctionPhase">🔴 입찰중</span>
      </div>
      
      <div class="container">
        <!-- 선수 현황 요약 -->
        <div class="player-status-summary" id="playerStatusSummary"></div>
        
        <!-- 현재 선수 -->
        <div class="current-player-card" id="currentPlayerCard">
          <div class="current-player-pos pos-mid" id="currentPlayerPos">✨ 미드</div>
          <div class="current-player-name" id="currentPlayerName">선수명</div>
          <div class="current-player-tier" id="currentPlayerTier">골드</div>
          <div class="current-player-note" id="currentPlayerNote"></div>
        </div>
        
        <!-- 실시간 입찰 현황 -->
        <div class="section-header">
          <span class="section-title">📊 실시간 입찰 현황</span>
        </div>
        <div class="bid-status-grid" id="bidStatusGrid"></div>
        
        <!-- 입찰 컨트롤 (팀장만) -->
        <div class="bid-controls" id="bidControls">
          <div class="my-team-info">
            <span id="myTeamName">내 팀</span> · 잔여 예산: <strong id="myTeamBudget">1000</strong>P
          </div>
          
          <div class="bid-input-row">
            <button class="bid-adjust-btn" onclick="adjustBid(-1)">−</button>
            <span class="bid-value" id="bidValue">50</span>
            <span class="bid-unit">P</span>
            <button class="bid-adjust-btn" onclick="adjustBid(1)">+</button>
          </div>
          
          <div class="quick-bid-row">
            <button class="quick-bid-btn" onclick="setQuickBid(10)">10P</button>
            <button class="quick-bid-btn" onclick="setQuickBid(30)">30P</button>
            <button class="quick-bid-btn" onclick="setQuickBid(50)">50P</button>
            <button class="quick-bid-btn" onclick="setQuickBid(100)">100P</button>
            <button class="quick-bid-btn" onclick="setQuickBid(150)">150P</button>
            <button class="quick-bid-btn" onclick="setQuickBid(200)">200P</button>
            <button class="quick-bid-btn" onclick="setBidToMax()">ALL-IN</button>
          </div>
          
          <div class="bid-action-row">
            <button class="btn-pass" onclick="submitPass()">PASS</button>
            <button class="btn-bid" onclick="submitBid()">💰 입찰하기</button>
          </div>
          
          <div class="current-bid-info">
            현재 최고가: <strong id="currentHighestBid">0</strong>P (<span id="currentHighestTeam">-</span>)
          </div>
        </div>
        
        <!-- 관리자 컨트롤 -->
        <div class="admin-controls" id="adminAuctionControls" style="display: none;">
          <div class="admin-title">👑 관리자 컨트롤</div>
          <div class="timer-setting">
            <label>⏱️ 타이머:</label>
            <button class="btn btn-secondary" onclick="pauseTimer()" style="padding: 8px 16px; font-size: 14px;">⏸️ 일시정지</button>
            <button class="btn btn-secondary" onclick="resumeTimer()" style="padding: 8px 16px; font-size: 14px;">▶️ 재개</button>
            <button class="btn btn-secondary" onclick="resetTimer()" style="padding: 8px 16px; font-size: 14px;">🔄 리셋</button>
          </div>
          <div style="display: flex; gap: 12px; justify-content: center; flex-wrap: wrap;">
            <button class="btn btn-primary" onclick="finalizeAuction()">✅ 즉시 낙찰</button>
            <button class="btn btn-secondary" onclick="skipPlayer()">⏭️ 유찰 (스킵)</button>
          </div>
        </div>
        
        <!-- 경매 기록 -->
        <div class="history-section">
          <div class="section-header">
            <span class="section-title">📜 경매 기록</span>
          </div>
          <div id="auctionHistory"></div>
        </div>
      </div>
    </div>
    
    <!-- 결과 화면 -->
    <div id="resultScreen" class="screen">
      <div class="home-screen" style="padding: 40px 20px;">
        <h1 class="logo" style="font-size: 48px; margin-bottom: 40px;">🏆 경매 완료!</h1>
        
        <div id="resultTeams" class="teams-grid" style="max-width: 1200px; width: 100%;"></div>
        
        <button class="btn btn-primary" onclick="location.reload()" style="margin-top: 40px;">
          🏠 처음으로
        </button>
      </div>
    </div>
    
    <!-- 카운트다운 오버레이 -->
    <div id="countdownOverlay" class="countdown-overlay" style="display: none;">
      <div class="countdown-number" id="countdownNumber">3</div>
      <div class="countdown-text">낙찰까지</div>
    </div>
  </div>

  <!-- Firebase SDK -->
  <script src="https://www.gstatic.com/firebasejs/10.7.0/firebase-app-compat.js"></script>
  <script src="https://www.gstatic.com/firebasejs/10.7.0/firebase-database-compat.js"></script>
  
  <script>
    // Firebase 설정
    const firebaseConfig = {
      apiKey: "AIzaSyB2hVbtkPLrAgIcpcqj_Rc_Oq0d_xbD4ms",
      authDomain: "bandle-99a28.firebaseapp.com",
      databaseURL: "https://bandle-99a28-default-rtdb.firebaseio.com",
      projectId: "bandle-99a28",
      storageBucket: "bandle-99a28.firebasestorage.app",
      messagingSenderId: "98824342460",
      appId: "1:98824342460:web:fc37e17f2fcf6d75a179b9"
    };
    
    // Firebase 초기화
    firebase.initializeApp(firebaseConfig);
    const db = firebase.database();
    
    // 상수
    const POSITIONS = {
      top: { name: '탑', icon: '⚔️', color: '#FF6B35' },
      jungle: { name: '정글', icon: '🌲', color: '#4ADE80' },
      mid: { name: '미드', icon: '✨', color: '#A78BFA' },
      adc: { name: '원딜', icon: '🏹', color: '#F87171' },
      support: { name: '서폿', icon: '🛡️', color: '#00D9FF' }
    };
    
    const TEAM_COLORS = ['#00D9FF', '#FF6B35', '#4ADE80', '#A78BFA', '#FFE66D', '#F87171', '#38BDF8', '#FB923C'];
    
    // 상태
    let currentRoom = null;
    let currentUser = { role: null, oderId: null };
    let currentBidAmount = 5;
    let roomListener = null;
    
    // 타이머 관련
    let timerInterval = null;
    let localTimeLeft = 0;
    let lastTimerSync = 0;
    
    // 방 코드 생성
    function generateRoomCode() {
      const chars = 'ABCDEFGHJKLMNPQRSTUVWXYZ23456789';
      let code = '';
      for (let i = 0; i < 6; i++) {
        code += chars[Math.floor(Math.random() * chars.length)];
      }
      return code;
    }
    
    // 화면 전환
    function showScreen(screenId) {
      document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));
      document.getElementById(screenId).classList.add('active');
    }
    
    // 토스트 메시지
    function showToast(message, type = 'info') {
      const toast = document.createElement('div');
      toast.className = `toast toast-${type}`;
      toast.textContent = message;
      document.body.appendChild(toast);
      setTimeout(() => toast.remove(), 3000);
    }
    
    // 방 코드 복사
    function copyRoomCode() {
      if (currentRoom) {
        navigator.clipboard.writeText(currentRoom.id);
        showToast('방 코드가 복사되었습니다!', 'success');
      }
    }
    
    // 방 생성
    async function createRoom() {
      const teamCount = parseInt(document.getElementById('createTeamCount').value);
      const budget = parseInt(document.getElementById('createBudget').value);
      const minBid = parseInt(document.getElementById('createMinBid').value);
      const bidIncrement = parseInt(document.getElementById('createBidIncrement').value);
      const timeLimit = parseInt(document.getElementById('createTimeLimit').value);
      
      const roomCode = generateRoomCode();
      
      const roomData = {
        id: roomCode,
        settings: { teamCount, budget, minBid, bidIncrement, timeLimit },
        teams: {},
        players: {},
        auction: {
          status: 'waiting',
          currentPlayerId: null,
          currentIndex: 0,
          bids: {},
          history: {},
          timer: {
            endTime: null,
            paused: false,
            pausedAt: null
          }
        },
        createdAt: Date.now()
      };
      
      try {
        await db.ref(`rooms/${roomCode}`).set(roomData);
        currentUser = { role: 'admin', oderId: null };
        currentBidAmount = minBid;
        subscribeToRoom(roomCode);
        showToast('방이 생성되었습니다!', 'success');
      } catch (error) {
        showToast('방 생성 실패: ' + error.message, 'error');
      }
    }
    
    // 방 참가
    async function joinRoom() {
      const roomCode = document.getElementById('joinRoomCode').value.toUpperCase().trim();
      const teamName = document.getElementById('joinTeamName').value.trim();
      const captainName = document.getElementById('joinCaptainName').value.trim();
      
      if (!roomCode || !teamName || !captainName) {
        showToast('모든 정보를 입력해주세요!', 'error');
        return;
      }
      
      try {
        const snapshot = await db.ref(`rooms/${roomCode}`).once('value');
        if (!snapshot.exists()) {
          showToast('방을 찾을 수 없습니다!', 'error');
          return;
        }
        
        const room = snapshot.val();
        const teamCount = Object.keys(room.teams || {}).length;
        
        if (teamCount >= room.settings.teamCount) {
          showToast('팀이 가득 찼습니다!', 'error');
          return;
        }
        
        if (room.auction.status !== 'waiting') {
          showToast('이미 경매가 시작된 방입니다!', 'error');
          return;
        }
        
        const oderId = `team_${Date.now()}`;
        const teamData = {
          id: oderId,
          name: teamName,
          captain: captainName,
          budget: room.settings.budget,
          players: {},
          color: TEAM_COLORS[teamCount],
          joinedAt: Date.now()
        };
        
        await db.ref(`rooms/${roomCode}/teams/${oderId}`).set(teamData);
        
        currentUser = { role: 'captain', oderId };
        currentBidAmount = room.settings.minBid;
        subscribeToRoom(roomCode);
        showToast('참가 완료!', 'success');
      } catch (error) {
        showToast('참가 실패: ' + error.message, 'error');
      }
    }
    
    // 방 구독
    function subscribeToRoom(roomCode) {
      if (roomListener) {
        db.ref(`rooms/${currentRoom?.id}`).off('value', roomListener);
      }
      
      roomListener = db.ref(`rooms/${roomCode}`).on('value', (snapshot) => {
        if (snapshot.exists()) {
          currentRoom = snapshot.val();
          renderRoom();
          syncTimer();
        }
      });
    }
    
    // 타이머 동기화
    function syncTimer() {
      if (!currentRoom || currentRoom.auction.status !== 'bidding') {
        stopLocalTimer();
        return;
      }
      
      const timer = currentRoom.auction.timer;
      if (!timer || !timer.endTime) return;
      
      if (timer.paused) {
        stopLocalTimer();
        localTimeLeft = Math.max(0, Math.ceil((timer.pausedAt - Date.now()) / 1000) + Math.ceil((timer.endTime - timer.pausedAt) / 1000));
        updateTimerDisplay(localTimeLeft);
        return;
      }
      
      const now = Date.now();
      localTimeLeft = Math.max(0, Math.ceil((timer.endTime - now) / 1000));
      
      // 로컬 타이머 시작
      if (!timerInterval) {
        startLocalTimer();
      }
      
      updateTimerDisplay(localTimeLeft);
    }
    
    // 로컬 타이머 시작
    function startLocalTimer() {
      stopLocalTimer();
      
      timerInterval = setInterval(() => {
        localTimeLeft--;
        
        if (localTimeLeft <= 0) {
          localTimeLeft = 0;
          stopLocalTimer();
          
          // 관리자만 자동 낙찰 처리
          if (currentUser.role === 'admin') {
            autoFinalize();
          }
        }
        
        updateTimerDisplay(localTimeLeft);
      }, 1000);
    }
    
    // 로컬 타이머 정지
    function stopLocalTimer() {
      if (timerInterval) {
        clearInterval(timerInterval);
        timerInterval = null;
      }
    }
    
    // 타이머 표시 업데이트
    function updateTimerDisplay(seconds) {
      const display = document.getElementById('timerDisplay');
      const barFill = document.getElementById('timerBarFill');
      
      if (!display || !barFill || !currentRoom) return;
      
      const timeLimit = currentRoom.settings.timeLimit;
      const percentage = (seconds / timeLimit) * 100;
      
      display.textContent = seconds;
      barFill.style.width = percentage + '%';
      
      // 색상 변경
      display.classList.remove('warning', 'danger');
      barFill.classList.remove('warning', 'danger');
      
      if (seconds <= 5) {
        display.classList.add('danger');
        barFill.classList.add('danger');
      } else if (seconds <= 10) {
        display.classList.add('warning');
        barFill.classList.add('warning');
      }
      
      // 카운트다운 오버레이
      const overlay = document.getElementById('countdownOverlay');
      const countdownNumber = document.getElementById('countdownNumber');
      
      if (seconds <= 3 && seconds > 0) {
        overlay.style.display = 'flex';
        countdownNumber.textContent = seconds;
      } else {
        overlay.style.display = 'none';
      }
    }
    
    // 자동 낙찰 (타이머 종료 시)
    async function autoFinalize() {
      if (currentUser.role !== 'admin' || !currentRoom) return;
      
      showToast('⏱️ 시간 종료! 자동 낙찰 처리중...', 'info');
      await finalizeAuction();
    }
    
    // 타이머 일시정지 (관리자)
    async function pauseTimer() {
      if (currentUser.role !== 'admin' || !currentRoom) return;
      
      try {
        await db.ref(`rooms/${currentRoom.id}/auction/timer`).update({
          paused: true,
          pausedAt: Date.now()
        });
        showToast('타이머 일시정지', 'info');
      } catch (error) {
        showToast('실패', 'error');
      }
    }
    
    // 타이머 재개 (관리자)
    async function resumeTimer() {
      if (currentUser.role !== 'admin' || !currentRoom) return;
      
      const timer = currentRoom.auction.timer;
      if (!timer || !timer.paused) return;
      
      const pausedDuration = Date.now() - timer.pausedAt;
      const newEndTime = timer.endTime + pausedDuration;
      
      try {
        await db.ref(`rooms/${currentRoom.id}/auction/timer`).update({
          paused: false,
          pausedAt: null,
          endTime: newEndTime
        });
        showToast('타이머 재개', 'info');
      } catch (error) {
        showToast('실패', 'error');
      }
    }
    
    // 타이머 리셋 (관리자)
    async function resetTimer() {
      if (currentUser.role !== 'admin' || !currentRoom) return;
      
      const timeLimit = currentRoom.settings.timeLimit;
      const newEndTime = Date.now() + (timeLimit * 1000);
      
      try {
        await db.ref(`rooms/${currentRoom.id}/auction/timer`).update({
          endTime: newEndTime,
          paused: false,
          pausedAt: null
        });
        showToast('타이머 리셋', 'info');
      } catch (error) {
        showToast('실패', 'error');
      }
    }
    
    // 방 렌더링
    function renderRoom() {
      if (!currentRoom) return;
      
      if (currentRoom.auction.status === 'complete') {
        stopLocalTimer();
        renderResult();
        showScreen('resultScreen');
      } else if (currentRoom.auction.status === 'bidding') {
        renderAuction();
        showScreen('auctionScreen');
      } else {
        stopLocalTimer();
        renderLobby();
        showScreen('lobbyScreen');
      }
    }
    
    // 로비 렌더링
    function renderLobby() {
      const room = currentRoom;
      
      document.getElementById('lobbyRoomCode').textContent = room.id;
      document.getElementById('lobbyBudget').textContent = room.settings.budget;
      document.getElementById('lobbyIncrement').textContent = room.settings.bidIncrement;
      document.getElementById('lobbyTimeLimit').textContent = room.settings.timeLimit;
      
      const roleBadge = document.getElementById('lobbyRoleBadge');
      if (currentUser.role === 'admin') {
        roleBadge.className = 'role-badge role-admin';
        roleBadge.textContent = '👑 관리자';
        document.getElementById('playerManagement').style.display = 'block';
        document.getElementById('lobbyFooter').style.display = 'block';
      } else {
        roleBadge.className = 'role-badge role-captain';
        roleBadge.textContent = '🎯 팀장';
        document.getElementById('playerManagement').style.display = 'none';
        document.getElementById('lobbyFooter').style.display = 'none';
      }
      
      const teams = Object.values(room.teams || {});
      document.getElementById('lobbyTeamCount').textContent = teams.length;
      document.getElementById('lobbyMaxTeams').textContent = room.settings.teamCount;
      
      const teamsGrid = document.getElementById('lobbyTeamsGrid');
      let teamsHTML = '';
      
      teams.forEach(team => {
        const isMyTeam = team.id === currentUser.oderId;
        const teamPlayers = Object.values(team.players || {});
        
        teamsHTML += `
          <div class="team-card ${isMyTeam ? 'my-team' : ''}">
            <div class="team-header">
              <span class="team-name" style="color: ${team.color}">${team.name}</span>
              <span class="team-budget">${team.budget}P</span>
            </div>
            <div class="team-captain">👑 ${team.captain}</div>
            <div class="online-indicator">
              <span class="online-dot"></span> 접속중
            </div>
            ${teamPlayers.length > 0 ? `
              <div class="team-players-list">
                ${teamPlayers.map(p => `
                  <div class="team-player-row">
                    <span>${POSITIONS[p.position].icon} ${p.name}</span>
                    <span>${p.price}P</span>
                  </div>
                `).join('')}
              </div>
            ` : ''}
          </div>
        `;
      });
      
      for (let i = teams.length; i < room.settings.teamCount; i++) {
        teamsHTML += `
          <div class="team-card empty">
            <div style="text-align: center; color: #5B5A56; padding: 20px;">
              대기중...
            </div>
          </div>
        `;
      }
      
      teamsGrid.innerHTML = teamsHTML;
      
      // 선수 목록 세분화
      const allPlayers = Object.values(room.players || {});
      const availablePlayers = allPlayers.filter(p => p.status === 'available');
      const passedPlayers = allPlayers.filter(p => p.status === 'passed');
      const soldPlayers = allPlayers.filter(p => p.status === 'sold');
      
      // 대기 선수
      document.getElementById('lobbyAvailableCount').textContent = availablePlayers.length;
      const availableList = document.getElementById('lobbyAvailableList');
      if (availablePlayers.length === 0) {
        availableList.innerHTML = '<div style="text-align: center; color: #5B5A56; padding: 20px;">등록된 선수가 없습니다</div>';
      } else {
        availableList.innerHTML = availablePlayers.map(player => `
          <div class="player-item">
            <span class="player-pos pos-${player.position}">${POSITIONS[player.position].icon} ${POSITIONS[player.position].name}</span>
            <span class="player-name">${player.name}</span>
            <span class="player-tier tier-${player.tier}">${player.tier}</span>
            ${player.note ? `<span style="color: #888; font-size: 12px;">${player.note}</span>` : ''}
            ${currentUser.role === 'admin' ? `
              <button class="player-remove" onclick="removePlayer('${player.id}')">✕</button>
            ` : ''}
          </div>
        `).join('');
      }
      
      // 유찰 선수 (재경매 대기)
      const passedSection = document.getElementById('passedSection');
      if (passedPlayers.length > 0) {
        passedSection.style.display = 'block';
        document.getElementById('lobbyPassedCount').textContent = passedPlayers.length;
        document.getElementById('lobbyPassedList').innerHTML = passedPlayers.map(player => `
          <div class="player-item" style="border-left: 3px solid #E67E22;">
            <span class="player-pos pos-${player.position}">${POSITIONS[player.position].icon} ${POSITIONS[player.position].name}</span>
            <span class="player-name">${player.name}</span>
            <span class="player-tier tier-${player.tier}">${player.tier}</span>
            <span style="color: #E67E22; font-size: 12px; font-weight: 700;">🔄 재경매 대기</span>
          </div>
        `).join('');
      } else {
        passedSection.style.display = 'none';
      }
      
      // 낙찰 완료 선수
      const soldSection = document.getElementById('soldSection');
      if (soldPlayers.length > 0) {
        soldSection.style.display = 'block';
        document.getElementById('lobbySoldCount').textContent = soldPlayers.length;
        document.getElementById('lobbySoldList').innerHTML = soldPlayers.map(player => {
          const winnerTeam = player.soldTo ? teams.find(t => t.id === player.soldTo) : null;
          return `
            <div class="player-item" style="border-left: 3px solid #1E9B6C; opacity: 0.8;">
              <span class="player-pos pos-${player.position}">${POSITIONS[player.position].icon} ${POSITIONS[player.position].name}</span>
              <span class="player-name">${player.name}</span>
              <span class="player-tier tier-${player.tier}">${player.tier}</span>
              <span style="color: #1E9B6C; font-size: 12px; font-weight: 700;">
                → ${winnerTeam ? winnerTeam.name : '유찰'} ${player.soldPrice > 0 ? `(${player.soldPrice}P)` : ''}
              </span>
            </div>
          `;
        }).join('');
      } else {
        soldSection.style.display = 'none';
      }
      
      const canStart = teams.length >= 2 && (availablePlayers.length >= 1 || passedPlayers.length >= 1);
      document.getElementById('startAuctionBtn').disabled = !canStart;
      document.getElementById('startAuctionHint').textContent = canStart ? '' : '최소 2팀, 1명 이상의 선수가 필요합니다';
    }
    
    // 선수 추가
    async function addPlayer() {
      if (currentUser.role !== 'admin') return;
      
      const name = document.getElementById('addPlayerName').value.trim();
      const position = document.getElementById('addPlayerPos').value;
      const tier = document.getElementById('addPlayerTier').value;
      const note = document.getElementById('addPlayerNote').value.trim();
      
      if (!name) {
        showToast('소환사명을 입력하세요!', 'error');
        return;
      }
      
      const playerId = `player_${Date.now()}`;
      const playerData = {
        id: playerId,
        name,
        position,
        tier,
        note,
        status: 'available',
        soldTo: null,
        soldPrice: null
      };
      
      try {
        await db.ref(`rooms/${currentRoom.id}/players/${playerId}`).set(playerData);
        document.getElementById('addPlayerName').value = '';
        document.getElementById('addPlayerNote').value = '';
        showToast('선수가 추가되었습니다!', 'success');
      } catch (error) {
        showToast('선수 추가 실패', 'error');
      }
    }
    
    // 선수 삭제
    async function removePlayer(playerId) {
      if (currentUser.role !== 'admin') return;
      
      try {
        await db.ref(`rooms/${currentRoom.id}/players/${playerId}`).remove();
        showToast('선수가 삭제되었습니다', 'success');
      } catch (error) {
        showToast('삭제 실패', 'error');
      }
    }
    
    // 경매 시작
    async function startAuction() {
      if (currentUser.role !== 'admin') return;
      
      const players = Object.values(currentRoom.players || {}).filter(p => p.status === 'available');
      if (players.length === 0) {
        showToast('경매할 선수가 없습니다!', 'error');
        return;
      }
      
      const timeLimit = currentRoom.settings.timeLimit;
      const endTime = Date.now() + (timeLimit * 1000);
      
      try {
        await db.ref(`rooms/${currentRoom.id}/auction`).update({
          status: 'bidding',
          currentPlayerId: players[0].id,
          currentIndex: 0,
          bids: {},
          timer: {
            endTime: endTime,
            paused: false,
            pausedAt: null
          }
        });
        showToast('경매가 시작되었습니다!', 'success');
      } catch (error) {
        showToast('경매 시작 실패', 'error');
      }
    }
    
    // 경매 화면 렌더링
    function renderAuction() {
      const room = currentRoom;
      const players = Object.values(room.players || {});
      const availablePlayers = players.filter(p => p.status === 'available');
      const passedPlayers = players.filter(p => p.status === 'passed');
      const soldPlayers = players.filter(p => p.status === 'sold');
      const currentPlayer = players.find(p => p.id === room.auction.currentPlayerId);
      const teams = Object.values(room.teams || {});
      const bids = room.auction.bids || {};
      const history = Object.values(room.auction.history || {});
      const currentRound = room.auction.round || 1;
      
      // 라운드 표시
      document.getElementById('auctionRound').textContent = `${currentRound}라운드`;
      
      // 진행률 (현재 선수 제외한 남은 available)
      const remainingCount = availablePlayers.length - 1; // 현재 선수 제외
      document.getElementById('auctionCurrent').textContent = soldPlayers.length + 1;
      document.getElementById('auctionTotal').textContent = players.length;
      
      // 선수 현황 요약
      const summaryEl = document.getElementById('playerStatusSummary');
      summaryEl.innerHTML = `
        <span class="status-badge status-available">⏳ 대기: ${availablePlayers.length}명</span>
        <span class="status-badge status-passed">🔄 유찰: ${passedPlayers.length}명</span>
        <span class="status-badge status-sold">✅ 완료: ${soldPlayers.length}명</span>
      `;
      
      if (currentPlayer) {
        const pos = POSITIONS[currentPlayer.position];
        document.getElementById('currentPlayerPos').className = `current-player-pos pos-${currentPlayer.position}`;
        document.getElementById('currentPlayerPos').innerHTML = `${pos.icon} ${pos.name}`;
        document.getElementById('currentPlayerPos').style.background = pos.color;
        document.getElementById('currentPlayerName').textContent = currentPlayer.name;
        document.getElementById('currentPlayerTier').className = `current-player-tier tier-${currentPlayer.tier}`;
        document.getElementById('currentPlayerTier').textContent = currentPlayer.tier;
        document.getElementById('currentPlayerNote').textContent = currentPlayer.note ? `📝 ${currentPlayer.note}` : '';
      }
      
      let highestBid = 0;
      let highestTeamId = null;
      Object.entries(bids).forEach(([oderId, bid]) => {
        if (!bid.pass && bid.amount > highestBid) {
          highestBid = bid.amount;
          highestTeamId = oderId;
        }
      });
      
      const bidGrid = document.getElementById('bidStatusGrid');
      bidGrid.innerHTML = teams.map(team => {
        const bid = bids[team.id];
        const isLeading = team.id === highestTeamId;
        const isMyTeam = team.id === currentUser.oderId;
        const playerCount = Object.keys(team.players || {}).length;
        const isFull = playerCount >= MAX_PLAYERS_PER_TEAM;
        
        return `
          <div class="bid-status-card ${isLeading ? 'leading' : ''} ${isMyTeam ? 'my-team' : ''} ${isFull ? 'full' : ''}">
            ${isLeading ? '<span class="leading-badge">👑 최고가</span>' : ''}
            ${isFull ? '<span class="full-badge">🚫 마감</span>' : ''}
            <div class="bid-team-name" style="color: ${team.color}">${team.name}</div>
            <div class="bid-team-budget">잔여: ${team.budget}P · 영입: ${playerCount}/${MAX_PLAYERS_PER_TEAM}명</div>
            <div class="bid-amount-display ${!bid ? 'no-bid' : ''} ${bid?.pass ? 'pass' : ''}">
              ${isFull ? '입찰 불가' : (!bid ? '입찰 대기' : (bid.pass ? 'PASS' : `${bid.amount}P`))}
            </div>
          </div>
        `;
      }).join('');
      
      const myTeam = teams.find(t => t.id === currentUser.oderId);
      const bidControls = document.getElementById('bidControls');
      
      if (currentUser.role === 'captain' && myTeam) {
        const myPlayerCount = Object.keys(myTeam.players || {}).length;
        const isFull = myPlayerCount >= MAX_PLAYERS_PER_TEAM;
        
        bidControls.style.display = 'block';
        
        if (isFull) {
          bidControls.classList.add('disabled');
          bidControls.innerHTML = `
            <div style="text-align: center; padding: 40px;">
              <div style="font-size: 48px; margin-bottom: 16px;">🎉</div>
              <div style="font-size: 20px; color: #1E9B6C; font-weight: 700;">팀 구성 완료!</div>
              <div style="color: #888; margin-top: 8px;">${MAX_PLAYERS_PER_TEAM}명 모두 영입했습니다</div>
            </div>
          `;
        } else {
          bidControls.classList.remove('disabled');
          document.getElementById('myTeamName').textContent = myTeam.name;
          document.getElementById('myTeamBudget').textContent = myTeam.budget;
          document.getElementById('bidValue').textContent = currentBidAmount;
          document.getElementById('currentHighestBid').textContent = highestBid;
          document.getElementById('currentHighestTeam').textContent = highestTeamId ? teams.find(t => t.id === highestTeamId)?.name || '-' : '-';
        }
      } else {
        bidControls.style.display = currentUser.role === 'admin' ? 'none' : 'block';
        if (currentUser.role !== 'captain') {
          bidControls.innerHTML = '<div style="text-align: center; color: #888;">관전 중</div>';
        }
      }
      
      document.getElementById('adminAuctionControls').style.display = currentUser.role === 'admin' ? 'block' : 'none';
      
      const historyEl = document.getElementById('auctionHistory');
      if (history.length === 0) {
        historyEl.innerHTML = '<div style="text-align: center; color: #5B5A56;">기록 없음</div>';
      } else {
        historyEl.innerHTML = history.slice().reverse().map(h => `
          <div class="history-item">
            <span class="history-player">${h.playerName}</span>
            <span class="history-arrow">→</span>
            <span class="history-winner">${h.winnerName || '유찰'}</span>
            <span class="history-price">${h.price > 0 ? h.price + 'P' : ''}</span>
          </div>
        `).join('');
      }
    }
    
    // 입찰 금액 조절
    function adjustBid(direction) {
      if (!currentRoom) return;
      const increment = currentRoom.settings.bidIncrement;
      const minBid = currentRoom.settings.minBid;
      const myTeam = Object.values(currentRoom.teams || {}).find(t => t.id === currentUser.oderId);
      const maxBid = myTeam ? myTeam.budget : 0;
      
      currentBidAmount += direction * increment;
      if (currentBidAmount < minBid) currentBidAmount = minBid;
      if (currentBidAmount > maxBid) currentBidAmount = maxBid;
      
      document.getElementById('bidValue').textContent = currentBidAmount;
    }
    
    // 빠른 입찰
    function setQuickBid(amount) {
      const myTeam = Object.values(currentRoom.teams || {}).find(t => t.id === currentUser.oderId);
      const maxBid = myTeam ? myTeam.budget : 0;
      
      currentBidAmount = Math.min(amount, maxBid);
      document.getElementById('bidValue').textContent = currentBidAmount;
    }
    
    // 올인
    function setBidToMax() {
      const myTeam = Object.values(currentRoom.teams || {}).find(t => t.id === currentUser.oderId);
      if (myTeam) {
        currentBidAmount = myTeam.budget;
        document.getElementById('bidValue').textContent = currentBidAmount;
      }
    }
    
    // 입찰 제출
    async function submitBid() {
      if (currentUser.role !== 'captain' || !currentUser.oderId) return;
      
      const myTeam = Object.values(currentRoom.teams || {}).find(t => t.id === currentUser.oderId);
      if (!myTeam) return;
      
      // 팀당 최대 인원 제한 체크
      const myPlayerCount = Object.keys(myTeam.players || {}).length;
      if (myPlayerCount >= MAX_PLAYERS_PER_TEAM) {
        showToast(`이미 ${MAX_PLAYERS_PER_TEAM}명을 영입했습니다! 더 이상 입찰할 수 없어요.`, 'error');
        return;
      }
      
      if (currentBidAmount > myTeam.budget) {
        showToast('예산이 부족합니다!', 'error');
        return;
      }
      
      // 현재 최고가보다 높은지 확인
      const bids = currentRoom.auction.bids || {};
      let highestBid = 0;
      Object.values(bids).forEach(bid => {
        if (!bid.pass && bid.amount > highestBid) {
          highestBid = bid.amount;
        }
      });
      
      if (currentBidAmount <= highestBid) {
        showToast(`현재 최고가(${highestBid}P)보다 높게 입찰하세요!`, 'error');
        return;
      }
      
      try {
        // 타이머 갱신 (입찰할 때마다 리셋)
        const timeLimit = currentRoom.settings.timeLimit;
        const newEndTime = Date.now() + (timeLimit * 1000);
        
        await db.ref(`rooms/${currentRoom.id}/auction/bids/${currentUser.oderId}`).set({
          amount: currentBidAmount,
          pass: false,
          timestamp: Date.now()
        });
        
        // 타이머 리셋
        await db.ref(`rooms/${currentRoom.id}/auction/timer`).update({
          endTime: newEndTime,
          paused: false,
          pausedAt: null
        });
        
        showToast(`${currentBidAmount}P 입찰! ⏱️ 타이머 리셋`, 'success');
      } catch (error) {
        showToast('입찰 실패', 'error');
      }
    }
    
    // 패스
    async function submitPass() {
      if (currentUser.role !== 'captain' || !currentUser.oderId) return;
      
      try {
        await db.ref(`rooms/${currentRoom.id}/auction/bids/${currentUser.oderId}`).set({
          amount: 0,
          pass: true,
          timestamp: Date.now()
        });
        showToast('PASS 완료', 'info');
      } catch (error) {
        showToast('패스 실패', 'error');
      }
    }
    
    // 낙찰 확정
    // 최대 팀원 수
    const MAX_PLAYERS_PER_TEAM = 4;
    
    async function finalizeAuction() {
      if (currentUser.role !== 'admin') return;
      
      const room = currentRoom;
      const bids = room.auction.bids || {};
      const currentPlayer = Object.values(room.players || {}).find(p => p.id === room.auction.currentPlayerId);
      const teams = Object.values(room.teams || {});
      
      if (!currentPlayer) return;
      
      // 팀당 인원 제한 체크하여 유효한 입찰만 필터링
      let highestBid = 0;
      let winnerId = null;
      Object.entries(bids).forEach(([oderId, bid]) => {
        const team = teams.find(t => t.id === oderId);
        const teamPlayerCount = Object.keys(team?.players || {}).length;
        
        // 이미 4명 이상이면 입찰 무효
        if (teamPlayerCount >= MAX_PLAYERS_PER_TEAM) return;
        
        if (!bid.pass && bid.amount > highestBid) {
          highestBid = bid.amount;
          winnerId = oderId;
        }
      });
      
      try {
        if (winnerId && highestBid > 0) {
          const winnerTeam = teams.find(t => t.id === winnerId);
          
          await db.ref(`rooms/${room.id}/players/${currentPlayer.id}`).update({
            status: 'sold',
            soldTo: winnerId,
            soldPrice: highestBid
          });
          
          await db.ref(`rooms/${room.id}/teams/${winnerId}`).update({
            budget: winnerTeam.budget - highestBid,
            [`players/${currentPlayer.id}`]: {
              id: currentPlayer.id,
              name: currentPlayer.name,
              position: currentPlayer.position,
              price: highestBid
            }
          });
          
          const historyId = `history_${Date.now()}`;
          await db.ref(`rooms/${room.id}/auction/history/${historyId}`).set({
            playerId: currentPlayer.id,
            playerName: currentPlayer.name,
            winnerId: winnerId,
            winnerName: winnerTeam.name,
            price: highestBid,
            timestamp: Date.now()
          });
          
          showToast(`${currentPlayer.name} → ${winnerTeam.name} (${highestBid}P) 낙찰!`, 'success');
        } else {
          await db.ref(`rooms/${room.id}/players/${currentPlayer.id}`).update({
            status: 'sold',
            soldTo: null,
            soldPrice: 0
          });
          
          const historyId = `history_${Date.now()}`;
          await db.ref(`rooms/${room.id}/auction/history/${historyId}`).set({
            playerId: currentPlayer.id,
            playerName: currentPlayer.name,
            winnerId: null,
            winnerName: '유찰',
            price: 0,
            timestamp: Date.now()
          });
          
          showToast(`${currentPlayer.name} 유찰`, 'info');
        }
        
        await moveToNextPlayer();
      } catch (error) {
        showToast('처리 실패: ' + error.message, 'error');
      }
    }
    
    // 유찰
    async function skipPlayer() {
      if (currentUser.role !== 'admin') return;
      
      const currentPlayer = Object.values(currentRoom.players || {}).find(p => p.id === currentRoom.auction.currentPlayerId);
      if (!currentPlayer) return;
      
      try {
        // 유찰 선수는 'passed' 상태로 변경 (나중에 재경매)
        await db.ref(`rooms/${currentRoom.id}/players/${currentPlayer.id}`).update({
          status: 'passed',
          soldTo: null,
          soldPrice: 0
        });
        
        const historyId = `history_${Date.now()}`;
        await db.ref(`rooms/${currentRoom.id}/auction/history/${historyId}`).set({
          playerId: currentPlayer.id,
          playerName: currentPlayer.name,
          winnerId: null,
          winnerName: '유찰',
          price: 0,
          timestamp: Date.now()
        });
        
        showToast(`${currentPlayer.name} 유찰 (재경매 대기)`, 'info');
        await moveToNextPlayer();
      } catch (error) {
        showToast('처리 실패', 'error');
      }
    }
    
    // 다음 선수로 이동
    async function moveToNextPlayer() {
      const allPlayers = Object.values(currentRoom.players || {});
      const availablePlayers = allPlayers.filter(p => p.status === 'available');
      const passedPlayers = allPlayers.filter(p => p.status === 'passed');
      
      // 1. 먼저 available 선수 처리
      if (availablePlayers.length > 0) {
        const timeLimit = currentRoom.settings.timeLimit;
        const newEndTime = Date.now() + (timeLimit * 1000);
        
        await db.ref(`rooms/${currentRoom.id}/auction`).update({
          currentPlayerId: availablePlayers[0].id,
          currentIndex: currentRoom.auction.currentIndex + 1,
          bids: {},
          round: currentRoom.auction.round || 1,
          timer: {
            endTime: newEndTime,
            paused: false,
            pausedAt: null
          }
        });
        currentBidAmount = currentRoom.settings.minBid;
        return;
      }
      
      // 2. available 없고, passed 선수가 있으면 재경매 라운드 시작
      if (passedPlayers.length > 0) {
        const currentRound = currentRoom.auction.round || 1;
        
        // 유찰 선수들을 다시 available로 변경
        const updates = {};
        passedPlayers.forEach(p => {
          updates[`players/${p.id}/status`] = 'available';
        });
        
        const timeLimit = currentRoom.settings.timeLimit;
        const newEndTime = Date.now() + (timeLimit * 1000);
        
        updates['auction/currentPlayerId'] = passedPlayers[0].id;
        updates['auction/currentIndex'] = currentRoom.auction.currentIndex + 1;
        updates['auction/bids'] = {};
        updates['auction/round'] = currentRound + 1;
        updates['auction/timer'] = {
          endTime: newEndTime,
          paused: false,
          pausedAt: null
        };
        
        await db.ref(`rooms/${currentRoom.id}`).update(updates);
        currentBidAmount = currentRoom.settings.minBid;
        
        showToast(`🔄 ${currentRound + 1}라운드 시작! 유찰 선수 ${passedPlayers.length}명 재경매`, 'info');
        return;
      }
      
      // 3. 모두 처리됨 - 경매 완료
      await db.ref(`rooms/${currentRoom.id}/auction`).update({
        status: 'complete',
        currentPlayerId: null,
        bids: {},
        timer: {
          endTime: null,
          paused: false,
          pausedAt: null
        }
      });
    }
    
    // 결과 화면 렌더링
    function renderResult() {
      const teams = Object.values(currentRoom.teams || {});
      const resultTeams = document.getElementById('resultTeams');
      
      resultTeams.innerHTML = teams.map(team => {
        const teamPlayers = Object.values(team.players || {});
        const totalSpent = teamPlayers.reduce((sum, p) => sum + (p.price || 0), 0);
        
        return `
          <div class="team-card" style="border-color: ${team.color}">
            <div class="team-header">
              <span class="team-name" style="color: ${team.color}">${team.name}</span>
              <span class="team-budget">${team.budget}P</span>
            </div>
            <div class="team-captain">👑 ${team.captain}</div>
            <div style="font-size: 13px; color: #888; margin-top: 8px;">사용: ${totalSpent}P</div>
            <div class="team-players-list">
              ${teamPlayers.length > 0 ? teamPlayers.map(p => `
                <div class="team-player-row">
                  <span>${POSITIONS[p.position]?.icon || '?'} ${p.name}</span>
                  <span>${p.price}P</span>
                </div>
              `).join('') : '<div style="color: #5B5A56;">영입 선수 없음</div>'}
            </div>
          </div>
        `;
      }).join('');
    }
    
    // 입력 필드 자동 대문자
    document.getElementById('joinRoomCode')?.addEventListener('input', function(e) {
      this.value = this.value.toUpperCase();
    });
  </script>
</body>
</html>
