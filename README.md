# ProjectT spring-2016 - Домашнее задание #4
## Задание
- Пусть дан следующий конечный автомат состояний льва. Входные символы: `антилопа`, `охотник`, `дерево`. Внутренние состояния: `сытый`, `голодный`. Действия автомата: `съесть`, `спать`, `убежать`, `смотреть`. Таблица переходов:

     | Сытый | Голодный
---- | ----- | --------
Антилопа | спать, перейти в состояние голодный | съесть, перейти в состояние сытый
Охотник | убежать, перейти в состояние голодный | убежать
Дерево | смотреть, перейти в состояние голодный | спать

- Реализовать поведение льва и написать на этот код unit-тесты

## Требования
- Python 3.5.x
- Колбасить код не в ветке `master`
- Автоматический запуск тестов на [Travic CI](https://travis-ci.org/)
- В `README.md` [бейдж](http://docs.travis-ci.com/user/status-images/) статуса сборки проекта
