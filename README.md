# Кейсы к хакатону
Кейсы и ТЗ к хакатону. Расположены в порядке возрастания сложности: от простых до самых хардовых

## Contents

* [Memory Game](#memory-game-table-of-contents)
* [Shoot Children Scares](#shoot-children-scares-table-of-contents)
* [15th Slider Game](#15th-slider-game-table-of-contents)
* [Charity Day Banners Builder](#charity-day-banners-builder-table-of-contents)
* [Maze Game](#maze-game-table-of-contents)
* [Home Builder](#home-builder-table-of-contents)

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

## 15th Slider Game ([Table of Contents](#contents)) 

**Сложность:** 💚 базовая

**Концепт:** игра-пятнашки "собери иллюстрацию". Берем иллюстрацию, режем на 15 кусочков - и дальше как в обычных, традиционных пятнашках. Иллюстрации используем на тему хакатона, берем их, например, с с [Freepik](https://www.freepik.com/) или [unsplash](https://unsplash.com/).

**Пример:**

Иллюстрация всратая, но лучший пример из того, что нашла (еще в иллюстрации - 3 на 3, а у нас будет базовая 4 на 4):

<img width="517" alt="image" src="https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/ce988791-6cfe-4f9d-9a03-ba4103890036">

![ezgif-2-78512cfaa5](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/473c5108-905d-4266-bc45-36c37c028993)

**Базовый минимум:**

* вывод поля с пятнашками и правилами игры;
* поле стандартное, 4*4, в нем иллюстрация, разделенная на 15 частей и пустым окошком (на каждую новую партию должно быть новое распределение кусочков);
* удобно подсвеченная навигация, которая показывает, какой из элементов будет перемещен;
* возможность начать игру заново;
* экран поздравления с окончанием игры;

**Возможности для расширения:**

* управление с клавиатуры;
* возможность других размеров поля (3 на 3, 6 на 6, свои варианты);
* возможность выбора из нескольких тематических иллюстраций;
* сохранение истории ходов (вплоть до возможности визуализировать ход партии);
* возможность отменить ход (на сколько угодно назад);
* мультиплеер;
* лидерборд (топ игроков и лучших партий);
* статистика в любых видах (графики, пай-чарты итд);
* аккаунты и авторизация;
* игра по таймеру (опционально - с ограничением времени на ход/партию, опционально - с уровнями сложности с установкой таймеров в зависимости от уровня);
* красивый дизайн, адаптив, анимации;
* возможность красиво пошарить свой результат или профиль в соцсетях;

## Shoot Children' Scares ([Table of Contents](#contents)) 

**Сложность:** 🟧 средняя

**Концепт:** point-and-click-игрушка, где надо "отстреливать" страхи приемных детей. Список страхов - [тут](https://docs.google.com/document/d/16nTLrzaVVOPffb91CrFZO0fv1KRhJQ1_hNFxRFyPYvQ), в разделе "Типичные страхи приемных детей". Можно использовать иконки с [flaticon](https://www.flaticon.com/), например, с хэллоуинской тематикой. По иконке должно быть понятно, какой именно это страх.

❗️**не используйте в своем дизайне концепт из примера с могильными плитами, и вообще ничего, связанного со смертью (привидений тех же), потому что _мы делаем игры для НКО, связанного с детьми-сиротами_. Пример функциональности, выбран, как самый наглядный, не копируйте его.**

**Пример:**

![Pure CSS ghost bustin' game w_ CSS variables 👻🕹#CodePenChallenge](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/37219648-3967-4637-9152-60c5e9e0b12c)

**Базовый минимум:**

* вывод поля с правилами игры и приглашением стартовать
* вывод поля со страхами, которые появляются и прячутся;
* возможность "отстреливать" страхи, при попадании они исчезают с анимацией, которая маркирует попадание;
* возможность начать игру заново;
* экран поздравления с окончанием игры + количество очков;
* "легенда" с описанием: какая иконка соответствует какому страху;

**Возможности для расширения:**

* разные уровни сложности и разное время для партий;
* возможность бесконечной партии;
* разная "сложность" страхов в рамках партии + разное количество очков сообразно сложности каждого (например, есть отдельный страх, в который особенно сложно попасть);
* дополнительный модус: игра не на время, а на количество промахов (например, заканчиваем, если игрок промахнулся трижды);
* адаптив и возможность играть с планшета/телефона;
* красивые анимации (включая svg-анимации иконок);
* лидерборд (топ игроков и лучших партий);
* статистика в любых видах (графики, пай-чарты итд);
* аккаунты и авторизация;
* возможность красиво пошарить свой результат или профиль в соцсетях;

## Charity Day Banners Builder ([Table of Contents](#contents)) 

**Сложность:** 🟧 средняя

**Концепт:** возможность генерировать баннеры к "Дню сироты". Максимально упрощенный вариант [Canva](https://www.canva.com/): возможность размещать на холсте текст, графику с помощью drag-n-drop и экспортировать в виде картинки (JPG/PNG) и/или PDF. Для экспорта можно использовать как сторонние либы типа [html-to-image](https://www.npmjs.com/package/html-to-image), так и сделать свое решение.

**Пример:**

Холст и смена его цвета:

![Дизайн без названия — Видео (1)](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/22050c8f-cec1-4344-8350-a2704928db73)

Создание текстового блока и его кастомизация:

![Дизайн без названия — Видео (2)](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/159cfeb3-228a-4f47-94ea-bb7bce7c2a78)

Использование графики:

![ezgif-1-6b94667dbe](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/0e140d4a-406e-49cf-82f1-7ac4da350b70)

**Базовый минимум:**

❗️**запрещено пользоваться готовыми решениями для задач базового минимума;**

* холст фиксированного размера, которому можно изменять цвет (либо из заданной палитры, либо устанавливать любой);
* возможность создавать текстовые блоки, вводить пользовательский текст, кастомизировать его (цвет, жирность, начертание, размер, выравнивание, подчеркнутость) и размещать на холсте;
* возможность добавлять ссылки к тексту;
* возможность использовать заранее подготовленную вами графику по теме хакатона (например, иконки, которые вы заранее подготовите с [flaticon](https://www.flaticon.com/) и картинки с [Freepik](https://www.freepik.com/) или [unsplash](https://unsplash.com/)), размещать ее на холсте и ресайзить;
* экспорт получившегося результата в виде картинки (JPG/PNG) и/или PDF;
* возможность очистить холст;
* удобный, аккуратный, понятный дизайн;

**Возможности для расширения:**

* аккаунты и авторизация;
* сохранение проектов:
  * локальное кэширование: когда юзер открывает страницу, он видит текущий статус проекта, а не новый проект;
  * сохранение проекта или проектов в ЛК аккаунта и возможность выбирать, какой проект редактировать;
* возможность отменять последние N действий в проекте, откатываться назад/вперед;
* набор геометрических фигур для использования: кругов, треугольников, квадратов, прямоугольников, которым можно менять цвет, задавать прозрачность итд;
* адаптив и возможность создавать баннеры с планшета/телефона;
* интеграция Unsplash API/Flaticon API/еще каким-либо, чтобы юзер мог прямо из проекта искать картинки и сразу их всталять;
* интеграция Google Fonts API, чтобы юзер мог выбирать тип шрифта;
* возможность юзеру загружать свою графику для баннера (если аккаунт - опция сохранения графики в аккаунте для дальнейшего использования, но с ограничением размера хранилища и, опционально, возможностью удалять загруженное без удаления этой графики из проекта);
* возможность обрезки графики (чтобы можно было отрезать кусок);
* интеграция/реализация простой рисовалки с последующим размещением графики на баннере:
  * возможность рисовать (в одном цвете или нескольких);
  * возможность очистить;
  * вставка рисунка в баннер (с перемещением, масштабированием);
  * интеграция рисовалки в UI/UX приложения;
* возможность красиво пошарить свой результат в соцсетях;

## Maze Game ([Table of Contents](#contents)) 

**Сложность:** 🔴 высокая

**Концепт:** гениерируем игру-лабиринт, в которой приводим приемного родителя/родителей к ребенку. Можно использовать [алгоритм генерации лабиринтов](https://www.dstromberg.com/2013/07/tutorial-random-maze-generation-algorithm-in-javascript/) и иконки с [flaticon](https://www.flaticon.com/).

**Пример:**

![ezgif-3-f8f861385f](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/693df18b-800b-41fe-a5b2-51250596a256)

**Базовый минимум:**

* сгенерированный с помощью любого алгоритма лабиринт;
* инструкция к игре (как в нее играть);
* управление "родителем" с клавиатуры стрелочками;
* реализован алгоритм самой игры: "родитель" не может проходить сквозь стены лабиринта;
* возможность сбросить игру к начальному значению;
* экран поздравления с окончанием игры;

**Возможности для расширения:**

* генерация рандомных лабиринтов на каждую игру;
* возможность выбрать уровень сложности лабиринта (например, с варьирующимся размером);
* игра на время;
* препятствия на пути в виде страхов ребенка. Список страхов - [тут](https://docs.google.com/document/d/16nTLrzaVVOPffb91CrFZO0fv1KRhJQ1_hNFxRFyPYvQ), в разделе "Типичные страхи приемных детей". Попадение в "страх" откатывает игру к началу/резко уменьшает таймер при игре на время/как-то еще дамажит прогресс. Можно использовать иконки с [flaticon](https://www.flaticon.com/), например, с хэллоуинской тематикой. По иконке должно быть понятно, какой именно это страх;
* красивый дизайн и анимации;
* лидерборд (топ игроков и лучших партий);
* статистика в любых видах (графики, пай-чарты итд);
* аккаунты и авторизация;
* возможность играть с мобильного устройства/планшета;
* возможность красиво пошарить свой результат или профиль в соцсетях;

## Home Builder ([Table of Contents](#contents)) 

**Сложность:** 🔴 высокая

**Концепт:** пожалуй, самое творческое задание. Задача - собрать домик для ребенка. Это может быть 3D-like интерьер, это может быть плоский план

❗**запрещено использовать готовые картинки и делать "коллаж" из иконок (исключение - 3d-модельки). Делаем иллюстрации на чистом CSS/JS руками с высокой детализацией.**

**Пример:**

3D-сцены:

<img width="765" alt="image" src="https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/325a32f3-0880-4f45-910a-271237653c6f">
<img width="765" alt="image" src="https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/5231efac-30e5-44b0-9d56-4e5a03b20df5">


Плоская сцена:

<img width="765" alt="image" src="https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/2e5fdf5e-2b37-48b1-b130-4c360377fb21">
<img width="765" alt="image" src="https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/3c6be23f-ed98-415f-85ab-f08d8265bc55">

**Базовый минимум:**

* одна сгенерированная сцена, содержащая детскую комнату (3d или плоскую);
* все предметы в этой комнате должны быть с высокой детализацией
* возможность кастомизировать все предметы мебели (например, по клику выбирать цвет из палитры или по клику на предмет, например, картину, выбрать одну из нескольких опций);

**Возможности для расширения:**

* больше, чем одна комната, на сцене;
* адаптив и возможность играть с телефона/планшета;
* интерактив взаимодействия с предметами (например, открывающиеся окна/двери/шкафчики или смена освещения от включения/выключения света);
* внедрение игровых механик (например, наличие бюджета и сбор домика по нему);
* возможность перетаскивать предметы мебели или декора (вплоть до пустой комнаты, в которой можно самостоятельно размешать элементы из подготовленного вами набора);
* внедрение фоновой музыки (бесплатной и в тему) и выбора озвучки;
* аккаунты и авторизация;
* сохранение проектов:
  * локальное кэширование: когда юзер открывает страницу, он видит текущий статус сцены, а не новый проект;
  * сохранение проекта или проектов в ЛК аккаунта и возможность выбирать, какой проект редактировать;
* возможность красиво пошарить свой результат в соцсетях;
