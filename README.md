# Hospital-San-Gabriel-Solution
# HOSPITAL SAN GABRIEL
## De registros clínicos a datos estructurados

**Asignatura:** Informática Médica  
**Actividad:** Semana 12 – De registros a datos  
**Modalidad:** Trabajo individual  

---

##  Descripción del proyecto

El presente proyecto tiene como objetivo organizar, estructurar y analizar la información clínica de 20 pacientes ficticios del Hospital San Gabriel.

La actividad consiste en transformar registros clínicos que se encontraban en diferentes formatos y con distintas formas de escritura en una base de datos organizada, utilizando Microsoft Excel.

Mediante este proceso se busca facilitar la consulta de la información, mejorar su comprensión, identificar datos faltantes y obtener indicadores estadísticos que permitan interpretar los registros de manera clara y ordenada.

##  Objetivo general

Construir una base de datos clínica estructurada a partir de 20 registros ficticios, aplicando procesos de organización, limpieza, estandarización y análisis de información mediante herramientas informáticas.

### Objetivos específicos

- Identificar los campos necesarios para organizar la información de cada paciente.
- Estandarizar los datos clínicos y administrativos.
- Organizar los registros en una hoja de cálculo.
- Calcular indicadores estadísticos mediante fórmulas de Excel.
- Representar los resultados mediante gráficos.
- Reconocer la importancia de la privacidad y el manejo responsable de la información clínica.

## Estructura de la base de datos

La base de datos contiene 20 registros de pacientes ficticios. Cada paciente ocupa una fila y cuenta con los siguientes campos:

| Campo | Descripción |
|---|---|
| Código | Identificador único del paciente. |
| Edad | Edad del paciente expresada en años. |
| Sexo | Sexo registrado mediante las letras F o M. |
| Fecha de consulta | Fecha en la que se realizó la consulta médica. |
| Motivo de consulta | Razón principal por la que el paciente acudió al servicio médico. |
| Temperatura (°C) | Temperatura corporal registrada. |
| Frecuencia cardíaca (lpm) | Número de latidos por minuto. |
| Saturación de oxígeno (%) | Porcentaje de saturación de oxígeno registrado. |
| Diagnóstico simulado | Diagnóstico incluido en el caso académico. |
| Estado de atención | Situación de la atención: Pendiente, En atención o Finalizada. |

##  Proceso de limpieza y organización

Para construir la base de datos se realizaron los siguientes procedimientos:

1. **Identificación de variables:** se determinaron los campos necesarios para representar la información de cada paciente.
2. **Estandarización de fechas:** todas las fechas se organizaron utilizando el formato AAAA-MM-DD.
3. **Normalización del sexo:** se unificaron las categorías en F y M.
4. **Normalización de estados:** se utilizaron únicamente las categorías Pendiente, En atención y Finalizada.
5. **Organización de valores numéricos:** la edad, temperatura, frecuencia cardíaca y saturación se registraron como valores numéricos.
6. **Identificación de datos faltantes:** se conservó vacía la saturación de oxígeno del paciente P016, debido a que este dato no aparece en el registro original.
7. **Aplicación de filtros:** se habilitaron filtros para facilitar la búsqueda y consulta de los registros.

##  Análisis de la información

A partir de los 20 registros se calcularon indicadores estadísticos para conocer las características generales de la información.

Los principales resultados fueron:

- Total de pacientes registrados: 20.
- Edad promedio: 42,95 años.
- Temperatura promedio: 37,12 °C.
- Pacientes de sexo femenino: 10.
- Pacientes de sexo masculino: 10.
- Atenciones pendientes: 4.
- Atenciones en curso: 7.
- Atenciones finalizadas: 9.
- Saturación mínima registrada: 91 %.
- Registros con información incompleta: 1.

También se elaboraron gráficos para representar la distribución de pacientes por sexo y el estado de atención.

## Archivos incluidos

El proyecto contiene los siguientes archivos:

- **Base_Datos_Hospital.xlsx:** archivo principal de Excel, con las hojas Pacientes y Análisis, indicadores estadísticos, fórmulas y gráficos.
- **pacientes.csv:** exportación de la base de datos en formato CSV UTF-8.
- **README.md:** documento que describe el proyecto, sus objetivos, estructura y metodología.
- **analisis.md:** documento destinado a presentar la interpretación de los resultados, las inconsistencias encontradas y la reflexión sobre privacidad clínica.

##  Importancia de la privacidad de los datos clínicos

La información clínica contiene datos que deben manejarse con responsabilidad y confidencialidad. Su almacenamiento y procesamiento requieren medidas que protejan la privacidad de los pacientes y eviten el acceso no autorizado.

La organización de los datos debe realizarse siguiendo principios de seguridad, confidencialidad e integridad. Además, es importante evitar publicar información personal o identificable en plataformas abiertas como GitHub.

En este proyecto se utilizaron exclusivamente datos ficticios con fines académicos, por lo que no se expone información de pacientes reales.

##  Conclusión

El desarrollo de esta actividad permitió comprender la importancia de transformar registros clínicos desorganizados en bases de datos estructuradas y fáciles de consultar.

La limpieza y estandarización de la información facilitaron el análisis de los 20 registros, permitiendo obtener indicadores estadísticos y representarlos mediante gráficos.

Asimismo, se identificó la importancia de reconocer los datos faltantes sin inventar información y de mantener buenas prácticas de privacidad y seguridad en el manejo de datos clínicos.

En conclusión, las herramientas informáticas como Excel y GitHub permiten organizar, analizar y documentar información de manera eficiente, contribuyendo al desarrollo de habilidades fundamentales en informática médica.

---
