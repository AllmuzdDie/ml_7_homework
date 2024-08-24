
##### Цель домашней работы:

Необходимо обучить две модели: логистическую регрессию и случайный лес. Далее нужно сделать подбор гиперпараметров с помощью базовых и продвинутых методов оптимизации. Важно использовать все четыре метода (GridSeachCV, RandomizedSearchCV, Hyperopt, Optuna) хотя бы по разу, максимальное количество итераций не должно превышать 50.

- Метрика для оценки -> f1_score

##### Общий вывод:
- Провели оптимизацию 2х моделей LogisticRegression и RandomForestClassifier
- Использовали 4 алгоритма оптимизации GridSearch и RamdomSearch, а также продвинутые алгориты Hyperopt и Optuna
- Использовали кросс-валидацию во всех случаях
- Для проверки использовали метрику f1_score
- По итогу можно сказать, что начальные настройки алгоритмов в целом показывают достойные результаты уже, что называется, из коробки
- Метрику удалось улучшить лишь на 0.01 при применении RandomForestClassifier и алгоритма optuna
- RandomForestClassifier в целом на тестовой выборки показывает лучнее показание f1

P.S. Лично мне понравился больше всего алгоритм optuna, очень понятный синтаксис, есть визуализация результатов, НАМНОГО быстрее чем какой нибудь GridSearch, есть можность задать гораздо больше параметров для поиска и при этом не умереть от старости.