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

# Módulo 2

## Gastos de capital en comparación con los gastos operativos

- Gastos de capital (CapEx) hacen referencia a la inversión previa de dinero en infraestructura física, que se podrá deducir a lo largo del tiempo. El costo previo de CapEx tiene un valor que disminuye con el tiempo. Este corresponde a la adquisición de infraestructura mantenida por la empresa.

- Gastos operativos (OpEx) son dinero que se inverte en servicios o productos y se factura al instante. Este gasto se puede deudicr el mismo año que se produce. No hay ningún costo previo, ya que se paga un servicio o producto a medida que se usa. Este corresponde a la contratación de servicios en la nube como Azure.

## Informática sin servidor

La informática sin serviddor permite que los desarrolladores creen aplicaciones más rápidamente, ya que elimina la neccesidad de administrar la infraestructura. En estas, el proveedor de servicios en la nube aprovisiona, escala y administra automáticamente la infraestructura necesaria para ejecutar el código. Suelen ser muy escalables y controladas por eventos, y solo usan recursos cuando se produce una función o un desencadenador concretos.

# Módulo 3

## Niveles de Azure

- Recursos: Los recursos son instancias de servicios que pueden ser creados, como máquinas virtuales, almacenamiento o bases de datos SQL.

- Grupos de recursos: Los recursos se combinan en grupos de recursos, que actuan como contenedor lógico en el que se implementan y administran recursos de Azure como aplicaciones web, bases de datos y cuentas de almacenamientos.

- Suscripciones: Una suscripción agrupa las cuentas de usuario y los recursos que han sido creadas por las cuentas de usuario. Para cada suscripción, hay límites o cuotas en la cantidad de recursos que se pueden crear y usar. Las organizaciones pueden usar sucripciones para adminsitrar los costos y los recursos creados por los los usuarios.

- Grupos de administración: Estos grupos permiten la administración del acceso, lass directivas y el cumplimiento de varias suscripciones. Todas las suscripciones de un grupo de administración heredan automáticamente las conodiciones que se aplican al grupo de administración.

A continuación se muestra una imagen que ilustra lo anterior:

<img src="https://docs.microsoft.com/es-mx/learn/azure-fundamentals/azure-architecture-fundamentals/media/hierarchy.png">

## Suscripciones de Azure

Una sucrpición de Azure proporciona acceso autenticado y autorizado a los servicios y productos de Azure. Además, también permite aprovisionar los recursos. Es una unidad lógica de servicios de Azure que está vinculada a una cuenta de Azure, que es una identidad en Azure Active Directory (Azure AD) o en un directorio en el que confía Azure AD.

<img src="https://docs.microsoft.com/es-mx/learn/azure-fundamentals/azure-architecture-fundamentals/media/subscriptions.png">

Una cuenta de Azure puede tener una suscripción o más con distintos modelos de facturación y a las que se aplican diferentes directivas de administración de acceso. Azure cuenta con dos tipos de límites de suscripción:

- Límite de facturación: Permite la administración y organización de los costos mediante el control de cuanto se factura.

- Límite de control de acceso: Permite administrar y controlar el acceso a los recursos que los usuarios aprovisionan con suscripciones específicas.

## Creación de una suscripción adicional

Las suscripciones pueden ser creadas para distintos propósitos, algunos de estos son:

- Entornos: Se pueden crear suscripciones con el fin de configurar entornos independientes para el desarrollo y las pruebas, para seguridad o para aislar los datos por motivo de cumplimiento. Esto es útil porque el control de los recursos se produce en el nivel de suscripción.

- Estructuras organizativas: Se pueden crear para reflejar distintas estructuras organizativas. Este diseño permite administrar y controlar el acceso a los recursos que los usuarios aprovisionan en cada suscripción. Esto podría por ejemplo limitar a un equipo a recursos de bajo costo, al tiempo que permite a otro equipo que necesita más de estos reccursos tener más libertad.

- Facturación: Crear suscripciones adicionales para fines de facturación. Dado a que los costos se agregan primero en el nivel de suscripción, es posible que se quieran crear suscripciones para administrar y realizar un seguimiento de los costos en función de sus necesidades.

- Límites de suscripción: Las suscripciones se enlazan a algunas limitaciones de hardware. Estos límites se deben de considerar al crear suscripciones en la cuenta.

## Personalización de la facturación para la satisfacción de necesidades

En función de las necesidades, es posible configurar facturas dentro de la misma cuenta de facturación, esto mediante la creación de perfiles de facturación adicionales. Cada perfil de facturación contiene su propia factura mensual y método de pago. A continuación se muestra un recurso que ejemplifica esto:

<img src="https://docs.microsoft.com/es-mx/learn/azure-fundamentals/azure-architecture-fundamentals/media/billing-structure-overview.png">

## Grupo de administración de Azure

Los grupos de administración de Azure ofrecen un nivel de ámbito que está por encima de las suscripciones. Las suscripciones son organizadas en contenedores y estas heredan las condiciones aplicadas al grupo de administración. 

## Hechos importantes sobre los grupos de administración

- Se admiten 10 000 grupos de administración en un único directorio.

- Un arbol de grupo de administrción admite hasta 6 niveles de profundidad sin incluir el nivel de raíz y el nivel de suscripción.

