# Previous steps:

- Download the dataset and drop it in the root of the main python file: https://liveutad-my.sharepoint.com/shared?listurl=https%3A%2F%2Fliveutad%2Dmy%2Esharepoint%2Ecom%2Fpersonal%2Fsilvia%5Fmartin%5Fu%2Dtad%5Fcom%2FDocuments&id=%2Fpersonal%2Fsilvia%5Fmartin%5Fu%2Dtad%5Fcom%2FDocuments%2FVisión%20por%20computador%2F25%2D26%2FT3%2FPráctica%2Fcards%2Ezip&parent=%2Fpersonal%2Fsilvia%5Fmartin%5Fu%2Dtad%5Fcom%2FDocuments%2FVisión%20por%20computador%2F25%2D26%2FT3%2FPráctica&shareLink=1&ga=1&share=cQrb%5FgD7FxbuRbSP%2DXF7mgdpEgUC5LaQLeGbOpG0jD3BRlUR0g

# --- ESPAÑOL ---

# ¡Bienvenidos a la competición de CNNs 2026!

En esta competición, el objetivo principal es alcanzar el **F1-score** más alto posible, demostrando tu destreza en la construcción y evaluación de modelos. El F1-score es una métrica fundamental que mide la precisión y la exhaustividad de tus predicciones, lo que significa que encontrarás un equilibrio perfecto entre la capacidad de acertar y evitar errores.

La participación en la competición únicamente será posible en **grupos de 3-4**. El dataset para la práctica ha sido proporcionado en la entrega. Las características de la clasificación o qué objetos se clasifican se deja a elección de los participantes (se recomienda evitar soluciones triviales, ej.: _tiene color rojo / no tiene color rojo_). Cada tipo de clasificación se considerará una categoría distinta.

En caso de necesitar reorganizar las imágenes dentro de cada conjunto de datos (sin mover imágenes entre particiones) para realizar otro tipo de clasificación, se deberá entregar el conjunto de datos completo ya reorganizado. En ningún caso se podrán eliminar imágenes de cualquiera de las tres particiones. Se puede utilizar _data augmentation_, redimensionamiento y otras modificaciones.

En el improbable caso de un empate en el F1-score, no te preocupes, analizaremos las tasas de falsos positivos y falsos negativos para determinar al ganador. Estas tasas son críticas para evaluar cuán efectivo es tu modelo en la detección de errores y cómo maneja los casos negativos y positivos de manera precisa.

## Puntuación

El premio para el ganador de cada categoría será de 3 puntos. ¡Pero eso no es todo! Los primeros puestos también tendrán su recompensa:

- **1er puesto:** 3 puntos.
- **2do puesto:** 2 puntos.
- **3er puesto:** 1 punto.

Lamentablemente, el resto de los participantes no recibirán ningún punto extra. ¡Pero eso no implica que no puedan sacar una buena nota! Los **7 puntos restantes** corresponderán a la implementación en Python con PyTorch del modelo CNN y su respectiva memoria.

## Contenido de la memoria

La memoria correspondiente deberá incluir:

1. **Temática y características de la clasificación realizada y su justificación.**
   1. ¿Qué objetos habéis decidido clasificar? ¿Por qué?
   2. ¿Qué tipo de clasificación se ha aplicado? ¿Por qué?
   3. ¿Se han realizado modificaciones al dataset? Indica cuáles y por qué.
2. **Decisiones en cuanto a la arquitectura de la CNN.**
   1. ¿Cuántas capas tiene vuestro modelo? ¿Por qué?
   2. ¿Qué modificaciones habéis introducido? ¿Por qué?
   3. Justificación de las métricas, función de pérdida y optimizador.
3. **Metodología y resultados, incluyendo gráficas que muestren claramente el rendimiento de la red implementada.**
   1. Hiperparámetros y selección de estos.
   2. Resultado de las métricas seleccionadas.
   3. Gráficas de resultados.

Cabe destacar que la estructura es orientativa y podéis incluir otra información si se considera oportuno. También se deberá entregar el **modelo entrenado**.

## Avisos importantes

- El falseamiento de resultados será gravemente penalizado.
- El uso de modelos de lenguaje (LLMs), tanto para la generación de código como de texto, será penalizado y puede requerir defensa presencial. Solo se permite su utilización para la corrección gramatical.
- En caso de emplear código o información procedente de alguna fuente, se recomienda encarecidamente indicar dicha fuente.
- Se recomienda el uso de Colab para aquellos participantes que tengan problemas de GPU.

# --- ENGLISH ---

# Welcome to the 2026 CNN Competition!

In this competition, the main goal is to achieve the highest possible **F1-score**, showing off your skill in building and evaluating models. The F1-score is a fundamental metric that measures the precision and recall of your predictions, meaning you will find a perfect balance between the ability to get things right and avoiding errors.

Participation in the competition is only possible in **groups of 3-4**. The dataset for the assignment has been provided with the submission. The characteristics of the classification, or which objects are classified, are left to the participants' choice (it is recommended to avoid trivial solutions, e.g.: _has red color / does not have red color_). Each type of classification will be considered a separate category.

If you need to reorganize the images within each dataset split (without moving images between partitions) in order to carry out a different type of classification, you must submit the complete dataset already reorganized. Under no circumstances may images be removed from any of the three partitions. You may use _data augmentation_, resizing and other modifications.

In the unlikely event of a tie in the F1-score, don't worry: we will analyze the false positive and false negative rates to determine the winner. These rates are critical for assessing how effective your model is at detecting errors and how accurately it handles negative and positive cases.

## Scoring

The prize for the winner of each category will be 3 points. But that's not all! The top positions will also be rewarded:

- **1st place:** 3 points.
- **2nd place:** 2 points.
- **3rd place:** 1 point.

Unfortunately, the rest of the participants will not receive any extra points. But that doesn't mean they can't get a good grade! The **remaining 7 points** will correspond to the Python implementation of the CNN model with PyTorch and its respective report.

## Report Contents

The corresponding report must include:

1. **Topic and characteristics of the classification performed and its justification.**
   1. Which objects have you decided to classify? Why?
   2. What type of classification has been applied? Why?
   3. Have any modifications been made to the dataset? Indicate which ones and why.
2. **Decisions regarding the CNN architecture.**
   1. How many layers does your model have? Why?
   2. What modifications have you introduced? Why?
   3. Justification of the metrics, loss function and optimizer.
3. **Methodology and results, including plots that clearly show the performance of the implemented network.**
   1. Hyperparameters and how they were selected.
   2. Results of the selected metrics.
   3. Result plots.

Note that the structure is indicative and you may include other information if you consider it appropriate. The **trained model** must also be submitted.

## Important Notices

- Falsification of results will be severely penalized.
- The use of language models (LLMs), both for code generation and for text, will be penalized and may require an in-person defense. Their use is only permitted for grammar correction.
- If you use code or information from any source, it is strongly recommended that you cite that source.
- The use of Colab is recommended for participants who have GPU problems.
