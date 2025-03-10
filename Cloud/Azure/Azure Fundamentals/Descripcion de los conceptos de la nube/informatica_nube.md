# Descripción de la informática en la nube

## Definición de informática en la nube

**Informática en la nube**: Es la prestación de servicios informáticos a través de Internet mediante un modelo de precios de pago por uso, no es necesario que la infraestructura física la restrinja del mismo modo que un centro de datos tradicional ademas ofrece una innovación más rápida, recursos flexibles y economías de escala.

Si necesita aumentar rápidamente la infraestructura de TI, no tiene que esperar a crear un centro de datos, sino que puede usar la nube para expandir rápidamente la superficie de TI.

Los servicios informáticos incluyen infraestructura de TI común:
- Máquinas virtuales. 
- Almacenamiento.
- Bases de datos.
- Redes.

## Descripción del modelo de responsabilidad compartida

Modelo que divide las responsabilidades de seguridad estas se comparten entre el proveedor de servicios en la nube y el consumidor, la responsabilidad depende de la situacion.

El provedor es responsable de:
- La seguridad física. 
- Incluyendo el centro de datos.
- La infraestructura del centro de datos (alimentación, refrigeración, red física y hosts físicos).
- La conectividad de red.

El consumidor es responsable de:
- Los datos y la información almacenada en la nube.
- La seguridad de acceso.

El modelo de responsabilidad compartida está muy vinculado a los tipos de servicio en la nube:
- **Infrastructure as a Service (IaaS)**: Sitúa la mayor responsabilidad en el consumidor y el proveedor de servicios en la nube es el responsable de los conceptos básicos de seguridad física, energía y conectividad
- **Platform as a Service (PaaS)**: Distribuye uniformemente la responsabilidad entre el proveedor de nube y el consumidor.
- **Software as a Service (SaaS)**: La mayor parte de la responsabilidad en el proveedor de servicios en la nube.

