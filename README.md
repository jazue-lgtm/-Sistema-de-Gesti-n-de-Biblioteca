# -Sistema-de-Gestion-de-Biblioteca
Documentación del Sistema de Gestión de Biblioteca
Sistema de Gestión de Biblioteca
📘 Descripción del Proyecto

El Sistema de Gestión de Biblioteca es una aplicación diseñada para administrar libros, usuarios y préstamos dentro de una biblioteca académica o institucional.
Permite registrar libros, controlar préstamos y devoluciones, llevar un inventario actualizado y ofrecer una experiencia clara y eficiente tanto para el bibliotecario como para los lectores.

🎯 Objetivos del Sistema

Registrar libros con su respectiva información (título, autor, año, categoría).

Registrar usuarios que pueden solicitar préstamos.

Gestionar préstamos y devoluciones de libros.

Controlar disponibilidad del inventario en tiempo real.

Permitir la búsqueda rápida de libros por varios criterios.

Servir de base para módulos adicionales como reportes, reservas o notificaciones.

📌 Requerimientos del Sistema
✔ Requerimientos Funcionales

RF1: El sistema debe permitir registrar nuevos libros.

RF2: El sistema debe permitir administrar usuarios de la biblioteca.

RF3: El sistema debe registrar préstamos validando disponibilidad del libro.

RF4: El sistema debe registrar devoluciones y actualizar la disponibilidad.

RF5: El sistema debe permitir buscar libros por título, autor o categoría.

RF6: El sistema debe generar reportes de préstamos.

✔ Requerimientos No Funcionales

RNF1: El sistema debe responder en menos de 2 segundos.

RNF2: La interfaz debe ser clara y fácil de usar.

RNF3: La información debe mantenerse segura.

RNF4: Debe funcionar correctamente en navegadores modernos.

🧪 Tabla de Casos de Prueba

📝 La tabla está totalmente funcional en GitHub.

# 📋 TABLA DE CASOS DE PRUEBA – Sistema de Gestión de Biblioteca

| ID   | Requerimiento Asociado | Datos de entrada | Resultado esperado | Resultado obtenido |
|------|-------------------------|------------------|--------------------|---------------------|
| CP1  | RF1 – Registrar Libro   | Título: *El Quijote*  <br> Autor: *Cervantes* <br> Año: *1605* | Libro registrado correctamente | Correcto |
| CP2  | RF1 – Registrar Libro (duplicado) | Título: *El Quijote*  <br> Autor: *Cervantes* | “El libro ya existe en el sistema” | Correcto |
| CP3  | RF3 – Registrar Préstamo | Usuario: *Juan Pérez* <br> Libro: *El Quijote* | Préstamo registrado y libro cambia a “Prestado” | Correcto |
| CP4  | RF4 – Registrar Devolución | Usuario: *Juan Pérez* <br> Libro: *El Quijote* | Devolución exitosa y libro cambia a “Disponible” | Correcto |
| CP5  | RF5 – Búsqueda de Libros | Palabra clave: *Quijote* | Muestra libros relacionados | Correcto |
| CP6  | RF2 – Registrar Usuario  | Nombre: *Ana Torres* <br> Correo: *ana@gmail.com* | Usuario registrado exitosamente | Correcto |
| CP7  | RF2 – Registrar Usuario (correo duplicado) | Correo: *ana@gmail.com* | “El correo ya está registrado” | Correcto |
| CP8  | RF6 – Reporte de Préstamos | Solicitar reporte del día | Se genera listado de préstamos activos | Correcto |

🔧 Mantenimiento Correctivo

Solucionar fallos de registro de libros o usuarios.

Arreglar errores en búsqueda o disponibilidad incorrecta.

Reparar problemas con la base de datos o conexiones fallidas.

⚙️ Mantenimiento Perfectivo

Mejorar la interfaz del catálogo.

Agregar filtros adicionales y opciones avanzadas de búsqueda.

Optimizar el tiempo de carga y la organización interna del sistema.

🚀 Mantenimiento Evolutivo

Añadir reservas de libros.

Integrar notificaciones por correo sobre devoluciones.

Implementar códigos QR o códigos de barras para inventario.

Incluir reportes avanzados y estadísticas.

🧠 Reflexión Final

El Sistema de Gestión de Biblioteca es una herramienta esencial para mejorar la eficiencia en la administración de recursos bibliográficos.
Su implementación adecuada garantiza control, orden y facilidad en el manejo del inventario. Además, es una base sólida para futuras ampliaciones que transformen el sistema en una plataforma más completa y moderna.
