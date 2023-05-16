# My-Sites
Public work of my projects
<!-- Скелет сайта -->
<!DOCTYPE html>
<html lang="en">

<head>
    <!-- Кодировка сайта -->
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Подключение каскадной таблицы стиля (CSS) -->
    <link href="../Assects/Style/DaZdrav2.css" rel="stylesheet" type="text/css">
    <link href="../Assects/Group 2.png" rel="shortcut icon" type="image/png">
    <!-- Подключение стиля шрифта -->
    <link href="https://fonts.googleapis.com/css2?family=Brygada+1918&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Golos+Text&display=swap" rel="stylesheet">
    <title>Интернет-аптека DaZdrav в Москве</title>
</head>

<body>
    
    <!-- Навигация по сайту -->
    <div class= "wrapper">
        <header>
            <nav class = "header">
            <img class = "logo" src="../Assects/Group 4.png">
                <h3>
                    <button onclick="window.location.href = 'DaZdrav.html';">
                        О нас
                    </button>
                </h3>
                <h1>
                    Главная
                </h1>
                <h3><button onclick="window.location.href = 'DaZdrav3.html';">
                    Отзывы
                </button>
                </h3>
                <a href = "DaZdrav3.html"><img class = 'burger' src="../Assects/Frame 8.png"></a>
            </nav>
        </header>

        <!-- Основная информация на сайте -->
        <div class="content">
            <h4>У нас на сайте вы найдете самые выгодные предложения на рынке.</h4>
            <form>  
                <p>Выберите дату:
                    <input type='date' name='calendar' value="2023-03-31" min="2023-04-01" max="2023-04-31" >
                </p>
            </form>
            <div class="container">
                <div class="item"><a href="../src/ROCS.html"><img src="../Assects/ROCS.png" class="img1"></a><figcaption>Зубная паста ROCS</figcaption></div>
                <div class="item"><a href="../src/Korega.html"><img src="../Assects/Korega.png" class="img1"></a><figcaption>Крем Корега</figcaption></div>
                <div class="item"><a href="../src/Farbentum.html"><img src="../Assects/Farbentum.png" class="img1"></a><figcaption>Спрей Фарбентум</figcaption></div>
                <div class="item"><a href="../src/Ibuprophen.html"><img src="../Assects/Ibuprophen.jpeg" class="img1"></a><figcaption>Обезболивающее Ибупрофен</figcaption></div>
                <div class="item"><a href="../src/Acc.html"><img src="../Assects/Acc.jfif" class="img1"></a><figcaption>Таблетки от кашля АЦЦ</figcaption></div>
                <div class="item"><a href="../src/Koldact.html"><img src="../Assects/Koldact.jpg" class="img1"></a><figcaption>Таблетки от простуды Колдакт</figcaption></div>
                <div class="item"><a href="../src/Suprastin.html"><img src="../Assects/Suprastin.jpg" class="img1"></a><figcaption>Детские витамины Супрастин Кидс</figcaption></div>
                <div class="item"><a href="../src/Fastum.html"><img src="../Assects/Fastum2.jpg" class="img1"></a><figcaption>Мазь разогревающаяя Фастум Гель</figcaption></div>
            </div>
        </div>

        <!-- "подвал" сайта -->
        <footer>
            <h5>All rights reserved DaZdrav© 2023</h5>
        </footer>
    </div>

</body>
</html>
