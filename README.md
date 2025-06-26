# Proyecto_4_pruebas_de_API
# Proyecto QA – Pruebas de API en Postman (Urban.Grocers)

Este proyecto corresponde al proceso de pruebas sobre la aplicación **Urban.Grocers**. En esta ocasión, el enfoque principal fue la validación de nuevas funcionalidades implementadas en el **back-end (API)**, mediante pruebas manuales en **Postman**, y la documentación de errores encontrados a través de **Jira**.

El objetivo fue asegurar que las nuevas funciones para el manejo de kits y servicios de entrega funcionen correctamente, según los requisitos proporcionados por el equipo de desarrollo.

---

## 🎯 Objetivo del Proyecto

- Analizar los requisitos de las nuevas funcionalidades de la API.
- Diseñar una lista de comprobación para verificar los endpoints nuevos.
- Probar la API usando **Postman**.
- Reportar errores encontrados en **Jira**.
- Documentar los resultados de prueba de manera clara y ordenada.

---

## 📁 Archivos incluidos en el repositorio

- `lista_comprobacion_api_urban_grocers.xlsx`:  
  Documento con la lista de comprobación detallada, diseñada para cubrir todos los escenarios de prueba de los endpoints nuevos, incluyendo pruebas positivas y negativas.

---

## 🔧 Funcionalidades probadas

### 1. 🧺 Endpoint: Agregar productos a un kit  
`POST /api/v1/kits/{id}/products`

- Se verificó la capacidad de agregar comestibles a un kit.
- Se comprobó que el endpoint rechaza listas de productos con más de **30 elementos**, retornando correctamente un **400 Bad Request**.
- Se realizaron pruebas positivas (listas válidas) y negativas (listas excedidas, kits inexistentes, campos vacíos, etc.).

### 2. 🚚 Endpoint: Verificar disponibilidad del servicio Order and Go  
`POST /order-and-go/v1/delivery`

- Se evaluó la respuesta del endpoint para determinar si el servicio está disponible y cuánto cuesta.
- Se validaron los cálculos de precio de entrega según los parámetros de entrada.
- Se probaron distintos escenarios: datos completos, campos faltantes, datos inválidos, zonas no cubiertas, etc.

---

## 🧪 Herramientas utilizadas

- **Postman**: Para ejecutar las peticiones HTTP y validar las respuestas de la API.
- **Jira**: Para la documentación y seguimiento de errores encontrados durante las pruebas.
- **Google Sheets**: Para crear y organizar la lista de comprobación de pruebas.

---

## 🐞 Reporte de errores

Todos los errores encontrados fueron documentados en **Jira**, incluyendo:

- Descripción clara del error.
- Pasos para reproducirlo.
- Resultado esperado vs. resultado actual.
- Severidad asignada.
- Enlaces a los tickets están referenciados en la hoja de cálculo, en la columna "ID de error".

---

## 💼 Rol desempeñado

- Análisis de requisitos de back-end.
- Diseño de una lista de comprobación estructurada y completa.
- Ejecución de pruebas en Postman (escenarios positivos y negativos).
- Reporte profesional de errores en Jira, siguiendo buenas prácticas de documentación.
- Organización de resultados y evidencias para su revisión.

---

## ✅ Estado del proyecto

✔️ Proyecto finalizado:  
Todas las pruebas fueron ejecutadas exitosamente, y los errores encontrados fueron documentados correctamente.

---
