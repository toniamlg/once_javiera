# Profundización del concepto
---
# Clase 2

**ingeniería del software**: Un **requerimiento** es una propiedad documentada que un sistema debe poseer para resolver un problema o lograr un objetivo. Es una **declaración verificable** de una funcionalidad, restricción o característica de calidad.
---

**Niveles de abstracción**

- Especificación técnica.
- Requerimiento del sistema.
- Necesidad del usuario.

**Fuentes de requerimientos**
Estos viene de diferentes **stakeholders**.

- Usuarios finales.
- Clientes / patrocinadores.
- Leyes y normas.
- Sistemas externos.

**Características de un BUEN requerimiento**
Se deben cumplir 7 cualidades:

1. **Necesario**: Si este no esta, el sistema no cumple su función.
2. **No ambiguo**: Una sola interpretación posible.
3. **Verificable**: Se puede probar si se cumple o no.
4. **Consistente**: No contradice a otro requerimiento.
5. **Consistente**: No contradice a otro requerimiento.
6. **Atómico**:  Una sola idea por requerimiento.
7. **Trazable**: Se puede rastrear de dónde vino y a qué afecta.

---

#  Requerimientos Funcionales

Un **requerimiento funcional** (RF) describe una acción concreta que el sistema debe realizar. Define las funciones, tareas, cálculos o respuestas del sistema ante entradas específicas.

**Cómo identificarlos**
 - Verbos de acción.
 - Entradas y salidas.
 - Decisiones.
 - Roles.
 - Plantilla profesional.

   **Categorías de RF**
- Autenticación.
- cálculo.
- Persistencia.
- Comunicación.
- Reporte.
- Validación.

---

# Requerimientos No Funcionales
---

Un **requerimiento no funcional** (RNF) describe **cómo debe comportarse** el sistema, no qué hace. Define características de calidad, restricciones y propiedades que el sistema debe cumplir.

Estos son criticos porque un sistema puede ser funcionalmente perfecto y a la vez un fracaso total si descuida los RNF.

**Categorías de RNF**
- Rendimiento.
- Seguridad.
- Usabilidad.
- Confiabilidad.
- Escalabilidad.
- Mantenibilidad.
- Portabilidad / Compatibilidad.
- Legales / Regulatorios.

**Regla de oro: Medir**

Un RNF sin métrica es un deseo, no un requerimiento. Para cada RNF debes responder:

 - ¿Qué métrica usas? (tiempo, %, número de usuarios, etc.)
 - ¿Cuál es el umbral aceptable?
 - ¿Cómo lo vas a verificar?

 **Trade-offs: cuando los RNF chocan**

- Seguridad - Usabilidad.
- Rendimiento - Mantenibilidad.
- Escalabilidad - Costo

Un buen analista balancea los trade-offs según lo más importante para el cliente.

---

# Atributos de Calidad

---

Los **atributos de calidad** son las características generales que determinan qué tan bueno es un software. Son los conceptos abstractos que luego se concretan en los RNF.

**RNF vs Atributos: la diferencia**

Atributo de calidad = concepto general.
RNF = forma concreta y medible del atributo.

**Los 8 atributos según ISO 25010**

1. Adecuación funcional.
2. Eficiencia de desempeño.
3. Compatibilidad.
4. Usabilidad.
5. Confiabilidad.
6.  Seguridad.
7. Mantenibilidad.
8. Portabilidad.

# Taller: Análisis de Necesidades + Caso Simulado

Ejercicios para realizar, según lo visto anteriormente.

---

**Historias de Usuario**

Una **historia de usuario es una descripción corta y simple** de un requerimiento contada desde la perspectiva del usuario que lo necesita. Nacieron en las metodologías ágiles (Scrum, XP) y son el corazón de muchísimos equipos modernos.

NO reemplazan a los RF formales, sino que son **otra forma de expresarlos**, más conversacional y centrada en el valor del usuario.

**Fórmula mágica**

1. Como [usuario]: ¿quién lo necesita?
2. Quiero [acción]: ¿qué quiere hacer?
3. Para [beneficio]: ¿por qué lo quiere? (el famoso "para qué")

**INVEST — Las 6 reglas de oro**
1. Independent  (Independiente).
2. Negotiable (Negociable).
3. Valuable (Valiosa).
4. Estimable (Estimable).
5. Small (Pequeña).
6. Testable (Testeable).

---

**Criterios de Aceptación**

Son las condiciones obligatorias para que una historia de usuario se 
considere terminada (sin ellos, es solo un deseo). Se escriben como Dado / Cuando / Entonces.
