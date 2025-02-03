# **Análisis de Medallas del Campeonato Europeo de Halterofilia** 🏋️‍♂️  

## **1. Introducción**  

### **Objetivo**  
Este proyecto tiene como finalidad realizar un estudio detallado de las medallas obtenidas en el **Campeonato Europeo de Halterofilia** para **Lift&Lead**, una empresa ficticia que planea abrir centros de **CrossFit** en España.  

A través de este análisis, se busca extraer **insights clave** sobre el rendimiento de los atletas en la competición y cómo estos datos pueden influir en la **toma de decisiones estratégicas** para la empresa.  

---

## **2. Metodología**  

### **Fuentes de Datos**  
Los datos fueron obtenidos mediante técnicas de **web scraping**, recopilados directamente de **Wikipedia**. Los enlaces específicos se encuentran adjuntos en el **Jupyter Notebook**.  

### **Herramientas Utilizadas**  
Para realizar el análisis y la visualización de datos, se ha utilizado **Python** junto con las siguientes librerías:  

- **`NumPy`**: Operaciones numéricas y manejo de arrays.  
- **`Pandas`**: Manipulación y análisis de datos.  
- **`Plotly`**: Visualización interactiva de datos.  
- **`Requests`**: Realización de solicitudes HTTP para el web scraping.  
- **`html5lib`**: Parseo de HTML.  
- **`BeautifulSoup` (de `bs4`)**: Extracción de datos desde documentos HTML.  
- **`re`**: Manejo de expresiones regulares para la limpieza de datos.  
- **`FuzzyWuzzy`**: Coincidencia difusa de cadenas y limpieza de datos.  

---

## **3. Análisis y Resultados**  

### **3.1. Limpieza y Manipulación de Datos**  
Para preparar los datos y hacerlos utilizables en el análisis, se aplicaron diversas técnicas, entre ellas:  
✔ **Uso de la función `melt`** para reestructurar los datos.  
✔ **Creación y eliminación de columnas** según las necesidades del análisis.  
✔ **Expresiones regulares (`re`)** para identificar y corregir patrones en los nombres de atletas y países.  

### **3.2. Web Scraping para Ampliación de Datos**  
✔ **Extracción de información clave** desde Wikipedia mediante `BeautifulSoup`.  
✔ **Enriquecimiento de los datos** con información adicional sobre los atletas y competiciones.  

### **3.3. Análisis de Datos**  
Para visualizar y comprender los datos, se han utilizado diversas técnicas de análisis:  
✔ **Gráficos de distribución, boxplots y gráficos de barras** creados con `Plotly`.  
✔ **Tablas de contingencia** para analizar la relación entre variables categóricas.  

### **3.4. Presentación y Comunicación de Resultados**  
✔ **Elaboración de informes** que contextualizan los hallazgos.  
✔ **Visualizaciones interactivas** para facilitar la interpretación de los datos.  

---

## **4. Conclusiones y Recomendaciones**  

### **4.1. Hallazgos Clave**  
Las conclusiones finales del análisis destacan los patrones en la distribución de medallas y el rendimiento de los atletas en diferentes categorías de la competición.  

### **4.2. Recomendaciones para Lift&Lead**  
Se ofrecen recomendaciones basadas en los datos obtenidos para optimizar la estrategia de la empresa en la apertura de centros de **CrossFit** en España.  

---

## **5. Documentación y Recursos**  

### **Dónde consultar los resultados**  
📂 **Informe en PDF:** Contiene un resumen detallado del análisis y las principales recomendaciones.  
📄 **Jupyter Notebook:** Explicación detallada de los resultados y su relevancia para la empresa.  

