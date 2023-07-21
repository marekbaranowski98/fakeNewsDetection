# AI system that classifies press releases as genuine or fake news
Code from my master's thesis AI system that classifies press releases as genuine or fake news.

As part of the work, a collection of articles was found, which were classified as either fake news or true. The found collection underwent preliminary processing, removing empty articles. The prepared dataset consists of 35028 true articles and 37106 false articles. To train the models, it was divided into smaller subsets (training, validation, and testing). Two network models were then prepared, the first one based on the RNN architecture was trained from scratch using the previously prepared dataset. The second model was prepared using transfer learning technique, relying on the pre-trained BERT model, which is based on the transformer architecture. These trained models were evaluated on the test set, measuring their accuracy. The RNN-based model achieved an accuracy level of 97%, while the BERT-based model achieved an accuracy level of 99,5%.

# System AI klasyfikujący wiadomości prasowe jako wiarygodne lub fake news
Kod pochodzi z mojej pracy magisterskiej "System AI klasyfikujący wiadomości prasowe jako wiarygodne lub fake news".

W ramach pracy znaleziono zbiór artykułów, które zostały sklasyfikowane jako fake news albo prawdziwe. Znaleziony zbiór poddano wstępnej obróbce, usuwając puste artykuły. Tak przygotowany zbiór składa się z 35028 artykułów prawdziwych i 37106 fałszywych. Do wytrenowania modeli został on podzielony na mniejsze podzbiory (treningowy, walidacyjny oraz testowy). Następnie przygotowano 2 modele sieci, pierwszy oparty o architekturę RNN został wytrenowany od początku tylko z użyciem wcześniej przygotowanego zbioru. Drugi model został przygotowany z wykorzystaniem techniki transfer learning, opierając się o wytrenowany model BERT, który jest oparty o architekturę transformer. Tak wytrenowane modele zostały sprawdzone na zbiorze testowym, mierząc ich dokładność. Model oparty o architekturę RNN osiągnął dokładność na poziomie 97%, a model oparty o model BERT osiągnął wynik accuracy na poziomie 99,5%.
