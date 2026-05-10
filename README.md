# Proyecto AdminCES

## Análisis Inicial: Funcionalidades de Adminces

### Panel sin login
- **Iniciar sesión (Admin)**
    - Acción: permite iniciar sesión de un administrador ya creado
    - Datos: email y contraseña
- **Registrarse (Admin)**
    - Acción: permite crear un nuevo administrador
    - Datos: nombre, apellido, email, contraseña, repetir contraseña y país nacimiento
- **Reiniciar contraseña (Admin)**
    - Acción: permite recuperar contraseña de administrador ya creado
    - Datos: email, contraseña, repetir contraseña

### Panel con login (admin)
- **Crear usuario tester**
    - Acción: El administrador crea una nueva cuenta de tester
    - Datos: nombre, apellido, email, país de nacimiento, contraseña por defecto y nivel de seniority
- **Reiniciar contraseña (Admin)** // Duplicada
- **Ver usuarios**
    - Acción: lista de usuarios registrados en el sistema
    - Datos: N/A
- **Borrar tester**
    - Acción: permite eliminar tester de la lista de usuarios registrados en el sistema
    - Datos: N/A
- **Perfil de Admin**
    - Acción: permite visualizar los datos personales del administrador
    - Datos: N/A
- **Editar datos**
    - Acción: permite modificar los datos personales del administrador
    - Datos: nombre, apellido, mail y país
- **Cerrar sesión**
    - Acción: permite cerrar la sesión del administrador
    - Datos: N/A