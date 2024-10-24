# Sistema POS para MiniSuper

Este proyecto es una implementación en Java de un sistema de Punto de Venta (POS) diseñado para operar en un "MiniSuper". Facilita la facturación de compras y gestiona el catálogo de productos, la lista de clientes, los cajeros y el historial de facturación.

El sistema POS está diseñado para optimizar las operaciones diarias en un MiniSuper, proporcionando una interfaz gráfica de usuario (GUI) tipo Swing. La persistencia de datos se lleva a cabo utilizando una base de datos en MySQL. Además, el sistema sigue una arquitectura en capas y aplica el patrón Modelo-Vista-Controlador (MVC).

## Integrantes del Proyecto

- **Sebastián Álvarez Gómez**
- **Esteban Cruz**
- **Anthony Li Perera**

## Funcionalidades

1. **Facturación**  
   - Permite a los cajeros facturar productos.
   - Selección de cliente y cajero desde listas.
   - Agrega productos a la factura mediante búsqueda por código o descripción.
   - Calcula el total por línea y total de la factura, mostrando un documento PDF al finalizar.

2. **Catálogo de Clientes**  
   - Búsqueda, inclusión, consulta, modificación y borrado de clientes.
   - Registro de ID, nombre, teléfono, email y porcentaje de descuento.

3. **Lista de Cajeros**  
   - Búsqueda, inclusión, consulta, modificación y borrado de cajeros.
   - Registro de ID y nombre.

4. **Catálogo de Productos**  
   - Búsqueda, inclusión, consulta, modificación y borrado de productos.
   - Registro de código, descripción, unidad de medida, precio unitario, existencias y categoría.

5. **Estadísticas**  
   - Genera estadísticas de ventas mensuales por categoría de productos.

6. **Histórico de Facturas**  
   - Listado y búsqueda de facturas existentes con detalles.
