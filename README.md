solo hay un commit porque este ejercicio lo hice en otro repositorio y lo unico que he hecho aqui es moverlo a este nuevo repositorio e implementarle el firebase, el otro repositorio donde están los commits es examen1eventos

https://github.com/ffernandoss/ejercicio2e.git


Ejecutar la aplicación
Abre el proyecto en Android Studio.
Conecta un dispositivo Android o inicia un emulador.
Ejecuta la aplicación.
Estructura del Proyecto
Ejercicio2MainActivity.kt
Esta es la actividad principal que muestra una pantalla de bienvenida y un botón para navegar a la actividad de la lista de compras.  
ListaCompraActivity.kt
Esta actividad permite al usuario añadir y eliminar productos de la lista de compras. Los datos se almacenan en Firebase Firestore.  
Producto.kt
Clase de datos que representa un producto en la lista de compras.  
Funcionalidades
Añadir Producto: Permite añadir un producto a la lista de compras y almacenarlo en Firebase Firestore.
Eliminar Producto: Permite eliminar un producto de la lista de compras y de Firebase Firestore.
Mostrar Lista de Compras: Muestra la lista de productos añadidos.
Calcular Precio Total: Calcula y muestra el precio total de los productos en la lista de compras.
