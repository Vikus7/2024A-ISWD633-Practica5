_Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar._

Mi aprendizaje

Docker Compose ha sido una herramienta invaluable para orquestar y gestionar contenedores de manera eficiente. Mediante la configuración declarativa en archivos YAML como `docker-compose.yaml`, he podido definir servicios como MySQL, WordPress, SonarQube y PostgreSQL de manera estructurada. Aprendí a configurar mapeos de puertos para permitir el acceso desde el host, redes de tipo bridge para la comunicación entre contenedores, y volúmenes para la persistencia de datos, como en PostgreSQL con `postgresql-data`.

Además, comprendí la importancia de los healthchecks para monitorear la salud de los servicios y configurar dependencias entre ellos. Por ejemplo, en WordPress configuré `depends_on` con `condition: service_healthy` para asegurar que el servicio dependiera de un MySQL saludable. Esta experiencia no solo mejoró mi comprensión de Docker como plataforma de contenedores, sino que también aumentó mi productividad al simplificar la administración y despliegue de aplicaciones en entornos de desarrollo y producción.
