---
layout: post
title:  "Hello World - Android"
date:   2015-11-23 08:00:00 +0100
category: articulos
tags: android, hello, world
author: vicboma1
icon: /images/icons/android/android.png
edit: /_posts/articles/2015-11-22-android-hello-world.markdown
permalink: /2015/11/android-hello-world/
---



Desde kotlin.es hoy vamos a mostrar como configurar un proyecto Android con Kotlin basado en un "Hola Mundo".
La idea de esta pequeña entrada es acercar un poco más el alcance de Kotlin en los dispositivos móviles y ir iterando sobre pequeños proyectos poco a poco.

Lo primero que necesitamos es descargarnos la versión de [Android Studio](https://developer.android.com/sdk/index.html) de la web oficial.
Una vez instalado, hacemos doble click en el icono principal y se debe mostrar el popup de entrada.
Seleccionamos la primera opción para la creación de un nuevo proyecto.

![](/images/android/helloWorld/00.png)

Configuramos el nombre de la aplicación, su dominio y el nombre del paquete.

![](/images/android/helloWorld/01.png)

Seleccionamos la opción "Phone and Tablet" y especificamos la versión mínima de la SDK de Android. 
Abajo hay un pequeño enlace "help me choose" que nos permite visualizar un gráfico con el alcance de la SDK seleccionada.
Esto permite saber en que dispositivos funcionará nuestra aplicación.

![](/images/android/helloWorld/03.png)

Añadimos una actividad en blanco a nuesta aplicación móvil.

![](/images/android/helloWorld/04.png)

Directamente le damos a "Finish".

![](/images/android/helloWorld/05.png)

A partir de aquí, podremos ver como Android Studio autogenera el proyecto.

![](/images/android/helloWorld/06.png)

Añade el framework "Gradle" automáticamente.

![](/images/android/helloWorld/07.png)

Una vez generado el proyecto dentro de Android Studio, debemos tener algo parecido a esta imagen.

![](/images/android/helloWorld/08.png)

Ahora debemos descarganos los plugins de "Kotlin" y "Kotlin Extension for Android". 
Pulsamos el botón de "Preferencias" localizado en la barra superior del IDLE. Cuando salga la ventana modal, vamos al apartado "Plugins" y en la busqueda ponemos el token "Kotlin".
Encontraremos dos plugins, los seleccionamos y le damos a "Ok". 
Debemos de reiniciar Studio Studio para que cargue los plugins.

![](/images/android/helloWorld/09.png)

Abrimos el proyecto creado y seleccionamos la carpeta "java/es.kotlin.vicboma.holaMundo". Aquí tenemos un fichero llamado "MainActivity.java" que es la entrada de nuestra aplicación.
Lo seleccionamos y en la parte derecha visualizaremos su código en Java.
Ahora necesitaremos decirle al proyecto que queremos trabajar con Kotlin con este fichero de java. 
Usamos la "short-cut" siguiente tanto para Windows o para Mac y abrimos una pequeño contenedor de acciones.

![](/images/android/helloWorld/19.png)

Aqui escribimos "Convert Java File to Kotlin file" y le damos aceptar.

![](/images/android/helloWorld/10.png)

Pulsamos el botón de "Ok" y automáticamente se generará el código correspondiente de java a kotlin .

![](/images/android/helloWorld/11.png)

Desde este momento el fichero "MainActivity.java" ha pasado a ser un fichero kotlin llamado "MainActivity.kt".
Si nos fijamos la sintaxis que tenemos en dicho fichero es perteneciente a kotlin.
Ahora hay que decirle a Android Studio que nuestro projecto generado tiene que ser configurado con Kotlin.
Para ello, utilizamos la misma "short-cut" que antes y escribimos "Configure Project with Kotlin".  

![](/images/android/helloWorld/20.png)

Nos aparecera una pequeña ventana modal. Seleccionamos la primera opción y la versión más reciente del plugin.

![](/images/android/helloWorld/21.png)

Una vez tenemos todas las configuraciones del proyecto, solamente queda lanzar nuestra App "Hola Mundo" que Android Studio nos ha autogenerado.
Seleccionamos el botón "Run" que se localiza en la parte superior del IDLE. 
Nos aparecerá una ventana modal para seleccionar nuestro móvil o un dispositivo virtual. En nuestro caso vamos a lanzar la App por el emulador.
Pulsamos el icono de la parte inferior derecha en la opcion "Android virtual device".

![](/images/android/helloWorld/12.png)

Pulsamos el boton "Create virtual device" y seleccionamos uno cualquiera.

![](/images/android/helloWorld/13.png)

En el caso de clonar un dispositivo, visualizaremos esta imagen. Deseleccionamos todas las opciones que estan en el recuadro rojo.
Esto permitirá que el emulador vaya un poquito más rápido.
Pulsamos "next" para salir de la conifuración y otra vez "next" para terminar de editar el dispositivo virtual.

![](/images/android/helloWorld/14.png)



![](/images/android/helloWorld/15.png)
![](/images/android/helloWorld/16.png)
![](/images/android/helloWorld/17.png)
![](/images/android/helloWorld/18.png)
