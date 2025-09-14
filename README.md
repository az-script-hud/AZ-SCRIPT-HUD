<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AZ SCRIPT BETA - README</title>
    <style>
        :root {
            --dark-bg: #1e1e1e;
            --primary-bg: #2d2d2d;
            --text-color: #e0e0e0;
            --header-color: #ffffff;
            --accent-color: #00aaff;
            --border-color: #444444;
            --code-bg: #1a1a1a;
            --warning-bg: #4a2c2c;
            --warning-border: #ff5555;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background-color: var(--dark-bg);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
            line-height: 1.7;
            font-size: 16px;
        }

        .container {
            max-width: 850px;
            margin: 0 auto;
            background-color: var(--primary-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 20px 40px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.4);
        }

        h1, h2, h3 {
            color: var(--header-color);
            font-weight: 600;
            margin-top: 1.5em;
            margin-bottom: 0.8em;
            padding-bottom: 0.3em;
            border-bottom: 1px solid var(--border-color);
        }

        h1 {
            text-align: center;
            font-size: 2.5em;
            border-bottom: 2px solid var(--accent-color);
            margin-top: 0;
        }

        h2 {
            font-size: 1.8em;
        }

        h3 {
            font-size: 1.4em;
            border-bottom: none;
        }
        
        h3 .icon {
            margin-left: 10px;
        }
        
        p {
            margin-bottom: 1em;
        }

        strong {
            color: var(--accent-color);
            font-weight: 600;
        }

        .code-container {
            position: relative;
            margin-bottom: 1.5em;
        }
        
        pre {
            background-color: var(--code-bg);
            padding: 20px;
            border-radius: 8px;
            border: 1px solid var(--border-color);
            overflow-x: auto;
            white-space: pre-wrap;
            word-wrap: break-word;
            font-family: 'Courier New', Courier, monospace;
        }
        
        code {
            color: #d4d4d4;
            font-size: 0.95em;
        }

        .copy-btn {
            position: absolute;
            top: 10px;
            left: 10px; /* Adjusted for RTL */
            background-color: var(--accent-color);
            color: white;
            border: none;
            padding: 8px 12px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            transition: background-color 0.2s;
        }

        .copy-btn:hover {
            background-color: #0088cc;
        }

        .copy-btn.copied {
            background-color: #28a745;
        }

        ul {
            list-style: none;
            padding-right: 20px;
        }

        ul li {
            position: relative;
            padding-right: 25px;
            margin-bottom: 12px;
        }

        ul li::before {
            content: '🔹';
            position: absolute;
            right: 0;
            top: 0;
            color: var(--accent-color);
        }
        
        ol {
            padding-right: 20px;
        }
        
        ol li {
            margin-bottom: 10px;
        }

        .warning-box {
            background-color: var(--warning-bg);
            border-right: 5px solid var(--warning-border);
            border-radius: 8px;
            padding: 15px 20px;
            margin-top: 2em;
        }

        .warning-box h3 {
            margin-top: 0;
            color: var(--warning-border);
        }

        hr {
            border: 0;
            height: 1px;
            background: var(--border-color);
            margin: 2em 0;
        }

    </style>
