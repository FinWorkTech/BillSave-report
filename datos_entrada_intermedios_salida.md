## Datos de Entrada

| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| Correo o usuario | Identificación del usuario para el inicio de sesión. | Texto | Cadena de caracteres |
| Contraseña | Clave de acceso del usuario. | Texto (password) | Cadena de caracteres |
| Nombres y apellidos | Nombre completo del usuario. | Texto | Cadena de caracteres |
| Correo electrónico | Correo electrónico validado del usuario. | Texto (validación de email) | Correo electrónico válido |
| Nombre de usuario | Identificador único del usuario en la plataforma. | Texto (único) | Cadena de caracteres |
| Confirmación de contraseña | Verificación de coincidencia con la contraseña ingresada. | Texto (password) | Cadena de caracteres |
| Fecha de registro | Fecha en la que el usuario completó el registro. | Fecha | DD/MM/AAAA |
| Términos y condiciones aceptados | Confirmación de que el usuario acepta los términos y condiciones. | Booleano | Verdadero/Falso |
| Nombre del portafolio | Identificación del portafolio financiero. | Texto | Cadena de caracteres |
| Fecha de descuento del portafolio | Fecha en la que se aplica el descuento del portafolio. | Fecha | DD/MM/AAAA |
| Código del documento | Código único que identifica un documento financiero. | Texto | Cadena de caracteres |
| Valor nominal | Valor nominal del documento. | Número decimal | Numérico |
| Fecha de emisión | Fecha en la que se emitió el documento financiero. | Fecha | DD/MM/AAAA |
| Fecha de vencimiento | Fecha en la que vence el documento financiero. | Fecha | DD/MM/AAAA |
| Tasa nominal o efectiva | Tasa de interés asociada al documento. | Número decimal | Numérico |
| Moneda | Tipo de moneda en la que se registró el documento (S/ o USD). | Texto | Cadena de caracteres |

---

## Datos Intermedios

| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| Token de autenticación | Token generado tras el inicio de sesión para validar autenticación. | Texto (token) | Cadena de caracteres |
| Estado de validación de usuario | Estado que indica si el usuario fue validado correctamente. | Booleano | Verdadero/Falso |
| Número de intentos fallidos de inicio de sesión | Registro de intentos fallidos de inicio de sesión. | Número entero | Número entero |
| Saldo total del portafolio | Monto total acumulado en un portafolio financiero. | Número decimal | Numérico |
| Cantidad de documentos asociados | Número total de documentos registrados dentro del portafolio. | Número entero | Número entero |
| TCEA promedio del portafolio | Tasa de Costo Efectivo Anual promedio de los documentos del portafolio. | Número decimal | Numérico |
| Estado del documento financiero | Estado actual del documento financiero (Activo, Vencido, Pagado). | Texto | Cadena de caracteres |

---

## Datos de Salida

| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| Mensaje de error - Usuario o contraseña incorrectos | Mensaje que aparece cuando las credenciales son incorrectas. | Texto | Cadena de caracteres |
| Confirmación de registro exitoso | Mensaje de confirmación tras completar el registro. | Texto | Cadena de caracteres |
| Mensaje de error - Contraseñas no coinciden | Mensaje de error si las contraseñas ingresadas no coinciden. | Texto | Cadena de caracteres |
| Mensaje de error - Campos obligatorios no completados | Mensaje de error cuando no se completan todos los campos requeridos. | Texto | Cadena de caracteres |
| Número total de portafolios activos | Cantidad de portafolios que están en estado activo. | Número entero | Número entero |
| Número total de documentos en el sistema | Número total de documentos registrados en el sistema. | Número entero | Número entero |
| Reporte financiero generado | Reporte generado con datos financieros de portafolios y documentos. | Documento generado | Documento |
| Exportación de reporte en PDF o Excel | Opción para descargar el reporte financiero en formato PDF o Excel. | Archivo descargable | PDF/Excel |
