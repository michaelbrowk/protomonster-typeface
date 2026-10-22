<p><img src="assets/protomonster-logo.png" alt="Protomonster" width="640"></p>

# Protomonster 1.300

Маркерный display-шрифт для коротких фраз и крупных заголовков. Латиница и кириллица, настоящие строчные буквы, 427 Unicode-символов и 430 глифов.

[Скачать комплект 1.300](https://github.com/michaelbrowk/protomonster-typeface/releases/download/v1.300/Protomonster-Family-1.300-Release.zip) · [Интерактивный specimen](specimen.html) · [Превью](preview.png)

[Лендинг и полный каталог](https://www.michaelbrowk.com/protomonster)

Расширенная европейская латиница, кириллица с украинскими и белорусскими буквами, стрелки, дроби, верхние и нижние индексы.

[Изменения 1.300 и границы проверки](CHANGELOG.md)

## Начертания

| Файл | Вес |
| --- | --- |
| Variable | 400–700, по умолчанию 500 |
| Regular | 400 |
| Medium | 500 |
| Bold | 700 |

В ZIP только Variable TTF / WOFF2, три статических начертания в TTF / OTF / WOFF2 и LICENSE.txt — всего 12 файлов.

## Установка

Для плавного выбора веса установите [Variable TTF](Protomonster-Variable.ttf), если приложение поддерживает variable fonts. Либо установите три статических TTF: [Regular](Protomonster-Regular.ttf), [Medium](Protomonster-Medium.ttf), [Bold](Protomonster-Bold.ttf). Выберите один вариант установки, чтобы избежать дубликатов семейства.

Для проверки своего текста используйте [тестер на сайте](https://www.michaelbrowk.com/protomonster). Локальный `specimen.html`, CSS и превью доступны отдельно в этом репозитории; в компактный ZIP они не входят.

## На сайте

Разместите `protomonster.css` и `Protomonster-Variable.woff2` рядом, затем подключите CSS:

```html
<link rel="stylesheet" href="./protomonster.css">
<h1 class="protomonster">Привет, монстр!</h1>
```

Вес меняется непрерывно через `font-weight: 400` … `700`. CSS использует 500 по умолчанию и отключает искусственное утолщение. Класс `protomonster-monster` включает вариант M / М с глазами (`ss01`):

```html
<h1 class="protomonster protomonster-monster">Монстр!</h1>
```

[Полный постер](specimen.png) · [Контрольные суммы SHA-256](SHA256SUMS)

## Лицензия

Бесплатно для личного и коммерческого использования. Распространение изменённых файлов шрифта запрещено; готовые дизайны, созданные со шрифтом, этим ограничением не затрагиваются. Полные условия — [LICENSE.txt](LICENSE.txt).
