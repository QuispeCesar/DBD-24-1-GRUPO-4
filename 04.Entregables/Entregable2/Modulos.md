# Módulos

# Módulo 1: CRM
- Responsabilidades:
  - Gestionar relaciones con clientes actuales y potenciales.
  - Administrar leads, oportunidades de venta, clientes y procesos comerciales.
  - Administrar leads, oportunidades de venta, clientes y procesos comerciales.
- Visibilidad de interfaces
  - Interfaz visible para los usuarios de marketing y puedan adecuar los anuncios según los clientes potenciales.
  - Interfaz visible para visualizar las necesidades o quejas de los clientes.
  - Interfaz visible para mostrar los mejores clientes.
- Interacción con otros módulos:
  - Interacción con Compras:
    El módulo de CRM ayudará a gestionar que productos deberían comprarse más para venderlos.
  - Interacción con Ventas:
    El módulo de CRM necesita las ventas para saber quiénes son sus mejores cliente.

Módulo 2: Compras
# Módulo 2: Compras
- Responsabilidades:
  - Almacenar compras realizadas por la empresa, incluyendo detalles como fecha, proveedor, productos adquiridos y cantidades.
  - Actualizar automáticamente el stock de productos en el inventario de la empresa después de cada compra.
  -  Generar notificaciones sobre productos que necesitan reabastecimiento o que están por debajo del nivel mínimo de stock.
  -  Recibir ofertas de proveedores y compararlas para determinar la mejor opción de compra.
  - Sugerir al usuario el proveedor más conveniente en función de criterios como precio, calidad y disponibilidad de productos.
  - Permitir la gestión y seguimiento de órdenes de compra y facturas.
  - Integrarse con el módulo de inventario para mantener actualizada la información sobre el stock de productos.
- Visibilidad de interfaces
  - Acceso al panel de control del módulo de compras para gestionar todas las operaciones relacionadas con la compra de productos.
  - Visualización de las compras realizadas, así como detalles como proveedor, fecha y productos adquiridos.
  - Recepción de notificaciones sobre productos con bajo stock o faltantes.
  - Visualización de ofertas recibidas de proveedores y comparación de precios y condiciones.
  - Posibilidad de realizar órdenes de compra y gestionar facturas desde la misma interfaz.
- Interacción con otros módulos:
  - Interacción con Almacén:
    Después de cada compra, se actualiza el stock de productos en el almacén para reflejar las nuevas adquisiciones.
  - Interacción con Finanzas:
    Cada transacción de compra se registra en los libros contables para mantener un registro preciso de los gastos.
  - Interacción con Autenticación/Registro de Usuario:
    Solo usuarios autenticados pueden acceder a la función de compras, lo que garantiza la seguridad y la integridad de las transacciones.
   
# Módulo 3: Ventas
- Responsabilidades:
  - Registrar todas las ventas realizadas por la empresa, incluyendo detalles como fecha, cliente, productos vendidos y cantidades.
  - Actualizar automáticamente el stock de productos en el inventario de la empresa después de cada venta.
  - Gestionar los diferentes métodos de pagos y definir reglas de pago.
  - Gestionar el historial de ventas de la empresa.
  - Gestionar el pago de los pedidos que realizan los clientes.
  - Informar a los clientes que su pedido ya se encuentra pagado, confirmar la compra, notificar que pueden acceder a un seguimiento de su producto.
- Visibilidad de interfaces:
   - Interfaz de "Home" para el gestor de ventas correspondiente.
   - Visualización del historial de ventas de la empresa. Se puede configurar para aplicar filtros a dicha tabla.
   - Interfaz de carro de compra para los clientes para la visaulización de productos, cantidad, fechas, dirrección para el cliente
   - Una visualización mas profunda donde esten los detalles del producto para el cliente.
   - Una visualización donde se escoja un método de pago para nuestro cliente.
   - Una visualizacíon donde se pueda añadir otra dirección para la comodidad del cliente. También una ventana de confirmación
   - Una pequeña venta que confirme el pago del producto. 
- Interacción con otros módulos:
   - Interacción con Almacén:
    Antes de procesar una venta, se verifica la disponibilidad de productos en el almacén para evitar ventas de productos agotados.
   - Interacción con Finanzas:
   Cada transacción de venta se registra en los libros contables para mantener un registro preciso de los ingresos.
   - Interacción con CRM:
    La información y datos que genere ventas puede ser de mucha utilidad para el área de CRM, que requiere de estos datos para hacer sus análisis.
   - Interacción con distribución:
    Distribuciónn necesita que se realice la compra para poder proseguir con el proceso de entrega de producto. Son modulos altamente ligados. 
   
# Módulo 4: Almacén
- Responsabilidades:
  - Registrar la cantidad de productos disponibles en el almacén, así como los que faltan o están por debajo del nivel mínimo de stock.
  - Permitir la gestión y seguimiento de las existencias de productos, incluyendo la recepción de notificaciones sobre productos bajos en stock.
  - Integrar información sobre los pedidos de los clientes para planificar la salida de productos del almacén.
  - Asociar cada producto con una ubicación específica dentro del almacén para facilitar su localización y manejo.
  - Proporcionar información actualizada sobre el inventario de productos a otros módulos del sistema, como ventas y compras.
  - Permitir la generación de informes y estadísticas sobre el movimiento de productos en el almacén para análisis y toma de decisiones.
- Visibilidad de interfaces:
  - Acceso al panel de control del módulo de almacén para gestionar y monitorear las existencias de productos.
  - Visualización de la cantidad actual de productos disponibles, así como aquellos que están por debajo del nivel mínimo de stock.
  - Recepción de notificaciones sobre productos bajos en stock para tomar acciones correctivas.
  - Asociación de productos con ubicaciones específicas dentro del almacén para facilitar su localización y manejo.
