## Результаты модели
| Метрика | Значение |
|---------|----------|
| Accuracy | 0.78 |
| Precision (Churn=Yes) | 0.59 |
| Recall (Churn=Yes) | 0.53 |
| F1-score (Churn=Yes) | 0.56 |
| ROC-AUC | 0.83 |

## Визуализация
![Отток по контрактам](images/contract_churn.png)
![Тепловая карта](images/contract_internet_heatmap.png)
![Влияние сервисов](images/services_churn.png)
![Оплата и отток](images/payment_churn.png)
![Срок и чек](images/tenure_charges_boxplot.png)
## Интерактивные графики (Plotly)
- [Отток по контрактам](https://htmlpreview.github.io/?https://raw.githubusercontent.com/f1retruckthepudge-prog/telco-churn-analysis/master/images/contract_churn_interactive.html)
- [Тепловая карта (контракт × интернет)](https://htmlpreview.github.io/?https://raw.githubusercontent.com/f1retruckthepudge-prog/telco-churn-analysis/master/images/contract_internet_heatmap_interactive.html)
- [Срок жизни и ежемесячный платёж](https://htmlpreview.github.io/?https://raw.githubusercontent.com/f1retruckthepudge-prog/telco-churn-analysis/master/images/tenure_charges_scatter.html)

- ## Python (Streamlit) Interactive Dashboard
[Смотреть код дашборда](churn_dashboard.py)  
*Локальный запуск:* `streamlit run churn_dashboard.py`
