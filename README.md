# ⚡ AI & Business Process Automation System

> Sistema integral de automatización inteligente diseñado para optimizar el ciclo de vida de leads, generación de propuestas comerciales y comunicación con proveedores mediante **n8n** e integración de modelos de **IA Generativa**.

[![n8n](https://img.shields.io/badge/Workflow-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)](https://n8n.io/)
[![OpenAI](https://img.shields.io/badge/AI-OpenAI%20%2F%20Claude-412991?style=flat-square&logo=openai&logoColor=white)](https://openai.com/)
[![Google Workspace](https://img.shields.io/badge/Integrations-Google%20Workspace-4285F4?style=flat-square&logo=google&logoColor=white)](https://workspace.google.com/)
[![License](https://img.shields.io/badge/Blueprint-Open%20Source-2ea44f?style=flat-square)](./)

---

## 📹 Video Walkthrough & Demo

[![Watch Demo](https://img.shields.io/badge/Loom-Ver%20Demo%20en%20V%C3%ADdeo%20(Walkthrough)-625DF5?style=for-the-badge&logo=loom&logoColor=white)](https://www.loom.com/share/ab6296c05d6e4937ae9e429e08079945)

---

## 🎯 Impacto & Objetivo de Negocio

El proyecto resuelve la fricción manual en la gestión comercial y técnica:
* **Escalabilidad operativa:** Aumento de capacidad de **50 a 100 ofertas comerciales mensuales** sin incremento de carga operativa manual.
* **Reducción de tiempos:** Disminución drástica en los tiempos de respuesta y seguimiento a proveedores/clientes.
* **Estandarización:** Clasificación automática de necesidades y redacción estructurada asistida por LLMs.

---

## ⚙️ Workflows & Blueprints (n8n)

A continuación se detallan los módulos desarrollados en el sistema (descargables e importables en formato JSON):

| # | Módulo / Flujo | Descripción Técnica | Blueprint JSON |
| :--- | :--- | :--- | :--- |
| **01** | **Recepción de Leads** | Ingesta, validación y almacenamiento estructurado de solicitudes inbound. | [📥 Descargar JSON](./1-recepcion-de-leads-spp.json) |
| **02** | **Selección & Redacción** | Enrutamiento inteligente y generación asistida por IA de propuestas/correos. | [📥 Descargar JSON](./2-seleccion-y-redaccion-de-correos.json) |
| **03** | **Seguimiento Proveedores** | Monitorización de estados, alertas automáticas y trazabilidad de respuestas. | [📥 Descargar JSON](./3-seguimiento-correos-proveedores.json) |

---

## 🛠️ Stack Tecnológico & Arquitectura

* **Motor de Automatización:** n8n (Lógica de control, webhooks, triggers y transformaciones).
* **Capa de Inteligencia Artificial:** Modelos LLM (OpenAI API / Claude) para extracción de entidades, clasificación y redacción contextual.
* **Integraciones & Datos:** Google Workspace (Sheets como base de datos operacional, Drive para almacenamiento y Gmail API).
* **Protocolos:** REST APIs, Webhooks, JavaScript (Data formatting y parseo de payloads JSON).

---

## 📄 Documentación Técnica

Para un desglose detallado de la arquitectura de datos, diagramas de flujo y análisis de viabilidad, consulta la memoria completa:

👉 [📘 Descargar Memoria Técnica del Proyecto (PDF)](<./MemoraTFM_Leandro_Da Silva.pdf>)
