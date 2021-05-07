# Notas Azure

## Informática en la nube

- Entrega de servicios informáticos a través de internet.

- Incluye servidores, almacenamiento, bases de datos, redes de software, análisis e inteligencia.

- Pagas solamente lo que usas.

Algunas ventajas que tiene el cómputo en la nube es que se tienen respaldos, el sistema operativo está siempre actualizado y está disponible todo el tiempo.

### Servicios básicos

#### Poder de procesamiento

Hace referencia al poder que la computadora tiene (generalmente dados por la RAM y el procesador). El uso de estos componentes tiene un precio, sin embargo, al trabajarlo en la nube, este se determina por la cantidad de uso que le des.

#### Almacenamiento

Hace referencia a la capacidad de información que tiene el servicio que contrates. Esta cantiddad puedes cambiarla como la vayas necesitando. 

## ¿Por qué es más barato?

Está basado en el esquema de pago por uso, lo que quiere decir que solamente se pagarán por los servicios en la nube que se necesitan, esto permite:

- Reducir costos operativos.

- Ejecutar infraestructura de forma eficaz.

- Escalar a medida que cambien las necesidades empresariales.

## ¿Por qué migrar a la nube?

La nube ayuda a moverse con más rapidez y a innovar de maneras que antes eran prácticamente imposibles. En la actualidad surgen dos tendencias:

- Los equipos proporcionan nuevas características a los usuarios a velocidades record.

- Los usuarios esperan una experiencia cada vez más ámplia y envolvente con sus dispositivos y con el software.

Las versiones de software antes se programaban en plazos de meses o años. En la actualidad, los equipos publican características en lotes pequeños que se programan en días o semanas.

## Ventajas de la informática en la nube

- Confiabilidad: Ofrecen una experiencia de usuario continua sin tiempo de inactividad perceptible aunque se produzcan errores.

- Escalabilidad: Las aplicaciones pueden escalar de dos maneras:
    - Verticalmente: La capacidad informática se puede aumentar si se agrega RAM o CPU adicionales a una máquina virtual.
    - Horizontalmente: La capacidad informática se puede aumentar si se agregan instancias de un recurso, como máquinas virtuales adicionales a la configuración.

- Elasticidad: Las aplicaciones en la nube se pueden implementar para tener siempre los recursos que necesitan.

- Agilidad: Los recursos basados en la nube se pueden implementar y configurar rápidamente a medida que cambian los requisitos de la aplicación.

- Distribución geográfica: Garantiza que los clientes siempre tendrán el mejor rendimiento de su región por la localización de los centros regionales de datos.

- Recuperación ante desastres: Al usar los servicios de copia de seguridad en la nube, la replicación de datos y la distribución geográfica, la información almacenada está segura.

## Modelos de servicio en la nube

- IaaS: infraestructura como servicio, trata de que un proveedor de servicios en la nube mantiene actualizado el hardware, pero el mantenimiento del sistema operativo y la configuración de red es responsabilidad del inquilino de la nube.
    - Ventaja: rápida implementación de una máquina virtual nueva lo cual es considerablemente más rápida que la obtención, instalación y configuración de un servidor físico.

- PaaS: Plataforma como servicio, se trata de un entorno de hospedaje administrado. El proveedor de servicios administra las máquinas virtuales y los recursos de red, y el inquilino de nube implementa sus aplicaciones en el entorno de hospedaje administrado.

SaaS: Software como servicio, el proveedor de servicios en la nube administra todos los aspectos del entorno de la aplicación, como las máquinas virtuales, los recursos de red, el almacenamiento de datos y las aplicaciones. El inquilino de nube solo proporciona sus datos a la aplicación administrativa por el proveedor de servicios en la nube.

### Servicios que pueden ser ejecutados en cada modelo.

<img src="https://docs.microsoft.com/es-mx/learn/azure-fundamentals/intro-to-azure-fundamentals/media/iaas-paas-saas.png">

