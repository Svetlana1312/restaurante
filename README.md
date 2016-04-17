El restaurante Ángel ha decidido solicitar la construcción de un sistema para la gestión de las reservas de sus mesas para comidas y los pedidos de las mismas.
El restaurante Ángel está situado en una zona de oficinas, y pretende reducir el tiempo de espera de los usuarios para ser atendidos y solicitar sus pedidos.
Bases de datos 
- Usuarios: dni, nombre, apellidos, teléfono, email, password, tipo
- Mesas: numeroMesa, tamaño
- Productos: idproducto, nombreProducto, tipoProducto
- MenusDia:idMenu(5primeros5segundos5Postres), fechaMenu, precioMenu
-PlatosXMenu: idMenuFK, idProductoFK
- Pedidos: idPedido, idProductoFK, cantidad
- Reservas: idreserva, idclienteFK, numeroMesaFK, idpedidoFK, inicio, fin, numeroComensales, activa

Login Usuario > Reservar > Ver dia > Especificar comensales > Ver mesa/horario > Elegir menús > Confirmar
+ Perfil de usuario > Modificar reserva > Modificar datos personales

Login Admin > Gestionar reservas > Gestionar menú > Gestionar usuarios

-Preguntas:
Cuanto dura la reserva? Horarios mesa? 1h15 // 12.30 a 16 // Lunes-viernes
Tamaño de mesas? 4de5, 1de10, 15de2
Menus? Primero segundo postre
Antelacion de la reserva? 30min