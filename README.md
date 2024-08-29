# <ins>Predicción del Precio de las Acciones de Apple con Árbol de Decisión</ins>
Este repositorio contiene una implementación sencilla de un Clasificador de Árbol de Decisión para predecir la dirección (subida o bajada) de los precios de las acciones de Apple utilizando datos históricos. El código utiliza Pandas para la manipulación de datos y scikit-learn para construir y visualizar el modelo de aprendizaje automático.

📂 Conjunto de Datos
El conjunto de datos utilizado es un archivo Excel (Apple.xlsx) que contiene datos históricos del mercado de acciones, con columnas para las fechas y la información correspondiente del mercado bursátil, incluyendo una columna llamada Direction, que representa la dirección del movimiento de las acciones (arriba o abajo).

### 🚀 Configuración del Proyecto
Para ejecutar este proyecto, asegúrate de tener Python y las dependencias necesarias instaladas.

Las principales bibliotecas utilizadas en este proyecto son:

  - pandas para la manipulación de datos.
  - scikit-learn para el modelo de aprendizaje automático (Clasificador de Árbol de Decisión).
  - matplotlib para la visualización del árbol de decisión.
### 📊  Modelo de Aprendizaje Automático
El objetivo de este proyecto es predecir la Dirección del precio de las acciones de Apple utilizando diversas variables explicativas. A continuación, se describe brevemente el proceso:

1. Cargar los Datos
Cargamos el conjunto de datos desde un archivo Excel y configuramos la columna de Date como índice para manejar los datos de series temporales.

2. Definir las Variables Objetivo y Explicativas
La columna Direction se establece como el objetivo (lo que queremos predecir), y las demás columnas son las variables explicativas que utilizamos para la predicción.

3. Entrenar el Modelo de Árbol de Decisión
Creamos un Clasificador de Árbol de Decisión con una profundidad máxima de 3 para asegurarnos de que el árbol se mantenga interpretable.

4. Realizar Predicciones
Una vez entrenado, realizamos predicciones utilizando el modelo y las comparamos con los valores reales de Direction.

5. Visualizar el Árbol de Decisión
Visualizamos el árbol de decisión utilizando la función de visualización de scikit-learn.

6. Evaluar el Modelo
Para evaluar qué tan bien ha funcionado el modelo, calculamos el porcentaje de predicciones correctas.

### 📈 Resultados Ejemplares
El árbol de decisión produce un modelo sencillo e interpretable que nos ayuda a predecir si el precio de las acciones de Apple subirá o bajará. La precisión del modelo se evalúa comparando las predicciones con los datos reales.

  - Precisión del Modelo: (ejemplo: 75.5%)
### 🛠️ Posibles Mejoras
A continuación, se mencionan algunas posibles mejoras que se pueden implementar:

  - Usar modelos más avanzados (por ejemplo, Random Forest, Gradient Boosting).
  - Ajustar hiperparámetros (por ejemplo, max_depth, min_samples_split) para mejorar el rendimiento del modelo.
  - Explorar técnicas de ingeniería de características para extraer datos más significativos.
### 📝 Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
### 🌟 Contribuciones
Siéntete libre de hacer un fork de este repositorio, enviar pull requests o reportar problemas. ¡Las contribuciones son siempre bienvenidas!

