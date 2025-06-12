# Курсовая работа на тему: "Прогнозирование эффективности химических соединений на основе молекулярных дескрипторов"

## Описание проекта
Проект направлен на анализ и прогнозирование ключевых параметров эффективности лекарственных соединений:
- **IC50** - полумаксимальная ингибирующая концентрация
- **CC50** - цитотоксическая концентрация
- **SI (Selectivity Index)** - индекс селективности

  ## 🎯 Поставленные задачи

### Регрессионные модели
1. Прогнозирование IC50
2. Прогнозирование CC50 
3. Прогнозирование SI (Selectivity Index)

### Классификационные модели
1. Превышает ли IC50 медианное значение
2. Превышает ли CC50 медианное значение  
3. Превышает ли SI медианное значение
4. Превышает ли SI порог 8.0

## 🔧 Используемый стек технологий
- Python 3.9+
- Библиотеки:
  - Pandas, NumPy - обработка данных
  - Scikit-learn - машинное обучение
  - XGBoost, CatBoost - ансамблевые методы
  - Matplotlib, Seaborn - визуализация
  - Jupyter - интерактивный анализ

## 📊 Ключевые результаты
1. **Лучшие модели**:
   - Для регрессии: Оптимизированный XGBoost (RMSE=1.39, R²=0.47)
   - Для классификации: Random Forest (F1=0.82)

2. **Основные выводы**:
   - Наибольшая предсказательная сила для пары IC50-CC50
   - SI слабо коррелирует с имеющимися признаками
   - Топологические индексы - наиболее информативные признаки

## 🚀 Как использовать
1. Клонировать репозиторий:
```bash
git clone https://github.com/CrimsonFox-hub/course_work_1_cource.git
```
## 🔗 Ссылки на реализацию

### 📊 Основные аналитические ноутбуки:
- [Первичный анализ данных (EDA)](https://github.com/CrimsonFox-hub/course_work_1_cource/blob/main/cw_EDA.ipynb)

### 📈 Регрессионные модели:
- [Прогнозирование IC50](https://github.com/CrimsonFox-hub/course_work_1_cource/blob/main/ic50_regression.ipynb)
- [Прогнозирование CC50](https://github.com/CrimsonFox-hub/course_work_1_cource/blob/main/cc50_regression.ipynb) 
- [Прогнозирование SI (Selectivity Index)](https://github.com/CrimsonFox-hub/course_work_1_cource/blob/main/SI_regression.ipynb)

### 🏷 Классификационные модели:
- [Классификация IC50 (медианный порог)](https://github.com/CrimsonFox-hub/course_work_1_cource/blob/main/IC50_median.ipynb)
- [Классификация CC50 (медианный порог)](https://github.com/CrimsonFox-hub/course_work_1_cource/blob/main/CC50_median.ipynb)
- [Классификация SI (медианный порог)](https://github.com/CrimsonFox-hub/course_work_1_cource/blob/main/SI_median.ipynb)
- [Классификация SI (порог 8.0)](https://github.com/CrimsonFox-hub/course_work_1_cource/blob/main/SI_8.ipynb)

### 📂 Полный список файлов:
[Все ноутбуки проекта](https://github.com/CrimsonFox-hub/course_work_1_cource/blob/main/)
