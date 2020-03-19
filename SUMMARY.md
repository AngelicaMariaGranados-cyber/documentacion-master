# Summary

* [ADM 9.5 - Manual de Uso e Instalación](<AngelicaMariaGranados-cyber/documentacion/master/docsAranda/index.html>)

* [Introducción](introduccion.md)
* [Requisitos de hardware y software](gitbook-adm-master/requisitos_de_hardware_y_software/README.md/)
  * [Puertos y permisos requeridos](gitbook-adm-master/requisitos_de_hardware_y_software/puertos_y_permisos_requeridos.md)
  * [Permisos adicionales](requisitos_de_hardware_y_software/permisos_adicionales.md)
  * [Exclusión en antivirus](requisitos_de_hardware_y_software/exclusion_en_antivirus.md)
  * [Servicio de licenciamiento](requisitos_de_hardware_y_software/servicio_de_licenciamiento.md)
* [Funcionalidades y componentes](funcionalidades_y_componentes.md)
* [Obtención y procesamiento de inventarios](obtencion_y_procesamiento_de_inventarios.md)
* [Instalación](instalacion\README.md)
  * [Instalación de la consola ADM](instalacion/instalacion_de_la_consola_adm.md)
  * [Instalación del Conserver](instalacion/instalacion_del_conserver.md)
  * [Instalación del Agente](instalacion/instalacion_del_agente.md)
  * [Instalación del visor de soporte remoto](instalacion\instalacion_del_visor_de_soporte_remoto.md)
* [Licenciamiento](licenciamiento.md)
* [Configuración ](configuracion\README.md)
  * [Generales](configuracion/generales.md)
  * [ADM ](configuracion\adm.md)
  * [Credenciales](configuracion/credenciales.md)
  * [Comunicaciones](configuracion/comunicaciones.md)
  * [Perfil Agente](configuracion/perfil_agente.md)
  * [Catálogo de aplicaciones](configuracion\catalogo_de_aplicaciones.md)
  * [Paquetes](configuracion/paquetes.md)
  * [Medición](configuracion/medicion.md)
  * [Campos adicionales](configuracion\campos_adicionales.md)
* [Inventario](inventario.md)
* [Dispositivos](dispositivos\README.md)
  * [Acciones](dispositivos\acciones.md)
  * [Pantalla de detalles del dispositivo](dispositivos\pantalla_de_detalles_del_dispositivo.md)
* [Hardware](hardware.md)
* [Software](software.md)
* [Catálogo](catalogo\README.md)
  * [Mini DashBoard ](catalogo\mini_dashboard.md)
  * [Creación de un ítem del catálogo de software](catalogo\creacion_de_un_item_del_catalogo_de_software.md)
  * [Pantalla de detalles de software](catalogo\pantalla_de_detalles_de_software.md)
  * [Acciones](catalogo\acciones.md)
  * [Obtener inventario](catalogo\obtener_inventario.md)
  * [Restricción de software](catalogo\restriccion_de_software.md)
  * [Desinstalar software](catalogo\desinstalar_software.md)
  * [Ejecutar comando](catalogo\ejecutar_comando.md)
  * [Reiniciar dispositivo](catalogo\reiniciar_dispositivo.md)
  * [Más acciones](catalogo\mas_acciones.md)
  * [Tipos de filtro](catalogo\tipos_de_filtro.md)
* [Actualizaciones \(distribución\)](actualizaciones_distribucion\README.md)
  * [Configuración ](actualizaciones_distribucion\configuracion.md)
  * [Distribución manual ](actualizaciones_distribucion\distribucion_manual.md)
* [Distribución \(de software\)](distribucion_de_software\README.md)
  * [Agente ](distribucion_de_software\agente.md)
  * [Software ](distribucion_de_software\software.md)
* [Políticas ](politicas.md)
* [Configuración de energía](configuracion_de_energia.md)
* [Creación de política](creacion_de_politica\README.md)
  * [Restricciones](creacion_de_politica\restricciones.md)
  * [Aplicaciones](creacion_de_politica\aplicaciones.md)
  * [Energía](creacion_de_politica\energia.md)
* [Reglas](reglas.md)
* [ Reportes ](reportes.md)
* [ Alertas](alertas.md)



# Actualizaciones (distribución) 

