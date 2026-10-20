## Diccionario de Datos

## Entidad: Info_carne
 Campo | Tipo de dato	| Descripción
id_corte |	Entero |	Identificador único del corte
nombre_corte	| String	| Nombre comercial del corte
peso_disponible_kg	| Decimal	| Stock disponible en kilogramos
requiere_reposicion	| Booleano	| Indica si debe solicitarse reposición

## Entidad: Venta_Mostrador
Campo	| Tipo de dato | Descripción
numero_ticket	| Entero	| Identificador de la venta
fecha_hora | DateTime	| Fecha y hora de la operación
kilos_vendidos | Decimal | Cantidad vendida
monto_cobrado	| Decimal	| Importe total abonado

## Entidad: Alerta_Reposicion
Campo	| Tipo de dato	| Descripción
id_alerta	| Entero	| Identificador de la alerta
fecha_emisión |	DateTime | Fecha de generación
kilos_solicitados	| Float	| Cantidad requerida
estado_despacho | Booleano	| Estado del envío
