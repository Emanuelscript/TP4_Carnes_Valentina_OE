# Diccionario de Datos

El siguiente diccionario define las entidades utilizadas para registrar los cortes, las ventas y las alertas de reposición. Se incorporan claves primarias y foráneas para garantizar la integridad referencial.

## Entidad: Info_Carne

| Campo | Tipo de dato | Clave | Descripción |
|---|---|---|---|
| id_corte | Entero | PK | Identificador único del corte |
| nombre_corte | String | - | Nombre comercial del corte |
| peso_disponible_kg | Float| - | Stock disponible en kilogramos |
| stock_minimo_kg | Float | - | Nivel mínimo que activa la reposición |
| requiere_reposicion | Booleano | - | Indica si debe solicitarse reposición |

## Entidad: Venta_Mostrador

| Campo | Tipo de dato | Clave | Descripción |
|---|---|---|---|
| id_venta | Entero | PK | Identificador único de la venta |
| numero_ticket | String | UNIQUE | Número del comprobante |
| fecha_hora | DATETIME | - | Fecha y hora de la operación |
| id_corte | Entero | FK | Referencia a Info_Carne.id_corte |
| kilos_vendidos | Float | - | Cantidad vendida en kilogramos |
| monto_cobrado | Float | - | Importe total cobrado |

## Entidad: Alerta_Reposicion

| Campo | Tipo de dato | Clave | Descripción |
|---|---|---|---|
| id_alerta | Entero | PK | Identificador único de la alerta |
| fecha_emision | DATETIME | - | Fecha y hora de generación |
| id_corte | Entero | FK | Referencia a Info_Carne.id_corte |
| kilos_solicitados | Float | - | Cantidad requerida para la reposición |
| transporte_despachado | Booleano | - | Indica si el transporte fue despachado |

## Reglas de integridad

- Cada venta debe estar vinculada con un corte existente.
- Cada alerta debe estar vinculada con un corte existente.
- Los kilogramos vendidos y solicitados deben ser mayores que cero.
- El peso disponible no puede ser negativo.
- Los campos de fecha y hora deben utilizar DATETIME.
- No debe eliminarse un corte que tenga ventas o alertas relacionadas.
