# ADR-0001 – Adoptar Next.js (App Router) para la capa UI

*Estado*: Aceptada  
*Fecha*: 2025-03-15  
*Autores*: Equipo Frontend

## Contexto
La rúbrica del curso exige un framework React-based con capacidad SSR/SSG.
El equipo ya ha desarrollado dos proyectos previos en Next.js 13, por lo que posee experiencia y componentes reutilizables.

## Decisión
Usar **Next.js 15.2.4** con el nuevo **App Router** como base de la interfaz.

## Consecuencias
* Beneficios  
  * SSR/SSG automáticos, optimización de imágenes (`next/image`) y división de código.  
  * Integración nativa con Vercel Edge y Serverless Functions.  
  * Estructura de rutas + layouts claramente tipada en TypeScript.  
* Inconvenientes  
  * Dependencia fuerte del ecosistema Vercel.  
  * Convención sobre configuración puede limitar personalizaciones profundas.  
