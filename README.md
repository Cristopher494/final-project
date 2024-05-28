https://deteccion-retinopatia-diabetica.streamlit.app/

Este proyecto se centra en el desarrollo de un modelo predictivo para la clasificación de imágenes, empleando una red neuronal convolucional (CNN).

El conjunto de datos utilizado consta de 25,000 imágenes de escáneres de retina, clasificadas de manera binaria en función de la presencia o ausencia de retinopatía.

Durante la exploración del conjunto de datos, se identificó un desbalance significativo entre las clases, con una menor cantidad de imágenes correspondientes a retinas afectadas por retinopatía. Para mitigar este desbalance, se aplicaron técnicas de ponderación, asignando un mayor peso a la clase minoritaria durante el entrenamiento del modelo.

Las imágenes corruptas fueron eliminadas y se llevaron a cabo múltiples técnicas de preprocesamiento para optimizar el aprendizaje del modelo. Se emplearon generadores de imágenes para preprocesar, redimensionar y escalar las imágenes adecuadamente antes de ser ingresadas en el modelo.

Se utilizó aprendizaje por transferencia mediante el modelo preentrenado DenseNet121, el cual fue adaptado específicamente para la tarea de clasificación binaria de este proyecto.
