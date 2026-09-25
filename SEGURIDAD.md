# Seguridad en Cloud

La seguridad en la nube no solo son buenas practicas y tecnología avanzada, sino una sinergia de esfuerzos entre clientes y proveedores de servicios en la nube, es una colaboración estratégica vital para un resguardo de los ecosistemas de la nube de una manera segura, mientras los proveedores se encargan de la infraestructura de seguridad, los proveedores deben de gestionar la seguridad de datos y apps

para esto existen modelos de responsabilidad compartida de los proveedores de servicios de la nube; los cuales son:

- **ENFOQUE DE RESPONSABILIDAD EN IaaS**
El proveedor de a nube es el responsable de la infraestructura física y la conectividad a internet, así como su gestión mayoritaria de la carga de trabajo así como S.O, parches , configuración, y muchos controles de seguridad este modelo nos ofrece la máxima flexibilidad y la mayor responsabilidad operativa

- **ENFOQUE DE RESPONSABILIDAD en PaaS**
el proveedor gestiona la infraestructura física y los componentes de la plataforma así cómo Sistemas Operativos ,middleware y runtimes gestionados, te centras en el código de tu app, los datos y los controles de acceso, estas dependen de la configuración del servicio, se comparten algunos ajustes de la red así como la seguridad de las apps

- **Enfoque de responsabilidad de SaaS**
El proveedor de la nube gestiona casi toda la pila de apps, incluyendo infra, plataforma y mantenimiento de apps, principalmente gestionando tus datos, la identidad y la configuración de acceso, así como la postura de acceso al dispositivo, esta tiene menor carga para los clientes

## Principios de Confidencialidad, Integridad y Disponibilidad (CIA)

La triada (CIA) es un modelo fundamental de seguridad de la información que asegura que los datos sean confidenciales, íntegros y disponibles para los usuarios autorizados.

- **CONFIENCIALIDAD**
Nos garantiza que la información solo sea accesible para personas autorizadas evitando divulgaciones no deseadas o accesos indebidos; Las medidas que se usan son

   - Control de acceso
   - Cifrado de datos
   - Políticas de privacidad

- **INTEGRIDAD**
Nos asegura que los datos sean exactos, completos y no fueran alterados de manera no autorizada, crucial  para la información confiable y útil; Las medidas mas comunes son:

   - Hashing y firmas digitales
   - Control de Versiones
   - Sistemas de detección de intrusiones

- **DISPONIBILIDAD**

Nos garantiza que los sistemas y datos estén accesibles para los usuarios autorizados cuando los necesiten; esto protege los recursos frente a fallos de hardware, interrupciones de software, problemas de red o ataques (DoS); Las estrategias utilizadas incluyen:

   - Redundancia y respaldo de sistemas
   - Monitoreo y mantenimiento de infraestructura
   - Planes de continuidad y recuperación ante desastres.

La importancia de la triada CIA nos proporciona un marco para analizar riesgos, diseño de controles de seguridad y proteger activos digitales.

# Gestión de Identidad y Acceso (IAM)

IAM proporciona acceso seguro a recursos de la empresa como (correos electrónicos, B.D y APPS) a entidades verificadas, idealmente con un mínimo de interferencia, el objetico es administrar el acceso para un control adecuado para los trabajadores y se deniegue la entrada a personas mal intencionadas

Las necesidades de acceso va mas alla de las de los empleado que trabajan en los equipos de la empresa.
esto incluye a contratistas, proveedores, partners empresariales y personas que trabajan en dispositivos personales, la IAM asegura de que cada persona tenga el acceso al nivel correspondiente a su posición en a empresa en el momento y equipo adecuado.

## Protección de datos y privacidad en Cloud

Es crucial para las organizaciones que utilizan los servicios de Cloud, esto incluye la gestión de datos sensibles, así mismo la seguridad de la información y el cumplimiento de la regulaciones de protección de datos, con eso las empresas deben de estipular y ordenar las políticas de datos, métodos de protección y herramientas técnicas para garantizar una seguridad de datos compleja y eficiente.

## Amenazas y riesgos comunes en entornos de Cloud.

Las principales amenazas en entornos Cloud son las siguientes:

- **Errores de configuración** 

Puertos abiertos innecesarios o funciones con privilegios excesivos son responsables del 80% de los incidentes en Cloud

- **Credenciales expuestas o mal   gestionadas**

Claves API subidas a repositorios públicos, tokens filtrados o un mal uso de IAM

- **Escalada de privilegios**

Atacante de pueden aprovechar funciones mal segmentadas obtener permisos adicionales incrementando el riesgo de comprometer datos critico

- **Amenazas Internas**

Personal con acceso legitimo abusan de sus privilegios, exponiendo, modificando o destruyendo datos confidenciales (**estas pueden pasar desapercibidas durante largos periodos **)

- **IaC mal protegida**
Plantillas de IaC mal gestionadas las cueles pueden introducir vulnerabilidades y facilitan la creación de entornos que ejecutan código desde fuentes externas

## Seguridad en Microsoft Azure 

Azure implementa controles de seguridad predeterminadas que protegen los recursos desde su despliegue, estos incluyen:

- **Cifrado de datos en reposo**
  - Azure Storage
  - SQL Database

- **Protección contra ataques DDoS**
- **Autenticación y Autorización**
  - Microsoft Entra ID

- **Zero Trust**
  - Segmentación de redes
  - Cifrado de Tráfico 
  - Refuerzo de seguridad de claves criptográficas mediante hardware especializado

## Buenas prácticas de seguridad en Cloud

Estas deben abarcar la adopción de medidas necesarias para monitorear y proteger los entornos de la nube, estas son:

- **Comprensión del modelo de responsabilidad compartida**
- **Educación a su empleados y fomentación sobre seguridad en la nube**
- **Actualizaciones y parches regulares**
- **Prevención de pérdida de datos**
- **Planificación de repuestas a incidentes**
- **Cumplimiento de Zero Trust**
- **WAF (Web Application Firewall) y CNAPP (Cloud-Native Application Protection Platform)**
- **Soluciones IAM y mejora de cifrado**
- **Uso de Nubes Privadas Virtuales (VPC) y Grupos de Seguridad de red (NSG)**
  -Aplicación de listas de control de acceso (ACL)
- **Escaneo de vulnerabilidades**
- **Marco de gobernanza en la nube**

## Cumplimiento normativo y gobernanza

Se deben cumplir estándares técnicos y requisitos regulatorios. A medida que estos evolucionan, la auditoría basada en la nube ayuda a detectar recursos que no cumplen con la línea base establecida y proporciona estrategias de mitigación. Esto depende del modelo operativo y se fortalece mediante la aplicación de parches y actualizaciones de software.

## Referencias
-https://blog.netdatanetworks.com/fundamentos-de-la-seguridad-en-la-nube
-https://www.bing.com/search?q=que+son+los+Gestión+de+identidades+y+accesos+(IAM).&cvid=87a1cc749f6a432e8f5948d22568c52d&gs_lcrp=EgRlZGdlKgYIABBFGDkyBggAEEUYOTIICAEQ6QcY_FUyBwgCEOsHGEDSAQg3Mzc5ajBqOagCCLACAQ&FORM=ANAB01&PC=U531&ntref=1
-https://www.sentinelone.com/es/cybersecurity-101/cloud-security/cloud-security-best-practices/
