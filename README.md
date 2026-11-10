# -
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>高校生のためのアルバイト面接 必勝攻略本</title>
<style>
  :root {
    --primary: #4F46E5;
    --primary-light: #EEF2FF;
    --secondary: #10B981;
    --accent: #F59E0B;
    --dark: #1F2937;
    --gray-bg: #F9FAFB;
    --card-bg: #FFFFFF;
    --text: #374151;
  }

  body {
    font-family: 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', 'Hiragino Sans', Meiryo, sans-serif;
    background-color: var(--gray-bg);
    color: var(--text);
    line-height: 1.6;
    margin: 0;
    padding: 20px 12px;
  }

  .container {
    max-width: 680px;
    margin: 0 auto;
  }

  /* ヘッダー */
  .hero-header {
    background: linear-gradient(135deg, #6366F1 0%, #4F46E5 100%);
    color: white;
    padding: 32px 20px;
    border-radius: 20px;
    text-align: center;
    box-shadow: 0 10px 25px -5px rgba(79, 70, 229, 0.4);
    margin-bottom: 28px;
    position: relative;
    overflow: hidden;
  }

  .hero-header::before {
    content: "LV.99";
    position: absolute;
    top: -10px;
    right: -10px;
    background: rgba(255, 255, 255, 0.15);
    font-weight: 900;
    font-size: 3.5rem;
    color: white;
    transform: rotate(12deg);
    pointer-events: none;
  }

  .badge-top {
    display: inline-block;
    background: #FBBF24;
    color: #78350F;
    font-weight: bold;
    font-size: 0.85rem;
    padding: 4px 14px;
    border-radius: 50px;
    margin-bottom: 12px;
    letter-spacing: 0.05em;
  }

  .hero-header h1 {
    font-size: 1.65rem;
    margin: 0 0 10px 0;
    font-weight: 800;
    line-height: 1.3;
  }

  .hero-header p {
    font-size: 0.95rem;
    margin: 0;
    opacity: 0.95;
  }

  /* ステップカード */
  .step-card {
    background: var(--card-bg);
    border-radius: 16px;
    padding: 24px;
    margin-bottom: 24px;
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -1px rgba(0, 0, 0, 0.03);
    border: 1px solid #E5E7EB;
    position: relative;
  }

  .step-tag {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-weight: 800;
    font-size: 0.85rem;
    color: white;
    padding: 4px 12px;
    border-radius: 8px;
    margin-bottom: 12px;
  }

  .tag-step1 { background: #6366F1; }
  .tag-step2 { background: #0EA5E9; }
  .tag-step3 { background: #10B981; }
  .tag-step4 { background: #8B5CF6; }

  .step-title {
    font-size: 1.25rem;
    font-weight: 700;
    color: var(--dark);
    margin: 0 0 16px 0;
    display: flex;
    align-items: center;
    gap: 8px;
  }

  /* ポイントボックス */
  .grid-2 {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }

  @media (max-width: 480px) {
    .grid-2 { grid-template-columns: 1fr; }
  }

  .box-item {
    background: var(--gray-bg);
    border-radius: 12px;
    padding: 14px;
    border-left: 4px solid var(--primary);
  }

  .box-item h4 {
    margin: 0 0 6px 0;
    font-size: 0.95rem;
    color: var(--dark);
  }

  .box-item p {
    margin: 0;
    font-size: 0.85rem;
    color: #4B5563;
  }

  /* コールアウト・ハイライト */
  .callout-box {
    background: #FFFBEB;
    border: 1.5px dashed #F59E0B;
    border-radius: 12px;
    padding: 14px 16px;
    margin-top: 14px;
  }

  .callout-title {
    color: #B45309;
    font-weight: 700;
    font-size: 0.9rem;
    margin-bottom: 4px;
    display: flex;
    align-items: center;
    gap: 6px;
  }

  .callout-text {
    font-size: 0.88rem;
    color: #92400E;
    margin: 0;
  }

  /* チェックリスト風 */
  .check-list {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .check-list li {
    position: relative;
    padding-left: 28px;
    margin-bottom: 10px;
    font-size: 0.92rem;
  }

  .check-list li::before {
    content: "✓";
    position: absolute;
    left: 0;
    top: 0;
    width: 20px;
    height: 20px;
    background: #DEF7EC;
    color: #03543F;
    font-weight: bold;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 0.75rem;
  }

  /* まとめバナー */
  .summary-box {
    background: #111827;
    color: white;
    border-radius: 16px;
    padding: 24px;
    text-align: center;
    margin-top: 32px;
  }

  .summary-box h3 {
    color: #FBBF24;
    margin: 0 0 16px 0;
    font-size: 1.2rem;
  }

  .summary-cards {
    display: flex;
    justify-content: space-around;
    gap: 10px;
    margin-bottom: 16px;
  }

  .mini-card {
    background: #1F2937;
    padding: 12px 8px;
    border-radius: 10px;
    flex: 1;
    font-size: 0.85rem;
    border: 1px solid #374151;
  }

  .mini-card span {
    display: block;
    font-size: 1.4rem;
    margin-bottom: 4px;
  }
</style>
</head>
<body>

<div class="container">

  <!-- ヘッダー -->
  <header class="hero-header">
    <span class="badge-top">不採用ゼロを目指す！</span>
    <h1>高校生のための<br>アルバイト面接 必勝攻略本</h1>
    <p>面接官の「合格基準」をクリアして採用を勝ち取ろう！</p>
  </header>

  <!-- STEP 1 -->
  <section class="step-card">
    <div class="step-tag tag-step1">STAGE 1</div>
    <h2 class="step-title">🛡️ 装備＆見た目（身だしなみ・マナー）</h2>
    <p style="font-size:0.9rem; margin-top:0;">面接官が見ているのはスキルではなく<b>「清潔感」</b>と<b>「マナー」</b>！ここを整えれば第一印象の評価が爆上がりします。</p>
    
    <div class="grid-2">
      <div class="box-item">
        <h4>🏫 最強の装備：制服</h4>
        <p>迷ったら学校の制服が一番確実！ボタンは留め、ネクタイやリボンも正しく着けよう。</p>
      </div>
      <div class="box-item">
        <h4>✨ 清潔感チェック</h4>
        <p>寝癖はない？前髪が目にかかってない？爪が伸びすぎていないか要確認！</p>
      </div>
    </div>

    <div class="callout-box">
      <div class="callout-title">⚡ 発声＆笑顔バフを発動させよう</div>
      <p class="callout-text">入室時の<b>「失礼します！」</b>と、質問への<b>「はい！」</b>というハキハキした返事＋笑顔だけで「一緒に働きたい！」と思ってもらえます。</p>
    </div>
  </section>

  <!-- STEP 2 -->
  <section class="step-card">
    <div class="step-tag tag-step2">STAGE 2</div>
    <h2 class="step-title">📅 シフト調整（条件のアピール）</h2>
    <p style="font-size:0.9rem; margin-top:0;">不採用理由No.1は<b>「お店の入ってほしい時間と合わないこと」</b>。自由度を少し見せるのがコツ！</p>
    
    <ul class="check-list">
      <li><b>「土日のどちらか入れます」「テスト期間以外は週2〜3日OK」</b>など柔軟性を出す</li>
      <li>「平日18〜20時の週1だけ」だとシフトが組みづらく不採用になりやすい</li>
      <li>WEB応募後の電話・メール返信は<b>スピード重視</b>！返信が早いだけで信頼度UP</li>
    </ul>
  </section>

  <!-- STEP 3 -->
  <section class="step-card">
    <div class="step-tag tag-step3">STAGE 3</div>
    <h2 class="step-title">🗣️ 面接での発言（志望動機＆両立）</h2>
    <p style="font-size:0.9rem; margin-top:0;">難しい言葉は不要！<b>「やる気」</b>と<b>「真面目さ」</b>が伝わればOKです。</p>

    <div class="box-item" style="margin-bottom: 12px; border-left-color: #10B981;">
      <h4>💡 志望動機に「プラス一言」</h4>
      <p>「家が近い」「お金が欲しい」＋<b>「いつも利用していて雰囲気が好きだから」「接客の練習がしたいから」</b>を添える。</p>
    </div>

    <div class="box-item" style="border-left-color: #10B981;">
      <h4>📚 テストや部活との両立</h4>
      <p><b>「テスト前はお休みしたいですが、その分ふだんはしっかり働きます！」</b>と事前に伝えておくと安心感を与えられます。</p>
    </div>
  </section>

  <!-- STEP 4 -->
  <section class="step-card">
    <div class="step-tag tag-step4">BONUS STAGE</div>
    <h2 class="step-title">🏆 受かりやすいイージーモード求人</h2>
    <p style="font-size:0.9rem; margin-top:0;">なかなか受からない時は、狙うお店のタイプを変えてみるのも戦略です！</p>
    
    <div class="grid-2">
      <div class="box-item" style="border-left-color: #8B5CF6;">
        <h4>✨ オープニングスタッフ</h4>
        <p>同期が一斉スタート＆大量採用のため合格率が高い！</p>
      </div>
      <div class="box-item" style="border-left-color: #8B5CF6;">
        <h4>🍔 大手チェーン店</h4>
        <p>ファーストフードやコンビニは高校生の採用実績が豊富。</p>
      </div>
    </div>
    
    <div class="callout-box" style="background: #F3E8FF; border-color: #A855F7;">
      <div class="callout-title" style="color: #6B21A8;">🤝 一番強いのは「友達の紹介（リファラル）」</div>
      <p class="callout-text" style="color: #581C87;">既に働いている友達に紹介してもらうと、信頼感があるため採用率は一気に跳ね上がります！</p>
    </div>
  </section>

  <!-- まとめ -->
  <footer class="summary-box">
    <h3>🔥 次の面接で意識する「3つの必殺ワザ」</h3>
    <div class="summary-cards">
      <div class="mini-card">
        <span>👔</span>
        制服をビシッと<br>正しく着る！
      </div>
      <div class="mini-card">
        <span>🗣️</span>
        ハキハキと<br>「はい！」と返事！
      </div>
      <div class="mini-card">
        <span>😊</span>
        目を見て<br>ニコッと笑顔！
      </div>
    </div>
    <p style="font-size: 0.85rem; color: #9CA3AF; margin: 0;">これさえできれば合格は目の前！自信を持って行ってらっしゃい！応援してるよ！</p>
  </footer>

</div>

</body>
</html>
　