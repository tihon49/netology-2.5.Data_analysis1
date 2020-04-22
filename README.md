# Домашнее задание к лекции 2.5 «Инструменты для оперативной работы с данными»

Решение выполнения задач необходимо предоставить в виде ссылки на файл формата Jupyter (ipynb) в GitHub.

В файле должны быть сохранены результаты запуска на тестовых данных.

Дано: данные о популярности имен для новорожденных, скачиваются по [ссылке](https://www.ssa.gov/oact/babynames/names.zip). Добавлять исходные данные в репозиторий с выполненным заданием необязательно, но в блокноте необходимо выделить путь к файлам в отдельную переменную, которую легко поменять.

## Задача №1
С использованием Pandas написать функцию, которая загружает указанные года и выводит ТОП-3 популярных имен. Например:

```python    
count_top3([1880]) == ['John', 'William', 'Mary']
count_top3([1900, 1950, 2000]) == ['James', 'John', 'Robert']
```      
    
## Задача №2
С использованием Pandas написать функцию, которая возвращает динамику изменения количества имен за указанные года в разрезе полов. Например:

```python      
count_dynamics([1900, 1950, 2000]) == {
  'F': [299810, 1713259, 1814922],
  'M': [150486, 1790871, 1962744]
}
```