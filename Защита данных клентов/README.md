# Описание проекта

Необходимо защитить данные клиентов страховой компании «Хоть потоп». Разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обосновать корректность его работы.

Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. 

## Используемый стек

- Python
- Pandas
- Sklearn
- Numpy

# Вывод

В результате исследования было доказано что можно зашифровать данные клиентов при умножении исходной матрицы признаков на обратимую матрицу.

Качество линейной регресии не изменилось от использования исxодных данных и данных, умноженных на обратимую матрицу.

# Статус

Проект завершён.
