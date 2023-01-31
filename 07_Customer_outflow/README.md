# Отток клиентов
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 

## Описание признаков
Признаки
- RowNumber — индекс строки в данных
- CustomerId — уникальный идентификатор клиента
- Surname — фамилия
- CreditScore — кредитный рейтинг
- Geography — страна проживания
- Gender — пол
- Age — возраст
- Tenure — сколько лет человек является клиентом банка
- Balance — баланс на счёте
- NumOfProducts — количество продуктов банка, используемых клиентом
- HasCrCard — наличие кредитной карты
- IsActiveMember — активность клиента
- EstimatedSalary — предполагаемая зарплата

Целевой признак
- Exited — факт ухода клиента

## Используемые инструменты

`pandas` `numpy` `matplotlib` `math` `missingno` `random` `seaborn`

### Используемые модели

`DecisionTreeClassifier` `LogisticRegression` `RandomForestClassifier`

### Дополнительные инструменты

`train_test_split` `StandardScaler` `shuffle` `OneHotEncoder`

### Метрики
`accuracy_score` `confusion_matrix` `recall_score` `precision_score` `f1_score` `roc_auc_score` `roc_curve` 

