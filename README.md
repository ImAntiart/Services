Описание проекта
Этот проект представляет собой адаптивный сайт, созданный с использованием современных технологий и методологий вёрстки. Вёрстка выполнена для нескольких разрешений экрана (мобильные устройства, планшеты, десктопы) с учётом семантики, доступности и удобства поддержки.

Технологии и инструменты
1. HTML5
Использованы семантические теги (<header>, <main>, <nav> и др.) для улучшения структуры документа.
Все изображения имеют атрибут alt для обеспечения доступности.
Установлен метатег <meta name="viewport" content="width=device-width, initial-scale=1.0"> для корректного отображения на мобильных устройствах.
2. CSS3
Flexbox : Используется для создания адаптивных макетов, выравнивания элементов и управления пространством между ними.
Медиа-запросы : Реализована адаптивность для трёх основных разрешений:
Мобильные устройства: max-width: 320px.
Планшеты: min-width: 784px.
Десктопы: min-width: 1121px.
Свойства :
object-fit: cover для масштабирования изображений.
white-space: nowrap и overflow: hidden для обработки текста.
text-overflow: ellipsis для многоточия в тексте.
3. Шрифты
Подключены кастомные шрифты через файл fonts.css.
Основные шрифты: "TT Lakes" и резервный Arial, sans-serif.
4. Изображения
Все изображения оптимизированы для быстрой загрузки.
Используется свойство object-fit: cover для корректного отображения изображений в контейнерах.
5. Адаптивность
Верстка полностью адаптивна благодаря медиа-запросам и гибким блокам.
6. Доступность
Все интерактивные элементы (например, кнопки) имеют правильные атрибуты для работы с клавиатурой и скринридерами.
Изображения снабжены альтернативными текстами (alt).
7. Особенности реализации
Прокручиваемое меню
Текстовые блоки
