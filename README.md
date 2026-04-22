# Лабораторная работа 1 *Вариант на тройку
## Обнаружение и распознавание объектов с использованием YOLOv11

В работе исследуется задача обнаружения объектов на датасете Safety Helmet Detection.
Были обучены baseline-модели YOLO11n и YOLO11s, проверены гипотезы улучшения baseline,
а также реализована собственная упрощённая модель SimpleCNN для классификации вырезанных объектов.

## Датасет

Используется датасет Safety Helmet Detection.
https://www.kaggle.com/datasets/andrewmvd/hard-hat-detection

`hard_hat_dataset.zip`

## Установка

```bash
git clone https://github.com/andruhaproger/cfs
cd cfs

python -m venv .venv

.venv\Scripts\Activate.ps1

python -m pip install -r requirements.txt

python -m pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu128
```

## Запуск

1. Скачать датасет Safety Helmet Detection с Kaggle.
2. Поместить архив `hard_hat_dataset.zip` в корень проекта.
3. Открыть `lab1.ipynb` в VS Code.
4. Последовательно выполнить все ячейки ноутбука.
5. Для обучения на GPU использовать окружение с CUDA-версией PyTorch. (PyTorch устанавливается отдельно, так как для локального запуска на GPU требуется CUDA-совместимая сборка.)
