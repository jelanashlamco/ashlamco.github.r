<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>عبدالسلام عدنان الجيلاني - مطور ويب</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            color: #333;
        }
        header {
            background-color: #2e7d32;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #1b5e20;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 40px 20px;
        }
        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .project {
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 8px;
            width: 250px;
            padding: 15px;
        }
        footer {
            background-color: #2e7d32;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            margin-bottom: 10px;
            padding: 10px;
            border-radius: 4px;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>
    <header>
        <h1>اشلامكو شلوم</h1>
        <p>مطور ويب ومصمم مواقع</p>
    </header>
    <nav>
        <a href="#about">عنّي</a>
        <a href="#portfolio">معرض الأعمال</a>
        <a href="#contact">اتصل بي</a>
    </nav>
    <section id="about">
        <h2>عنّي</h2>
        <p>أنا اشلامكو شلوم، مصمم ويب وإنشاء مواقع ومختص في البرمجة. أعمل على تطوير مواقع احترافية وعصرية تلبي حاجات العملاء.</p>
    </section>
    <section id="portfolio">
        <h2>معرض الأعمال</h2>
        <div class="projects">
            <div class="project">
                <h3>مشروع 1</h3>
                <p>وصف مختصر للمشروع الأول.</p>
            </div>
            <div class="project">
                <h3>مشروع 2</h3>
                <p>وصف مختصر للمشروع الثاني.</p>
            </div>
            <!-- أضف المزيد حسب الحاجة -->
        </div>
    </section>
    <section id="contact">
        <h2>اتصل بي</h2>
        <form class="contact-form">
            <input type="text" placeholder="الاسم" required>
            <input type="email" placeholder="البريد الإلكتروني" required>
            <textarea rows="5" placeholder="رسالتك" required></textarea>
            <button type="submit">إرسال</button>
        </form>
        <p>أو تواصل عبر البريد: <a href="mailto:ashlamco144@gmail.com">ashlamco144@gmail.com</a></p>
    </section>
    <footer>
        <p>&copy; 2025 اشلامكو شلوم. جميع الحقوق محفوظة.</p>
    </footer>
</body>
</html>
