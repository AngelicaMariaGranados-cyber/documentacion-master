# Instalación

ADM cuenta en total con cuatro instaladores, explicados a continuación:  
                                  
![Imagen 1][1]  ![Imagen 2][2] ![Imagen 3][3]  ![Imagen 4][4]

 [1]: img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\assets\instalacion\consola1.png
 [2]: img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\assets\instalacion\agente1.png 
 [3]: img src="C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\assets\instalacion\conserver1.png
 [4]: img src="C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\assets\instalacion\visor1.png


# Consola

El instalador de la **consola web** de aranda Device Management.Web. Installer instala los sitios de la consola y el Repserver, adicionalmente crea los servicios de los Crunchers, License, Scheduler, Mailer, Worker que se usan en la aplicación. A continuación, el paso a paso de la instalación. Hacer clic sobre el instalador, se visualiza la siguiente advertencia.

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_1.png)

Ingresar el nombre de usuario y la organización donde se está instalando la aplicación.

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_2.png)


Se visualizará el siguiente formulario:

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_3.png)


Ingresar los datos de autenticación de base de datos. Existen dos formas de autenticación: Windows y SQL, ingresar el nombre de la base de datos y hacer clic en Siguiente.

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_4.png)

Existen dos instalaciones (Completa y personalizada), seleccionar instalación Completa y hacer clic en siguiente.

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_5.png)


Hacer clic en Instalar.

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_6.png)


# Agente

Para realizar la instalación del **Agente** de ADM por línea de comando se puede ejecutar la siguiente instrucción de

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_7.png)
sde el command promt de Windows.

<span style="color:#000; font-family: 'courrier'; font-size: 4em;">Agent.Windows.x86_x64.9.3.1803.0108 /S /V"/norestart /qn AGENT_SERVER_ADDRESS=http://localhost/Conserver AGENT_PROFILE_ID=0"</span>

# Conserver

**Aranda.Conserver.Installer** el cual instala el servicio del Conserver. Se deberá instalar uno por cada segmento de red. A continuación, el paso a paso de la instalación del Conserver. Al hacer clic sobre el instalador, se visualiza la siguiente advertencia.

![conserver](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_1.png)

En la siguiente pantalla se visualiza un mensaje informando que se va a instalar Aranda Conserver Service, hacer clic en Siguiente para continuar.

![conserver](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_2.png)


Seleccione el tipo de instalación Completa y haga clic en Siguiente.

![conserver](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_3.png)

Luego, hacer clic en Instalar.

![conserver](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_4.png)

Cuando finalice el proceso de instalación, hacer clic en Finalizar.

![conserver](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\cons_5.png)
