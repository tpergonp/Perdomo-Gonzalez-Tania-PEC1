# Metadatos del Dataset 'human_caquexia'

## Descripción General
Este dataset contiene datos de los niveles de distintos metabolitos en pacientes con caquexia y un grupo control. 
El objetivo del estudio es identificar posibles biomarcadores para el diagnóstico y seguimiento de la misma 

- **Número de muestras**: 77 pacientes.
- **Grupos**: Cachexia, Control.
- **Número de variables**: 63 metabolitos analizados y 2 variables de identificación (ID de paciente y caquexia/control).
- **Formato del archivo**: CSV (human_caquexia.csv).

## Definición de Variables: 63 variables numéricas y dos variables categóricas (Patiente.ID y Muscle.loss)

## Ejemplo de Estructura de Datos

| Patient.ID | Muscle.loss | 1,6-Anhydro-beta-D-glucose | 2-Aminobutyrate | Creatinine | Lactate | Glycine | Tyrosine | ... | Valine |
|------------|-------------|----------------------------|-----------------|------------|---------|---------|----------|------|--------|
| PIF_178    | cachexic    | 40.85                      | 18.73           | 16481.6    | 685.4   | 4582.5  | 925.19   | ...  | 237.46 |
| PIF_087    | cachexic    | 62.18                      | 24.29           | 15835.35   | 651.97  | 368.71  | 845.56   | ...  | 376.15 |

## Fuente de Datos
Los datos fueron recogidos como parte de un estudio experimental sobre caquexia en pacientes.

## Limitaciones
- Tamaño de muestra limitado a 77 pacientes, lo cual puede no representar completamente la variabilidad de la población general.
- Variabilidad significativa en los valores de los metabolitos entre pacientes.
- Necesidad de considerar factores adicionales (edad, sexo, marcadores inflamatorios,etc) en estudios futuros para reducir la asimetría en los datos.
