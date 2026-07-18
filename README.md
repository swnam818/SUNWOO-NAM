<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>남선우 | Sunwoo Nam</title>
    <!-- 깔끔한 한글 폰트(Noto Sans KR) 불러오기 -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700&display=swap" rel="stylesheet">
    <!-- 아이콘(이메일, 링크드인 등) 불러오기 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        /* 디자인(CSS) 설정 */
        :root {
            --primary-color: #2c3e50; /* 진한 남색 (신뢰감을 주는 색상) */
            --accent-color: #3498db; /* 밝은 파란색 (포인트 색상) */
            --bg-color: #f4f6f9; /* 배경색 */
            --text-color: #333333;
            --card-bg: #ffffff;
        }
        
        body {
            font-family: 'Noto Sans KR', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.7;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            max-width: 800px;
            width: 90%;
            background: var(--card-bg);
            padding: 3rem;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.08); /* 부드러운 그림자 효과 */
            margin: 2rem 0;
        }

        header {
            margin-bottom: 2.5rem;
            border-bottom: 2px solid #f0f0f0;
            padding-bottom: 1.5rem;
        }

        h1 {
            color: var(--primary-color);
            font-size: 2.2rem;
            margin: 0 0 0.5rem 0;
            font-weight: 700;
        }

        .subtitle {
            color: #666;
            font-size: 1.1rem;
            margin: 0;
            font-weight: 400;
        }

        .section-title {
            color: var(--primary-color);
            font-size: 1.3rem;
            margin-bottom: 1rem;
            font-weight: 700;
        }

        .about-section {
            margin-bottom: 2.5rem;
        }

        .about-section p {
            font-size: 1.05rem;
            color: #444;
            margin-bottom: 1rem;
            word-break: keep-all; /* 한글 줄바꿈 최적화 */
        }

        .interests-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            margin-bottom: 2.5rem;
        }

        .tag {
            background-color: #e8f4f8;
            color: var(--accent-color);
            padding: 8px 18px;
            border-radius: 25px;
            font-size: 0.95rem;
            font-weight: 500;
            transition: all 0.3s ease;
        }

        /* 태그에 마우스를 올렸을 때의 효과 */
        .tag:hover {
            background-color: var(--accent-color);
            color: white;
            transform: translateY(-2px);
        }

        .links-section {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .link-item {
            display: flex;
            align-items: center;
            text-decoration: none;
            color: #555;
            font-size: 1.05rem;
            transition: color 0.3s ease;
            padding: 10px;
            border-radius: 10px;
            background-color: #f8f9fa;
        }

        .link-item i {
            width: 30px;
            font-size: 1.2rem;
            color: var(--primary-color);
            margin-right: 10px;
            text-align: center;
        }

        .link-item:hover {
            color: var(--accent-color);
            background-color: #f0f7fb;
        }

        .link-item:hover i {
            color: var(--accent-color);
        }

        /* 모바일 화면(작은 화면)을 위한 설정 */
        @media (max-width: 600px) {
            .container {
                padding: 2rem;
            }
            h1 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 상단 헤더: 이름과 소속 -->
        <header>
            <h1>남선우</h1>
            <p class="subtitle">경희대학교 의과대학 학부생</p>
        </header>

        <!-- 1. 자기소개 섹션 -->
        <div class="about-section">
            <h2 class="section-title">자기소개</h2>
            <p>안녕하세요. 저는 현재 경희대학교 의과대학에 재학중인 학부생입니다.</p>
            <p>저는 신경과학을 중심으로 유전체분석, 계산신경과학, 시스템 생물학 등을 폭넓게 탐색하고 있습니다. 특히 신경세포의 유전체 분석에 깊은 관심을 느끼고 있습니다.</p>
            <p>저와 비슷한 관심분야를 가진 분들의 만남은 언제나 환영입니다. 저와의 교류를 희망하시는 분은 언제든지 제게 연락을 주시면 감사하겠습니다.</p>
        </div>

        <!-- 2. 관심분야 섹션 -->
        <div class="interests-section">
            <h2 class="section-title">관심 분야</h2>
            <div class="interests-tags">
                <span class="tag">계산신경과학</span>
                <span class="tag">신경유전학</span>
                <span class="tag">생물정보학</span>
                <span class="tag">신경발달</span>
                <span class="tag">멀티오믹스</span>
            </div>
        </div>

        <!-- 3. 관련 링크 섹션 -->
        <div class="links-section">
            <h2 class="section-title">Contact & Links</h2>
            <a href="mailto:sunwoodotnam@gmail.com" class="link-item">
                <i class="fa-regular fa-envelope"></i> sunwoodotnam@gmail.com
            </a>
            <a href="https://www.linkedin.com/in/sunwoo-nam317" target="_blank" rel="noopener noreferrer" class="link-item">
                <i class="fa-brands fa-linkedin"></i> LinkedIn
            </a>
            <a href="https://velog.io/@swnam818/posts" target="_blank" rel="noopener noreferrer" class="link-item">
                <i class="fa-solid fa-pen-nib"></i> Velog
            </a>
        </div>
    </div>
</body>
</html>****
