# Security Policy – Conducción Segura

## Introducción
La seguridad de nuestros usuarios es una prioridad en **Conducción Segura**. Agradecemos a la comunidad por ayudarnos a identificar y reportar vulnerabilidades de manera responsable.

## Alcance
Esta política aplica al ecosistema de **Conduccion Segura**, incluyendo:
- Aplicación móvil y web desarrollada en Flutter.
- Servicios backend integrados con Firebase (Auth, Firestore).
- Funcionalidades de geolocalización y mapas (OpenStreetMap vía flutter_map).

No aplica a servicios de terceros fuera de nuestro control.

## Cómo Reportar Vulnerabilidades
Si detecta una vulnerabilidad de seguridad, repórtela **de forma privada** enviando un correo a:

**conduccionseguracuc@gmail.com**  

Incluya la siguiente información:
- Descripción clara de la vulnerabilidad.
- Pasos reproducibles (si aplica).
- Evidencias técnicas (logs, capturas de pantalla, código de prueba).
- Impacto estimado y condiciones en las que ocurre.
- Información de contacto (opcional, si desea seguimiento).

⚠️ **No use Issues públicos ni discusiones del repositorio para reportar vulnerabilidades.**

## Tiempo de Respuesta
- Confirmación de recepción: ≤ 5 días hábiles.
- Evaluación inicial: ≤ 10 días hábiles desde la confirmación.
- Comunicación de avances: se mantendrá informado al investigador durante el proceso.

## Lineamientos
Para investigaciones de seguridad se espera:
- No exfiltrar ni divulgar datos reales de usuarios.
- No realizar ataques de denegación de servicio.
- No utilizar ingeniería social ni técnicas similares.
- Respetar siempre la privacidad y legalidad.

## Versiones Soportadas
Solo se garantiza soporte de seguridad en la **última versión estable** de la aplicación.

## Prácticas de Seguridad Implementadas
- Autenticación con Firebase Authentication.
- Reglas de seguridad en Firestore.
- Comunicación cifrada mediante HTTPS/TLS.
- Minimización de permisos de geolocalización.
- Monitoreo y control de versiones en despliegues.

## Divulgación Responsable
Le pedimos no divulgar públicamente vulnerabilidades hasta que:
1. Hayan sido reportadas de forma privada.
2. Se haya dado tiempo razonable para investigar y resolver.
3. Se haya coordinado una comunicación pública responsable.

## Agradecimientos
Reconocemos a los investigadores que colaboran con reportes responsables.  
*(Sección en actualización; añadiremos nombres con el consentimiento de cada colaborador.)*

---

**Contactos de seguridad:**  
Oscar David Navarro Villamizar  
Luis Angel Quiros Flores  
Correo: conduccionseguracuc@gmail.com
