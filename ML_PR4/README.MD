# Практическая работа № 4. Регрессионная модель

**ФИО:** Твоё ФИО
**Группа:** Твоя группа
**Дата:** 02.10.2026

**Датасет:** Boston Housing
**Целевая:** MEDV — медианная стоимость домов (тыс. $)

## Что сделано

1. Split на train/test до любых fit.
2. ColumnTransformer для предобработки.
3. Базовая модель LinearRegression на всех признаках.
4. Проверка мультиколлинеарности (heatmap + VIF).
5. Сокращённая модель без RAD.
6. График остатков + гистограмма.
7. Обоснование финального набора.

## Метрики

| Модель | MAE | RMSE | R² |
|---|---|---|---|
| Базовая | 3.50 | 4.69 | 0.70 |
| Сокращённая | 3.52 | 4.71 | 0.69 |

## Как запустить

```bash
python -m venv .venv
.venv\Scripts\activate
pip install pandas numpy scikit-learn statsmodels jupyter matplotlib seaborn
jupyter notebook
