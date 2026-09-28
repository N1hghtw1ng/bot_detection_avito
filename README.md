# Bot Detection Solution

## Ограничения
- Использованы только open-source библиотеки локально.
- Внешние API или большие языковые модели не применялись.
- Решение не предназначено для автоматической блокировки в production "как есть", а лишь максимизирует метрику `P@R>=0.7` на предоставленных тестовых данных.

## Воспроизводимость
Версия Python: `3.12`
Для установки зависимостей:
```bash
pip install -r requirements.txt
```

Использованные open-source библиотеки: `pandas`, `numpy`, `scikit-learn`, `lightgbm`.

## Запуск
Просто откройте `solution.ipynb` в Jupyter Notebook / JupyterLab / VSCode и выполните все ячейки. На выходе будет сформирован файл `submission.csv`.
