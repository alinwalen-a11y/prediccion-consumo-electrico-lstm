 ⚡ Predicción de Consumo Eléctrico con LSTM

Modelo de Deep Learning para predecir el consumo eléctrico de la próxima hora y detectar anomalías de posible fraude o falla.

 📊 Resultados
- **Dataset:** 8,760 registros (1 año, 1 dato por hora)
- **Anomalías detectadas:** 58 eventos atípicos
- **Modelo V1:** Error MAE 1.91 kW
- **Modelo V2:** Error MAE **0.79 kW** (mejora del 59%)

🧠 ¿Qué hice?
1. Limpieza y análisis de datos con Pandas
2. Detección de anomalías con umbral estadístico (Media + 3σ)
3. Creación de ventanas de 24 horas para entrenar el LSTM
4. Entrenamiento en PyTorch con 50 épocas
5. Optimización: de 2 capas a 1 capa, learning rate de 0.001 a 0.005

 🛠️ Tecnologías
Python, PyTorch, Pandas, NumPy, Matplotlib, Scikit-learn, Kaggle

 📈 Gráfica del modelo
La línea roja (predicción) sigue a la azul (real), incluso detectando picos de consumo.
