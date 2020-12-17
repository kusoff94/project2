# Project 2

## Github Actions

Проект по knn на python состоит из 4 частей:
- distances.py
- nearest_neighbors.py
- classification.py
- model_selection.py

Каждый блок должен проходить тесты для него:
- test_distances.py
- test_nearest_neigbours.py
- test_classification.py
- test_model_selection.py


Workflow вызывается при запросе pull-request, который автоматически выполняет merge, если выполнены некоторые условия.
Если добавлен файл name.py, то запускается тест test_name.py. В случае успешного прохождения для всех добавленных файлов, автоматически происходит merge.
