# Proyecto Software Avanzado
Notas Generales:
 * Todos los endpoints deben de ir en `kebab-case`;
 * Todos los objetos del payload deben de ir en `snake_case`;
 * Todas las URLs deben de ir en minúsculas.
 * Todos los objetos del payload deben de ir en minúsculas.

El objeto de respuesta (cliente a servidor) deberá tener el siguiente aspecto:
| Atributo | Tipo | Requerido | Descripción |
| ------ | ------ | ------ | ------ |
| status | string | SI | Puede ser cualquiera de los siguientes:  'success', 'fail', or 'error'. (minúsculas). |
| data | Object \| Object [] | NO | (Opcional) Contiene un objeto o un arreglo de objetos correspondientes a la solicitud. |
| message | string | NO | (Opcional)  Devuelve un mensaje relevante a la solicitud. |
## Registro
Registro [/registro][RegistroAPI]
* Registrar Cliente [/registro/#registrar-cliente][RegistroCliente]
* Registrar Proveedor [/registro/#registrar-proveedor][RegistroProveedor]

[RegistroAPI]: </registro/README.md>
[RegistroCliente]: </registro/README.md#registrar-cliente>
[RegistroProveedor]: </registro/README.md#registrar-proveedor>
## Login
Login [/login][LoginAPI]
* Login Cliente [/login/#login-proveedor][LoginCliente]
* Login Proveedor [/login/#login-proveedor][LoginProveedor]

[LoginAPI]: </login/README.md>
[LoginCliente]: </login/README.md#login-cliente>
[LoginProveedor]: </login/README.md#login-proveedor>

## Crear Producto
Crear Producto [/crear-producto][CrearProductoAPI]
* Crear Producto Cliente [/crear-producto/#crear-producto-cliente][CrearProductoCliente]
* Crear Producto Proveedor [/crear-producto/#crear-producto-proveedor][CrearProductoProveedor]

[CrearProductoAPI]: </crear-producto/README.md>
[CrearProductoCliente]: </crear-producto/README.md#crear-producto-cliente>
[CrearProductoProveedor]: </crear-producto/README.md#crear-producto-proveedor>

## Ver Productos
Ver Productos [/ver-productos][VerProductosAPI]
* Ver todos los productos [/ver-productos/#ver-productos][VerProductos]
* Ver productos fase 3 [/ver-productos/#ver-productos-fase-3][VerProductosFase3]
* Ver un producto [/ver-productos/#ver-producto][VerProducto]

[VerProductosAPI]: </ver-producto/README.md>
[VerProductos]: </ver-producto/README.md#ver-todos-los-productos>
[VerProductosFase3]: </ver-producto/README.md#ver-productos-fase-3>
[VerProducto]: </ver-producto/README.md#ver-producto>

## Comprar
Realizar Compra [/realizar-compra][ComprarAPI]

[ComprarAPI]: </comprar/README.md>