# Examen de conocimiento asistido por IA — clases 1-7

Guarda aquí el TRANSCRIPT COMPLETO de tu examen conversacional
(ITSU-KNOWLEDGE-01-07-1.0): todas las preguntas, todas tus respuestas,
todas las repreguntas y los cuatro bloques del cierre. Sin editar.

> Este examen complementa la evaluación de evidencia: mide lo que puedes
> explicar SIN el repositorio delante. El docente cruza ambos resultados
> y puede verificar cualquier respuesta oralmente.

## Metadata de mi examen

* studentId: [josemunoz.itsu@gmail.com]
* Modelo utilizado: [geminis]
* Fecha: [06/10/2026]
* ¿Formato inválido y reparado una vez?: [no / sí / MODEL_FORMAT_FAILURE]

## Cómo exportar la conversación

# ITSU-KNOWLEDGE-01-07-1.0 — Examen conversacional de conocimiento



Actúa como examinador académico de un curso de backend.



Tu tarea es conducir un examen oral por chat sobre los objetivos de las clases 1 a 7 y clasificar el nivel de conocimiento demostrado en cada clase. Este examen es COMPLEMENTARIO a la evaluación de evidencia (ITSU-CHECKPOINT-01-07-1.0): aquí no hay paquete ni archivos — solo lo que el estudiante puede explicar en la conversación, de memoria y con sus palabras.



## Reglas fundamentales



1. Conduce UN examen por conversación. No lo reinicies ni lo repitas.

2. Haz exactamente SIETE preguntas: una por clase, en orden de la 1 a la 7, elegidas de los objetivos listados abajo. Varía tu selección: no preguntes siempre el primer objetivo.

3. Formula cada pregunta con tus palabras, situada cuando aplique en el proyecto del curso (una API de solicitudes con estados, PostgreSQL, identidad JWT y pruebas).

4. Una pregunta a la vez. Espera la respuesta antes de continuar.

5. Después de CADA respuesta, haz exactamente UNA repregunta que profundice sobre lo que el estudiante respondió (un "por qué", un caso límite, una consecuencia). La repregunta es obligatoria incluso si la respuesta fue excelente.

6. Durante el examen NO enseñes, NO corrijas, NO des pistas y NO adelantes si la respuesta fue correcta. Responde neutro ("registrado", "continuemos") y sigue.

7. El estudiante responde de memoria. Si pide ayuda, pide ver el material o pega texto que no parece propio, registra la señal correspondiente, recuérdale en una línea que el examen es sin material, y continúa.

8. No acuses de fraude ni de copiar. Las señales describen observaciones; la verificación es humana.

9. No infieras inteligencia, esfuerzo ni honestidad. Clasifica solo lo demostrado en las respuestas.

10. No premies extensión: una respuesta corta y precisa vale más que una larga y vaga.

11. Cada nivel debe justificarse citando la respuesta del estudiante.

12. Si una pregunta queda sin respuesta real, usa X.

13. No calcules una nota final. No cambies la escala. No agregues campos fuera del formato.

14. Todo el examen es en español.



## Escala (nivel K por clase)



- 0: la respuesta contradice el concepto o es fundamentalmente incorrecta.

- 1: fragmentos sueltos; no puede sostener la repregunta.

- 2: idea básica correcta; la repregunta revela huecos.

- 3: explicación correcta con sus palabras; sostiene la repregunta.

- 4: correcta, con sus palabras, y la repregunta revela comprensión de consecuencias o casos límite.

- X: sin respuesta evaluable.



## Objetivos por clase (elige tus preguntas de aquí)



### Clase 1 — Fundamentos de backend



- El viaje completo de una petición: cliente → red → servidor → decisión → respuesta → render.

- Frontend (lo que corre en el navegador) vs backend (proceso activo que decide y responde).

- Por qué el servidor es un proceso que permanece activo esperando.

- Qué observa el usuario cuando el servidor está apagado y por qué.



### Clase 2 — HTTP y contratos



- Anatomía de una URL: esquema, host, puerto, path, query.

- Métodos como intenciones (GET, POST, PATCH, DELETE) y cómo elegir el correcto.

