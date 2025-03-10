# Descripción de las ventajas de usar servicios en la nube

## Descripción de las ventajas de la alta disponibilidad y la escalabilidad en la nube

- **Alta Disponibilidad**: Garantiza la máxima disponibilidad, independientemente de las interrupciones o eventos que puedan producirse. Las aplicaciones pueden proporcionar una experiencia de usuario continua sin tiempo de inactividad perceptible aunque se produzcan errores segun el SLA (Service Level Agreement) que elija.

- **Escalabilidad**: Capacidad de ajustar los recursos para satisfacer la demanda, solo paga por lo que usa.
    - **Verticalmente**: Aumentar o disminuye las capacidades de los recursos. Capacidad informática que puede aumentar si se agrega RAM o CPU adicionales a una máquina virtual.
    - **Horizontalmente**: Agrega o resta el número de recursos. Capacidad informática que puede aumentar si se agregan instancias de un recurso.

## Descripción de las ventajas de la confiabilidad y la previsibilidad en la nube

- **Confiabilidad**: La capacidad de un sistema para recuperarse de errores y seguir funcionando sin interrupciones. Azure ofrece un diseño **descentralizado** que garantiza la disponibilidad incluso si una región experimenta fallas.

| **Concepto** | **Descripción** | **Servicios de Azure** |
|-------------|----------------|----------------|
| **Alta Disponibilidad (High Availability, HA)** | Garantiza que los servicios permanezcan accesibles incluso ante fallos de hardware o software. | Azure Availability Zones, Azure Traffic Manager |
| **Resiliencia ante Fallos Regionales** | Si una región tiene un evento catastrófico, otras regiones siguen operando. | Azure Site Recovery, Geo-Redundant Storage (GRS) |
| **Redundancia Multirregional** | Replicación automática de datos en múltiples regiones para evitar pérdida de información. | Azure Cosmos DB, Azure SQL Geo-Replication |
| **Recuperación ante Desastres (Disaster Recovery)** | Permite restaurar aplicaciones y datos en caso de fallas. | Azure Backup, Azure Site Recovery |
| **Contramedidas contra Ataques DDoS** | Protección integrada para mitigar ataques de denegación de servicio distribuido (DDoS). | Azure DDoS Protection |

- **Previsibilidad**: Permite a las empresas planificar y optimizar el rendimiento y los costos en la nube. Se divide en dos aspectos clave:: 

    - **Previsibilidad del rendimiento**: Se centra en estimar y asignar los recursos adecuados para garantizar una experiencia óptima para los usuarios.

    | **Concepto** | **Descripción** | **Servicios de Azure** |
    |-------------|----------------|----------------|
    | **Escalado Automático (Auto-scaling)** | Ajusta automáticamente la cantidad de recursos en función de la demanda. Si el tráfico aumenta, se agregan más recursos; si disminuye, se reducen para optimizar costos. | Azure Virtual Machine Scale Sets, Azure Kubernetes Service (AKS) |
    | **Equilibrio de Carga (Load Balancing)** | Distribuye el tráfico de manera eficiente entre diferentes servidores para evitar sobrecargas y garantizar disponibilidad. | Azure Load Balancer, Azure Application Gateway |
    | **Alta Disponibilidad (High Availability, HA)** | Mantiene las aplicaciones en funcionamiento incluso ante fallos de infraestructura. | Azure Availability Zones, Azure Load Balancer |
    | **Monitoreo y Ajuste Dinámico** | Herramientas para rastrear el rendimiento y ajustar recursos en tiempo real. | Azure Monitor, Azure Log Analytics |

    - **Previsibilidad de costos**: Permite **planificar el gasto en la nube** y evitar costos inesperados mediante herramientas de análisis y monitoreo.

    | **Concepto** | **Descripción** | **Servicios de Azure** |
    |-------------|----------------|----------------|
    | **Seguimiento en Tiempo Real** | Monitoreo constante del uso de recursos para evitar sobrecostos. | Azure Cost Management + Billing |
    | **Optimización de Recursos** | Uso eficiente de instancias reservadas, instancias Spot y ajuste de almacenamiento. | Azure Reserved Instances, Azure Spot Virtual Machines |
    | **Análisis de Costos y Tendencias** | Herramientas de análisis para detectar patrones de consumo y optimizar la inversión. | Azure Advisor, Azure Pricing Calculator |
    | **Herramientas de Estimación** | Cálculo de costos futuros basados en uso estimado de recursos. | Azure Pricing Calculator |
    | **Costo Total de Propiedad (TCO)** | Evaluación de los costos de migración y operación a largo plazo en comparación con la infraestructura on-premise. | Azure TCO Calculator |

