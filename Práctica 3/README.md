# Práctica 3: Manufactura Aditiva e Impresión 3D

## I. Objetivo

Comprender los principios de la manufactura aditiva y conocer las características principales de la impresión 3D. Aplicar estos conocimientos al diseño de una caja con tapa articulada, considerando la geometría de sus componentes, el movimiento de apertura y los aspectos necesarios para su fabricación.

## II. Introducción

La manufactura aditiva es un proceso de fabricación que permite crear objetos tridimensionales mediante la incorporación sucesiva de material. Para ello, se parte de un modelo digital que se procesa con un programa especializado antes de enviarlo a la impresora 3D.

Esta tecnología se utiliza en el desarrollo de prototipos, piezas mecánicas, objetos personalizados y componentes funcionales. Una de sus principales ventajas es que permite fabricar geometrías que pueden resultar difíciles de producir mediante métodos tradicionales.

En esta práctica se relacionan los conceptos de manufactura aditiva con el diseño de una caja que cuenta con una tapa que abre hacia atrás. Este tipo de objeto permite estudiar la forma de las piezas, la relación entre sus componentes y la importancia de diseñar correctamente una unión articulada.

## III. Marco teórico

### 1. Manufactura aditiva

La manufactura aditiva consiste en fabricar objetos mediante la incorporación progresiva de material a partir de un diseño digital. A diferencia de los procesos sustractivos, en los que se elimina material de una pieza inicial, este método construye el objeto agregando material únicamente en las zonas determinadas por el diseño.

La impresión 3D es una de las aplicaciones más conocidas de la manufactura aditiva. Su uso facilita la elaboración de modelos de prueba y permite modificar un diseño digital antes de volver a fabricarlo.

### 2. Principales tecnologías de impresión 3D

Existen diferentes tecnologías de manufactura aditiva. Cada una utiliza un procedimiento particular y ofrece distintas características de precisión, materiales, acabado y resistencia.

| Tecnología | Funcionamiento                                                                | Materiales habituales                                                 | Aplicaciones                                                                 |
| ---------- | ----------------------------------------------------------------------------- | --------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| FDM/FFF    | Deposita filamento termoplástico fundido en capas sucesivas.                  | PLA, ABS, PETG y TPU.                                                 | Prototipos, cajas, soportes y piezas funcionales.                            |
| SLA        | Utiliza luz para solidificar selectivamente una resina fotosensible.          | Resinas fotopoliméricas.                                              | Modelos detallados, piezas pequeñas y prototipos que requieren buen acabado. |
| MSLA/DLP   | Emplea una pantalla o un proyector de luz para solidificar capas de resina.   | Resinas fotosensibles.                                                | Modelos con detalles finos y geometrías pequeñas.                            |
| SLS        | Utiliza energía láser para fusionar material en polvo.                        | Principalmente polvos poliméricos, como determinados tipos de nailon. | Componentes funcionales y geometrías complejas.                              |
| MJF        | Fusiona selectivamente polvo mediante agentes de impresión y energía térmica. | Polvos poliméricos compatibles con el proceso.                        | Producción de piezas funcionales y series de componentes.                    |

La elección de una tecnología depende de las características del objeto, el material disponible, la precisión necesaria y los recursos del laboratorio.

### 3. Funcionamiento de la impresión FDM

La tecnología de modelado por deposición fundida (FDM) es común en entornos educativos debido a que permite fabricar piezas con filamentos termoplásticos.

Su funcionamiento general se divide en las siguientes etapas:

1. Se crea el modelo tridimensional mediante un programa CAD.
2. Se exporta el archivo a un formato compatible con el programa de laminado.
3. El laminador divide virtualmente el objeto en capas y genera las instrucciones para la impresora.
4. La impresora deposita el material capa por capa hasta formar la pieza.
5. Se retira la pieza y se revisa su acabado y funcionamiento.

El resultado depende de factores como la temperatura, la velocidad de impresión, la altura de capa, la orientación del objeto y las características del material.

### 4. Materiales utilizados en impresión 3D

