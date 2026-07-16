# BooksCollector — юнит-тесты

Проект содержит юнит-тесты для приложения BooksCollector: добавление книг, установка жанров и работа со списком избранного.

## Реализованные тесты

1. test_add_new_book_add_two_books — можно добавить две книги.
2. test_add_new_book_has_no_genre — у новой книги пустой жанр.
3. test_add_new_book_invalid_name_not_added — книги с пустым и со слишком длинным названием не добавляются.
4. test_set_book_genre_valid_genre — установка допустимого жанра.
5. test_set_book_genre_invalid_genre_not_set — жанр не из списка не устанавливается.
6. test_get_book_genre_returns_correct_genre — получение жанра книги по имени.
7. test_get_books_with_specific_genre_returns_matching_books — вывод книг определённого жанра.
8. test_get_books_for_children_excludes_age_rated — книги для детей не содержат жанры с рейтингом по возрасту.
9. test_add_book_in_favorites_added — добавление книги в избранное.
10. test_delete_book_from_favorites_removed — удаление книги из избранного.

## Запуск тестов

pytest -v tests.py