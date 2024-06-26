---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Презентация в Markdown"
subtitle: "Особенности создания, оформления и не только"
summary: "В этом посте идет речь о том, как создавать презентации на языке Markdown, как оформлять слайды, вставлять изображения и так далее"
authors: [Жибицкая Евгения]
tags: []
categories: []
date: 2024-04-14T19:34:44+03:00
lastmod: 2024-04-14T19:34:44+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
В предыдущем посте было произведено знакомство с языком разметки Markdown. Там можно было узнать про его создание, синтаксис, особенности работы с ним и многое другое. 

Этот пост является продолжением и посвящется более продвинутому использованию - созданию презентаций.

Базовые принципы:

Файл с презентацией должен иметь имя presentation.md и в первой строке указываем настройки презентации
<!-- center ... theme:white -->

center - вертикальное центрирование содержимого слайдов;
number - выводить номер слайда;
code   - вставлять коды программ
math   - вставлять математические формулы;
plot   - вставлять графики функций;
uml    - вставлять UML-диаграммы, интерфейсы пользователя и графы;
speadsheet -  вставлять вычисляемые таблицы;
board -  чертить "маркером" на слайде и рисовать мышкой на чёрной доске;
audio - для каждого слайда в папке audio может быть указан звук;
autoplay:10 - автоматический показ слайдов с указанной задержкой или по продолжительности звука;
recorder -  записать звук во время лекции и скачать его по окончании;
theme:white - начальная цветовая тема, можно сменить на другую при показе презентации, вместо white можно указать black, moon, sky и т.д.;
960x700 - разрешение для презентации (по умолчанию 1600x900).
Кодировка файла должна быть UTF-8 и для ввода необходим соответствующий редактор (редактор Far Manager, Notepad++).

Также, если необходимо преобразование презентации в другие форматы, то необходимо добавить соответсвующий код: 
- Использование LaTeX
- Пакет для презентации: [beamer](https://ctan.org/pkg/beamer)
- Тема оформления: `metropolis`

```yaml
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
```

Кроме того, наверняка потребуется загрузить и указать в начале необходимые для работы шрифты. Я, например,рекомендую эти: 
- mainfont: PT Serif
- romanfont: PT Serif
- sansfont: PT Sans
- monofont: PT Mono
- mainfontoptions: Ligatures=TeX
- romanfontoptions: Ligatures=TeX
- sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9

Эти пункты необходимо добавить в первый отдел, где указываются все настройки.



Разделы в презентации вводятся с помощью --- на отдельной строке. Переход между разделами - стрелки влево-вправо.

Разделение на слайды внутри раздела - с помощью --. Переход между разделами - стрелки вверх-вниз.

Последовательное листание всех слайдов - пробел.

Для заголовков слайдов используются хештеги(#). Количество - уровень заголовка по убыванию размера.

Синтаксис для форматирования текста сохраняется.
Текст на слайдах можно разделять на несколько столбцов, выранивать по разным краям и не только.


Пример оформления слайда

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Жибицкая Е.Д.
  * студент
  * Российский университет дружбы народов
  * <ссылка>

:::
::: {.column width="30%"}

![](.изображение)

:::
::::::::::::::


Итак, здесь была представлена краткая информация о том, что необходимо указать в файле, для создания презентации на языке разметки Markdown.