Los filamentos presentan diferentes propiedades mecánicas y térmicas. Por ello, es importante seleccionar el material de acuerdo con el uso que tendrá la pieza.

| Material    | Características                                                                                  | Ventajas                                                             | Limitaciones                                                                                    | Aplicaciones                                |
| ----------- | ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------- |
| PLA         | Termoplástico rígido y de impresión relativamente sencilla.                                      | Fácil de utilizar y adecuado para prototipos.                        | Puede deformarse con temperaturas elevadas y es relativamente frágil frente a ciertos impactos. | Modelos, cajas y piezas de uso general.     |
| ABS         | Plástico resistente al impacto y al calor en comparación con PLA.                                | Adecuado para determinadas piezas funcionales.                       | Puede contraerse durante el enfriamiento y presentar deformaciones.                             | Carcasas y componentes mecánicos.           |
| PETG        | Material con buena adherencia entre capas y cierta flexibilidad.                                 | Combina resistencia y facilidad de impresión en muchas aplicaciones. | Puede generar hilos durante la impresión y requiere ajustes adecuados.                          | Recipientes, soportes y piezas funcionales. |
| TPU         | Material flexible y elástico.                                                                    | Permite fabricar componentes deformables.                            | Su impresión puede ser más lenta y requiere una configuración apropiada.                        | Protectores, sellos y elementos flexibles.  |
| Nailon (PA) | Material con buenas propiedades mecánicas y resistencia al desgaste en determinadas condiciones. | Útil para componentes sometidos a movimiento o fricción.             | Puede absorber humedad y requerir condiciones de impresión específicas.                         | Engranajes, bujes y componentes mecánicos.  |

La temperatura adecuada de impresión depende del fabricante, la composición del filamento y el equipo utilizado. Por eso, se deben consultar las recomendaciones correspondientes antes de establecer los parámetros.

### 5. Diseño para manufactura aditiva

El diseño para manufactura aditiva, conocido como DfAM, consiste en adaptar la geometría de un objeto a las características y limitaciones de la impresión 3D.

No basta con que un modelo tenga la forma deseada en la pantalla: también es necesario considerar cómo se fabricará, qué zonas necesitarán soporte y cómo se comportará la pieza una vez terminada.

Entre los aspectos más importantes se encuentran:

* **Orientación:** la posición del objeto durante la impresión influye en su acabado, resistencia y necesidad de soportes.
* **Voladizos:** las partes que sobresalen pueden requerir soporte dependiendo de su geometría y de las capacidades de la impresora.
* **Espesor de pared:** las paredes deben tener dimensiones adecuadas para las condiciones de fabricación y el uso previsto.
* **Relleno:** la estructura interna de una pieza influye en su peso, consumo de material y resistencia.
* **Tolerancias:** las separaciones entre componentes deben considerar las variaciones propias del proceso de impresión.
* **Adherencia entre capas:** la orientación y los parámetros de impresión influyen en la resistencia de las uniones entre capas.

Estos factores son especialmente importantes cuando se diseñan objetos con tapas, articulaciones o piezas que deben moverse entre sí.

## IV. Diseño de la caja con tapa articulada

### 1. Descripción del modelo

El proyecto consiste en una caja diseñada digitalmente, con una tapa que se abre hacia atrás. Su función es permitir el acceso al espacio interior y mantener unidos los componentes que forman la estructura.

El diseño permite estudiar la relación entre la base, las paredes y la tapa, así como los elementos que permiten realizar el movimiento de apertura y cierre.

La geometría de cada componente debe ser compatible con las dimensiones generales de la caja para que las piezas puedan integrarse correctamente.

### 2. Consideraciones de diseño

Para desarrollar una caja con tapa articulada, es necesario considerar diferentes aspectos geométricos y funcionales.

