# Кейсы к хакатону
Кейсы и ТЗ к хакатону. Расположены в порядке возрастания сложности: от простых до самых хардовых

## Contents

* [Memory Game](#memory-game-table-of-contents)
* [Shoot Children Scares](#shoot-children-scares-table-of-contents)

## Memory Game ([Table of Contents](#contents)) 

**Сложность:** 💚 базовая

**Концепт:** игра с карточками, которые открываются попарно, и задача - открыть все карточки за наименьшее количество ходов. В качестве иллюстраций можем использовать иконки на тему детства/родительства/приемных семей с [flaticon](https://www.flaticon.com/)

**Пример:** 

![Sweet Memory Game - HTML5, JS and SCSS](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/b1b7f73f-c932-43b6-99a8-891cf1e138ad)

**Базовый минимум:**

* вывод поля с рандомно расположенными карточками (каждый раунд - новая позиция карточек);
* возможность открывать карточки;
* закрытие непарных карточек, парные - остаются открытыми;
* подсчет количества ходов;
* возможность начать игру заново;
* экран поздравления с окончанием игры;

**Возможности для расширения:**

* сохранение истории ходов (вплоть до возможности визуализировать ход партии);
* мультиплеер;
* лидерборд (топ игроков и лучших партий);
* статистика в любых видах (графики, пай-чарты итд);
* аккаунты и авторизация;
* игра по таймеру (опционально - с ограничением времени на ход/партию, опционально - с уровнями сложности с установкой таймеров в зависимости от уровня);
* красивый дизайн, адаптив, анимации;
* возможность красиво пошарить свой результат или профиль в соцсетях;

## Shoot Children Scares ([Table of Contents](#contents)) 

**Сложность:** 💚 базовая

**Концепт:** point-and-click-игрушка, где надо "отстреливать" страхи приемных детей. Список страхов - [тут](https://docs.google.com/document/d/16nTLrzaVVOPffb91CrFZO0fv1KRhJQ1_hNFxRFyPYvQ), в разделе "Типичные страхи приемных детей". Можно использовать иконки с [flaticon](https://www.flaticon.com/), например, с хэллоуинской тематикой. По иконке должно быть понятно, какой именно это страх.

**Пример:**

![Pure CSS ghost bustin' game w_ CSS variables 👻🕹#CodePenChallenge](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/37219648-3967-4637-9152-60c5e9e0b12c)

**Базовый минимум:**

* вывод поля с правилами игры и приглашением стартовать
* вывод поля со страхами, которые появляются и прячутся;
* возможность "отстреливать" страхи, при попадании они исчезают с анимацией, которая маркирует попадание;
* возможность начать игру заново;
* экран поздравления с окончанием игры + количество очков;

**Возможности для расширения:**

* разные уровни сложности и разное время для партий;
* возможность бесконечной партии;
* разная "сложность" страхов в рамках партии + разное количество очков сообразно сложности каждого (например, есть отдельный страх, в который особенно сложно попасть);
* дополнительный модус: игра не на время, а на количество промахов (например, заканчиваем, если игрок промахнулся трижды);
* адаптив и возможность играть с планшета/телефона;
* красивые анимации (включая svg-анимции иконок);
* лидерборд (топ игроков и лучших партий);
* статистика в любых видах (графики, пай-чарты итд);
* аккаунты и авторизация;
* возможность красиво пошарить свой результат или профиль в соцсетях;
