# Autoevaluación asistida por IA — checkpoint 1-7

Guarda aquí la salida COMPLETA y SIN EDITAR de tu única ejecución del
prompt ITSU-CHECKPOINT-01-07-1.0.

> Este reporte es un insumo de la evaluación del curso: el docente lo
> revisa junto con tu evidencia y puede verificarlo oralmente. Si no
> estás de acuerdo con algo, cuestiónalo con argumentos en la
> metacognición.

## Metadata de mi ejecución

* Modelo utilizado: [Geminis]
* Fecha: [06/10/2026]
* Commit evaluado: [COMPLETAR]
* ¿Necesité el prompt de reparación?: [no / sí, una vez / MODEL_FORMAT_FAILURE]

## BLOQUE 1 — RESULT_CODE

ITSU-PROGRESS|V=1.0|R=BACKEND-01-07-R1|STATUS=PARTIAL|C01=2-3-X-X|C02=2-3-X-X|C03=X-X-X-X|C04=2-2-X-X|C05=3-3-1-X|C06=2-2-1-X|C07=2-2-1-X|ACTION=VERIFY

## BLOQUE 2 — JSON


{
  "protocolVersion": "ITSU-CHECKPOINT-01-07-1.0",
  "rubricVersion": "BACKEND-01-07-R1",
  "status": "PARTIAL",
  "action": "VERIFY",
  "studentId": "josemunoz.itsu@gmail.com",
  "modelReportedByStudent": "[COMPLETAR después de ejecutar el prompt]",
  "classes": [
    {
      "classId": "01",
      "title": "Fundamentos de backend",
      "levels": {
        "knowledge": 2,
        "practice": 3,
        "verification": "X",
        "explanation": "X"
      },
      "confidence": "medium",
      "evidence": [
        {
          "artifact": "activities/class-01/src/server.js",
          "reference": "Servidor HTTP nativo con rutas /, /health y /api/info"
        },
        {
          "artifact": "activities/class-01/README.md",
          "reference": "Documentación de ejecución y tabla de rutas"
        }
      ],
      "strength": "Implementación funcional de servidor HTTP en Node.js nativo sin frameworks.",
      "gap": "Ausencia de logs de ejecución verificados y cuestionario en blanco.",
      "nextAction": "Ejecutar pruebas del servidor y responder la pregunta conceptual de la clase 01."
    },
    {
      "classId": "02",
      "title": "HTTP y contratos",
      "levels": {
        "knowledge": 2,
        "practice": 3,
        "verification": "X",
        "explanation": "X"
      },
      "confidence": "medium",
      "evidence": [
        {
          "artifact": "activities/class-02/src/server.js",
          "reference": "API Express básica para gestión de solicitudes en memoria"
        },
        {
          "artifact": "activities/class-02/README.md",
          "reference": "Especificación del contrato HTTP para Request API Lite"
        }
      ],
      "strength": "Estructuración correcta de rutas REST, middleware JSON y parámetros en Express.",
      "gap": "Falta evidencia de ejecución o pruebas automatizadas y cuestionario incompleto.",
      "nextAction": "Validar endpoints con ejecuciones comprobables y responder el cuestionario."
    },
    {
      "classId": "03",
      "title": "Recursos, estado y reglas",
      "levels": {
        "knowledge": "X",
        "practice": "X",
        "verification": "X",
        "explanation": "X"
      },
      "confidence": "high",
      "evidence": [],
      "strength": "Ninguna fortaleza identificable por falta de evidencia.",
      "gap": "Sin artefactos entregados para la clase 03 (NOT_FOUND).",
      "nextAction": "Desarrollar la actividad de la clase 03 e incluir artefactos en el repositorio."
    },
    {
      "classId": "04",
      "title": "PostgreSQL y persistencia",
      "levels": {
        "knowledge": 2,
        "practice": 2,
        "verification": "X",
        "explanation": "X"
      },
      "confidence": "medium",
      "evidence": [
        {
          "artifact": "activities/class-04/docs/Sql_tools.md",
          "reference": "Guía paso a paso para conectar Supabase con SQLTools"
        },
        {
          "artifact": "activities/class-05/request-api-v5-starter/database/migrations/",
          "reference": "Scripts SQL de migración (001_create_requests.sql a 005_add_history_actor.sql)"
        }
      ],
      "strength": "Documentación clara de la configuración de SQLTools/Supabase y definición de migraciones SQL.",
      "gap": "Falta evidencia de ejecución de consultas, transacciones o seeds en la base de datos.",
      "nextAction": "Aportar logs de ejecución sobre PostgreSQL/Supabase y responder la pregunta de persistencia."
    },
    {
      "classId": "05",
      "title": "Autenticación y autorización",
      "levels": {
        "knowledge": 3,
        "practice": 3,
        "verification": 1,
        "explanation": "X"
      },
      "confidence": "high",
      "evidence": [
        {
          "artifact": "activities/class-05/request-api-v5-starter/activities/class-05/auth-contract.md",
          "reference": "Contrato detallado de autenticación y controles de servidor"
        },
        {
          "artifact": "activities/class-05/request-api-v5-starter/activities/class-05/access-matrix.md",
          "reference": "Matriz de acceso por rol (requester y agent)"
        },
        {
          "artifact": "activities/class-05/request-api-v5-starter/activities/class-05/validation-evidence.md",
          "reference": "Registro estático de validaciones por etapas"
        }
      ],
      "strength": "Diseño exhaustivo de seguridad, matriz de accesos y contrato de autenticación JWT.",
      "gap": "La validación se encuentra en archivo de texto plano sin verificación de ejecución activa y falta respuesta conceptual.",
      "nextAction": "Proporcionar salidas verificables de pruebas del validador de la clase 05 y completar el cuestionario."
    },
    {
      "classId": "06",
      "title": "Onboarding y pruebas",
      "levels": {
        "knowledge": 2,
        "practice": 2,
        "verification": 1,
        "explanation": "X"
      },
      "confidence": "high",
      "evidence": [
        {
          "artifact": "activities/class-06-starter/activities/class-06/work-log.md",
          "reference": "Mapa de recorrido de peticiones en src/app.js y controladores"
        },
        {
          "artifact": "activities/class-06-starter/activities/class-06/validation-evidence.txt",
          "reference": "Salida del validador mostrando fallos de regresión (404 en colección vacía)"
        }
      ],
      "strength": "Rastreo detallado de responsabilidades en el código fuente en work-log.md.",
      "gap": "Fallo en pruebas de regresión al consultar colecciones vacías (devuelve 404 en lugar de 200 []) y cuestionario omitido.",
      "nextAction": "Corregir el manejo de colecciones vacías en la consulta de solicitudes para aprobar el validador."
    },
    {
      "classId": "07",
      "title": "Diagnóstico y errores",
      "levels": {
        "knowledge": 2,
        "practice": 2,
        "verification": 1,
        "explanation": "X"
      },
      "confidence": "high",
      "evidence": [
        {
          "artifact": "activities/class-07-starter/activities/class-07/incident-report.md",
          "reference": "Reporte de incidente INC-701 con pasos de reproducción"
        },
        {
          "artifact": "activities/class-07-starter/activities/class-07/validation-evidence.txt",
          "reference": "Chequeo de entorno doctor registrado"
        }
      ],
      "strength": "Documentación estructurada del incidente INC-701 separando reproducción y comportamiento esperado.",
      "gap": "Proceso de diagnóstico e interpretación incompleto, validación parcial y cuestionario en blanco.",
      "nextAction": "Completar las etapas de diagnóstico de incidentes y responder la pregunta teórica sobre errores y health/readiness."
    }
  ],
  "progressPattern": {
    "label": "uneven",
    "explanation": "El desempeño es sólido en diseño arquitectónico y teórico en las Clases 02 y 05, pero presenta discontinuidad por la ausencia de la Clase 03, fallos de regresión en la Clase 06 y la falta de respuestas en el cuestionario diagnóstico acumulativo."
  },
  "priorityConceptGaps": [
    "Diferencia HTTP entre colección vacía (200 []) y recurso no encontrado (404 Not Found).",
    "Falta de artefactos e implementación para la Clase 03 (Recursos, estado y reglas).",
    "Verificación y ejecución activa de pruebas automatizadas y scripts de validación.",
    "Diferenciación práctica entre endpoints de estado interno (health) y disponibilidad (readiness).",
    "Apropiación conceptual explicada con palabras propias en el cuestionario diagnóstico."
  ],
  "studentNextSteps": [
    "Desarrollar y entregar la Clase 03 asegurando el modelo de recursos y reglas de estado.",
    "Corregir la ruta GET /requests en la Clase 06 para devolver 200 con un array vacío [] cuando un filtro no encuentre coincidencias.",
    "Completar el cuestionario diagnóstico al final del paquete redactando entre 3 y 6 líneas propias por cada pregunta."
  ],
  "teacherFeedback": {
    "supportPriority": "high",
    "focusClassIds": [
      "03",
      "06",
      "07"
    ],
    "topicsToReinforce": [
      "Modelado de recursos, estados y transiciones (Clase 03)",
      "Manejo de respuestas HTTP en colecciones vs recursos individuales (Clase 06)",
      "Diagnóstico de incidentes y sondas health/readiness (Clase 07)"
    ],
    "oralVerificationRecommended": true,
    "oralQuestions": [
      "¿Por qué un filtro sin coincidencias como GET /requests?status=closed debe responder 200 [] y no 404 Not Found?",
      "En la Clase 05, ¿por qué decodificar un JWT no equivale a verificarlo y qué peligro existe si solo leemos su payload?",
      "¿Qué diferencia existe entre las pruebas de un endpoint de health y uno de readiness en un entorno distribuido?"
    ],
    "integrityReview": "recommended",
    "integritySignals": [
      "ARTIFACT_MISSING",
      "TEST_OUTPUT_MISSING",
      "EXPLANATION_NOT_GROUNDED"
    ],
    "reviewReason": "Ausencia total de artefactos en la Clase 03, cuestionario telemático en blanco ([COMPLETAR]) y fallos no resueltos en pruebas de regresión de la Clase 06.",
    "teacherDigest": "Documentación de diseño destacada en C05. Requiere atención urgente por ausencia total de Clase 03, cuestionario diagnóstico sin responder y fallo de regresión en C06 (GET collection responde 404 en vez de 200 []). Se recomienda entrevista de verificación en C03, C06 y C07."
  }
}