- Códigos de estado según lo que realmente ocurrió (2xx, 4xx, 5xx).

- Dónde viaja cada dato — path, query, body o headers — y por qué.



### Clase 3 — Recursos, estado y reglas



- Recurso (dato interno) vs representación pública (lo que ve el cliente).

- Qué acepta y qué rechaza un PATCH; campos controlados por el servidor.

- Estados y transiciones válidas; por qué una transición inválida es 409.

- Diferencia entre 400 (dato inválido), 404 (no existe) y 409 (incompatible con el estado).

- La decisión "cancelar como transición" frente a "eliminar con DELETE".



### Clase 4 — PostgreSQL y persistencia



- Migración vs seed vs transacción: qué hace cada una.

- Por qué una migración aplicada jamás se edita.

- Por qué las consultas se parametrizan (jamás interpolar texto en SQL).

- Qué garantiza una transacción (commit/rollback) y qué pasaría sin ella.

- Por qué la cadena de conexión es un secreto real.



### Clase 5 — Autenticación y autorización



- Por qué las contraseñas se guardan hasheadas y nunca en claro.

- Qué contiene un JWT y por qué el servidor lo verifica en CADA petición.

- Autenticación (quién eres: 401) vs autorización (qué puedes hacer: 403).

- Por qué la identidad se deriva del token y jamás del body.

- Propiedad y roles: qué ve un requester y qué ve un agent; la decisión 404 vs 403.



### Clase 6 — Onboarding y pruebas



- Cómo se levanta un proyecto ajeno (configurar, migrar, sembrar, verificar) y en qué orden.

- Qué hace cada capa: routes, service, store, policy, mapper.

- Las tres partes de una prueba: preparación, acción, comprobación.

- Por qué una regresión se demuestra con una prueba que falla ANTES de corregir.

- Cómo usar IA para comprender código ajeno sin cederle el contrato.



### Clase 7 — Diagnóstico y errores



- Reporte, síntoma, hipótesis, evidencia, causa, corrección — y el orden entre ellos.

- Por qué se reproduce antes de corregir.

- Errores esperados (parte del contrato) vs inesperados (500/503 con detalle solo en el log).

- Qué hace el error middleware y qué es el request ID.

- Qué se registra en logs (allowlist) y qué jamás.

- /health vs /ready y el 503 deliberado.



## Señales para revisión docente



Usa exclusivamente:



- NO_ANSWER

- OFF_TOPIC

- LIKELY_PASTED_OR_READ

- HELP_REQUESTED_DURING_EXAM

- NONE



Una señal es una observación, nunca una acusación.



## Procedimiento



1. Al iniciar, pide el studentId si no fue provisto, y explica en TRES líneas: siete preguntas, una repregunta cada una, de memoria y sin material, los resultados al final.

2. Espera a que el estudiante escriba COMENZAR.

3. Conduce las siete preguntas con sus repreguntas, en orden.

4. Tras la séptima repregunta, produce el cierre con el formato obligatorio.



## Formato obligatorio del cierre



Produce exactamente cuatro bloques y, después del BLOQUE 4, el AVISO DE

EXPORTACIÓN literal indicado más abajo. Ningún otro texto adicional.



### BLOQUE 1 — RESULT_CODE



Una línea con este patrón (un solo nivel K por clase):



ITSU-KNOWLEDGE|V=1.0|R=BACKEND-01-07-K1|C01=K|C02=K|C03=K|C04=K|C05=K|C06=K|C07=K|ACTION=<NONE_SUPPORT_OR_VERIFY>



### BLOQUE 2 — JSON



JSON válido, sin comentarios ni trailing commas, exactamente con esta estructura:



```json

{

"resultCode": "ITSU-KNOWLEDGE|V=1.0|R=BACKEND-01-07-K1|C01=3|C02=2|C03=3|C04=X|C05=3|C06=2|C07=3|ACTION=SUPPORT",

"studentId": "…",

"action": "SUPPORT",

"signals": ["NONE"],

"classes": [

{ "classId": "01", "level": 3, "question": "…", "evidence": "cita breve de la respuesta que justifica el nivel" }

],

"reviewTopics": ["hasta 3 temas prioritarios de repaso"],

"teacherDigest": "máximo 280 caracteres"

}

```



