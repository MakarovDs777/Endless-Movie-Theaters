# Endless-YouTube
[![Endless-Youtube.png](https://i.postimg.cc/DycFHyCX/Endless-Youtube.png)](https://postimg.cc/3dWPD7Q8)

Бесконечная видеотека бэкрумса, это неограниченный ютуб с бесконечным количеством видео каждое из которых может быть которое только снято, и соответственно продолжительность каждого видео, и самих видео в ней от одного до бесконечности включая саму бесконечность, бесконечная закулисная видеотека разделена на стеллажи, который обозначаются числом, равным количеству продолжительности видео, например, если это канал № 1, то все видео в нем с одной секундой, и все варианты размещения всех возможных кадров всех всевозможных расположений пикселей в этом кадре каждую секунду, если это канал № 2 тогда в нём все видео по 2 секунды и все варианты расположения всех кадров в этом видео которые только могут быть и т.д. Количество стеллажей бесконечно. 

У Брогли есть [классное видео](https://www.youtube.com/watch?v=yE0Am1TeXRk) на эту тему, ну и сам уровень [444](https://web.archive.org/web/20221002174838/https://backrooms.fandom.com/wiki/Level_444), и мне понравилась такая концепция... Но странно что кому до сих пор не пришла такая идея в голову! Представьте себе бесконечный ютуб с бесконечным числом видео! Или как в Рике и Морти было межгалактическое ТВ! Вот это было реально круто спрограммировать что-то подобное! Блин как же я хочу реализовать этот бэкрумс чёрт побери...

# Generate_random_video

Программа получает на вход номер канала, и номер видео в этом канале, и генерирует его на рабочий стол.

Да, вы правильно понимаете. В теории, с учетом того, что каждый кадр генерируется случайным образом, существует вероятность того, что все пиксели на всех кадрах будут одного и того же цвета, например, красного. Однако вероятность этого очень низка, особенно при использовании 24-битного цветового пространства (8 бит на каждый канал - красный, зеленый, синий), которое позволяет более чем 16 миллионам различных цветовых комбинаций.

Таким образом, хотя такая последовательность кадров теоретически возможна, вероятность ее возникновения крайне мала.

Хорошая эта идея про бесконечный ютуб но как из этого бесконечного цветного шума выделить и отсортировать что-то осмысленное? Что-то что действительно имеет какую-то ценность? Вот в чем вопрос... У меня кажется есть идея на этот счёт нужно просто взять какой-то образ за основу какого-то видео как точку отсчёта, и при каждой последующей итерации изменить что-то одно в этом образе видео, и таким образом мы получим бесконечное число вариаций этого образа которое позволит создать бесконечное множество чего-то осмысленного!
