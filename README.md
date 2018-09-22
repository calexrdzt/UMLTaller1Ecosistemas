# UML Taller1 Ecosistemas de aplicaciones Servidor en Eclipse

## Main
+ **Main(String[]):** Con este metodo se ejecuta la aplicación
+ **Setup() : void :** Se establece las cosas que se ejecutan al iniciar el codigo
+ **Settings() :** void : Configuración del lienzo
+ **Draw() : void :** se dibuja toda la parte gráfica de la app
+ **MousePressed() :** void : Metodo para ejecutrar los clicks del mouse

## Logica
+ **Logica(PApplet app):** Constructor de la Logica
+ **Pintar() : void:** Pinta la parte grafica de los elementos graficos
+ **Interaccion() : void:** Metodo para establecer las relaciones entre los diferentes elementos
+ **EjecutarMouse() : void:** Ejecutar las funciones del mouse

## Personaje
+ **Personaje(int x, int y):** Constructor del personaje, con X y Y inicial
+ **Pintar() : void:** Pinta el personaje y su gif
+ **Movimiento() : void:** Metodo para el movimiento del personaje
+ **getPosX : void:** Obtener la posición en X del personaje
+ **getPosY : void:** Obtener la posición en Y del personaje
+ **setPosX(float) : void:** Se realiza el cambio en la posicion X del personaje
+ **setPosY(float) : void:** Se realiza el cambio en la posicion Y del personaje

## Item
+ **Item(int x, int y):** Constructor del item, con X y Y inicial
+ **Aparecer() : void:** Metodo para mostrar los elementos en la pantalla
+ **Desaparecer(): void:** Metodo para desaparecer los elementos de la pantalla
+ **getPosrX : void:** Obtener la posición en X del item
+ **getPosrY : void:** Obtener la posición en Y del item
+ **setPosrX(float) : void:** Se realiza el cambio en la posicion X del item
+ **setPosrY(float) : void:** Se realiza el cambio en la posicion Y del item

## Servidor
+ **Run() : void:** Metodo para iniciar el Hilo
+ **Enviar() : void:** Metodo para enviar informacion al cliente en Android

## Receptor
+ **Receptor(Socket socket):** Constructor del receptor
+ **Run() : void:** Metodo para iniciar al hilo

# UML Taller1 Ecosistemas de aplicaciones Cliente en Android

## ActivityMain
+ **onCreate(Bundle):** Metodo para iniciar la aplicación
+ **BotonesMov() : void:** Metodo para ejecutar la funcion de cada boton que mueve el personaje

## Receptor
+ **Receptor(Socket socket):** Constructor del receptor, recibe un Socket
+ **Run() : void:** Metodo para iniciar el hilo del receptor

## Cliente
+ **Cliente (MainActivity Activity):** Constructor del cliente, recibe una Activity
+ **Run () : Void:** Metodo para iniciar el hilo del receptor
+ **Enviar () : Void:** Metodo para enviar la información 

