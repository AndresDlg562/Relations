# ADR-0003 – Monolito modular (front y API) desplegado en Vercel

*Estado*: Aceptada  
*Fecha*: 2025-03-18  
*Autores*: Equipo completo

## Contexto
Plazo de un semestre y recursos limitados.  
La clase evalúa el diseño, no la complejidad de DevOps.

## Decisión
Mantener **dos repos independientes** (front y API) pero cada uno como **monolito modular**, desplegados en **Vercel Hobby** (región West Virginia).

## Consecuencias
* Beneficios  
  * Simplicidad operacional (sin Kubernetes, sin microservicios).  
  * CI/CD integrado: push a `main` = deploy automático.  
* Inconvenientes  
  * Escalado limitado a las cuotas free-tier.  
  * Cambios grandes en una parte del backend implican redeploy completo.  
  * Comunicación entre módulos internos no está aislada por red (menos resiliencia).  
