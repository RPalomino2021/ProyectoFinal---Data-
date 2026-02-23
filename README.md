
🚀 Azure Databricks Data Engineer – Final Project
  Este repositorio contiene el desarrollo integral de un proyecto final enfocado en la ingeniería de datos utilizando Azure Databricks.
  La solución implementa un pipeline de datos bajo el enfoque de arquitectura Medallion (Bronze / Silver / Gold), aplicando buenas prácticas de procesamiento, transformación y modelado analítico.
  El proyecto trabaja con dos fuentes de datos en formato CSV:
    🚗 Automobile Dataset
    🛒 Ecommerce Dataset
--------------------------------------------------------------------------------------------------------------------
🥇 Arquitectura Medallion
La arquitectura Medallion organiza los datos en tres capas principales:
Capa	Descripción
  🥉 Bronze	Datos crudos tal como llegan desde las fuentes
  🥈 Silver	Datos limpios, transformados y enriquecidos
  🥇 Gold	Datos agregados y modelados para consumo analítico
-------------------------------------------------------------------------------------------------------------------
🔄 Orquestación
La ejecución de pipelines se realiza mediante:
Databricks Workflows
Jobs programados
Ejecuciones dependientes por capa
Flujo recomendado:
      Bronze → Silver → GoldFinal Project - Azure Databricks
------------------------------------------------------------------------------------------------------------------
📦ProyectoFinal---Data-/
├── 📂 0. PreAmbPrd/                   # Archivo .ipynb para Preparación de ambiente
├── 📂 1. Reversión/                   # Archivo .ipynb para Revoke y drop de objetos
├── 📂 2. Seguridad/                   # Archivo .ipynb para Grants y control de accesos
├── 📂 4. Datasets/                    # Archivos de referencia / muestras
├── 📂 5. Proceso/                     # Archivo .ipynb -- Extract / Transform / Load
├── 📂 6. GitHub-Workflow/             # Imagen de la ejecución del  Workflow
├── 📂 7. Dashboard/                   # Evidencias de Dashboard realizado
├── 📂 8. Certificaciones/             # Material y evidencias de certificaciones
├── 📂 Evidencias/                     # Evidencias de todo lo trabajado en el Proyecto    
└── README.md                          # Documentación Final
------------------------------------------------------------------------------------------------------------------
