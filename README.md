# Hala-Bani-atta
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ترخيص الصيدليات</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #0d6efd;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        header p {
            margin: 5px 0;
        }
        .container {
            width: 90%;
            margin: 20px auto;
            max-width: 1200px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #0d6efd;
            border-bottom: 2px solid #0d6efd;
            padding-bottom: 5px;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            margin: 10px 0;
            background: #eef2ff;
            padding: 10px;
            border-radius: 5px;
        }
        .note {
            background: #fff3cd;
            color: #856404;
            padding: 15px;
            margin: 20px 0;
            border-radius: 5px;
        }
        .links {
            margin-top: 20px;
            text-align: center;
        }
        .links a {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            text-decoration: none;
            color: white;
            background-color: #0d6efd;
            border-radius: 5px;
            font-size: 1rem;
        }
        .links a:hover {
            background-color: #0056b3;
        }
        form {
            margin-top: 20px;
            display: flex;
            flex-direction: column;
        }
        label {
            margin: 10px 0 5px;
        }
        input, textarea, button {
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
        }
        button {
            background-color: #0d6efd;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
        footer {
            text-align: center;
            background-color: #0d6efd;
            color: white;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>متطلبات ترخيص الصيدليات</h1>
        <p>توفير الوقت والجهد والمال من خلال الخطوات الإلكترونية</p>
    </header>
    <div class="container">
        <h2>الأوراق المطلوبة</h2>
        <ul>
            <li>صورة عن ترخيص مزاولة المهنة للصيدلي مقدم الطلب.</li>
            <li>صورة عن هوية الأحوال المدنية.</li>
            <li>كشف عن الالتزامات المالية يوضح عدم وجود ذمة مالية مستحقة تجاه النقابة حتى تاريخه.</li>
            <li>صورة عن سند ملكية الصيدلي للعقار أو عقد استئجاره.</li>
            <li>مخطط كروكي صادر عن مساح أو مكتب هندسي مرخص يبين مساحة المكتب.</li>
            <li>مخطط أراضي ومخطط تنظيمي للقطعة المراد ترخيص الصيدلية عليها.</li>
        </ul>

        <h2>الشروط الأساسية</h2>
        <ul>
            <li>مساحة الصيدلية لا تقل عن 32 متراً مربعاً.</li>
            <li>المسافة بين الصيدلية المراد ترخيصها وأقرب صيدلية أخرى لا تقل عن 200 متر.</li>
            <li>اسم الصيدلية يجب أن يكون فريداً وغير مستخدم من قبل صيدلية أخرى.</li>
            <li>موافقة المجلس التنظيمي على رخصة الصيدلية المقترحة.</li>
        </ul>

        <div class="note">
            <strong>ملاحظات:</strong>
            <p>يجب تقديم جميع الوثائق بشكل رسمي ومختوم من الجهات المعنية مثل المساح والمجلس التنظيمي.</p>
        </div>

        <h2>النموذج الإلكتروني</h2>
        <form id="pharmacyForm">
            <label for="name">اسم الصيدلي:</label>
            <input type="text" id="name" name="name" placeholder="أدخل اسمك" required>

            <label for="id">رقم الهوية:</label>
            <input type="text" id="id" name="id" placeholder="أدخل رقم الهوية" required>

            <label for="license">رقم ترخيص مزاولة المهنة:</label>
            <input type="text" id="license" name="license" placeholder="أدخل رقم الترخيص" required>

            <label for="details">تفاصيل إضافية:</label>
            <textarea id="details" name="details" rows="4" placeholder="اكتب أي ملاحظات أو تفاصيل إضافية"></textarea>

            <label for="file">إضافة صورة أو ملف PDF:</label>
            <input type="file" id="file" name="file" accept="image/*,.pdf" multiple required>

            <div class="note">
                <strong>ملاحظة:</strong> سيتم فتح محادثة WhatsApp تلقائيًا لإرسال النصوص. يرجى إرفاق الملفات يدويًا داخل المحادثة.
            </div>

            <button type="button" onclick="sendToWhatsApp()">إرسال</button>
        </form>

        <div class="links">
            <a href="https://shorturl.at/bzHJ2" target="_blank">الاستفسار عبر الموقع</a>
            <a href="https://wa.me/962781339210" target="_blank">التواصل عبر WhatsApp</a>
        </div>
    </div>
    <footer>
        <p>© 2024 - تطبيق إدارة وترخيص الصيدليات</p>
    </footer>

    <script>
        function sendToWhatsApp() {
            const name = document.getElementById('name').value;
            const id = document.getElementById('id').value;
            const license = document.getElementById('license').value;
            const details = document.getElementById('details').value;

            const message = `مرحباً،\n\nأود إرسال الأوراق التالية لترخيص الصيدلية:\n\n- اسم الصيدلي: ${name}\n- رقم الهوية: ${id}\n- رقم ترخيص مزاولة المهنة: ${license}\n\nتفاصيل إضافية:\n${details}\n\nيرجى مراجعة الملفات المرفقة لاحقاً.`;
            const whatsappNumber = "962781339210";

            const url = `https://wa.me/${whatsappNumber}?text=${encodeURIComponent(message)}`;
            window.open(url, '_blank');
        }
    </script>
</body>
</html>
