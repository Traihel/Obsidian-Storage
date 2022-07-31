2022-07-24 22:15
Tags: #CSS 
__
# Flex-box

- Свойства применяемые к контейнеру:

`flex-direction` - задает направление главной оси  (по умолчанию - row)
   - row - элементы размещаются по направлению текста.
   - row-revers - элементы отображаются в обратном порядке к направлению текста.
   - column - элементы располагаются сверху вниз.
   - column-revers - элементы располагаются снизу вверх.
   
`justify-content` - (горизонтально) выравнивает элементы по главной оси 
   - flex-start - элементы выравниваются по левой стороне контейнера.
   - flex-end - элементы выравниваются по правой стороне контейнера.
   - center - элементы выравниваются по центру контейнера.
   - space-between - элементы отображаются с одинаковыми отступами между ними.
   - space-around - элементы отображаются с одинаковыми отступами вокруг них.
   - space-evenly; - равное растояние между элементами
   
`align-items` - (вертикально) выравнивает элементы по второстепенной оси 
   - flex-start - элементы выравниваются по верхнему краю контейнера.
   - flex-end - элементы выравниваются по нижнему краю контейнера.
   - center - элементы выравниваются вертикально по центру контейнера.
   - baseline - элементы отображаются на базовой линии контейнера.
   - stretch - элементы растягиваются, чтоб заполнить контейнер.
   - space-evenly;
   
`flex-wrap` -  Будут ли элементы выходить за рамки контейнера (по умолчанию – nowrap). 
   Если wrap, то элементы, которые не помещаются, будут переноситься на новую строку (столбец).
   - nowrap - размеры элементов устанавливаются автоматически, чтоб они поместились в один ряд.
   - wrap - элементы автоматически переносятся на новую строку.
   - wrap-reverse - Элементы автоматически переносятся на новую строку, но строки расположены в обратном порядке.

- Свойства применяемые к отдельному элементу внутри контейнера:
`order` - определяет порядок элемента. Каким по счету (в ряду или столбце) он будет 
   Значения: 1, 2, 3…
`align-self` - выравнивает 1 элемент (ребенка) по второстепенной оси (если нужно его 
   как-то по-другому разместить)
   Значения: flex-start, flex-end, center, baseline, stretch

__
### Links
[[CSS]]