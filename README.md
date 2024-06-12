## DatePicker y ColorPicker
####Introducción
Este programa de JavaFX nos permite jugar con fechas y colores.  
####Desarrollo
Conozcamos con más detalle cómo se usa este programa en conjuntos con los elementos que lo componen:
#####Uso
En la parte superior, encontrarás un cuadro llamado *"Selecciona una fecha"* junto a un calendario desplegable **(DatePicker)**. Puedes hacer clic en las fechas para elegir la que desees.
Debajo, verás otro cuadro que dice* "Selecciona un color" *acompañado de un selector de color **(ColorPicker)**. 
Una vez que hayas elegido tu fecha y color, presiona el botón *"Confirmar"* para que pueda ser aplicado la fecha con su color elegido.

![Captura de pantalla (294)](https://github.com/Dayana-Sabando/ProyectPiker/assets/168872451/b467d73d-6155-4986-b242-dcdca6c8ba0c)
![Captura de pantalla (295)](https://github.com/Dayana-Sabando/ProyectPiker/assets/168872451/62ea8500-497a-4748-bce7-f1fe42cffe87)

Al presionar "Confirmar", la aplicación te mostrará dos mensajes:
-	La fecha que seleccionaste con el formato** "dd/MM/yyyy"** (por ejemplo, "Fecha    seleccionado: 11/06/2024").
-	El nombre del color que elegiste (por ejemplo, "Color seleccionado: Verde").
#####**Si no seleccionas una fecha o un color y presionas "Confirmar", la aplicación te recordará que debes elegir ambos para continuar.* *

![Captura de pantalla 2024-06-11 214536](https://github.com/Dayana-Sabando/ProyectPiker/assets/168872451/18dee6ef-3617-4daf-a899-648546d1a774)
![Captura de pantalla 2024-06-11 214602](https://github.com/Dayana-Sabando/ProyectPiker/assets/168872451/3b9b5558-d887-41df-ac7b-8444913f47dd)

####Componentes
-	**Importaciones:** Importamos las clases necesarias de JavaFX.
-	**Clase Principal**: Extiende Application y sobrescribe el método start.
-	**ColorPicker:** Creamos un ColorPicker que permite al usuario seleccionar un color.
-	**Label: **Creamos un Label para mostrar la información del color seleccionado.
-	**Evento:** Configuramos un evento para actualizar el Label cada vez que se selecciona un nuevo color en el ColorPicker.
-	**VBox:** Usamos un VBox para organizar el ColorPicker y el Label verticalmente.
-	**Escena:** Configuramos la escena y el escenario para mostrar la GUI.
###Conclusión:
Como se mencionó anteriormente esta aplicación brinda un pequeño espacio para divertirte eligiendo fechas y colores. Puedes probar con diferentes combinaciones y ver los resultados en los mensajes. Es una forma sencilla de aprender a usar los componentes DatePicker y ColorPicker de JavaFX.