- Cada grupo de adminstración y suscripción admiten solamente un elemento primario.

- Cada grupo de administración puede tener muchos elementos secundarios.

- Todas las suscripciones y grupos de administración están dentro de una única jerarquía en cada directorio.

## Recursos de Azure y Azure Resource Manager

- Recurso: Elemento administrable que está disponible mediante Azure, tales como DB, VM, almacenamiento, etc.

- Grupo de recursos: El grupo de recursos incluye los recursos que se quieren administrar como grupos.

## Grupos de recursos de Azure

Se trata de un contenedor lógico para recursos implementados en Azure. Todos los recursos deben de pertenecer a un grupo de recursos y solamente pueden pertenecer a un grupo. Los grupos de recursos no se pueden anidar.

## Ciclo de vida

Si se elimina un grupo de recursos, también se eliminarán todos los recursos contenidos. La organización de recursos por ciclo de vida puede ser útil en entornos que nos sean de producción, en los que se puede probar una experimento y después descartarlo.

## Azure Resource Manager

Es el servicio de implementación y administración para Azure. Proporciona una capa de administración que permite crear, actualizar y eliminar recursos de la cuenta de Azure. Cuando un usuario envía una solicitud de cualquiera de las herramientas, las API o los SDK de Azure, Resource Manager recibe la solicitud. A continuación se muestra el rol del administrador de recursos:

<img src="https://docs.microsoft.com/es-mx/learn/azure-fundamentals/azure-architecture-fundamentals/media/consistent-management-layer.png">

Todas las funcionalidades que están disponibles en Azure Portal también lo están a través de PowerShell, la CLI de Azure, las API REST y los SDK de cliente.

## Ventajas de usar Administrador de recursos

- Administrar la infraestructura mediante plantillas declarativas (escritas en JSON) en lugar de scripts.

- Implementar, administrar y supervisar todos los recursos de la solución en grupo, en lugar de controlarlos individualmente.

- Los recursos se implementan en un estado coherenete al reimplementar la solución a lo largo del ciclo de vida de desarrollo.

- Aplica control de acceso a todos los servicios, puesto que RBAC se integra de forma nativa en la plataforma de administración.

- Aplicar etiquetas a los recursos para organizar de manera lógica todos los recursos de la suscripción.

Comprender la facturación de la organización viendo los costos de grupo de recursos que comparten la misma etiqueta.

## Zonas de disponibilidad, pares de regiones y regiones de Azure

Los recursos se crean en regiones, que son diferentes ubicaciones geográficas de todo el mundo que continenen centros de datos de Azure.

Azure está formado por centros de datos ubicados en todo el mundo. Al utilizar un servicio o crear un recurso, se utiliza un equipo físico en una o varias de estas ubicaciones. Estos centros de datos no están expuestos a los usuarios, si no que Azure los organiza en regiones. 

## Regiones de Azure

Una región es un área geográfica del planeta que contiene al menos un centro de datos, aunque podrían ser varios centros de datos cercanos y conectados mediante una red de baja latencia. Azure asigna y controla los recursos de forma inteligente dentro de cada región para garantizar que las cargas de trabajo estén bien compensadas. A continuación se ven las regiones disponibles a fecha de juno del 2020:

<img src = "https://docs.microsoft.com/es-mx/learn/azure-fundamentals/azure-architecture-fundamentals/media/regions-small.png">

## Regiones de Azure especiales

- US DoD(centro), US Gov Virginia, US Gov Iowa y más: Son instancias físicas y lógicas con aislamiento de red de Azure para asociados y agencias de la administración pública de EE. UU. Estos centros de datos son operados por personal estadounidense sometido a evaluación e incluyen certificaciones de cumplimiento adicionales.

- Este de China, Norte de China y más: Estas regiones están disponibles gracias a una asociación exclusiva entre Microsoft y 21Vianet, por la cual Microsoft no mantiene directamente los centros de datos.

## Zona de disponibilidad

Se tratan de centros de datos separados físicamente dentro de una región de Azure. Esta se configura para constituir un límite de aislamiento. Si una zona deja de trabajar, la otra continua trabajando. Estas se conectan mediante redes de fibra óptica de alta velocidad privadas.

## Uso de las zonas de disponibilidad en las aplicaciones

Para conseguir una alta disponibilidad en la arquitectura de la aplicaciones, se deben de poner los recursos de un proceso, almacenamiento y red dentro de una zona y posteriormente replicarlas. Esto puede suponer un costo.

Los servicios de Azure que admiten zonas de disponibilidad se dividen en dos categorías:

- Servicios de zona: Se ancla el recurso a una zona específica.

- Servicios de redundancia de zona: La plataforma se replica automáticamente entre zonas.

## Pares de regiones de Azure

Cada región de Azure se empareja siempre con otra región de la misma zona geográfica que se encuentre como mínimo a 500 km de distancia. Esto permite la replicación de recursos, lo que ayuda a reducir la probabilidad que se produzcan interrupciones provocadas por eventos como desastres naturales o disturbios. Si una región de un par se ve afectada por un desastre, los servicios conmutarán por error automáticamente a la otra región de su par de regiones. A continuación se muestran algunos de estos pares:

<img src="https://docs.microsoft.com/es-mx/learn/azure-fundamentals/azure-architecture-fundamentals/media/region-pairs.png">