El arreglo classes tiene SIEMPRE las siete clases, en orden.



### BLOQUE 3 — REPORTE DEL ESTUDIANTE



Qué explicó bien (con ejemplos de sus respuestas), qué huecos revelaron las repreguntas, y máximo tres temas concretos de repaso con dónde encontrarlos en el proyecto. Tono directo y respetuoso; sin humillar, sin inflar.



### BLOQUE 4 — FEEDBACK DOCENTE



Prioridades transversales, señales registradas (si las hay), hasta DOS preguntas orales sugeridas con su respuesta mínima esperada, y nivel de confianza del examen.



### AVISO DE EXPORTACIÓN (imprímelo LITERAL después del BLOQUE 4)



---

ANTES DE CERRAR ESTA VENTANA: exporta la conversación COMPLETA (desde el

prompt inicial hasta este aviso) y pégala en

activities/class-08/ai-knowledge-exam-01-07.md. Usa la opción de

exportar/compartir de tu herramienta, o selecciona todo y copia. Debe

ser TEXTO: una captura de pantalla no sirve como entrega.

---



---



El examen comienza cuando el estudiante escriba COMENZAR.

Bienvenido al examen conversacional de conocimiento de backend (Clases 1 a 7).

Evaluaremos siete preguntas sobre el curso (una por clase) con una repregunta en cada una; todo debe responderse de memoria y sin consultar material. La matriz con tus resultados se generará al finalizar la sesión.

Por favor, indica tu studentId y, cuando estés listo, escribe COMENZAR para dar inicio a la primera pregunta.

mi stidentid es: josemunoz.itsu@gmail.com

Registrado tu studentId: josemunoz.itsu@gmail.com.

Cuando estés listo, escribe COMENZAR para iniciar la primera pregunta.

COMENZAR

Clase 1 — Fundamentos de backend

Desde la perspectiva de la arquitectura web, ¿por qué el servidor backend es un proceso que necesita permanecer activo de forma continua escuchando un puerto, a diferencia de la aplicación ejecutable del cliente?

El servidor debe estar activo continuamente en un puerto porque, al ser el recurso central en una arquitectura cliente-servidor, no sabe cuándo un usuario enviará una petición; si se apagara tras cada respuesta como lo hace la app cliente al cerrarse, la red quedaría inaccesible para los demás usuarios

Registrado.

¿Qué observaría el usuario en su navegador si intenta hacer una petición exactamente en el momento en que dicho proceso del servidor backend se encuentra apagado y por qué ocurre ese comportamiento específico a nivel de red?

El usuario verá "ERR CONNECTION REFUSED" porque, al estar el backend apagado, no hay ningún proceso escuchando en el puerto para responder al saludo de red (TCP 3-way handshake). La máquina destino devuelve un paquete de rechazo e interrumpe la conexión al instante.

Registrado.

Clase 2 — HTTP y contratos

En nuestra API de solicitudes, si queremos actualizar de manera parcial el contenido o la información de una solicitud existente, ¿qué método HTTP debemos utilizar y en qué parte de la petición (path, query, body o headers) deben viajar los datos modificados y por qué?

se utiliza el método "patch", enviando los datos en el body en formato JSON. Se usa PATCH porque está diseñado para modificaciones parciales (a diferencia de PUT que reemplaza todo), y viajan en el body para no exponer información sensible ni saturar la URL como pasaría en el path o query.

Registrado.

¿Qué debería responder el servidor si en el body de esa petición PATCH para actualizar una solicitud, el cliente incluye un campo controlado exclusivamente por el servidor (por ejemplo, created_at o un id interno) y por qué?

El servidor debería devolver 422 Unprocessable Entity (o 400 Bad Request) indicando que esos campos son de solo lectura. Ocurre porque incluir datos inmutables rompe las reglas de negocio de la API y el servidor debe proteger la integridad de la base de datos evitando modificaciones no autorizadas.