### Niveles de responsabilidad

<img src="https://docs.microsoft.com/es-mx/learn/azure-fundamentals/intro-to-azure-fundamentals/media/shared-responsibility.png">

## Informática sin servidor

Se superpone a PaaS y permite el desarrollo de aplicaciones de manera más ágil, eliminando la necesidad de administrar la infraestructura. El proveedor de servicios en la nube proporciona, escala y administra la infraestructura necesaria. Estas son totalmente escalables.

## Nube pública, privada e híbrida

### Nube pública

Los servicios son ofrecidos mediante internet pública y están disponibles para cualquiera que quiera comprarlos. Los recursos de nube son propiedad de un proveedor de servicios en la nube de terceros, que los explota y distribuye mediante internet.

### Nube privada

Los recursos informáticos son de uso exclusivo de los usuarios de una empresa u organización. Esta se ubica físicamente y es administrada por la empresa.

### Nube híbrida

Combina la nube pública con la privada, lo que permite compartir datos y aplaciones entre estas dos.

## Azue

Se trata de un conjunto de servicios en la nube en expansión constante que ayuda a las empresass a cumplir los desafíos empresariales actuales y futuros.

## ¿Qué ofrece Azure?

- Preparado para el futuro: La inovación continua de Microsoft apoya el desarrollo actual y los proyectos futuros.

- Crear: Si se mantiene un compromiso con el código abierto y se admiten todos los lenguajes marcos, es posible compilar como se desee e implementar desde cualquier parte.

- Operar el entorno híbrido sin problemas: Permite la integración y administración de los entornos con herramientas y servicios diseñados para una solución híbrida.

- Seguridad: Está respaldado por un equipo de expertos.

## ¿Cómo funciona Azure?

Azure ofrece un portal con el que interactua el usuario. Este portal se conecta a un orquestador mediante una API. Posterior a esto, el orquestador empaqueta la solicitud y la envía al servidor del rack, el cual lo comunica al controlador de fábrica para que ejecute la acción empaquetada por el orquestador (como crear una máquina virtual por ejemplo).

<img src="/FuncionAzure.PNG">

## Azure portal

Es una alternativa a las herramientas de líneas de comandos online. Permite la administración de los servicios mediante interfaz gráfica. Esta permite administrar la suscripción de Azure mediante una interfaz gráfica de usuario. Esta puede:

- Compilar, administrar y supervisar todo, desde aplicaciones web sencillas hasta complejas implementaciones en la nube.

- Crear páneles personalizados para una vista organizada de recursos.

- Configurar opciones de accesbilidad para una experiencia óptima.

<img src="https://docs.microsoft.com/es-mx/learn/azure-fundamentals/intro-to-azure-fundamentals/media/azure-portal.png">

## Azure Marketplace

Facilita la conexión entre los usuarios y los proveedores de software que ofrecen soluciones y servicios optimizzados para ejecutarse en Azure. Los clientes pueden buscar, probar, comparar y aprovisionar aplicaciones y servicios de cientos de proveedores de servicios.

<img src="https://docs.microsoft.com/es-mx/learn/azure-fundamentals/intro-to-azure-fundamentals/media/marketplace.png">

# Unidad 4

## Paseo por los servicios de Azure

A continuación se muestra una lista de servcios y características disponibles de Azure:

<img src="https://docs.microsoft.com/es-mx/learn/azure-fundamentals/intro-to-azure-fundamentals/media/azure-services.png">

## Proceso

Los servicios a menudo son una de las razones principales de por qué las compañías se cambian a la plataforma Azure. A continuación se muestran algunos de estos:

- Azure Virtual Machines: Máquinas virtuales Windows o Linux hospedadas en Azure.

- Azure Virtual Machine Scale Sets: Escalado de máquinas virtuales Windows o Linux hospedadas en Azure.

- Azure Kubernetes Service: Administración de clústeres para máquinas virtuales que ejeutan servicios en contenedores.

