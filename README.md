# Тестовое задание на VKLab

Обучение легковесного классификатора на токсичных комментариях. 
Датасет взят из соревнования [kaggle](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview). В качестве нижней оценки качества используется Tf-Idf с логистической регрессией. Уменьшалась attention-based нейронная сеть. Результат: получилось сделать неплохой классификатор.

## Описание файлов
- Report.md - отчет о проделанной работе
- BPE_10000.model - BPE encoder
- train.csv - датасет для обучения
- LookAtData.ipynb - первичный осмотр данных
- baseline.ipynb - простая модель для нижней оценки качества
- BaseAttention.ipynb - модель №1
- BestResult.ipynb - модель №2

Для запуска 2 модели требуется предварительно загруженный [Glove](https://nlp.stanford.edu/projects/glove/) на 6B токенов.  