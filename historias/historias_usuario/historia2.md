# Historia de usuario #2

**Como** usuario registrado  
**Quiero** iniciar sesión con mi correo y contraseña  
**Para** acceder al sistema con los permisos correspondientes a mi rol

## Criterios de aceptación:
- El sistema debe autenticar al usuario mediante correo institucional y contraseña, mostrando un mensaje de error claro si las credenciales son incorrectas.
- Tras autenticarse correctamente, el sistema debe redirigir al usuario a la vista correspondiente según su rol (administrador o usuario general).
- El formulario debe validar que ambos campos estén completos antes de enviar la solicitud.
- La sesión debe mantenerse activa hasta que el usuario cierre sesión manualmente.