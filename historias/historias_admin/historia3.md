# Historia de usuario #3

**Como** administrador  
**Quiero** crear, editar, visualizar y eliminar actividades inclusivas  
**Para** mantener actualizado el catálogo de actividades del sistema

## Criterios de aceptación:
- El formulario de creación/edición debe incluir todos los campos requeridos: nombre, fecha, cupo, responsable, descripción, tipo de inclusión/discapacidad, latitud, longitud y estado (tabla Estados).
- Al guardar una actividad, el sistema debe registrar el evento en la tabla Auditoría_Actividades con fecha, hora y usuario responsable.
- La eliminación de una actividad debe solicitar confirmación antes de ejecutarse y reflejarse inmediatamente en el listado.
- Los campos obligatorios deben mostrar mensajes de advertencia si se intenta guardar el formulario incompleto.