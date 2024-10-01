# Проект классификации данных

Этот проект направлен на классификацию данных с использованием демографического набора данных взрослых для предсказания уровня доходов. Анализ включает в себя этапы разведочного анализа данных (EDA) и обучения моделей.

## Структура 

- **Разведочный анализ данных (EDA)**: На начальном этапе загружается и визуализируется набор данных для понимания его структуры и связей между переменными.
- **Предобработка данных**: Обрабатываются пропуски в данных и удаляются нерелевантные столбцы перед обучением моделей.
- **Обучение моделей**: Применяются различные модели машинного обучения для классификации людей на основе их демографических характеристик.

## Набор данных

Набор данных включает информацию о демографии взрослых, такую как:
- Возраст
- Класс работы
- Уровень образования
- Семейное положение
- Профессия
- Раса
- Пол
- Количество рабочих часов в неделю
- Страна происхождения
- Категория дохода (`<=50K` или `>50K`)

Данные загружаются из файла CSV под названием `DatasetAdults.csv`.

## Необходимые библиотеки

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

## Использование

1. Клонируйте репозиторий.
2. Установите необходимые библиотеки.
3. Запустите Jupyter Notebook для просмотра полного анализа.