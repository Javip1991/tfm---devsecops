# Política de Seguridad de la Información

## 1. Objetivo

Esta política establece los principios y medidas de seguridad aplicables al laboratorio de ciberseguridad desarrollado en el marco del TFM.

Su objetivo es proteger la confidencialidad, integridad y disponibilidad de los sistemas, aplicaciones, credenciales, registros y datos utilizados en el laboratorio.

## 2. Alcance

La política aplica a:

- Sistemas operativos y máquinas virtuales.
- Servidores y aplicaciones desplegadas en el laboratorio.
- Aplicaciones web utilizadas para las pruebas.
- Herramientas de análisis, explotación y monitorización.
- Credenciales y cuentas de usuario.
- Registros y evidencias generados durante las pruebas.
- Repositorios de código y documentación del proyecto.
- Equipos utilizados para administrar el laboratorio.

## 3. Control de acceso

El acceso a los sistemas deberá realizarse mediante cuentas identificadas.

Se aplicará el principio de mínimo privilegio, proporcionando únicamente los permisos necesarios para realizar cada actividad.

Las cuentas administrativas se utilizarán exclusivamente para tareas que requieran privilegios elevados.

Las credenciales no deberán almacenarse en código fuente ni compartirse mediante canales inseguros.

## 4. Política de contraseñas

Las contraseñas deberán:

- Tener una longitud mínima de 12 caracteres.
- Combinar mayúsculas y minúsculas.
- Incluir números.
- Incluir caracteres especiales.
- No utilizar información personal.
- No reutilizarse entre servicios.
- Cambiarse inmediatamente ante sospecha de compromiso.

Se recomienda utilizar un gestor de contraseñas.

## 5. Autenticación multifactor

La autenticación multifactor deberá utilizarse en cuentas con acceso a sistemas críticos o información sensible.

Durante el desarrollo del laboratorio se ha habilitado MFA/2FA en GitHub mediante una aplicación de autenticación.

## 6. Seguridad de red

El laboratorio deberá mantenerse aislado de sistemas no autorizados.

Las comunicaciones estarán restringidas mediante reglas de firewall siguiendo el principio de mínimo privilegio y deny-by-default.

Las pruebas de seguridad únicamente podrán realizarse contra sistemas pertenecientes al laboratorio o aquellos para los que exista autorización expresa.

## 7. Gestión de vulnerabilidades

Los sistemas deberán analizarse periódicamente mediante herramientas de identificación de vulnerabilidades.

Las vulnerabilidades detectadas deberán documentarse incluyendo:

- Identificador CVE cuando exista.
- Severidad.
- CVSS cuando esté disponible.
- Sistema afectado.
- Evidencia.
- Impacto.
- Medidas de mitigación.

## 8. Desarrollo seguro

El código desarrollado deberá someterse a controles de seguridad.

Se utilizarán herramientas SAST para detectar vulnerabilidades en el código fuente y herramientas DAST para analizar aplicaciones en ejecución.

El pipeline DevSecOps incorporará controles automatizados de seguridad.

## 9. Registro y monitorización

Los eventos relevantes de seguridad deberán registrarse y conservarse durante un periodo adecuado.

Se deberán monitorizar especialmente:

- Autenticaciones.
- Elevaciones de privilegios.
- Errores de aplicación.
- Actividad sospechosa.
- Accesos a recursos sensibles.
- Eventos relacionados con ataques.

## 10. Respuesta ante incidentes

Ante un incidente de seguridad se deberán realizar, como mínimo, las siguientes fases:

1. Identificación.
2. Contención.
3. Erradicación.
4. Recuperación.
5. Análisis posterior al incidente.

Las evidencias deberán conservarse evitando su modificación accidental.

## 11. Copias de seguridad

La documentación, configuraciones y evidencias relevantes deberán disponer de copias de seguridad.

Las copias deberán protegerse frente a accesos no autorizados y comprobarse periódicamente.

## 12. Gestión de cambios

Los cambios importantes en sistemas, configuraciones y aplicaciones deberán documentarse.

Antes de realizar modificaciones críticas se deberá disponer de una copia de seguridad o mecanismo de recuperación cuando sea posible.

## 13. Uso aceptable

Los sistemas del laboratorio únicamente podrán utilizarse para actividades académicas, de formación, análisis y pruebas de seguridad autorizadas.

Queda prohibido utilizar las herramientas del laboratorio contra sistemas de terceros sin autorización.

## 14. Revisión

La presente política deberá revisarse al menos anualmente o cuando se produzcan cambios significativos en la arquitectura, amenazas o requisitos de seguridad.
