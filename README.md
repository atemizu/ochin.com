<!DOCTYPE html>
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
      <img
        src="![8A9D7B26-C229-496D-862C-3E746D4B44A0_1_105_c](https://github.com/user-attachments/assets/06dfa2c5-71c9-4e58-938a-15b6f05ff6c5)
"
        alt="サンプル画像"
        loading="lazy"
      />
    </div>
  </body>
</html>
