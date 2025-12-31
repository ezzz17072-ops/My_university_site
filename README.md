# My_university_site
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>مشروع الجامعة</title>
  <style>
    /* الخلفية */
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 0;
      color: #333;
    }

    /* العنوان الرئيسي */
    h1 {
      text-align: center;
      margin-top: 40px;
      color: #2c3e50;
    }

    /* الفقرات */
    p {
      max-width: 700px;
      margin: 20px auto;
      line-height: 1.6;
      font-size: 16px;
    }

    /* روابط */
    a {
      color: #2980b9;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }

    /* قسم محتوى */
    .content {
      background-color: #fff;
      padding: 20px;
      margin: 20px auto;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>

  <h1>جامعة المثال</h1>

  <div class="content">
    <p>هذا نص توضيحي عن المشروع. تقدر تضيفي هنا معلومات عن الجامعة، الأقسام، والمميزات.</p>
    <p>مثال على رابط: <a href="#">زيارة الموقع الرسمي</a></p>
  </div>

</body>
</html>
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>جامعة الأفق</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Tahoma;
            direction: rtl;
            background-color: #f5f7fa;
        }

        header {
            background: url("images/banner.jpg") center/cover no-repeat;
            height: 350px;
            color: white;
            position: relative;
        }

        header::after {
            content: "";
            position: absolute;
            inset: 0;
            background-color: rgba(0,0,0,0.6);
        }

        .header-content {
            position: relative;
            z-index: 2;
            text-align: center;
            top: 50%;
            transform: translateY(-50%);
        }

        .header-content img {
            width: 90px;
            margin-bottom: 10px;
        }

        nav {
            background-color: #1e3a5f;
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 18px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            background-color: white;
            margin: 30px auto;
            padding: 25px;
            width: 85%;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
        }

        h2 {
            color: #1e3a5f;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }

        .gallery img {
            width: 100%;
            border-radius: 10px;
        }

        footer {
            background-color: #1e3a5f;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }

        .project-info {
            background-color: #eef2f7;
            text-align: center;
            font-weight: bold;
        }
    </style>
</head>
<body>

<header>
    <div class="header-content">
        <img src="images/logo.png" alt="شعار الجامعة">
        <h1>جامعة الأفق</h1>
        <p>نحو تعليم جامعي يواكب المستقبل</p>
    </div>
</header>

<nav>
    <a href="#about">عن الجامعة</a>
    <a href="#colleges">الكليات</a>
    <a href="#gallery">الصور</a>
    <a href="#contact">التواصل</a>
</nav>

<section id="about">
    <h2>عن الجامعة</h2>
    <p>
        جامعة الأفق جامعة تعليمية حديثة تهدف إلى تقديم تعليم عالي الجودة
        باستخدام أحدث التقنيات، وتسعى إلى تخريج طلاب مؤهلين لخدمة المجتمع
        وسوق العمل.
    </p>
</section>

<section id="colleges">
    <h2>الكليات</h2>
    <ul>
        <li>كلية الحاسب وتقنية المعلومات</li>
        <li>كلية الهندسة</li>
        <li>كلية العلوم الإدارية</li>
        <li>كلية الطب</li>
        <li>كلية الآداب</li>
    </ul>
</section>

<section id="gallery">
    <h2>معرض الصور</h2>
    <div class="gallery">
        <img src="images/library.jpg" alt="مكتبة">
        <img src="images/students.jpg" alt="طلاب">
        <img src="images/class.jpg" alt="قاعة دراسية">
    </div>
</section>

<section id="contact">
    <h2>معلومات التواصل</h2>
    <p>📍 الموقع: الرياض – المملكة العربية السعودية</p>
    <p>📧 البريد الإلكتروني: info@alofaq-university.edu</p>
    <p>📞 الهاتف: +966 55 123 4567</p>
</section>

<section class="project-info">
    <h2>معلومات المشروع</h2>
    <p>إعداد الطالبة: سلا محمد</p>
    <p>إشراف الدكتور: عز الدين النزيلي</p>
</section>

<footer>
    <p>© 2025 جامعة الأفق – جميع الحقوق محفوظة</p>
</footer>

</body>
</html>
