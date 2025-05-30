# Tukan Airlines: Expansión Estratégica en el Mercado Asiático 🚀

Este proyecto de análisis de datos fue desarrollado por **Oracle Data Labs** para **Tukan Airlines**, una aerolínea caribeña con la ambición de expandirse estratégicamente en el mercado asiático. Nuestro objetivo fue identificar los mejores primeros pasos para esta expansión, a través de un análisis exhaustivo de sus datos operativos.

## 📝 Tabla de Contenidos

1.  [Acerca del Proyecto](#-acerca-del-proyecto)
2.  [El Desafío de Tukan Airlines](#-el-desafío-de-tukan-airlines)
3.  [Metodología](#-metodología)
    * [Extracción de Datos (ETL)](#extracción-de-datos-etl)
    * [Almacenamiento en Base de Datos](#almacenamiento-en-base-de-datos)
    * [Análisis Exploratorio de Datos (EDA)](#análisis-exploratorio-de-datos-eda)
4.  [Tecnologías Utilizadas](#-tecnologías-utilizadas)
5.  [Estructura del Proyecto](#-estructura-del-proyecto)
6.  [Instalación y Uso](#-instalación-y-uso)
7.  [Dashboard y KPIs Clave](#-dashboard-y-kpis-clave)
8.  [Visualizaciones Destacadas](#-visualizaciones-destacadas)
9.  [Conclusiones Estratégicas y Recomendaciones](#-conclusiones-estratégicas-y-recomendaciones)
10. [Contribución](#-contribución)
11. [Licencia](#-licencia)
12. [Contacto](#-contacto)
13. [Agradecimientos](#-agradecimientos)

---

## 💡 Acerca del Proyecto

Este repositorio contiene el análisis de datos realizado para **Tukan Airlines**, una aerolínea con sede en el Caribe que busca incursionar y establecer una fuerte presencia en el dinámico mercado asiático. Como **Oracle Data Labs**, nuestra tarea fue proporcionar un análisis de datos profundo para identificar patrones operativos, tendencias de reservas y métricas clave que informen las decisiones estratégicas de Tukan Airlines en su fase inicial de expansión.

## ✈️ El Desafío de Tukan Airlines

Tukan Airlines, en su visión de crecimiento, se enfrenta al desafío de entender un nuevo mercado con dinámicas de viaje diferentes. La aerolínea necesita respuestas a preguntas cruciales como:
* ¿Cuáles son los patrones de reserva más comunes?
* ¿Qué tipos de aeronaves son más eficientes para ciertos rangos o rutas?
* ¿Cómo se distribuyen los ingresos entre los diferentes modelos de avión y condiciones de tarifa?
* ¿Existen horarios específicos del día que muestren picos de demanda de reservas?
* ¿Cuáles son las ciudades más populares y las de menor actividad?

Nuestro análisis busca responder a estas preguntas y sentar las bases para una expansión exitosa.

## 📈 Metodología

El proyecto siguió una metodología estructurada de análisis de datos para asegurar la calidad y relevancia de los insights.

### Extracción de Datos (ETL)

Los datos brutos fueron extraídos de una fuente en Kaggle, originalmente en formato **SQLite**. Se llevó a cabo un proceso de **ETL (Extracción, Transformación y Carga)** para limpiar, transformar y estructurar los datos. Este proceso resultó en la generación de 8 archivos CSV consolidados, que representan las tablas clave de la operación de la aerolínea:

* `aircrafts_data.csv`
* `airports_data.csv`
* `boarding_passes.csv`
* `bookings.csv`
* `flights.csv`
* `seats.csv`
* `ticket_flights.csv`
* `tickets.csv`

### Almacenamiento en Base de Datos

Para garantizar un almacenamiento robusto y escalable, y facilitar futuras consultas y análisis, los 8 archivos CSV fueron cargados y almacenados en una base de datos **MySQL Server**. Esto proporciona una base de datos centralizada y optimizada para el rendimiento.

### Análisis Exploratorio de Datos (EDA)

Una vez los datos estuvieron disponibles y estructurados, se realizó un **Análisis Exploratorio de Datos (EDA)** exhaustivo utilizando Python. Este EDA incluyó:
* Limpieza de datos (manejo de valores nulos, formatos incorrectos).
* Identificación de distribuciones y correlaciones.
* Cálculo de estadísticas descriptivas.
* Generación de diversas visualizaciones para comprender los patrones subyacentes en los datos.

## 🛠️ Tecnologías Utilizadas

* **Lenguajes:**
    * Python
    * SQL (para la base de datos MySQL)
* **Librerías/Frameworks Python:**
    * Pandas (para manipulación y análisis de datos)
    * Matplotlib (para creación de gráficos estáticos)
    * Seaborn (para visualizaciones estadísticas avanzadas y estéticas)
    * `sqlite3` (para la extracción inicial de SQLite)
    * `mysql.connector` (para la conexión con MySQL)
* **Base de Datos:**
    * MySQL Server
* **Entornos de Desarrollo:**
    * Jupyter Notebook / JupyterLab (para el desarrollo del EDA y análisis)
    * (Si usaste Power BI, Tableau u otra herramienta para el dashboard, menciónala aquí, ej: "Power BI para el dashboard final")

## 📂 Estructura del Proyecto
