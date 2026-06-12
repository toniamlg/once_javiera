# Documentación de Requerimientos


**¿Por qué documentar?**
Creer que por hacer encuentas, observaciones y hablar con los clientes toda esa información se tiene que pasar de forma inmediata en vez de "perder el tiempo".

**Mente vs Papel**
**"Lo tengo en la cabeza"**
- Te olvidas detalles en horas o días.
- Nadie más puede acceder a esa información.
- Si te enfermas o renuncias, todo se pierde.
- Imposible auditar o validar.
- Cambia con tu estado de ánimo.

**Documentado en papel**
- Permanece igual a través del tiempo.
- Todo el equipo puede consultarlo.
- Sobrevive a cambios de personal.
- Sirve de evidencia legal.
- Se puede revisar y mejorar.

**Casos reales de no documentar**
Se presentarian problemas por no documentar la información, por si personas externas entran a un empresas donde solo alguien era el programador, dejando un gran problema. No escribir los cambios o peticiones del cliente, puede generar problemas en el futuro, etc.

**Las 5 funciones de la documentación**
1. Acuerdo.
2. Guía.
3. Verificación.
4. Conocimiento.
5. Legal.

## El estándar IEEE 830

**¿Qué es IEEE 830?**
El IEEE 830 es una guía internacional que establece las reglas y la estructura para redactar un documento de Especificación de Requerimientos de Software (SRS).**¿Quién lo creó?** El Institute of Electrical and Electronics Engineers (IEEE). **¿Para qué sirve?** Sirve para que cualquier ingeniero de software en el mundo pueda leer el documento, entender el proyecto perfectamente y hablar el mismo idioma técnico.

**¿Por qué usar IEEE 830?**
**La ventaja:** Da una estructura clara, evita que olvides detalles importantes y mejora la comunicación con el cliente.

**La desventaja:** Puede ser muy pesado, lento de llenar y excesivo para proyectos pequeños o metodologías ágiles.

**Estructura del SRS IEEE 830**
Aquí tienes la estructura del IEEE 830 en su mínima expresión:

1. **Introducción:** Presentación, qué hace (y qué no hace) el sistema y el glosario.

2. **Descripción General:** Visión general (sin tecnicismos) de las funciones, los usuarios y las limitaciones.

3. **Requisitos Específicos:** El núcleo detallado; incluye los Requisitos Funcionales (qué hace), No Funcionales (seguridad/rendimiento) y casos de uso.

4. **Apéndices:** Información extra (diseños de pantalla, diagramas y tablas).


**Características de un buen SRS**
1. Correcto.
2. No ambiguo.
3. Completo.
4. Consistente.
5. Clasificado por importancia.
6. Verificable 
7. Modificable.
8. Trazable.

**Casos de uso**
Un **caso de uso** es la descripción paso a paso de cómo un usuario interactúa con el sistema para lograr un objetivo específico. Básicamente, es una "mini-historia" de esa interacción.

**Componentes de un caso de uso:** actor, sistema, objetico y escenario.

## Plantilla profesional de caso de uso

- **Datos Básicos:** **ID** (código), **Nombre** (verbo + objeto), **Actor** (quién lo usa) y **Descripción** (objetivo).
- **Estados:** **Precondiciones** (requisito previo) y **Postcondiciones** (resultado final exitoso).
- **Caminos (Flujos):** **Principal** (todo sale bien), **Alternos** (otros caminos válidos) y **Excepciones** (qué pasa si algo falla).
- **Control:** **Reglas de negocio** (restricciones), **Frecuencia** (qué tan seguido se usa) y **Prioridad** (importancia de desarrollo).

## Plantilla SRS IEEE — Por Secciones

**Revisión Cruzada**

**¿Qué es la revisión cruzada?** La revisión cruzada es cuando otro analista (o varios) lee TU documento buscando errores, ambigüedades, contradicciones o cosas faltantes. Es la primera defensa contra un mal SRS.

**¿Qué buscar en una revisión cruzada?**
1. Ambigüedades.
2. Contradicciones.
3. Faltantes.
4. No medibles.
5. Dependencias.
6. No atómicos.
7. Jerga técnica innecesaria.
8. Sin verificación posible.

**SRS:** Sistema de Reservas de Salón de Estudio.