<html>
    <head <meta name="viewport" content="width=device-width, initial-scale=1">>
        <title>Сайт Эдика</title>
    </head>
    
    
    <body class="back-row-toggle splat-toggle">
    <script type="text/javascript">var makeItRain = function() {
  //clear out everything
  $('.rain').empty();

  var increment = 0;
  var drops = "";
  var backDrops = "";

  while (increment < 100) {
    //couple random numbers to use for various randomizations
    //random number between 98 and 1
    var randoHundo = (Math.floor(Math.random() * (98 - 1 + 1) + 1));
    //random number between 5 and 2
    var randoFiver = (Math.floor(Math.random() * (5 - 2 + 1) + 2));
    //increment
    increment += randoFiver;
    //add in a new raindrop with various randomizations to certain CSS properties
    drops += '<div class="drop" style="left: ' + increment + '%; bottom: ' + (randoFiver + randoFiver - 1 + 100) + '%; animation-delay: 0.' + randoHundo + 's; animation-duration: 0.5' + randoHundo + 's;"><div class="stem" style="animation-delay: 0.' + randoHundo + 's; animation-duration: 0.5' + randoHundo + 's;"></div><div class="splat" style="animation-delay: 0.' + randoHundo + 's; animation-duration: 0.5' + randoHundo + 's;"></div></div>';
    backDrops += '<div class="drop" style="right: ' + increment + '%; bottom: ' + (randoFiver + randoFiver - 1 + 100) + '%; animation-delay: 0.' + randoHundo + 's; animation-duration: 0.5' + randoHundo + 's;"><div class="stem" style="animation-delay: 0.' + randoHundo + 's; animation-duration: 0.5' + randoHundo + 's;"></div><div class="splat" style="animation-delay: 0.' + randoHundo + 's; animation-duration: 0.5' + randoHundo + 's;"></div></div>';
  }

  $('.rain.front-row').append(drops);
  $('.rain.back-row').append(backDrops);
}

$('.splat-toggle.toggle').on('click', function() {
  $('body').toggleClass('splat-toggle');
  $('.splat-toggle.toggle').toggleClass('active');
  makeItRain();
});

$('.back-row-toggle.toggle').on('click', function() {
  $('body').toggleClass('back-row-toggle');
  $('.back-row-toggle.toggle').toggleClass('active');
  makeItRain();
});

$('.single-toggle.toggle').on('click', function() {
  $('body').toggleClass('single-toggle');
  $('.single-toggle.toggle').toggleClass('active');
  makeItRain();
});

