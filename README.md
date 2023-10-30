<div id="header" align="center">
  <img src="https://media.giphy.com/media/mTPjPA6SSXgTsnZ1Dh/giphy.gif" width="200" height="150" border=""/>
</div>
<div id="badges" align="center">
  <a href="https://discordapp.com/users/grifaka">
    <img src="https://img.shields.io/badge/Discord-blue?style=for-the-badge&logo=discord&logoColor=white" alt="Discord Badge"/>
  </a>
</div>
 
 Bicycle!World
 
 - Это мой первый проект, написанный на препроцессоре «pug» и «sass» с использованием сторонних библиотек, а также небольшим javascript кодом для оживления страниц.
 - Сайт сверстан по моему .psd макету разработанному в программе «Adobe Photoshop»
 - Страница представляет из себя одностраничник рассказывающий о велосипедных брендах, небольших цитатах о пользе велоспорта, а также добавленным видеороликом рассказывающим о том как 
   правильно выбирать велосипед.

- Для запуска проекта следует использовать команды:
  1. brew install node (установка node.js для mac)
  2. npm i (установка всех пакетов из зависимостей «package.json»)
    - npm install pug (установка препроцессора pug)
  3. pug -w pug/pages -o ./html -P (запуск рендра файлов pug в папку html)
    - npm install sass (установка препроцессора sass)
  4. sass -w sass/style.sass ./css/style.css (запуст рендра файлов sass в папку css)
