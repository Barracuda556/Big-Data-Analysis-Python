# Введение в анализ больших данных (Python)

Лекционные материалы и задания по дисциплине **«Введение в анализ больших данных»**, адаптированные с языка R на **Python** (NumPy + SciPy + Pandas + Matplotlib + Seaborn).

## Содержание

### Лекция 1 — Создание объектов для хранения данных
Файл: [`Lecture_01_Data_Structures_Python.ipynb`](Lecture_01_Data_Structures_Python.ipynb)

Темы: векторы, DataFrame, матрицы, массивы, списки, факторы, фреймы данных.

### Лекция 2 — Вероятностные распределения
Файл: [`Lecture_02_Probability_Distributions_Python.ipynb`](Lecture_02_Probability_Distributions_Python.ipynb)

Темы: нормальное, равномерное, Стьюдента; генерация выборок, плотности, гистограммы.

### Лекция 3 — Описательные статистики
Файл: [`Lecture_03_Descriptive_Statistics_Python.ipynb`](Lecture_03_Descriptive_Statistics_Python.ipynb)

Темы: NMES1988, гистограмма + KDE, mean/SE, медиана, квартили, skewness/kurtosis, groupby, boxplot, barplot.

### Лекция 4 — Построение таблиц частот
Файл: [`Lecture_04_Frequency_Tables_Python.ipynb`](Lecture_04_Frequency_Tables_Python.ipynb)

Темы:
- `pd.cut()` — разбиение на категории (пятибалльная и европейская системы)
- Таблицы абсолютных и относительных частот (`value_counts`)
- Объединение таблиц (`pd.concat` ≈ `cbind`)
- Столбчатые диаграммы (stacked / grouped)
- Круговые диаграммы (`plt.pie`)

В тетрадях приведены:
- объяснения основных классов и методов;
- полное решение всех пунктов соответствующих заданий;
- шпаргалки R → Python.

## Как открыть

1. Скачайте `.ipynb` файл.
2. Откройте в Jupyter Notebook, JupyterLab, VS Code или Google Colab.
3. Убедитесь, что установлены библиотеки:
   ```bash
   pip install numpy scipy pandas matplotlib seaborn
   ```

## Репозиторий

https://github.com/Barracuda556/Big-Data-Analysis-Python
