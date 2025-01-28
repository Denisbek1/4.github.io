<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Дорожные знаки</title>
    <link rel="stylesheet" href="https://code.jquery.com/ui/1.14.1/themes/base/jquery-ui.css">
    <script src="https://code.jquery.com/jquery-3.7.1.js"></script>
    <script src="https://code.jquery.com/ui/1.14.1/jquery-ui.js"></script>
    <style>
        .tooltip {
            position: relative;
        }
        .tooltip .ui-tooltip {
            position: absolute;
            background-color: #fff;
            border: 1px solid #ddd;
            padding: 5px;
            z-index: 1;
        }
        img {
            margin: 10px;
            width: 100px; /* Настройте размер изображений по вашему усмотрению */
        }
    </style>
    <script>
        $(function () {
            $(document).tooltip({
                items: "img",
                content: function () {
                    var $element = $(this);
                    if ($element.is("img")) {
                        return $element.data('hint');
                    }
                }
            });
        });
    </script>
</head>
<body>
    <h1>Дорожные знаки</h1>
    <p>
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\sign1.png" class="tooltip" data-hint="Знак 1: Выезд на набережную">
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\sign2.png" class="tooltip" data-hint="Знак 2: скользкая дорога">
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\sign3.png" class="tooltip" data-hint="Знак 3: двустороннее движение">
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\sign4.png" class="tooltip" data-hint="Знак 4: дикие животные">
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\sign5.png" class="tooltip" data-hint="Знак 5: боковой ветер">
    </p>
    <p>

        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\Снимок экрана 2025-01-28 151031.png" class="tooltip" data-hint="Знак 1: главная дорога">
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\Снимок экрана 2025-01-28 151036.png" class="tooltip" data-hint="Знак 2: пересение с второтепенной дорогой">
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\Снимок экрана 2025-01-28 151040.png" class="tooltip" data-hint="Знак 3: движение без остановки запрещено">
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\Снимок экрана 2025-01-28 151044.png" class="tooltip" data-hint="Знак 4: преимущество встречного движения">
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\Снимок экрана 2025-01-28 151047.png" class="tooltip" data-hint="Знак 5: преимущество перед встречным движением">
    </p>
    <p>
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\Снимок экрана 2025-01-28 151052.png" class="tooltip" data-hint="Знак 1: движение грузовых запрещено" >
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\Снимок экрана 2025-01-28 151056.png" class="tooltip" data-hint="Знак 2: движение с прицепом запрещено" >
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\Снимок экрана 2025-01-28 151058.png" class="tooltip" data-hint="Знак 3: движение пешеходов запрещено">
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\Снимок экрана 2025-01-28 151102.png" class="tooltip" data-hint="Знак 4: ограничение ширины">
        <img src="c:\Users\Admin\Documents\USB\Технологии программирования и создание WEB приложений\Знакомство с базовыми тегами HTML\img\Снимок экрана 2025-01-28 151105.png" class="tooltip" data-hint="Знак 5: куртой поворот запрещено">
    </p>
    <!-- Добавьте другие параграфы с изображениями, если необходимо -->
</body>
</html>
