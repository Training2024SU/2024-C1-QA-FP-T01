# Resumen Certified Tester Fundation Level

> By: Jesus David Bonelo Cuellar

## 1. Fundamentos de la Prueba

### ¿Qué es probar?

Es el conjunto de actividades para evaluar la calidad del software, descubrir defectos y ayudar a reducir el riesgo de falla del software en funcionamiento.

Las pruebas son mayormente una actividad intelectual que requiere:

- Conocimientos especializados
- Habilidades analíticas
- Pensamiento crítico
- Pensamiento sistémico

**Verificar:** verificar que el sistema cumpla con los requisitos especificados.
**Validar:** comprobar si el sistema acumple con las necesidades de los usuarios y las partes interesadas.

Pruebas dinamicas: ejecutan software, derivan casos de prueba, desencadenan fallas causadas por defectos en el software.

Pruebas estáticas: no ejecutan software, incluye revisiónes y análisis estático, no pueden causar fallas, encuentran directamente defectos en el objeto de prueba, los cuales para su depuración no necesitan reproducción ni diagnóstico.

**Depuración:** Se realiza sobre un defecto.

- Reproducción de la falla
- Diagnóstico (encontrar la causa raíz)
- Corregir la causa

### ¿Por qué es necesario probar?

- Para detectar defectos lo que contribuye indirectamente a mejorar la calidad del objeto de prueba.
- Al involucrarse en el ciclo de vida del desarrollo de software, contribuye a las desiciones de pasar de etapa o la entrega.
- Para cumplir con requisitos contractuales o legales, o complir con estandares reglamentarios.

Aseguramiento de calidad (QA) es un enfoque preventivo centrado en los procesos, la implementación y mejora de éstos.

Control de calidad (QC) es un enfoque correctivo orientado al producto, centrado en actividades que apoyen el logro de niveles de calidad.
Las pruebas son una forma de QC. Los resultados se utilizan en QA y QC

**Defectos(bug)** pueden resultar en fallas.  SKILL ISSUE MENTIONED HAHA

**Causa raíz** es la razón fundamental para la ocurrencia de un problema.

### Principios de la Prueba

1. Las pruebas muestran la presencia, no la ausencia de defectos.
2. Las pruebas exhaustivas son imposibles.
3. Las pruebas tempranas ahorran tiempo y dinero.
4. Los defectos se agrupan. // Pareto, importante para pruebas basadas en riesgo.
5. Las pruebas se desgastan.
6. Las pruebas dependen del contexto.
7. Falacia de la ausencia de defectos. // validación!! > verificación

### Actividades, Testware y Roles de la Prueba

**Roles:** Gestor de pruebas (GP) y Probador (P)

Las actividades componen un proceso, el cual se debe adaptar dependiendo el contexto del systema y proyecto. Algunas actividades comunes son:

- (GP) **Planificación** definición de objetivos, enfoque y limitaciónes
- (GP) **Monitoreo y control de prueba** monitoreo de las actividades, comprobación del progreso y toma de acciones para cumplir los objetivos de las pruebas.
- (P) **Análisis de prueba** ***¿Qué probar?*** identificación de caracteristicas comprobables del objeto de prueba, priorización y riesgo de las pruebas.
- (P) **Diseño de prueba** ***¿Cómo probar?*** elaboración de casos de prueba. Definición de requisitos, entorno, herramientas, etc.
- (P) **Implementación de la prueba** creación o adquisición de lo necesario para la ejecución, datos, scripts manuales y automatizados, cronograma, entorno.
- (P) **La ejecución de pruebas** Ejecución, comparación de los resultados obtenidos y los esperados, repoprtes, análisis de anomalías.
- (GP) **Finalización de prpuebas** archivo, entrega de información útil, cierre de entorno, review general e informe de finalización.

**Contexto:** Partes interesadas, Miembros del equipo, Dominio del negocio, Factores técnicos, Limitaciones del proyecto, Factores organizativos, Ciclo de vida del desarrollo de software, Herramientas.

**Impacto:** estrategia, técnicas, automatización, cobertura, documentación, informes, etc.

**Testware:** productos de trabajo de salida de las actividades ^^

**Trazabilidad** importante para el seguimiento, la cobertura, etc.

### Habilidades y buenas prácticas

- Conocimiento en pruebas
- Rigurosidad, atención al detalle, ser metódico
- Habilidades de comunicación y trabajo en equipo. (Los probadores son a menudo los portadores de malas noticias.)
- Pensamiento analítico, crítico y creatividad.
- Conocimientos técnicos
- Conocimiento del dominio

**Enfoque de equipo completo**

- Cualquier miembro del equipo con los conocimientos y habilidades necesarios puede realizar cualquier tarea, y todos son responsables de la calidad.
- Esto incluye colaborar con representantes de negocios para ayudarlos a crear pruebas de aceptación adecuadas y trabajar con desarrolladores para acordar la estrategia de prueba.
- **Los probadores pueden transferir el conocimiento de las pruebas a otros miembros del equipo e influir en el desarrollo del producto.**

**Independencia:**

- Es mejor llevar a cabo pruebas con diferentes niveles de independencia (unit, integration, acceptance).
- Los probadores indepenientes pueden reconocer diferentes tipos de fallas y defectos debido a sus diferentes antecedentes, perspectivas y sesgos

