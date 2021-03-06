## Generales {#generales}

### Roles y permisos {#roles-y-permisos}

Un rol es el conjunto de permisos que puede tener un usuario para utilizar la consola ADM. Es posible adicionar varios roles a un mismo usuario. Para crear un rol, ingrese a **Configuración &gt; Generales &gt; Roles** **y** **permisos**, luego haga clic en el menú desplegable de **Más opciones** y seleccione la opción **Nuevo**; se visualizará un formulario para completar el nombre del rol y una descripción.

En la pestaña **Permisos** seleccione las opciones que desea para este rol.

Haga clic en **Guardar**. Aparecerá un mensaje confirmando que se guardó correctamente la información del rol.

### Usuarios {#usuarios}

En la sección **Usuarios** se encuentran los usuarios creados desde la consola de ADM y los que están sincronizados con el directorio empresarial.

Para crear un usuario, ingrese a **Configuraciones &gt; Generales &gt; Usuarios,** vaya a **Más opciones**, abra la lista desplegable y seleccione la opción **Usuario**. Se visualizará un formulario para ingresar la información del usuario, una vez diligenciado el formulario haga clic en **Guardar**. Al guardar, se activarán dos pestañas más: **Grupos** y **Roles**.

Haga clic en la pestaña **Grupos** y realice la búsqueda del grupo al que desea asociar el usuario, luego haga clic en **Guardar**.

Haga clic en la pestaña **Roles** y seleccione el rol que desea asociar al usuario, una vez finalice, haga clic sobre el botón **Guardar**.

Para editar un usuario, haga clic sobre el usuario a modificar y seleccione la información que desea cambiar en cualquiera de las pestañas **General**, **Grupos** o **Roles**. Una vez modificada la información, guarde los cambios haciendo clic en **Actualizar**.

### Grupos {#grupos}

En la sección **Grupos** es posible crear y visualizar los grupos (creados manualmente o importados del directorio activo) que se usarán en las diferentes funcionalidades de la herramienta. En esta pestaña es posible configurar el grupo de energía (grupo de ubicación) obligatorio para crear las políticas de uso de energía.

Para crear un grupo, ingrese a **Configuración &gt; Generales &gt; Grupos.**

Al hacer clic en **Agregar** **nuevo árbol**, se visualizará un formulario con los campos **Nombre nodo raíz** y **Descripción**. Seleccione los roles para el grupo en el menú desplegable de la derecha.

Puede jerarquizar grupos y subgrupos configurando un _árbol de ubicación_, para ello se requiere activar la opción: **Predeterminar como árbol de ubicación.**

Haga clic en **Guardar**. Aparecerá un mensaje confirmando la creación del árbol.

Para modificar un grupo, haga clic sobre el nodo y se visualizarán tres iconos circulares. Haga clic sobre para activar el formulario que permite editar el grupo.

Luego de hacer las modificaciones pertinentes, haga clic en el botón **Guardar**. Aparecerá un mensaje en la parte inferior de la pantalla confirmando que el grupo se almacenó satisfactoriamente.

Para eliminar un grupo haga clic en .

Aparecerá un mensaje para confirmar que desea eliminar esa agrupación.

Finalmente aparecerá un mensaje en la parte inferior de la pantalla confirmando la eliminación del grupo.

Para adicionar un usuario a un grupo, es necesario activar la sección de usuarios en el botón . Haga clic en el botón **Agregar usuario** que aparece a la derecha de la pantalla.

Aparecerá una barra de búsqueda para encontrar el usuario que desea adicionar, selecciónelo y luego haga clic en el botón **Agregar**.

Finalmente aparecerá un mensaje en la parte inferior de la pantalla confirmando la adición del usuario al grupo.

![C:\Users\ivonne.gonzalez\AppData\Local\Microsoft\Windows\INetCache\Content.Word\800px-ADMMANUAL_064.png](C:\Users\jaime.chavarriaga\Documents\Test\export\assets\cusersivonnegonzalezappdatalo.png)

Para eliminar un usuario, haga clic sobre el icono que se encuentra en el recuadro de cada usuario; se visualizará un mensaje para verificar que desea eliminarlo; al hacer clic en **Aceptar** el usuario se eliminará del grupo.

Aparecerá un mensaje en la parte inferior de la pantalla confirmando la eliminación del usuario para ese grupo.

Para adicionar dispositivos a un grupo, es necesario activar la sección de dispositivos en el botón . Haga clic en el botón **Agregar Dispositivo** que aparece a la derecha de la pantalla.

Aparecerá una barra de búsqueda para encontrar el dispositivo que desea adicionar, selecciónelo y luego haga clic en el botón **Agregar**.

Aparecerá un mensaje en la parte inferior de la pantalla confirmando la correcta adición del dispositivo.

