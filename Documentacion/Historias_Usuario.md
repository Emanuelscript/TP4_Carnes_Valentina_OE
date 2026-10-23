# Historias de Usuario

## HU-01 - Actualización automática del stock

Como encargada de la carnicería, quiero que el sistema actualice automáticamente el stock después de cada venta, para conocer en tiempo real la disponibilidad de cada corte.

### Criterios de aceptación

- La venta debe registrar fecha, hora, corte, kilogramos vendidos e importe cobrado.
- La venta debe estar vinculada con un corte existente.
- El stock debe actualizarse en menos de 5 segundos.
- El sistema no debe aceptar cantidades iguales o menores que cero.
- El stock disponible no puede quedar con valores negativos.
- La operación debe quedar registrada para su posterior consulta.

## HU-02 - Gestión de reposición

Como responsable del sector ganadero, quiero recibir alertas cuando el stock alcance un nivel crítico, para planificar la reposición de mercadería.

### Criterios de aceptación

- Cada corte debe tener definido un nivel mínimo de stock.
- La alerta debe generarse cuando el stock sea igual o inferior al mínimo establecido.
- La alerta debe identificar el corte y registrar la fecha y hora de emisión.
- La alerta debe indicar la cantidad sugerida para reponer.
- El sistema no debe generar dos alertas abiertas para el mismo corte.
- La alerta debe permitir registrar si el transporte fue despachado.

## HU-03 - Estadísticas de ventas

Como propietario del negocio, quiero consultar estadísticas de ventas, para tomar mejores decisiones sobre producción, abastecimiento y comercialización.

### Criterios de aceptación

- La consulta debe permitir seleccionar un período.
- El reporte debe mostrar los kilogramos vendidos.
- El reporte debe informar los importes cobrados.
- El sistema debe identificar los cortes con mayor y menor rotación.
- La información debe poder filtrarse por corte.
- El resultado debe presentarse mediante un resumen claro y legible.
