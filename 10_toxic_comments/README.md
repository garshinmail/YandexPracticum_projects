# Классификация текстов 

## Описание проекта
Необходимо построить модель бинарной классификации для текстов - комментариев онлайн магазина: токсичные и нетоксичные.

## Навыки и инструменты
* python
* pandas
* numpy
* nltk
* spacy
* re
* sklearn: Pipeline, TfidfVectorizer, RandomForestClassifier, LogisticRegression, GridSearchCV.
* torch
* transformers
  
## Общий вывод

Были опробованы два подхода решения задачи: через векторизацию методом tf-idf и при помощи предоубченной BERT-модели. Оба варианта оказались удовлетворительны в своём применении: tf-idf оказалась быстрее и проще, тогда как BERT - более тяжёлая обработка, но и качество выше. 
