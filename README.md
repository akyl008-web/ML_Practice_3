# Практическая работа №3 — Pipeline и предобработка данных

**Студент:** Ашымбеков Акыл  
**Дисциплина:** Машинное обучение  
**Датасет:** Titanic

## Что сделано

- Train/test split со стратификацией
- SimpleImputer (медиана / Unknown)
- OneHotEncoder и StandardScaler
- ColumnTransformer и Pipeline
- Защита от data leakage
- Проверка размерности Train и Test

## Основные результаты

- Train: 712 × 13, Test: 179 × 13
- Пропусков после обработки нет

## Структура проекта

```text
Titanic_Practice_3/
├── data/
│   └── titanic.csv
├── notebooks/
│   └── practice_3.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Как запустить

1. Создать и активировать виртуальное окружение:

```bash
python3 -m venv venv
source venv/bin/activate
```

2. Установить библиотеки:

```bash
pip install -r requirements.txt
```

3. Открыть `notebooks/practice_3.ipynb` в VS Code или Jupyter и выполнить **Restart & Run All**.

## Технологии

Python, pandas, NumPy, matplotlib, seaborn, scikit-learn, Jupyter Notebook.