Ambos aspectos están influenciados por **Microsoft Azure Well-Architected Framework**, un marco de arquitectura que permite diseñar soluciones en la nube con costos y rendimiento predecibles.

## Descripción de las ventajas de la seguridad y la gobernanza en la nube

La seguridad y la gobernanza en la nube son elementos esenciales para garantizar el cumplimiento normativo, la administración eficiente de los recursos y la protección contra amenazas cibernéticas. Independientemente del modelo de implementación (*IaaS, PaaS o SaaS*), las características de la nube permiten un alto nivel de control, auditoría y mitigación de riesgos.

- **Seguridad**: Los servicios en la nube ofrecen soluciones que pueden adaptarse a diferentes niveles de control y gestión de seguridad.

| **Ventaja** | **Descripción** | **Servicios en Azure** |
|------------|----------------|----------------|
| **Seguridad Administrada** | En modelos **PaaS y SaaS**, Azure gestiona automáticamente revisiones de seguridad, parches y protección contra amenazas. | Microsoft Defender for Cloud, Azure Security Center |
| **Control Total en IaaS** | En **IaaS**, las empresas administran la seguridad del sistema operativo y las aplicaciones. | Azure Virtual Machines, Azure Key Vault |
| **Protección contra Ataques DDoS** | Azure detecta y mitiga ataques de denegación de servicio distribuido (DDoS). | Azure DDoS Protection |
| **Monitoreo en Tiempo Real** | Permite la detección y respuesta ante amenazas de manera proactiva. | Azure Monitor, Microsoft Sentinel |
| **Cifrado de Datos** | Protección de datos en tránsito y en reposo con cifrado avanzado. | Azure Disk Encryption, Azure Storage Service Encryption |

- **Gobernanza**: La gobernanza en la nube se refiere al conjunto de políticas, reglas y procesos que garantizan que los recursos en la nube cumplan con los estándares corporativos y las normativas regulatorias.

| **Ventaja** | **Descripción** | **Servicios en Azure** |
|------------|----------------|----------------|
| **Cumplimiento Normativo** | Cumple con regulaciones globales como **ISO 27001, GDPR, HIPAA, SOC 2**. | Microsoft Purview Compliance Manager |
| **Plantillas de Gobernanza** | Aplicación de reglas de cumplimiento y control de acceso para todos los recursos. | Azure Policy, Azure Blueprints |
| **Actualización Centralizada** | Actualiza y administra configuraciones de seguridad en toda la infraestructura. | Azure Update Management |
| **Auditoría Basada en la Nube** | Detección de recursos no conformes y mitigación automática de riesgos. | Azure Security Center, Microsoft Defender for Cloud |
| **Automatización de Revisiones y Seguridad** | Aplicación automática de actualizaciones de seguridad en **PaaS y SaaS**. | Azure Automation, Azure Logic Apps |

###  Beneficios Clave de una Estrategia de Gobernanza y Seguridad en la Nube
- **Reducción de Riesgos**: Detección y mitigación de amenazas con monitoreo continuo.  
- **Cumplimiento de Normativas**: Herramientas integradas para auditorías y cumplimiento regulatorio.  
- **Gestión Centralizada**: Control de todos los recursos en la nube desde una única plataforma.  
- **Escalabilidad Segura**: Permite agregar más recursos sin comprometer la seguridad.  
- **Protección Integral contra Amenazas**: Soluciones avanzadas de Microsoft contra ciberataques.  

Una estrategia sólida de **seguridad y gobernanza en la nube** permite mantener la infraestructura segura, cumplir con regulaciones y optimizar la administración de recursos. Dependiendo del modelo de servicio (*IaaS, PaaS o SaaS*), las empresas pueden elegir entre un **control total de seguridad** o una **gestión automatizada con seguridad administrada por el proveedor**.

## Descripción de las ventajas de la capacidad de administración en la nube

- **Administración de la nube**: Trata sobre administrar los recursos en la nube.
    - Escalar automáticamente la implementación de recursos en función de las necesidades.
    - Implementar recursos basados en una plantilla preconfigurada, lo que elimina la necesidad de realizar la configuración manual.
    - Supervisar el estado de los recursos y reemplazar automáticamente los recursos con errores.
    - Recibir alertas automáticas basadas en métricas configuradas, de modo que esté informado del rendimiento en tiempo real.

- **Administración en la nube**: Trata sobre cómo puede administrar el entorno y los recursos en la nube.
    - Mediante un portal web.
    - Con una interfaz de línea de comandos básica.
    - Mediante las API.
    - Mediante PowerShell.

[Azure Fundamentals](../README.md)