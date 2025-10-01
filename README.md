<body>
    <div style="text-align: center; font-weight: bolder">
        <p>Universidad Peruana de Ciencias Aplicadas - Ingeniería de Software - 7° Ciclo</p>
        <img src="assets/0.cover/logo-upc.png" alt="logo of UPC"/>
        <p>1ACC0240 - Metodología para Data Science</p>
        <p>Sección - 14083</p>
        <p>Docente: Victoria Alejandra Ubaldo Gamarra</p>   
        <p>Informe de Trabajo Final - TB1<p>
    </div>
    <div style="text-align: center; display: flex; flex-direction: column; align-items: center">
        <h3 style="font-weight: bolder">Integrantes del equipo:</h3>
        <table style="width: fit-content">
            <tr>
                <th style="text-align:start;">Estudiante</th>
                <th style="text-align:center;">Código</th>
            </tr>
            <tr>
                <td style="text-align:start;">Rojas Ccama, Carlos Andres</td>
                <td>202114657</td>
            </tr>
            <tr>
                <td style="text-align:start;">Castillo Olivera, Trilce Trissty Deyannira</td>
                <td>202218225</td>
            </tr>
            <tr>
                <td style="text-align:start;">Aquino Cruz, Leonardo José</td>
                <td>20201B949</td>
            </tr>
            <tr>
                <td style="text-align:start;">Burga Loarte, Anaely Zarely</td>
                <td>202118264</td>
        </table>
    </div>
    <p style="text-align: center">Septiembre 2025</p>
</body>

<div style="page-break-before: always"></div>


# Registro de Versiones del Informe

| Versión | Fecha      | Autor                             | Descripción de modificación |
|---------|------------|-----------------------------------|-----------------------------|

<div style="page-break-before: always"></div>

# Project Report Collaboration Insights

En esta sección se documenta la colaboración del equipo en la elaboración del informe, mostrando evidencias gráficas de la actividad en GitHub y su coherencia con el registro de versiones.

