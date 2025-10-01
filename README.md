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

## 1.2. Tema elegido.
Predicción de la necesidad de receta médica en medicamentos usando datos farmacéuticos abiertos
## 1.3. Antecedentes y problemática
El desarrollo de las farmacias digitales y las plataformas de comercio electrónico en el sector de la salud en los años recientes ha estimulado la exigencia de contar con sistemas más eficaces para clasificar medicamentos. En el sector farmacéutico, la importancia de implementar técnicas de análisis de datos y modelos predictivos es resaltada por investigaciones anteriores, porque posibilitan prever patrones de prescripción, optimizar la trazabilidad de los productos y asegurar que las regulaciones sanitarias se cumplan. Estas acciones demuestran que la digitalización del sector puede aprovechar herramientas de inteligencia artificial para mejorar procesos y disminuir los fallos humanos en el manejo de información.

Sin embargo, la dificultad de automatizar la identificación de medicamentos que necesitan receta médica es el problema actual, debido a la amplia variedad de características que los definen, entre las cuales se encuentran su presentación, el costo, el país productor o la enfermedad vinculada. La categorización inadecuada de un medicamento puede provocar el incumplimiento de la ley, afectar la logística de ventas y mermar la confianza del cliente. Por esto, es esencial examinar las soluciones que emplean machine learning, ya que posibilitan prever de forma fiable la necesidad de recetas médicas y favorecen tanto la seguridad y accesibilidad del sistema de distribución farmacéutica como la eficacia operativa.

## 1.4. Dataset y Análisis.
Nombre: Medicines Dataset (https://www.kaggle.com/datasets/drowsyng/medicines-dataset)

Fuente: Kaggle, recopilado mediante web scraping de la plataforma NetMeds (última actualización febrero 2025).
