# Awesome ML
В рамках выполнения данной лабораторной работы вам предстоит выполнить следющие задачи:
1. Научиться работать с Jupyter Notebook
2. Проанализировать датасет при помощи Pandas
3. Представить результаты анализа пр  помощи Mathplotlib
4. Создать классификатор на базе деревьев принятий решений
4. Создать SVM-классификатор
6. Классификатор на базе нейронной сети

## Подготовка окружения
работу рекомендуется выполнять в отдельном python окружении на python3.8 и выше
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter lab
```
Всю работу можно выполнить в jupyter notebook

## Изучение датасета
1. Запустить Jupyter Notebook
2. Загрузить датасет titanic_train.csv в [Pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html) DataFrame, после чего подготовить ответы 
на следующие вопросы:
   1. Какой процент женщин и мужчин выжили?
   2. Какой процент пассажиров в каждом классе выжил?
   3. Сколько было пассажиров, для которых не  указан номер  кабины?
   4. Построить график распределения числа пассажиров в зависимости от возраста при помощи библиотеки mathplotlib
4. Сделать предположение: какие столбцы сильнее всего влияют на выживаемость пассажира

## Деревья принятий решений
1. При помощи sklearn [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) построить классификатор 
на основе столбцов, полученных в результате анализа датасета
2. При помощи полностью размеченного датасета titanic_test_augmented.csv получить [метрики](https://habr.com/ru/companies/ods/articles/328372/) 
(Accuracy, Precition, Recall), полученного классификатора
3. Вывести результаты в Jupyter Notebook

## SVM
1. При помощи sklearn [svm](https://scikit-learn.org/stable/modules/svm.html) построить разделющую плоскость
2. Обучить SVM
3. Получить метрики Accuracy, Precition, Recall при помощи размеченного датасета
4. Вывести результаты в Jupyter Notebook

## Нейронная сеть
1. Создать нейронную сеть (в комментарии в Jupyter обосновать выбранную архитектуру сети) при помощи библиотеки [keras](https://keras.io/examples/vision/mnist_convnet/) (Хотя это не панацея - можете выбрать любой современный фремворк: Pytorch, Tensorflow и т.д.)
2. Обучить нейронную сеть
3. Получить метрики Accuracy, Precition, Recall при помощи размеченного датасета
4. Вывести результаты в Jupyter Notebook

## Сдача работы
1. Вся работа оформляется в виде Jupyter notebook, под каждый раздел которого должен быть комментарий
2. На сдачу приходим с Notebok с готовыми резудьтатами