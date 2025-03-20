<!-- <!DOCTYPE html> -->
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="ChanHyeok Jeon의 개인 웹페이지입니다.">
    <title>ChanHyeok Jeon - 소개 페이지</title>
    <link rel="stylesheet" href="styles.css"> <!-- 스타일을 외부 CSS 파일로 분리 -->
    <style>
        /* 기본적인 스타일을 여기에도 추가할 수 있습니다 */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            margin: 0;
        }
        section {
            padding: 20px;
            margin: 20px;
        }
        .content {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .content div {
            flex: 1;
            margin: 10px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
        }
        .content div h2 {
            color: #333;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>안녕하세요, 저는 전찬혁(ChanHyeok Jeon)입니다!</h1>
        <p>개발자 | 기술 enthusiast | 열정적인 학습자</p>
    </header>

    <section>
        <h2>👨‍💻 나에 대해</h2>
        <p>저는 백엔드 개발을 전문으로 하는 개발자입니다. 새로운 기술을 배우고, 다양한 프로젝트를 만들어가며 성장하는 것을 좋아합니다.</p>
        
        <div class="content">
            <div>
                <h2>📚 기술 스택</h2>
                <ul>
                    <li>프론트엔드: HTML, CSS, JavaScript</li>
                    <li>백엔드: C, C++, Python, java</li>
                    <li>데이터베이스: MySQL</li>
                    <li>기타 도구: Git</li>
                </ul>
            </div>
            <div>
                <h2>💼 현재 프로젝트</h2>
                <p>Yolov5기반 불법 쓰레기 투기 방지 어플리케이션등이 있습니다. </p>
            </div>
            <div>
                <h2>📫 연락처</h2>
                <p>이메일: <a href="mailto:cx8207@naver.com">cx8207@naver.com</a></p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 ChanHyeok Jeon. All rights reserved.</p>
    </footer>

</body>
</html>
