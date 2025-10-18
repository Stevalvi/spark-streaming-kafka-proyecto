# Proyecto: Análisis de Datos en Tiempo Real con Apache Spark y Kafka

Este proyecto implementa un sistema de análisis de datos en tiempo real utilizando Apache Spark Streaming y Apache Kafka.  
Simula sensores que envían datos de temperatura y humedad, los cuales son procesados en tiempo real por Spark.

## 🧩 Archivos del proyecto

- `kafka_producer.py`: Genera y envía datos simulados a un *topic* de Kafka llamado `sensor_data`.
- `spark_streaming_consumer.py`: Consume los datos desde Kafka y calcula promedios por minuto usando Spark Streaming.

## ⚙️ Requisitos

- Python 3.x  
- Apache Kafka 3.x  
- Apache Spark 3.x  
- Librería `kafka-python`  

Instalar librería Kafka para Python:
```bash
pip install kafka-python
