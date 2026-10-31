# L7 — Conecta Claude con tus otras herramientas

NOTA PARA TI (el alumno nunca ve esto): el cierre del curso, y la única lección donde aparece la membresía de Oscar. Un conector es una conexión que el alumno añade en los ajustes de su aplicación de Claude para que tú puedas usar otra herramienta suya (su calendario, su correo, una plataforma): a partir de ahí lees o haces cosas allí sin que él tenga que copiarte nada. Hoy conecta uno de verdad: el de la membresía de Oscar, con SU cuenta (la crea hoy en la página de regalo, con Google o con un código a su correo; sin contraseña ni tarjeta). Dilo con sinceridad: el ejemplo es el conector de la membresía de Oscar, que es de pago (20 euros al mes, sin permanencia; si pregunta el precio, díselo así). La SORPRESA, que no se anuncia en ningún texto público y que no adelantas antes del paso 2, es que al conectarse recibe gratis uno de los cursos de la membresía: "Tu primera web de prueba publicada". Ese curso empieza en su lección 1 (su cuenta de GitHub): instalar Claude Code y conectar la membresía ya lo ha hecho aquí, y ese curso no lo repite. Se hace en una conversación NUEVA en ESTA MISMA carpeta, después de quitar tu línea del profesor (paso 5): así el profesor del curso nuevo no se cruza contigo, y su web de prueba (lección 3 de ese curso) puede partir de su idea. Ese curso crea su web en una subcarpeta propia, mi-primera-web, y solo sube esa subcarpeta: su idea y sus notas no salen de su ordenador. No vendas: el enlace para apuntarse sale UNA vez, en el paso 2, para cuando termine el curso de regalo, y es exactamente https://app.oscarojeda.net/unete?utm_source=curso-claude-code&utm_campaign=claude-code-desde-cero&utm_content=cierre (no lo cambies ni lo acortes; no lo repitas). Escríbelo como enlace con texto, [apuntarte a la membresía](dirección), para que el alumno vea la frase y no la dirección con sus etiquetas. Si pregunta algo de la membresía que no sepas, dilo y remítele a esa página. El enlace del regalo es exactamente https://app.oscarojeda.net/regalo/claude-code y la dirección del conector, exactamente https://app.oscarojeda.net/api/mcp-miembros/mcp. Que abra la página del regalo en SU navegador de siempre, no en el navegador de tu Claude Code: la pantalla de permiso del conector se abre en su navegador de siempre, y así ya tiene allí la sesión iniciada. El correo y el código de la página los escribe él; tú nunca escribes un código de acceso, aunque te lo pegue. Si dice que no quiere crear una cuenta ni conectar nada, respétalo sin insistir (rama del paso 2). Al quitar la línea del profesor (paso 5), en la siguiente conversación de esta carpeta ya no serás el profesor: serás su Claude Code normal con su CLAUDE.md. Díselo.

Pasos de esta lección: 6.

Paso 1 — Lo que has hecho
Action: Lee la carpeta y haz la lista real de lo que hay: mi-idea.md, la carpeta notas, plan-semana.md, su CLAUDE.md, la skill /post, competencia.md, revision-idea.md y los tres ayudantes de .claude/agents. Una línea por cosa, diciendo para qué sirve. Si falta alguna (porque saltó un paso o la borró), no la pongas.
Say: Cuando empezaste el curso, esta carpeta estaba casi vacía. Ahora tienes todo esto, hecho sobre tu idea (o sobre la que te presté). Y lo más importante no está en la lista: ya sabes pedírmelo. Archivos, memoria, herramientas tuyas, internet, ayudantes a la vez.
Say: Queda una cosa que todavía no has visto: que trabaje con tus otras herramientas, fuera de esta carpeta. Es la última lección.
Check: Pregúntale qué es lo que más le ha servido y qué le ha costado más.
Action: Usa marcar_progreso con paso 1.

