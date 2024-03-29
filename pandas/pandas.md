# Основы Pandas

Импортировать библиотеку `pandas`
```python
import pandas as pd
```

Прочитать CSV файл с именем `titanic.csv` (если он находится в текущем каталоге), полученный датафрейм присвоить переменной `df`
```python
df = pd.read_csv("titanic.csv")
```

Вывести первые 5 строк датафрейма (метод `.head()`)
```python
df.head()
```

Методу `.head()` можно передать необязательный позиционный аргумент - целое число. В этом случае будет получено указанное число строк
```python
# указанный ниже код позволяет получить 
# 8 первых строк датайфрейма df
df.head(8)
```

Метод `.tail()` используется аналогично `.head()`, но позволяет получить последние 5 строк либо указанное число строк.
```python
# указанный ниже код позволяет получить 
# 3 последних строки датайфрейма df
df.tail(3)
```

Метод `.sample()` позволяет получить 1 случайную строку из датафрейма либо указанное число случайных строк
```python
# указанный ниже код позволяет получить 
# 4 случайных строки датайфрейма df
df.sample(4)
```