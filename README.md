# Introducci-n-a-las-GNN

El link a este repositorio es: [github](https://github.com/GonzaloGmv/Introduccion-a-las-GNN)

Los participantes somos:
- Alexandre Muñoz
- José Luis Rodríguez
- Gonzalo Martínez

## Resultados y Análisis

### Presentación de resultados basados en la implementación y experimentación

Durante el proceso de entrenamiento, se observó una rápida mejora en la precisión del modelo en el conjunto de entrenamiento. A continuación, se presentan algunos resultados clave:

- Convergencia del Modelo: Se observó que el modelo convergió de manera eficaz hacia una precisión del 100% en el conjunto de entrenamiento después de 200 épocas. El análisis de la curva de aprendizaje reveló la velocidad de convergencia y proporcionó insights sobre la estabilidad del modelo durante el entrenamiento.

- Validación cruzada: Para evaluar la generalización del modelo, se aplicó un riguroso proceso de validación cruzada. Esto implicó la evaluación del modelo en conjuntos de validación independientes para detectar posibles problemas de sobreajuste y garantizar un rendimiento sólido en datos no vistos.
  
- Visualización de la Evolución: Se proporcionó una animación que muestra la evolución de las predicciones de la GCN en cada época. Se observó que las predicciones mejoraron progresivamente hasta alcanzar la precisión máxima.

- Significación de las Incrustaciones: Las incrustaciones aprendidas por la GCN fueron sometidas a un análisis exhaustivo. Se exploró la coherencia y la interpretabilidad de estas incrustaciones para comprender cómo el modelo asigna características específicas a cada nodo. Este análisis respaldó la afirmación de que las incrustaciones proporcionan una representación rica y significativa de los nodos en el espacio latente.

### Reflexiones y Observaciones sobre los Resultados y la Eficacia del Modelo

- Capacidad de Aprendizaje de la GCN: La GCN demostró una capacidad excepcional para aprender patrones complejos en datos estructurados, como se evidencia en la alta precisión alcanzada en el conjunto de entrenamiento. Sin embargo, se debe realizar una evaluación cuidadosa en un conjunto de prueba independiente para verificar la capacidad de generalización del modelo.

- Importancia de las Incrustaciones: Las incrustaciones aprendidas ofrecen una representación valiosa de los nodos en el conjunto de datos. La capacidad de la GCN para capturar información estructural del grafo se refleja en estas incrustaciones, que podrían ser exploradas en futuras investigaciones para comprender mejor la topología del grafo.

- Generalización del Modelo: Aunque se logró una precisión del 100% en el conjunto de entrenamiento, existe la posibilidad de sobreajuste (overfitting). Es esencial evaluar el modelo en un conjunto de prueba independiente para asegurar que pueda generalizar bien a datos no vistos.

- Ajuste de Parámetros: Durante la experimentación, se ajustaron diversos hiperparámetros, como la tasa de aprendizaje y el tamaño del lote. Se observó que ciertos ajustes impactaron significativamente en el rendimiento del modelo, destacando la importancia de un ajuste fino de parámetros.

- Interpretación de Nodos Mal Clasificados: Se examinaron los nodos mal clasificados para comprender mejor las limitaciones del modelo. Esto proporcionó información valiosa sobre los casos en los que la GCN podría tener dificultades, lo cual podría orientar futuras mejoras del modelo.

- Posibilidades de Mejora: Se identificaron áreas potenciales de mejora, como la exploración de arquitecturas más complejas de GCN, la aplicación de técnicas de regularización y la incorporación de información adicional al modelo para mejorar aún más su rendimiento.