makeItRain();</script>
  <div class="rain front-row"></div>
  <div class="rain back-row"></div>
  <div class="toggles">
    <div class="splat-toggle toggle active">SPLAT</div>
    <div class="back-row-toggle toggle active">BACK<br>ROW</div>
    <div class="single-toggle toggle">SINGLE</div>
  </div>
	 <link rel="stylesheet" type="text/css" href="EdikTV.github.io/Style.css">
        <!-- Шапка начало -->
        <div id="header" class="section">
            <img alt="" class="img-circle" src="https://pp.userapi.com/c845124/v845124064/180e84/YUOAHBu8Fgs.jpg">
            <p>Эдуард Пирогов</p>
        </div>
        <!-- Шапка конец -->
        
        <!-- Коротко о сайте -->
        <div class="section">
            <h1><span>Коротко о сайте</span></h1>
            <p>
                Привет, я <strong>Эдик</strong>. Это мой первый адекватный сайт. Тут я пытаюсь что-то нормальное сделать <i>, чтобы понять, что к чему тут </i> и у меня немного получается. Что-то скопипастил, что-то сам внедрил. <strong>В любом случае, это интересно.</strong> Пока другие тупо играют, я тупо делаю сайт. Впрочем, копипаст это тоже метод разработки.
            </p>
            <p class="quote">"А верну я всё в джейсончик..."</p>
        </div>
        <!-- Кончили с сайтом -->
        <!-- Моё расписание -->
        <div class="section">
            <h1><span align="center">Моё расписание</span></h1>
            <table>
                <tr>
                    <th>День</th>
                    <th>Понедельник</th>
                    <th>Вторник</th>
                    <th>Среда</th>
                    <th>Четверг</th>
                    <th>Пятница</th>
                </tr>
                <tr>
                    <td>8:30-10:00</td>
                    <td class="selected">Спать</td>
                    <td class="selected">Спать</td>
                    <td class="selected">Дискретка лекция</td>
                    <td class="selected">БЖД</td>
                    <td class="selected">Сдача лаб по ИиП</td>
                </tr>
                <tr>
                    <td>10:10-11:40</td>
                    <td class="selected">Ин.Яз</td>
                    <td class="selected">Спать</td>
                    <td class="selected">Ин.Яз</td>
                    <td class="selected">Правоведение</td>
                    <td class="selected">Окно/Web-дизайн</td>
                </tr>
                <tr>
                    <td>11:50-13:20</td>
                    <td class="selected">Вышмат лекция</td>
                    <td class="selected">Спать</td>
                    <td class="selected">Физра</td>
                    <td class="selected">Инфа лекция</td>
                    <td class="selected">Спать</td>
                </tr>
                <tr>
                    <td>14:00-15:30</td>
                    <td class="selected">Вышмат практика</td>
                    <td class="selected">Вышмат практика</td>
                    <td class="selected">Вышмат для слабых</td>
                    <td class="selected">Инфа практика</td>
                    <td class="selected">Философия практика</td>
                </tr>
                <tr>
                    <td>15:40-17:10</td>
                    <td class="selected">Спать</td>
                    <td class="selected">Дискреточка с куратором</td>
                    <td class="selected">Спать</td>
                    <td class="selected">Спать</td>
                    <td class="selected">Спать</td>
                </tr>
            </table>
        </div>
        <!-- Конец расписания -->
      
        
        <!-- Мои скилы -->
        <div class="section">
            <h1><span>Мои скилы</span></h1>
            <ul>
                <li>HTML <br />
                    <progress min="0" max="100" value="30"></progress>
	        </li>
		<li>С# <br />
                    <progress min="0" max="100" value="50"></progress>
                </li>
                <li>С++ <br />
                    <progress min="0" max="100" value="75"></progress>
                </li>
                <li>Си <br />
                    <progress min="0" max="100" value="60"></progress>
                </li>
            </ul>
        </div>
        <!-- Кончились скилы -->
       
        
         <!-- Блок видосов -->
        <div class="section">
            <h1><span>Медиа ресурсы</span></h1>
            <iframe height="500" width="500" src="https://coub.com/view/10rm7q" allowfullscreen frameborder="0"></iframe>
        </div>
        <!-- Блок видосов кончился -->
        
        
       
        <!-- Контакты -->
        <div class="section" id="contacts">
            <h1><span>Следуй за мной</span></h1>
            <div>
                <a href="https://www.sololearn.com/Profile/9440517/CPlusPlus" target="_blank">
                    <img alt="SoloLearn" src="https://www.sololearn.com/Uploads/icons/sololearn.png" />
                </a>
                <a href="https://vk.com/id167846834" target="_blank">
                    <img alt="VK" src="http://vk.com/images/vk32.png"/>
                </a>
                <a href="https://coub.com/8698497ae744373a1b0e13bcb836e267" target="_blank">
                    <img alt="Coub" src="https://coubsecure-s.akamaihd.net/get/b176/p/channel/cw_avatar/30e0a89d3f3/31a3fd5f24dff8ebe19b8/medium_1521806390_1521737087261.png" width="46" viewBox="0 0 46 46" />
                </a>
            </div>
        </div>
        <!-- Контакты -->
       
        <div class="copyright" align="center">
            &copy; 2019 Сайт Эдика. Все права защищены.
        </div>
        
    </body>
</html>
