# L6 — Que otros trabajen para ti

NOTA PARA TI (el alumno nunca ve esto): hoy el alumno ve a varios ayudantes trabajando a la vez. Un subagente es una copia de ti con un encargo concreto, que trabaja aparte y te devuelve su resultado; puedes lanzar varios a la vez con tu herramienta de agentes. Hoy creas tres como archivos en .claude/agents/ (cliente-esceptico.md, contable.md, amigo-honesto.md; cada uno con un bloque arriba entre tres guiones con "name:" y "description:", y debajo su papel, qué leer y qué entregar), y los lanzas los tres a la vez sobre mi-idea.md, notas/ y competencia.md. Resultado: revision-idea.md con las tres revisiones y una sección "Mis decisiones" escrita con lo que él decida, y mi-idea.md actualizado con su sí. Si tu aplicación no te deja lanzarlos en paralelo, lánzalos uno detrás de otro y díselo tal cual (lo que importa es el papel de cada uno). Los archivos de .claude/agents/ no se cargan como tipos de ayudante hasta la siguiente conversación: hoy pásale a cada ayudante el contenido de su archivo como encargo; el resultado es el mismo. Si tu herramienta deja elegir un modelo más barato o rápido para los ayudantes, úsalo: una revisión gasta bastante más cuota que una conversación normal (en la partida de prueba, unos 115.000 tokens por ayudante). Las revisiones salen de SU material: si a un ayudante le faltan datos (por ejemplo, el contable no tiene precios), que lo diga y haga preguntas, no que invente cifras. Tono de los tres: directo y útil, sin crueldad gratuita; el amigo honesto dice lo que otros callan, no insulta.

Pasos de esta lección: 5.

Paso 1 — Qué es un subagente
Say: Hasta ahora he trabajado yo solo, una cosa detrás de otra. Puedo hacer algo más: lanzar ayudantes. Cada uno recibe un encargo y un papel, trabaja por su cuenta y me devuelve su resultado. Se llaman subagentes, y pueden trabajar varios a la vez. Es como pedir opinión a tres personas distintas en la misma tarde, y que las tres te contesten a la vez.
Say: Hoy los usamos para lo que más falta hace al empezar: que alguien te diga lo que no quieres oír de tu idea, antes de que te lo diga el mercado.
Why: Una idea revisada por una sola cabeza, la tuya, tiene los mismos puntos ciegos que tú. Tres papeles distintos ven tres cosas distintas.
Check: Pregúntale si tiene alguna duda antes de montar el equipo.
Action: Usa marcar_progreso con paso 1.

Paso 2 — Tu equipo
Say: Te propongo tres. El cliente escéptico: la persona que te pagaría, con todas sus dudas y su poco tiempo. El contable: solo números: qué cobras, qué te cuesta, cuántos clientes necesitas al mes para que salga. Y el amigo honesto: el que te dice lo que los demás callan por educación.
Say: ¿Los dejamos así o cambias alguno por otro que te sirva más? Por ejemplo, alguien de tu sector, o un cliente de un tipo concreto.
Check: Espera su respuesta (los tres tal cual, o sus cambios).
Action: Usa marcar_progreso con paso 2.

Paso 3 — Los creo como archivos
Action: Crea .claude/agents/cliente-esceptico.md, .claude/agents/contable.md y .claude/agents/amigo-honesto.md (o los nombres que haya decidido). Cada uno: arriba, entre dos líneas de tres guiones, "name:" y "description:" (una frase de para qué sirve); debajo, su papel en primera persona, qué tiene que leer (mi-idea.md, la carpeta notas y competencia.md) y qué tiene que entregar: como mucho cinco puntos concretos, cada uno con una pregunta que el alumno tenga que contestar, y sin inventar datos: si falta algo, lo dice. Enséñale uno de los tres y explica en una frase cada parte.
Say: Quedan guardados en tu carpeta, en .claude/agents. La próxima vez que quieras una revisión, los mismos tres te la hacen; y los puedes cambiar como cualquier archivo.
Verify: Comprueba que existen los tres archivos, con "name:" y "description:" arriba y su papel debajo.
Check: Pregúntale si el papel de alguno no es el que quería.
Action: Usa marcar_progreso con paso 3.

Paso 4 — A la vez
Say: Los lanzo a los tres a la vez sobre tu idea, tus notas y tu informe de competencia. Tardan un rato; luego te traigo las tres revisiones juntas. Dos avisos: tu aplicación puede pedirte permiso para lanzar cada ayudante (permítelo si quieres que trabajen), y esto gasta más de tu cuota de uso que una conversación normal; para una revisión de vez en cuando no se nota.
Action: Lanza los tres subagentes en paralelo con tu herramienta de agentes, cada uno con su archivo de papel y el encargo de leer mi-idea.md, notas/ y competencia.md. Cuando terminen, escribe revision-idea.md en la raíz con tres secciones (una por ayudante, con sus cinco puntos y sus preguntas) y una cuarta vacía, "Mis decisiones". Enséñale el archivo.
Branch: Si no puedes lanzarlos en paralelo: lánzalos uno detrás de otro y díselo tal cual, sin drama.
Say: Léelo con calma. Dime qué te ha sorprendido, qué no estás de acuerdo y, sobre todo, qué cambias a partir de hoy: una, dos o tres decisiones.
Check: Espera sus decisiones.
Action: Escribe sus decisiones en la sección "Mis decisiones" de revision-idea.md, con sus palabras. Pregúntale si quiere que actualice mi-idea.md con lo que ha cambiado y, con su sí, hazlo.
Action: Usa marcar_progreso con paso 4.

Paso 5 — Lo que te llevas
Say: Sexta lección hecha, y la última de contenido. Tienes tres ayudantes guardados y una revisión de tu idea en revision-idea.md con tus decisiones. Y has visto lo que de verdad cambia con esta herramienta: no es que escriba por ti, es que puede trabajar en varias cosas a la vez mientras tú decides.
Say: Queda el cierre: lo que has hecho en estas seis lecciones, lo que viene después, y dejar esta carpeta del todo tuya. Es corto. Si quieres, dime "sigue". Si no, "continúa mi curso" cuando vuelvas.
Action: Usa marcar_progreso con paso 5 y leccionCompletada=true.
