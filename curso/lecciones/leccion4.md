# L4 — Tus propias herramientas: skills

NOTA PARA TI (el alumno nunca ve esto): hoy el alumno crea su primera skill, /post, y la prueba. Una skill es una carpeta .claude/skills/<nombre>/ con un archivo SKILL.md que empieza por un bloque entre tres guiones con "name:" y "description:", y debajo las instrucciones en texto normal. Las skills de la carpeta del proyecto se pueden invocar escribiendo /nombre al principio del mensaje, y también se activan solas cuando lo que pide el alumno encaja con la descripción. Resultado: .claude/skills/post/SKILL.md con su voz, probada al menos una vez y ajustada con lo que él diga. Si al escribir /post la aplicación no la reconoce (algunas versiones cargan las skills nuevas al abrir una conversación nueva): que escriba "usa la skill post con esta nota: ..." o que abra una conversación nueva, escriba "continúa mi curso" y pruebe /post ahí (el progreso se guarda antes de mandarle). Si no tiene publicaciones suyas para enseñarte la voz, que la describa en tres palabras y usa lo que dice su CLAUDE.md en "Cómo quiero que me hables". La skill no se publica en ninguna red: solo escribe el texto; publicar es cosa suya, desde su cuenta.

Pasos de esta lección: 5.

Paso 1 — Qué es una skill
Say: Hoy creas tu primera herramienta. Se llama skill, y es una receta que escribes una vez y luego usas con una palabra. Como guardar una orden larga en un botón: escribes "/post" y una nota, y sale una publicación para tus redes con tu voz, tu largo y tu forma de terminar. Sin que vuelvas a explicarme nada.
Say: Vive en un archivo de tu carpeta, dentro de .claude/skills/post/. Lo vamos a crear juntos, en texto normal. No hay que programar nada.
Why: Lo que te hace lento no es escribir una publicación. Es explicar cada vez cómo la quieres. La receta lo explica una sola vez y ya.
Check: Pregúntale si tiene alguna duda y en qué red publica, o publicaría, sobre su idea (LinkedIn, Instagram, X, Facebook, otra).
Action: Usa marcar_progreso con paso 1.

Paso 2 — Tu voz
Say: Para que la receta suene a ti, tengo que saber cómo escribes. Pégame aquí una o dos publicaciones o mensajes tuyos, de los que te gusten. Si no tienes, descríbeme cómo quieres sonar en tres palabras. Y dime también: cuánto de largo, con o sin hashtags, con o sin emojis, y cómo te gusta terminar (una pregunta, una invitación, nada).
Branch: Si no tiene ejemplos: usa sus tres palabras y la sección "Cómo quiero que me hables" de su CLAUDE.md como punto de partida. Dile que la receta se afina con el uso.
Check: Espera sus ejemplos o su descripción y sus preferencias.
Action: Usa marcar_progreso con paso 2.

Paso 3 — Creo la skill
Action: Crea .claude/skills/post/SKILL.md. Arriba, entre dos líneas de tres guiones, "name: post" y "description: Convierte una nota o una idea en una publicación para <su red> con la voz de <su nombre>". Debajo, en texto normal: para quién escribe (su idea, de mi-idea.md), su voz (lo que te ha dado, con sus ejemplos citados), el largo, la estructura (cómo empieza, cómo termina), lo que nunca (de su CLAUDE.md y lo que haya dicho hoy) y una instrucción final: "entrega solo el texto de la publicación, listo para copiar, y pregunta si quiere otra versión". Enséñale el archivo y explícale en una frase cada parte.
Say: La carpeta .claude es donde Claude Code guarda las cosas tuyas de esta carpeta. Empieza por un punto, así que puede que tu explorador la esconda. No pasa nada: está ahí, y yo la veo.
Verify: Comprueba que .claude/skills/post/SKILL.md existe, que el bloque de arriba tiene "name: post" y una "description", y que el cuerpo recoge su voz y sus preferencias.
Check: Pregúntale si la receta dice lo que él quiere o si cambiaría algo antes de probarla.
Action: Usa marcar_progreso con paso 3.

Paso 4 — Pruébala
Say: A probarla. Un detalle antes: la aplicación carga las herramientas nuevas al abrir una conversación, así que en esta, recién creada, puede que "/post" aún no exista. Hoy la pedimos con palabras y, a partir de la próxima conversación, con la barra. Escríbeme: "usa la skill post con esta nota:" y a continuación una nota: algo que te haya pasado esta semana con tu idea, o una de tus notas de la carpeta notas. Por ejemplo: "usa la skill post con esta nota: hoy he llamado a tres sitios para saber qué cobran y ninguno me ha contestado el mismo día".
Say: La barra (/) está, en un teclado español, pulsando Mayúsculas y el 7 a la vez. A partir de la próxima conversación bastará con escribir "/post" y la nota.
Branch: Si prefiere probar ya con "/post" y su aplicación la reconoce: perfecto, sigue. Si no la reconoce: que use la frase con palabras; y si quiere verla funcionar con la barra hoy mismo, usa marcar_progreso con paso 4 ANTES, y dile que abra una conversación nueva, escriba "continúa mi curso" y pruebe "/post" allí.
Check: Espera su petición con la nota.
Action: Escribe la publicación siguiendo la receta, solo el texto, y pregúntale qué cambiaría. Con su respuesta, ajusta SKILL.md (no solo la publicación: la receta), y dile qué has cambiado en la receta para que la próxima salga mejor a la primera.
Why: La primera vez nunca sale perfecta. Lo que importa es que cada corrección se guarda en la receta, no en tu cabeza: la segunda publicación ya la aprovecha.
Action: Usa marcar_progreso con paso 4.

Paso 5 — Lo que te llevas
Say: Cuarta lección hecha. Tienes una herramienta tuya, /post, que vive en un archivo y viaja con esta carpeta. Se te van a ocurrir más: "/resumen" para pasar las notas de una reunión a tareas, "/correo" para contestar a un cliente con tu tono, "/presupuesto" para que salgan siempre con tu formato. Cada una es un archivo como este. Dímelo y las hacemos.
Say: La próxima lección sale de la carpeta: ojos en internet. Busco y visito webs por ti, y te traigo lo que importa de tu competencia. Si quieres seguir, dime "sigue". Si no, "continúa mi curso" cuando vuelvas.
Action: Usa marcar_progreso con paso 5 y leccionCompletada=true.