</head>
<body>

    <div class="container">
        <h1>🚀 AZ SCRIPT BETA</h1>

        <p>
            سكريبت AZ SCRIPT BETA هو أداة مساعدة قوية وشاملة مصممة لتحسين تجربتك في ألعاب Roblox القتالية. يجمع السكريبت بين مجموعة واسعة من الميزات الدقيقة والقوية، بدءًا من مساعد التصويب المتقدم وكشف الأماكن، وصولًا إلى تحسينات الأداء وتعديلات حركة اللاعب.
        </p>

        <hr>

        <h3><span class="icon">📥</span> طريقة الاستعمال</h3>
        <p>استخدام السكريبت سهل للغاية. اتبع الخطوات التالية:</p>
        <ol>
            <li><strong>احصل على منفذ (Executor):</strong> يجب أن يكون لديك منفذ سكريبتات متوافق مع Roblox.</li>
            <li><strong>انسخ رابط التشغيل:</strong> اضغط على الزر لنسخ الكود أدناه.</li>
            <li><strong>قم بالتشغيل:</strong> الصق الكود المنسخ في المنفذ الخاص بك وقم بتشغيله.</li>
        </ol>

        <h3><span class="icon">📋</span> رابط التشغيل (قابل للنسخ)</h3>
        <div class="code-container">
            <button class="copy-btn" id="copyButton">نسخ</button>
            <pre><code id="scriptCode">loadstring(game:HttpGet("https://raw.githubusercontent.com/az-script-hud/AZ-SCRIPT-HUD/refs/heads/main/AZ%20SCRIPT.lua"))()</code></pre>
        </div>

        <hr>

        <h2>✨ أبرز الميزات</h2>
        <p>يحتوي السكريبت على واجهة رسومية سهلة الاستخدام مقسمة إلى عدة أقسام لتسهيل الوصول إلى جميع الميزات.</p>

        <h3><span class="icon">🎯</span> مساعد التصويب (Aim Assist)</h3>
        <ul>
            <li><strong>تفعيل مساعد التصويب:</strong> قفل تلقائي وسلس على الأعداء.</li>
            <li><strong>تجاهل الفريق:</strong> لتجنب التصويب على زملائك.</li>
            <li><strong>تجاهل الجدران:</strong> للتحقق من أن العدو ليس خلف جدار.</li>
            <li><strong>حجم مجال الرؤية (FOV):</strong> دائرة مرئية لتحديد نطاق عمل مساعد التصويب.</li>
            <li><strong>إشعار بأقرب عدو:</strong> واجهة صغيرة في أعلى الشاشة تعرض اسم ومسافة أقرب عدو لك.</li>
        </ul>

        <h3><span class="icon">💥</span> Hitbox (صندوق الإصابة)</h3>
        <ul>
            <li><strong>موسع الـ Hitbox:</strong> زيادة حجم صندوق الإصابة للأعداء لتسهيل إصابتهم (تفعيل/إيقاف، تجاهل الفريق، تخصيص الحجم والشفافية).</li>
            <li><strong>حركة اللاعب:</strong>
                <ul>
                    <li><strong>سرعة المشي (WalkSpeed):</strong> تحكم كامل في سرعة حركتك.</li>
                    <li><strong>قوة القفز (JumpPower):</strong> اقفز أعلى من المعتاد.</li>
                    <li><strong>اختراق الجدران (Noclip):</strong> القدرة على الطيران والمرور عبر الجدران.</li>
                    <li><strong>قفز لانهائي (Infinite Jump):</strong> اقفز في الهواء بشكل متكرر.</li>
                </ul>
            </li>
        </ul>

        <h3><span class="icon">👁️</span> كشف الأماكن (ESP)</h3>
        <ul>
            <li><strong>تفعيل ESP الشامل:</strong> رؤية معلومات كاملة عن اللاعبين الآخرين من خلال الجدران.</li>
            <li><strong>تلوين اللاعبين (Chams):</strong> تلوين الأعداء بلون مميز لرؤيتهم بوضوح.</li>
            <li><strong>الصناديق (Boxes):</strong> رسم صندوق حول كل لاعب (نمط زاوية أو كامل).</li>
            <li><strong>الخطوط (Tracers):</strong> رسم خط من شاشتك إلى كل لاعب.</li>
            <li><strong>شريط الصحة (Health Bar):</strong> عرض شريط يوضح صحة كل لاعب.</li>
            <li><strong>الأسماء (Names):</strong> إظهار اسم كل لاعب.</li>
            <li><strong>المسافة (Distance):</strong> إظهار بعدك عن كل لاعب بالأمتار.</li>
            <li><strong>الهيكل العظمي (Skeleton):</strong> رسم الهيكل العظمي لكل لاعب.</li>
        </ul>

        <h3><span class="icon">🎨</span> المرئيات (Visuals)</h3>
        <ul>
            <li><strong>قوس قزح شامل:</strong> تفعيل ألوان قوس قزح لجميع عناصر الـ ESP ودائرة الـ FOV.</li>
            <li><strong>تخصيص الألوان:</strong> تغيير ألوان عناصر الـ ESP والـ FOV.</li>
            <li><strong>أوضاع السماء:</strong> تغيير شكل السماء لتحسين الرؤية والأجواء القتالية.</li>
            <li><strong>حركة بطيئة عند القتال:</strong> تأثير درامي عند الاشتباك مع الأعداء.</li>
        </ul>

        <h3><span class="icon">⚡</span> التحسينات (Optimizations)</h3>
        <ul>
            <li><strong>تحسين FPS:</strong> تقليل جودة الرسوميات بشكل كبير لزيادة معدل الإطارات في الثانية.</li>
            <li><strong>فاتح FPS:</strong> إزالة حد الـ 60 إطارًا في الثانية للحصول على تجربة أكثر سلاسة.</li>
            <li><strong>تحسين Ping:</strong> تقليل استخدام الشبكة عن طريق تعطيل بعض التأثيرات غير الضرورية.</li>
        </ul>

        <div class="warning-box">
            <h3><span class="icon">⚠️</span> تنبيه هام</h3>
            <ul>
                <li>استخدام السكريبتات يخالف شروط خدمة Roblox.</li>
                <li>هناك خطر دائم من حظر حسابك عند استخدام أي نوع من أدوات الغش.</li>
                <li>ينصح بشدة باستخدام حساب بديل لتجربة السكريبت.</li>
                <li>أنت المسؤول الوحيد عن أي إجراء يتم اتخاذه ضد حسابك. استخدمه على مسؤوليتك الخاصة.</li>
            </ul>
        </div>
    </div>

    <script>
        document.getElementById('copyButton').addEventListener('click', function() {
            const scriptText = document.getElementById('scriptCode').innerText;
            navigator.clipboard.writeText(scriptText).then(() => {
                const button = document.getElementById('copyButton');
                button.innerText = 'تم النسخ!';
                button.classList.add('copied');
                
                setTimeout(() => {
                    button.innerText = 'نسخ';
                    button.classList.remove('copied');
                }, 2000);
            }).catch(err => {
                console.error('Failed to copy text: ', err);
            });
        });
    </script>

</body>
</html>