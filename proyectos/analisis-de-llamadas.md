# Análisis de llamadas

Leer todas las llamadas grabadas del equipo y sacar qué objeciones se repiten, qué duele y de qué se habla de verdad.

## Qué resuelve

Las llamadas de venta se graban y casi nadie las vuelve a oír. Lo que se aprende en una se queda en la memoria de quien estuvo ahí. Este análisis las lee todas y devuelve los patrones.

## Cómo funciona

Seis pasos, cada uno reanudable:

1. **Bajar** las reuniones y sus transcripciones.
2. **Preparar:** quitar duplicados y dejar una transcripción legible por llamada.
3. **Costear:** estimar tokens y costo antes de gastar un solo crédito.
4. **Extraer:** mandar las transcripciones al modelo por lotes.
5. **Agrupar** objeciones, dolores y temas de operación.
6. **Agregar** en local: una tabla por reunión y otra por cuenta.

## Cómo está armado

Un solo script de Python, con sus dependencias declaradas en el encabezado. La extracción va por lotes, que cuestan la mitad que las llamadas una por una, y corre con los créditos de Claude for Startups de SuperLeads.

## Decisiones

- El costo se estima antes de correr. Si no convence, no corre.
- Cada paso guarda su avance. Si se corta, sigue donde se quedó.
- El agregado final se hace en local, sin modelo: contar no necesita IA.

## Estado

Herramienta de uso propio. Código privado.