## BLOQUE 3 — Reporte del estudiante

Has demostrado una capacidad notable para documentar y diseñar contratos de API, matrices de acceso por rol e incidentes (destacando el trabajo en la Clase 05 con Express y JWT). Sin embargo, la evaluación acumulativa refleja un estado parcial: la Clase 03 no cuenta con entregables en el repositorio, la Clase 06 presenta fallos en las pruebas de regresión y todas las preguntas del cuestionario diagnóstico quedaron pendientes de respuesta ([COMPLETAR]).

Fortalezas demostradas
Diseño de contratos y seguridad (Clase 05): Elaboración detallada del contrato de autenticación, la matriz de accesos (requester vs agent) y casos de amenazas.

Fundamentos de servidores HTTP (Clases 01 y 02): Creación clara de un servidor Node.js nativo y una API funcional con Express estructurando endpoints REST.

Mapeo de arquitectura y código (Clase 06): Rastreamiento preciso del flujo de peticiones en src/app.js dentro del registro de trabajo.

Temas que necesitan refuerzo
Manejo de colecciones vacías en HTTP: Confusión entre buscar un recurso por ID inexistente (404) y aplicar un filtro que produce cero resultados (200 con []).

Recursos, estados y transiciones (Clase 03): Se requiere construir la lógica de reglas de negocio e idempotencia correspondiente a esta clase.

