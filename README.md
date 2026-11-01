## Описание
Репозиторий с домашними заданиями по курсу **Machine Learning**.  
Каждое задание оформлено в виде отдельного Jupyter Notebook, каждый из которых содержит эксперименты и выводы.

## Содержание

| Ноутбук | Тема |
|---------|------|
| `lab_1.ipynb` | Очистка и визуализация сырых данных.
| `lab_2.ipynb` | Перцептрон. Функции активации.
| `lab_3.ipynb` | Нейронная сеть.
| `lab_4.ipynb` | Оптимизацторы.
| `lab_5.ipynb` | Классификация изображений.
| `lab_6.ipynb` | RNN.

## Запуск

1. Клонировать репозиторий
```bash
git clone https://github.com/laxlite/ML.git
cd ML
```

2. Окружение и зависимости 

```bash
python -m venv .venv
source .venv/bin/activate        # Linux / macOS
# .venv\Scripts\activate         # Windows

pip install -r requirements.txt
```

3. Запустить Jupyter

```bash
jupyter notebook
# или
jupyter lab
```

## Стек

- Язык программирования: Python 3.12
- Среда написания и запуска кода: Jupyter Notebook
- Библиотеки для работы с большими данными: NumPy, pandas, Matplotlib, Seaborn, scikit-learn
- Библиотеки для работы с нейронными сетями: TensorFlow