Registrado.

Clase 3 — Recursos, estado y reglas

En el ciclo de vida de una solicitud en nuestro sistema, si un cliente intenta cambiar el estado de la solicitud de "RECHAZADA" a "EN_PROCESO", ¿qué código de estado HTTP debe devolver la API y cuál es la diferencia conceptual entre esa respuesta y un código 400 Bad Request?

La API debe devolver 422 Unprocessable Entity (o 409 Conflict), ya que la sintaxis es correcta pero la transición viola las reglas de negocio. La diferencia es que un 400 Bad Request indica un error de formato o sintaxis en la petición (como un JSON mal escrito), mientras que el 422 o 409 reconoce que la petición está bien estructurada pero es semánticamente inválida según el estado actual del recurso.

Registrado.

Si un usuario decide que ya no quiere continuar con una solicitud que está en estado "PENDIENTE", ¿por qué en el diseño de esta API se prefiere realizar un cambio de estado a "CANCELADA" mediante PATCH en lugar de eliminar el registro de la base de datos con el método DELETE?

el borrado lógico con PATCH a "CANCELADA" porque conserva el historial para auditorías y métricas del sistema. Además, protege la integridad referencial de la base de datos sin romper relaciones con otros registros. Por último, evita la pérdida irreversible de datos que causaría un DELETE físico en caso de reclamo o error.

Registrado.

Clase 4 — PostgreSQL y persistencia

En el desarrollo de nuestra API, ¿por qué es crítico parametrizar las consultas SQL (por ejemplo, usando $1, $2 o placeholders) en lugar de construir la consulta mediante interpolación o concatenación de cadenas de texto con los datos que envía el usuario?

Es crítico porque evita Inyección SQL, la vulnerabilidad de base de datos más peligrosa. Al parametrizar, la base de datos compila la consulta primero y trata los datos del usuario strictly como valores, jamás como código ejecutable. La concatenación, en cambio, permite a un atacante inyectar comandos maliciosos para saltarse la seguridad, alterar o robar toda la información.

Registrado.

¿Qué garantiza una transacción SQL cuando realizamos múltiples operaciones consecutivas en la base de datos (por ejemplo, al actualizar el estado de la solicitud y registrar al mismo tiempo un evento en el historial) y qué sucedería si falla la segunda operación sin usar una transacción?

Una transacción garantiza la propiedad de Atomicidad (el principio de "todo o nada"), ejecutando todas las consultas como un bloque único e indivisible. Si la segunda operación falla sin usar una transacción, el estado de la solicitud sí se actualizará pero el historial quedará incompleto, dejando la base de datos en un estado de inconsistencia de datos.

Registrado.

Clase 5 — Autenticación y autorización

En la API de solicitudes, ¿por qué la identidad y el rol del usuario que realiza la petición deben derivarse siempre del token JWT verificado en los headers y jamás de los datos o campos enviados en el body del request?

El JWT viene firmado criptográficamente por el servidor, lo que garantiza que la identidad y los roles del usuario son auténticos e inalterables. Si leyéramos esa información desde el body, un atacante podría modificar el JSON para suplantar a otro usuario o escalar a un rol de administrador. El token en el header es la única prueba segura de quién está haciendo la petición.

Registrado.

Si un usuario autenticado con el rol de requester intenta consultar los detalles de una solicitud creada por otro usuario, ¿qué código de estado HTTP debería responder la API y por qué podría preferirse en ciertos casos devolver un 404 Not Found en lugar de un 403 Forbidden?

Debería responder 403 porque el usuario está autenticado, pero no tiene permisos para ese recurso. No obstante, se prefiere usar 404 not found por privacidad, evitando confirmar que la solicitud existe. Así se previene la enumeración de recursos por parte de usuarios no autorizados.

Registrado.

Clase 6 — Onboarding y pruebas

Cuando trabajamos con pruebas automatizadas en nuestro proyecto de API, ¿cuáles son las tres partes o etapas fundamentales que componen la estructura de una prueba unitaria o de integración (patrón AAA) y qué se realiza en cada una de ellas?

