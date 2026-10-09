Отчёт по парсингу HTML

1. Файл news.html — Новости

Общая информация

* Сущность: новость.
* Селектор карточки сущности: body div#news-root div.news-item
* Контейнер страницы: body div#news-root
* Количество карточек: 3.

Таблица полей

Поле Selector path Тег Атрибут / источник значения
Заголовок страницы body div#news-root h1#page-title h1 Текст элемента
ID новости body div#news-root div.news-item div id
ID данных новости body div#news-root div.news-item div data-id
Категория новости body div#news-root div.news-item div data-category
Изображение body div#news-root div.news-item img.news-image img src
Альтернативный текст изображения body div#news-root div.news-item img.news-image img alt
Дата новости body div#news-root div.news-item span.news-date span data-iso
Заголовок новости body div#news-root div.news-item h2.news-title h2 Текст элемента
Текст новости body div#news-root div.news-item p.news-text p Текст элемента
Автор новости body div#news-root div.news-item span.news-author span Текст элемента
ID автора body div#news-root div.news-item span.news-author span data-author-id

Примечание: селекторы карточек и полей выбраны по структуре исходного HTML-кода. Значения, получаемые из текста элемента, отличаются от значений, получаемых из атрибутов.
