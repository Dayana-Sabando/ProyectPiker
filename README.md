# DatePicker y ColorPicker

##3 INTRODUCCIÓN

Este programa de JavaFX nos permite jugar con fechas y colores.  


### DESARROLLO

Conozcamos con más detalle cómo se usa este programa en conjuntos con los elementos que lo componen:


### UTILIDAD

En la parte superior, encontrarás un cuadro llamado *"Selecciona una fecha"* junto a un calendario desplegable **(DatePicker)**. Puedes hacer clic en las fechas para elegir la que desees.
Debajo, verás otro cuadro que dice* "Selecciona un color" *acompañado de un selector de color **(ColorPicker)**. 
Una vez que hayas elegido tu fecha y color, presiona el botón *"Confirmar"* para que pueda ser aplicado la fecha con su color elegido.


![Captura de pantalla (294)](https://github.com/Dayana-Sabando/ProyectPiker/assets/168872451/c8ab436d-2ff3-4a92-8c8a-47037ba7d8c2)



![Captura de pantalla (295)](https://github.com/Dayana-Sabando/ProyectPiker/assets/168872451/d5c8b300-a6b3-412d-81c1-94e2a251e3fd)


Al presionar "Confirmar", la aplicación te mostrará dos mensajes:
-	La fecha que seleccionaste con el formato** "dd/MM/yyyy"** (por ejemplo, "Fecha    seleccionado: 11/06/2024").
-	El nombre del color que elegiste (por ejemplo, "Color seleccionado: Verde").


  **Si no seleccionas una fecha o un color y presionas "Confirmar", la aplicación te recordará que debes elegir ambos para continuar.**
  

![Captura de pantalla 2024-06-11 214536](https://github.com/Dayana-Sabando/ProyectPiker/assets/168872451/18dee6ef-3617-4daf-a899-648546d1a774)


![Captura de pantalla 2024-06-11 220612](https://github.com/Dayana-Sabando/ProyectPiker/assets/168872451/048a211b-eca2-4faa-bf65-28f4bbb0b83c)



### COMPONENTES

-	**Importaciones:** Importamos las clases necesarias de JavaFX.
-	**Clase Principal**: Extiende Application y sobrescribe el método start.
-	**ColorPicker:** Creamos un ColorPicker que permite al usuario seleccionar un color.
-	**Label**:Creamos un Label para mostrar la información del color seleccionado.
-	**Evento:** Configuramos un evento para actualizar el Label cada vez que se selecciona un nuevo color en el ColorPicker.
-	**VBox:** Usamos un VBox para organizar el ColorPicker y el Label verticalmente.
-	**Escena:** Configuramos la escena y el escenario para mostrar la GUI.

![Captura de pantalla 2024-06-11 214602](https://github.com/Dayana-Sabando/ProyectPiker/assets/168872451/f3956bc1-6684-4301-93a3-6f821f451494)


### CONCLUSIÓN

Como se mencionó anteriormente esta aplicación brinda un pequeño espacio para divertirte eligiendo fechas y colores. Puedes probar con diferentes combinaciones y ver los resultados en los mensajes. Es una forma sencilla de aprender a usar los componentes DatePicker y ColorPicker de JavaFX.
