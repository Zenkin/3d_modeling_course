Лабораторная работа №2
=========================

Теперь создадим модель двигателя, под который и делается наша сборка.

Следует сделать его в новой “Parat studio”. Создадим новую вкладку с деталями.
1. Нажимаем на “+”
2. Выбираем “Create part studio”

.. figure:: _static/Pictures/lab2/Рисунок1.png
       :scale: 35 %
       :align: center
       :alt: Модель двигателя

       Рисунок 1 - Модель двигателя

Назовем ее “RealParts”.

Сейчас как раз произошло разделение деталей по группам, мы обособили
детали, касающиеся корпуса от деталей которые не будут участвовать в печати
(подшипники, двигатели и пр.)

Перед началом моделирования того, что уже существует, необходимо либо
иметь его чертежи с размерами, или этот объект и штангенциркуль для измерения.

Создаем первый эскиз.

.. figure:: _static/Pictures/lab2/Рисунок2.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 2 - Первый эскиз

Необходимо сделать срезы по всем углам, но, чтобы не проводить каждый раз
линию и не выставлять размеры можно воспользоваться операцией “Mirror”.

Для начала построим линии относительно которых будет производиться
отражение.

Проводим на произвольную длину.

.. figure:: _static/Pictures/lab2/Рисунок3.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 3

Далее используем модификатор превращающий их во вспомогательные или
осевые (Это делать не обязательно, но когда на эскизе очень много геометрии, то
разделение линий на основные и вспомогательные значительно упрощает восприятие)

1;2. Выделяем отрезки, которые хотим преобразовать; 

3. Активируем инструмент для преобразования.

.. figure:: _static/Pictures/lab2/Рисунок4.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 4

Теперь отражаем нашу геометрию.

1. Активируем инструмент для создания зеркальной геометрии.

2. Выбираем опорную прямую, относительно которой будет отражаться
геометрия.

3. Выбираем саму геометрию для отражения.

.. figure:: _static/Pictures/lab2/Рисунок5.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 5


Мы отразили уголок относительно вертикали, теперь аналогично отразим его
относительно горизонтали, чтобы получилось так:

.. figure:: _static/Pictures/lab2/Рисунок6.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 6

И выдавливаем на 9.5 мм.

.. figure:: _static/Pictures/lab2/Рисунок7.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 7

Создаем новый эскиз на выделенной плоскости.

.. figure:: _static/Pictures/lab2/Рисунок8.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 8

Создаем эскиз. (Сначала был спроектирован контур выделенной детали, потом с
помощью Offset былми сдвинты необходимые линии на 2 мм и позже удлинены до границ,
чтобы замкнуть эскиз, но можно делать и другими способами).

.. figure:: _static/Pictures/lab2/Рисунок9.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 9

Далее выдавливаем его на 23мм.

.. figure:: _static/Pictures/lab2/Рисунок10.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 10

Создаем эскиз

.. figure:: _static/Pictures/lab2/Рисунок11.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 11

.. figure:: _static/Pictures/lab2/Рисунок12.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 12

Выдавливаем на 8 мм.

.. figure:: _static/Pictures/lab2/Рисунок13.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 13

Далее создаем эскизы и выдавливания соответственно. Создаем верхнее кольцо
шаговика.

.. figure:: _static/Pictures/lab2/Рисунок14.png
       :scale: 35 %
       :align: center
       :alt: Верхнее кольцо шаговика

       Рисунок 14 - Верхнее кольцо шаговика

.. figure:: _static/Pictures/lab2/Рисунок15.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 15

Создадим вал двигателя. Окружность в центре предварительно выдавлена.

.. figure:: _static/Pictures/lab2/Рисунок16.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 16

.. figure:: _static/Pictures/lab2/Рисунок17.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 17

Теперь необходимо сделать несколько отверстий для крепления двигателя (у
NEMA 17 это 4 отверстия под винты М3).

.. figure:: _static/Pictures/lab2/Рисунок18.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 18

Используя вспомогательную геометрию (квадрат 31 на 31 с центром в центре
окружности) строим 4 окружности радиусом 3 мм.

.. figure:: _static/Pictures/lab2/Рисунок19.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 19

И выдавливаем их вниз на 7мм.

.. figure:: _static/Pictures/lab2/Рисунок20.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 20

Теперь сделаем входной порт для проводов. Создаем эскиз снизу нашей модели.

.. figure:: _static/Pictures/lab2/Рисунок21.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 21

Для простоты был использован прямоугольник с центром в заданной точке,
чтобы удалить лишнюю геометрию используем инструмент “Trim”. Но предварительно
спроецируем геометрию нашей плоскости.

.. figure:: _static/Pictures/lab2/Рисунок22.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 22

1. Активируем инструмент;
2. Выбираем геометрию для удаления.

Отличие этого метода от простого выделения геометрии с последующим
удалением клавишей “Delete” в том, что этот инструмент позволяет удалять геометрию
от точки до точки.

.. figure:: _static/Pictures/lab2/Рисунок23.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 23

.. figure:: _static/Pictures/lab2/Рисунок24.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 24

Выдавливаем на 9.5 мм.

.. figure:: _static/Pictures/lab2/Рисунок25.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 25

На верхней части двигателя возле вала есть выемка, в которую могут упираться
некоторые детали. Создаем эскиз.

.. figure:: _static/Pictures/lab2/Рисунок26.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 26

.. figure:: _static/Pictures/lab2/Рисунок27.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 27

Выдавливаем вглубь на 3мм.

.. figure:: _static/Pictures/lab2/Рисунок28.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 28

Вернемся к валу двигателя. Сделаем фаску.

.. figure:: _static/Pictures/lab2/Рисунок29.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 29

Чтобы на валу было проще закреплять детали (шестерни муфты и т.д.)
производители делают небольшую площадку (лыску) для предотвращения
прокручивания детали.

Создаем скетч на верхней плоскости вала.

.. figure:: _static/Pictures/lab2/Рисунок30.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 30

Выдавливаем на 21мм.

.. figure:: _static/Pictures/lab2/Рисунок31.png
       :scale: 35 %
       :align: center
       :alt: Первый эскиз

       Рисунок 31

Двигатель готов.

Для более детализированной сборки с демонстрацией работы абсолютно всех
узлов двигатель следовало бы изготовить из 2 деталей: корпуса и вала. 
Но в наших условиях нет такой необходимости, поэтому модель немного упрощена.