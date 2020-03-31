# Configuración

Con esta conﬁguración va a poder acceder a la consola.

# Repserver y Conserver

Al momento de instalar el Conserver todos los archivos permanecen en la ruta C:\Program Files (x86)\Aranda\Conserver, allí se encuentra el archivo **Aranda.Conserver.Windows.Service.exe.conﬁg** el cual se debe conﬁgurar de la siguiente manera para que se comunique con el Repserver:

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\conf_1.png)

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\conf_2.png)


Iniciar el servicio Aranda Conserver Service, que permite la comunicación con el Repserver.

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\conf_3.png)


# Conserver

En la consola Aranda Device Management, ingresar a **Conﬁguración > ADM > Comunicaciones**, se visualizará el árbol de comunicaciones donde está el nodo del Repserver, al hacer clic sobre el nodo se despliegan todos los Conserver que se están comunicando, La primera vez que se visualiza el Conserver se debe realizar la conﬁguración de los campos puerto Wake on LAN y la ruta almacenamiento de archivos.

La conﬁguración del puerto depende de la administración, pero normalmente es el número 7, la ruta de almacenamiento de archivos corresponde a la ubicación temporal de almacenamiento.

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\conf_4.png)


# Cargar licencias

Todos los productos de Aranda Software requieren una licencia para su funcionamiento, por tal razón la primera vez que ingrese a **Aranda Device Managements** se solicitará la licencia correspondiente.

En la pestaña Licencias deberá cargar el archivo de licenciamiento de la consola para que funcione correctamente. Ingrese a la opción Archivos y haga clic en Nuevo.

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\conf_5.png)


# Pérﬁl de Agente

El perﬁl es utilizado al momento de la instalación del agente; las funcionalidades principales son las tareas que realizará dependiendo de la parametrización, por ejemplo: Programación de inventarios, sincronización de datos, inventarios, licenciamiento, distribución, actualizaciones, energía y control remoto.

A continuación, el paso a paso de la conﬁguración del perﬁl del agente. Ingresar a **Aranda Device Management >Perﬁl Agente**, despliegue la lista Más opciones y seleccione Perﬁl agente.

![consola](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\conf_6.png)


