# Auditoría de Seguridad Interna - Botium Toys

## Contexto y Objetivo

Este documento forma parte de mi portafolio de ciberseguridad. Como parte del proceso de aprendizaje práctico, se presenta una auditoría de seguridad interna basada en una empresa ficticia llamada **Botium Toys**.

**Botium Toys** es una empresa que fabrica y vende juguetes físicos y digitales. A través de sus canales en línea, maneja datos personales de clientes, datos de tarjetas de crédito, y controla maquinaria robótica conectada a su red interna. Aunque es ficticia, representa una situación realista de riesgos de seguridad que enfrentan muchas empresas hoy en día.

**Objetivo:** Evaluar el estado actual de los controles de seguridad de la empresa, verificar el cumplimiento con marcos como **PCI DSS**, **GDPR** y **SOC**, y emitir recomendaciones para mejorar su postura de seguridad.

---

## 1. Evaluación de Controles Existentes

| Control                                 | Implementado |
|-----------------------------------------|--------------|
| Antivirus                               | Sí           |
| Cortafuegos (Firewall)                  | Sí           |
| Sistema de videovigilancia (CCTV)       | Sí           |
| Cerraduras físicas                      | Sí           |
| Detección de incendios                  | Sí           |
| Cifrado de datos                        | No           |
| Copias de seguridad                     | No           |
| Plan de recuperación ante desastres     | No           |
| Gestor de contraseñas                   | No           |
| Monitoreo en tiempo real                | Parcial      |
| Principio de menor privilegio           | No           |
| Separación de funciones                 | No           |

---

## 2. Lista de Comprobación de Cumplimiento

### PCI DSS

| Requisito                                 | Cumple |
|-------------------------------------------|--------|
| Protección de datos del titular de tarjeta| No     |
| Políticas de seguridad claras             | No     |
| Control de acceso basado en roles         | No     |
| Monitoreo y prueba de redes               | Parcial|
| Protección contra malware y antivirus     | Sí     |

### GDPR

| Requisito                                 | Cumple |
|-------------------------------------------|--------|
| Consentimiento del usuario                | Parcial|
| Notificación de brechas en 72 horas       | Sí     |
| Derecho al olvido                         | No     |
| Seguridad de los datos personales         | No     |
| Designación de un DPO (si aplica)         | No     |

### SOC

| Requisito                                 | Cumple |
|-------------------------------------------|--------|
| Control de acceso                         | No     |
| Confidencialidad de la información        | Parcial|
| Privacidad de datos personales (PII)      | No     |
| Integridad del sistema y procesamiento    | Sí     |
| Disponibilidad de la información          | Parcial|

---

## 3. Recomendaciones

- **Implementar cifrado** de datos sensibles, tanto en tránsito como en reposo.
- **Crear copias de seguridad regulares** y almacenarlas fuera del sitio.
- **Desarrollar e implementar un plan de recuperación ante desastres.**
- **Adoptar un gestor de contraseñas seguro** para todos los empleados.
- **Aplicar el principio de menor privilegio**, asegurando que los usuarios solo tengan acceso a lo necesario.
- **Separar funciones críticas** para evitar conflictos de interés o abuso de privilegios.
- **Cumplir con PCI DSS** si se procesan pagos con tarjeta.
- **Mejorar el cumplimiento con GDPR**, incluyendo opciones claras de consentimiento y procedimientos para ejercer derechos del usuario.
- **Actualizar controles SOC**, principalmente en control de accesos y protección de PII.

---

## Conclusión

Botium Toys ha implementado algunos controles básicos como antivirus, CCTV y firewall. Sin embargo, presenta deficiencias importantes en protección de datos, planes de contingencia, y cumplimiento normativo. Se recomienda aplicar las acciones sugeridas para fortalecer su postura de ciberseguridad y proteger los datos de sus clientes y operaciones internas.

---

## Autor

Este análisis fue realizado por mi, David Dael, como parte de mi portafolio personal de aprendizaje en ciberseguridad.

