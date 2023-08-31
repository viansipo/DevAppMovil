# DevAppMovil
Curso de Desarrollo de Aplicaciones Móviles
Ejercicio práctico
Introducción a Android

Crear una aplicación utilizando Android Studio con las siguientes especificaciones:

    Nombre: AppPractica1
    Nombre del paquete: com.curso.android.app.practica.uno
    Versión mínima a soportar: Android 5
    Basa en un template del tipo: Vista Primaria con Detalle
C:\Users\Andres\AndroidStudioProjects\AppPractica1

Actividad 1
Crear un emulador del tipo Tablet, con un tamaño de pantalla de al menos 8”.

    Correr la aplicación en el emulador en orientación Portrait (vertical).
    Correr la aplicación en el emulador en orientación Landscape (horizontal).

Actividad 2
Crear un emulador del tipo Teléfono.

    Correr la aplicación en el emulador en orientación Portrait (vertical).
    Correr la aplicación en el emulador en orientación Landscape (horizontal).

Actividad 3
En ambos los casos:

    Indicar que configuración tiene cada emulador creado (versión de Android, tamaño de pantalla, memoria RAM).
    Realizar capturas de pantalla de cómo se ven todas las pantallas de la aplicación en cada configuración.

Tablet Nexus 9” API 34.
8,86” 2045 x 1536 xhdpi
Android API 34 x86_64
Memory and Storage: 
RAM 1536 MB
VM heap 192 MB
Internal Storage 2048 MB
SD card 512 MB

Capturas
         

Celular Pixel 2 5” API 30.
5” 1080 x 1920 420dpi
Android R 11.0 x86 
Memory and Storage: 
RAM 1536 MB
VM heap 228 MB
Internal Storage 2048 MB
SD card 512 MB

Capturas
      

Actividad 4

¿Qué diferencia observás en el funcionamiento de la aplicación en una tablet con orientación Landscape y un teléfono con orientación Portrait?
Los componentes de reubican distinto dependiendo del tamaño de pantalla, llegando incluso a no mostrar todo en una misma pantalla.

Actividad extra
    ¿En qué archivo está el nombre de tu aplicación? Probá cambiarlo y correr la aplicación nuevamente.
La dirección del nombre de la aplicación puede observarse a partir del archivo manifests. Aquí nos indica que es del tipo string, y para cambiarlo se encuentra en app / res / values / string.xml. En la línea donde dice <string name=“app_name”>Nombre</string>. Se procede a cambiarlo a “Unno”.

    ¿Y el ícono?
El ícono se encuentra en app / res / mipmap / ic_launcher. Aquí se encuentran los archivos según los distintos formatos de íconos de nuestra app.

