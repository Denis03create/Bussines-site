<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Business — визитка</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
            background: #ffffff;
            color: #111;
            line-height: 1.6;
        }

        /* Контейнер */
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 24px 16px;
        }

        /* Шапка */
        header {
            padding: 60px 0 40px;
            text-align: center;
        }

        header h1 {
            font-size: 32px;
            font-weight: 600;
        }

        header p {
            margin-top: 12px;
            font-size: 16px;
            color: #555;
        }

        /* Кнопка */
        .btn {
            display: inline-block;
            margin-top: 24px;
            padding: 12px 24px;
            border: 1px solid #111;
            background: transparent;
            color: #111;
            text-decoration: none;
            border-radius: 6px;
            transition: 0.2s;
        }

        .btn:hover {
            background: #111;
            color: #fff;
        }

        /* Секции */
        section {
            margin-top: 60px;
        }

        section h2 {
            font-size: 22px;
            margin-bottom: 16px;
        }

        section p {
            color: #444;
            font-size: 15px;
        }

        /* Услуги */
        .services {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
            margin-top: 20px;
        }

        .service {
            padding: 20px;
            border: 1px solid #eee;
            border-radius: 8px;
        }

        .service h3 {
            font-size: 16px;
            margin-bottom: 8px;
        }

        .service p {
            font-size: 14px;
            color: #555;
        }

        /* Контакты */
        .contacts a {
            display: block;
            margin-top: 8px;
            color: #111;
            text-decoration: none;
            font-size: 15px;
        }

        /* Футер */
        footer {
            margin-top: 80px;
            padding: 24px 0;
            text-align: center;
            font-size: 13px;
            color: #777;
            border-top: 1px solid #eee;
        }

        /* Адаптация под планшеты и ПК */
        @media (min-width: 768px) {
            header h1 {
                font-size: 40px;
            }

            .services {
                grid-template-columns: repeat(3, 1fr);
            }
        }
    </style>
</head>
<body>

<div class="container">

    <header>
        <h1>Business</h1>
        <p>Простые решения для роста вашего бизнеса</p>
        <a href="#contacts" class="btn">Связаться</a>
    </header>

    <section>
        <h2>О нас</h2>
        <p>
            Мы помогаем бизнесу становиться эффективнее:
            стратегия, цифровые решения и сопровождение.
            Минимум слов — максимум результата.
        </p>
    </section>

    <section>
        <h2>Услуги</h2>
        <div class="services">
            <div class="service">
                <h3>Консалтинг</h3>
                <p>Анализ и развитие бизнес-процессов.</p>
            </div>
            <div class="service">
                <h3>Маркетинг</h3>
                <p>Привлечение клиентов и рост продаж.</p>
            </div>
            <div class="service">
                <h3>IT</h3>
                <p>Сайты и автоматизация для бизнеса.</p>
            </div>
        </div>
    </section>

    <section id="contacts" class="contacts">
        <h2>Контакты</h2>
        <a href="tel:+77000000000">+7 700 000 00 00</a>
        <a href="mailto:info@business.kz">info@business.kz</a>
    </section>

    <footer>
        © 2026 Business
    </footer>

</div>

</body>
</html>
