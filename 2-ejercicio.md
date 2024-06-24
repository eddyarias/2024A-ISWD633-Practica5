# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a uan red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba 
# COMPLETAR CON UNA CAPTURA DE PANTALLA LUEGO DE EJECUTAR EL ARCHIVO
![image](https://github.com/eddyarias/2024A-ISWD633-Practica5/assets/94008713/d98e5e76-baa0-481d-9101-b20394ebf152)

# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube
![Anotación 2024-06-24 151323](https://github.com/eddyarias/2024A-ISWD633-Practica5/assets/94008713/f9c827e2-5fa1-45ff-9b5a-0ff1dfd1bfd3)
