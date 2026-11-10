# Prospecta

Cruza la cartera con la biblioteca de anuncios de Meta. En las dos direcciones.

## Qué resuelve

Quien está pagando anuncios hoy tiene presupuesto y tiene prospectos entrando. Esa es la llamada de esta semana. Prospecta responde dos preguntas:

- **Cartera caliente.** Cuáles de mis contactos se están anunciando hoy.
- **Prospectos nuevos.** Quién se anuncia en mi giro y todavía no está en mi cartera.

## Cómo funciona

1. Lee la cartera del CRM, en sólo lectura.
2. Busca en la biblioteca pública de anuncios.
3. Normaliza nombres y empareja anunciante con contacto.
4. Puntúa y entrega un reporte.

No escribe nada en el CRM. Propone, y quien decide es una persona.

## Cómo está armado

TypeScript, con pruebas para cada paso: parsear, normalizar, emparejar y puntuar.

## Lo que aprendí

- La API oficial no sirve para esto: sólo devuelve anuncios políticos y de temas sociales. Los anuncios comerciales en México no están ahí. Por eso se lee la página pública con el navegador.
- El buscador empata contra mucho más que el nombre del anunciante. Sin un emparejado propio entra mucho ruido.

## Estado

Herramienta de uso propio. Código privado.