- Interacción con otros módulos:
  - Interacción con Compras:
    Después de cada compra, se actualiza el stock de productos en el almacén para reflejar las nuevas adquisiciones.
  - Interacción con Ventas:
    Antes de procesar una venta, se verifica la disponibilidad de productos en el almacén para garantizar una entrega oportuna.

# Módulo 5: Distribución
- Responsabilidades:
  - Asociar cada pedido realizado por un cliente con un repartidor disponible para su entrega
  - Calcular y asignar el costo del servicio de entrega (delivery) al pedido y comunicarlo al repartidor.
  - Permitir al repartidor actualizar el estado del pedido en tiempo real, informando al cliente sobre su progreso.
  - Facilitar la comunicación entre el cliente, el repartidor y la empresa a través de la aplicación, proporcionando un canal de mensajes instantáneo.
  - Proporcionar detalles sobre el repartidor asignado a cada pedido, incluyendo información de contacto y tiempo estimado de llegada.
  - Implementar un sistema de rastreo para que el cliente pueda seguir el progreso de su pedido en tiempo real y tener una mayor confiabilidad en la entrega.
- Visibilidad de interfaces:

  Para el cliente:
  - Acceso a la aplicación para realizar pedidos y seguir su progreso de entrega.
  - Visualización de detalles sobre el repartidor asignado, como nombre, foto y tiempo estimado de llegada.
  - Comunicación con el repartidor a través de mensajes instantáneos para coordinar detalles adicionales o hacer consultas.
  - Seguimiento en tiempo real del estado del pedido mediante el sistema de rastreo.
  
  Para el repartidor:
  - Acceso a la aplicación para recibir detalles sobre los pedidos asignados y actualizar su estado.
  - Visualización del costo del servicio de entrega asociado a cada pedido.
  - Comunicación con el cliente y la empresa a través de mensajes instantáneos para informar sobre el progreso de la entrega.
  - Utilización del sistema de rastreo para proporcionar una ubicación precisa y confiable al cliente durante la entrega.
  
  Para la empresa:
  - Acceso a una plataforma de gestión para asignar repartidores a pedidos y monitorear el progreso de las entregas.
  - Visualización de detalles sobre los repartidores disponibles y sus horarios de trabajo.
  - Comunicación con los clientes y repartidores en caso de incidencias o cambios en los pedidos.
 - Interacción con otros módulos:
   - Interacción con Almacén:
    Antes de cada entrega, se verifica la disponibilidad de productos en el almacén para garantizar una entrega exitosa.
   - Interacción con Ventas:
     Después de cada entrega, se actualiza el estado de la venta para reflejar la finalización de la transacción.
  
# Módulo 6: Finanzas
- Responsabilidades:
  - Gestionar los procesos contables de la empresa, incluyendo la creación y mantenimiento de registros financieros.
  - Registrar todas las transacciones financieras, tales como compras, ventas, gastos e ingresos.
  - Generar reportes financieros periódicos, como estados de resultados, balances generales y flujos de efectivo.
  - Realizar conciliaciones bancarias para asegurar la precisión de los registros financieros.
  - Facilitar la facturación electrónica y la declaración de impuestos ante las autoridades fiscales.
  - Automatizar procesos repetitivos relacionados con la contabilidad para aumentar la eficiencia y reducir errores.
  - Mantener la confidencialidad y seguridad de la información financiera de la empresa.
- Visibilidad de interfaces:
  - Acceso al sistema de contabilidad para ingresar y revisar registros financieros.
  - Generación de reportes financieros y análisis de datos para tomar decisiones estratégicas.
  - Realización de conciliaciones bancarias y seguimiento de transacciones.
  - Interacción con otras áreas de la empresa para garantizar la exactitud de los registros contables.
- Interacción con otros módulos:
  - Interacción con Compras y Ventas:
   Registra todas las transacciones financieras relacionadas con compras y ventas para mantener un registro preciso de los ingresos y gastos de la empresa.
  - Interacción con Autenticación/Registro de Usuario:
   Garantiza que solo usuarios autorizados tengan acceso a los registros financieros y las funciones de contabilidad.
  
# Módulo 7: Marketing
- Responsabilidades:
  - Diseñar funciones de promoción de productos en la interfaz web, como banners y publicaciones en redes sociales.
  - Crear elementos de interfaz para mostrar promociones y ofertas especiales a los clientes.
  - Diseñar formularios para recopilar datos de clientes y realizar análisis de mercado.
  - Diseñar formularios para recopilar datos de clientes y realizar análisis de mercado donde según el nivel el cliente accede a diversas promociones.
  - Integrar un sistema de seguimiento de progreso para que los clientes puedan ver cuánto les falta para alcanzar el próximo nivel y las recompensas asociadas.
- Visibilidad de interfaces:
   - Interfaz visible del progreso en su cuenta personal.
  - Acceso a un panel de control personalizado donde se muestra el progreso actual del cliente.
  - Gráficos o indicadores visuales que representan el nivel actual del cliente en el programa de fidelización.
  - Historial de compras y actividad de la cuenta para que el cliente pueda realizar un seguimiento de sus acciones pasadas.
  - Acceso a banners y publicaciones de promociones en diversas secciones del sitio web.
 - Interacción con otros módulos:
   - Interacción con Finanzas:
     Utiliza información financiera para optimizar las estrategias de marketing y promoción en función del rendimiento económico de la empresa.
   - Interacción con Autenticación/Registro de Usuario:
     Personaliza las promociones y ofertas según el perfil y las preferencias de los usuarios registrados.
    
[Regresar a Entregable 2](entregable2.md)
