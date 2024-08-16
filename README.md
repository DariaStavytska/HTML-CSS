<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Бандерогусь</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="./CSS/reset.css">
    <link rel="stylesheet" href="./CSS/styles.css">

    <link rel="preload" href="./img/gus-anim.gif" as="image">
</head>
<body>
    <section class="main-page">
        <div class="wrapper">
            <header>
                <img src="./img/logo.svg" alt="Логотип">
                <p class="log-text">
                    Школа підготовки<br> IT-спеціалістів
                </p>
            </header>

                <div class="main-page-row">
                    <div class="banderogus-container">

                        <h3 class="banderogus-greeting">Доброго вечора, ми з України</h3>
                        <h2 class="banderogus-start-text">На старт. Увага. Полетіли!</h2>
                        <h1 class="banderogus-title">Бандерогусь</h1>
                        <p class="banderogus-descr">
                        Спеціальний бойовий гусак із біолабораторій України. Пишаюся своїми подвигами, бороню Батьківщину та підтримую позитивний дух народу. Слава Україні!
                        </p> 
                        <button class="banderogus-launch" id="open-form-modal-btn">Запустити гуся</button>
                    </div>
                    <img src="./img/gus.svg" alt="banderogus" class="banderogus-image">
             </div>
        </div>
    </section>


     <section class="gus-facts">
        <img src="./img/trezub.svg" alt="ukr-logo" class="ukr-logo">

        <h3 class="gus-title"> Цікаві факти про бандерогусей</h3>
        <p class="gus-descr">
            Зазвичай бандерогуси — виключно мирні птахи. Але у разі небезпеки можуть атакувати ворога системою надпотужного озброєння. Також нищать психологічно, активуючи високочастотне шипіння та розмахування крилами
        </p>
        
        <div class="gus-facts-container">
       <div class="gus-fact-item">
           <img src="./img/gus1.svg" alt="gus 1" class="gus-fact-img">
           <h4 class="gus-fact-title">Система навігації</h4>
           <p class="gus-fact-descr">Супутниковий GPS та ехолокатори розпізнають ворожу техніку навіть на етапі збірки</p>
       </div>
       <div class="gus-fact-item">
           <img src="./img/gus2.svg" alt="gus 2" class="gus-fact-img">
           <h4 class="gus-fact-title">Очі-тепловізори</h4>
           <p class="gus-fact-descr">Допомагають виявити характер сигнатури об’єктів та значно підвищують точність удару</p>
       </div>
       <div class="gus-fact-item">
           <img src="./img/gus3.svg" alt="gus 3" class="gus-fact-img">
           <h4 class="gus-fact-title">Байракрила</h4>
           <p class="gus-fact-descr">Можуть нести 2-4 керовані ракети, що вражають ціль на відстані «ніхріна собі» кілометрів</p>
       </div>

        </div>
            
     </section>


     <footer class="victory-footer">
         <div class="victory-bgd">
             <img src="./img/trezub.svg" alt="ukr logo" class="ukr-logo">
             <h4 class="victory-title">Перемога завжди за нами!</h4>
             <p class="victory-descr">Головна мета бандерогусей — служити гумору та доброті нашого народу. Ми забезпечимо вашу посмішку у часи, коли вона так необхідна</p>

         </div>
     </footer>

        <div class="modal-bgs" id="form-modal">

            <div class="modal-form-contaainer">

                <button class="close-btn">x</button>

                <form action="#" class="modal-form" data-netlify="true" id="form">
                
                    <img src="./img/trezub.svg" alt="ukr logo">

                    <h4 class="modal-form-title">Поділися, будь ласка, поштою</h4>
                    <p class="modal-form-descr">та запиши гуся до бандерозагону</p>


                    <div class="modal-form-field">
                        <label for="user-name" class="modal-field-name">Ім'я</label>
                        <input type="text" class="modal-field-input" id="user-name" name="Ім'я">
                    </div>

                    <div class="modal-form-field">
                        <label for="user-email" class="modal-field-name">Email</label>
                        <input type="email" class="modal-field-input" id="user-email" name="email">
                    </div>

                    <button class="modal-form-btn" id="launch-btn">Запустити гуся</button>


                </form>
         </div>

        </div>


        <div class="modal-bgs" id="success-modal">

            <div class="modal-form modal-form-contaainer">
                <button class="close-btn">x</button>

                <img src="./img/trezub.svg" alt="ukr logo">

                <h4 class="modal-form-title">Дякуємо, гусь успішно запущений</h4>
                <p class="modal-form-descr">Слава Україні! Героям Слава!</p>

            </div>

        </div>
        <script src="./scripts/form.js"></script>
</body>
</html>