![responsabilidad_compartida](https://learn.microsoft.com/es-es/training/wwl-azure/describe-cloud-compute/media/shared-responsibility-b3829bfe.svg)

El modelo de servicio determinará la responsabilidad de cosas como lo siguiente:
- Sistemas operativos.
- Controles de red.
- Aplicaciones.
- Identidad e infraestructura.

## Definición de modelos de nube, incluidos públicos, privados e híbridos

Los modelos en la nube definen el tipo de implementación de recursos en la nube.

- **Nube Publica**: Los servicios son gestionados y proporcionados por un tercero y están disponibles para múltiples clientes.
    
    - Caracteristicas:
        
        - No requiere inversión en infraestructura, ya que el proveedor administra los recursos.
        - Escalabilidad rápida y flexible.
        - Pago por consumo.

- **Nube Privada**: Es un entorno de computación en la nube utilizado exclusivamente por una organización. Se asemeja a un centro de datos tradicional, pero con tecnologías de virtualización y automatización. Tambien la puede hospedar un provedor de servicios de terceros.

    - Características:

        - Ofrece mayor control y seguridad.
        - Puede alojarse en instalaciones propias o en centros de datos externos dedicados.
        - Requiere una inversión inicial alta en infraestructura y mantenimiento.

- **Nube Hibrida**: Combina nubes privadas y públicas, permitiendo una integración fluida entre ambas.

    - Características:

        - Permite utilizar la nube pública para escalar recursos sin comprometer la seguridad de datos críticos.
        - Proporciona flexibilidad al permitir que las empresas gestionen qué aplicaciones se ejecutan en cada entorno.
        - Facilita el cumplimiento normativo al mantener datos sensibles en la nube privada.

- **Nube Múltiple**: Un cuarto escenario común es el uso de múltiples proveedores de nube pública.

    - Características:

        - Permite aprovechar las mejores características de cada proveedor.
        - Evita la dependencia de un solo proveedor (vendor lock-in).
        - Requiere mayor gestión y coordinación de recursos.

## Identificación de los casos de uso adecuados para cada modelo de nube

- **Nube Publica**:
    - Startups y empresas con presupuestos limitados que buscan reducir costos iniciales.
    - Aplicaciones web y móviles que requieren escalabilidad dinámica.
    - Proyectos de desarrollo y pruebas donde se necesiten recursos temporales.

- **Nube Privada**: 
    - Organizaciones con requisitos estrictos de seguridad y cumplimiento (banca, salud, gobierno).
    - Empresas que manejan datos sensibles y necesitan control total sobre la infraestructura.
    - Negocios que requieren personalización extrema de los entornos de TI.

- **Nube Hibrida**: 
    - Permite utilizar la nube pública para escalar recursos sin comprometer la seguridad de datos críticos.
    - Proporciona flexibilidad al permitir que las empresas gestionen qué aplicaciones se ejecutan en cada entorno.
    - Facilita el cumplimiento normativo al mantener datos sensibles en la nube privada.

- **Nube Múltiple**: 
    - Empresas con necesidades de alta disponibilidad y redundancia.
    - Organizaciones que requieren servicios específicos de distintos proveedores.
    - Negocios en proceso de migración entre proveedores de nube.

### Herramientas para la Gestión de Entornos en la Nube

- **Azure Arc**: Azure Arc permite administrar entornos híbridos y de múltiples nubes.

    - Beneficios:

        - Gestión centralizada de recursos en la nube pública, privada y en entornos híbridos.
        - Compatible con servidores físicos, máquinas virtuales y Kubernetes.
        - Facilita la seguridad y el cumplimiento normativo en múltiples entornos.

- **Azure VMware Solution** Azure VMware Solution permite migrar cargas de trabajo VMware a la nube pública de Azure sin necesidad de rediseñar aplicaciones.

    - Beneficios:
    
        - Integración nativa con la infraestructura de Azure.
        - Permite ejecutar entornos VMware en la nube sin cambios estructurales.
        - Facilita la escalabilidad y optimización de costos.

## Descripción del modelo basado en el consumo

Los usuarios finales solo pagan por los recursos que usan. Lo que usan es lo que pagan.

**Ventajas**:
- Sin costes por adelantado. 
- No es necesario comprar ni administrar infraestructuras costosas que es posible que los usuarios no aprovechen del todo. 
- Se puede pagar para obtener recursos adicionales cuando se necesiten. 
- Se puede dejar de pagar por los recursos que ya no se necesiten.

**Capital Expensive (CapEx)**: Inversión previa de dinero, que se podrá deducir a lo largo del tiempo. El costo previo tiene un valor que disminuye con el tiempo. Requiere unos costos financieros previos considerables, así como unos gastos continuos de mantenimiento y soporte técnico.

**Operational Expensive (OpEx)**: Inviersión en servicios o productos que se factura al instante. Este gasto se puede deducir el mismo año que se produce. No hay ningún costo previo, se paga por un servicio o producto a medida que se usa.

## Comparación de los modelos de precios en la nube

Los proveedores de servicios en la nube ofrecen diferentes modelos de precios para adaptarse a las necesidades de sus clientes. Los modelos más comunes son:

| **Modelo de Precio** | **Descripción** | **Ventajas** | **Desventajas** | **Casos de Uso** |
|----------------------|----------------|--------------|----------------|----------------|
| **Pago por uso (Pay-as-you-go, PAYG)** | Se paga únicamente por los recursos consumidos en función del tiempo de uso (por hora, por segundo, etc.). | - Costos flexibles.<br>- No requiere inversión inicial.<br>- Adecuado para cargas de trabajo variables. | - Puede ser costoso a largo plazo si no se optimiza.<br>- Difícil de predecir costos exactos. | Aplicaciones con demanda fluctuante, desarrollo y pruebas, startups con bajo presupuesto inicial. |
| **Reserva de capacidad (Reserved Instances, RI)** | Se compromete a usar ciertos recursos por un período de 1 o 3 años con descuentos sobre la tarifa estándar. | - Costos predecibles.<br>- Descuentos significativos (hasta 75%).<br>- Ideal para cargas de trabajo estables. | - Se paga aunque no se usen los recursos.<br>- Menos flexibilidad si cambian los requerimientos. | Infraestructura estable en producción, aplicaciones de negocio de misión crítica. |
| **Instancias Spot / Precios basados en subasta** | Se compran recursos no utilizados a precios reducidos, pero pueden ser recuperados por el proveedor en cualquier momento. | - Ahorro de hasta 90% en costos.<br>- Útil para cargas de trabajo tolerantes a fallos. | - No hay garantía de disponibilidad.<br>- Las instancias pueden ser interrumpidas. | Procesamiento por lotes, simulaciones, renderizado, machine learning no crítico. |
| **Precios fijos / Suscripción (Enterprise Agreements, EAs)** | Se paga una tarifa fija mensual o anual, con descuentos adicionales por volumen. | - Costos predecibles.<br>- Descuentos significativos para grandes empresas. | - Puede ser costoso si la empresa no usa todos los recursos contratados.<br>- Requiere contrato a largo plazo. | Grandes empresas con necesidades constantes de computación en la nube. |
| **Pago por capacidad (Storage & Data Transfer Pricing)** | Se paga por el almacenamiento utilizado y la transferencia de datos, en función del volumen y la ubicación de los datos. | - Modelo escalable según el uso real.<br>- Se paga solo por lo consumido. | - Transferencias de datos entre regiones pueden ser costosas.<br>- Costos difíciles de predecir sin monitoreo. | Almacenamiento en la nube, backup, análisis de big data. |

### Consideraciones para Elegir un Modelo de Precios
Al seleccionar un modelo de precios en la nube, es importante considerar:

- Frecuencia de uso: Si los recursos se usan de manera intermitente, el modelo de pago por uso es ideal. Si se usan constantemente, una instancia reservada puede ser más económica.
- Presupuesto disponible: Si se requiere previsibilidad en los costos, los precios fijos o las instancias reservadas son mejores opciones.
- Tolerancia a interrupciones: Las instancias Spot son ideales para tareas que pueden ser interrumpidas sin afectar el resultado final.
- Tipo de carga de trabajo: Para almacenamiento y transferencia de datos, se debe monitorear el consumo para evitar costos elevados inesperados.

## Descripción de la informática sin servidor

Se superpone a PaaS y permite que los desarrolladores creen aplicaciones más rápidamente, ya que elimina la necesidad de administrar la infraestructura. el proveedor de servicios en la nube aprovisiona, escala y administra automáticamente la infraestructura necesaria para ejecutar el código tambien ayuda a los equipos a aumentar su productividad y a comercializar los productos con más rapidez. Permite que las organizaciones optimicen mejor los recursos y se centren en la innovación. 

Las arquitecturas sin servidorson altamente escalables y controladas por eventos. Solo usan recursos cuando se produce una función o un desencadenador específico.