# Go Web Notes

Простое веб-приложение для создания заметок на языке Go.  
Позволяет добавлять заметки через HTML-форму и отображает их на странице.

## Функциональность

- Веб-сервер на Go (`net/http`)
- HTML-шаблоны (`html/template`)
- Добавление заметок через форму (`POST`)
- Отображение списка заметок
- Перенаправление после отправки формы (`POST → Redirect → GET`)

## Структура проекта

/templates
  └── index.html      — HTML-шаблон
main.go               — основной код сервера
README.md             — этот файл
