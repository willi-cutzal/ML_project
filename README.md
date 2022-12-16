![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

​
# <h1 align="center">**`Willi Cutzal`**
# <h1 align="center">**`Data Scientist`**



## **Introducción**

Bienvenido! En esta ocasión ​se llevará a cabo la elaboración de un modelo de Machine Learning. Para este proyecto se hará uso de librerías tales como: Pandas (para el análisis exploratorio de datos y preprocesamiento), Seabor y Matplotlib (para algunas visualizaciones) y finalmente Scikit-learn (para Machine Learning)

## **Contexto**
Un importante centro de Salud no has contratado con el fin de poder predecir si un paciente tendrá una estancia hospitalaria prolongada o no. Utilizando la información contenida en el datasest asociado, la cual recaba una muestra histórica de sus pacientes, para poder administrar la demanda de camas en el hospital según la condición de los pacientes recientemente ingresados.

## **Motivo del proyecto**

La hospitalización, cuando es prolongada constituye una preocupación a nivel mundial debido a sus efectos negativos en el sistema de salud, aumentando los costos, generando deficiencia en la accesibilidad de prestación de servicios de salud, saturación de unidades de hospitalización y urgencias, por consiguiente, mayores efectos adversos como lo son las enfermedades intrahospitalarias.

El estudio de los procesos de atención en salud, así como el conocimiento de las características y perfiles de los usuarios con el objetivo de predecir la ocupación hospitalaria, es uno de los aspectos al que las autoridades de salud han prestado gran interés, pues permite no sólo garantizar los recursos necesarios para la atención del paciente, sino realizar ajustes respecto a la oferta y demanda de los servicios de salud y los implementos asociados.

## **Elección de modelo**
Para este problema se usará el algoritmo de **_`Regresión Logística`_**, es un modelo para problemas de clasificación. Ya que lo que se quiere saber es si un paciente tendrá una estancia hospitalaria prolongada o no. Por lo que el _target_ tendrá solo dos opciones.

Estos modelos se emplean mucho para test de enfermedades, filtros de correo spam, test de embarazo, etc.

Clasifica separando por una linea. Con ese umbral, determina si una instancia es 0 o 1 -es decir, si pertenece a una categoría o a la otra-.

### **Estancia Hospitalaria prolongada**

Se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado más de 8 días.
​​
## **Archivos provistos**
- 'step_by_step_ipynb': archivo donde se muestra el paso a paso del proyecto.

- 'hospitalizaciones_train.csv': Contiene 410000 registros y 15 dimensiones, el cual incluye la información **numérica** de la cantidad de días de estancia hospitalaria.

- 'hospitalizaciones_test.csv': Contiene 90000 registros y 14 dimensiones, el cual no incluye la información de la cantidad de días de estancia hospitalaria.
​
## **Descripción de las dimensiones del archivo hospitalizaciones_train/test.csv**
- Available Extra Rooms in Hospital: Habitaciones adicionales disponibles en el hospital. Una habitación no es igual a un paciente, pueden ser individuales o compartidas.
- Department: Área de atención a la que ingresa el paciente. 
- Ward_Facility_Code: Código de la habitación del paciente.
- doctor_name: Nombre de el/la doctor/a a cargo del paciente.
- staff_available: Cantidad de personal disponible al momento del ingreso del paciente.
- patientid: Identificador del paciente.
- Age: Edad del paciente.
- gender: Género del paciente.
- Type of Admission: Tipo de ingreso registrado según la situación de ingreso del paciente.
- Severity of Illness: Gravedad de la enfermedad/condición/estado del paciente al momento del ingreso.
- health_conditions: Condiciones de salud del paciente. 
- Visitors with Patient: Cantidad de visitantes registrados para el paciente.
- Insurance: Indica si la persona posee o no seguro de salud. 
- Admission_Deposit: Pago realizado a nombre del paciente, con el fin de cubrir los costos iniciales de internación. 
- Stay (in days): Días registrados de estancia hospitalaria. 
​


## **Descripción de las dimensiones del archivo Hospitalizaciones_codificado/_test.csv**
- Hab_Disponibles: Habitaciones adicionales disponibles.
- Departamento: Área de atención a la que ingresa el paciente.
- Codigo_Hab: Código de la habitación del paciente.
- Nombre_Medico: Nombre del Doctor(a) a cargo del paciente.
- Staff_Disponible: Cantidad de personal disponible.
- Rango_Etario_Ordenado:
    - 0 para el rango 0-10
    - 1 para el rango 11-20
    - 2 para el rango 21-30
    - 3 para el rango 31-40
    - 4 para el rango 41-50
    - 5 para el rango 51-60
    - 6 para el rango 61-70
    - 7 para el rango 71-80
    - 8 para el rango 81-90
    - 9 para el rango 91-100
- Las columnas que hacen referencia al género: Female, Male, Other
    - 0 para Negativo
    - 1 para Afirmativo
- Las columnas que hacen referencia al tipo de ingreso: Emergency, Trauma, Urgent
    - 0 para Negativo
    - 1 para Afirmativo
- Gravedad_Enfermedad_Ordenado:
    - 0 para Extreme
    - 1 para Moderate
    - 2 para Minor
- Condicion_Salud_Ordenado:
    - 0 para Heart disease
    - 1 para Diabetes
    - 2 para High Blood Pressure
    - 3 para Asthama
    - 4 para Other
    - 5 para None
- Visitantes: Cantidad de visitantes registrados para el paciente
- Las columnas que hacen referencia al Seguro: Con_Seguro y Sin_Seguro
    - 0 para Negativo
    - 1 para Afirmativo
- Deposito_Ingreso: Pago realizado a nombre del paciente
- Estadia: días registrados de estancia hospitalaria
- Estadia_Prolongada: 
    - 0 para Estadia menor o igual a 8 días
    - 1 para Estadía mayor a 8 días



<hr>

## **Recursos y links provistos**

### `Pandas`
+ https://pandas.pydata.org/pandas-docs/stable/index.html
### `Matplotlib`
+ https://matplotlib.org/
### `Seaborn`
+ https://seaborn.pydata.org/
### `Scikit-learn`
+ https://scikit-learn.org/stable/index.html