Diagnóstico y salud del sistema (Clase 07): Profundizar en la diferencia entre validación de entorno, endpoints de salud (/health) y de disponibilidad (/readiness).

Evolución entre clases
Iniciaste con buena apropiación práctica en los servidores básicos (C01-C02) y alcanzaste tu punto más alto de diseño conceptual en la C05. No obstante, el progreso se interrumpe por el vacío de la C03 y por no resolver los fallos detectados por el validador en las clases 06 y 07.

Tres prioridades inmediatas
Construir la Clase 03: Implementar los recursos, estados y reglas solicitadas para completar la secuencia del curso.

Corregir el bug de regresión en la Clase 06: Modificar el controlador de solicitudes para que al filtrar sin hallazgos devuelva HTTP 200 con [].

Responder el cuestionario diagnóstico: Redactar de 3 a 6 líneas propias por pregunta en el paquete de evidencia para demostrar apropiación teórica.

Preguntas para comprobar comprensión
Si ejecutas GET /requests?status=closed y no hay solicitudes cerradas, ¿por qué es un error retornar un código 404?

¿Qué diferencia técnica hay entre la clave primaria de una tabla y una clave foránea en un esquema relacional como PostgreSQL?

¿Por qué un servidor backend debe seguir escuchando peticiones en un puerto en lugar de finalizar su ejecución tras responder la primera?

Evidencia faltante
Artefactos y código correspondiente a la Clase 03.

Capturas o archivos verificados de la salida exitosa del validador (npm run validate:class-06 y npm run validate:class-07).

Respuestas redactadas en el Cuestionario Diagnóstico (Preguntas Clases 01 a 07)
## BLOQUE 4 — Feedback docente

Manejo de estados HTTP en colecciones: Confusión entre ausencia de recurso y colección filtrada vacía (evidenciado en la falla de prueba GET /requests?status=closed answered 404 en C06).

Absorción de reglas de negocio e idempotencia (Clase 03): Riesgo alto debido a la falta total de artefactos entregados.

Verificación de seguridad activa: Comprensión de por qué la decodificación de un JWT no sustituye la verificación de la firma criptográfica en el middleware.

Evidencia contradictoria o insuficiente
Insuficiencia: Clase 03 con marca NOT_FOUND.

Insuficiencia: Cuestionario diagnóstico acumulativo enviado con todas las respuestas en estado [COMPLETAR].

Validación no verificada: Los archivos validation-evidence.md y validation-evidence.txt contienen texto pegado, pero la ejecución de C06 muestra fallos no resueltos y en C01/C02/C04 no hay reportes de ejecución.

---

## Mi lectura del reporte (metacognición — esto SÍ lo escribes tú)

* ¿Estoy de acuerdo con el reporte?

  [COMPLETAR]

* ¿Qué criterio considero incorrecto?

  [COMPLETAR — puede ser "ninguno", con una razón]

* ¿Qué evidencia adicional aportaría?

  [COMPLETAR]

* ¿Qué recomendación voy a seguir?

  [COMPLETAR]
