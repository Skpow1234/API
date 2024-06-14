# Lista de mejoras que podrían realizarse en el proyecto

- Refactorizar la cantidad/stock del producto para que sea [atómica y segura en concurrencia](https://www.freecodecamp.org/news/acid-databases-explained/#what-does-atomicity-mean). La implementación actual podría llevar a valores de stock inválidos si se realizan múltiples solicitudes al mismo tiempo. No solo eso, cada vez que se actualiza la cantidad de un producto, necesitamos consultar la tabla de productos *(viola el principio de normalización de bases de datos)*.

- Implementar la funcionalidad de direcciones de usuarios. De esta manera, podemos almacenar la dirección del usuario y usarla en el proceso de pago en lugar de un valor codificado.

- Implementar el historial de pedidos del usuario. De esta manera, podemos almacenar los pedidos del usuario y mostrarlos en el perfil del usuario.

- Implementar el endpoint de cancelación de pedidos. De esta manera, podemos permitir que el usuario cancele un pedido si aún no ha sido enviado.
