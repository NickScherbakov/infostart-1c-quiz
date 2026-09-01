[![Infostart](https://infostart.ru/bitrix/templates/sandbox_empty/assets/tpl/abo/img/logo.svg)](https://infostart.ru/public/REPLACE_WITH_ARTICLE_ID)

# 1C Quiz Advanced v2

Практический интерактивный тест по теме Linux/SRE/DevOps в экосистеме 1C для встраивания в публикацию на infostart.ru.

## Структура репозитория

.
|- index.html                # Интерактивный тест
|- article-code.html         # Код для вставки в Source-режиме редактора Infostart
|- .nojekyll                 # Отключает Jekyll в GitHub Pages
`- README.md                 # Инструкция по публикации

## Быстрый старт

1. Создайте пустой публичный репозиторий на GitHub.
2. Откройте терминал в этой папке и выполните:

  git remote add origin https://github.com/USERNAME/REPO.git
  git push -u origin main

3. В GitHub включите Pages:
  Settings -> Pages -> Deploy from a branch -> main -> /(root)
4. Дождитесь публикации по адресу:
  https://USERNAME.github.io/REPO/

## Вставка в статью на Infostart

1. Откройте файл article-code.html.
2. Замените USERNAME и REPO на реальные значения.
3. В редакторе статьи нажмите Source и вставьте содержимое файла.

## Соответствие правилам публикации

- В репозитории нет рекламы, реферальных ссылок и скрытого сбора данных.
- Ссылка на GitHub должна быть тематически связана с материалом статьи.
- Рекомендуется добавить в текст статьи пояснение, что интерактивный тест размещен во внешнем репозитории.
