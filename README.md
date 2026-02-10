⚽ Predicción de Resultados de Fútbol
Este proyecto utiliza un modelo de Machine Learning (Regresión Logística) para predecir el resultado de partidos de la liga española basándose en estadísticas ofensivas.

📊 Resumen del Proyecto
El objetivo es clasificar los partidos en tres categorías: Victoria Local, Empate o Victoria Visitante.

🛠️ Tecnologías Utilizadas
Python 🐍 para la lógica principal.

Pandas para la manipulación del dataset SP1.csv.

Scikit-learn para el entrenamiento del modelo y escalado de datos.

Seaborn para visualizar la Matriz de Confusión.

📈 Resultados y Conclusiones
Precisión General: El modelo alcanza un 53%, lo cual es sólido considerando la imprevisibilidad del fútbol.

Variables Clave: Se determinó que los tiros a puerta (HST, AST) y los córners (HC, AC) son los mejores predictores.

El Desafío del Empate: Como muestra la Matriz de Confusión, el modelo tiene un recall bajo en los empates (24%). Esto ocurre porque las estadísticas de un empate son muy similares a las de una victoria ajustada, lo que confunde al algoritmo.
