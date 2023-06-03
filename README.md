OptimizadorPC 🚀💫
=============

Este optimizador que cree, elimina servicios que nomas consumen recursos de sus pc que podrían afectar el rendimiento del mismo a la hora de estar ejecutando un juego, stream, etc.

## ¿Virus? 😒
Probablemente tu navegador o PC detecten mi programa como virus.
Esto se debe a que como el programa realiza cambios en el equipo, y no tener un certificado oficial de windows, hace que el navegador quiera "defender" tu computadora de posible codigo malicioso, que evidentemente no es.\
Cuando tu navegador detecte el archivo como virus, selecciona el boton de 3 puntos en el area de descargas y despues en "conservar", una vez hecho todo lo anterior mencionado la descarga se acompletara de forma segura.\
Gracias por tu atencion, si es que leiste esto.

## Servicios que deshabilita el programa ✅
-`AppVClient:`\
El servicio "AppVClient" es responsable de gestionar la ejecución de las aplicaciones virtualizadas a través de App-V. En pocas palabras, si no emulas sistemas operativos VIRTUALES en tu pc, no necesitas para nada este servicio.

-HvHost\
El servicio "HvHost" es complemento del servicio de arriba de Hyper-V.

-autotimesvc\
El servicio "autotimesvc" es responsable de "cambiar" el reloj de tu computador cuando el horario cambia, pongo cambiar entre comillas porque deshabilitando este servicio podemos darnos cuenta de que aunque el horario cambie, el sistema sigue acomodando la hora de nuestro computador.

-diagsvc\
El servicio "diagnosticshub.standardcollector.service" es parte de la plataforma de diagnóstico de Windows. Este servicio normalmente funciona como deberia, siempre que algo en tu programa se bugea y se abre un cuadro de diagnostico te da "soluciones", pero al final estas soluciones nunca terminan arreglando el error y aun asi realizan cambios en el equipo.

-diagnosticshub.standardcollector.service\
El servicio "diagsvc" se refiere al servicio de diagnóstico en Windows. Es responsable de realizar diagnósticos y recopilar información sobre el rendimiento y la confiabilidad del sistema operativo. Basicamente es complemento del servicio de arriba.

-DiagTrack\
El servicio "DiagTrack" se refiere a Diagnostics Tracking Service en Windows. Su función principal es recopilar y enviar datos de diagnóstico y telemetría al equipo de Microsoft con el fin de mejorar la calidad, seguridad y rendimiento del sistema operativo.

-dmwappushservice\
El servicio "dmwappushservice" se refiere al servicio de notificaciones push de Wi-Fi Direct en Windows. Es responsable de enviar notificaciones y actualizaciones a dispositivos cercanos utilizando la tecnología Wi-Fi Direct.

-DsSvc\
El servicio "DsSvc" se refiere a "Delivery Optimization Service" en Windows. Su función principal es administrar y optimizar la entrega de actualizaciones y descargas de software en los sistemas operativos Windows.

-lfsvc\
El servicio "lfsvc" se refiere a "Windows License Manager Service" en Windows. Su función principal es administrar y realizar un seguimiento de las licencias y activaciones del sistema operativo Windows.

-MapsBroker\
El servicio "MapsBroker" en Windows es responsable de brindar funcionalidades relacionadas con los mapas y la ubicación en el sistema operativo, solo cuando tienes instalado google maps (que normalmente todos lo usan desde google).

-MsKeyboardFilter\
El servicio "MsKeyboardFilter" se refiere al "Microsoft Keyboard Filter Service" en Windows. Este servicio es parte de la funcionalidad de accesibilidad de Windows y se utiliza para filtrar y controlar el teclado en el sistema operativo.

-NetTcpPortSharing\
El servicio "NetTcpPortSharing" en Windows se utiliza para permitir el uso compartido de puertos TCP (Protocolo de Control de Transmisión) en el sistema operativo. Su función principal es facilitar la comunicación entre aplicaciones y servicios que utilizan el protocolo TCP.

-PcaSvc\
El servicio "PcaSvc" se refiere a "Program Compatibility Assistant Service" en Windows. Su función principal es ayudar a identificar y solucionar problemas de compatibilidad de programas en el sistema operativo.

-PhoneSvc\
El servicio PhoneSvc es el Servicio de Teléfono en Windows 10. Este servicio administra el estado de la telefonía en el dispositivo. Por defecto, su tipo de inicio es Manual y su nombre de visualización es Servicio de Teléfono.

-RemoteAccess\
El servicio "RemoteAccess" en Windows se refiere al servicio de Acceso Remoto. Su función principal es permitir a los usuarios acceder y conectarse de forma remota a una red o computadora desde ubicaciones externas a través de una conexión de red.

-RemoteRegistry\
El servicio RemoteRegistry es el Servicio de Registro remoto en Windows. Este servicio permite a los usuarios remotos modificar el Registro de Windows.

-RetailDemo\
El servicio RetailDemo es el Servicio de Demostración Comercial en Windows. Este servicio controla la actividad del modo de demostración comercial en dispositivos Windows.

-RmSvc\
RmSvc es el Media Center Extender Resource Monitor Service en Windows. Este servicio es un componente del software de Microsoft Windows y pertenece a Microsoft.

-RpcLocator\
El servicio RpcLocator es el Localizador de llamada a procedimiento remoto (RPC) en Windows. En Windows 2003 y versiones anteriores de Windows, este servicio administra la base de datos del servicio de nombres RPC.

-SCardSvr\
El servicio SCardSvr es el Servicio de Tarjeta Inteligente en Windows. Este programa le permite a su ordenador leer tarjetas Inteligentes y da servicios de autenticación para las tarjetas inteligentes (Smart cards) de seguridad, por lo general nadie tiene un lector de cartas en su computadora.

-SCPolicySvc\
El servicio SCPolicySvc es el Servicio de Directiva de Extracción de Tarjetas Inteligentes en Windows.

-SensorService\
El servicio SensorService es el Servicio de Sensores en Windows 10. Este servicio administra la funcionalidad de diferentes sensores.

-SensrSvc\
Este servicio es complemento del de arriba.

-SysMain\
SysMain es un servicio en Windows que tiene como objetivo mejorar el rendimiento del sistema, en algunos casos, SysMain puede consumir muchos recursos del disco y provocar un uso elevado de la CPU.

-TapiSrv\
TapiSrv es el Servicio de Telefonía en Windows. Este servicio administra los servicios de telefonía como el marcado de números, etc.

-TermService\
El servicio de TermService es un componente de Windows que permite a un usuario acceder a las aplicaciones y datos almacenados en otro ordenador mediante wifi.

-UevAgentService\
permite capturar opciones de configuración de Windows y de las aplicaciones personalizadas por el usuario y almacenarlas en un recurso compartido de archivos de red administrado de forma centralizada.
