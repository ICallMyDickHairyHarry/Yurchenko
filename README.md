# Yurchenko

Android-приложение со списком фильмов и их описанием для Тинькофф Финтех, курс Android-разработка.

В роли источника данных выступает неофициальный API кинопоиска.

Выполнены все основные требования к приложению: 
1. На главном экране необходимо отображать список популярных фильмов.
2. В каждой карточке фильма на главной странице должны содержаться следующие элементы:
  2.1 Наименование фильма.
  2.2 Изображение-постер фильма.
  2.3 Год выпуска.
3. При клике на карточку открывается экран с постером фильма, описанием, жанром, страной 
производства.
4. Если сеть недоступна или в процессе загрузки произошла ошибка, необходимо предусмотреть 
уведомление пользователя об этом.

Дополнительно было реализовано:
- В разделе популярных фильмов доступен поиск фильмов по наименованию.

Особенности реализации:
- Приложение написано на Kotlin.
- Обеспечена общая плавность и стабильность приложения.
- Во время длительных загрузок, отображаются шиммеры/прогресс бары.
- Изображения загружаются с помощью Coil, которая автоматически их кеширует, 
остальные данные хранятся в ViewModel.
- Приложение частично покрыто INSTRUMENTATION тестами.
