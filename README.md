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
cd cps-lab1-cv-hardhat-yolo

python -m venv .venv

.venv\Scripts\Activate.ps1

python -m pip install -r requirements.txt

python -m pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu128
```

