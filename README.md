<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>医学部家庭教師掲示板</title>
  <link rel="icon" type="image/png" href="favicon.png">
  <style>
    body {
      font-family: "Helvetica Neue", sans-serif;
      margin: 0;
      background-color: #f5f9ff;
      color: #333;
      line-height: 1.8;
      font-size: 16px;
    }
    header {
      background-color: #0077cc;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    header img {
      height: 120px;
      margin-bottom: 10px;
    }
    nav {
      background-color: #005fa3;
      text-align: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a.contact-btn {
      background-color: #ff9800;
      color: white;
      padding: 8px 15px;
      border-radius: 5px;
      margin-left: 15px;
    }
    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }
    section:nth-child(even) {
      background-color: #ffffff;
    }
    section:nth-child(odd) {
      background-color: #eef6ff;
    }
    h2 {
      color: #005fa3;
      margin-bottom: 20px;
      text-align: center;
    }
    .feature-cards {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .card {
      background-color: #ffffff;
      border: 1px solid #ccc;
      border-radius: 8px;
      width: 280px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    .card img {
      width: 80px;
      height: 80px;
      margin-bottom: 15px;
    }
    .pricing-table {
      width: 100%;
      border-collapse: collapse;
    }
    .pricing-table th, .pricing-table td {
      border: 1px solid #ccc;
      padding: 12px;
      text-align: center;
    }
    .faq-item {
      background-color: #fff;
      border-left: 4px solid #0077cc;
      padding: 15px 20px;
      margin-bottom: 20px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }
    .faq-item h3 {
      color: #005fa3;
      margin-bottom: 8px;
    }
    ol {
      padding-left: 20px;
    }
    .footer {
      background-color: #eee;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <img src="header_logo.png" alt="医学部家庭教師ロゴ">
    <h1>医学部家庭教師掲示板</h1>
    <p>現役医学生によるオンライン個別指導</p>
  </header>

  <nav>
    <a href="#features">特徴</a>
    <a href="#pricing">料金</a>
    <a href="#trial">体験授業</a>
    <a href="#fee">紹介料</a>
    <a href="#faq">FAQ</a>
    <a href="https://docs.google.com/forms/d/1E_0jZ8WJGoaDiQ-1AeJqaRTRzUhMERLDmSPKXQ-YYuk/viewform" target="_blank" rel="noopener noreferrer" class="contact-btn">お問い合わせ</a>
  </nav>

  <section id="features">
    <h2>サービスの特徴</h2>
    <div class="feature-cards">
      <div class="card">
        <img src="https://img.icons8.com/fluency/96/medical-doctor.png" alt="現役医学生による指導">
        <h3>現役医学生による指導</h3>
        <p>医学部在学中の講師が最新の知識で指導します。</p>
      </div>
      <div class="card">
        <img src="https://img.icons8.com/fluency/96/video-call.png" alt="Zoomを使った指導">
        <h3>Zoomを用いたオンライン授業</h3>
        <p>通塾不要。自宅で安心して受講可能です。</p>
      </div>
      <div class="card">
        <img src="https://img.icons8.com/fluency/96/money.png" alt="低価格">
        <h3>無駄を省いた低価格</h3>
        <p>通塾コスト削減により価格を抑えました。</p>
      </div>
      <div class="card">
        <img src="https://img.icons8.com/fluency/96/task.png" alt="学習計画と報告書">
        <h3>学習計画と報告書</h3>
        <p>3ヶ月ごとの学習計画と月1回の報告書でサポート。</p>
      </div>
    </div>
  </section>

  <section id="pricing">
    <h2>授業料金</h2>
    <table class="pricing-table">
      <tr><th>月間授業時間</th><th>月額料金（税込）</th></tr>
      <tr><td>240分</td><td>25,000円</td></tr>
      <tr><td>360分</td><td>34,000円</td></tr>
      <tr><td>480分</td><td>42,000円</td></tr>
      <tr><td>720分</td><td>51,000円</td></tr>
    </table>
  </section>

  <section id="trial">
    <h2>体験授業</h2>
    <p>初回体験授業（60分）を <strong>3,000円</strong> でご提供中！</p>
    <h3>お申し込みの流れ</h3>
    <ol>
      <li><strong>お問い合わせ</strong>：フォームからご希望内容をご送信ください。</li>
      <li><strong>体験授業の実施</strong>：現役医学生の講師とZoomで1時間体験授業を行います。</li>
      <li><strong>入会判断</strong>：授業後、講師との相性や内容を確認いただき、正式に入会されるかをご判断いただけます。</li>
    </ol>
    <p><small>※授業料は毎月末に当月分をお支払いいただきます。</small></p>
  </section>

  <section id="fee">
    <h2>紹介手数料</h2>
    <p>紹介料：<strong>20,000円</strong></p>
    <p>女性講師をご希望の場合：追加<strong>6,000円</strong></p>
  </section>

  <section id="faq">
    <h2>よくある質問</h2>
    <div class="faq-item">
      <h3>Q. 講師はどのような人ですか？</h3>
      <p>A. すべて現役の医学部生で、厳選された指導経験のある講師のみをご紹介しています。</p>
    </div>
    <div class="faq-item">
      <h3>Q. 指導の対象学年は？</h3>
      <p>A. 中学生・高校生（医学部志望者）を中心に、浪人生や再受験生にも対応可能です。</p>
    </div>
    <div class="faq-item">
      <h3>Q. 授業はいつ行われますか？</h3>
      <p>A. 講師と相談のうえ、曜日・時間帯を柔軟に設定可能です。</p>
    </div>
    <div class="faq-item">
      <h3>Q. どのような生徒が対象ですか？</h3>
      <p>A. 中学生、高校生、浪人生、再受験生など、医学部を目指す幅広い層を対象としています。</p>
    </div>
    <div class="faq-item">
      <h3>Q. 受講に必要なものはありますか？</h3>
      <p>A. パソコンやタブレットなどの端末と、安定したWi-Fi環境があれば受講可能です。</p>
    </div>
  </section>

  <div class="footer">
    <p>&copy; 2025 医学部家庭教師掲示板. All rights reserved.</p>
  </div>
</body>
</html>