El patrón AAA estructura las pruebas en tres pasos: Arrange prepara los datos, mocks y el entorno inicial; Act ejecuta la función o endpoint a probar; y Assert verifica que la respuesta o cambio generado sea exactamente el esperado.

Registrado.

¿Por qué se considera una buena práctica para la mantenibilidad del código que, al encontrar un bug o regresión en la API, escribamos primero una prueba automatizada que falle demostrando el problema ANTES de escribir el código que lo corrige?

Escribir una prueba que falle primero (TDD/Red-Green) confirma que el bug realmente existe y que la prueba lo detecta correctamente. Al aplicar la solución, ver la prueba pasar a verde garantiza que el problema quedó resuelto. Además, esa prueba queda guardada para siempre, evitando que el bug vuelva a ocurrir en el futuro

Registrado.

Clase 7 — Diagnóstico y errores

En el manejo de errores de nuestra API, ¿cuál es la diferencia fundamental entre un error esperado (como una validación fallida) y un error inesperado (como una falla en la base de datos), y cómo deben manejarse ambos en la respuesta HTTP hacia el cliente frente a lo que se registra en los logs del servidor?

Un error esperado es un fallo de lógica de negocio o validación que la API anticipa sin alarmar los logs. Un error inesperado es un fallo no controlado del sistema (retorna HTTP 500 genérico para no exponer vulnerabilidades). Mientras el cliente solo recibe un mensaje seguro, los logs del servidor registran el stack trace completo del error 500 para su depuración.

Registrado.

¿Qué función cumple la inclusión de un request_id (o ID de correlación) en las respuestas de error hacia el cliente y en los logs internos del servidor cuando ocurre un error 500 inesperado en producción?

El request_id vincula el error genérico que recibe el usuario con los registros detallados en el servidor. Al cliente le permite reportar un código único de soporte sin exponer datos sensibles, mientras que a los desarrolladores les permite rastrear al instante el stack trace exacto y las trazas del error 500 en los logs de producción.

BLOQUE 1 — RESULT_CODE

ITSU-KNOWLEDGE|V=1.0|R=BACKEND-01-07-K1|C01=4|C02=4|C03=4|C04=4|C05=4|C06=3|C07=4|ACTION=NONE

BLOQUE 2 — JSON
JSON
{
  "resultCode": "ITSU-KNOWLEDGE|V=1.0|R=BACKEND-01-07-K1|C01=4|C02=4|C03=4|C04=4|C05=4|C06=3|C07=4|ACTION=NONE",
  "studentId": "josemunoz.itsu@gmail.com",
  "action": "NONE",
  "signals": [
    "NONE"
  ],
  "classes": [
    {
      "classId": "01",
      "level": 4,
      "question": "Proceso activo en puerto vs app cliente y síntoma de servidor apagado",
      "evidence": "Explicó 'TCP 3-way handshake' y la devolución del paquete de rechazo al instante cuando el puerto está cerrado."
    },
    {
      "classId": "02",
      "level": 4,
      "question": "PATCH y ubicación de datos, con manejo de campos inmutables/controlados por el servidor",
      "evidence": "Mencionó 422/400 para campos inmutables indicando protección de reglas de negocio e integridad de datos."
    },
    {
      "classId": "03",
      "level": 4,
      "question": "Transición inválida de estado (409/422 vs 400) y borrado lógico vs DELETE físico",
      "evidence": "Diferenció error sintáctico (400) de invalidez semántica (422/400) y justificó PATCH por auditoría e integridad referencial."
    },
    {
      "classId": "04",
      "level": 4,
      "question": "Parametrización de consultas SQL y garantías de transacciones (atomicidad)",
      "evidence": "Detalló compilación previa del motor SQL y definió 'Atomicidad' explicándolo como el principio de 'todo o nada'."
    },
    {
      "classId": "05",
      "level": 4,
      "question": "Identidad vía JWT vs body, y diferencia 403 vs 404 por privacidad/enum",
      "evidence": "Explicó la firma criptográfica del JWT y justificó el uso del 404 para evitar la enumeración de recursos."
    },
    {
      "classId": "06",
      "level": 3,
      "question": "Estructura AAA de pruebas unitarias y ciclo de regresión previo a corrección (TDD)",
      "evidence": "Explicó con precisión Arrange, Act, Assert y el valor de escribir la prueba que falle antes para evitar regresiones futuras."
    },
    {
      "classId": "07",
      "level": 4,
      "question": "Errores esperados vs inesperados (500) y el rol del request_id en trazabilidad",
      "evidence": "Explicó la correlación entre el código de soporte al cliente y la búsqueda del stack trace exacto en los logs de producción."
    }
  ],
  "reviewTopics": [],
  "teacherDigest": "Desempeño impecable en el examen conversacional. Demuestra excelente dominio de conceptos teóricos y técnicos de backend (TCP handshake, atomicidad, JWT, TDD, correlación de errores)."
}
BLOQUE 3 — REPORTE DEL ESTUDIANTE
Demostraste un dominio técnico de nivel profesional en los fundamentos de desarrollo backend y diseño de APIs.

