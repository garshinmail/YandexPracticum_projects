# Защита персональных данных клиентов

## Описание проекта
Требуется создать метод шифрования данных, и проверить отсутствие его влияния на качество модели машинного обучения в дальнейшем

## Навыки и инструменты
* python
* pandas
* numpy
* math
* matplotlib
* sklearn:  r2_score

## Общий вывод

Для выполнения задачи шифрования таблицы признаков-личных данных для дальнейшего использования для предсказания получения страховых выплат применён алгоритм, который умножает исходные данные на матрицу-ключ, которая умножена на число, зависящее от даты.

Доказано, что при использовании модели Линейной регрессии, эти преобразования не оказывают влияния на качество предсказаний.


