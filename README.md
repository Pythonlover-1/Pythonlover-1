<h1 align="center">Приветствую 👋</h1>
<h3 align="center">Я Петухов Дмитрий, студент 3-го курса кафедры Компьютерных технологий университета ИТМО</h3>

# Учебные проекты

## [Интерпретатор Python на Python](https://github.com/Pythonlover-1/python-vm)
В этом задании было необходимо написать интерпретатор байткода python на языке python
Сложность этого задания состояла в том, чтобы разобраться в документации (которая не везде была корректно написана). Наибольшую трудность для меня представила поддержка генераторов в языке.

## [Текстовое ранжирование](https://github.com/Pythonlover-1/text-ranking)
В этом задании я реализовал алгоритм текствого ранжирования BM25F и занял первое место в публичном лидерборде на kaagle. Для более выского результата и использовал [pymorphy3](https://pypi.org/project/pymorphy3/), чтобы учитывать морфологию языка.

## ML-проекты
### [kNN](https://github.com/Pythonlover-1/kNN-implementation)
Реализация алгоритма ближайших соседей. Алгоритм запускался на данных, собранных [собственным парсером](https://github.com/Pythonlover-1/transfermarkt-parser) с сайта [transfermarkt](https://www.transfermarkt.com). С помощью kNN я пытался по цене футболистов и их игровой статистике за сезон предсказать их позицию на поле. 

### [Линейные методы](https://github.com/Pythonlover-1/linear-methods)
В этом задании я реализовал линейную регресию в матричном виде и два алгоритма линейной классификации. С помощью классификатора я пытался предсказать, по данным пациента, болен ли он сахарным диабетом или нет. [Датасет](https://www.kaggle.com/datasets/mathchi/diabetes-data-set) был взят из данных [Национального института диабета, заболеваний органов пищеварения и почек](http://niddk.nih.gov).

### Деревья решений и ансамбли
В этом задании я реализовал простейшее дерево принятий решений и сравнил его с реализаций из sklearn. Также мной были написаны градиентный бустинг и случайный лес. Это задание мне особенно понравилось, поскольку разбираться в идее бустинга было очень интересно.

## DL-проекты

### Реализация собственной нейронной сети на Numpy
В этом задании я реализовал прямые и обратные проходы для таких слоёв как ReLu, SoftMax, Dense, Conv2D, Pooling, Dropout, BatchNorm. Все слои были реализованы на чистом Numpy, без использования torch'а. Затем, используя сделанные мной слои, я реализовал простой персептрон для классификации цифр из датасета MNIST (получив точность >90%), и небольшую сетку для классификации картинок из датасета CIFAR-10 (получив точность >70%).

### Точки лица
В этом задании я сделал собственную архитектуру с ResNet-конфигурацией. Полученная сетка решала задачу регрессии для расположения точек лица (нос, глаза, губы и т.д.) -- всего предсказывалось 28 точек. Мне удалось выбить 7.0 по метрике MSE на валидации (и 4.0 на тесте).

### Детектор машин
Имея обученный классификатор, мне нужно было сделать из него детектор. Чтобы выполнить задание, я заменил полносвязные слои классификатора на свёрточные слои, получив полносвёрточную нейронную сеть, которая выдаёт "уверенность" в том, что в области есть автомобиль. Затем я использовал алгоритм подавления немаксимумов, чтобы улучшить качество детектора (качество детектора оценивалось с помощью меры IoU).

<h3 align="left">Языки и инструменты:</h3>
<p align="left"> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://cassandra.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_cassandra/apache_cassandra-icon.svg" alt="cassandra" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://grafana.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" alt="grafana" width="40" height="40"/> </a> <a href="https://www.haskell.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Haskell-Logo.svg" alt="haskell" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://opencv.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/> </a> <a href="https://www.oracle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://redis.io" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> </p>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=pythonlover-1&show_icons=true&locale=en&layout=compact" alt="pythonlover-1" /></p>
