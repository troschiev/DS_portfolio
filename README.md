# Intro

Here I post projects with something interesting and useful.

Each project is a .ipynb file with:

- formally set task
- EDA
- working code
- text explanations
- visualized results
- conclusions and / or plans for improving the result

# Large projects

<table>
  <tr>
    <th>Project</th>
    <th>Methods</th>
    <th>Stack</th>
  </tr>

<tr>
    <td><a href=
"https://github.com/troschiev/Face_Recognition_Pipeline"
>Full face recognition pipeline</a></td>
    <td>Face detection (YOLO), face landmarks coordinates regression, face alignment, face embedding DNN, cos similarity analysis, telegram bot implementation</td>
    <td>python, pytorch, albumentations, timm, aiogram, cv2</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/DCGAN_Faces"
>DCGAN for face generation</a></td>
    <td>Hand-made DCGAN, custom Gauss noise layers, gradien penalty, regularization by labels (soft, noise, flip), 
specific metrics: Fréchet inception distance и Leave-one-out-1-NN classification, epoch animation</td>
    <td>python, pytorch, matplotlib, albumentations, timm</td>
  </tr>

</table>

# Selected study projects
 
<table>
  <tr>
    <th>Project</th>
    <th>Methods</th>
    <th>Stack</th>
  </tr>

<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/Age_Regression_Photo"
>Person Age by Photo</a><br>Yandex Practicum</td>
    <td>EffecientNet V2 pretrained, strong augmentation, result analysis</td>
    <td>python, pytorch, matplotlib, albumentations, timm, альтернативный код в keras</td>
  </tr>
  <tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/Image_Autoencoders"
>Image Autoencoders</a><br>DL school MIPT</td>
    <td>CNN, latent vectors, latent space sampling, VAE, Conditional VAE, KL divergence loss</td>
    <td>python, pytorch, sklearn, matplotlib</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/BERT_Text_Classifiaction"
>Toxic Comment Classification</a><br>Yandex Practicum</td>
    <td>Text preprocessing, TF-IDF, lemmatization, word2vec, fine-tuned BERT, weighted loss</td>
    <td>python, pandas, numpy, pytorch, BERT, sklearn, optuna, matplotlib, seaborn, wordcloud, nltk, enchant, spacy, gensim</td>
  </tr>
  <tr>
  <tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/Semantic_Segmentation_Skin_Lesions"
>Semantic Segmentation of Skin Lesions</a><br>DL school MIPT</td>
    <td>CNN, hand-made Unet и SegNet (based on VGG16), image augmentations, custom loss functions</td>
    <td>python, pytorch, sklearn, albumentations, matplotlib</td>
  </tr>
  <tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Gold_Ore_Extraction_Efficiency"
>Gold Recovery Efficiency Model</a><br>Yandex Practicum</td>
    <td>EDA, preprocessing, feature selection by phik correlation, feature dimensionality reduction, gradient boosting, hyperparameter tuning</td>
    <td>python, pandas, seaborn, sklearn, pipeline, optuna, phik, xgboost</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Simpsons_Classification"
>Simpsons Classification</a><br>DL school MIPT</td>
    <td>CNN, transfer learning, image augmentation, class imbalance, extended result visualization</td>
    <td>python, pytorch, sklearn, matplotlib</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Taxi_Demand_Time_Series"
>Taxi Demand Time Series</a><br>Yandex Practicum</td>
    <td>Exponential smoothing, SARIMA, linear regression, gradient boosting, hybrid boosting, hyperparameter tuning, neural networks: dense, LSTM</td>
    <td>python, pandas, numpy, seaborn, sklearn, pipeline, statsmodels, pytorch, lightgbm, optuna, prophet, phik, pmdarima</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Used_Cars_Price_Prediction"
>Used Car Price Prediction</a><br>Yandex Practicum</td>
    <td>EDA, deep preprocessing, feature selection, gradient boosting, hyperparameter tuning, fully connected neural network, residual analysis, postcode coordinates, feature importance (permutation)</td>
    <td>python, pandas, numpy, seaborn, sklearn, pipeline, pytorch, lightgbm, xgboost, catboost, optuna, phik</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Bank_Churn_Prediction"
>Bank Customer Churn</a><br>Yandex Practicum</td>
    <td>Class imbalance, T-SNE visualization, gradient boosting, hyperparameter tuning, cross-validation ROC curves, feature engineering, wrapper class, stacking, feature importance (permutation)</td>
    <td>python, pandas, numpy, seaborn, sklearn, pipeline, lightgbm, xgboost, optuna,</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Titanic_Kaggle"
>Titanic Analysis</a><br>Kaggle</td>
    <td>Advanced analysis, advanced visualization, gradient boosting, hyperparameter tuning</td>
    <td>python, pandas, numpy, seaborn, plotly, sklearn, catboost, optuna,</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Oil_Deposits"
>Selecting Oil Well Location</a><br>Yandex Practicum</td>
    <td>Synthetic data, bootstrap, QQ-plot, confidence intervals</td>
    <td>python, pandas, numpy, seaborn, sklearn, pipeline</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/tree/main/Video_Games_Market_Analysis"
>Video Game Market Analysis</a><br>Yandex Practicum</td>
    <td>Deep data analysis, advanced visualization, hypothesis testing</td>
    <td>python, pandas, numpy, seaborn, plotly, scipy</td>
  </tr>
<tr>
    <td><a href=
"https://github.com/troschiev/DS_portfolio/blob/main/Cell_Tarif_Classification"
>Tariff Recommendation for a Mobile Operator Client</a><br>Yandex Practicum</td>
    <td>Classic ML models: logistic regression with feature engineering, SVM, naive Bayes classifier, decision trees, random forest, gradient boosting, model stacking</td>
    <td>python, pandas, sklearn, numpy, seaborn, xgboost</td>
  </tr>
</table>

# Contacts

E-mail: [sergey.troschiev@gmail.com](mailto:sergey.troschiev@gmail.com)

Telegram: [https://t.me/sergey_doc](https://t.me/sergey_doc)