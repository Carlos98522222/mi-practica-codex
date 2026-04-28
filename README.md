# Actividad: Propuesta de Práctica Temática Mini (Documentación Primero)

## 1) Título

**Diseña el título de tu práctica temática** (elige uno claro y específico).

Ejemplos:
- **Mini Toolkit en ARM64**
- **Asistente de Estudio en Terminal**
- **Reporteador de Información del Sistema**
- **Organizador de Archivos**
- **Juego de Aprendizaje en Línea de Comandos**

---

## 2) Descripción General

En esta actividad vas a **diseñar una propuesta de proyecto pequeño** para terminal, con enfoque en:
- documentación técnica,
- planeación,
- estructura del repositorio,
- y justificación del caso de uso.

> **Importante:** la prioridad es **documentar y justificar la idea antes de escribir mucho código**.

Debes elegir **un solo lenguaje principal**:
- ARM64 Assembly
- C
- Python
- Bash

### Restricciones del proyecto
- Debe ser un proyecto **pequeño y alcanzable**.
- Evita ideas grandes o con demasiadas funciones.
- **No uses** frameworks pesados, APIs pagadas, bases de datos, nube, contenedores ni dependencias complejas.
- Si eliges **ARM64 Assembly**, se recomienda únicamente para programas **muy pequeños** (por ejemplo: utilidades básicas de entrada/salida, operaciones simples o mini ejercicios de arquitectura).

### Objetivo académico
Que puedas demostrar que sabes:
1. plantear un problema realista,
2. proponer una solución técnica mínima,
3. estructurar un repositorio limpio,
4. planear pruebas desde el inicio,
5. comunicar decisiones de diseño con claridad.

---

## 3) Entregables del Estudiante

Tu repositorio debe incluir **como mínimo**:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Opcionales (si decides implementar una versión mínima):
- `src/`
- `scripts/`
- `tests/`

### Contenido esperado por archivo

#### `README.md`
Incluye:
- título del proyecto,
- lenguaje elegido,
- resumen breve (5–10 líneas),
- instrucciones básicas para ejecutar (si ya hay código),
- estado del proyecto (solo propuesta / propuesta + prototipo).

#### `docs/propuesta.md`
Incluye:
- problema que quieres resolver,
- objetivo general,
- 2 a 4 objetivos específicos,
- alcance (qué sí incluye),
- fuera de alcance (qué no incluye),
- justificación de por qué el proyecto es pequeño y viable.

#### `docs/caso_de_uso.md`
Incluye:
- usuario objetivo,
- escenario de uso,
- flujo principal paso a paso,
- entradas esperadas,
- salidas esperadas,
- al menos 2 casos límite.

#### `docs/estructura_repositorio.md`
Incluye:
- árbol de carpetas,
- propósito de cada carpeta/archivo,
- convención de nombres,
- estrategia de organización mínima para escalar sin complicar.

#### `docs/plan_de_pruebas.md`
Incluye:
- estrategia de pruebas manuales y/o simples automatizadas,
- tabla de casos de prueba (ID, entrada, resultado esperado),
- criterios de aceptación mínimos,
- riesgos técnicos y mitigaciones.

---

## 4) Estructura Recomendada del Repositorio

Usa esta estructura base mínima:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `<ext>` depende del lenguaje elegido:
> - Assembly: `.s`
> - C: `.c`
> - Python: `.py`
> - Bash: `.sh`

---

## Instrucciones de trabajo para el estudiante

1. Define una idea **mini** y concreta (1 problema, 1 solución principal).
2. Selecciona tu lenguaje principal.
3. Crea la carpeta `docs/` y redacta los 4 documentos obligatorios.
4. Asegura coherencia entre propuesta, caso de uso y plan de pruebas.
5. (Opcional) Implementa un prototipo mínimo en `src/`.
6. Revisa ortografía, formato Markdown y claridad técnica.

---

## Rúbrica sugerida (100 puntos)

- **Claridad y viabilidad de la propuesta (25 pts)**
- **Calidad del caso de uso (20 pts)**
- **Diseño de estructura del repositorio (20 pts)**
- **Plan de pruebas completo y realista (20 pts)**
- **Presentación, redacción y consistencia global (15 pts)**

---

## Criterios de aceptación

Para considerar la actividad como completa:

- [ ] Entregaste todos los archivos obligatorios.
- [ ] La propuesta está enfocada en un proyecto pequeño y realista.
- [ ] El lenguaje principal está claramente justificado.
- [ ] El caso de uso describe entradas, proceso y salidas.
- [ ] El plan de pruebas incluye casos verificables.
- [ ] La estructura del repositorio es clara y coherente.

---

## Recomendaciones finales

- Empieza simple; evita “feature creep” (querer abarcar demasiado).
- Si usas IA (Codex u otra), úsala para **iterar documentación** y no solo para generar código.
- Prioriza decisiones técnicas explicadas sobre cantidad de líneas programadas.
- Un proyecto pequeño, bien documentado y comprobable vale más que uno grande e incompleto.
