# WearMe — Datos de investigación

Datos de campo del proyecto **[WearMe](https://github.com/juancamiloamarillo41-cloud/wearme)**, un wearable IoT para la detección de **metano entérico (eructos) en ganado bovino** con Machine Learning embebido, desarrollado en el **Instituto iOMICAS** de la Pontificia Universidad Javeriana.

## Contenido

- `wearme_ble_sesion_XX_animal_YYY_*.csv` — Sesiones de captura en campo transmitidas por BLE desde el dispositivo: datos de **IMU** (acelerómetro y giroscopio), **sensor de metano** y **variables ambientales** (temperatura/humedad), etiquetadas por animal y fecha.
- `Features_modelo_c.zip` — Características (features) extraídas para el entrenamiento e inferencia del modelo.

## Proyecto completo

El firmware (nRF52840 + Edge Impulse) y la app Android (Kotlin/Compose) están en 👉 **[github.com/juancamiloamarillo41-cloud/wearme](https://github.com/juancamiloamarillo41-cloud/wearme)**

---
**Autor:** Juan Camilo Amarillo Morales · Ingeniería Mecatrónica · Instituto iOMICAS, Pontificia Universidad Javeriana
