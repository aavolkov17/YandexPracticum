## Задача проекта

Разработать алгоритм анонимизации персональных данных

## Описание задачи

Необходимо защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно 
восстановить персональную информацию. Обоснуйте корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей 
машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.

## Навыки и инструменты
- python
- pandas
- numpy
- scikit-learn

## Вывод

Алгоритм шифрования заключается в умножении матрицы признаков на случайную обратимую матрицу.

При данном алгоритме качество Линейной Регрессии не изменяется.
