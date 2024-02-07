# [Исследование текстов](https://github.com/observer012/yandex_practicum/blob/main/12.%20Машинное%20обучение%20для%20текстов%20(17)/Исследование%20текстов.ipynb)


## Описание проекта
### Данные

В распоряжении набор данных с разметкой о токсичности правок.

## Задача

Обучить модель классифицировать комментарии на позитивные и негативные.

## Что сделано

При ознакомление с данными выявлена необходимость в балансировке классов и предобработке текста. 
Проведена токенизация, лемматизация, частотный анализ. 
Признаки разделены на выборки, проведен ребаланс. Данные очищены от стоп слов и размечены. 
Обучены разные модели, использован автоматический подбор гиперпараметров. Выбрана лучшая модель. 
Проведено тестирование. 
Подготовлены выводы. 

## Навыки и инструменты
- IPython.**display**
- **pandas**
- matplotlib.**pyplot**
- **re**
- sklearn.pipeline.**Pipeline**
- sklearn.model_selection.
	- **train_test_split**, **GridSearchCV** 
- sklearn.utils.**shuffle**
- sklearn.metrics.
	- **f1_score**, **make_scorer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.feature_extraction.text.
	- **CountVectorizer**, **TfidfVectorizer**
- catboost.**CatBoostClassifier**
- **nltk**
- nltk.probability.**FreqDist**
- nltk.stem.**WordNetLemmatizer**
- nltk.corpus.
	- **wordnet**, **stopwords**
- **time**
- tqdm.
	- **notebook**, **tqdm**
- wordcloud.**WordCloud**

##

## Общий вывод

Обучена модель для классификации комментариев на позитивные и негативные. Точность метрики f1 удовлетворяет критерию заказчика.

<u>***Статус проекта: завершен.***</u>  


