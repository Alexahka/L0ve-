
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Проверка подарков</title>
    <style>
        body {
            background-color: black;
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            color: white;
            font-family: Arial, sans-serif;
        }

        /* Бегущая строка */
        .marquee {
            width: 100%;
            white-space: nowrap;
            overflow: hidden;
            position: absolute;
            top: 20px;
            font-size: 20px;
            text-align: center;
        }

        .marquee span {
            display: inline-block;
            animation: move 10s linear infinite;
        }

        @keyframes move {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-100%);
            }
        }

        /* Стиль кнопки */
        .button {
            background-color: red;
            color: white;
            border: 2px solid yellow;
            padding: 15px 30px;
            font-size: 20px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .button:hover {
            backgro
