# 1. Comprensión de Docker Compose
Antes de la práctica, tenía una comprensión básica de Docker y sus conceptos fundamentales. Después de completar el ejercicio, mi conocimiento sobre Docker Compose se ha profundizado significativamente. Ahora entiendo cómo definir y gestionar aplicaciones multi-contenedor utilizando un archivo compose.yaml.

# 2. Estructura del Archivo YAML
La práctica me permitió aprender a crear un archivo YAML correctamente, usando la indentación adecuada y separando claves y valores de manera precisa. Este conocimiento es esencial para configurar correctamente los servicios en Docker Compose.

# 3. Configuración de Servicios
Aprendí a configurar múltiples servicios (contenedores) dentro de un archivo compose.yaml, específicamente mysql-service y wordpress-service. Ahora puedo definir las imágenes de Docker, los volúmenes, las redes, y las variables de entorno necesarias para cada servicio.

# 4. Mapeo de Puertos
Comprendí cómo mapear puertos entre el host y el contenedor, lo cual es crucial para acceder a servicios específicos desde el host. En este ejercicio, se configuró el mapeo de puertos para WordPress.

# 5. Healthchecks
Aprendí a implementar healthchecks para asegurarme de que los servicios estén funcionando correctamente antes de iniciar otros servicios que dependan de ellos. Esto incluye el uso de comandos específicos para verificar la salud de los servicios mysql-service y wordpress-service.

# Problemas Solucionados
Durante la práctica, enfrenté un problema relacionado con la falta de privilegios debido a ejecutar sin administrador.
