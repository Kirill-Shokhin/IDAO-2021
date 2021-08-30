# IDAO-2021
C 1 по 31 марта 2021 года проводилась очередная [международная олимпиада по анализу данных](https://idao.world) от ВШЭ и Яндекса.

Есть изображения двух типов частиц __ER__ и __NR__, и шести значений энергии (__1__, __3__, __6__, __10__, __20__, __30__ кэВ).  
Примеры __ER__, по возрастанию энергии:

<p align="center">
  <img src="https://github.com/Kirill-Shokhin/IDAO-2021/blob/main/images/ER.png">
</p>
<!-- ![ER](https://github.com/Kirill-Shokhin/IDAO-2021/blob/main/images/ER.png) -->

Примеры __NR__, по возрастанию энергии:

<p align="center">
  <img src="https://github.com/Kirill-Shokhin/IDAO-2021/blob/main/images/NR.png">
</p>
<!-- ![NR](https://github.com/Kirill-Shokhin/IDAO-2021/blob/main/images/NR.png) -->

Задание состоит одновременно в __классификации__ типа и в __регрессии__ энергии частиц.  
Однако в тренировочном (__\*__) и тестовом (__-__) датасетах находятся разные классы, что доставляет не мало неприятностей.

<p align="center">
  <img src="https://github.com/Kirill-Shokhin/IDAO-2021/blob/main/images/Splitting.png">
</p>

__Обучающая выборка__ содержит 2200 примеров каждого обучающего класса. Известны энергии и типы частиц для обучающего набора данных.  
__Публичная тестовая выборка__ содержит 250 примеров каждого из обучающих классов. __Приватная тестовая выборка__ содержит 2500 примеров из каждого тестового класса.


## Решение
Сперва [подготовим данные][1] для удобного пользования, затем [обработаем][2] и проведем [тестовое обучение][3].  
__Полное обучение__ и __результаты__ в процессе оформления...

[1]: https://nbviewer.jupyter.org/github/Kirill-Shokhin/IDAO-2021/blob/main/Data%20preparation.ipynb
[2]: https://nbviewer.jupyter.org/github/Kirill-Shokhin/IDAO-2021/blob/main/Data%20processing.ipynb
[3]: https://nbviewer.jupyter.org/github/Kirill-Shokhin/IDAO-2021/blob/main/Trial%20training.ipynb
