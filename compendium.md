<!-- HTML -->

<!-- CSS -->

1vh - 1% висоти вьюпорта

<!-- Flexbox -->

CSS-властивості Flexbox:

<!-- -- Flex Container -- -->

- display: flex — вирівнює елементи по осі Х
- flex-direction: row (default) | column | row-reverse — змінити напрямок
- order: 3; — переміщає на інше місце

                .item {
                  height: fit-content - розмір елементу відповідно розміру вмісту
                  width: fit-content
                }

- justify-content — вирівнює елементи відносно осі X justify-content: center |
  flex-start | flex-end | space-between | space-around

- align-items — вирівнює елементи відносно осі Y align-items: center |
  flex-start | flex-end | space-between | space-around

- align-content — вирівнює весь контент відносно осі Y

        flex-flow — скорочення від flex-direction

- flex-wrap — елементи, що не помістились в рядку, переносяться на наступний
  рядок

<!-- -- Flex Items -- -->

- align-self — дозволяє керувати кожним конкретним елементом відносно осі Y

- flex-basis — задає розмір елемента відносно осі Х — у відсотках %
- flex-grow — скільки умовних одиниць розміру елемент буде займати (1,2,1 =
  25%,50%,25%)

- flex-shrink — як вжимається елемент при зменшенні розміру вьюпорту
  flex-shrink: 4 — цей елемент вжимається в 4 рази швидше інших
