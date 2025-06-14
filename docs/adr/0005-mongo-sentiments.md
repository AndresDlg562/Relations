# ADR-0005 – Almacenar sentimiento y chaptering en MongoDB Atlas

*Estado*: Planeada  
*Fecha*: 2025-04-25  
*Autores*: Equipo IA

## Contexto
Los resultados de análisis de sentimientos y capítulos varían en estructura
y pueden crecer rápidamente.  
Crear tablas relacionales dedicadas supondría migraciones frecuentes.

## Decisión
Persistir los documentos de análisis en **MongoDB Atlas** usando esquema
semiestructurado (colección `call_sentiments`).

## Consecuencias
* Beneficios  
  * Flexibilidad de esquema para futuros atributos (confianza, entidades).  
  * Escalado horizontal gestionado por Atlas.  
* Inconvenientes  
  * Doble base de datos (PostgreSQL + MongoDB) aumenta complejidad operativa.  
  * Consultas JOIN entre llamadas y sentimiento deben resolverse en la capa de aplicación.  
