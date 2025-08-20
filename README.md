# UniversityDWH
Proyecto de Data Warehouse universitario con dbt (ETL/ELT) y Power BI
# UniversityDWH – dbt + Power BI

Proyecto de **Data Warehouse universitario** usando **dbt** para modelado/transformaciones (ETL/ELT) y **Power BI** para visualización.  
Demuestro habilidades de integración de datos, modelado en capas (staging/core/marts), pruebas y documentación con dbt, y creación de dashboards.

## Contenido del repositorio
- `models/`, `macros/`, `seeds/`, `snapshots/`, `tests/`, `analyses/` (dbt)
- `docs/` (diagrama ERD y capturas de Power BI)
- `powerbi/` (opcional: archivo .pbix o PDF/capturas)

## Requisitos (local)
- dbt 1.x con perfil en `~/.dbt/profiles.yml` (credenciales **no** se versionan)

## Cómo ejecutar (dbt)
```bash
dbt deps
dbt run
dbt test
# Documentación local
dbt docs generate
dbt docs serve
