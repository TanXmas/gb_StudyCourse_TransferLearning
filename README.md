# Transfer learning

## Семинар 1. Современный перенос обучения

### Практическое задание

1. Скачать нейросети ResNet и написать короткую процедуру для предсказания класса изображения.

2. Скачать нейросеть BERT для лингвистических задач и реализовать процедуру классификации текстов (без оглядки на качество классификации).

## Семинар 2. Representation learning

### Практическое задание

Заменить используемую сеть на менее "глубокую". \
Увеличить размер изображения, задав большее значение чем 256. \
Изменить соотношение стиля и контента. \
Сгенерировать стилизованное изображение, используя другие, выбранные вами изображения.  

Специальные требования:
1. Ноутбук должен выполняться в Colab или в локальном Jupyter нотбуке. Изображения должны быть приложены (например, вклеены в текутовую ячейку), либо должны быть даны ссылки на них (URL).
2. Если ноутбук выложен в Colab, не забудьте разрешить к нему доступ. Преподаватель готов подождать получения доступа, но, к сожалению, без доступа, задание будет считаться несданным.

Скрипт можно выполнять в Jupyter на собственном ПК (в том числе на CPU), а можно в Google Colab.

**Замечание**: Иллюстрации первой части ноутбука могут не открываться в Google Colab. И пока мы не оптимизировали ноутбук для Colab, вы можете прочитать теорию в приложенном HTML файле.

## Семинар 3. Model as a service и разные применения Transfer learning

### Практическое задание

Реализуйте классификацию эмоциональной окрашенности текстов при помощи объекта pipeline.

1. Найдите тип задач Sentiment Analysis на huggingface.co
2. Найдите модель для русского языка (примеры: rubert-tiny2..., rubert-base...)