* URL del repositorio del Project Report en la organización de GitHub del equipo:
* [https://github.com/xLeonardo32/prescription-prediction-group4](https://github.com/xLeonardo32/prescription-prediction-group4)

<div style="page-break-before: always"></div>

# 1. Contenido

<!-- TOC -->
* [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
* [Project Report Collaboration Insights](#project-report-collaboration-insights)
* [Contenido](#contenido)
* [Student Outcome](#student-outcome)



## 1.1. Perfiles de integrantes del equipo

| Roles asignados                                                                      | Nombres y apellidos              | Código de estudiante | Carrera                | Conocimientos técnicos y habilidades                                                                                                                                                                                                                                                                                                |
|---------------------------------------------------------------------------------------------|----------------------------------|----------------------|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Data Scientist  | Leonardo José Aquino Cruz | 20201B949 | Ingeniería de Software | Manejo de análisis de datos con Python (pandas, matplotlib, seaborn), experiencia en limpieza y visualización de datasets, así como documentación de procesos de análisis.
| Data Analyst | Trilce Trissty Deyannira Castillo Olivera | 202218225 | Ingeniería Biomédica | Durante mi formación, he adquirido conocimientos básicos en análisis de datos con Python y Excel, manejo de bases de datos, visualización gráfica e interpretación de información para la toma de decisiones.
| Data Visualization & Documentation Specialist | Anaely Zarely Burga Loarte | 202118264 | 
| Data Engineer | Carlos Andres Rojas Ccama | 202114657 | Ingeniería de Software | Durante mi formación, he desarrollado habilidades en diversos lenguajes de programación como C++, Python así como experiencia en desarrollo web con Angular para el frontend y Spring Boot para el backend |

## 1.2. Tema elegido
Predicción de la necesidad de receta médica en medicamentos usando datos farmacéuticos abiertos
## 1.3. Antecedentes y problemática
El desarrollo de las farmacias digitales y las plataformas de comercio electrónico en el sector de la salud en los años recientes ha estimulado la exigencia de contar con sistemas más eficaces para clasificar medicamentos. En el sector farmacéutico, la importancia de implementar técnicas de análisis de datos y modelos predictivos es resaltada por investigaciones anteriores, porque posibilitan prever patrones de prescripción, optimizar la trazabilidad de los productos y asegurar que las regulaciones sanitarias se cumplan. Estas acciones demuestran que la digitalización del sector puede aprovechar herramientas de inteligencia artificial para mejorar procesos y disminuir los fallos humanos en el manejo de información.

Sin embargo, la dificultad de automatizar la identificación de medicamentos que necesitan receta médica es el problema actual, debido a la amplia variedad de características que los definen, entre las cuales se encuentran su presentación, el costo, el país productor o la enfermedad vinculada. La categorización inadecuada de un medicamento puede provocar el incumplimiento de la ley, afectar la logística de ventas y mermar la confianza del cliente. Por esto, es esencial examinar las soluciones que emplean machine learning, ya que posibilitan prever de forma fiable la necesidad de recetas médicas y favorecen tanto la seguridad y accesibilidad del sistema de distribución farmacéutica como la eficacia operativa.

## Fuente del dataset (link de Kaggle)
* [https://www.kaggle.com/datasets/drowsyng/medicines-dataset/data](https://www.kaggle.com/datasets/drowsyng/medicines-dataset/data)

## **Acerca del conjunto de datos**
El presente conjunto de datos constituye un recurso de gran valor para el análisis en el ámbito farmacéutico y sanitario, ya que reúne información estructurada sobre medicamentos, enfermedades y fabricantes, obtenida de un sitio web de farmacia en línea. Su diseño facilita la exploración de distintos aspectos relacionados con la disponibilidad de medicamentos, sus precios, características de prescripción y composición, así como el estudio de tendencias en el consumo y distribución de productos farmacéuticos.

La recopilación de esta información se realizó mediante técnicas de raspado web, lo que permitió extraer datos actualizados y organizados en campos claramente definidos. De esta manera, el conjunto de datos no solo sirve como fuente para estudios comparativos de medicamentos, sino también como base para el desarrollo de herramientas tecnológicas orientadas a la salud digital.
### **Resumen**
En términos generales, el conjunto de datos incluye información acerca de enfermedades, medicamentos disponibles, precios finales, descuentos, necesidad de prescripción médica, variantes de presentación, fabricantes, país de origen, componentes activos y descripciones detalladas sobre el uso de cada medicamento. A su vez, se incorporan enlaces tanto a las páginas oficiales de los productos como a las enfermedades correspondientes, lo que amplía el contexto y facilita la verificación de la información.

Cada registro también contiene detalles adicionales como los posibles efectos secundarios, interacciones medicamentosas y advertencias de uso, aspectos que resultan esenciales para estudios clínicos, análisis comparativos y aplicaciones orientadas al bienestar de los pacientes.
### **Detalles del conjunto de datos**
**Campos incluidos**\
El conjunto de datos está compuesto por los siguientes campos:

1. **disease\_name (string):** Nombre de la enfermedad para la que se utiliza el medicamento.
1. **disease\_url (string):** Enlace a la página informativa de la enfermedad.
1. **med\_name (string):** Nombre del medicamento.
1. **med\_url (string):** Enlace a la página del producto.
1. **final\_price (string):** Precio final de venta del medicamento.
1. **precio (string):** Precio de referencia (MRP) y descuentos aplicables.
1. **prescription\_required (string):** Indicación sobre si se requiere receta médica (por ejemplo, *Rx required*).
1. **drug\_variant (string):** Tipo de variante del medicamento, como el número de comprimidos por tira.
1. **drug\_manufacturer (string):** Nombre del fabricante.
1. **drug\_manufacturer\_origin (string):** País de origen del fabricante.
1. **drug\_content (string):** Descripción detallada del medicamento: uso, mecanismo de acción, advertencias, efectos secundarios e interacciones.
1. **generic\_name (string):** Nombre genérico del principio o principios activos.
1. **img\_urls (lista de strings):** Enlaces a imágenes del medicamento.
### **Procedencia y metodología**
- **Fuente de origen:** Netmeds (farmacia en línea).
- **Metodología de extracción:** Se utilizaron técnicas de raspado web (web scraping), que permiten recopilar datos directamente desde las páginas web mediante procesos automatizados.

Este procedimiento asegura que la información esté en un formato legible por máquinas, lo que facilita su análisis posterior mediante herramientas de ciencia de datos, inteligencia artificial o sistemas de gestión de información sanitaria.
### **Usos potenciales**
El conjunto de datos presenta múltiples aplicaciones en áreas de investigación, desarrollo tecnológico y gestión de la salud. Entre los usos más relevantes se encuentran:

- **Sistemas de recomendación médica:** Desarrollo de algoritmos capaces de sugerir medicamentos alternativos o equivalentes en función de enfermedades específicas, principios activos o disponibilidad local.
- **Investigación clínica y farmacológica:** Análisis de medicamentos comunes, sus efectos secundarios reportados y las interacciones que podrían generar riesgos para la salud.
- **Estudios de mercado y distribución:** Comprender la dinámica de disponibilidad de medicamentos, los fabricantes predominantes y los países de origen más frecuentes.
- **Análisis de precios y accesibilidad:** Realizar comparaciones de costos entre diferentes productos, identificar patrones de descuento y estudiar las implicaciones de la accesibilidad económica de ciertos tratamientos.
- **Tendencias en recetas médicas:** Explorar los patrones de prescripción y los medicamentos que requieren obligatoriamente una receta, lo cual resulta relevante para políticas de salud pública y regulaciones.
### **Importancia del conjunto de datos**
La información contenida en este dataset resulta de especial interés en un contexto donde la digitalización del sector salud y la transparencia en el acceso a medicamentos son cada vez más prioritarias. Permite a investigadores, instituciones académicas, profesionales de la salud y desarrolladores de software contar con una base confiable para estudios comparativos, proyectos de innovación y aplicaciones en inteligencia artificial orientadas a la salud.

En este sentido, su valor trasciende el ámbito meramente descriptivo, convirtiéndose en un recurso estratégico para el análisis integral de la industria farmacéutica, el comportamiento del mercado y el bienestar de los pacientes.
