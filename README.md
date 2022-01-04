# Blackjack

Задача
Цель этого домашнего задания
Научиться писать код С++, соответствующий Unreal Engine Coding Standard, что, в свою очередь, означает полностью правильный нейминг всех символов, корректное форматирование и комментирование кода, использование только совместимого с Unreal Engine синтаксиса C++.

Реализация простой карточной игры в полном соответствии с Coding Standart.

Что нужно сделать:
- Реализуйте на C++ класс ADeck, реализующий стандартную колоду из 52 игральных карт ACard. Класс должен иметь возможность перетасовать колоду, вытащить карту из колоды сверху.
- Реализуйте на C++ класс ACard, реализующий стандартную игральную карту масти ESuit и достоинства ERank.
- Реализуйте на C++ перечисления ERank и ESuit, реализующие перечисления мастей и достоинств стандартной французской игральной колоды.

Реализуйте в проекте игровую логику blackjack со следующим сокращенным набором правил:
- Используется одна колода.
- Первая карта сдаётся крупье, затем набирает игрок.
- Если игрок набрал 21, сразу засчитывается победа, если перебрал — поражение.
- Крупье набирает, пока сумма меньше или равна 16.
- После окончания набора крупье игроку засчитывается победа, если его сумма больше, чем сумма крупье, или если крупье перебрал.
- В случае равных сумм засчитывается ничья.
- После окончания раунда колода перемешивается.


Советы и рекомендации
- Описание стандарта с примерами доступно по ссылке: https://docs.unrealengine.com/4.26/en-US/ProductionPipelines/DevelopmentSetup/CodingStandard/.
- Студенты, использующие Rider в качестве основной IDE, могут полагаться на встроенный линтер.
- Описание правил игры: https://ru.wikipedia.org/wiki/Блэкджек.