| Elemento                | Función                               | Aspectos que deben considerarse                                     |
| ----------------------- | ------------------------------------- | ------------------------------------------------------------------- |
| Base                    | Forma la parte inferior de la caja.   | Dimensiones, estabilidad y espesor.                                 |
| Paredes laterales       | Delimitan el espacio interior.        | Altura, espesor y unión con la base.                                |
| Tapa                    | Cubre la abertura de la caja.         | Dimensiones, alineación y espacio necesario para abrir.             |
| Articulación trasera    | Permite que la tapa gire hacia atrás. | Eje de giro, separación entre componentes y libertad de movimiento. |
| Unión entre componentes | Mantiene las piezas en su posición.   | Ajuste, resistencia y compatibilidad geométrica.                    |

La solución utilizada para la articulación depende del diseño específico. Puede tratarse de una unión integrada en la pieza o de componentes separados que permitan el giro. Por ello, es importante revisar el modelo real antes de describir su mecanismo exacto.

### 3. Tolerancias y movimiento de la tapa

Las tolerancias son importantes cuando dos componentes deben ajustarse o moverse entre sí. Si las piezas quedan demasiado juntas, pueden rozar o bloquearse; si existe demasiada separación, la unión puede presentar holgura.

En una caja con tapa articulada, deben revisarse especialmente las zonas de giro y los puntos donde la tapa se relaciona con el cuerpo principal.

La separación adecuada depende de la impresora, el material, la orientación y los parámetros utilizados. Por lo tanto, no existe una medida única que funcione en todos los casos.

Si la tapa se imprime por separado, también es necesario comprobar que la geometría de su unión permita instalarla y moverla correctamente.

### 4. Parámetros que influyen en el resultado

| Parámetro                | Efecto en la pieza                                                | Importancia para la caja                                                   |
| ------------------------ | ----------------------------------------------------------------- | -------------------------------------------------------------------------- |
| Altura de capa           | Influye en el detalle y el tiempo de fabricación.                 | Afecta el acabado de las paredes y de la tapa.                             |
| Temperatura de impresión | Influye en la extrusión y la unión entre capas.                   | Ayuda a conseguir una fabricación consistente.                             |
| Velocidad de impresión   | Modifica el tiempo de fabricación y puede afectar la calidad.     | Debe ser compatible con la geometría del modelo.                           |
| Relleno                  | Determina parte de la estructura interna de la pieza.             | Influye en el peso y la rigidez de la base y la tapa.                      |
| Soportes                 | Sostienen zonas que no pueden imprimirse correctamente sin apoyo. | Pueden ser necesarios según la forma de la tapa y sus salientes.           |
| Orientación              | Modifica la dirección de las capas y la necesidad de soportes.    | Influye en el acabado, la resistencia y la fabricación de la articulación. |

Los valores concretos de estos parámetros deben corresponder a la configuración utilizada durante la impresión.

## V. Ventajas y limitaciones de la manufactura aditiva

La impresión 3D permite fabricar prototipos con rapidez y modificar los diseños digitales sin necesidad de elaborar herramientas específicas para cada cambio.

También facilita la creación de piezas personalizadas y permite comprobar las dimensiones y el funcionamiento de un objeto antes de desarrollar una versión definitiva.

Sin embargo, existen limitaciones. La fabricación puede requerir bastante tiempo dependiendo del tamaño y la complejidad de la pieza. Además, la resistencia, el acabado y la precisión dimensional dependen del material y de las condiciones de impresión.

En los objetos con componentes móviles, también es necesario considerar las tolerancias y comprobar que las partes puedan moverse sin interferencias.

## VI. Conclusión

La manufactura aditiva permite transformar modelos digitales en objetos físicos mediante la incorporación sucesiva de material. Para obtener buenos resultados, es necesario seleccionar un material apropiado, preparar correctamente el archivo y considerar las características de la impresora.

El diseño de una caja con tapa articulada permite aplicar estos conceptos a un objeto funcional. Su elaboración requiere prestar atención a las dimensiones, los espesores, la alineación de los componentes y el espacio necesario para que la tapa pueda abrirse y cerrarse.

En conclusión, el diseño y la impresión 3D son procesos complementarios que permiten desarrollar prototipos, evaluar su funcionamiento y realizar modificaciones antes de fabricar una versión definitiva.

## VII. Evidencias


