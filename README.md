
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Тренировка на турнике</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            padding: 20px;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            margin: auto;
        }
        h1 {
            color: #333;
        }
        video {
            width: 100%;
            border-radius: 10px;
        }
        .muscles {
            margin-top: 20px;
        }
        .muscles span {
            display: inline-block;
            background: #ff9800;
            color: white;
            padding: 5px 10px;
            margin: 5px;
            border-radius: 5px;
        }
        .rating {
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Тренировка на турнике</h1>
        <p><strong>Цель:</strong> 50 подтягиваний</p>

        <h2>Техника выполнения</h2>
        <video controls>
            <source src="pullup.mp4" type="video/mp4">
            Ваш браузер не поддерживает видео.
        </video>
        <p>Сделай полный вис, затем подтянись, пока подбородок не окажется над перекладиной.</p>

        <h2>Какие мышцы работают?</h2>
        <div class="muscles">
            <span>Широчайшие мышцы спины</span>
            <span>Бицепс</span>
            <span>Предплечья</span>
            <span>Трапеции</span>
            <span>Пресс</span>
        </div>

        <h2>Оцените тренировку</h2>
        <div class="rating">
            <button onclick="alert('Спасибо за отзыв!')">👍 Класс!</button>
            <button onclick="alert('Спасибо за отзыв!')">👎 Не очень</button>
        </div>
    </div>

</body>
</html>
