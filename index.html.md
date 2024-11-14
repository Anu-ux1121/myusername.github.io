<!DOCTYPE html>
<html lang="mn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Миний Гоёмсог Вебсайт</title>
    <style>
        /* Нийтлэг тохиргоо */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            color: #333;
            background-color: #f9f9f9;
        }

        /* Толгой хэсэг */
        header {
            background-image: linear-gradient(to right, #6a11cb, #2575fc);
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2em;
        }

        /* Навигаци */
        nav {
            background-color: #444;
            padding: 10px 0;
        }

        nav ul {
            list-style-type: none;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.1em;
        }

        nav ul li a:hover {
            color: #ffd700;
        }

        /* Контент хэсэг */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .intro {
            text-align: center;
            margin-bottom: 30px;
        }

        .intro h2 {
            font-size: 2em;
            margin-bottom: 10px;
        }

        .intro p {
            font-size: 1.1em;
            color: #555;
        }

        .features {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .feature-box {
            flex: 1 1 300px;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .feature-box h3 {
            font-size: 1.5em;
            color: #6a11cb;
            margin-bottom: 10px;
        }

        .feature-box p {
            color: #666;
        }

        /* Хөл хэсэг */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 30px;
        }

        footer p {
            font-size: 0.9em;
        }
    </style>
</head>
<body>

    <!-- Толгой хэсэг -->
    <header>
        <h1>Миний Гоёмсог Вебсайт</h1>
        <p>Эндээс та сонирхолтой мэдээ, мэдээллийг унших болно</p>
    </header>

    <!-- Навигаци -->
    <nav>
        <ul>
            <li><a href="#">Нүүр</a></li>
            <li><a href="#">Бидний тухай</a></li>
            <li><a href="#">Үйлчилгээ</a></li>
            <li><a href="#">Холбоо барих</a></li>
        </ul>
    </nav>

    <!-- Контент хэсэг -->
    <div class="container">
        <!-- Танилцуулга -->
        <section class="intro">
            <h2>Манай сайтыг сонирхоорой!</h2>
            <p>Энэхүү вебсайтад та төрөл бүрийн сонирхолтой, хэрэгцээтэй мэдээллүүдийг олж унших болно.</p>
        </section>

        <!-- Үйлчилгээний хэсэг -->
        <section class="features">
            <div class="feature-box">
                <h3>Чанартай контент</h3>
                <p>Бид уншигчдад зориулан чанартай, мэдлэгтэй мэдээллүүдийг хүргэж байна.</p>
            </div>
            <div class="feature-box">
                <h3>Хэрэглэгчидтэй ойр</h3>
                <p>Таны санал, хүсэлтийг байнга сонсож, вебсайтаа сайжруулж байна.</p>
            </div>
            <div class="feature-box">
                <h3>Олон төрлийн мэдээлэл</h3>
                <p>Сонирхолтой мэдээ, мэдээлэл, зөвлөгөө зэрэг төрөл бүрийн контентыг та эндээс уншаарай.</p>
            </div>
        </section>
    </div>

    <!-- Хөл хэсэг -->
    <footer>
        <p>&copy; 2024 Миний Гоёмсог Вебсайт. Бүх эрх хуулиар хамгаалагдсан.</p>
    </footer>

</body>
</html>