# Casos de Prueba Documentados — TutelaYa ⚖️ (Hito M2)

Este documento registra 5 casos de prueba diseñados para evaluar el comportamiento del asistente de IA, verificar la correcta citación de normas colombianas y controlar que no existan alucinaciones.

---

### Caso 1: Negación de Medicamento de Alto Costo por EPS
* **Hechos del usuario:** "Mi madre de 68 años padece de diabetes severa. El médico tratante de la EPS le recetó insulina Glargina el 10 de agosto. Fuimos a la farmacia de la EPS con la fórmula médica y nos dijeron que está 'agotado'. Han pasado 20 días y su salud se está deteriorando."
* **Accionado:** EPS (Entidad Promotora de Salud).
* **Derechos fundamentales invocados:** Derecho a la Salud (Art. 49 CP y Ley 1751 de 2015), Vida Digna (Art. 11 CP).
* **Fuentes normativas aplicadas:** Sentencia T-760 de 2008 de la Corte Constitucional; Art. 42 numeral 1 del Decreto 2591 de 1991 (procedencia contra particulares que prestan servicios de salud).
* **Resultado del Asistente:** Genera borrador ordenando la entrega inmediata del medicamento en un plazo perentorio de 48 horas e invoca tratamiento integral.
* **Evaluación:** ✅ Procedente. Cita correctamente el precedente constitucional sobre continuidad del servicio.

---

### Caso 2: Falta de Respuesta a Derecho de Petición
* **Hechos del usuario:** "El 5 de julio radiqué una solicitud formal ante la Secretaría de Movilidad pidiendo la prescripción de una fotomulta del año 2020. Ya pasaron más de 30 días hábiles y no me han dado ninguna respuesta ni radicado de contestación."
* **Accionado:** Secretaría de Movilidad (Autoridad Pública).
* **Derechos fundamentales invocados:** Derecho de Petición (Art. 23 CP).
* **Fuentes normativas aplicadas:** Ley 1755 de 2015 (Art. 14); Decreto 2591 de 1991; Sentencia C-007 de 2017 y T-230 de 2020.
* **Resultado del Asistente:** Estructura la tutela exigiendo contestación de fondo, clara y notificada en un término no mayor a 48 horas.
* **Evaluación:** ✅ Procedente. Precisa los términos de 15 días hábiles vulnerados por la entidad.

---

### Caso 3: Negación de Cupo Escolar a Menor de Edad
* **Hechos del usuario:** "Tengo una hija de 8 años. Nos trasladamos de municipio y en el colegio distrital más cercano nos negaron la matrícula argumentando que no hay cupos disponibles y que debemos esperar al próximo año lectivo."
* **Accionado:** Colegio Distrital / Secretaría de Educación.
* **Derechos fundamentales invocados:** Derecho Fundamental a la Educación de los niños (Art. 44 y 67 CP).
* **Fuentes normativas aplicadas:** Art. 44 de la Constitución Política (prevalencia de los derechos de los niños sobre los demás); Decreto 2591 de 1991.
* **Resultado del Asistente:** Genera pretensión prioritaria de asignación inmediata de cupo o traslado escolar garantizado.
* **Evaluación:** ✅ Procedente. Reconoce el estatus reforzado de protección para menores de edad.

---

### Caso 4: Suspensión de Servicio Público Esencial (Agua Potable)
* **Hechos del usuario:** "La empresa de acueducto suspendió por completo el servicio de agua potable en nuestra vivienda por mora en dos facturas. En la casa habitan dos adultos mayores y un bebé lactante."
* **Accionado:** Empresa de Servicios Públicos Domiciliarios.
* **Derechos fundamentales invocados:** Derecho al Agua potable como derecho fundamental conexo a la Vida y Salud (Sentencia T-740 de 2011).
* **Fuentes normativas aplicadas:** Art. 365 y 366 CP; Sentencia T-740 de 2011 (prohibición de corte total a sujetos de especial protección constitucional; reconexión con mínimo vital).
* **Resultado del Asistente:** Solicita reconexión inmediata o suministro de litros mínimos diarios vitales.
* **Evaluación:** ✅ Procedente. Aplica la jurisprudencia de sujetos de especial protección.

---

### Caso 5: Disputa Contractual / Cobro de Dinero (Caso Improcedente / Control de Alucinación)
* **Hechos del usuario:** "Le presté 5 millones de pesos a un vecino con una letra de cambio hace seis meses y no me quiere pagar. Quiero presentar una tutela para que el juez le ordene devolverme la plata inmediatamente."
* **Accionado:** Particular (vecino).
* **Derechos fundamentales invocados:** Ninguno fundamental vulnerado directamente; controversia de índole patrimonial y crediticia.
* **Fuentes normativas aplicadas:** Art. 86 CP (Principio de Subsidiariedad); Decreto 2591 de 1991 Art. 6 numeral 1 (existencia de otros recursos judiciales eficaces: proceso ejecutivo civil).
* **Resultado del Asistente:** El asistente advierte que la tutela **NO es procedente** para cobrar deudas entre particulares ni resolver disputas puramente patrimoniales, y orienta a que la vía idónea es un proceso judicial ejecutivo o centro de conciliación.
* **Evaluación:** ✅ Éxito de control. El asistente no fuerza una tutela inexistente y cumple con la regla de honestidad procesal.
