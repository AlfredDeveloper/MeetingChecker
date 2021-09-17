# FAQ (Preguntas Frecuentes)
## PREGUNTAS
### El bot no funciona, ¿cómo puedo solucionarlo?
Intente deshabilitar su Antivirus (si usa Windows Defender, intente deshabilitarlo y verifique si funciona), el bot realiza tareas automatizadas en segundo plano para verificar sus reuniones y, a veces, algunos Antivirus bloquean la aplicación para que no revise las reuniones.
### El bot ya no actualiza las reuniones, ¿cómo puedo solucionarlo?
A veces necesita verificar sus credenciales de Google para continuar usando el bot, [verifíquelas](https://github.com/AlfredDeveloper/MeetingChecker/blob/main/FAQ/FAQ_ES.md#preferencias), vaya al menú de configuración y haga clic en “Ingresar cuenta”. Se abrirá una nueva ventana, inicie sesión en su cuenta para verificarla después de que termine de cerrar la ventana.
### ¿Qué es un Discord MD?
Es un mensaje que el bot le envía a través de Discord, MD significa (Mensaje directo)
### ¿Puedo iniciar sesión en más de una cuenta?
Actualmente, esa función no está disponible, solo puede iniciar sesión en una cuenta al mismo tiempo.
### ¿Qué es un bot?
Un bot es un programa de software que realiza tareas automatizadas, repetitivas o predefinidas; en este caso, comprueba si ha comenzado una reunión.
### ¿Cómo obtengo mi token del bot de Discord y mi ID del usuario de Discord para habilitar Discord MD?
#### Token del bot de Discord
1. Asegúrese de haber iniciado sesión en el [sitio web de Discord.](https://discord.com/)
2. Vaya al [Portal para desarrolladores de Discord](https://discord.com/developers/applications)
3. Haga clic en el botón “New Application”.
4. Agregue un nombre y haga clic en “create”.
5. Vaya a la pestaña “Bot”.
6. Haga clic en “Add Bot” y “Yes, Do it!”.
7. Debajo de “Click to Reveal Token”, haga clic en “Copy”.
8. Péguelo en el campo “Token del bot de Discord” del menú Preferencias.

**Para personalizar el bot, verifique la documentación de Discord.**
**Necesitas compartir un servidor con el bot.**
##### Agregar al servidor
1. Crea un servidor de Discord. **Para crear un servidor de Discord, consulte la documentación de Discord.**
2. Vaya al [Portal para desarrolladores de Discord](https://discord.com/developers/applications)
3. Haga clic en el bot que creó antes.
4. Vaya a la pestaña “OAuth2”.
5. Desplácese hasta la sección “SCOPES” y marque la opción “bot” y haga clic en el botón “copy” debajo de las opciones.
6. Pegue el enlace en la otra pestaña para ir al sitio.
7. Seleccione el servidor donde desea agregar el bot.
8. Haga clic en “Autorizar”.
9. Resuelva el hCaptcha.
#### ID de usuario de Discord
1. Abra Discord e inicie sesión en su cuenta.
2. Vaya a Ajustes de usuario > Avanzado (sección Ajustes de aplicación) > Modo de desarrollador y habilítelo.
3. En el servidor de Discord que creó, haga clic en el icono Usuarios en la esquina superior derecha.
4. Haga clic con el botón derecho en su nombre de usuario de Discord y seleccione “Copiar ID”
5. Péguelo en el campo “ID de usuario de Discord” del menú Preferencias.
## TABLERO
### Widget de Actualización
<img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/UpdateWidget_1_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/UpdateWidget_2_ES.png?raw=true" width="205" height="95">

Esto verifica si hay una nueva actualización disponible para la aplicación. Si hay una disponible (imagen n. ° 2), puede hacer clic en el widget para abrir la página de la aplicación en Microsoft Store y actualizarla.
### Widget de estado del bot
<img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/BotStatusWidget_1_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/BotStatusWidget_2_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/BotStatusWidget_3_ES.png?raw=true" width="205" height="95">

Esto le indica si el Bot está en línea o fuera de línea, para iniciar el bot, haga clic sobre el widget.
Después de hacer clic en el botón en el estado en línea, tendrá un retraso de 1 segundo **(imagen n. ° 3)** antes de hacer clic en el botón nuevamente.

**Puede configurar las reuniones en el menú “Establecer”**
### Widget de la próxima comprobación
<img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/TimeForNextCheckWidget_1_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/TimeForNextCheckWidget_2_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/TimeForNextCheckWidget_3_ES.png?raw=true" width="205" height="95">

Esto le indica cuánto tiempo queda hasta que el bot compruebe nuevamente si se inició alguna reunión, se inicia/detiene automáticamente cuando se hace clic en el estado del bot. Si hace clic en un botón de menú, la cuenta atrás no estará disponible hasta que haga clic en el widget de estado del bot para detener y volver a iniciar el bot.

**Puede configurar el tiempo en el menú “Establecer” (mínimo 60 segundos)**
### Widget del Historial de reuniones
<img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/LastMeetingsEnabledWidget_1_ES.png?raw=true" width="340" height="318">

Muestra un historial con la última actividad de las reuniones (qué reuniones se habilitaron/deshabilitaron y la hora/día)

✔ ⇨ Habilitado
“X” ⇨ Deshabilitado

**Haga clic en el círculo con la “✔” o “X” para abrir la reunión en su navegador predeterminado**

**Puede configurar las reuniones en el menú “Establecer”**

## REUNIONES

### Estado de la reunión
<img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Meetings_1_ES.png?raw=true" width="137" height="205"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Meetings_2_ES.png?raw=true" width="137" height="205">

La fila de nombre muestra los nombres de las reuniones que configuró en la opción del menú de Establecer. **(Imagen 2)**

La fila de estado muestra si la reunión que está en la fila del nombre está habilitada o deshabilitada. **(Imagen 1)**
Verde ⇨ Habilitado
Rojo ⇨ Deshabilitado
**Haga clic en el círculo verde / rojo para abrir la reunión en su navegador predeterminado**

## Establecer
Aquí puede Establecer sus reuniones.

<img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Setup_1_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Setup_2_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Setup_3_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Setup_4_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Setup_5_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Setup_6_ES.png?raw=true" width="205" height="95"> 

* En la fila “Nombre de la reunión”, escriba el nombre de la reunión **(puede ser cualquier nombre).**
* En la fila “Código de reunión”, escribe tu código de reunión **(Puedes encontrarlo en Google Classroom debajo del nombre de la clase en “Enlace de Meet”) Si el enlace es https://meet.google.com/lookup/dkuy9slrpr escribe dkuy9slrpr en la fila del código de la reunión.**
* En la fila “Color” puedes elegir cualquier color **(Este color aparecerá en el lado izquierdo del mensaje de Discord y será el color del [Widget de Historial de reuniones](https://github.com/AlfredDeveloper/MeetingChecker/blob/main/FAQ/FAQ_ES.md#widget-del-historial-de-reuniones)).**
* Si hace clic en el botón Eliminar, eliminará la reunión de su fila.
* Para agregar otra reunión, haga clic en el botón “Añadir reunión”.
* Para guardar todos los cambios, haga clic en el botón “Guardar”, cierre la aplicación y vuelva a iniciarla.

## Preferencias
Aquí puede cambiar las preferencias de la aplicación

<img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Settings_1_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Settings_2_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Settings_3_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Settings_4_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Settings_5_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Settings_6_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Settings_7_ES.png?raw=true" width="205" height="95"> <img src="https://github.com/SpaceGamerFury/MeetingChecker/blob/main/FAQ/FAQ_IMAGES/Settings_8_ES.png?raw=true" width="205" height="95"> 

* En la sección “Tiempo entre comprobaciones (segundos)”, escriba los segundos que desea que el bot espere hasta que vuelva a comprobar si comenzó alguna reunión, **mínimo: 60 segundos.**
* En la sección “Idioma” puede elegir qué idioma desea ver en la aplicación y el DM de discord **actualmente solo se admiten inglés y español.**
* En la sección “Minimizar en bandeja del sistema”, puede elegir si desea minimizar la aplicación en la barra de tareas **(cuando está deshabilitada)** o en la bandeja del sistema **(cuando está habilitada, si desea abrir la aplicación nuevamente, haga clic en el icono de la bandeja del sistema)** haga clic en el cuadro blanco para habilitar/deshabilitar la opción.
* En la sección “Discord MD” puede elegir si desea permitir que el bot le envíe un mensaje a través de Discord cuando comience una reunión **(cuando esté habilitado)** o solo mostrarlo en la opción de menú Inicio y Reuniones **(Cuando está deshabilitado)** haga clic en el cuadro blanco para habilitar / deshabilitar la opción.
* En la sección “Token del bot de Discord”, escribe el bot token que obtienes [Aquí.](https://github.com/AlfredDeveloper/MeetingChecker/blob/main/FAQ/FAQ_ES.md#token-del-bot-de-discord)
* En la sección “ID de usuario de Discord”, escribe el token de bot que obtienes [Aquí.](https://github.com/AlfredDeveloper/MeetingChecker/blob/main/FAQ/FAQ_ES.md#id-de-usuario-de-discord)
* Para guardar todos los cambios, haga clic en “¡Guardar preferencias!”. Y cierre la aplicación y vuelva a iniciarla.
* Para iniciar sesión en su cuenta de Google, haga clic en el botón “Ingresar cuenta” y se abrirá una ventana de chromium para que pueda iniciar sesión o verificar su contraseña. 
