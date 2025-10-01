# Carpeta: data

Nombre: Medicines Dataset (https://www.kaggle.com/datasets/drowsyng/medicines-dataset)
Fuente: Kaggle, recopilado mediante web scraping de la plataforma NetMeds (última actualización febrero 2025).
Tamaño: 240.23 MB, con decenas de miles de registros.

## Contenido

Variables más relevantes para el objetivo:
* disease_name: indica la enfermedad asociada al medicamento; ayuda a identificar patrones de prescripción, ya que ciertas patologías requieren fármacos regulados.
* med_name: nombre comercial del medicamento; útil para identificación, aunque no aporta directamente a la predicción.
* final_price y price: precios de venta; pueden influir porque los medicamentos de alto costo o especializados suelen estar sujetos a receta.
* prescription_required: variable objetivo (sí/no); es lo que se busca predecir.
* drug_variant: presentación (ej. número de tabletas, solución inyectable); relevante porque algunas presentaciones implican mayor control médico.
* drug_manufacturer: fabricante; puede reflejar tendencias regulatorias o reputación del laboratorio.
* drug_manufacturer_origin: país de origen; importante porque en algunos países las regulaciones son más estrictas.
* generic_name: principio activo; es clave, ya que la sustancia define si el fármaco necesita supervisión médica.
* drug_content: texto con usos, mecanismo de acción y advertencias; muy valioso para análisis de texto, pues contiene directamente información regulatoria.

- Archivos de datos procesados o intermedios (si se generan en el análisis).

⚠️ Nota: No se recomienda subir datasets muy pesados directamente al repositorio. 
