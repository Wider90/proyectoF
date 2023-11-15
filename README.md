# Instalar MOODLE y creacion de un curso

## Moodle
- Instalación con docker-compose 

## Usuarios y Contraseñas que se deben cambiar en el archivo docker-compose.yml
- MYSQL_ROOT_PASSWORD: password
- MYSQL_PASSWORD: wordpress


### Correr localmente usando docker

1. Clonar el repositorio al directorio local de instalación
git clone https://github.com/Wider90/proyectoF.git

2. Para correr los contenedores

$cd proyectoF

$docker compose up

3. Para detener los contenedores

$docker compose down


# Paso 1) Correr MOODLE 

- http://localhost:8000/
- 

![Captura1](imgs/Captura1.png)

# Paso 2)Login 

- Presionar el botón de Log In e introducir las credenciales de administradr:
- Usuario: user
- Contraseña: bitnami

![Captura2](imgs/Captura2.png)

-Con esto nos debe aparecer la siguiente pantalla

![Captura3](imgs/Captura3.png)

# Paso 3) Creación de un curso

- Para la creación de un curso necesitamos dirigirnos al menú site administration.

![Captura4](imgs/Captura4.png)

- Posteriormente ir al submenu Courses y dar click en Add a new course

![Captura5](imgs/Captura5.png)

-Se nos va a desplegar un formulario que lo llenaremos con la información de nuestro curso

![Captura6](imgs/Captura6.png)

-Por ultimo vamos clickear el botón desplegar e iremos al menú "Mis cursos"

![Captura7](imgs/Captura7.png)

# Paso 4) Inscribirnos al curso

- Lo primero sera entrar a nuestro curso

![Captura8](imgs/Captura8)
  
- Vamos ir al menu particpantes

![Captura9](imgs/Captura9.png)

- Ahora vamos a dar click en el botón enrol users

![Captura10](imgs/Captura10)

-Agregamos a los usuarios y clickeamos enrol users y podremos ver como fueron agregados los participantes.

![Captura11](imgs/Captura11)
