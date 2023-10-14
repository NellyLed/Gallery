Задача:
Создать меню, состоящее из 3-х горизонтально расположенных гиперссылок. При нажатии на первую ниже должно появиться подменю с
гиперссылкой, которое выводит меню кафе в виде HTML-файла.Вторая гиперссылка должна выводить изображение, а третья - галерею.

Меню кафе:
должно выглядеть как вертикальное раздвигающееся меню, состоящее из 3-х пунктов, в каждом из которых содержится по 3 гиперссылки
подменю. Изначально должны быть показаны только элементы главного меню. При наведении курсора на пункт основного меню цвет его 
текста должен меняться, под ним должны отображаться (либо скрываться, если уже отображены) элементы выпадающего меню, при этом все
элементы, расположенные ниже, должны сдвигаться вниз. При наведении курсора на пункт подменю цвет текста данной гиперссылки должен
изменяться. При щелчке на каждой гиперссылке подменю осуществляется переход на сайт, на котором объясняется как готовится тот или иной рецепт.

Галерея:
слева должны располагаться 8 миниатюрных изображений по 2 изображения на строку. Всего 4 строки. По наведению мыши на каждое из 
изображений в центре должно появиться выбранное изображение в оригинальном размере. Сверху с правой стороны поместить
значок «закрыть», по щелчку на котором полноразмерное изображение исчезнет.
Решение:
Вертикальное раздвигающееся меню достигается с помощью языка JavaScript, используя в нем объект document со слушателями событий (нажатие 
на кнопку, проверка нахождения кнопки мыши внутри блока и т.д.). Значки "Закрыть" внедрены с использованием библиотек fancybox и jQuery.
Также используются внешние стили css.
