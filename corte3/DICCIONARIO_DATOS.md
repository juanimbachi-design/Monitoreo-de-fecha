
<img width="814" height="372" alt="Captura de pantalla 2026-05-14 171144" src="https://github.com/user-attachments/assets/1dab9bbf-f2dd-4e1a-9128-f4565b35da90" />










 # 4. DEFINICIÓN DE ROLES Y FUNCIONES
Para que los datos anteriores mantengan su calidad, asignen responsabilidades según lo visto en la clase anterior:
# 1)	¿Qué ROL es el encargado de capturar estos datos? (Ej: Recepcionista, Administrador, Cliente).
  El rol principal encargado de almacenar o capturar estos datos es el Recepcionista de almacén o       Encargado de inventario 
# 2)	¿Qué FUNCIÓN de validación debe realizar el sistema automáticamente?

•	Que la fecha de caducidad sea mayor de la fecha actual 
•	Que el código de productos y el lote sean únicos
•	Que la fecha de ingreso no sea una fecha futura
•	Alerta visualmente (en rojo o con mensajes) cuando un producto este próximo a caducar o ya está caducado (Si faltan >30 días Estado: consumible) y (si faltan <15 días Estado: Próximo a vencer) Y (Si la fecha ya paso Estado: vencido)


# 3)	¿Qué sucede con la información del sistema si este Rol no cumple su Función?
  Si el rol no cumple su función (por ejemplo, ingresa datos erróneos o incompletos) puede generar 
•	Alertas de caducidad incorrectas
•	Riesgo de vender o usar productos caducados
•	Perdida de stock real (por información desactualizada)
•	Posibles sanciones sanitarias, por esta razón, el sistema debe registrar quien ingreso cada dato 

