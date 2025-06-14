# ADR-0002 – Usar Prisma ORM con PostgreSQL 15

*Estado*: Aceptada  
*Fecha*: 2025-03-15  
*Autores*: Equipo Backend

## Contexto
Se requiere un motor relacional ACID para manejar relaciones complejas (usuarios-proyectos-llamadas).  
El equipo valora el tipado fuerte en TypeScript y el versionado de esquemas.

## Decisión
Adoptar **Prisma 6.9** como ORM y **PostgreSQL 15** alojado en **Prisma Platform**.

## Consecuencias
* Beneficios  
  * Type-safety end-to-end: consultas 100 % tipadas.  
  * Migraciones controladas (`prisma migrate`).  
  * Soporte de transacciones multi-paso.  
* Inconvenientes  
  * Prisma Client genera binarios por cada versión de Node (impacto en build).  
  * Bloqueo parcial al ecosistema Prisma Platform para hosting administrado.  
