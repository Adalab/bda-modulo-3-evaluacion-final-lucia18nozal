# Análisis de Clientes en un Programa de Lealtad de Aerolíneas 🛩

## 📖 Descripción del Proyecto
Este proyecto tiene como objetivo analizar el comportamiento de los clientes dentro de un programa de lealtad de una aerolínea. Para ello, se analizan dos conjuntos de datos: uno que detalla la actividad de vuelo de los clientes y otro que describe su perfil dentro del programa de lealtad. A través de este análisis se realizará: una exploración inicial, limpieza de datos, visualizaciones y pruebas estadísticas para extraer insights relevantes.


## 🛠️ Tecnologías Utilizadas
- **Python**: Lenguaje de programación utilizado para realizar el procesamiento y análisis de datos.
   - **Pandas, NumPy**: Librería de Python utilizada para la manipulación y limpieza de los datos.
   - **Matplotlib, Seaborn**: Librerías de Python utilizadas para crear visualizaciones.
- **Jupyter Notebook**: Para análisis exploratorio y visualización.
- **CSV**: Manejo de datos proporcionados.
- **Git Hub:** Para el control de versiones.


## Hallazgos del Análisis
![Distribución de vuelos reservados por mes.](Images/Pregunta%201.jpg)
![Relación entre distancia y puntos acumulados.](Images/Pregunta%202.jpg)
![Distribución de clientes por provincia/estado.](Images/Pregunta%203.jpg)
![Comparación de salario promedio por nivel educativo.](Images/Pregunta%204.jpg)
![Proporción de clientes según tipo de tarjeta de lealtad.](Images/Pregunta%205.jpg)
![Distribución de clientes según estado civil y género.](Images/Pregunta%206.jpg)


## 📉 Datos Utilizados
Se proporcionan dos archivos CSV que contienen información sobre los clientes y su actividad dentro del programa de lealtad:

### 1. *Customer Flight Analysis.csv*
Contiene datos sobre la actividad de vuelo de los clientes, incluyendo:
- **Loyalty Number**: Identificador único de cada cliente.
- **Year** y **Month**: Fecha de la actividad.
- **Flights Booked**: Vuelos reservados en el mes.
- **Flights with Companions**: Vuelos reservados con acompañantes.
- **Total Flights**: Total de vuelos realizados.
- **Distance**: Distancia total volada.
- **Points Accumulated**: Puntos acumulados en el mes.
- **Points Redeemed**: Puntos redimidos.
- **Dollar Cost Points Redeemed**: Valor en dólares de los puntos redimidos.

### 2. *Customer Loyalty History.csv*
Proporciona detalles sobre el perfil de los clientes, incluyendo:
- **Loyalty Number**: Identificador único del cliente.
- **Country, Province, City, Postal Code**: Ubicación del cliente.
- **Gender, Education, Salary, Marital Status**: Datos demográficos.
- **Loyalty Card**: Tipo de tarjeta de lealtad.
- **CLV (Customer Lifetime Value)**: Valor estimado del cliente.
- **Enrollment Type, Year, Month**: Datos de inscripción al programa.
- **Cancellation Year, Month**: Datos de cancelación (si aplica).


## 🎯 Objetivos del Proyecto por Fases

### *Fase 1: Exploración y Limpieza 🧐*
- Explorar la estructura y calidad de los datos, identificando valores nulos, atípicos o inconsistentes.
- Combinar ambos conjuntos de datos a través de la columna Loyalty Number para integrar la información del cliente con su actividad de vuelo.
- Limpiar y transformar los datos para asegurar que sean consistentes y estén listos para el análisis.

### *Fase 2: Visualización 📊*
Se generarán visualizaciones para responder a las siguientes preguntas:
- Distribución de vuelos reservados por mes.
- Relación entre distancia volada y puntos acumulados.
- Distribución de clientes por provincia o estado.
- Comparación del salario promedio entre diferentes niveles educativos.
- Proporción de clientes con diferentes tipos de tarjetas de fidelidad.
- Distribución de clientes por estado civil y género.

### *Fase 3 (BONUS): Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo*
- Analizar si existen diferencias significativas en el número de vuelos reservados según el nivel educativo de los clientes.

## 🚀 Cómo Ejecutar el Proyecto
1. Clona este repositorio o descarga los archivos necesarios.
   - `git clone https://github.com/Adalab/bda-modulo-3-evaluacion-final-lucia18nozal.git`
2. Instala las dependencias utilizando los siguientes comandos:
   - `pip install pandas`
   - `pip install numpy`
   - `pip install matplotlib`
   - `pip install seaborn`
3. Ejecutar el archivo *'Ejercicio_Evaluacion_Modulo_3_LuciaNozal'* para ver el análisis y resultados con mayor detalle.


## 📈 Mejoras 
- Aplicar una prueba estadística adecuada para evaluar estas diferencias en la fase 3 del proyecto.


## 👩🏻‍💻 Autora
- Lucía Nozal Benito.


## 🪪 Licencia
Este proyecto se distribuye bajo la licencia [MIT (Massachusetts Institute of Technology)].
MIT es una de las licencias de software libre y de código abierto más utilizadas. Es conocida por ser simple y permisiva, lo que significa que permite a cualquier persona usar, modificar y distribuir el software con muy pocas restricciones.