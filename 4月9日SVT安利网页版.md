<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SEVENTEEN 安利站</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@300;400;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #6C5B7B;
            --secondary-color: #C06C84;
            --accent-color: #F67280;
            --text-color: #2A363B;
            --bg-color: #F8BBD0;
        }

        body {
            font-family: 'Noto Sans SC', sans-serif;
            color: var(--text-color);
            margin: 0;
            overflow-x: hidden;
            background: var(--bg-color);
        }

        .hero-section {
            position: relative;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
        }

        .hero-video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: 1;
            opacity: 0.8;
        }

        .hero-content {
            position: relative;
            z-index: 2;
            text-align: center;
            color: white;
        }

        .hero-title {
            font-size: 4rem;
            font-weight: 700;
            text-shadow: 2px 2px 8px rgba(0,0,0,0.3);
            animation: fadeInDown 1s ease;
        }

        .section {
            padding: 4rem 2rem;
            background: white;
            margin: 2rem;
            border-radius: 15px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .section:hover {
            transform: translateY(-5px);
        }

        .member-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .member-card {
            background: white;
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            text-align: center;
            transition: all 0.3s ease;
        }

        .member-card:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        @keyframes fadeInDown {
            0% {
                opacity: 0;
                transform: translateY(-20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <section class="hero-section">
        <video class="hero-video" autoplay muted loop>
            <source src="./videos/svt-hero.mp4" type="video/mp4">
        </video>
        <div class="hero-content">
            <h1 class="hero-title">SEVENTEEN 安利站</h1>
        </div>
    </section>

    <section class="section">
        <h2>团队成员</h2>
        <div class="member-grid">
            <div class="member-card">
                <h3>崔胜澈</h3>
                <p>队长</p>
                <h3>尹净汉</h3>
                <p>队员:又称队内"妈妈"</p>
                <h3>洪知秀</h3>
                <p>队员:水系魔法师</p>
                <h3>文俊辉</h3>
                <p>队员:中国制造！精神忙内</p>
                <h3>权顺荣</h3>
                <p>队员:婆队(performance)队长</p>
                <h3>全圆佑</h3>
                <p>队员:火鸡面代言人 宽肩男神</p>
                <h3>李知勋</h3>
                <p>队员:男歌手</p>
                <h3>徐明浩</h3>
                <p>队员:男歌手</p>
                <h3>金珉奎</h3>
                <p>队员:男歌手</p>
                <h3>李硕珉</h3>
                <p>队员:男歌手</p>
                <h3>夫胜宽</h3>
                <p>队员:男歌手</p>
                <h3>崔瀚率</h3>
                <p>队员:男歌手</p>
                <h3>李灿</h3>
                <p>队员:男歌手</p>
            </div>
           
        </div>
    </section>

    <section class="section">
        <h2>音乐作品</h2>
        <div class="video-grid">
            <iframe src="//player.bilibili.com/player.html?aid=945160821&bvid=BV1MW4y1x7vv" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
            <!-- 添加其他视频 -->
        </div>
    </section>

    <section class="section">
        <h2>相关话题</h2>
        <div class="topic-grid">
            <div class="topic-card">次人</div>
            <div class="topic-card">束草之约</div>
            <!-- 添加其他话题 -->
        </div>
    </section>
</body>
</html>
