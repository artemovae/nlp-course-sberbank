# Автоматическая обработка текстов 

Екатерина Черняк 

email: echernyak@hse.ru

telegram: @echer


|                       | Лекции                                                                                                                                           | Практика                                                    | Домашнее  задание                                                   |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|---------------------------------------------------------------------|
| занятие 1 (14 марта)  | Введение: задачи автоматической обработки текстов и основные подходы к их решению. Токенизация, морфологический анализ.  | Регулярные выражения, лемматизация, POS-тэггинг | Описание прогноза погоды                                            |
| занятие 2 (21 марта)  | Синтаксический анализ. Векторная модель документа. Снижение размерности. Тематические модели.                                                                           | SOV-тройки, извлечение ключевых слов и словосочетаний, LSI, LDA                                               | Использование тематического моделирования для мягкой кластеризации  |
| занятие 3 (28 марта)  | Векторная модель слова. Дистрибутивная семантика                                                                                                 |  word2vec                                                   | Составление словаря эмоционально окрашенных слов                    |
| занятие 4 (4 апреля)  | Сети прямого распространения и сверточные нейронные сети. Их использование для классификации текстов, определения парафраза и извлечения отношений                                                        | Классификация новостей                                      | Предсказание цены акции по новостям                                 |
| занятие 5 (23 апреля) | Языковые модели: Марковские цепи, нейронные языковые модели, рекуррентные языковые модели.                                                       | Генерация текстов. Извлечение именованных сущностей.        | Классификация имен по полу                                          |
| занятие 6 (18 апреля) | Разное: определимся ближе к концу курса, что будет интереснее                                                                                    |                                                             |                                                                     |


## 14 марта

Данные к занятию: [dropbox](https://www.dropbox.com/sh/513tgmhz2ollna5/AAB6W-J3zwKDxKHSUnhjaYINa?dl=0)

Лекция и практика: intro.ipynb,  домашнее задание: hw1.ipynb

Необходимые библиотеки Python:
* nltk; после установки nltk необходимо из командной строки Python3 вызвать команды
```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```
* pymystem3
* pymorphy2
* matplotlib

Другое: 
* docker; после установки docker необходимо из командной строки вызвать команды
```
docker pull inemo/syntaxnet_rus
```


## 20 марта

Данные к занятию: [dropbox](https://www.dropbox.com/sh/513tgmhz2ollna5/AAB6W-J3zwKDxKHSUnhjaYINa?dl=0)

Лекция и практика: intro.ipynb, 2_VSM.ipynb

Необходимые библиотеки Python:
* natasha

Другое: 
* docker; после установки docker необходимо из командной строки вызвать команды
```
docker pull inemo/syntaxnet_rus
```


## 27 марта



Данные к занятию: [dropbox](https://www.dropbox.com/s/ksm21a8y6lgl511/all.txt.zip?dl=0)

Лекция и практика: 3_DS.pdf, 3_WMD.ipynb, 3_DSM.ipynb

Необходимые библиотеки Python:
* pydsm
* gensim

## 4 апреля

Данные к занятию: [dropbox](https://www.dropbox.com/sh/513tgmhz2ollna5/AAB6W-J3zwKDxKHSUnhjaYINa?dl=0)

Лекция и практика: 4_FNN_CNN.pdf, 4_RU_FNN_CNN.ipynb

Необходимые библиотеки Python:

* keras

## 23 апреля

Данные к занятию:  [dinos (dropbox)](https://www.dropbox.com/s/e0v7ex10s5kfu0y/dinos.txt?dl=0), [ner (dropbox)](https://www.dropbox.com/s/mijn5sf02oc9poc/ner.csv?dl=0)


Лекция и практика: 5_LM.ipynb, English_bilstm_NER.ipynb

Необходимые библиотеки Python:

* keras





## Рекомендуемые ресурсы
### На английском

* [Jurafsky & Martin](https://web.stanford.edu/~jurafsky/slp3/)
* [Курс Лауры Каллмайер по МО для NLP](https://user.phil.hhu.de/~kallmeyer/MachineLearning/index.html)
* [Курс Нильса Раймерса по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Оксфорде по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Стенфорде по DL для NLP](http://cs224d.stanford.edu)
* [Reinforcment Learning for NLP](https://github.com/jiyfeng/rl4nlp)


### На русском (и про русский, в основном)

* [НКРЯ](http://ruscorpora.ru)
* [Открытый корпус](http://opencorpora.org)
* [Дистрибутивные семантические модели для русского языка](http://rusvectores.org/ru/)
* [Морфология](https://tech.yandex.ru/mystem/)
* [Синтаксис](https://habrahabr.ru/post/317564/)
* [Томита-парсер](https://tech.yandex.ru/tomita/)
* [mathlingvo](http://mathlingvo.ru)
* [nlpub](https://nlpub.ru)
* [Text Visualisation browser](http://textvis.lnu.se)



## Литература

* Manning, Christopher D., and Hinrich Schütze. Foundations of statistical natural language processing. Vol. 999. Cambridge: MIT press, 1999.
* Martin, James H., and Daniel Jurafsky. "Speech and language processing." International Edition 710 (2000): 25.
* Cohen, Shay. "Bayesian analysis in natural language processing." Synthesis Lectures on Human Language Technologies 9, no. 2 (2016): 1-274.
* Goldberg, Yoav. "Neural Network Methods for Natural Language Processing." Synthesis Lectures on Human Language Technologies 10, no. 1 (2017): 1-309.
