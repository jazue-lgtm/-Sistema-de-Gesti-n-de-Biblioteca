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
