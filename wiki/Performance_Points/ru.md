<img src="Performance point.jpg" title="fig:Внешний вид графика" alt="Внешний вид графика" width="200" /> Очки производительности (англ. perfomance points, также пеппи-поинты, ппочки, почки) — ранговая метрика, учитывающая скорей навык игры, чем её продолжительность.

История
=======

Новая метрика первоначально появилась в апреле 2012 года под названием "???". После тестирования и отладки, её переименовали в "pp" 17 апреля. Будучи более точными и объективными, чем старая метрика (представлявшая собой сумму очков на всех ранкнутых картах), pp окончательно заменили её 24 июля, вместе с одним из релизов клиента osu! [(20120722-24)](http://osu.ppy.sh/forum/p/1687719). Обновления происходили каждые полчаса, а с 16 августа — мгновенно. Спустя почти два года работы, 27 января 2014 года, система очков производительности получила серьёзный апдейт. Для этого к работе был привлечён [Tom94](http://osu.ppy.sh/u/1857058), всё это время работавший над собственной неофициальной [системой ранкинга osu!tp](http://osutp.net). В конечном итоге, примерно 80% логики работы pp базируется на osu!tp.

Недавние изменения можно посмотреть [здесь](https://osu.ppy.sh/p/changelog?category=performance), а лог работы над ppv1 — [здесь](http://osu.ppy.sh/forum/t/92185).

Расположение
============

Добраться до нового ранкинга можно, кликнув по [ссылке](http://osu.ppy.sh/p/pp) или найдя эту же ссылку на сайте в меню Rankings → Performance.

Узнать, сколько очков принесла каждая карта, можно в профиле в разделе Top Ranks. Не забудьте учесть веса рекордов (см. далее)!

Расчет
======

Система пп основывается на сложности карты, которая, в свою очередь, рассчитывается отдельно для каждого режима игры. Ниже — табличка с подробным описанием.

| ![](osu.gif "fig:osu.gif") [Стандарт](RU:Standard "wikilink") |-align="center" |  | (**Aim**^*X* + **Speed**^*X* + **Accuracy**^*X*)^(1/*X*) |
|-----------------------------------------------------------------------------------|----------------------------------------------------------|
| ![](taiko.gif "fig:taiko.gif") [Тайко](Тайко "wikilink") |-align="center" |       | (**Strain**^*X* + **Accuracy**^*X*)^(1/*X*)              |
| ![](ctb.gif "fig:ctb.gif") [КТБ](RU:Catch_the_Beat "wikilink") |-align="center" | | **Aim**                                                  |
| ![](mania.gif "fig:mania.gif") [Мания](Мания "wikilink") |-align="center" |       | (**Strain**^*X* + **Accuracy**^*X*)^(1/*X*)              |

-   Стандарт и тайко: *X* = 1.1
-   Мания: *X* пока что тоже равен 1.1. **Strain** влияет на количество полученных pp сильней, чем **Accuracy**, так как последний параметр неявно присутствует в **Strain**.

| Режим\\Характеристики                                          | Aim                                                                                                                      | Speed                                                   | Accuracy                                                                                                                       | Strain                                                                                                                                                |
|----------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](osu.gif "fig:osu.gif") [Стандарт](RU:Standard "wikilink")  | -   **Аим** + [моды](RU:Game_Modifiers "wikilink")  
                                                                  -   **[AR](Song_Setup#Approach_Rate "wikilink")** + [моды](RU:Game_Modifiers "wikilink")
                                                                  -   Длина карты (кол-во объектов)
                                                                  -   Комбо и кол-во промахов
                                                                  -   Точность (небольшая доля)
                                                                  -   Включённые [Hidden](RU:Game_Modifiers#Hidden "wikilink") и/или [Flashlight](RU:Game_Modifiers#Flashlight "wikilink")  | -   **Скорость** + [моды](RU:Game_Modifiers "wikilink")
                                                                                                                                                                                             -   Длина карты (кол-во объектов)
                                                                                                                                                                                             -   Комбо и кол-во промахов
                                                                                                                                                                                             -   Точность (небольшая доля)                            | -   **[OD](Song_Setup#Overall_Difficulty "wikilink")** + [моды](RU:Game_Modifiers "wikilink")
                                                                                                                                                                                                                                                       -   Длина карты (кол-во объектов)
                                                                                                                                                                                                                                                       -   Комбо и кол-во промахов
                                                                                                                                                                                                                                                       -   Точность без учета слайдеров и спиннеров
                                                                                                                                                                                                                                                       -   [Hidden](RU:Game_Modifiers#Hidden "wikilink") и/или [Flashlight](RU:Game_Modifiers#Flashlight "wikilink") (небольшая доля)  |                                                                                                                                                       |
| ![](taiko.gif "fig:taiko.gif") [Тайко](Тайко "wikilink")       |                                                                                                                          |                                                         | -   **[OD](Song_Setup#Overall_Difficulty "wikilink")** + [моды](RU:Game_Modifiers "wikilink")  
                                                                                                                                                                                                                                                       -   Длина карты (кол-во объектов) без учёта драмроллов и спиннеров
                                                                                                                                                                                                                                                       -   Точность                                                                                                                    | -   **Напряжение** + [моды](RU:Game_Modifiers "wikilink")
                                                                                                                                                                                                                                                                                                                                                                                        -   Длина карты (кол-во объектов)
                                                                                                                                                                                                                                                                                                                                                                                        -   Комбо и кол-во промахов
                                                                                                                                                                                                                                                                                                                                                                                        -   Точность (небольшая доля)                                                                                                                          |
| ![](ctb.gif "fig:ctb.gif") [КТБ](RU:Catch_the_Beat "wikilink") | -   **Аим** + [моды](RU:Game_Modifiers "wikilink")  
                                                                  -   **[AR](Song_Setup#Approach_Rate "wikilink")** + [моды](RU:Game_Modifiers "wikilink")
                                                                  -   Длина карты (кол-во объектов)
                                                                  -   Комбо и кол-во промахов
                                                                  -   Точность (небольшая доля)
                                                                  -   Включённые [Hidden](RU:Game_Modifiers#Hidden "wikilink") и/или [Hidden](RU:Game_Modifiers#Hidden "wikilink")          |                                                         |                                                                                                                                |                                                                                                                                                       |
| ![](mania.gif "fig:mania.gif") [Мания](Мания "wikilink")       |                                                                                                                          |                                                         | -   **[OD](Song_Setup#Overall_Difficulty "wikilink")** + [моды](RU:Game_Modifiers "wikilink")  
                                                                                                                                                                                                                                                       -   Длина карты (кол-во объектов)
                                                                                                                                                                                                                                                       -   Точность                                                                                                                    | -   **Напряжение** + [моды](RU:Game_Modifiers "wikilink") (пока что без [Double Time](RU:Game_Modifiers#Double_Time "wikilink"), но с кол-вом клавиш)
                                                                                                                                                                                                                                                                                                                                                                                        -   Длина карты (кол-во объектов)
                                                                                                                                                                                                                                                                                                                                                                                        -   Отношение полученных очков к максимальным (меняется не линейно)                                                                                    |

'''Заметки:- '''

-   Strain (напряжение) — параметр, отвечающий за рост сложности с течением времени. Чем выше Strain, тем выше средняя сложность (количество объектов, их плотность на такт и так далее) карты.
-   Aim (аим) — насколько хорошей координации требует карта. Проще говоря, ваше умение целиться курсором по нотам.
-   Моды, которые уменьшают пп:-
    -   [No Fail](RU:Game_Modifiers#No_Fail "wikilink") — -10%
    -   [Spun Out](RU:Game_Modifiers#Spun_Out "wikilink") — -5%.
-   Сравнение длин карт:
    -   Длина 2 минуты, 1000 объектов &gt; 500 объектов
    -   Длина 2 минуты, 1000 объектов &gt; 5 минут, 900 объектов.
-   На сложность не влияют:
    -   [Sudden Death](RU:Game_Modifiers#Sudden_Death "wikilink")/[Perfect](RU:Game_Modifiers#Perfect "wikilink"), [Relax](RU:Game_Modifiers#Relax "wikilink"), [Auto Pilot](RU:Game_Modifiers#Auto_Pilot "wikilink"), [Auto](RU:Game_Modifiers#Auto "wikilink")/[Cinema](RU:Game_Modifiers#Cinema "wikilink").

Как увеличить свой ранк
=======================

Ваш ранк складывается из того, насколько успешно вы играете отдельные карты. Самый простой способ повысить количество пп — улучшить свои результаты на сложных картах. Несмотря на очевидность, стоит отметить, что пп для каждого режима игры считаются **отдельно.**

-   Играйте эффективно, совершенствуйтесь.
-   Один классный результат лучше, чем пять хороших или двадцать обыкновенных.
-   Точность **имеет значение.** Даже один лишний процент может ощутимо помочь.
-   Стремитесь набрать наиболее длинное комбо. В идеале — пройти карту на фк или получить SS.
-   Играйте достойные сложности, а не нормалы и харды без модов.

Весовая система
===============

<img src="Pp bp.jpg" title=" Список результатов и их весов." alt=" Список результатов и их весов." width="200" />

Для большей прозрачности, рядом с каждой картой указывается ее вес и то, сколько пп она принесла. Целиком учитывается только карта с наибольшим количеством пп, остальные же урезаются. При показе в списке вес округляется до ближайшего целого числа, но в расчётах ничего не округляется.

Если n — это количество карт, давших больше пп, чем текущий результат, то его вес будет равен **0.95^n**. Поэтому для расчётов можно применить следующую логику.

Пусть PP — список ваших результатов, посортированный по убыванию, а PP\[i\] — количество пп, которая вам дала карта под номером i (i меняется от 1 до n). Тогда:

**Общее кол-во пп** = PP\[1\] \* **0.95**^0 + PP\[2\] \* **0.95**^1 + PP\[3\] \* **0.95**^2 + ... + PP\[n\] \* **0.95**^(n-1)

[Образец расчетов (прокрутите чуть вниз)](/wiki/Pp_bp.jpg)
