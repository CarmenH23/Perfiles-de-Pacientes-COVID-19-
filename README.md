# Perfiles-de-Pacientes-COVID-19-
Nombre: María del Carmen Herrera Jiménez
Materia: Desarrollo de Proyectos I
Correo: maria.herrera6329@alumnos.udg.mx
Código estudiante: 208763291
Maestro: Victor Hugo Cuspinera Contreras.


## Descripción General 

En esta investigación se realiza el estudio de los síntomas de los resultados de laboratorio de pacientes que durante la pandemia de COVID-19 presentaron síntomas de la enfermedad. El objetivo principal es agrupar pacientes tomando como base sus síntomas y comorbilidades, utilizando técnicas de análisis de clústeres.La identificación de estos patrones permitirá  descubrir grupos de pacientes que cuentan con características similares. Se espera que a través del estudio se obtenga para el personal médico:
1. Mejora en el tratamiento; ya que al identificar perfiles de pacientes las estrategias de cuidado y tratamientos se pueden adaptar mejor.
2. Predicción de riesgos: Los perfiles identificados pueden ayudar a predecir qué pacientes tienen mayor riesgo de desarrollar complicaciones.
3. Optimización de recursos: Permite una mejor asignación de recursos médicos al identificar grupos de pacientes con necesidades específicas.

## Resumen de análisis EDA

En la aplicación del análisis EDA de esta base de datos, se encontraron diversos problemas principalmente con el formato de los mismos, por ejemplo el formato FECHA en columnas de tipo FECHA, la falta de datos en columnas claves de comorbilidades o síntomas , falta de datos en fechas de nacimiento y/o edad, y esto fue la causa de un paso adicional para determinar la edad en los casos en que hacía falta, tomando fecha de nacimiento, y determinar la fecha de nacimiento en los casos en los que se contaba con la edad y con la fecha en que se capturó la información del paciente.

Estadísticas de Edad:
Media: 38.52
Mediana: 36.00
Desviación Estándar: 14.98
Mínimo: 0.00
Máximo: 100.00

Porcentaje de edades fuera del rango 0-100: 0.01%

### Resumen de comorbilidades:
DIABETES: 13003.0 casos (5.15%)
ENF_PULMONAR: 1211.0 casos (0.48%)
ASMA: 9033.0 casos (3.57%)
INMUNOSUPRESION: 913.0 casos (0.36%)
VIH_SIDA: 519.0 casos (0.21%)
ENFERMEDAD_CARDIACA: 4029.0 casos (1.59%)
OBESIDAD: 35294.0 casos (13.97%)
HIPERTENSION_ARTERIAL: 19606.0 casos (7.76%)
INSUF_RENAL_CRONICA: 2054.0 casos (0.81%)
TABAQUISMO: 27877.0 casos (11.03%)
CANCER: 1096.0 casos (0.43%)
ENFERMEDAD_HEPATICA: 900.0 casos (0.36%)


### Resumen de síntomas:
FIEBRE: 80907.0 casos (32.01%)
DOLOR_MUSCULAR: 65446.0 casos (25.9%)
DIARREA: 41069.0 casos (16.25%)
VOMITO: 10784.0 casos (4.27%)
ESCALOFRIOS: 40962.0 casos (16.21%)
CONJUNTIVITIS: 43231.0 casos (17.11%)


### Estructura del repositorio


C:.
|   README.md
|
+---data
|       datos_covid_2020.csv
|       README.md
|
+---doc
|       .gitkeep
|       README.md
|
+---results
|       .gitkeep
|       README.md
|
\---src
        .gitkeep
        Análisis descriptivo BD covid.ipynb
        README.md




