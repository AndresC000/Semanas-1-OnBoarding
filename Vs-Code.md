## ¿Qué es VS CODE?
Es un editor de código fuente potente y versátil que permite a los desarrolladores escribir, depurar y gestionar proyectos de software de manera eficiente; la diferencia entre Visual Studio IDE, VS Code es mas ligero, la cual esta orientada a ofrecer una experiencia ágil de edición de código compatible con **WINDOWS**, **macOS** y **Linux**

## Características principales

- **Autocompletado Inteligente**
- **Depuración Integrada**
- **Control de versiones GIT**
- **Extensiones y personalización**
- **Colaboración en tiempo real** 

## Integración con Microsoft Azure

Mediante extensiones oficiales de Azure, VS Code permite:

Administrar recursos de Azure.
Desplegar aplicaciones.
Conectarse a servicios cloud.
Ejecutar comandos de Azure CLI.
Desarrollar y validar archivos Bicep y ARM Templates.

Esto facilita la administración y automatización de recursos directamente desde el editor.

 **NOTA:**
 	-Archivos BICEP y ARM templates:
	Estas son herramientas de infraestructura como código utilizadas en Azure para definir y gestionar recursos de manera declarativa.
	
	-BICEP es un lenguaje de dominio especifico (DSL) la cual simplifica la creación de pantillas ARM (JSON) la cual se despliega mediante el mismo motor que las plantillas ARM.
	-ARM Templates nos permite definir los recursos, dependencias, parámetros y configuraciones directamente por Azure para realizar despliegues.
**FIN DE LA NOTA**

## Uso de extensiones para IaC

Las extensiones permiten convertir VS Code en un entorno especializado para Infraestructura como Código.

Algunas de las más utilizadas son:

Bicep Extension
Azure Resource Manager Tools
Microsoft Terraform
Azure Tools Extension Pack

Estas extensiones agregan validación, autocompletado, documentación contextual y gestión de recursos Cloud.

## Azure CLI dentro de VS Code

VS Code permite utilizar Azure CLI desde su terminal integrada para:

- Crear recursos.
- Administrar máquinas virtuales.
- Configurar redes.
- Automatizar tareas administrativas.
- Ejecutar scripts de despliegue.

Esto permite trabajar desde un único entorno sin cambiar entre múltiples herramientas

## Control de versiones con Git y GitHub

VS Code incorpora herramientas nativas para Git que permiten:

- Crear commits.
- Gestionar ramas.
- Resolver conflictos.
- Sincronizar cambios con GitHub.
- Revisar historial de cambios.

Estas capacidades facilitan la colaboración y el seguimiento de configuraciones de infraestructura.

## Beneficios de utilizar VS Code para IaC

- Automatización de despliegues.
- Reducción de errores manuales.
- Mayor consistencia entre entornos.
- Administración centralizada de configuraciones.
- Integración con herramientas Cloud.
- Mejor colaboración mediante Git y GitHub.
- Mayor productividad gracias a extensiones especializadas.

## Conclusión

Visual Studio Code se ha consolidado como una de las herramientas más importantes para el desarrollo y la administración de Infraestructura como Código (IaC) en entornos Cloud. Gracias a su facilidad de uso, amplia compatibilidad y ecosistema de extensiones, permite a los usuarios gestionar recursos, automatizar despliegues y mantener configuraciones de infraestructura de manera eficiente.

## Referencias

- https://learn.microsoft.com/en-us/azure/templates/
- https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-bicep
- https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureterraform
- https://code.visualstudio.com/docs
- https://developer.hashicorp.com/terraforM
