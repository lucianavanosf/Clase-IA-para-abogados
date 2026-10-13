# Reglas del Proyecto: TutelaYa ⚖️🤖

## Contexto del Proyecto
Este es un proyecto académico de la asignatura **Derecho e Inteligencia Artificial** (Pontificia Universidad Javeriana · 2026-II) desarrollado por **Luciana Margarita Vaños Fuentes**.

**Nombre de la herramienta:** TutelaYa  
**Lema:** Derecho al alcance de todos  
**Objetivo:** Ayudar a personas sin formación jurídica a estructurar los hechos de su caso, identificar posibles vulneraciones a derechos fundamentales en Colombia y redactar un borrador de acción de tutela fundamentado rigurosamente en un corpus jurídico real.

---

## Directrices para el Asistente de IA

1. **Rigor Jurídico Colombiano:**
   - Todas las referencias normativas deben basarse en el ordenamiento jurídico colombiano (Constitución Política de Colombia, Decreto 2591 de 1991, leyes estatutarias y jurisprudencia de la Corte Constitucional).
   - **Cero alucinaciones:** Nunca inventar artículos, decretos o sentencias. Si no hay suficiente información en el corpus o en las normas verificables, indicar expresamente la limitación.

2. **Lenguaje Claro y Pedagógico:**
   - La herramienta está orientada a personas no abogadas. Explicar conceptos procesales y derechos de forma comprensible, evitando tecnicismos innecesarios o explicándolos de forma sencilla.

3. **Alcance y Advertencias:**
   - Recordar siempre que la herramienta genera borradores orientativos y no sustituye la asesoría legal de un abogado titulado ni garantiza la concesión de la tutela por un juez de la República.

4. **Estructura del Proyecto:**
   - `corpus/`: Documentos y fuentes jurídicas en texto o markdown para el sistema RAG.
   - `docs/`: Casos de prueba, bitácoras y documentación de diseño.
   - Código en Python (ej. Streamlit / LangChain) estructurado de manera simple y modular.
