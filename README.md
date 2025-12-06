# COL_MEN_STAT

Proyecto de ciencia de datos basado en datos abiertos del MEN (Colombia). Incluye ETL, EDA, modelado, validación y una interfaz simple para uso final. El repositorio muestra el flujo completo desde la recolección del dato hasta el despliegue del modelo.


## Contexto y condiciones iniciales
 El dataset de *Matrícula de educación preescolar, básica y media* surge como un registro administrativo consolidado por el SIMAT, cuyo propósito central es producir información estadística oportuna, confiable y desagregada sobre la población atendida en el sistema educativo colombiano. Esta información permite organizar el proceso de matrícula, monitorear la cobertura, caracterizar estudiantes y establecimientos, y constituir la base para la distribución de recursos del Sistema General de Participaciones, la formulación de políticas públicas y el análisis de trayectorias educativas.

Desde la perspectiva del Estado, la ***calidad educativa*** se entiende como un componente del derecho a la educación que integra disponibilidad, accesibilidad, adaptabilidad y aceptabilidad. En este marco, la calidad se vincula tanto al desempeño académico como a la capacidad del sistema de garantizar acceso equitativo, permanencia, pertinencia, infraestructura adecuada, docentes cualificados y trayectorias educativas completas.

Los actores involucrados en la operación estadística abarcan diferentes niveles y responsabilidades:

* Ministerio de Educación Nacional: Diseña los lineamientos, garantiza la calidad del proceso, consolida la información y publica los resultados estadísticos.

* Secretarías de Educación de Entidades Territoriales Certificadas: Gestionan el cargue de datos, validan reportes institucionales y acompañan a los establecimientos educativos.

* Establecimientos educativos oficiales y privados: Registran la información estudiante a estudiante, actualizan novedades y aseguran la veracidad de los datos reportados.

* Organismos nacionales como DNP, DANE, ICBF, ICFES y DPS: Utilizan la información para análisis sectoriales, planeación social y definición de políticas.

* Organizaciones internacionales: UNESCO, OCDE y UNICEF emplean estos datos para comparaciones globales y seguimiento a compromisos internacionales.

* Ciudadanía, academia e investigadores: Consumen la información para investigación, evaluación de políticas y control social.

Este conjunto de actores garantiza que el proceso estadístico sea integral, continuo y transparente, fortaleciendo la capacidad del Estado para comprender y mejorar el sistema educativo.

## Preguntas de investigación iniciales

Este proyecto busca responder las siguientes preguntas orientadoras:

* ¿Cómo ha evolucionado la tasa de cobertura bruta y neta por departamento a lo largo del tiempo?

* ¿Existen desigualdades significativas entre departamentos en indicadores como deserción o cobertura?

* ¿Es posible predecir la tasa de deserción futura o la matrícula con base en tendencias históricas y otros factores asociados?

* ¿Cuál es el porcentaje de estudiantes que cursan educación regular en condición de extraedad y cómo varía entre territorios?

* ¿Existe correlación entre el tamaño del grupo y el porcentaje de reprobación?

## Métricas de Éxito del Análisis y Modelado

Para garantizar la rigurosidad del estudio y la utilidad de los resultados dentro del proceso de toma de decisiones, se establecen métricas de éxito diferenciadas según la naturaleza del análisis realizado.

En los **análisis descriptivos y exploratorios**, el éxito se medirá por la capacidad del estudio para identificar patrones territoriales en cobertura, deserción, extraedad y reprobación, así como desigualdades significativas entre departamentos. Se considerará exitoso si logra presentar información clara, desagregada y consistente que permita a los tomadores de decisión comprender la magnitud y distribución de los fenómenos analizados. La utilidad para políticas públicas será clave: el análisis debe permitir señalar cuellos de botella, poblaciones vulnerables y brechas educativas que orienten intervenciones concretas.

En los **análisis comparativos entre territorios**, las métricas de éxito se centrarán en la solidez estadística de los hallazgos. Se considerará exitoso si detecta desigualdades con significancia estadística, si los indicadores empleados son robustos y si los resultados permiten priorizar territorios para intervenciones. La capacidad del análisis para ofrecer evidencia verificable y replicable será un componente esencial.

En los **procesos predictivos orientados a proyectar matrícula o deserción futura**, se emplearán métricas estadísticas específicas. Para modelos de regresión que predicen valores continuos, como la matrícula proyectada, se utilizarán MAE, RMSE y R² para evaluar precisión, distancia promedio del error y capacidad explicativa. Para modelos de clasificación, relevantes en la predicción de deserción, se utilizarán exactitud, precisión, sensibilidad, F1 Score y AUC-ROC, especialmente en escenarios con clases desbalanceadas. El modelo será considerado exitoso si supera los valores base obtenidos con modelos simples y si el nivel de error es lo suficientemente bajo como para permitir una planificación informada.

Finalmente, desde el enfoque del marco lógico, el éxito de los análisis y modelos se definirá por su utilidad práctica. Se considerará exitoso aquel resultado que contribuya a la asignación adecuada de recursos educativos, a la proyección de cupos escolares, a la identificación temprana de territorios críticos y a la formulación de intervenciones focalizadas para mejorar la calidad y permanencia escolar.