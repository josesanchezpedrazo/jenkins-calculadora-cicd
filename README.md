# Repo para EIEC - DevOps - UNIR

Este repositorio incluye un proyecto sencillo para demostrar el uso de SonarQube y Jenkins. El objetivo es que el alumno entienda el concepto de análisis estático, de Jenkinsfile y las fases del pipeline, por lo que el código y la estructura del proyecto son especialmente sencillos. Salvo por el código del Jenkinsfile y la configuración de Sonar, el código es igual al de https://github.com/srayuso/unir-test. El repositorio https://github.com/srayuso/unir-build-tools contiene comandos para facilitar el despliegue de Jenkins en local.

El único requisito es tener Docker instalado. Los comandos del Makefile funcionarán en MacOS y Linux. En caso de usar Windows, será necesario adaptarlos o ejecutarlos en una máquina virtual Linux con Docker instalado.

## Resumen 

Este repositorio tiene un proyecto python que es una calculadora que expone un API en el puerto localhost:5000 y una parte web expuesta en el puerto localhost:80 compuesta por un bastion/nginx muy pequeñito que sirve un fichero html con JS. La UI llama a la API para solicitar ejecución y mostrar el resultado.

El proyecto esta dockerizado.
