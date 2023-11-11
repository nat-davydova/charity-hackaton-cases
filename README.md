# Кейсы к хакатону
Кейсы и ТЗ к хакатону. Расположены в порядке возрастания сложности: от простых до самых хардовых

## Contents

* [Memory Game](#memory-game-table-of-contents)
* [15th Slider Game](#15th-slider-game-table-of-contents)
* [Shoot Children Scares](#shoot-children-scares-table-of-contents)
* [Maze Game](#maze-game-table-of-contents)
* [Charity Day Banners Builder](#charity-day-banners-builder-table-of-contents)
* [Home Builder](#home-builder-table-of-contents)

## Memory Game ([Table of Contents](#contents)) 

**Сложность:** 💚 базовая

**Концепт:** игра с карточками, которые открываются попарно, и задача - открыть все карточки за наименьшее количество ходов. В качестве иллюстраций можем использовать иконки на тему детства/родительства/приемных семей с [flaticon](https://www.flaticon.com/)

**Пример:** 

![Sweet Memory Game - HTML5, JS and SCSS](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/12735f2d-4e77-4aa3-a733-1a97e12b01e7)

**Базовый минимум:**

* вывод поля с рандомно расположенными карточками (каждый раунд - новая позиция карточек);
* возможность открывать карточки;
* закрытие непарных карточек, парные - остаются открытыми;
* подсчет количества ходов;
* возможность начать игру заново;
* экран поздравления с окончанием игры;

**Возможности для расширения:**

* сохранение истории ходов (вплоть до возможности визуализировать ход партии);
* мультиплеер формата "горячий стул" (опционально - с ограничением времени на ход);
* игра по таймеру (опционально - с ограничением времени на ход/партию);
* уровни сложности (с установкой таймеров в зависимости от уровня сложности или/и с ограничением по ходам или/и с убыванием очков за ошибки);
* лидерборд (топ игроков и лучших партий);
* статистика в любых видах (графики, пай-чарты итд);
* аккаунты и авторизация;
* красивый дизайн, адаптив, анимации;
* возможность красиво пошарить свой результат или профиль в соцсетях;

## 15th Slider Game ([Table of Contents](#contents)) 

**Сложность:** 💚 базовая

**Концепт:** игра-пятнашки "собери иллюстрацию". Берем иллюстрацию, режем на 15 кусочков - и дальше как в обычных, традиционных пятнашках. Иллюстрации используем на тему хакатона, берем их, например, с с [Freepik](https://www.freepik.com/) или [unsplash](https://unsplash.com/).

**Пример:**

Иллюстрация всратая, но лучший пример из того, что нашла (еще в иллюстрации - 3 на 3, а у нас будет базовая 4 на 4):

<img width="609" alt="image" src="https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/eb3c5d60-ea87-4f27-b0ac-7e779fb74be0">

![ezgif-2-78512cfaa5](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/cb9b7b91-c181-499d-9445-b0b659937a64)

**Базовый минимум:**

* вывод поля с пятнашками и правилами игры;
* поле стандартное, 4*4, в нем иллюстрация, разделенная на 15 частей и пустым окошком (на каждую новую партию должно быть новое распределение кусочков);
* удобно подсвеченная навигация, которая показывает, какой из элементов будет перемещен;
* возможность начать игру заново;
* экран поздравления с окончанием игры;

**Возможности для расширения:**

* управление с клавиатуры;
* возможность других размеров поля (3 на 3, 6 на 6, свои варианты);
* возможность выбора из нескольких тематических иллюстраций и/или возможность загрузить свою;
* сохранение истории ходов (вплоть до возможности визуализировать ход партии);
* возможность отменить ход (на сколько угодно назад);
* мультиплеер;
* игра по таймеру (опционально - с ограничением времени на ход/партию, опционально - с уровнями сложности с установкой таймеров в зависимости от уровня);
* лидерборд (топ игроков и лучших партий);
* статистика в любых видах (графики, пай-чарты итд);
* аккаунты и авторизация;
* красивый дизайн, адаптив, анимации;
* возможность красиво пошарить свой результат или профиль в соцсетях;

## Shoot Children' Scares ([Table of Contents](#contents)) 

**Сложность:** 🟧 средняя

**Концепт:** point-and-click-игрушка, где надо "отстреливать" страхи приемных детей. Список страхов - [тут](https://docs.google.com/document/d/16nTLrzaVVOPffb91CrFZO0fv1KRhJQ1_hNFxRFyPYvQ), в разделе "Типичные страхи приемных детей". Можно использовать иконки с [flaticon](https://www.flaticon.com/), например, с хэллоуинской тематикой. По иконке должно быть понятно, какой именно это страх.

❗️**не используйте в своем дизайне концепт из примера с могильными плитами, и вообще ничего, связанного со смертью (привидений тех же), потому что _мы делаем игры для НКО, связанного с детьми-сиротами_. Пример функциональности выбран, как самый наглядный, не копируйте его.**

**Пример:**

![Pure CSS ghost bustin' game w_ CSS variables 👻🕹#CodePenChallenge](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/7ceabb8f-ebaf-4953-a056-3eb5bd2dba2e)

**Базовый минимум:**

* вывод поля с правилами игры и приглашением стартовать
* вывод поля со страхами, которые появляются и прячутся;
* возможность "отстреливать" страхи, при попадании они исчезают с анимацией, которая маркирует попадание;
* возможность начать игру заново;
* экран поздравления с окончанием игры + количество очков;
* "легенда" с описанием: какая иконка соответствует какому страху;

**Возможности для расширения:**

* разное время для партий на выбор;
* возможность бесконечной партии;
* разная "сложность" страхов в рамках партии + разное количество очков сообразно сложности каждого (например, есть отдельный страх, в который особенно сложно попасть);
* разная "сложность" и сила оружия (разные страхи по-разному реагируют на разные виды оружия);
* какой-либо игровой сюжет;
* дополнительный модус: игра не на время, а на количество промахов (например, заканчиваем, если игрок промахнулся трижды);
* адаптив и возможность играть с планшета/телефона;
* красивые анимации (включая svg-анимации иконок);
* лидерборд (топ игроков и лучших партий);
* статистика в любых видах (графики, пай-чарты итд);
* аккаунты и авторизация;
* возможность красиво пошарить свой результат или профиль в соцсетях;

## Maze Game ([Table of Contents](#contents)) 

**Сложность:** 🟧 средняя 

**Концепт:** гениерируем игру-лабиринт, в которой приводим приемного родителя/родителей к ребенку. Можно использовать [алгоритм генерации лабиринтов](https://www.dstromberg.com/2013/07/tutorial-random-maze-generation-algorithm-in-javascript/) и иконки с [flaticon](https://www.flaticon.com/).

**Пример:**

![ezgif-3-f8f861385f](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/c792c4d3-2ff6-45e5-9927-c6bea57c6443)

**Базовый минимум:**

* генерация рандомных лабиринтов на каждую игру;
* инструкция к игре (как в нее играть);
* управление "родителем" с клавиатуры стрелочками;
* реализован алгоритм самой игры: "родитель" не может проходить сквозь стены лабиринта;
* возможность сбросить игру к начальному значению (без потери конфигурации лабиринта);
* возможность "завершить" раунд и увидеть визуализацию правильного пути (дальше - рестарт партии с новым лабиринтом);
* экран поздравления с окончанием игры;

**Возможности для расширения:**

* возможность выбрать уровень сложности лабиринта (например, с варьирующимся размером);
* игра по таймеру (опционально - с ограничением времени на партию, опционально - с уровнями сложности с установкой таймеров в зависимости от уровня);
* препятствия на пути в виде страхов ребенка. Список страхов - [тут](https://docs.google.com/document/d/16nTLrzaVVOPffb91CrFZO0fv1KRhJQ1_hNFxRFyPYvQ), в разделе "Типичные страхи приемных детей". Попадение в "страх" откатывает игру к началу/резко уменьшает таймер при игре на время/как-то еще дамажит прогресс. Можно использовать иконки с [flaticon](https://www.flaticon.com/), например, с хэллоуинской тематикой. По иконке должно быть понятно, какой именно это страх (или нужна легенда);
* красивый дизайн и анимации;
* лидерборд (топ игроков и лучших партий);
* статистика в любых видах (графики, пай-чарты итд);
* аккаунты и авторизация;
* возможность играть с мобильного устройства/планшета;
* возможность красиво пошарить свой результат или профиль в соцсетях;

## Charity Day Banners Builder ([Table of Contents](#contents)) 

**Сложность:** 🔴 высокая

**Концепт:** возможность генерировать баннеры к "Дню сироты". Максимально упрощенный вариант [Canva](https://www.canva.com/): возможность размещать на холсте текст, графику с помощью drag-n-drop и экспортировать в виде картинки (JPG/PNG) и/или PDF. Для экспорта можно использовать как сторонние либы типа [html-to-image](https://www.npmjs.com/package/html-to-image), так и сделать свое решение.

**Пример:**

Холст и смена его цвета:

![Дизайн без названия — Видео (1)](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/3acafc8a-ccdc-4ce0-b199-b34b3baeb67d)

Создание текстового блока и его кастомизация:

![Дизайн без названия — Видео (2)](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/7ac103da-f32d-4598-8ab4-536a897f544a)

Использование графики:

![ezgif-1-6b94667dbe](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/8d6e6ce1-9d28-450b-ad44-4c02897f76ec)

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

## Home Builder ([Table of Contents](#contents)) 

**Сложность:** 🔴 высокая

**Концепт:** пожалуй, самое творческое задание. Задача - собрать домик для ребенка. Это может быть 3D-like интерьер, это может быть плоский план

❗**Для плоских сцен запрещено использовать готовые картинки и делать "коллаж" из иконок. Делаем иллюстрации на чистом CSS/JS руками с высокой детализацией (как на примерах).**
<br />
<br />
❗**Для 3D сцен разрешено использовать модельки**

**Пример:**

3D-сцены:

![f3c6c873c8a3ac412ee1c96cec50baee](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/066e15bb-56c9-489d-8846-09c4a58ed538)
![original-feb3f9c174aa0055b40ca251cd86bba6](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/bb651436-e3c4-4ba8-863e-d3626a2147ec)

Плоская сцена:

![d2a422a7401e1a9459e1015a0e9a13da](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/24f3a18f-2ba1-4f07-9878-094bd703921f)
![living-room-interior-with-large-panoramic-windows_107791-11853](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/ce925728-878b-4c4f-991b-1783c05a788c)
![condo-accommodation-living-room-cosy-modern-minimalism-minimal-interior-indoor-set_126523-2467](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/e01e592d-86b8-48e9-8938-6c5a283c9234)
![living-room-interior-set-of-furniture_107791-830](https://github.com/nat-davydova/charity-hackaton-cases/assets/52240221/ff8809b9-0503-41cb-9b0a-f56f369afac6)

**Базовый минимум:**

* одна сгенерированная сцена, содержащая детскую комнату (3d или плоскую);
* все предметы в этой комнате должны быть с высокой детализацией (как на примерах);
* возможность кастомизировать все предметы мебели и декора (например, по клику выбирать цвет из палитры или по клику на предмет, например, картину, выбрать одну из нескольких опций);
* возможность сбросить сцену к начальному виду;

**Возможности для расширения:**

* адаптив и возможность играть с телефона/планшета;
* интерактив взаимодействия с предметами (например, открывающиеся окна/двери/шкафчики или смена освещения от включения/выключения света);
* внедрение игровых механик;
* возможность перетаскивать предметы мебели или декора (вплоть до пустой комнаты, в которой можно самостоятельно размешать элементы из подготовленного вами набора):
  * если у вас перетаскивание предметов, вы можете его логически усложнять и получать дополнительные баллы (например, кресло может быть только на полу, полки - только на стене, предметы не висят в воздухе и не идут внахлест итд);
  * возможность отменять последние N действий в проекте, откатываться назад/вперед; 
* внедрение фоновой музыки (бесплатной и в тему) и выбора озвучки, возможность включить/выключить;
* аккаунты и авторизация;
* сохранение проектов:
  * локальное кэширование: когда юзер открывает страницу, он видит текущий статус сцены, а не новый проект;
  * сохранение проекта или проектов в ЛК аккаунта и возможность выбирать, какой проект редактировать;
  * возможность выгрузить проект как картинку (в JPG/PNG/PDF);
  * красивое переключение между проектами;
* возможность красиво пошарить свой результат в соцсетях;
