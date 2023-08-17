# Определение токсичных комментариев

**Цель проекта:** построение модели машинного обучения для определения токсичости комментариев

Предоставлены тексты англоязычных комментариев.

В проекте был применен следующий стек:
- Pandas
- Matplotlib, Seaborn
- Numpy
- nltk.tokenize, nltk.stem
- Spacy
- Sklearn
- Lightgbm, Catboost


 **Вывод:**

Обучены три разные модели (LogisticRegression, RandomForestClassifier, CatBoostClassifier) Согласно метрике F1 лучше всего себя показала модель LogisticRegression с векторизацией данных TF-IDF:: F1 = 0.766 на обучающей выборке, и F1=0.776 на тестовой выборке. 