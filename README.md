# Victor Gallo

Account Executive en [SuperLeads](https://superleads.mx). Ayudo a colegios y universidades a inscribir más alumnos, con datos.

Vengo de finanzas — BanBajío, Globant, GBM — y leo un embudo de admisiones como un estado de resultados. Vendo de día. Y construyo las herramientas con las que vendo.

El código de SuperLeads es de la casa y vive en repos privados. Aquí está lo que sí se puede contar: qué resuelve cada pieza, cómo está armada y qué decidí al diseñarla.

## Lo que construyo

| Proyecto | Qué resuelve | Con qué |
|---|---|---|
| [Motor Comercial](proyectos/motor-comercial.md) | Cada mañana el comercial sabe a quién escribirle, qué decirle y por qué | Cloudflare Workers, D1, TypeScript |
| [Hunter](proyectos/hunter.md) | Clasifica todo el CRM por institución y arma el plan de reactivación de 30 días | Cloudflare Workers, D1, cron |
| [Brief Agendado](proyectos/brief-agendado.md) | Investiga al prospecto antes de la reunión y manda el brief el mismo día | Cloudflare Workers, calendarios ICS |
| [Rayos X de Inscripciones](proyectos/rayos-x.md) | El diagnóstico de admisiones que se llena en vivo, con la institución enfrente | Next.js sobre Cloudflare, D1 |
| [Generador de video](proyectos/generador-de-video.md) | De una idea escrita a un video listo para publicar | Remotion, React |
| [Publicador](proyectos/publicador.md) | Publica en cada red lo que ya está aprobado, una sola vez | Cloudflare Workers, D1, R2 |
| [Prospecta](proyectos/prospecta.md) | Cruza la cartera con quién se está anunciando hoy | TypeScript, navegador |
| [Modelo de admisiones](proyectos/modelo-de-admisiones.md) | Ajustar un modelo abierto con conversaciones anónimas, y medir antes de entrenar | NVIDIA Nemotron, AWS SageMaker, S3 |
| [Análisis de llamadas](proyectos/analisis-de-llamadas.md) | Qué objeciones se repiten en las llamadas grabadas | Python, lotes |
| [Inventario comercial](proyectos/inventario-comercial.md) | Un plan donde cada cifra se contó en la fuente | Datos de cada sistema |
| [Rutinas con agentes](proyectos/rutinas-con-agentes.md) | Un agente corre mi operación diaria y corrige sus propias rutinas | Servidor propio, cron, MCP |

Lo personal: [victorgallo.com](https://victorgallo.com) (sitio estático armado por un script, servido por un Worker) y [omona](https://github.com/victorgalloo/omona), un asistente de ventas por WhatsApp para pymes.

## Cómo decido al construir

- **La lógica decide; el modelo redacta.** A quién escribirle, cuándo y por qué canal sale de reglas que se pueden probar. El modelo sólo escribe el texto.
- **Sin datos inventados.** Si la evidencia no alcanza, la respuesta es «desconocido». Un hueco honesto sirve más que un dato bonito.
- **Una pantalla.** Lo que el comercial necesita hoy cabe en una vista. Lo demás estorba.
- **Propone la máquina, decide la persona.** En el Motor y en Hunter el mensaje lo escribe el sistema y lo manda alguien.
- **Los secretos, en una bóveda.** Ni en el repo ni en un archivo suelto.

## Dónde encontrarme

[victorgallo.com](https://victorgallo.com)
