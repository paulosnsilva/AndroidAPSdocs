Seguimiento remoto
**************************************************

.. image:: ../images/KidsMonitoring.png
   :alt: Supervisión de los niños
  
AndroidAPS ofrece varias opciones para el monitorización remota de los parámetros de niños y también permite enviar comandos remotos. Por supuesto, también puedes usar la monitorización remota para seguir los datos de tu pareja o amigo.

Funciones
==================================================
La bomba de insulina de un niño es controlado por el teléfono móvil del niño usando AndroidAPS.
* Los padres pueden seguir de forma remota todos los datos relevantes, tales como los niveles de glucosa, carbohidratos a bordo, insulina a bordo, etc. utilizando la aplicación **NSClient** en su teléfono. Los valores deben ser los mismos en AndroidAPS y NSClient.
* Los padres pueden visualizar las alarmas usando la aplicación **xDrip en modo seguidor** en su teléfono.
* Control remoto de AndroidAPS usando `Comandos SMS <../ Niños / SMS-Commands.html>`_ protegido por autenticación de dos pasos.
* Remote control through NSClient app is only recommended if your synchronization is working well (ie. you don’t see unwanted data changes like self modification of TT, TBR etc) see `release notes for Version 2.8.1.1 <https://androidaps.readthedocs.io/en/latest/EN/Installing-AndroidAPS/Releasenotes.html#important-hints>`_ for further details.

Herramientas y aplicaciones para monitorización remota
--------------------------------------------------
* `Nightscout <http://www.nightscout.info/>`_ en el navegador web (principalmente para visualización de datos)
* Aplicación NSClient
*	Dexcom seguidor si está usando la aplicación original Dexcom (sólo valores BG)
* `xDrip <../Configuration/xdrip.html>`_ en modo seguidor (principalmente valores de BG y **alarmas**)
*	`Sugarmate <https://sugarmate.io/>`_ o `Spike <https://spike-app.com/>`_ en iOS (principalmente valores de glucosa en sangre y **alarmas**)

Puntos a considerar
==================================================
* Establecer los `factores de tratamiento correctos <../Getting-Started/FAQ.html#how-to-begin>`_ (tasa basal, DIA, ISF...) es difícil para los niños, especialmente cuando las hormonas de crecimiento están involucradas. 
* La configuración debe ser la misma en AndroidAPS y NSClient.
* Considere la diferencia de tiempo entre el maestro y el seguidor debido al tiempo de subida y descarga, así como el hecho de que el teléfono maestro de AAPS sólo subirá después de la ejecución del bucle.
* Por lo tanto, tómese su tiempo para establecer los parámetros correctamente y probarlos en la vida real con su niño junto a usted, antes de comenzar el control y tratamiento remoto. Las vacaciones escolares pueden ser un buen momento para ello.
* Cuál es su plan de emergencia cuando el control remoto no funciona (por ejemplo, problemas de conectividad). problemas de red)?
* La monitorización y el tratamiento a distancia pueden ser realmente útiles en la guardería y colegio. Pero asegúrate de que los profesores y educadores estén al tanto del plan de tratamiento de tu hijo. Ejemplos de planes de atención se pueden encontrar en los archivos de la sección de AndroidAPS usuarios <https://www.facebook.com/groups/AndroidAPSUsers/files/>`_ en Facebook.
