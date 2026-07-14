# Optimización de Consultas SQL en un Sistema de Gestión de Pedidos

La empresa 'Pragmatic Orders' gestiona un sistema de pedidos en línea para una tienda de artículos tecnológicos. El sistema utiliza una base de datos relacional para almacenar información sobre productos, clientes y pedidos. El equipo de calidad de software ha identificado una brecha en la eficiencia de las consultas SQL utilizadas para generar informes y realizar análisis de ventas. Es necesario mejorar la performance de estas consultas para asegurar que el sistema pueda manejar un mayor volumen de datos sin degradar el rendimiento.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Consultas intermedias |
| **Nivel** | senior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 4-6 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Análisis de Consultas Existentes

**Objetivo:** Identificar las consultas SQL que pueden ser optimizadas.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Revisa las consultas SQL utilizadas actualmente en el sistema para generar informes y realizar análisis de ventas.
- Identifica las consultas que consumen más tiempo de ejecución y analiza sus estructuras para determinar posibles optimizaciones.

**Entregable:** Lista de consultas SQL que pueden ser optimizadas.

<details>
<summary>Pistas de conocimiento</summary>

- Considera el uso de índices para mejorar la velocidad de las consultas.
- Evalúa la posibilidad de reducir la cantidad de datos procesados en cada consulta.

</details>

### Fase 2: Optimización de Consultas

**Objetivo:** Reescribe las consultas SQL identificadas en la fase anterior para mejorar su performance.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Reescribe las consultas SQL identificadas en la fase anterior utilizando técnicas de optimización como el uso de índices, la reducción de la cantidad de datos procesados y la eliminación de subconsultas innecesarias.
- Asegúrate de que las consultas optimizadas mantengan la misma funcionalidad que las consultas originales.

**Entregable:** Consultas SQL optimizadas.

<details>
<summary>Pistas de conocimiento</summary>

- Utiliza la cláusula JOIN en lugar de subconsultas cuando sea posible.
- Considera el uso de funciones agregadas y agrupamiento para reducir la cantidad de datos procesados.

</details>

### Fase 3: Evaluación de Rendimiento

**Objetivo:** Evaluar el rendimiento de las consultas SQL optimizadas.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Ejecuta las consultas SQL optimizadas en la base de datos y mide su tiempo de ejecución.
- Compara el tiempo de ejecución de las consultas optimizadas con el tiempo de ejecución de las consultas originales.
- Documenta los resultados de la evaluación y propone recomendaciones para futuras optimizaciones.

**Entregable:** Reporte de evaluación de rendimiento.

<details>
<summary>Pistas de conocimiento</summary>

- Utiliza herramientas de monitoreo y análisis para medir el tiempo de ejecución de las consultas.
- Considera el impacto de las optimizaciones en el rendimiento general del sistema.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué son las consultas SQL y por qué son importantes en un sistema de gestión de pedidos?
- **paraQueSirve**: ¿Para qué sirven las consultas SQL en el contexto de un sistema de gestión de pedidos?
- **comoSeUsa**: ¿Cómo se pueden optimizar las consultas SQL para mejorar el rendimiento del sistema?
- **erroresComunes**: ¿Cuáles son los errores comunes al optimizar consultas SQL y cómo se pueden evitar?
- **queDecisionesImplica**: ¿Qué decisiones implica la optimización de consultas SQL en términos de rendimiento y mantenibilidad del sistema?

## Criterios de Evaluacion

- Identificar consultas SQL que pueden ser optimizadas.
- Reescribir consultas SQL utilizando técnicas de optimización.
- Evaluar el rendimiento de las consultas SQL optimizadas.
- Documentar los resultados de la evaluación y proponer recomendaciones para futuras optimizaciones.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