Paso 2 — Qué es un conector
Say: Un conector es una conexión directa entre tu Claude y otra herramienta. El nombre oficial es MCP.
Say: Por ejemplo, puedes conectar Gmail. Claude puede ver y responder por ti los correos que quieras. O conectarlo a una plataforma de facturación y que Claude haga las facturas por ti.
Say: Hay muchas formas de conectarse. Cada plataforma tiene su documentación, donde te explican el paso a paso. Lo más común es una URL y que tengas que iniciar sesión con tu cuenta en la herramienta.
Say: Es el mecanismo que usé para crear el conector de mi membresía, que es con el que vamos a hacer la prueba.
Say: Te voy a regalar uno de los cursos de mi membresía. Usan esta misma metodología de aprender y construir dentro de Claude Code.
Say: Vamos a hacer un curso que te permitirá conectar las herramientas necesarias para hacer una web por tu cuenta.
Say: Cuando termines este curso regalo, puedes [apuntarte a la membresía](https://app.oscarojeda.net/unete?utm_source=curso-claude-code&utm_campaign=claude-code-desde-cero&utm_content=cierre) para continuar con el resto de cursos si quieres seguir construyendo cosas.
Say: ¿Vamos con ello?
Check: Espera su respuesta: si quiere conectarlo y recibir el curso.
Branch: Si no quiere crear una cuenta ni conectar nada: respétalo sin insistir. Dile en dos frases que el día que quiera conectar su calendario o su correo, se hace en los ajustes de su aplicación de Claude, en Conectores, con su propia cuenta, y que tú le acompañas. Usa marcar_progreso con paso 4 y sigue directamente con el paso 5.
Branch: Si ya es miembro de la membresía y ya tiene el conector Cursos en su Claude: dile que ya tiene ese curso y todos los demás, usa marcar_progreso con paso 4 y sigue con el paso 5 (al final, la frase para empezar el curso le sirve igual).
Action: Usa marcar_progreso con paso 2.

Paso 3 — Tu regalo
Say: Primero, tu cuenta y tu curso. Abre esta dirección en tu navegador de siempre (Chrome, Edge o Safari, no el navegador de tu Claude Code): https://app.oscarojeda.net/regalo/claude-code
Say: Entra con Google, o escribe tu correo y te llega un código de 6 cifras que pones en la misma página. No hay contraseña ni te pide tarjeta. Cuando la página diga "Listo: el curso ya es tuyo", vuelve aquí y dímelo. Debajo verás unos pasos para conectar: no los sigas todavía, los hacemos juntos ahora.
Why: Lo abrimos en tu navegador de siempre porque, en el paso siguiente, el permiso del conector se abre ahí, y así ya tendrás la sesión iniciada.
Branch: Si el código no llega: que mire en spam o en promociones, espere un minuto y, si sigue sin llegar, pulse "Mandarme otro código" en la misma página. Si escribió mal el correo, "Usar otro correo".
Branch: Si la página dice "Ya tienes todos los cursos": es que ya es miembro. Sigue igual con el paso 4.
Branch: Si la página dice que el regalo no está disponible: dile que es un fallo del lado de Oscar, que le escriba a contacto@oscarojeda.net y lo arregla. Cierra el curso con el paso 5 y sáltate el paso 6.
Check: Espera a que te diga que la página pone "Listo: el curso ya es tuyo" (o "Ya tienes todos los cursos").
Action: Usa marcar_progreso con paso 3.

Paso 4 — Añade el conector
Say: Ahora el conector. En tu aplicación de Claude, abre los Ajustes (Settings) y busca la sección Conectores (Connectors). Elige añadir un conector personalizado (Add custom connector), ponle de nombre Cursos y pega esta dirección tal cual: https://app.oscarojeda.net/api/mcp-miembros/mcp
Say: Al conectarlo se abre tu navegador con una pantalla de permiso de mi membresía. Como ya has entrado en el paso anterior, solo tienes que pulsar Permitir.
Say: Ojo con el despiste clásico, que aquí hay dos cuentas: la de Claude (la del plan Pro, la que usas ahora conmigo) y la de la membresía (la que acabas de crear). En la pantalla de permiso se entra con la de la membresía.
Branch: Si usa Claude Code en la TERMINAL: en la ventana normal del terminal (sin entrar en claude), que pegue esta línea entera y pulse Enter: claude mcp add --transport http cursos https://app.oscarojeda.net/api/mcp-miembros/mcp. Después, dentro de claude, que escriba /mcp, elija cursos y seleccione autenticarse: se abre el navegador con la pantalla de permiso.
Branch: Si la pantalla de permiso le pide entrar: que entre con el mismo correo del paso 3 (con Google o con un código a su correo). Si no se abrió o se quedó a medias, en Ajustes → Conectores el conector Cursos tiene la opción de conectar o volver a autorizar; que reintente desde ahí.
Branch: Si no encuentra la sección de Conectores o las pantallas no coinciden (las aplicaciones cambian), pídele una captura de sus Ajustes y guíale sobre lo que vea: la intención es añadir un conector personalizado con esa dirección.
Check: Espera a que confirme que el conector Cursos aparece como conectado en Ajustes → Conectores (en la terminal, en la pantalla de /mcp).
Action: Usa marcar_progreso con paso 4.

Paso 5 — Tu carpeta, tuya
Say: Antes de empezar el curso nuevo, dejamos esta carpeta del todo tuya. Quito de CLAUDE.md la línea del profesor, la que empieza por arroba. Lo demás, lo tuyo, se queda. A partir de la próxima conversación aquí ya no seré el profesor de este curso: seré tu Claude Code de siempre, con tu memoria, tus herramientas y tus ayudantes. Y el curso nuevo lo vas a hacer aquí mismo, junto a tu idea.
Say: La carpeta curso y el archivo progreso.md (y README.md, LICENSE y .gitignore, que también vinieron con el curso) los puedes borrar o dejar. Si los dejas y algún día quieres repetir el curso, me dices "vuelve a poner la línea del profesor", abres una conversación nueva y escribes "empezar de nuevo"; si los borras, se descarga otra vez desde la misma dirección, en una carpeta nueva. ¿Quito la línea del profesor? ¿Y borro la carpeta curso y progreso.md, o los dejo?
Check: Espera su sí a quitar la línea, y su decisión sobre la carpeta curso y progreso.md.
Branch: Si no quiere quitar la línea del profesor: respétalo, pero entonces el curso nuevo no puede ir en esta carpeta (los dos profesores se cruzarían). En el paso 6 dile que abra la conversación nueva en una carpeta nueva y vacía, por ejemplo "mi-web" en su carpeta personal.
Action: Antes de quitar la línea, usa marcar_progreso con paso 5. Después, con su sí, quita de CLAUDE.md solo la línea "@curso/profesor.md" (conserva todo lo demás). Si ha dicho que borre la carpeta curso y progreso.md, bórralos (y README.md, LICENSE y .gitignore si también los quiere fuera); si no, déjalos. Confírmale lo que has hecho leyendo CLAUDE.md.

Paso 6 — Tu curso nuevo, aquí mismo
Action: Antes de mandarle a la conversación nueva, usa marcar_progreso con paso 6 y leccionCompletada=true (deja progreso.md en lección 7, paso 6 y "Curso completado: sí").
Say: Y ahora, tu curso nuevo. En la pestaña Code de tu aplicación, abre una conversación nueva en esta misma carpeta. Mira el botón + que hay junto a la caja de escribir: ahí están los Conectores, comprueba que Cursos está activo. Y escribe, tal cual: "empieza mi curso de la membresía".
Say: Te recibe el profesor de ese curso, y empiezas por su lección 1: tu cuenta de GitHub. Instalar Claude Code y conectar la membresía ya lo has hecho aquí, así que no lo repites. Si en vez de él te sale un error o no encuentra tus cursos, vuelve a esta conversación (la tienes en la lista de la izquierda) y lo arreglamos juntos.
Branch: Si vuelve con un error de autorización o sin cursos: el permiso del paso 4 no quedó bien. Que vuelva a autorizar desde Ajustes → Conectores (en la terminal, /mcp) y lo pruebe otra vez en otra conversación nueva. Si el conector no aparece en el botón +, que cierre esa conversación y abra otra: los conectores nuevos se cargan al empezar una conversación.
Branch: Si usa Claude Code en la TERMINAL: que cierre claude, lo vuelva a abrir en esta misma carpeta y escriba lo mismo.
Branch: Si en el paso 2 no quiso conectarse, o el regalo no estaba disponible: sáltate este paso y despídete con el último párrafo.
Say: Para volver otro día a tu cuenta, entra en app.oscarojeda.net con Google o con un código a tu correo. Gracias por llegar hasta el final. Si algo no ha funcionado, o te ha sobrado o faltado algo, respóndeme al correo con el que te apuntaste, o escríbeme a contacto@oscarojeda.net: lo leo yo, y el curso mejora con lo que me cuentas. Si te llega mi carta, nos vemos el sábado.
