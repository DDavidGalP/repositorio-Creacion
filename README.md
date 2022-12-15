# MESA DE AYUDA API
Mesa de Ayuda API para enyoi

# Guia de instalacion
Guia de instalacion de servicio Rest de enyoi Api Mesa de Ayuda. Es necesario tener encuenta que esta aplicacion es totalmente para pruebas por lo cual las configuraciones y la guia aqui dada es para una instalacion local o en un servidor. se dejara un despliegue montado para despligue local de acuerdo al siguiente link para su respectiva prueba [enlace](http://localhost:8080/api-notas/swagger-ui/index.html#/) se encontrara la documentacion de la API.

## 1. Instalacion de docker
ir al sitio web de [descarga](https://www.docker.com/get-started) y seguir los pasos para instalar docker


## 2. Instalar imagen de mysql
antes de realizar la instalacion de la imagen de mysql verificar que se tenga instalado docker:
```bash
docker version
```
en caso de no tenerlo regresar al paso 1. 
continuamos con la instalacion de la imagen:
```bash
docker pull mysql
```

## 3. Instalar e iniciar contenedor: 
procedemos a instalar el contenedor

  1- descargamos los scripts con los que se crean los contenedores con las bases de datos desde el enlace donde estara el repositorio con las instrucciones({Creacion Contenedor Docker} --> https://github.com/DDavidGalP/repositorio-Creacion.git)
    
  2- Deben seguir las indicaciones del archivo para crear el contenedor y dicha base de Datos

## 4. Ejecutar API
Posterior a la descarga del contenido de la api ubicada en el repositorio de git. deberan descomprimir dicho archivo, y dentro de la raiz principal de la aplicacion dar clic derecho, abrir con IntelliJ IDEA Community Edition y proceder a ejecutat la Api, y abrir el link de prieba (http://localhost:8080/api-notas/swagger-ui/index.html#/)
Ejecutar el siguiente comando en la consola estando en la raiz principal de la aplicacion:
```