Para eliminar un dispositivo, haga clic sobre el icono que se encuentra en el recuadro de cada dispositivo, se visualizará un mensaje para verificar que desea borrarlo, haga clic en el botón **Aceptar** y el dispositivo se eliminará del grupo.

Aparecerá un mensaje en la parte inferior de la pantalla confirmando la correcta eliminación del dispositivo.

Puede configurar los permisos de control remoto sobre las máquinas de un grupo haciendo clic en el icono que aparece al lado del nombre del grupo. Luego haga clic en **Editar permisos para soporte remoto** al lado derecho de la pantalla. Aparecerá una ventana en donde se pueden seleccionar grupos o usuarios (ubicándolos con la barra de búsqueda) y definir para cada uno el rol que tendrá sobre estas máquinas (Administrador/Gestor).

### Licencias {#licencias}

En la sección **Licencias** se carga el archivo de licenciamiento de la consola para que funcione correctamente. Ver detalles en [6\. Licenciamiento](..\licenciamiento.md).

### Alertas {#alertas}

En esta sección podrá realizar la configuración de las notificaciones sobre eventos específicos. Podrá modificar las alertas existentes, teniendo en cuenta la siguiente información:

*   **Tipo de alerta:** Hace referencia al nivel de relevancia de la alerta (bajo, medio, alto o crítico).
*   **Estado**: Puede ser activo o inactivo. Solo se notifica sobre alguna novedad cuando el estado de la alerta es activo.
*   **Eliminar alertas**: Cuando la opción de eliminación de alertas está habilitada se puede acceder a la configuración de la periodicidad de eliminación de las alertas (última semana, último mes o último año).

### Integración empresarial {#integraci-n-empresarial}

La sección de integración empresarial se compone de los siguientes cuatro módulos:

### LDAP {#ldap}

La sincronización de ADM con el directorio activo de usuarios y grupos se realiza importando el directorio empresarial desde el módulo de LDAP.

Para ingresar la información de autenticación del LDAP, diligencie los campos que se encuentran en la pestaña **General** al lado derecho de la pantalla y haga clic en **Guardar**.

En la parte inferior de la pantalla aparecerá un mensaje confirmando que se ha guardado la información del directorio activo.

A continuación, debe definir la información por la cual se va a realizar el filtro. Los campos de la pestaña **Filtro** son obligatorios para la importación del directorio, también es necesario cumplir con los filtros de sintaxis del LDAP para sincronizar la información.

Tenga en cuenta que, dependiendo del tamaño de su pantalla, puede ser necesario desplazarse hacia abajo para visualizar todos los campos de la pestaña **Filtro**.

La sincronización del LDAP, se puede ejecutar de manera inmediata o programada con una periodicidad de ejecución diaria, semanal o mensual. Para hacer esta configuración vaya a la pestaña **Sincronización** al lado derecho de la pantalla, llene los campos y haga clic en **Guardar**.

### Servidor de correo {#servidor-de-correo}

En el módulo **Servidor de Correo** ingrese la información del correo electrónico remitente de las notificaciones que se enviarán a los usuarios desde la consola web, de acuerdo con las acciones que se realicen en la aplicación.

Complete los datos solicitados en el formulario y haga clic en **Actualizar**.

Opcionalmente puede enviar un correo de prueba para verificar que fue correcta la configuración.

Finalmente visualizará un mensaje confirmando la correcta configuración del servidor de correo electrónico.

### Servidor Proxy {#servidor-proxy}

En el módulo **Proxy** se debe ingresar la información del servidor proxy requerida para poder comunicarse con las estaciones de trabajo.

### CMDB {#cmdb}

En este módulo se ingresa la información para conectarse al servidor de Aranda CMDB y así poder gestionar los activos de la organización. La CMDB permite almacenar la información de los elementos de configuración de la infraestructura en su empresa (hardware y software) en un único repositorio de datos, lo cual se verá reflejado en reducción de costos, mayor eficiencia y mejora en los niveles de servicio respecto a sus recursos.

#### Prerrequisitos {#prerrequisitos}

*   Credenciales del usuario con permisos de creación de CI
*   URL de conexión a la CMDB
*   Mapeo de campos adicionales de ADM a CMDB. Esto es opcional, aunque debe confirmarse en la pantalla de cada categoría, aún si no hay nada que mapear.
*   Proyecto predeterminado dentro de la CMDB para los CI a crear.

#### Integración con Aranda CMDB Versión 8 {#integraci-n-con-aranda-cmdb-versi-n-8}

Dentro del módulo de **CMDB** elija la pestaña **Conexión con CMDB**. Allí podrá elegir el tipo de versión que desea configurar. Elija la versión 8.

Luego ingrese los siguientes datos: URL del servicio, usuario y contraseña. Ahora haga clic en el botón **Verificar conexión**.

Si los datos para la conexión son correctos, el botón cambiará a color verde con un mensaje confirmando la conexión exitosa; si los datos ingresados son incorrectos, el botón cambiará a color naranja con un mensaje informando la conexión fallida.

