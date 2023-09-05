# Proyecto Final

Para visualizar el README.md, favor de presionar **_Ctrl+Shift+V_** aquí.

#### Como parte de mi Tésis realice la primera aplicación web

#### Que administra las "Tareas" de un equipo de trabajo

#### El APP tiene como backed python y como frontend Django y manejador de base de datos de postgreSQL

#### El APP es una aplicación web con Autentificación - Rutas Protegidas - Login - Registro de Usuarios

#### - Una vez que se entra o se "logea" la barra de navegación muestra las opciones de:

#### - Tareas Tearminadas - Tareas Pendientes y Crear Tareas entre otras

#### - Una vez que elige una tarea el usuario puede Modificar, Completar o Eliminar la Tarea o desactivar lo importante.

#### - Al salir (logout) de la APP solo muestra en la barra de navegación 3 opciones: "HOME", "Login" y "Register

### Una opción es vincular el API de "OpenRiverCam" con ésta APP.

El proyecto final se encuentra en: [Repositorio github Ohmicat GO](https://github.com/OhmiCat/ProyectFinal).

#### Descargar el proyecto final:

---

1. Clonar el repositorio en github: git clone https://github.com/OhmiCat/ProyectFinal.gits
2. Crear un archivo venv en la raiz del proyecto (en caso ya va incluido, pero no debe ir):
   - py -3.10 -m venv venv
3. Activar el entorno virtual:
   - ./venv/Scripts/activate
4. Instalar las dependencias:
   - pip install -r requirements.txt
5. Ejecutar las migraciones:
   - python manage.py migrate
6. Crear un superusuario:
   - python manage.py createsuperuser
7. Ejecutar el servidor en el puerto 8001 (se pone el 8001 porque por default utilizan el 8000 y puede ser otro puerto):
   - python manage.py runserver 8001
8. Para ejecutar el proyecto en el navegador puede utilizar cualquiera de las dos ligas:
   - http://127.0.0.1:8001/
   - http://localhost:8001/
