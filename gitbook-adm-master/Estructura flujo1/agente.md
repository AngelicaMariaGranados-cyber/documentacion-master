# Agente

Con esta conﬁguración va a poder acceder a la consola.

# Instalación manual

El Agente ADM Aranda.Agent.9, mediante este se instala los servicios requeridos para el Agente en Windows. Para realizar la instalación de manera des-atendida y automática del agente, la consola Web de ADM cuenta con la funcionalidad de distribución de agente.

En los casos en los cuales se desee instalar el agente de manera manual se puede hacer uso de la interfaz de usuario. A continuación, se muestra un paso a paso de la instalación manual del Agente. Haga clic sobre el instalador Aranda Agent.


![agente](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_1.png)

A continuación, se visualiza un mensaje informando que se va a instalar Aranda Agent.

![agente](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_2.png)

Si se tiene un archivo de configuración seleccionar Si e ingresar la ruta, de lo contrario seleccionar No y hacer clic en siguiente.

![agente](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_3.png)

Al ingresar el identificador del perfil en 0, significa que va a descargar el perfil por defecto que esté configurado, ingresar la dirección de Conserver (Se encuentra en el módulo **Configuración > Aranda Device Management > Comunicaciones > Nodo del Conserver)**.

![agente](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_4.png)

Ingresar el nombre de usuario y la organización donde se instalará el agente.

![agente](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_5.png)

Seleccionar el tipo de instalación que desea realizar (Completa o Personalizada) y hacer clic en siguiente.

![agente](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_6.png)

A continuación, inicia la instalación del agente.

![agente](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_7.png)

Una vez finalizada la instalación del agente, hacer clic en Finalizar.

![agente](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_8.png)

# Creación semilla

Es cuando se instala el agente en una máquina y la máquina se clona en muchas mas.


# Resolución de conﬂictos

Desde la versión 9.5 la consola de administración de ADM permite visualizar y gestionar fácilmente los potenciales problemas de identificación que ocurren a los dispositivos. Estos problemas se conocen como conflictos y son mostrados en la hoja de vida de los dispositivos para que el usuario tome una decisión sobre cada uno de ellos. De esta manera se evitan más fácilmente inconsistencias como la suplantación de máquinas y la duplicidad de registros. La suplantación ocurre cuando muchos dispositivos se ven como uno solo en la consola, como efecto de clonación de equipos que ya tienen instalado el agente, principalmente. La duplicidad ocurre cuando una máquina tiene mas de un registro asociado en la consola, normalmente es debido al ingreso de máquinas que fueron formateadas después de tener agente instalado.

Todo agente instalado en un dispositivo realiza periódicamente una operación de registro con su servidor, en donde se envían tres valores: una marca de hardware, la identificación asignada por el servidor y un token dinámico. Si alguno de estos valores no coincide con el que el servidor espera se bloquean permanentemente las solicitudes de este equipo y se muestra un conflicto en la hoja de vida respectiva en consola. El usuario debe entonces resolver el conflicto eligiendo una acción a tomar cuando la solicitud de registro sospechosa vuelva a presentarse. Cuando se presente la siguiente solicitud el conflicto quedará resuelto.

Todas las máquinas que presenten conflictos serán marcadas y podrán ser filtradas en el listado para que el usuario pueda gestionarlas fácilmente.

![conflictos](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_9.png)

Al entrar a la hoja de vida el usuario verá una lista con todos los conflictos detectados para una máquina, para cada conflicto se indica el tipo y se muestra un selector para la acción a tomar. Los conflictos pueden ser de tres tipos: Hardware duplicado, Hardware inconsistente e identificador duplicado. La pestaña de ayuda en este pantalla explica cada uno de ellos y explica cómo deben resolverse.

![conflictos](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_10.png)

Las aciones a tomar son Asociar dispositivo, Crear dispositivo o aplazar la decisión dejándo la acción Pendiente. El usuario podría también Borrar el conflicto si considera que ya no volverá a ocurrir.

![conflictos](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_11.png)

Es posible que el usuario sepa de antemano qué un tipo específico de conflicto se presentará muy frecuentemente para una máquina. Por ejemplo, si una máquina virtual fue clonada muchas veces después de tener el agente instalado y se pretende ingresar todos los clones al sistema (generando conflictos de identificador duplicado), o si una máquina física es formateada y regingresada cada semana para ser usada en campañas diferentes (generando conflictos de hardware duplicado). En estos casos los conflictos son predecibles y el usuario puede configurar una acción automática en la hoja de vida.

![conflictos](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_12.png)


# Descubrimiento

El descubrimiento de dispositivos se realiza solo la primera vez que desea instalar el agente a un dispositivo, este se puede realizar por diferentes medios (IP, DNS, ICMP, NetBIOS SMB, WMI, Dominio). A continuación, el paso a paso de la configuración del descubrimiento de dispositivos.

Ingresar a **Configuración > Aranda Device Management > Comunicaciones**, seleccionar el nodo del Conserver y hacer clic en la pestaña Descubrimiento, se visualizará el formulario para realizar el descubrimiento, ingresar la información solicitada.

Ingresar la información en el programador para que ejecute, de lo contrario no se va realizar esta acción. Adicionalmente, ingresar la información de periodicidad para que se realice en un tiempo determinado, sin necesidad de configurar nuevamente.

![descubrimiento](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_13.png)


# Distribución de Agente

Para crear el proyecto de distribución de agente, hacer clic en Nuevo y seleccionar Agente.

![distribucion](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_14.png)

# Políticas de Dominio

Las políticas definen el comportamiento de un dispositivo con respecto al consumo de energía, restricciones, puertos de entrada, aplicaciones permitidas y otros aspectos. Una política se crea, configurando las diferentes secciones, luego se aplica a los dispositivos apropiados. Un dispositivo puede tener a lo sumo una política aplicada al tiempo, por tal motivo al aplicarla se borra el efecto de la anterior en el dispositivo.

En el menú principal hacer clic en Políticas. Desplegar la lista Más opciones, haga clic en Política e ingresar la información solicitada.

![politicas](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_15.png)

En la pantalla de creación de una nueva política, podrá realizar la configuración de restricciones, aplicaciones y energía.

![politicas](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_16.png)


# Alertas

Las alertas son mensajes generados por la consola en respuesta a situaciones especiales que ben ser atendidas por el administrador. Las alertas se relacionan a dispositivos, licencias o cualqueir iotro concepto del producto. Las alertas tienen diferentes estados: creada, revisada y cerrada. Toda alerta ingresa al listado en estado creada, el usuario de consola es el encargado de cambiar su estado y adjuntar los comentarios que se requieran dependiendo del manejo que se le esté dando.

![alertas](img src=C:\Users\angelica.granados\Documents\GitHub\documentacion-master\gitbook-adm-master\Estructura flujo1\imagenes\instalacion\agen_17.png)