# Instalación

ADM cuenta en total con cuatro instaladores, explicados a continuación:  


# Consola

El instalador de la **consola web** de aranda Device Management.Web. Installer instala los sitios de la consola y el Repserver, adicionalmente crea los servicios de los Crunchers, License, Scheduler, Mailer, Worker que se usan en la aplicación. A continuación, el paso a paso de la instalación. Hacer clic sobre el instalador, se visualiza la siguiente advertencia.

# Agente

Para realizar la instalación del **Agente** de ADM por línea de comando se puede ejecutar la siguiente instrucción desde el command promt de Windows.

<span style="color:#000; font-family: 'courrier'; font-size: 4em;">Agent.Windows.x86_x64.9.3.1803.0108 /S /V"/norestart /qn AGENT_SERVER_ADDRESS=http://localhost/Conserver AGENT_PROFILE_ID=0"</span>

# Conserver

**Aranda.Conserver.Installer** el cual instala el servicio del Conserver. Se deberá instalar uno por cada segmento de red. A continuación, el paso a paso de la instalación del Conserver. Al hacer clic sobre el instalador, se visualiza la siguiente advertencia.