# Введение

Здесь я размещаю свои лучшие проекты, в которых реализовал что-то интересное и полезное.

Каждый проект - ноутбук, в котором:
- поставлена задача
- сделан хотя бы минимальный EDA
- написан, отлажен и запущен код
- подробно описаны и обоснованы мои действия
- визуализированы результаты
- сделано разбиение по разделам
- написаны выводы и/или планы по улучшению результата

# Пет-проекты

<table>
  <tr>
    <th>Проект</th>
    <th>Методы</th>
    <th>Технологии</th>
  </tr>

<tr>
    <td><a href=
"https://github.com/troschiev/Face_Recognition_Pipeline"
>Full face recognition pipeline</a></td>
    <td>Face detection (YOLO), face landmarks coordinates regression, face alignment, face embedding DNN, cos similarity analysis, telegram bot implementation</td>
    <td>python, pytorch, albumentations, timm, aiogram, cv2</td>
  </tr>
</table>

# Избранные учебные проекты
 
<table>
  <tr>
    <th>Проект</th>
    <th>Методы</th>
    <th>Технологии</th>
  </tr>

<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/DCGAN_Faces"
>DCGAN для генерации лиц</a><br>DL school МФТИ</td>
    <td>DCGAN вручную, кастомные слои гауссовского шума, gradien penalty, регуляризация за счет работы с лейблами (soft, noise, flip), 
специфические метрики: Fréchet inception distance и Leave-one-out-1-NN классификация, анимация по эпохам</td>
    <td>python, pytorch, matplotlib, albumentations, timm</td>
  </tr>

<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/Age_Regression_Photo"
>Определение возраста человека по фотографии</a><br>Я.Практикум</td>
    <td>EffecientNet V2 pretrained, сильная аугментация, анализ ошибок</td>
    <td>python, pytorch, matplotlib, albumentations, timm, альтернативный код в keras</td>
  </tr>
  <tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/Image_Autoencoders"
>Автоэнкодеры изображений</a><br>DL school МФТИ</td>
    <td>Сверточные нейронные сети, латентные векторы, сэмплирование из латентного пространства, вариационный автоэнкодер, Conditional VAE, лосс на основе KL divergence</td>
    <td>python, pytorch, sklearn, matplotlib</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/BERT_Text_Classifiaction"
>Идентификация токсичных комментариев</a><br>Я.Практикум</td>
    <td>Очистка текста, TF-IDF, лемматизация, word2vec, fine-tuned BERT, взвешенная функция потерь</td>
    <td>python, pandas, numpy, pytorch, BERT, sklearn, optuna, matplotlib, seaborn, wordcloud, nltk, enchant, spacy, gensim</td>
  </tr>
  <tr>
  <tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/Semantic_Segmentation_Skin_Lesions"
>Сегментация изображений дефектов кожи</a><br>DL school МФТИ</td>
    <td>Сверточные нейронные сети, ручная реализация Unet и SegNet (на базе предобученной VGG16), аугментация изображений, custom loss functions</td>
    <td>python, pytorch, sklearn, albumentations, matplotlib</td>
  </tr>
  <tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Gold_Ore_Extraction_Efficiency"
>Восстановление золота из руды</a><br>Я.Практикум</td>
    <td>EDA, предобработка, выбор фич на основе корреляции phik, снижение размерности пространства фич методом PCA, градиентный бустинг, подбор гиперпараметров</td>
    <td>python, pandas, seaborn, sklearn, pipeline, optuna, phik, xgboost</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Simpsons_Classification"
>Классификация изображений Симпсонов</a><br>DL school МФТИ</td>
    <td>Сверточные нейронные сети, transfer learning, аугментация изображений, дисбаланс классов, расширенная визуализация результатов</td>
    <td>python, pytorch, sklearn, matplotlib</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Taxi_Demand_Time_Series"
>Прогнозирование заказов такси</a><br>Я.Практикум</td>
    <td>Экспоненциальное сглаживание, SARIMA, линейная регрессия, градиентный бустинг, гибридный бустинг, подбор гиперпараметров, нейросети: dense, LSTM</td>
    <td>python, pandas, numpy, seaborn, sklearn, pipeline, statsmodels, pytorch, lightgbm, optuna, prophet, phik, pmdarima</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Used_Cars_Price_Prediction"
>Определение стоимости автомобилей</a><br>Я.Практикум</td>
    <td>EDA, глубокая предобработка, отбор фич, градиентный бустинг, подбор гиперпараметров, полносвязная нейронная сеть, анализ остатков, определение координат по почтовым индексам, важность признаков (пермутация)</td>
    <td>python, pandas, numpy, seaborn, sklearn, pipeline, pytorch, lightgbm, xgboost, catboost, optuna, phik</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Bank_Churn_Prediction"
>Отток клиентов банка</a><br>Я.Практикум</td>
    <td>Дисбаланс классов, визуализация TSNE, градиентный бустинг, подбор гиперпараметров, ROC-кривые на кросс-валидации, инжиниринг признаков, класс-обертка, стекинг, важность признаков (пермутация)</td>
    <td>python, pandas, numpy, seaborn, sklearn, pipeline, lightgbm, xgboost, optuna,</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Titanic_Kaggle"
>Выжившие на Титанике (eng)</a><br>Kaggle</td>
    <td>Расширенный анализ, расширенная визуализация, градиентный бустинг, подбор гиперпараметров</td>
    <td>python, pandas, numpy, seaborn, plotly, sklearn, catboost, optuna,</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Oil_Deposits"
>Выбор локации нефтяной скважины</a><br>Я.Практикум</td>
    <td>Синтетические данные, bootstrap, QQ-plot, доверительные интервалы</td>
    <td>python, pandas, numpy, seaborn, sklearn, pipeline</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/Video_Games_Market_Analysis"
>Анализ рынка видеоигр</a><br>Я.Практикум</td>
    <td>Глубокий анализ данных, продвинутая визуализация, проверка гипотез</td>
    <td>python, pandas, numpy, seaborn, plotly, scipy</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Personal_Data_Encoding"
>Защита персональных данных клиентов</a><br>Я.Практикум</td>
    <td>Линейная алгебра, линейная регрессия</td>
    <td>python, pandas, numpy, seaborn, sklearn</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Cell_Tarif_Classification"
>Рекомендация тарифа клиенту мобильного оператора</a><br>Я.Практикум</td>
    <td>Классические модели машинного обучения: логистичесая регрессия с инжинирингом признаков, SVM, наивный байесовский классфикатор, решающие деревья, случайный лес, градиентный бустинг, стекинг моделей</td>
    <td>python, pandas, sklearn, numpy, seaborn, xgboost</td>
  </tr>
</table>

# Контакты

Связаться со мной можно по почте [sergey.troschiev@gmail.com](mailto:sergey.troschiev@gmail.com) и через телеграм: https://t.me/sergey_doc