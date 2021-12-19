# Uso de S3 & cloudfront.

# Manos a la obra
## Desde el servicio S3
1) Crear un bucket con un nombre a elección de ACCESSO PUBLICO!
2) Crear una carpeta dentro del bucket
3) Subir el archivo index.html dentro de la carpeta que esta dentro del bucket

## Desde el servicio cloudfront
4) Crear un OAI (Origin Access Identify)
5) Crear una distribución que referencia a la OAI anterior (tener en cuenta activar las politicas de bucket y establecer el default root object)
6) Realizar las pruebas y ajustes requeridos

## Links de interes




