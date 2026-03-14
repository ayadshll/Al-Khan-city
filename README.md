<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الخان .. حكاية عشق لا تنتهي</title>
    <!-- Google Fonts للخطوط العربية -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700;900&family=Tajawal:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Cairo', 'Tajawal', sans-serif;
            background: linear-gradient(145deg, #fef9e7 0%, #fae6d1 100%);
            color: #3e2c1f;
            line-height: 1.8;
            padding: 20px;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            max-width: 1100px;
            width: 100%;
            background: rgba(255, 255, 255, 0.5);
            backdrop-filter: blur(10px);
            border-radius: 40px;
            box-shadow: 0 25px 50px -8px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            border: 1px solid rgba(255, 215, 175, 0.7);
            padding: 30px;
        }

        header {
            text-align: center;
            margin-bottom: 40px;
            position: relative;
        }

        header h1 {
            font-size: 4rem;
            font-weight: 900;
            color: #b45f2b;
            text-shadow: 3px 3px 0 #ffe1b3;
            letter-spacing: 2px;
            animation: fadeInDown 1s ease;
        }

        header p {
            font-size: 1.7rem;
            color: #7b4a2c;
            background: rgba(255, 235, 205, 0.8);
            display: inline-block;
            padding: 10px 30px;
            border-radius: 60px;
            margin-top: 20px;
            box-shadow: 0 10px 20px -5px rgba(180, 95, 43, 0.3);
            font-weight: 700;
        }

        .hero-image {
            width: 100%;
            height: 400px;
            /* تم استبدال الصورة القديمة بصورة لخان بني سعد في ديالى */
            background: url('') center/cover no-repeat;
            border-radius: 30px;
            margin: 40px 0;
            box-shadow: 0 20px 30px -5px rgba(0, 0, 0, 0.3);
            transition: transform 0.5s, box-shadow 0.5s;
            border: 5px solid #fbe9d2;
        }

        .hero-image:hover {
            transform: scale(1.02);
            box-shadow: 0 30px 40px -5px #b45f2b;
        }

        .content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin: 50px 0;
        }

        .card {
            background: rgba(253, 242, 226, 0.8);
            backdrop-filter: blur(4px);
            border-radius: 30px;
            padding: 30px 20px;
            box-shadow: 0 15px 30px -8px #d9b48f;
            border: 1px solid #fff1dd;
            transition: all 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
            background: #fae2c1;
        }

        .card h2 {
            font-size: 2.2rem;
            color: #9d5430;
            margin-bottom: 15px;
            border-right: 8px solid #c78a5c;
            padding-right: 20px;
        }

        .card p {
            font-size: 1.2rem;
            color: #3f2e1d;
            margin-bottom: 15px;
        }

        .heart-icon {
            color: #c44536;
            font-size: 2rem;
            display: inline-block;
            animation: heartbeat 1.5s infinite;
        }

        .developer-story {
            background: #dbb48b;
            border-radius: 40px;
            padding: 40px;
            color: #2b1b0f;
            text-align: center;
            margin-top: 40px;
            border: 4px dashed #ffeac2;
        }

        .developer-story h3 {
            font-size: 2.5rem;
            font-weight: 900;
            margin-bottom: 20px;
        }

        .developer-story p {
            font-size: 1.5rem;
            font-weight: 700;
            background: #fff7e3;
            display: inline-block;
            padding: 15px 40px;
            border-radius: 60px;
            box-shadow: 0 8px 0 #8b5a32;
        }

        .glow-text {
            color: #a9341c;
            font-size: 1.8rem;
            font-weight: 900;
        }

        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 1.2rem;
            color: #6b4b2e;
            border-top: 2px solid #efd6b5;
            padding-top: 25px;
        }

        /* animations */
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes heartbeat {
            0% { transform: scale(1); }
            25% { transform: scale(1.3); }
            35% { transform: scale(1); }
            45% { transform: scale(1.15); }
            55% { transform: scale(1); }
            100% { transform: scale(1); }
        }

        /* استجابة للأجهزة الصغيرة */
        @media (max-width: 700px) {
            header h1 {
                font-size: 3rem;
            }
            .hero-image {
                height: 250px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>الـخـان</h1>
            <p>حيث يسكن الجمال ويُفتن العقل</p>
        </header>

        <!-- تم تغيير الصورة هنا: خان بني سعد في ديالى -->
        <div class="hero-image" aria-label="صورة لخان بني سعد في ديالى"></div>

        <section class="content">
            <div class="card">
                <h2>✨ سحر الشرق</h2>
                <p>الخان ليس مجرد مكان، إنه لوحة فنية رسمتها الأزقة القديمة ورائحة البهارات ودفء أهلها. كل زاوية تحكي قصة، وكل حجر يروي حكاية عشق.</p>
                <span class="heart-icon">❤️</span>
            </div>
            <div class="card">
                <h2>🌙 ليالي الخان</h2>
                <p>تحت ضوء القمر، تزداد الأزقة جمالاً وغموضاً. الأضواء الخافتة، والمقاهي الشعبية، وأصوات الموسيقى الهادئة تجعل القلب يخفق بحنين لا يُوصف.</p>
                <span class="heart-icon">❤️</span>
            </div>
            <div class="card">
                <h2>🍃 نسمات الخان</h2>
                <p>الهواء هناك معبق بعبق التاريخ والياسمين. تمشي فتجد نفسك تائهًا في عالم من الجمال، لا تفكر إلا بالبقاء.</p>
                <span class="heart-icon">❤️</span>
            </div>
        </section>

        <div class="developer-story">
            <h3>💖 لماذا أحب الخان؟</h3>
            <p>يقول مطور هذا الموقع:<br> "أحب الخان كثيرًا، لأن هناك شخصًا أخذ عقلي وقلبي هناك. كلما زرت تلك المنطقة، أعيش أجمل الذكريات، وأشعر أنني أطير من الفرح. الخان هو مكاني المفضل في الكون كله."</p>
            <div class="glow-text">✨ شخص واحد جعل الخان أجمل بقعة على وجه الأرض ✨</div>
        </div>

        <footer>
            <p>صُنع بحب ❤️ لمطور يعشق الخان وذاك الشخص الذي أسره.</p>
            <button id="loveButton" style="background: #b45f2b; color: white; border: none; padding: 12px 30px; border-radius: 50px; font-size: 1.3rem; margin-top: 15px; cursor: pointer; font-family: 'Cairo', sans-serif; font-weight: bold; box-shadow: 0 5px 0 #6d3c1d; transition: 0.1s;">💬 حدثني عن الخان</button>
        </footer>
    </div>

    <script>
        document.getElementById('loveButton').addEventListener('click', function() {
            // رسائل عشوائية جميلة عن الخان
            const messages = [
                "الخان هو عنوان الجمال، ومن فيه أخذ العقل والروح.",
                "لو كان الخان وردة، لكنت أنا النحلة التي لا تفارقه.",
                "شخص واحد جعل الخان أغلى من الدنيا كلها.",
                "في الخان.. وجدت نفسي ووجدت قلبي مع شخص أحبه.",
                "لولا ذاك الإنسان، لما كان للخان هذا الجمال في عيوني.",
                "الخان سرّي الذي لا أبوح به إلا لمن يحب."
            ];
            const randomIndex = Math.floor(Math.random() * messages.length);
            alert(messages[randomIndex]);
        });

        // تأثير إضافي: تغيير لون الخلفية قليلاً عند تحريك الماوس (نكتة بسيطة)
        const hero = document.querySelector('.hero-image');
        hero.addEventListener('mousemove', function(e) {
            const x = (e.clientX / window.innerWidth * 20) - 10;
            const y = (e.clientY / window.innerHeight * 20) - 10;
            hero.style.transform = `scale(1.02) translate(${x}px, ${y}px)`;
        });
        hero.addEventListener('mouseleave', function() {
            hero.style.transform = 'scale(1)';
        });
    </script>
</body>
</html>
