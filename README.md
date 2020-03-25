# Путешествие по России


## Описание проекта и его функциональности
Проект представляет собой одностраничный сайт про локации России. Сайт адаптирован под самые популярные разрешения — 1440, 1280, 1024, 768, 375 и 320 пикселей. По ссылкам внутри страницы можно перейти на сторонние сайты и сервисы.


## Технологии

*	CSS-правила варьируются в зависимости от ширины устройства благодаря директиве @media;
*	Создана Nested файловая структура по БЭМ;
*	Для формирования сеток используется flex или grid-layout;
*	Ссылкам задано состояние при наведении на них указателя мыши (:hover);
*	Затемнение background реализовано с помощью псевдоэлемента (selector::before).


## Планы по доработке проекта

1.	Для повторяющихся CSS-свойств использовать отдельные блоки title, subtitle и др., чтобы данные сущности с большей вероятностью отображались одинаково.
2.	Для придания «резинового» эффекта текстовым элементам использовать функцию «са1с()» и относительные величины (что-то из этого: %,vh и vw, vmin и vmax).
3.	Для блока cover использовать background: contain, чтобы и на промежуточных точках было «как в макете». Только я не уверена, что это в принципе можно реализовать.
4.	Добиться большей отзывчивости в других блоках.
5.	Привести содержание файлов .css к единому стилю (и сделать одинаковые поля).

