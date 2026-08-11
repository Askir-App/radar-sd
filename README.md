# RADAR-SD: Monitoreo Urbano Descentralizado (Protocolo Vanguard)

![Status](https://img.shields.io/badge/Status-Active-00ffff?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-ff00ff?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Android-ff00ff?style=for-the-badge)

**RADAR-SD** es una plataforma descentralizada de monitoreo ciudadano diseñada para la detección y reporte de incidencias en la infraestructura urbana (baches, fallas eléctricas, problemas de agua potable, etc.) mediante una red **P2P (Peer-to-Peer) pura**.

A diferencia de las aplicaciones convencionales, RADAR-SD convierte cada dispositivo en un **nodo soberano**. Esto garantiza la operatividad absoluta incluso en apagones tecnológicos o zonas sin cobertura, protegiendo la privacidad mediante criptografía de grado militar y anonimato por diseño.

---

## 🛡️ Arquitectura de Seguridad:

La red no tiene dueños. La integridad se mantiene mediante el **Protocolo Vanguard**, que rige el comportamiento técnico de los nodos:

1.  **Identidad Criptográfica (ECDSA):** No existen cuentas de usuario. La identidad es una llave pública técnica que firma cada transmisión, garantizando la autenticidad sin revelar al sujeto humano.
2.  **Consenso de Veto Comunitario:** La red autogestiona la calidad de la información. Los nodos validadores purgan reportes falsos o spam mediante votación distribuida, afectando la reputación técnica del nodo emisor.
3.  **Privacidad por Diseño (Privacy by Design):** Cumplimiento estricto de la LOPDP y principios de minimización. Los datos personales nunca salen del dispositivo; solo se transmiten incidentes ciudadanos anonimizados.
4.  **Bóveda Local (AES-256):** Toda la base de datos de incidentes y mapas reside cifrada localmente en el almacenamiento del dispositivo.

---

## 🧠 Inteligencia Artificial y Visión de Borde

RADAR-SD integra modelos de IA local para garantizar la utilidad del canal:
*   **Vanguard Vision:** Clasificación automática de infraestructura (Baches, Red Eléctrica, Fugas de Agua) para evitar la congestión de la red con datos irrelevantes.
*   **Filtro Ético:** Procesamiento local para detectar contenido sensible o inapropiado antes de la difusión P2P.

---

## 📡 Tecnología Mesh Local (Google Nearby)

Utilizamos el stack de **Nearby Connections** para crear una red dinámica:
*   **Descubrimiento:** Sincronización directa entre dispositivos vía Bluetooth Low Energy (BLE) y Wi-Fi Direct.
*   **Propagación por Salto:** Los reportes se propagan orgánicamente de nodo a nodo en un radio de acción ciudadana.
*   **Modo Sigilo:** Protocolo de suspensión de radiofrecuencia para ahorrar energía o mantener perfil bajo.

---

## 📂 Transparencia y Documentación Legal

En cumplimiento con la **Ley Orgánica de Protección de Datos Personales (Ecuador)** y las políticas de **Google Play**, este repositorio contiene los pilares legales y técnicos:

| Archivo | Descripción |
| :--- | :--- |
| [`terms.html`](terms.html) | **Protocolo de Red y Reglas de Consenso:** Detalla el Veto de Vanguard y la responsabilidad técnica del nodo. |
| [`privacy.html`](privacy.html) | **Política de Privacidad P2P:** Detalla la anonimización, el uso de sensores y la ausencia de rastreo centralizado. |
| [`credits.html`](credits.html) | **Créditos:** Detalla todos los servicios y librerías usadas en la app. |

> [!TIP]
> La aplicación incluye un **Visor de Protocolos** interno que permite consultar estos documentos offline y, mediante la última actualización, abrirlos en el navegador para auditoría externa.

---

## ⚖️ Responsabilidad y Ética

El uso de RADAR-SD implica la aceptación de la **Neutralidad Tecnológica**:
*   **Anonimato Digital ≠ Impunidad Física:** Se exhorta a los usuarios a evaluar su entorno (CCTV, seguridad física) antes de reportar.
*   **Protección de Terceros:** La aplicación integra herramientas de **desenfocado de rostros y placas** obligatorio para los emisores.
*   **Uso No Partidista:** El sistema prohíbe el uso del canal para propaganda política o acoso.

---

## 📥 Despliegue Operativo

Disponible para dispositivos Android en la vanguardia ciudadana:

[![Get it on Google Play](https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png)](https://play.google.com/store/apps/details?id=app.askir.radar_sd)

---
*RADAR-SD es un protocolo de fuente abierta distribuido para la resiliencia ciudadana en Santo Domingo de los Tsáchilas.*
---
