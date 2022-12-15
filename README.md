![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

​
# <h1 align="center">**`Willi Cutzal`**
# <h1 align="center">**`Data Scientist`**



## **Introducción**

Bienvenido! En esta ocasión ​se llevará a cabo la elaboración de un modelo de Machine Learning.

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
## **Descripción de las dimensiones**
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
## **Escalas de las dimensiones**
-  
