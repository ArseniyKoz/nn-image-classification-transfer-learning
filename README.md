# Классификация изображений и transfer learning

Pet-проект по компьютерному зрению: аугментации, семплирование и дообучение готовых CNN.

## Что сделано

- Аугментация изображений через torchvision.transforms.
- Подготовка train/valid/test загрузчиков.
- Эксперименты с предобученными архитектурами (ResNet/EfficientNet).

## Стек

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

## Как запустить

`ash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook nn_practice_2.ipynb
```

## Результаты

Подготовлен воспроизводимый шаблон обучения CNN с transfer learning для задач классификации.

## Чему научился

- Настраивать пайплайн аугментаций под качество и скорость.
- Адаптировать предобученные модели под новую задачу.

## Ограничения и что улучшить

- Добавить tracking метрик по эпохам и confusion matrix по классам.

## Автор

Арсений Козлов - [github.com/ArseniyKoz](https://github.com/ArseniyKoz)

