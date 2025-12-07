<!doctype html>
<html lang="ar" dir="rtl">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>نظام تسجيل الدخول - Portarage</title>
  <script src="/_sdk/element_sdk.js"></script>
  <style>
    body {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #000000;
      color: #ffffff;
      height: 100%;
      width: 100%;
      overflow: auto;
      position: relative;
    }

    html {
      height: 100%;
      width: 100%;
    }

    * {
      box-sizing: border-box;
    }

    .animated-background {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: radial-gradient(ellipse at top, #1a0f00 0%, #000000 50%, #000000 100%);
      z-index: 0;
    }

    .animated-background::before {
      content: '';
      position: absolute;
      top: -50%;
      left: -50%;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle, rgba(218, 165, 32, 0.1) 0%, transparent 70%);
      animation: rotate 20s linear infinite;
    }

    @keyframes rotate {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    .particles {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      overflow: hidden;
      z-index: 1;
      pointer-events: none;
    }

    .particle {
      position: absolute;
      width: 3px;
      height: 3px;
      background: rgba(218, 165, 32, 0.5);
      border-radius: 50%;
      animation: float 15s infinite;
    }

    @keyframes float {
      0%, 100% {
        transform: translateY(0) translateX(0);
        opacity: 0;
      }
      10% {
        opacity: 1;
      }
      90% {
        opacity: 1;
      }
      100% {
        transform: translateY(-100%) translateX(100px);
        opacity: 0;
      }
    }

    .main-container {
      width: 100%;
      min-height: 100%;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 40px 20px;
      position: relative;
      z-index: 2;
    }

    .login-card {
      background: rgba(0, 0, 0, 0.7);
      backdrop-filter: blur(20px);
      border: 2px solid rgba(218, 165, 32, 0.3);
      border-radius: 30px;
      padding: 50px 40px;
      width: 100%;
      max-width: 500px;
      box-shadow: 0 20px 60px rgba(0, 0, 0, 0.8), 0 0 40px rgba(218, 165, 32, 0.1);
      position: relative;
      overflow: hidden;
    }

    .login-card::before {
      content: '';
      position: absolute;
      top: -2px;
      left: -2px;
      right: -2px;
      bottom: -2px;
      background: linear-gradient(45deg, #DAA520, #FFD700, #DAA520, #B8860B);
      background-size: 300% 300%;
      border-radius: 30px;
      z-index: -1;
      opacity: 0;
      transition: opacity 0.3s ease;
      animation: gradientShift 3s ease infinite;
    }

    .login-card:hover::before {
      opacity: 0.3;
    }

    @keyframes gradientShift {
      0%, 100% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
    }

    .logo-container {
      text-align: center;
      margin-bottom: 35px;
    }

    .logo {
      width: 200px;
      height: auto;
      margin-bottom: 25px;
      filter: drop-shadow(0 5px 15px rgba(218, 165, 32, 0.3));
      transition: transform 0.3s ease;
    }

    .logo:hover {
      transform: scale(1.05);
    }

    .login-title {
      font-size: 32px;
      font-weight: bold;
      text-align: center;
      margin-bottom: 10px;
      background: linear-gradient(135deg, #FFD700 0%, #DAA520 50%, #B8860B 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .login-subtitle {
      font-size: 16px;
      text-align: center;
      margin-bottom: 35px;
      color: #cccccc;
      font-weight: 400;
    }

    .form-group {
      margin-bottom: 25px;
      position: relative;
    }

    .form-label {
      display: block;
      margin-bottom: 10px;
      font-size: 15px;
      font-weight: 600;
      color: #DAA520;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }

    .input-wrapper {
      position: relative;
    }

    .form-input {
      width: 100%;
      padding: 16px 20px;
      background: rgba(255, 255, 255, 0.05);
      border: 2px solid rgba(218, 165, 32, 0.3);
      border-radius: 12px;
      color: #ffffff;
      font-size: 16px;
      transition: all 0.3s ease;
    }

    .form-input:focus {
      outline: none;
      border-color: rgba(255, 215, 0, 0.6);
      background: rgba(255, 255, 255, 0.08);
      box-shadow: 0 0 20px rgba(218, 165, 32, 0.2);
    }

    .form-input::placeholder {
      color: rgba(255, 255, 255, 0.3);
    }

    .login-button {
      width: 100%;
      padding: 18px;
      background: linear-gradient(135deg, #DAA520 0%, #FFD700 50%, #DAA520 100%);
      background-size: 200% 200%;
      border: none;
      border-radius: 12px;
      color: #000000;
      font-size: 18px;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.4s ease;
      margin-top: 15px;
      text-transform: uppercase;
      letter-spacing: 1px;
      box-shadow: 0 5px 20px rgba(218, 165, 32, 0.4);
      position: relative;
      overflow: hidden;
    }

    .login-button::before {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.3), transparent);
      transition: left 0.5s ease;
    }

    .login-button:hover::before {
      left: 100%;
    }

    .login-button:hover {
      background-position: 100% 0;
      transform: translateY(-3px);
      box-shadow: 0 8px 30px rgba(218, 165, 32, 0.6);
    }

    .login-button:active {
      transform: translateY(-1px);
    }

    .error-message {
      background: rgba(220, 53, 69, 0.15);
      border: 2px solid rgba(220, 53, 69, 0.5);
      color: #ff6b6b;
      padding: 14px;
      border-radius: 10px;
      margin-bottom: 25px;
      text-align: center;
      font-size: 14px;
      display: none;
      animation: shake 0.5s;
    }

    @keyframes shake {
      0%, 100% { transform: translateX(0); }
      25% { transform: translateX(-10px); }
      75% { transform: translateX(10px); }
    }

    .error-message.show {
      display: block;
    }

    .dashboard {
      display: none;
      width: 100%;
      height: 100%;
      position: fixed;
      top: 0;
      left: 0;
      background: #000000;
    }

    .dashboard.active {
      display: block;
    }

    .dashboard-header {
      background: linear-gradient(135deg, rgba(0, 0, 0, 0.95) 0%, rgba(26, 15, 0, 0.95) 100%);
      backdrop-filter: blur(10px);
      border-bottom: 2px solid rgba(218, 165, 32, 0.3);
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      z-index: 1000;
      box-shadow: 0 5px 20px rgba(0, 0, 0, 0.5);
    }

    .dashboard-logo {
      width: 120px;
      height: auto;
      filter: drop-shadow(0 3px 10px rgba(218, 165, 32, 0.3));
    }

    .logout-button {
      padding: 10px 24px;
      background: rgba(220, 53, 69, 0.2);
      border: 2px solid rgba(220, 53, 69, 0.5);
      border-radius: 8px;
      color: #ff6b6b;
      font-size: 15px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .logout-button:hover {
      background: rgba(220, 53, 69, 0.3);
      border-color: rgba(220, 53, 69, 0.7);
      transform: translateY(-2px);
    }

    .button-panel {
      position: fixed;
      right: 20px;
      top: 100px;
      display: flex;
      flex-direction: column;
      gap: 15px;
      z-index: 100;
      transition: all 0.3s ease;
    }

    .button-panel.hidden {
      opacity: 0;
      pointer-events: none;
      transform: translateX(100px);
    }

    .nav-button {
      padding: 18px 28px;
      background: rgba(0, 0, 0, 0.8);
      backdrop-filter: blur(10px);
      border: 2px solid rgba(218, 165, 32, 0.4);
      border-radius: 12px;
      color: #DAA520;
      font-size: 18px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s ease;
      text-align: center;
      min-width: 180px;
      position: relative;
      overflow: hidden;
    }

    .nav-button::before {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: linear-gradient(90deg, transparent, rgba(218, 165, 32, 0.2), transparent);
      transition: left 0.5s ease;
    }

    .nav-button:hover::before {
      left: 100%;
    }

    .nav-button:hover {
      background: rgba(218, 165, 32, 0.2);
      border-color: rgba(255, 215, 0, 0.6);
      transform: scale(1.05);
      box-shadow: 0 8px 25px rgba(218, 165, 32, 0.3);
      color: #FFD700;
    }

    .nav-button.active {
      background: rgba(218, 165, 32, 0.3);
      border-color: rgba(255, 215, 0, 0.8);
      box-shadow: 0 0 30px rgba(218, 165, 32, 0.5);
      color: #FFD700;
    }

    .content-area {
      width: 100%;
      height: 100%;
      padding-top: 70px;
    }

    .content-frame {
      width: 100%;
      height: 100%;
      border: none;
      background: #000000;
    }

    .toggle-button {
      position: fixed;
      top: 80px;
      right: 20px;
      width: 50px;
      height: 50px;
      background: rgba(0, 0, 0, 0.9);
      backdrop-filter: blur(10px);
      border: 2px solid rgba(218, 165, 32, 0.4);
      border-radius: 10px;
      cursor: pointer;
      display: none;
      align-items: center;
      justify-content: center;
      z-index: 200;
      transition: all 0.3s ease;
    }

    .toggle-button:hover {
      background: rgba(218, 165, 32, 0.2);
      border-color: rgba(255, 215, 0, 0.6);
      box-shadow: 0 4px 12px rgba(218, 165, 32, 0.3);
    }

    .toggle-button.visible {
      display: flex;
    }

    .hamburger {
      width: 24px;
      height: 18px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .hamburger span {
      width: 100%;
      height: 3px;
      background: #DAA520;
      border-radius: 2px;
    }

    @media (max-width: 768px) {
      .login-card {
        padding: 40px 30px;
      }

      .logo {
        width: 160px;
      }

      .login-title {
        font-size: 26px;
      }

      .dashboard-header {
        flex-direction: column;
        gap: 10px;
        padding: 15px;
      }

      .button-panel {
        right: 10px;
        top: 140px;
      }

      .toggle-button {
        top: 120px;
      }
    }
  </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
  <script src="https://cdn.tailwindcss.com" type="text/javascript"></script>
 </head>
 <body>
  <div class="animated-background"></div>
  <div class="particles" id="particles"></div>
  <main>
   <div class="main-container" id="loginContainer">
    <div class="login-card">
     <div class="logo-container"><img src="https://i.top4top.io/p_35860o72q1.png" alt="Portarage Logo" class="logo" onerror="this.style.display='none'; this.alt='Logo failed to load';">
     </div>
     <h1 class="login-title" id="loginTitle">مرحباً بك</h1>
     <p class="login-subtitle" id="loginSubtitle">سجل دخولك للمتابعة</p>
     <div class="error-message" id="errorMessage">
      اسم المستخدم أو كلمة المرور غير صحيحة
     </div>
     <form id="loginForm">
      <div class="form-group"><label for="username" class="form-label" id="usernameLabel">اسم المستخدم</label>
       <div class="input-wrapper"><input type="text" id="username" class="form-input" required autocomplete="username" placeholder="أدخل اسم المستخدم">
       </div>
      </div>
      <div class="form-group"><label for="password" class="form-label" id="passwordLabel">كلمة المرور</label>
       <div class="input-wrapper"><input type="password" id="password" class="form-input" required autocomplete="current-password" placeholder="أدخل كلمة المرور">
       </div>
      </div><button type="submit" class="login-button" id="loginButton">دخول</button>
     </form>
    </div>
   </div>
   <div class="dashboard" id="dashboard">
    <header class="dashboard-header"><img src="https://i.top4top.io/p_35860o72q1.png" alt="Portarage Logo" class="dashboard-logo" onerror="this.style.display='none'; this.alt='Logo failed to load';"> <button class="logout-button" id="logoutButton">تسجيل الخروج</button>
    </header>
    <div class="button-panel" id="buttonPanel"><button class="nav-button" id="tiresBtn" data-url="https://portaragetiers.netlify.app">التواير</button> <button class="nav-button" id="batteryBtn" data-url="https://portaragebattery.netlify.app/">البطاريات</button> <button class="nav-button" id="oilsBtn" data-url="https://portarageoils.netlify.app/">الزيت والفلتر</button>
    </div><button class="toggle-button" id="toggleButton">
     <div class="hamburger"><span></span> <span></span> <span></span>
     </div></button>
    <div class="content-area"><iframe class="content-frame" id="contentFrame"></iframe>
    </div>
   </div>
  </main>
  <script>
    const defaultConfig = {
      login_title: "مرحباً بك",
      login_subtitle: "سجل دخولك للمتابعة",
      username_label: "اسم المستخدم",
      password_label: "كلمة المرور",
      login_button: "دخول",
      button_tires: "التواير",
      button_battery: "البطاريات",
      button_oils: "الزيت والفلتر",
      logout_button: "تسجيل الخروج",
      background_color: "#000000",
      surface_color: "#1a0f00",
      text_color: "#ffffff",
      primary_action_color: "#DAA520",
      accent_color: "#DAA520",
      font_family: "Segoe UI",
      font_size: 16
    };

    let config = { ...defaultConfig };

    // Create floating particles
    const particlesContainer = document.getElementById('particles');
    for (let i = 0; i < 30; i++) {
      const particle = document.createElement('div');
      particle.className = 'particle';
      particle.style.left = Math.random() * 100 + '%';
      particle.style.animationDelay = Math.random() * 15 + 's';
      particle.style.animationDuration = (Math.random() * 10 + 10) + 's';
      particlesContainer.appendChild(particle);
    }

    const users = {
      'Abdullah': 'portarage1',
      'Suaad': 'portarage2',
      'Laila': 'portarage3',
      'Nasser': 'portarage4',
      'Khalifa': 'portarage11',
      'Azam': 'portarage6',
      'Abdulwahab': 'portarage7',
      'Bashar': 'portarage8',
      'Ali': 'portarage9',
      'Sabah': 'portarage10',
      'Hamad': 'portarage12',
      'Fawzi': 'portarage12',
      'Mohamad': 'portarage7896',
      'Salem': 'portarage7887'
    };

    const loginForm = document.getElementById('loginForm');
    const loginContainer = document.getElementById('loginContainer');
    const dashboard = document.getElementById('dashboard');
    const errorMessage = document.getElementById('errorMessage');
    const logoutButton = document.getElementById('logoutButton');
    const buttonPanel = document.getElementById('buttonPanel');
    const toggleButton = document.getElementById('toggleButton');
    const contentFrame = document.getElementById('contentFrame');
    const tiresBtn = document.getElementById('tiresBtn');
    const batteryBtn = document.getElementById('batteryBtn');
    const oilsBtn = document.getElementById('oilsBtn');

    let currentActiveButton = null;

    loginForm.addEventListener('submit', function(e) {
      e.preventDefault();
      const username = document.getElementById('username').value;
      const password = document.getElementById('password').value;

      if (users[username] && users[username] === password) {
        errorMessage.classList.remove('show');
        loginContainer.style.display = 'none';
        dashboard.classList.add('active');
      } else {
        errorMessage.classList.add('show');
      }
    });

    logoutButton.addEventListener('click', function() {
      dashboard.classList.remove('active');
      loginContainer.style.display = 'flex';
      document.getElementById('username').value = '';
      document.getElementById('password').value = '';
      errorMessage.classList.remove('show');
      contentFrame.src = '';
      if (currentActiveButton) {
        currentActiveButton.classList.remove('active');
        currentActiveButton = null;
      }
      buttonPanel.classList.remove('hidden');
      toggleButton.classList.remove('visible');
    });

    function loadContent(url, button) {
      contentFrame.src = url;

      if (currentActiveButton) {
        currentActiveButton.classList.remove('active');
      }
      button.classList.add('active');
      currentActiveButton = button;

      buttonPanel.classList.add('hidden');
      toggleButton.classList.add('visible');
    }

    tiresBtn.addEventListener('click', function() {
      loadContent(this.dataset.url, this);
    });

    batteryBtn.addEventListener('click', function() {
      loadContent(this.dataset.url, this);
    });

    oilsBtn.addEventListener('click', function() {
      loadContent(this.dataset.url, this);
    });

    toggleButton.addEventListener('click', function() {
      buttonPanel.classList.toggle('hidden');
    });

    async function onConfigChange(newConfig) {
      const customFont = newConfig.font_family || defaultConfig.font_family;
      const baseFontSize = newConfig.font_size || defaultConfig.font_size;
      const backgroundColor = newConfig.background_color || defaultConfig.background_color;
      const surfaceColor = newConfig.surface_color || defaultConfig.surface_color;
      const textColor = newConfig.text_color || defaultConfig.text_color;
      const primaryActionColor = newConfig.primary_action_color || defaultConfig.primary_action_color;
      const accentColor = newConfig.accent_color || defaultConfig.accent_color;

      document.body.style.fontFamily = `${customFont}, Arial, sans-serif`;
      document.body.style.fontSize = `${baseFontSize}px`;
      document.body.style.background = backgroundColor;
      document.body.style.color = textColor;

      document.getElementById('loginTitle').textContent = newConfig.login_title || defaultConfig.login_title;
      document.getElementById('loginSubtitle').textContent = newConfig.login_subtitle || defaultConfig.login_subtitle;
      document.getElementById('usernameLabel').textContent = newConfig.username_label || defaultConfig.username_label;
      document.getElementById('passwordLabel').textContent = newConfig.password_label || defaultConfig.password_label;
      document.getElementById('loginButton').textContent = newConfig.login_button || defaultConfig.login_button;
      document.getElementById('logoutButton').textContent = newConfig.logout_button || defaultConfig.logout_button;
      document.getElementById('tiresBtn').textContent = newConfig.button_tires || defaultConfig.button_tires;
      document.getElementById('batteryBtn').textContent = newConfig.button_battery || defaultConfig.button_battery;
      document.getElementById('oilsBtn').textContent = newConfig.button_oils || defaultConfig.button_oils;

      document.querySelector('.login-title').style.fontSize = `${baseFontSize * 2}px`;
      document.querySelector('.login-subtitle').style.fontSize = `${baseFontSize}px`;
      document.querySelector('.login-subtitle').style.color = textColor;

      const formLabels = document.querySelectorAll('.form-label');
      formLabels.forEach(label => {
        label.style.fontSize = `${baseFontSize * 0.9375}px`;
        label.style.color = accentColor;
      });

      const formInputs = document.querySelectorAll('.form-input');
      formInputs.forEach(input => {
        input.style.fontSize = `${baseFontSize}px`;
        input.style.color = textColor;
        input.style.borderColor = `rgba(${hexToRgb(accentColor)}, 0.3)`;
      });

      const loginBtn = document.querySelector('.login-button');
      loginBtn.style.fontSize = `${baseFontSize * 1.125}px`;

      const navButtons = document.querySelectorAll('.nav-button');
      navButtons.forEach(button => {
        button.style.fontSize = `${baseFontSize * 1.125}px`;
        button.style.borderColor = `rgba(${hexToRgb(accentColor)}, 0.4)`;
        button.style.color = accentColor;
      });

      const logoutBtn = document.querySelector('.logout-button');
      logoutBtn.style.fontSize = `${baseFontSize * 0.9375}px`;

      const toggleBtn = document.querySelector('.toggle-button');
      toggleBtn.style.borderColor = `rgba(${hexToRgb(accentColor)}, 0.4)`;

      const hamburgerSpans = document.querySelectorAll('.hamburger span');
      hamburgerSpans.forEach(span => {
        span.style.background = accentColor;
      });
    }

    function hexToRgb(hex) {
      const result = /^#?([a-f\d]{2})([a-f\d]{2})([a-f\d]{2})$/i.exec(hex);
      return result ? `${parseInt(result[1], 16)}, ${parseInt(result[2], 16)}, ${parseInt(result[3], 16)}` : '0, 0, 0';
    }

    function hexToRgba(hex, alpha) {
      return `rgba(${hexToRgb(hex)}, ${alpha})`;
    }

    function mapToCapabilities(config) {
      return {
        recolorables: [
          {
            get: () => config.background_color || defaultConfig.background_color,
            set: (value) => {
              config.background_color = value;
              window.elementSdk.setConfig({ background_color: value });
            }
          },
          {
            get: () => config.surface_color || defaultConfig.surface_color,
            set: (value) => {
              config.surface_color = value;
              window.elementSdk.setConfig({ surface_color: value });
            }
          },
          {
            get: () => config.text_color || defaultConfig.text_color,
            set: (value) => {
              config.text_color = value;
              window.elementSdk.setConfig({ text_color: value });
            }
          },
          {
            get: () => config.primary_action_color || defaultConfig.primary_action_color,
            set: (value) => {
              config.primary_action_color = value;
              window.elementSdk.setConfig({ primary_action_color: value });
            }
          },
          {
            get: () => config.accent_color || defaultConfig.accent_color,
            set: (value) => {
              config.accent_color = value;
              window.elementSdk.setConfig({ accent_color: value });
            }
          }
        ],
        borderables: [],
        fontEditable: {
          get: () => config.font_family || defaultConfig.font_family,
          set: (value) => {
            config.font_family = value;
            window.elementSdk.setConfig({ font_family: value });
          }
        },
        fontSizeable: {
          get: () => config.font_size || defaultConfig.font_size,
          set: (value) => {
            config.font_size = value;
            window.elementSdk.setConfig({ font_size: value });
          }
        }
      };
    }

    function mapToEditPanelValues(config) {
      return new Map([
        ["login_title", config.login_title || defaultConfig.login_title],
        ["login_subtitle", config.login_subtitle || defaultConfig.login_subtitle],
        ["username_label", config.username_label || defaultConfig.username_label],
        ["password_label", config.password_label || defaultConfig.password_label],
        ["login_button", config.login_button || defaultConfig.login_button],
        ["button_tires", config.button_tires || defaultConfig.button_tires],
        ["button_battery", config.button_battery || defaultConfig.button_battery],
        ["button_oils", config.button_oils || defaultConfig.button_oils],
        ["logout_button", config.logout_button || defaultConfig.logout_button]
      ]);
    }

    if (window.elementSdk) {
      window.elementSdk.init({
        defaultConfig,
        onConfigChange,
        mapToCapabilities,
        mapToEditPanelValues
      });

      config = window.elementSdk.config;
      onConfigChange(config);
    }
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9aa6b76c10bf7cc9',t:'MTc2NTEzODc1MS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
