# MrJoe-Center
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سنتر مستر جو</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            background-color: #f4f4f4;
            margin: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            text-align: center;
            background-color: #555;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: inline-block;
        }
        nav a:hover {
            background-color: #777;
        }
        .teacher-card {
            background-color: white;
            border: 1px solid #ccc;
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
            display: inline-block;
            width: 250px;
            text-align: center;
        }
        .teachers {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>مرحبًا بكم في سنتر مستر جو</h1>
    </header>

    <nav>
        <a href="#">الرئيسية</a>
        <a href="#">المدرسين</a>
        <a href="#">تواصل معنا</a>
    </nav>

    <div class="teachers">
        <div class="teacher-card">
            <h2>أستاذ أحمد</h2>
            <p>رقم الهاتف: 01012345678</p>
            <p>مواعيد الدروس: السبت والثلاثاء</p>
            <p>المواد: الرياضيات، الفيزياء</p>
        </div>
        <div class="teacher-card">
            <h2>أستاذة منى</h2>
            <p>رقم الهاتف: 01087654321</p>
            <p>مواعيد الدروس: الأحد والأربعاء</p>
            <p>المواد: الكيمياء، الأحياء</p>
        </div>
        <div class="teacher-card">
            <h2>أستاذ محمد</h2>
            <p>رقم الهاتف: 01011223344</p>
            <p>مواعيد الدروس: الاثنين والخميس</p>
            <p>المواد: اللغة العربية، التاريخ</p>
        </div>
    </div>

    <footer>
        <p>للتواصل معنا: 01001234567 | سنتر مستر جو</p>
    </footer>
</body>
</html>
