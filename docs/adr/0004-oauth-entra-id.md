# ADR-0004 – Autenticación mediante OAuth 2.0 con Microsoft Entra ID

*Estado*: Aceptada  
*Fecha*: 2025-04-02  
*Autores*: Equipo Seguridad

## Contexto
Los usuarios pertenecen a una organización que ya utiliza Microsoft 365.  
Se evita la gestión interna de contraseñas y MFA.

## Decisión
Implementar flujo **OAuth 2.0 Authorization Code + PKCE** contra **Microsoft Entra ID** (antes Azure AD).  
Almacenar únicamente el MSFT UID y el correo.

## Consecuencias
* Beneficios  
  * Inicio de sesión SSO, MFA heredado de políticas corporativas.  
  * Cumplimiento de políticas de TI sin desarrollo extra.  
* Inconvenientes  
  * Límite de llamadas a Microsoft Graph.  
  * La app depende de disponibilidad de Entra ID para login.  
