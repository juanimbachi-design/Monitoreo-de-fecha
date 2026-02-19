# Monitoreo-de-fecha
MiniMarket
## Descripcion
Sistema de información para la toma de decisiones que monitorea automáticamente las fechas de vencimiento de los productos en supermercados o tiendas. El sistema genera alertas, reportes y notificaciones sobre productos próximos a vencer, permitiendo a los encargados tomar decisiones oportunas como reorganizar inventario, y optimizar pedidos futuros, reduciendo pérdidas económicas y desperdicio de alimentos.
## Equipo
Nombres:
Juan David Mosquera Imbachi 
Juan David Montengero
Kevin Alejandro Muñoz 
Andres Alejandro Rodriguez

#Arquitectura del sistema:[ monitoreo de fecha ]

## Entradas (Inputs)
* productos (string)
* fechas de vencimiento (float)
* tipos de productos (string)

## Procesos (Throughput)
* guarda los datos en el programa
* verifica que el producto se pueda consumir en la fecha establecida
  
## Salidas (Outputs)
* imprime un mensaje si los productos han caducado
* imprime una lista de los productos que estan proximos a caducar

## Usuarios y Roles 
*  el  administrador del programa
*  solo un usuario tiene todos los permisos

  ##  Informacion Manejada
* los productos que ya caducaron
* mayor cantidad de productos caducados que de productos consumibles
