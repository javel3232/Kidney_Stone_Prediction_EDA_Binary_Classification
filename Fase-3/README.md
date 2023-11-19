# Instrucciones para ejecutar Fase-3

**1**. Primero que todo debemos tener instalado Docker y Docker Compose  y asegurase de que este corriendo o ejecutandose en nuestro ordenador.

**2**. Clonamos la carpeta Fase-3 en nuestro Id.

**3**.Una ves estando en el proyecto abrimos una terminal y ejecutamos el siguiente comando: **docker-compose up --build** ,este comando se utiliza para construir y levantar los servicios definidos en el archivo **docker-compose.yml** que se encuentra en el proyecto,este comando es útil cuando queremos realizar cambios en el código fuente o en la configuración del contenedor sin tener que volver a crear la imagen,en caso de realizar un cambio simplemete ejecutamos **docker-compose up** para levantar el servicio de nuevo, ya que asegura que las imágenes se reconstruyan antes de iniciar los servicios.

