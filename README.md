## Домашнее задание 2. Блок ML Ops

До начала сборки сервиса добавьте папку train_data в папку fraud_detector и загрузите в добавленную папку файл *train.csv* из соревнования --- https://www.kaggle.com/competitions/teta-ml-1-2025/data. Он необходим для работы энкодера.

### Запуск
```bash
git clone https://github.com/aminovrustam/ml_ops_hw2.git
cd fraud-detection-system
```bash

(Обязательно установите файл train.csv!)

# Сборка и запуск всех сервисов
```bash
docker-compose up --build
```bash

Готово!

- Для загрузки файлов для скоринга используйте: **Streamlit UI**: http://localhost:8501
- Для мониторинга: **Kafka UI**: http://localhost:8080
**Логи сервисов**: 
  ```bash
docker-compose logs <service_name>
