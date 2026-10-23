# Indicadores de Control y Estándares de Desempeño

Los siguientes indicadores recuperan las metas cuantitativas definidas durante la planificación del proyecto y permiten controlar el desempeño del sistema.

## 1. Tiempo de actualización del stock

**Objetivo:** medir el tiempo transcurrido entre el registro de una venta y la actualización del inventario.

**Fórmula:**

Tiempo promedio = suma de los tiempos de actualización / cantidad total de ventas medidas

**Estándar de desempeño:**

- Tiempo promedio menor a 5 segundos.
- Al menos el 95 % de las ventas debe actualizar el stock dentro de ese tiempo.

**Frecuencia:** diaria.

**Fuente de información:** registros de ventas y actualizaciones del inventario.

**Responsable:** responsable técnico del sistema.

**Acción ante un desvío:** revisar la conexión con la balanza, las consultas a la base de datos y el procesamiento de las ventas.

## 2. Disponibilidad del sistema

**Objetivo:** medir el porcentaje del horario laboral durante el cual el sistema se encuentra operativo.

**Fórmula:**

Disponibilidad (%) = tiempo disponible / tiempo laboral planificado × 100

**Estándar de desempeño:** disponibilidad mensual igual o superior al 99 %.

**Frecuencia:** mensual.

**Fuente de información:** registro de actividad e incidentes.

**Responsable:** soporte técnico.

**Acción ante un desvío:** identificar la causa de las interrupciones, registrar los incidentes y aplicar medidas de recuperación.

## 3. Alertas de reposición generadas correctamente

**Objetivo:** comprobar que el sistema genere alertas cuando un corte alcance el nivel mínimo de stock.

**Fórmula:**

Alertas correctas (%) = alertas generadas correctamente / situaciones de stock crítico detectadas × 100

**Estándar de desempeño:** 100 % de generación correcta.

**Frecuencia:** semanal.

**Fuente de información:** registro de inventario y tabla de alertas.

**Responsable:** encargada de la carnicería.

**Acción ante un desvío:** revisar el stock mínimo configurado, la regla de generación y la existencia de alertas duplicadas.

## 4. Capacidad operativa

**Objetivo:** medir la cantidad de transacciones que el sistema puede procesar durante una jornada.

**Fórmula:**

Capacidad operativa = cantidad total de ventas procesadas durante el día

**Estándar de desempeño:** al menos 300 transacciones diarias sin errores críticos.

**Frecuencia:** diaria y durante las pruebas de carga.

**Fuente de información:** base de datos de ventas y reporte de pruebas.

**Responsable:** responsable técnico del sistema.

**Acción ante un desvío:** revisar el rendimiento de la base de datos y optimizar las operaciones que presenten demoras.

## 5. Exactitud del inventario

**Objetivo:** comparar el stock registrado por el sistema con el conteo físico.

**Fórmula:**

Exactitud (%) = registros coincidentes / registros auditados × 100

**Estándar de desempeño:** exactitud igual o superior al 98 %.

**Frecuencia:** semanal.

**Fuente de información:** inventario del sistema y conteo físico.

**Responsable:** encargada de la carnicería.

**Acción ante un desvío:** realizar una conciliación y revisar ventas no registradas, errores de carga o modificaciones manuales.

## 6. Alertas atendidas dentro del plazo

**Objetivo:** medir el porcentaje de alertas de reposición atendidas dentro de las 24 horas.

**Fórmula:**

Alertas atendidas (%) = alertas atendidas dentro de 24 horas / total de alertas emitidas × 100

**Estándar de desempeño:** al menos el 95 %.

**Frecuencia:** semanal.

**Fuente de información:** registro de alertas.

**Responsable:** responsable del sector ganadero.

**Acción ante un desvío:** revisar las notificaciones, la asignación de responsables y el procedimiento de despacho.

## 7. Cumplimiento del plazo de implementación

**Objetivo:** verificar el cumplimiento del plazo previsto para completar el módulo.

**Fórmula:**

Cumplimiento (%) = hitos completados en fecha / hitos planificados × 100

**Estándar de desempeño:** 100 % de los hitos completados antes de los 3 meses.

**Frecuencia:** semanal durante el desarrollo.

**Fuente de información:** cronograma y tablero del proyecto.

**Responsable:** responsable del proyecto.

**Acción ante un desvío:** reorganizar las tareas, revisar la carga de trabajo y priorizar las funciones críticas.
