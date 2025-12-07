# COL_MEN_STAT

Proyecto de ciencia de datos basado en datos abiertos del MEN (Colombia). Incluye ETL, EDA, modelado, validación y una interfaz simple para uso final. El repositorio muestra el flujo completo desde la recolección del dato hasta el despliegue del modelo.



>  **Estado del proyecto:** En desarrollo activo.  
Actualmente se cuenta con la estructura del repositorio y un notebook inicial para el proceso ETL.

## 📁 Estructura del repositorio
```bash
COL_MEN_STAT/
├── Data/
│   ├── Raw/
│   ├── Processed/
├── Docs/
│   ├─ context.md─
│   └── methodology.md
├── Notebooks/
│   ├─ 01-inspecion-datos.ipynb
├── Report/
├── Visuals/
├── LICENSE
└── README.md
```

### Directorios principales

- **Data/Raw**: Datos originales descargados del MEN.  
- **Data/Processed**: Archivos generados durante el ETL.  
- **Notebooks**: Notebooks de análisis, ETL, modelado y validación.  
- **Docs**: Documentación complementaria (contexto operativo y metodología).  
- **Report**: Versiones de resultados y reportes finales.  
- **Visuals**: Gráficos, visualizaciones y recursos generados.



## 🚧 Estado actual

En esta fase se encuentra:

- ✔️ Estructura del repositorio definida  
- ✔️ Dataset base almacenado en `Data/Raw`  
- ✔️ Documentos iniciales de contexto y metodología  
- 🔄 Notebook de ETL **en proceso**  
- ⏳ Aún no hay scripts ejecutables ni modelos entrenados  



## 🎯 Objetivos del proyecto

El análisis se enfoca en:

- Caracterizar la matrícula por departamento  
- Explorar patrones de cobertura, deserción y extraedad  
- Identificar desigualdades territoriales significativas  
- Desarrollar modelos predictivos preliminares (proyección de matrícula / deserción)



## 🛠️ Requisitos e instalación

> Esta sección se expandirá a medida que se integren los notebooks y scripts.

Ejemplo de entorno recomendado:

```bash
python >= 3.10
pandas
numpy
matplotlib
scikit-learn
jupyter
