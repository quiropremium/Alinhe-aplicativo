<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alinhe - Postura Correta</title>

  <style>
    :root {
      --bg-color: #0b2230;
      --card-bg: #133347;
      --accent: #E5C158;
      --danger: #EF4444;
      --text: #FFFFFF;
      --subtext: #CBD5E1;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }

    body {
      background-color: #040c12;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .app-screen {
      width: 100%;
      max-width: 390px;
      height: 844px;
      background-color: var(--bg-color);
      color: var(--text);
      display: flex;
      flex-direction: column;
      padding: 20px;
      position: relative;
      border-radius: 30px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.5);
      overflow-y: auto;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-top: 10px;
      margin-bottom: 20px;
    }

    .page {
      display: flex;
      flex-direction: column;
      gap: 14px;
    }

    .hidden {
      display: none !important;
    }

    .card {
      background-color: var(--card-bg);
      border-radius: 16px;
      padding: 18px;
      text-align: center;
    }

    .status-badge {
      width: 65px;
      height: 65px;
      background-color: var(--accent);
      color: var(--bg-color);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 30px;
      font-weight: bold;
      margin: 0 auto 10px auto;
    }

    .btn {
      background-color: var(--accent);
      color: #0b2230;
      border: none;
      padding: 16px;
      border-radius: 14px;
      font-weight: bold;
      font-size: 16px;
      cursor: pointer;
      width: 100%;
    }

    .btn-secondary {
      background-color: transparent;
      border: 1px solid var(--accent);
      color: var(--accent);
      padding: 12px;
      border-radius: 10px;
      font-weight: bold;
      font-size: 14px;
      cursor: pointer;
      width: 100%;
    }

    .plan-card {
      background-color: var(--card-bg);
      border: 2px solid transparent;
      border-radius: 14px;
      padding: 16px;
      margin-bottom: 10px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      cursor: pointer;
    }

    .plan-card.active {
      border-color: var(--accent);
    }

    .tag {
      background-color: var(--accent);
      color: #0b2230;
      font-size: 11px;
      font-weight: bold;
      padding: 3px 8px;
      border-radius: 6px;
      margin-left: 8px;
    }

    .ad-banner {
      background-color: rgba(255, 255, 255, 0.05);
      border: 1px dashed var(--subtext);
      border-radius: 10px;
      padding: 12px;
      text-align: center;
      font-size: 12px;
      color: var(--subtext);
      margin-top: auto;
    }

    .stats-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }

    .stat-box {
      background-color: var(--card-bg);
      padding: 14px;
      border-radius: 14px;
      text-align: center;
    }

    .stat-number {
      font-size: 22px;
      font-weight: bold;
      color: var(--accent);
      margin-top: 4px;
    }

    .chart-container {
      display: flex;
      justify-content: space-between;
      align-items: flex-end;
      height: 110px;
      padding-top: 15px;
    }

    .bar-wrapper {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 6px;
    }

    .bar {
      width: 22px;
      border-radius: 6px;
      background-color: rgba(255, 255, 255, 0.1);
    }

    .bar.filled {
      background-color: var(--accent);
    }

    #camera-preview {
      display: none;
      width: 100%;
      height: 140px;
      object-fit: cover;
      border-radius: 12px;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <div class="app-screen">
    
    <!-- TELA 1: MAIN -->
    <div id="page-main" class="page">
      <div class="header">
        <div style="display: flex; align-items: center; gap: 10px;">
          <h2 style="font-size: 22px; color: var(--accent);">Alinhe</h2>
        </div>
        <button onclick="navigate('page-paywall')" id="btn-premium-badge" style="background:none; border:none; color:var(--accent); font-size:20px; cursor:pointer;">👑 Premium</button>
      </div>

      <div class="card" id="status-card">
        <div class="status-badge" id="status-badge">✓</div>
        <h3 id="status-title" style="font-size: 18px;">POSTURA ALINHADA!</h3>
        <p id="status-desc" style="color: var(--subtext); font-size: 14px; margin-top: 4px;">Celular na altura dos olhos</p>
      </div>

      <video id="camera-preview" autoplay playsinline></video>

      <div class="card" style="text-align: left; padding: 14px;">
        <h4 style="margin-bottom: 8px; font-size: 16px;">Como funciona:</h4>
        <p style="font-size: 13px; color: var(--subtext); margin-bottom: 6px;">📱 Mantenha o dispositivo paralelo ao rosto</p>
        <p style="font-size: 13px; color: var(--subtext);">🧍 O Alinhe vibrará se a cabeça inclinar</p>
      </div>

      <button class="btn" onclick="toggleMonitoring()" id="btn-monitor">INICIAR MONITORAMENTO</button>
      <button class="btn-secondary" onclick="calibrateCamera()">📷 Calibrar Câmera</button>
      <button class="btn-secondary" onclick="openStatsPage()">📊 Relatório de Postura <span id="lock-icon">🔒</span></button>

      <div class="ad-banner" id="ad-banner">
        Anúncio Patrocinado<br>
        <span style="text-decoration: underline; cursor: pointer; font-weight: bold; font-size: 13px;" onclick="navigate('page-paywall')">Remova anúncios no menu Premium</span>
      </div>
    </div>

    <!-- TELA 2: DASHBOARD / ESTATÍSTICAS -->
    <div id="page-stats" class="page hidden">
      <div class="header">
        <button onclick="navigate('page-main')" style="background:none; border:none; color:var(--text); font-size:18px; cursor:pointer;">← Voltar</button>
        <h3>Relatório de Qualidade</h3>
        <div style="width: 30px;"></div>
      </div>

      <div class="card" style="background: linear-gradient(135deg, #133347 0%, #0b2230 100%); border: 1px solid var(--accent);">
        <p style="font-size: 13px; color: var(--subtext);">Índice de Saúde Postural Hoje</p>
        <h1 style="font-size: 42px; color: var(--accent); margin: 6px 0;" id="score-percentage">85%</h1>
        <p style="font-size: 14px; font-weight: bold; color: var(--accent); margin-bottom: 4px;" id="motivational-phrase">"Incrível! Postura em dia e coluna protegida."</p>
        <p style="font-size: 12px; color: var(--subtext);" id="health-benefit">💡 Benefício: Previne o envelhecimento precoce das vértebras cervicais.</p>
      </div>

      <div class="stats-grid">
        <div class="stat-box">
          <p style="font-size: 12px; color: var(--subtext);">Postura Correta</p>
          <div class="stat-number">2h 45m</div>
        </div>
        <div class="stat-box">
          <p style="font-size: 12px; color: var(--subtext);">Cabeça Inclinada</p>
          <div class="stat-number" style="color: var(--danger);">28 min</div>
        </div>
      </div>

      <div class="card" style="text-align: left;">
        <h4 style="margin-bottom: 10px; font-size: 15px;">Evolução da Semana</h4>
        <div class="chart-container">
          <div class="bar-wrapper"><div class="bar filled" style="height: 50px;"></div><span style="font-size: 10px; color: var(--subtext);">Seg</span></div>
          <div class="bar-wrapper"><div class="bar filled" style="height: 70px;"></div><span style="font-size: 10px; color: var(--subtext);">Ter</span></div>
          <div class="bar-wrapper"><div class="bar filled" style="height: 40px;"></div><span style="font-size: 10px; color: var(--subtext);">Qua</span></div>
          <div class="bar-wrapper"><div class="bar filled" style="height: 85px;"></div><span style="font-size: 10px; color: var(--subtext);">Qui</span></div>
          <div class="bar-wrapper"><div class="bar filled" style="height: 75px;"></div><span style="font-size: 10px; color: var(--subtext);">Sex</span></div>
          <div class="bar-wrapper"><div class="bar" style="height: 25px;"></div><span style="font-size: 10px; color: var(--subtext);">Sáb</span></div>
          <div class="bar-wrapper"><div class="bar filled" style="height: 80px;"></div><span style="font-size: 10px; color: var(--subtext);">Dom</span></div>
        </div>
      </div>
    </div>

    <!-- TELA 3: PAYWALL / COMPRA -->
    <div id="page-paywall" class="page hidden">
      <div class="header">
        <button onclick="navigate('page-main')" style="background:none; border:none; color:var(--text); font-size:18px; cursor:pointer;">← Voltar</button>
        <div style="display: flex; align-items: center; gap: 8px;">
          <h3>Alinhe Premium</h3>
        </div>
        <div style="width: 30px;"></div>
      </div>

      <div style="text-align: center; margin-bottom: 8px;">
        <p style="color: var(--subtext); font-size: 14px;">Desbloqueie o relatório completo e remova anúncios</p>
      </div>

      <div class="plan-card active" onclick="selectPlan(this, 'https://mpago.la/SEU_LINK_ANUAL', 365)">
        <div>
          <strong style="font-size: 16px;">Plano Anual</strong><span class="tag">Economize 41%</span>
          <p style="font-size: 13px; color: var(--subtext); margin-top: 2px;">R$ 5,82/mês</p>
        </div>
        <div><strong style="font-size: 16px;">R$ 69,90/ano</strong></div>
      </div>

      <div class="plan-card" onclick="selectPlan(this, 'https://mpago.la/SEU_LINK_SEMESTRAL', 180)">
        <div>
          <strong style="font-size: 16px;">Plano Semestral</strong>
          <p style="font-size: 13px; color: var(--subtext); margin-top: 2px;">R$ 7,48/mês</p>
        </div>
        <div><strong style="font-size: 16px;">R$ 44,90/6m</strong></div>
      </div>

      <div class="plan-card" onclick="selectPlan(this, 'https://mpago.la/SEU_LINK_MENSAL', 30)">
        <div>
          <strong style="font-size: 16px;">Plano Mensal</strong>
          <p style="font-size: 13px; color: var(--subtext); margin-top: 2px;">Sem fidelidade</p>
        </div>
        <div><strong style="font-size: 16px;">R$ 9,90/mês</strong></div>
      </div>

      <button class="btn" onclick="processCheckout()">ASSINAR AGORA</button>
    </div>

  </div>

  <script>
    let checkoutUrl = "https://mpago.la/SEU_LINK_ANUAL";
    let selectedDays = 365;
    let isPremium = false;

    // Executa ao carregar a página de forma segura
    window.addEventListener('DOMContentLoaded', () => {
      const expirationDate = localStorage.getItem('alinhe_expiration');
      const now = new Date().getTime();

      if (expirationDate && now < parseInt(expirationDate)) {
        isPremium = true;
        const adBanner = document.getElementById('ad-banner');
        const lockIcon = document.getElementById('lock-icon');
        const badge = document.getElementById('btn-premium-badge');

        if (adBanner) adBanner.style.display = 'none';
        if (lockIcon) lockIcon.style.display = 'none';
        if (badge) badge.innerText = "✨ Ativo";
      }
    });

    function navigate(pageId) {
      document.getElementById('page-main').classList.add('hidden');
      document.getElementById('page-stats').classList.add('hidden');
      document.getElementById('page-paywall').classList.add('hidden');
      
      const target = document.getElementById(pageId);
      if (target) {
        target.classList.remove('hidden');
      }
    }

    function openStatsPage() {
      if (isPremium) {
        navigate('page-stats');
      } else {
        alert("Recurso exclusivo Premium! Assine para acessar suas estatísticas detalhadas.");
        navigate('page-paywall');
      }
    }

    async function calibrateCamera() {
      const video = document.getElementById('camera-preview');
      try {
        const stream = await navigator.mediaDevices.getUserMedia({ video: { facingMode: "user" } });
        video.srcObject = stream;
        video.style.display = "block";
        alert("Câmera conectada com sucesso!");
      } catch (err) {
        alert("Erro ao acessar a câmera. Certifique-se de usar HTTPS (Netlify) e permitir o acesso.");
      }
    }

    let isMonitoring = false;

    async function toggleMonitoring() {
      const btn = document.getElementById('btn-monitor');

      if (!isMonitoring) {
        if (typeof DeviceOrientationEvent !== 'undefined' && typeof DeviceOrientationEvent.requestPermission === 'function') {
          try {
            const permissionState = await DeviceOrientationEvent.requestPermission();
            if (permissionState !== 'granted') {
              alert('Permissão para o sensor negada.');
              return;
            }
          } catch (error) {
            console.error(error);
          }
        }

        window.addEventListener('deviceorientation', handleOrientation);
        isMonitoring = true;
        btn.innerText = "PARAR MONITORAMENTO";
        btn.style.backgroundColor = "var(--danger)";
        btn.style.color = "#FFFFFF";
      } else {
        window.removeEventListener('deviceorientation', handleOrientation);
        isMonitoring = false;
        btn.innerText = "INICIAR MONITORAMENTO";
        btn.style.backgroundColor = "var(--accent)";
        btn.style.color = "#0b2230";
        resetStatus();
      }
    }

    function handleOrientation(event) {
      let pitch = event.beta;
      const card = document.getElementById('status-card');
      const badge = document.getElementById('status-badge');
      const title = document.getElementById('status-title');
      const desc = document.getElementById('status-desc');

      if (pitch && pitch > 45) {
        if (card) card.style.backgroundColor = "#3B1818";
        if (badge) {
          badge.style.backgroundColor = "var(--danger)";
          badge.innerText = "⚠️";
        }
        if (title) title.innerText = "CORRIJA A POSTURA!";
        if (desc) desc.innerText = "Eleve o celular na altura dos olhos";

        if (navigator.vibrate) {
          navigator.vibrate(300);
        }
      } else {
        resetStatus();
      }
    }

    function resetStatus() {
      const card = document.getElementById('status-card');
      const badge = document.getElementById('status-badge');
      const title = document.getElementById('status-title');
      const desc = document.getElementById('status-desc');

      if (card) card.style.backgroundColor = "var(--card-bg)";
      if (badge) {
        badge.style.backgroundColor = "var(--accent)";
        badge.innerText = "✓";
      }
      if (title) title.innerText = "POSTURA ALINHADA!";
      if (desc) desc.innerText = "Celular na altura dos olhos";
    }

    function selectPlan(element, url, days) {
      document.querySelectorAll('.plan-card').forEach(card => card.classList.remove('active'));
      element.classList.add('active');
      checkoutUrl = url;
      selectedDays = days;
    }

    function processCheckout() {
      const expirationTime = new Date().getTime() + (selectedDays * 24 * 60 * 60 * 1000);
      localStorage.setItem('alinhe_expiration', expirationTime);
      window.open(checkoutUrl, '_blank');
      location.reload(); 
    }
  </script>
</body>
</html>
