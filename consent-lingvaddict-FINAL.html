<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>Consent Form | LingvAddict</title>

  <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=DM+Sans:wght@400;500;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --purple: #6B21A8; --purple-mid: #7C3AED; --purple-light: #EDE9FE;
      --gold: #C9A84C; --cream: #FAF7F2; --text: #1C0A3A; --muted: #7C6F8E;
      --card: #FFFFFF;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'DM Sans', sans-serif; background: var(--cream); min-height: 100vh; display: flex; justify-content: center; align-items: center; padding: 15px; }
    
    .card { background: var(--card); border-radius: 24px; max-width: 450px; width: 100%; box-shadow: 0 20px 50px rgba(107,33,168,.1); overflow: hidden; position: relative; }

    /* Переключатель языков */
    .lang-switcher {
      display: flex; justify-content: flex-end; gap: 8px; padding: 12px 20px; background: rgba(0,0,0,0.03);
    }
    .lang-btn {
      font-size: 11px; font-weight: 700; cursor: pointer; color: var(--muted); border: none; background: none; padding: 4px 8px; border-radius: 6px; transition: 0.2s;
    }
    .lang-btn.active { background: var(--purple); color: #fff; }

    .card-header { background: linear-gradient(135deg, var(--purple) 0%, var(--purple-mid) 100%); padding: 25px 20px; color: #fff; }
    .logo { display: flex; align-items: center; gap: 8px; margin-bottom: 12px; }
    .logo-mark { background: rgba(255,255,255,.2); padding: 5px; border-radius: 8px; font-size: 16px; }
    .logo-name { font-family: 'Playfair Display', serif; font-size: 18px; }
    .hero-badge { display: inline-block; background: rgba(201,168,76,.2); border-radius: 50px; padding: 3px 10px; font-size: 10px; text-transform: uppercase; margin-bottom: 8px; }
    h1 { font-family: 'Playfair Display', serif; font-size: 20px; line-height: 1.3; margin-bottom: 8px; }
    p.subtitle { font-size: 13px; opacity: 0.9; }

    .card-body { padding: 20px; }
    .platforms { background: var(--purple-light); border-radius: 16px; padding: 15px; margin-bottom: 20px; }
    .platforms-label { font-size: 10px; font-weight: 700; text-transform: uppercase; color: var(--purple); margin-bottom: 10px; }
    .platform-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 8px; }
    .platform-item { display: flex; align-items: center; gap: 6px; font-size: 12px; color: var(--text); font-weight: 500; }
    
    .fields { display: flex; flex-direction: column; gap: 12px; margin-bottom: 20px; }
    .field-label { font-size: 12px; font-weight: 600; color: var(--text); margin-bottom: 4px; display: block; }
    .field-input { font-family: inherit; font-size: 15px; background: var(--cream); border: 1.5px solid rgba(107,33,168,.1); border-radius: 12px; padding: 10px 12px; width: 100%; outline: none; }

    .btn { width: 100%; padding: 14px; border-radius: 12px; font-size: 14px; font-weight: 700; cursor: pointer; border: none; margin-bottom: 8px; transition: 0.2s; }
    .btn-confirm { background: var(--purple-mid); color: #fff; }
    .btn-decline { background: transparent; color: var(--muted); border: 1px solid #ddd; }

    .state { display: none; padding: 40px 20px; text-align: center; }
    .state.active { display: block; }
    .state-icon { font-size: 48px; margin-bottom: 15px; display: block; }
  </style>
</head>
<body>

<div class="card">
  <div class="lang-switcher">
    <button class="lang-btn active" onclick="setLang('ru')">RU</button>
    <button class="lang-btn" onclick="setLang('en')">EN</button>
    <button class="lang-btn" onclick="setLang('am')">AM</button>
  </div>

  <div id="view-main">
    <div class="card-header">
      <div class="logo">
        <div class="logo-mark">📚</div>
        <div class="logo-name">LingvAddict</div>
      </div>
      <div class="hero-badge" id="txt-badge">✨ Запрос</div>
      <h1 id="txt-title">Разрешите поделиться успехом ребёнка?</h1>
      <p class="subtitle" id="txt-subtitle">Хотим опубликовать видео прогресса на наших площадках.</p>
    </div>

    <div class="card-body">
      <div class="platforms">
        <div class="platforms-label" id="txt-plat-label">Где публикуем</div>
        <div class="platform-grid">
          <div class="platform-item">🌐 <span id="txt-site">Сайт</span></div>
          <div class="platform-item">📸 Instagram</div>
          <div class="platform-item">▶️ YouTube</div>
          <div class="platform-item">✈️ Telegram</div>
          <div class="platform-item">🎬 VK Видео</div>
          <div class="platform-item">💬 VK Сообщество</div>
        </div>
      </div>

      <div class="fields">
        <div class="field-group">
          <label class="field-label" id="txt-label-parent">Ваше имя и фамилия *</label>
          <input class="field-input" id="parentName" type="text">
        </div>
        <div class="field-group">
          <label class="field-label" id="txt-label-child">Имя ребёнка</label>
          <input class="field-input" id="childName" type="text">
        </div>
      </div>

      <button class="btn btn-confirm" id="txt-btn-yes" onclick="sendEmail('confirm')">Да, разрешаю</button>
      <button class="btn btn-decline" id="txt-btn-no" onclick="sendEmail('decline')">Нет, не сегодня</button>
    </div>
  </div>

  <div id="view-confirmed" class="state">
    <span class="state-icon">✅</span>
    <h2 id="txt-res-yes-h">Спасибо!</h2>
    <p id="txt-res-yes-p">Мы получили ваше согласие.</p>
  </div>

  <div id="view-declined" class="state">
    <span class="state-icon">🙏</span>
    <h2 id="txt-res-no-h">Понимаем вас</h2>
    <p id="txt-res-no-p">Ваш отказ принят.</p>
  </div>
</div>

<script>
  const translations = {
    ru: {
      badge: "✨ Запрос", title: "Разрешите поделиться успехом ребёнка?", subtitle: "Хотим опубликовать видео прогресса на наших площадках.",
      platLabel: "Где публикуем", site: "Сайт", labelParent: "Ваше имя и фамилия *", labelChild: "Имя ребёнка",
      btnYes: "Да, разрешаю", btnNo: "Нет, не сегодня", resYesH: "Спасибо!", resYesP: "Мы получили ваше согласие.",
      resNoH: "Понимаем вас", resNoP: "Ваш отказ принят.", alert: "Введите имя"
    },
    en: {
      badge: "✨ Request", title: "Can we share your child's success?", subtitle: "We'd like to post the progress video on our platforms.",
      platLabel: "Where we post", site: "Website", labelParent: "Your Full Name *", labelChild: "Child's Name",
      btnYes: "Yes, I agree", btnNo: "No, not today", resYesH: "Thank you!", resYesP: "We have received your consent.",
      resNoH: "We understand", resNoP: "Your refusal is accepted.", alert: "Please enter your name"
    },
    am: {
      badge: "✨ Հարցում", title: "Կարո՞ղ ենք կիսվել Ձեր երեխայի հաջողությամբ:", subtitle: "Ցանկանում ենք տեղադրել առաջընթացի տեսանյութը մեր հարթակներում:",
      platLabel: "Որտեղ ենք հրապարակում", site: "Կայք", labelParent: "Ձեր անունը և ազգանունը *", labelChild: "Երեխայի անունը",
      btnYes: "Այո, թույլատրում եմ", btnNo: "Ոչ, այսօր ոչ", resYesH: "Շնորհակալություն", resYesP: "Մենք ստացել ենք Ձեր համաձայնությունը:",
      resNoH: "Մենք հասկանում ենք", resNoP: "Ձեր մերժումն ընդունված է:", alert: "Խնդրում ենք լրացնել անունը"
    }
  };

  let currentLang = 'ru';

  function setLang(lang) {
    currentLang = lang;
    const t = translations[lang];
    document.getElementById('txt-badge').innerText = t.badge;
    document.getElementById('txt-title').innerText = t.title;
    document.getElementById('txt-subtitle').innerText = t.subtitle;
    document.getElementById('txt-plat-label').innerText = t.platLabel;
    document.getElementById('txt-site').innerText = t.site;
    document.getElementById('txt-label-parent').innerText = t.labelParent;
    document.getElementById('txt-label-child').innerText = t.labelChild;
    document.getElementById('txt-btn-yes').innerText = t.btnYes;
    document.getElementById('txt-btn-no').innerText = t.btnNo;
    document.getElementById('txt-res-yes-h').innerText = t.resYesH;
    document.getElementById('txt-res-yes-p').innerText = t.resYesP;
    document.getElementById('txt-res-no-h').innerText = t.resNoH;
    document.getElementById('txt-res-no-p').innerText = t.resNoP;

    document.querySelectorAll('.lang-btn').forEach(btn => {
      btn.classList.toggle('active', btn.innerText.toLowerCase() === lang);
    });
  }

  emailjs.init('9FE6h2CX3GfOY_NU8');

  function sendEmail(action) {
    const parentName = document.getElementById('parentName').value.trim();
    if (!parentName) { alert(translations[currentLang].alert); return; }
    
    const isConfirm = action === 'confirm';
    emailjs.send('service_36c0dpk', 'template_bjphp9o', {
      parent_name: parentName,
      child_name: document.getElementById('childName').value.trim() || '—',
      action: isConfirm ? 'СОГЛАСИЕ ✅' : 'ОТКАЗ ❌',
      timestamp: new Date().toLocaleString()
    }).then(() => {
      document.getElementById('view-main').style.display = 'none';
      document.getElementById(isConfirm ? 'view-confirmed' : 'view-declined').classList.add('active');
    });
  }
</script>
</body>
</html>
