![IMG_0147](https://github.com/user-attachments/assets/d043f658-4bb9-4d82-a8c4-b7a785cff23b)<!DOCTYPE html>
<html lang="ja">
  <head>
    <meta charset="UTF-8" />
    <title>画像表示テスト</title>
    <style>
      /* ———  基本レイアウト  ——— */
      html,
      body {
        margin: 0;
        padding: 0;
        font-family: system-ui, -apple-system, "Helvetica Neue", Arial, sans-serif;
        background: #f8f9fa;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
      }

      /* ———  画像を囲むラッパー ——— */
      .image-wrapper {
        max-width: 800px; /* 画像の横幅を 800px 以下に抑える */
        width: 90vw;      /* 画面の 90% 幅まで可変 */
      }

      /* ———  画像スタイル ——— */
      img {
        width: 100%;      /* ラッパーの幅にフィットさせる */
        height: auto;     /* アスペクト比維持 */
        border-radius: 12px;
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
      }
    </style>
  </head>
  <body>
    <div class="image-wrapper">
      <!-- 画像ファイルは同じディレクトリの images フォルダに置く -->
      <!-- src="images/sample.jpg" の部分を実際のファイル名に変更してください -->
      <img![IMG_0147](https://github.com/user-attachments/assets/b6246e7a-232c-4ceb-9ad1-5b2f207db261)

        src="![Uploading IMG_0147.PNG…]()
"
        alt="サンプル画像"
        loading="lazy"
      />
    </div>
  </body>
</html>
