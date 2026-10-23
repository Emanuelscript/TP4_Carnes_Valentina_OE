## Sistema de Gestión de Inventario - Carnes Valentina
Documentacion del sistema propuesto para registrar ventas, controlar el stock de carne y gestionar reposiciones en Carnes Valentina.
## Software propuesto
Registro, control de stock y reposiciones en Carnes Valentina.
## Descripción
Programa de control de inventario, al registrar cada venta en el mostrador mediante balanzas conectadas con el software, el sistema descuenta automáticamente el stock disponible y además cuando el stock de carne llega a un nivel crítico genera una alerta para que el padre verifique la disponibilidad y gestione la reposición.
## Objetivo
Automatizar el control de inventario de cortes de carne mediante el registro de ventas, actualización automática de stock y generación de alertas de reposición.
## Declaración de Transparencia en el Uso de Inteligencia Artificial

Durante el desarrollo del proyecto se utilizaron herramientas de inteligencia artificial como apoyo para comprender las consignas, organizar ideas, revisar la redacción y mejorar la presentación de la documentación.

La inteligencia artificial también se utilizó para recibir orientación sobre la organización del repositorio en GitHub, el uso de ramas y Pull Requests, la elaboración de historias de usuario, la definición de indicadores de control y la revisión del diccionario de datos.

Los resultados generados no fueron incorporados automáticamente. Cada propuesta fue revisada, comparada con las consignas de la asignatura y adaptada a las características reales del caso de estudio Carnes Valentina.

### Ejemplos de consultas realizadas

#### Historias de usuario

**Síntesis de la consulta:** se solicitó orientación para revisar las historias relacionadas con la actualización automática del inventario, las alertas de reposición y las estadísticas de ventas.

**Aporte obtenido:** se propuso mantener el formato “Como usuario, quiero funcionalidad, para beneficio” e incorporar criterios de aceptación verificables.

**Revisión humana:** se conservaron los roles correspondientes a Carnes Valentina y se agregaron condiciones concretas para determinar cuándo cada historia puede considerarse cumplida.

#### Indicadores de control

**Síntesis de la consulta:** se solicitó orientación para transformar las metas cuantitativas definidas en la planificación en indicadores de control.

**Aporte obtenido:** se propuso agregar a cada indicador una fórmula, un estándar de desempeño, una frecuencia de medición y una fuente de información.

**Revisión humana:** los indicadores fueron relacionados con las metas originales del proyecto: actualización del stock en menos de 5 segundos, disponibilidad del 99 %, capacidad de 300 transacciones diarias y cumplimiento del plazo de implementación. También se incorporaron responsables y acciones ante desvíos.

#### Diccionario de datos

**Síntesis de la consulta:** se solicitó revisar las entidades necesarias para registrar cortes, ventas y alertas de reposición.

**Aporte obtenido:** se identificó la necesidad de utilizar tipos de datos específicos y de establecer relaciones entre las entidades.

**Revisión humana:** se sustituyeron los campos de fecha definidos como texto por DATETIME, se identificaron las claves primarias y foráneas y se incorporó id_corte como clave foránea en Venta_Mostrador y Alerta_Reposicion.

#### Integración de las entregas progresivas

**Síntesis de la consulta:** se solicitó orientación para integrar las cuatro entregas sin limitarse a unir los documentos de manera consecutiva.

**Aporte obtenido:** se propuso organizar el contenido como un único proyecto progresivo, eliminar repeticiones y relacionar las correcciones docentes con las secciones correspondientes.

**Revisión humana:** se conservaron los datos comprobables del caso, se revisó la coherencia entre las entregas y se identificaron las evidencias reales que debían incorporarse desde GitHub y el tablero de gestión.

### Correcciones y decisiones humanas

Las principales correcciones realizadas sobre los aportes obtenidos fueron:

- Adaptación de las historias de usuario a los roles reales de Carnes Valentina.
- Incorporación de criterios de aceptación verificables.
- Uso de DATETIME para los campos de fecha y hora.
- Incorporación de claves primarias y foráneas.
- Inclusión de id_corte en las entidades transaccionales.
- Desarrollo de las fórmulas y estándares de los indicadores.
- Incorporación de responsables, fuentes y acciones ante desvíos.
- Revisión de la coherencia entre las cuatro entregas.
- Aplicación de las observaciones realizadas por el docente 
## Autor
José Emanuel Leguizamón.
