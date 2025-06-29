# Contabilidad Gerencial · CyTA

Este repositorio contiene desarrollos vinculados al análisis del Estado de Resultados de pequeñas empresas, integrando herramientas digitales, lógica contable y generación de prompts para inteligencia artificial (IA).

Los proyectos se encuentran enmarcados en el modelo MOA (Modelo de Organización de Aprendizajes) impulsado desde [CyTA](https://cyta.com.ar).

---

## 🧩 Contenidos

### 1. `estado_resultados.php` — Versión genérica
Formulario en PHP 5.6 que permite ingresar los valores de los principales rubros de un Estado de Resultados. Calcula subtotales y genera automáticamente un prompt adaptado para su análisis con ChatGPT.

🔗 Ver en línea:  
[https://cyta.com.ar/cybercyta/moa/estado_resultados.php](https://cyta.com.ar/cybercyta/moa/estado_resultados.php)

### 2. `estado_resultados_rt9.php` — Versión basada en RT N.º 9 (FACPCE)
Versión adaptada al modelo alternativo definido por la Resolución Técnica N.º 9 de la FACPCE. Incluye:

- Rubros contables diferenciados por función (comercialización, administración)
- Resultado financiero y por tenencia
- Cálculo del resultado del ejercicio
- Subtotales destacados visualmente
- Prompt automático ajustado al tipo de empresa y normativa aplicada

🔗 Ver en línea:  
[https://cyta.com.ar/cybercyta/moa/estado_resultados_rt9.php](https://cyta.com.ar/cybercyta/moa/estado_resultados_rt9.php)

---

## 🎯 Objetivos

- Fomentar la enseñanza de la contabilidad gerencial a través de herramientas interactivas
- Promover el análisis financiero apoyado en IA (ChatGPT)
- Facilitar la incorporación de normas contables argentinas (RT 9)
- Documentar buenas prácticas de curación semántica y metadatos

---

## 🧠 Tecnologías utilizadas

- PHP 5.6 (compatible con servidores legacy)
- HTML5 + CSS
- JSON-LD para Schema.org
- Lógica contable adaptada a pequeñas empresas
- Generación automática de prompts para ChatGPT

---

## 🏷️ Metadatos semánticos

Cada versión incluye metadatos en formato `JSON-LD` conforme a `schema.org`, validados con [validator.schema.org](https://validator.schema.org) y Google.  
Se utilizan las clases `SoftwareApplication`, `FinancialStatement` y `MonetaryAmount` según corresponda.

---

## 🤖 IA y créditos

El desarrollo fue asistido por ChatGPT (OpenAI) con curación técnica y adaptación pedagógica realizada por **Marcelo Claudio Perissé**.

Más información sobre IA en CyTA:  
[https://cyta.com.ar/cybercyta/](https://cyta.com.ar/cybercyta/)

---

## 📄 Licencia

Uso libre, educativo y sin fines comerciales. Más detalles en:  
[https://cyta.com.ar/licencia](https://cyta.com.ar/licencia)