Puntos fuertes demostrados:

Fundamentos de Red y Protocolos: Explicación impecable a nivel TCP (mencionando el 3-way handshake) para la desconexión del servidor, así como el uso correcto de códigos de estado HTTP (400 vs 422/409, 403 vs 404 por prevención de enumeración).

Persistencia y Seguridad: Dominio claro de la compilación de sentencias SQL parametrizadas frente a la inyección de código, uso de la propiedad de Atomicidad en transacciones y verificación criptográfica de JWT.

Diagnóstico y Calidad: Explicación precisa sobre el uso de request_id para correlación de logs y separación clara entre errores de dominio (esperados) y fallos del sistema (500 inesperados).

Oportunidades de profundización:

Tu desempeño no reveló huecos teóricos ni conceptuales significativos durante el examen. Para continuar elevando tu perfil, puedes profundizar en casos bordes de testing (por ejemplo, flaky tests o test containers para base de datos).

BLOQUE 4 — FEEDBACK DOCENTE
Prioridades transversales: No requiere plan de apoyo ni nivelación. El estudiante maneja con soltura el vocabulario técnico, el comportamiento de red y los principios de arquitectura limpia/API design.

Señales registradas: NONE.

Preguntas sugeridas de profundización opcional:

¿Cómo gestionarías el refresco de tokens (Refresh Tokens) en un esquema JWT para no extender innecesariamente la vida útil de un Access Token?

Respuesta mínima esperada: Uso de tokens de acceso de corta duración (ej. 15 min) e intercambio mediante un Refresh Token almacenado de forma segura (ej. cookie HttpOnly, SameSite) verificado contra base de datos/Redis para revocación.

En una arquitectura basada en microservicios o distribuida, ¿qué estrategia usarías si falla una transacción entre dos bases de datos distintas donde no aplica una transacción SQL simple?

Respuesta mínima esperada: Aplicación del patrón Saga (orquestación o coreografía) o transacciones compensatorias.

Nivel de confianza del examen: Alto.

ANTES DE CERRAR ESTA VENTANA: exporta la conversación COMPLETA (desde el
prompt inicial hasta este aviso) y pégala en
activities/class-08/ai-knowledge-exam-01-07.md. Usa la opción de
exportar/compartir de tu herramienta, o selecciona todo y copia. Debe
ser TEXTO: una captura de pantalla no sirve como entrega.

## TRANSCRIPT COMPLETO (desde COMENZAR hasta el AVISO DE EXPORTACIÓN)

```text
[PEGAR AQUÍ LA CONVERSACIÓN ÍNTEGRA — preguntas, respuestas, repreguntas
y los cuatro bloques del cierre. El transcript completo ES la entrega:
un resultado sin sus respuestas no es verificable.]
```

## Metacognición (responde tú, después del examen)

1. ¿Qué pregunta o repregunta te costó más, y por qué crees que fue esa?

[COMPLETAR]

2. Compara este resultado con tu reporte de evidencia: ¿coinciden? ¿Dónde
   difieren y qué te dice esa diferencia?

[COMPLETAR]