Una vez la conexión sea exitosa, guarde la información haciendo clic en el botón **Guardar**. Si se almacena correctamente aparecerá un mensaje informando que la información se guardó correctamente.

Si desea limpiar la conexión, haga clic en el botón **Limpiar conexión**. Se mostrará un mensaje solicitando confirmación de la acción.

Si confirma la solicitud de limpiar la conexión, se borrará la información y aparecerá un mensaje informando que la información de la conexión se borró exitosamente. Tenga en cuenta que al borrar la conexión ADM, se borra toda la información relacionada con CMDB, incluyendo los CI que ya se habían sincronizado, por lo tanto, si se integra por segunda vez con la misma CMDB se pueden duplicar los CI.

**Configuración de campos de mapeo**

En esta sección se pueden mapear los campos de los elementos de ADM a los campos de los ítems de configuración (CI) de la CMDB.

**Importante:** El mapeo de campos debe confirmarse por cada categoría de CI, aún si no hay campos adicionales para mapear.

![C:\Users\ivonne.gonzalez\AppData\Local\Microsoft\Windows\INetCache\Content.Word\800px-CMDB_Configuration_26.png](C:\Users\jaime.chavarriaga\Documents\Test\export\assets\cusersivonnegonzalezappdatalo.png)

Aquí usted podrá hacer el mapeo de los campos adicionales que se obtendrán de la CMDB.

Podrá seleccionar un campo de la CMDB con el campo adicional que se haya creado previamente.

Una vez se tengan los campos que se desean mapear, se procede a guardar la información. Si la información se guardó correctamente aparecerá un mensaje de satisfacción.

![C:\Users\ivonne.gonzalez\AppData\Local\Microsoft\Windows\INetCache\Content.Word\800px-CMDB_Configuration_29.png](C:\Users\jaime.chavarriaga\Documents\Test\export\assets\cusersivonnegonzalezappdatalo.png)

#### Integración con Aranda CMDB Versión 9 {#integraci-n-con-aranda-cmdb-versi-n-9}

En **Configuración &gt; Generales &gt; Integración empresarial &gt; CMDB**, elija la pestaña **Conexión con CMDB** y seleccione la versión 9\. Ingrese allí los siguientes datos: URL del servicio, usuario y contraseña. Haga clic en el botón **Verificar conexión**.

Si los datos para la conexión son correctos, el botón cambiará a color verde con un mensaje confirmando la conexión exitosa; si los datos ingresados son incorrectos, el botón cambiará a color naranja con un mensaje informando la conexión fallida.

Una vez la conexión sea exitosa, guarde la información haciendo clic en el botón **Guardar**. Si se almacena correctamente aparecerá un mensaje informando que la información se guardó correctamente.

Si desea limpiar la conexión, haga clic en el botón **Limpiar conexión**. Se mostrará un mensaje solicitando confirmación de la acción.

Si confirma la solicitud de limpiar la conexión, se borrará la información y aparecerá un mensaje informando que la información de la conexión se borró exitosamente. Tenga en cuenta que al borrar la conexión ADM, se borra toda la información relacionada con CMDB, incluyendo los CI que ya se habían sincronizado, por lo tanto, si se integra por segunda vez con la misma CMDB se pueden duplicar los CI.

**Configuración de campos de mapeo**

En esta sección se pueden mapear los campos de los elementos de ADM a los campos de los ítems de configuración (CI) de la CMDB.

**Importante:** El mapeo de campos debe confirmarse por cada categoría de CI, aún si no hay campos adicionales para mapear.

Puede seleccionar un modelo de CI para generar su configuración.

Una vez seleccionado un modelo de CI, aparecerán los posibles campos de CI para el mapeo.

Aquí usted podrá hacer el mapeo de los campos adicionales que se obtendrán de la CMDB.

![C:\Users\ivonne.gonzalez\AppData\Local\Microsoft\Windows\INetCache\Content.Word\800px-CMDB_Configuration_10.png](C:\Users\jaime.chavarriaga\Documents\Test\export\assets\cusersivonnegonzalezappdatalo.png)

Podrá seleccionar un campo de la CMDB con el campo adicional que se haya creado previamente.

Una vez se tengan los campos que se desean mapear, se procede a guardar la información, si la información se guarda correctamente aparecerá un mensaje de satisfacción.

**Nota:** Tenga en cuenta que, al alterar la conexión de la CMDB, desencadenará la eliminación de todos los datos de sincronización almacenados en el producto (ADM), esto no altera los datos previamente exportados y almacenados en la CMDB. De igual manera, al reconectar el producto (ADM) a una CMDB con datos previamente sincronizados resultará en problemas de integración por duplicidad de datos. Se recomienda eliminar todos los datos de sincronización exportados a la CMDB (procedimiento manual) por la anterior instancia de ADM.