# 🏦 BP Internet Banking – Arquitectura de Solución

Este repositorio contiene el documento y los diagramas correspondientes al diseño arquitectónico del sistema **BP Internet Banking**, desarrollado como propuesta técnica de solución.

## 📘 Entregables

| Archivo | Descripción |
|----------|-------------|
| [BP_Internet_Banking_Arquitectura.pdf](BP_Internet_Banking_Arquitectura.pdf) | Documento principal con análisis, diagramas C4, justificaciones y cumplimiento normativo. |
| [BP_Internet_Banking_Arquitectura.drawio](BP_Internet_Banking_Arquitectura.drawio) | Archivo editable con todas las vistas arquitectónicas (niveles C4 y soporte). |
| [/exports](./exports) | Diagramas exportados en formato PNG para visualización rápida. |

## 🧩 Contenido del archivo Draw.io

| Pestaña | Descripción |
|----------|-------------|
| C4 - Nivel 1 - Contexto | Actores, sistemas externos y límites del sistema. |
| C4 - Nivel 2 - Contenedores | Microservicios, bases de datos y componentes cloud. |
| C4 - Nivel 3 - Transferencias | Estructura interna del servicio de transferencias. |
| C4 - Nivel 3 - Onboarding | Validación biométrica con Uanataca y registro en Entra ID. |
| Segmentación y Acoplamiento | Relación entre dominios funcionales y responsabilidades. |
| Infraestructura y Seguridad | Alta disponibilidad, monitoreo y componentes Azure. |

## ⚙️ Tecnologías principales

- **Azure Kubernetes Service (AKS)** – Orquestación de microservicios.  
- **Azure API Management (APIM)** – Gateway de seguridad y versionamiento de APIs.  
- **Azure Entra ID (OAuth2 + OIDC)** – Autenticación centralizada.  
- **Uanataca** – Validación facial y documental (KYC/PYC).  
- **Azure SQL / Cosmos DB / Redis** – Persistencia, auditoría y cache.  
- **Terraform** – Despliegue automatizado (IaC).

## 🔐 Cumplimiento

Cumple con estándares **ISO 27001**, **PCI DSS**, **GDPR**, **PSD2** y **PYC**, asegurando trazabilidad, protección de datos y auditoría completa.

---

👤 **Autor:**  
**Iván Lima Coronel**  

