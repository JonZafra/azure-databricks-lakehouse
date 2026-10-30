# Azure Databricks Lakehouse

Proyecto de ingeniería de datos con Azure Data Factory, Databricks y Delta Lake.

## Objetivo

Construir un pipeline de datos de extremo a extremo en Azure: ingesta con Azure Data Factory, procesamiento con Azure Databricks (PySpark y Delta Lake) en capas bronze, silver y gold, y consumo en Power BI. Proyecto de aprendizaje y portfolio, orientado a la certificación DP-750.

## Arquitectura

## Fuente de datos

REData API de Red Eléctrica: https://www.ree.es/es/apidatos

- Endpoint principal: generación por tecnología (`generacion/estructura-generacion`).
- Agregación temporal: día, mes o año; filtrable por comunidad autónoma (Navarra: `geo_id` 14).
- Formato: JSON anidado (estándar JSON:API), solo peticiones GET.

## Stack

## Cómo ejecutarlo

## Estado del proyecto

## Decisiones

