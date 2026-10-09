

<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>欢迎来到我的个人空间</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background-color: #f8f9fa;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }
        .container {
            max-width: 900px;
            width: 100%;
            background: #ffffff;
            padding: 40px;
            border-radius: 16px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
            text-align: center;
        }
        h1 {
            font-size: 2rem;
            margin-bottom: 12px;
            color: #111;
        }
        .intro {
            font-size: 1.05rem;
            color: #666;
            margin-bottom: 36px;
            line-height: 1.6;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
            gap: 24px;
            margin-bottom: 36px;
        }
        .card {
            background: #fff;
            border: 1px solid #eaeaea;
            border-radius: 12px;
            padding: 28px 20px;
            text-decoration: none;
            color: inherit;
            transition: all 0.25s ease;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            border-color: #0070f3;
        }
        .card-icon {
            font-size: 3rem;
            margin-bottom: 16px;
        }
        .card-title {
            font-size: 1.2rem;
            font-weight: 600;
            margin-bottom: 8px;
            color: #222;
        }
        .card-desc {
            font-size: 0.9rem;
            color: #0070f3;
            font-weight: 500;
        }
        .footer {
            border-top: 1px solid #eee;
            padding-top: 20px;
            font-size: 0.85rem;
            color: #888;
            font-style: italic;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>歡迎來到我的個人空間 👋</h1>
        <p class="intro">這裡是我記錄生活、分享文章與存放書籍的靜態小天地。請點擊下方區塊進入各個板塊：</p>

        <div class="grid">
            <!-- 板块 1：部落格 -->
            <a href="blog.html" class="card">
                <div class="card-icon">📝</div>
                <div class="card-title">我的部落格文章</div>
                <div class="card-desc">點此進入文章列表 &rarr;</div>
            </a>

            <!-- 板块 2：摄影照片墙 -->
            <a href="gallery.html" class="card">
                <div class="card-icon">📷</div>
                <div class="card-title">我的攝影照片牆</div>
                <div class="card-desc">點此觀看照片展示 &rarr;</div>
            </a>

            <!-- 板块 3：云端电子书库 -->
            <a href="books.html" class="card">
                <div class="card-icon">📚</div>
                <div class="card-title">雲端電子書庫</div>
                <div class="card-desc">點此瀏覽電子書 &rarr;</div>
            </a>
        </div>

        <div class="footer">
            本站所有內容皆有本地硬碟 Word 備份，可隨時離線閱讀。
        </div>
    </div>

</body>
</html>