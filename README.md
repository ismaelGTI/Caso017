# Caso017

## Crear un repositorio en GitHub para almacenar el código fuente de la aplicación de TuEmpresa (puedes reutilizar el de talleres anteriores).

Crear dos custom actions:
InfraConfig: Contendrá un echo “Configurando la infraestructura necesaria para la aplicación”
Tests: Recibira dos parámetros y tendrá un echo “Ejecutando tests param1 y param2”
Crear un workflow en el repositorio de la aplicación con los siguientes pasos:
InfraConfig(la action anteriormente desarrollada).
Build (un echo building).
Deploy (un echo Deploying).
Test (la action anteriormente desarrollada a la que se le pasaran los dos parámetros necesarios).
