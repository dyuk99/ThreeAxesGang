# Three axes gang - lighting system 
Рік випуску: 2016<br/>
Версія: 1.0.1<br/>
Розробник: ThreeAxesGang<br/>
Платформа: Windows/Android<br/>
<br/>

<h4>Складання схеми ДУСО</h4>
Схема без BT модуля та батареї докладно описана тут: <a href="http://imgur.com/Tmnh8zQ"> </a> <br/>
Для підключення BT модуля необхідно: <br />
1. Підключити усі проводи типу "мама-тато" однією частиною "мами" до BT модуля.<br />
2. Провід RX підключити до pin1 плати arduino <br />
3. Провід TX підключити до pin0 плати arduino <br />
4. Провід GND підключити до pin GND плати arduino <br />
5. Провід +5V підключити до pin 3.3V плати arduino <br />
Можна використовувати блок батарей - тоді їх можна підключити у окремий вихід для живлення. <br />

<br/>

<h4>Завантаження коду на плату Arduino Uno</h4>
Для завантаження коду на плату необхідно завантажити Arduino IDE за <a href="www.arduino.cc/en/Main/Software">посиланням</a> <br />
Після встановлення програми, підключіть плату до комп'ютера за допомогою USB кабеля. <br />
Натисність кнопку [Upload] або (ctrl + U) - цим програма завантажиться до плати. <br />

<br/>

<h4>Встановлення додатків</h4>
<b>Desktop додаток</b> <br/>
Завантажте Qt creator за <a href="https://www.qt.io/download-open-source/">посиланням</a> <br/> 
Після встановлення Qt creator відкрийте папку "Qt" у корені. Запустіть .pro файл. Натисніть кнопку "run" (ctrl + r) <br/>
Desktop додаток готовий до використання! <br/>
<b>Android додаток</b> <br/>
Завантажте .apk файл із папки "Android" у корені. Встановіть цей додаток на свій Android-смартфон. <br/>
Android додаток готовий до використання! <br/>

<br/>

<h4>Використання програми</h4>
<b>Desktop додаток</b> <br />
Після відкриття панелі керування ДУСО, натисніть кнопку <b>"ON"</b> зліва знизу. <br />
Дочекайтесь виводу надпису Port opened to [номер порту]. <br />
Додаток готовий до використання - усі кнопки тепер змінюватимуть стан ДУСО! <br />
<b>Android додаток</b> <br />
Після встановлення .apk додатку та його відкриття натисність на кнопку [Select BT module]. <br/>
Виберіть із запропонованого списку елемент із надписом [HC-06]. <br/>
При успішності процесу з'єднання ДУСО із BT модулем, виведеться надпис [Connected]. <br/>
Тепер можна змінювати стан ДУСО за допомогою Android додатку. <br />

<br/>

При виникненні непередбачуваних труднощів, будь ласка, напишіть scrum-майстеру команди TAG: <br/>
<b>vk</b>: vk.com/diferenzial13 <br/>
<b>mail</b>: maxgonchar9@gmail.com <br/>