En **Inicio &gt; Software &gt; Actualizaciones** podrá configurar la distribución de actualizaciones. De esta manera ayuda a prevenir ataques externos al mantener actualizados sus equipos con los últimos parches y versiones liberadas por los fabricantes. Igualmente permite eliminar los riesgos y vulnerabilidades de seguridad en el sistema al proteger la infraestructura y mantener actualizadas todas las estaciones de trabajo de la organización de manera centralizada y permanente. Realiza programación automática para descarga de actualizaciones de software; instalación programada o inmediata de actualizaciones y notificación permanente sobre actualizaciones o parches que generen riesgo en la seguridad del sistema operativo de los servidores y estaciones de trabajo.

En la parte izquierda de esta pantalla están los filtros con los cuales podrá ubicar fácilmente las actualizaciones por criterios como estado, instalación, severidad, actualización (si es un parche individual o un paquete), tipo de parche y aplicación. En la lista de actualizaciones se observa un resumen de cada actualización, la fecha de publicación y la fecha de descarga; podrá seleccionar una o varias actualizaciones con el fin de realizar acciones masivas sobre ellas. A la derecha se encuentra el resumen detallado de la o las actualizaciones junto con las acciones disponibles para realizar sobre ellas.

# Catálogo 

El catálogo de software contiene toda la información recopilada del inventario de software instalado en los dispositivos. El software se clasifica automáticamente de acuerdo a las reglas predefinidas por el catálogo de software de ADM. La asociación de licencias y el conteo del uso del software se hace por medio de estas agrupaciones o ítems del catálogo de software.

El usuario podrá crear sus propias reglas de acuerdo a las necesidades de clasificación de su organización.

*   Grupos por nombre del software: Reglas que definen la agrupación de todo el software según su nombre. Por ejemplo: Microsoft Visual Studio*. Todo el software que cumpla con el criterio definido se considera como parte de ese grupo, Microsoft Visual Studio 2017, Microsoft Visual Studio 2015, Microsoft Visual Studio Premium 2012.
*   Grupos por ejecutables: Reglas que definen la agrupación de todo el software basado en los archivos ejecutables identificados en el inventario. Por ejemplo: Office = winword.exe, Excel.exe, powerpnt.exe Todo el software que contenga los archivos ejecutables definidos se considera como parte de ese grupo.

**Nota:** En el listado del catálogo, se muestra tanto el software inventariado como el no inventariado (creado manualmente). Solo se puede agrupar el software inventariado. Es posible ordenar el software por: nombre, fabricante, cantidad de instalaciones y uso.

En la pantalla del catálogo de software encontrará los siguientes elementos:

# Configuración 

En esta sección encontrará al costado izquierdo un menú que se compone de dos grupos de módulos: **Generales** y **ADM**.

# Creación de política {#creaci-n-de-pol-tica}

En **Inicio &gt; Políticas**, despliegue la lista **Más opciones**, haga clic en **Política** e ingrese la información solicitada.

En la pantalla de creación de una nueva política, podrá realizar la configuración de restricciones, aplicaciones y energía.

# Dispositivos 

Esta solución se especializa en la gestión integral de inventarios actualizados de hardware y software, permite tomar el control remoto de sus estaciones de trabajo minimizando los tiempos de desplazamiento de los especialistas de soporte. Contribuye a reducir la pérdida de hardware, mediante el control permanente del uso de los recursos; con un único agente instalado en cada estación de trabajo, tendrá información relevante de sus activos.

Usted podrá acceder a esta opción a través del menú **Inicio &gt; Inventario &gt; Dispositivos**. En la parte izquierda de la pantalla están los filtros con los cuales podrá ubicar fácilmente los dispositivos por criterios como tipo, estado, sistema operativo, fabricante y versión de agente. En la lista de dispositivos se observa un resumen de cada dispositivo, la fecha del último inventario y el estado del dispositivo; podrá seleccionar uno o varios dispositivos con el fin de realizar acciones masivas sobre ellos. A la derecha el detalle en resumen de el o los dispositivos junto con las acciones disponibles para realizar sobre estos.

# Distribución (de software) 

Aquí puede realizar la instalación del software requerido en su organización de forma desatendida y sin interferir en la productividad de los usuarios. Adicionalmente podrá programar la distribución e instalación automática de software y archivos en forma centralizada mediante la configuración de paquetes estandarizados y autoajustables. La solución organiza y planifica las tareas de instalación de software con la generación de proyectos, la definición de paquetes de instalación, la creación y acceso permanente a un catálogo de software para descargar los instaladores autorizados. Así mismo, efectúa tareas de administración de infraestructura IT tales como: Implementación de Aplicaciones Nuevas, Transferencia, Ejecución de Archivos y Desinstalación de Software No Autorizado.

