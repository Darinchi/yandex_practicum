# Анализ взаимодействия пользователей с карточками Яндекс.Дзен

## Цель исследования
Используя данные Яндекс.Дзена построить дашборд с метриками взаимодействия пользователей с карточками статей

## Инструменты и навыки
Python, PostgreSQL, dash, Tableu, продуктовые метрики, построение дашбордов

## Описание проекта
Работу над этим проектом я провела на удаленной машине в сервисе Yandex.Cloud. 
Мной был установлен PostgreSQL, развернута база данных. 
Затем я написала скрипт пайплайна, который позволил собирать данные за определенный временной период, 
и настроила его автономную работу через crontab. 

Для визуализации собранных данных я написал скрипт дашборда с несколькими фильтрами и также запустил его на удаленной машине. 
По результатам была подготовлена презентация с полученными графиками

## Общий вывод
Создан дашборд:
https://public.tableau.com/app/profile/darina5957/viz/Yandex_16546020198280/Dashboard1?publish=yes

При использовании дашборда на данных за период 24 сентября 2019 г. с 18:28 по 19:00 получены выводы:

1.Топ-3 популярных тем карточек:
- Наука, 
- Отношения, 
- Интересные факты

2. Топ-3 популярных тем источников: 
- Семейные отношения, 
- Россия, 
- Полезные советы

3. С повышением возраста пользователей больше интересуют карточки с темами: Семья и Полезные советы.

4. Наиболее популярные переходы из одной темы в другую: 
- из Путешествий в Рассказы, 
- из России в Общество, 
- из Кино в Науку.
