<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ウイスキーの世界</title>
  <style>
    /* ページ全体の背景を海の画像に設定 */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-image: url('sea.jpg'); /* 海の画像URL */
      background-size: cover; /* 画像を画面全体にフィットさせる */
      background-position: center; /* 画像を中央に配置 */
      background-attachment: fixed; /* スクロールしても背景が固定される */
      color: #fff; /* 文字色を白に */
    }

    /* ヘッダーのデザイン */
    header {
      background-color: rgba(0, 0, 0, 0.7); /* 半透明の黒背景 */
      color: #fff;
      padding: 2rem;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.5);
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    /* ウイスキーのカードが並ぶコンテナ */
    .whiskey-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin: 2rem;
      gap: 2rem;
    }

    /* 各ウイスキーのカードデザイン */
    .whiskey-card {
      max-width: 300px;
      padding: 1rem;
      border: 1px solid #ccc;
      border-radius: 15px;
      background-color: #fff;
      color: #333;
      text-align: center;
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2); /* 影を追加して立体感 */
      transition: transform 0.3s ease-in-out;
      cursor: pointer; /* クリック可能に見せる */
    }

    .whiskey-card:hover {
      transform: translateY(-10px); /* ホバー時に少し浮かせる */
    }

    .whiskey-card img {
      width: 100%; /* 画像の幅をカードに合わせて100% */
      height: 300px; /* 画像の高さを300pxに統一 */
      object-fit: cover; /* 画像のアスペクト比を保ちつつ、カード内に収まるように調整 */
      border-radius: 8px;
      margin-bottom: 1rem;
    }

    .whiskey-card h3 {
      font-size: 1.6rem;
      color: #333;
      margin: 0.5rem 0;
    }

    .whiskey-card p {
      font-size: 1rem;
      color: #666;
    }

    /* フッターのデザイン */
    footer {
      background-color: rgba(0, 0, 0, 0.7);
      color: #fff;
      text-align: center;
      padding: 1rem;
      position: relative;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <!-- ヘッダー -->
  <header>
    <h1>ウイスキーの世界</h1>
  </header>

  <!-- ウイスキーのコンテンツ -->
  <div class="whiskey-container">
    
    <a href="whiskey_detailsmacallan12.html" class="whiskey-card">
      <img src="https://tse2.mm.bing.net/th?id=OIP.K_WjWXb9VgbXMT1l5dQ_MQHaHa&pid=Api" alt="マッカラン 12年">
      <h3>マッカラン 12年</h3>
      <p>濃厚なシェリー風味とフルーティーな香りが魅力。</p>
    </a>

    <a href="whiskey_detailsyamazaki18.html" class="whiskey-card">
      <img src="https://tse2.mm.bing.net/th?id=OIP.rtjF-rNgk2lYmPQwAq4TWwAAAA&pid=Api" alt="山崎 18年">
      <h3>山崎 18年</h3>
      <p>深い熟成感と複雑な味わいが特徴の日本を代表するシングルモルト。</p>
    </a>

    <a href="whiskey_detailsmakersmark.html" class="whiskey-card">
      <img src="https://tse2.mm.bing.net/th?id=OIP.bvaHCxdQBGRvdh89LJ_oVgHaE3&pid=Api" alt="メーカーズマーク">
      <h3>メーカーズマーク</h3>
      <p>甘くスムースな味わいで知られるアメリカンバーボンの代表格。</p>
    </a>

    <!-- 新しく追加したグレンフィディック12年の紹介 -->
    <a href="whiskey_detailsglenfiddich12.html" class="whiskey-card">
      <img src="https://m.media-amazon.com/images/I/81+tILtEIKL._AC_SL1500_.jpg" alt="グレンフィディック12年">
      <h3>グレンフィディック 12年</h3>
      <p>ウイスキー初心者におすすめのシングルモルト。フルーティーで軽やかな味わい。</p>
    </a>

  </div>

  <!-- フッター -->
  <footer>
    <p>&copy; 2025 ウイスキーの世界 | All Rights Reserved</p>
  </footer>

</body>
</html>

