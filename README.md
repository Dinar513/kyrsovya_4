Парсер данных с hh.ru
Программа получает информацию о вакансиях с платформы hh.ru в России, 
сохраняет ее в файл и позволяет удобно работать с ней:
1. добавлять
2. фильтровать
3. удалять
Структура проекта:
1.абстрактный класс для работы с API сервиса с вакансиями
2. класс для работы с вакансиями
3. абстрактный класс, который обязывает реализовать методы для добавления вакансий в файл, получения данных из файла по указанным критериям и удаления информации о вакансиях
4. функция для взаимодействия с пользователем
5. описанный функционал покрыт тестами
Документация для сбора вакансий с hh.ru
Ссылка на API: https://github.com/hhru/api/.