Podrá acceder a esta opción a través del menú **Inicio &gt; Software &gt; Distribución**. En la parte izquierda de la pantalla están los filtros con los cuales podrá ubicar fácilmente los proyectos por criterios. En la lista de proyectos se observa un resumen de cada proyecto, la fecha de creación y la fecha de última ejecución; podrá seleccionar uno o varios proyectos con el fin de realizar acciones masivas sobre ellos. A la derecha el resumen en detalle de el o los proyectos junto con las acciones disponibles para realizar.

# Instalación 

ADM cuenta en total con cuatro instaladores, explicados a continuación:



# Requisitos de hardware y software 
Se recomienda la siguiente configuración para administrar entre 1 y 2500 dispositivos.

---

## Servidor de Aplicaciones de Aranda

|  |  |
| :-- | :-- |
| **Sistema Operativo** | Windows Server 2012 R2, Standard Edition, x64, con las últimas versiones de Service Pack instaladas. |
| **Memoria RAM** | 6 GB o Superior. |
| **Procesador** | Intel Xeon 2,0 GHz, 12 MB Cache, Turbo, HT de 4 Core o superior, Intel Core i7 de cuarta generación o superior. |
| **Discos Duros** | Opción 1:<ul><li>DD 0 (RAID 10) Partición C: 60 GB (SO) </li><li>DD 1 (RAID 10) Partición D: 80 GB (App y Servidor de archivos)</li></ul> *Notas:* <ul><li>Se recomienda que los discos duros sean SAS de 15.000 RPM o superior</li><li>El espacio en GB es el requerido y puede ser aumentado</li></ul> |
| **Notas** | Estos son los requisitos necesarios únicamente para Aranda y el servidor debe ser dedicado. |

---

## Servidor de Comunicaciones de Aranda (Conserver)

|  |  |
| :-- | :-- |
| **Sistema Operativo** | Windows Server 2012 R2, Standard Edition, x64, con las últimas versiones de Service Pack instaladas. |
| **Memoria RAM** | 4 GB o Superior. |
| **Procesador** | Intel Xeon 2,0 GHz, 12 MB Cache, Turbo, HT de 4 Core o superior, Intel Core i7 de cuarta generación o superior. |
| **Discos Duros** | Opción 1:<ul><li>DD 0 (RAID 10) Partición C: 60 GB (SO) </li><li> DD 1 (RAID 10) Partición D: 80 GB (App y Servidor de archivos)</li></ul> *Notas:* <ul><li>Se recomienda que los discos duros sean SAS de 15.000 RPM o superior</li><li>El espacio en GB es el requerido y puede ser aumentado</li></ul>|
| **Notas** | Estos requisitos son los necesarios únicamente para Aranda y este servidor debe ser dedicado. |

---

## Servidor de base de datos

|  |  |
| :-- | :-- |
| **Sistema Operativo** | Windows Server 2012 R2, Standard Edition, x64, con las últimas versiones de Service Pack instaladas. |
| **Memoria RAM** | 8 GB o Superior. |
| **Procesador** | Intel Xeon, 2.0 GHz, 12 MB Cache, Turbo, HT de 6 Core o superior. |
| **Discos Duros** | Opción 1: <ul><li>DD 0 (RAID 1) Partición C: 60 GB (SO)</li><li>DD 1 (RAID 10) Partición D: 120 GB (Data Files MDF)</li><li>DD 2 (RAID 1) Partición E: 80 GB (Transaction Log LDF)</li></ul>Opción 2:<ul><li>DD 0 (RAID 1) Partición C: 140 GB (SO, Transaction Log LDF)</li><li>DD 1 (RAID 10) Partición E: 120 GB (Data Files MDF)</li></ul> Opción 3:<ul><li>DD 0 (RAID 1) Partición C: 140 GB (SO, Transaction Log LDF)</li><li>DD 1 (RAID 5) Partición E: 120 GB (Data Files MDF)</li></ul>*Notas:* <ul><li>La opción 1 es la más recomendada, ya que su funcionamiento es mucho más rápido para las operaciones de lectura y escritura aleatorias en los MDF y para las operaciones de lectura y escritura secuenciales en los LDF.</li><li>Se recomienda que los discos duros sean SAS de 15.000 RPM o superior</li><li>El espacio en GB es el requerido y este puede ser aumentado en cualquiera de las 3 opciones.</li></ul> |
| **SQL Server** | Microsoft SQL Server 2012 Service Pack 2 Actualizado, instalado con: Full Text Search, Autenticación Mixta y Servicios de SQL Server Reporting Services. |
| **Notas** | Estos son los requerimientos necesarios únicamente para Aranda y el servidor debe ser dedicado. |