- Axure Service Fabric: Plataforma de sistemas distribuidos que se ejecuta en Azure o en el entorno local.

- Azure Batch: Servicio administrado para aplicaciones informáticas de alto rendimientos y paralelas.

- Azure Container Instances:  Aplicaciones en contendores que se ejecutan en Azure sin necesidad de aprovisionar servidores ni máquinas virtuales.

- Azure Functions: Un servico de procesos sin servidor y controlado por eventos.

## Redes

Azure Virtual Network: Conecta máquinas vrituales a VPN entrantes.

Azure Load Balancer: Equilibra las conexiones entrantes y salientes a aplicaciones o puntos de conexión de servicio.

Azure Application Gateway: Optimiza la entrega de granjas de servidores de aplicaciones y aumenta su seguridad.

Azure VPN Gateway: Accede a redes de Azure Virtual Network mediante VPN de alto rendimiento.

Azure DNS: Proporciona respuestas DNS ultrarrápidas y disponibildad de dominio extremadamente alta.

Azure DNS: Proporciona respuestas DNS rápidas y disponibilidad de dominio alto.

Azure Content Delivery Network: Entrega contenido de gran ancho de banda a los clientes globalmente.

Azure DDoS Protection: Protege las aplicaciones hospedadas en Azure frente ataques DDoS.

Azure Trafic Manager: Distribuye el tráfico de rede entre las regiones de Azure todo el mundo.

Azure ExpressRoute: Se conecta mediante conexiones seguras de gran ancho de banda dedicadas.

Azure Network Watcher:  Supervisa y diagnostíca problemas de red.

Azure Firewall: Firewall de alta seguridad, disponibilidad y escalabilidad ilimitada.

Azure Virtual WAN: Crea un área WAN que conecta sitios locales y remotos.

## Almacenamiento

Azure proporciona 4 tipos principales de almacenamiento:

- Azure Blob Storage: Almacenamiento de archivos muy grandes, como videos o mapas de bits.

- Azure File Storage: Recurso compartido de archivos que se administra como servidor de archivos.

- Azure Queue Storage: Almacen de archivos para la puesta en cola y la entrega confiable de mensajes entre aplicaciones.

Todos estos servicios cuentan con durabilidad, seguridad, escalabilidad, administración y accesibilidad.

## Móvil

Azure permite la creación de servicios back-end para aplicaciones móviles. Estas tienen las siguientes características:

- Sincronización de datos sin conexión.

- Conectividad a datos locales.

- Difusión de notificaciones de insercción.

- Escalado automático.

## Bases de datos

- Azure Cosmos DB: Base de datos distribuida globalmente que admite opciones NoSQL.

- Azure SQL Database: Base de datos relacional administrada con escalado automático, inteligencia integral y seguridad sólida.

- Azure Synapse Analytics: Almacen de datos administrado con seguridad integral en todos los niveles de escala sin costo adicional.

- Azure Database Migration Service: Migra bases de datos a la nube sin cambios en el código de aplicación.

- Azure Cache for Redis: Almacena en caché datos estáticos usados con frecuencia para reducir latencia de datos.

## Web

- Azure App Service: Creación rápida de aplicaciones en la nube basadas en web.

- Azure Notification Hubs: Enviar notificaciones push a cualquier plataforma desde cualquier back-end.

- Azure Api Management: Publicar API para desarrolladores.

- Azure Cognitive Search: Búsqueda completamente administrada que se implementa como servicio.

- Característica Web Apps de Azure App Service: Creación de aplicaciones web críticas a escala.

- Servicio Azure SignalR: Agrega funcionalidades web en tiempo real.

## IoT

- IoT Central: SaaS de IoT administrada que facilita la conexión, supervisión y la administración de los recursos de IoT a escala.

- Azure IoT Hub: Proporciona comunicaciones y supervisión segura entre millones de dispositivos IoT.

- IoT Edge: Permite insertar los modelos de análisis de datos directamente en los dispositivos IoT.