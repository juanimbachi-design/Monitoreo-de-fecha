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
## Entradas (Inputs)
* Productos string 
* Tipo de producto string 
* Fecha de vencimiento float

## Procesos (Throughput)
  * Guarda los datos en el programa
  * Veridica que el producto aun se pueda consumir en la fecha establecida

## Salidas (Ouputs)
 * Imprime un mensaje informando si los productos han caducado
 * Imprime una lista de los productos que estan proximos a caducar

## Usuarios y roles
* el adminisrtrador del programa
* Solo un usuario tiene todos los permisos

## Informacion manejada
* Los productos que ya caducaron
* Mayor cantidad de productos caducados que consumibles
  
