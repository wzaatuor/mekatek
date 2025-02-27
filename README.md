# mekatek
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>wissam-mekatek</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>مرحبًا بكم في wissam-mekatek</h1>
        <nav>
            <ul>
                <li><a href="#about">من نحن</a></li>
                <li><a href="#services">الخدمات</a></li>
                <li><a href="#Our work">اعمالنا</a></li>
                <li><a href="#contact">اتصل بنا</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>من نحن</h2>
        <p>نحن شركة ناشئة متخصصة في تقديم حلول مبتكرة في عدة مجالات صناعية و تصنيع الات بلاستيك موفرة للطاقة.</p>
         <img src="images/شعار-الشركة.jpg" alt="شعار الشركة" width="200">
    </section>

    <section id="services">
        <h2>الخدمات</h2>
        <ul>
            <li>بيع الات بلاستيك كبيرة و صغيرة</li>
            <li>تركيب و تعديل نظم التحكم في الالات و المعامل</li>
            <li>استشارات تقنية و فنية</li>
            <li>تقديم دورات في مجال التحكم و البرمجة</li>
        </ul>
           <img src="images/صورة-الخدمات.jpg" alt="صورة الخدمات" width="300">
    </section>
<section id="Our work">
        <h2>اعمالنا</h2>
<ul>
            <li>تصنيع وتشغيل مكنة حقن صغيرة</li>
            <li>تركيب و تعديل نظم التحكم في معمل فاروق فرحات</li>
            <li>استشارات تقنية و فنية لعدة معامل</li>
            <li>تركيب انفرتر لمكنة حقن في حفسرجة وعقربات و الدانا لتوفير الطاقة</li>
        </ul>
            <img src="images/اعمالنا.jpg" alt="صورة الخدمات" width="300">
  </section>

    <section id="contact">
        <h2>اتصل بنا</h2>
        <form>
            <label for="name">الاسم:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">البريد الإلكتروني:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">الرسالة:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">إرسال</button>
        </form>
    </section>
    body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 0;
    text-align: right;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 8px;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-bottom: 5px;
}

form input, form textarea, form button {
    margin-bottom: 10px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    background-color: #4CAF50;
    color: white;
    border: none;
    cursor: pointer;
}

form button:hover {
    background-color: #45a049;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
}

    <footer>
        <p>© 2023 شركتي الناشئة. جميع الحقوق محفوظة.</p>
    </footer>
</body>
</html>
