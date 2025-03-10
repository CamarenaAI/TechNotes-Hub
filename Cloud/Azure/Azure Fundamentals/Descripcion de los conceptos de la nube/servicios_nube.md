# Descripción de los tipos de servicio en la nube

## Descripción de la infraestructura como servicio (Iaas)

**Infrastructure as a service (IaaS)**: La categoría más flexible de servicios en la nube. Su objetivo es ofrecer un control completo sobre el hardware que ejecuta la aplicación. En vez de comprar hardware se alquila.

La mayor parte de responsabilidad recae en usted:
- Instalación.
- Configuración y mantenimiento del sistema operativo.
- Configuración de red.
- Configuración de base de datos
- Configuración de almacenamiento.

La responsabilidad del provedor es:
- Mantener el hardware.
- Mantener la conectividad de red (a Internet).
- Mantener la seguridad física.

**Ventajas**:
- Sin gastos de capital (CapEx).
- Agilidad.
- Administración.
- Modelo basado en el consumo.
- Aptitudes. 
- Flexibilidad.

## Descripción de la plataforma como servicio (PaaS)

**Platform as a service (PaaS)**: Punto intermedio entre alquilar espacio en un centro de datos (IaaS) y pagar por una solución completa e implementada (Saas). Es un entorno de hospedaje administrado, no tiene que preocuparse por las licencias ni la aplicación de revisiones para los sistemas operativos y las bases de datos.

La responsabilidad del provedor es:
- La infraestructura física.
- La seguridad física
- La conexión a Internet. 
- Mantener los sistemas operativos.
- Mantener el middleware.
- Mantener las herramientas de desarrollo
- Mantener los servicios de inteligencia empresarial.

**Ventajas**:
- Sin gastos de capital (CapEx).
- Agilidad.
- Modelo basado en el consumo.
- Aptitudes. 
- Productividad.

**Desventaja**:
- Limitaciones de la plataforma.

## Descripción del software como servicio (SaaS)

**Software as a service (SaaS)**: Software que se hospeda y administra de forma centralizada para usted y sus usuarios o clientes, es el modelo de servicio en la nube más completo desde el punto de vista del producto. Básicamente lo que hace es alquilar o usar una aplicación totalmente desarrollada. Puede ser el menos flexible pero también es el más sencillo de poner en marcha. Requiere la menor cantidad de conocimientos técnicos o experiencia para utilizarlo en toda su dimensión.

**Ventajas**:
- Sin gastos de capital (CapEx).
- Agilidad.
- Modelo de precio de pago por uso.
- Aptitudes. 
- Flexibilidad.

**Desventaja**:
- Limitaciones de software.

## Identificación de los Casos de Uso Adecuados para Cada Tipo de Servicio en la Nube

Los servicios en la nube se clasifican en tres modelos principales: **IaaS, PaaS y SaaS**, cada uno con aplicaciones específicas según las necesidades del negocio.

- **Infrastructure as a Service (IaaS)**
IaaS proporciona recursos de infraestructura como servidores virtuales, almacenamiento y redes. Es ideal para empresas que desean administrar sus propias aplicaciones sin preocuparse por la infraestructura física.

| **Casos de Uso** | **Descripción** | **Servicios en Azure** |
|------------------|----------------|----------------|
| **Migración mediante lift-and-shift** | Se trasladan aplicaciones existentes desde entornos on-premises a la nube sin modificaciones significativas. | Azure Migrate, Azure Virtual Machines |
| **Pruebas y desarrollo** | Creación de entornos de prueba y desarrollo flexibles sin la necesidad de adquirir hardware físico. | Azure DevTest Labs, Azure Virtual Machines |
| **Almacenamiento y backup** | Uso de almacenamiento escalable para copias de seguridad y recuperación ante desastres. | Azure Blob Storage, Azure Backup, Azure Site Recovery |
| **Sitios web de alto tráfico** | Hosting de sitios web con alta demanda, asegurando escalabilidad y disponibilidad. | Azure Virtual Machines, Azure Load Balancer |
| **Big Data y análisis** | Procesamiento de grandes volúmenes de datos sin necesidad de infraestructura local. | Azure Data Lake, Azure Synapse Analytics |

- **Platform as a Service (PaaS)**
PaaS proporciona un entorno de desarrollo con herramientas preconfiguradas para facilitar la creación y gestión de aplicaciones sin preocuparse por la infraestructura subyacente.

| **Casos de Uso** | **Descripción** | **Servicios en Azure** |
|------------------|----------------|----------------|
| **Marco de desarrollo** | Proporciona herramientas y frameworks para desarrollar aplicaciones sin preocuparse por la infraestructura subyacente. | Azure App Service, Azure Functions |
| **Análisis o inteligencia empresarial** | Permite procesar datos y generar informes sin administrar hardware o sistemas operativos. | Azure Synapse Analytics, Azure Machine Learning |
| **Automatización de procesos de negocio** | Facilita la creación de flujos de trabajo y automatización de tareas empresariales. | Azure Logic Apps, Power Automate |
| **Aplicaciones IoT** | Desarrollo y despliegue de soluciones para dispositivos IoT con conectividad en la nube. | Azure IoT Hub, Azure Time Series Insights |
| **Bases de Datos como Servicio** | Gestión de bases de datos sin necesidad de administración de servidores físicos. | Azure SQL Database, Azure Cosmos DB |

- **Software as a Service (SaaS)**
SaaS ofrece aplicaciones listas para usar a través de Internet, sin necesidad de instalación o mantenimiento.

| **Casos de Uso** | **Descripción** | **Servicios en Azure** |
|------------------|----------------|----------------|
| **Correo electrónico y mensajería** | Comunicación empresarial basada en la nube. | Microsoft 365 (Outlook, Teams), Exchange Online |
| **Aplicaciones de productividad empresarial** | Herramientas para colaboración y gestión de documentos. | Microsoft 365 (Word, Excel, SharePoint) |
| **Seguimiento de finanzas y gastos** | Control y análisis financiero en la nube. | Dynamics 365 Finance |
| **Gestión de relaciones con clientes (CRM)** | Administración de interacciones con clientes. | Dynamics 365 Customer Engagement |
| **E-learning y Capacitación** | Plataformas de aprendizaje en línea. | Microsoft Learn, Viva Learning |

Cada modelo de servicio en la nube se adapta a diferentes necesidades empresariales.  
- **IaaS** es ideal para empresas que buscan flexibilidad y control sobre la infraestructura.  
- **PaaS** facilita el desarrollo y la gestión de aplicaciones sin preocuparse por servidores.  
- **SaaS** ofrece soluciones listas para usar sin requerir instalación o mantenimiento.  

La elección del servicio adecuado depende de los objetivos y recursos de cada organización.

### Servicios que pueden ejecutarse en cada uno de los modelos de servicio
![modelos_de_servicio](https://docs.microsoft.com/es-mx/training/azure-fundamentals/fundamental-azure-concepts/media/iaas-paas-saas-expanded.png#lightbox)

### Modelo de responsabilidad compartida
![responsabilidad_compartida](https://learn.microsoft.com/es-mx/training/wwl-azure/describe-cloud-service-types/media/shared-responsibility-b3829bfe.svg)