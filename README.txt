Manual de Instalación

----------------------------------------
Autor:
Sisops. Salón 8:30 a.m. Equipo 03.


Fecha:
06 de Mayo 2026
----------------------------------------

++++++++++++++++++++++++++++++++++++++++
VISUAL OS LAB - URL FUNCIONAL 
++++++++++++++++++++++++++++++++++++++++


El proyecto se encuentra en: 
https://ubiquitous.udem.edu/~587823_user/reportes/simulador/index.html 


++++++++++++++++++++++++++++++++++++++++
VISUAL OS LAB - MANUAL DE INSTALACIÓN
++++++++++++++++++++++++++++++++++++++++


Descripción:
------------
Este proyecto consiste en un simulador desarrollado con archivos HTML.
No requiere instalación de dependencias ni compilación.


El sistema puede ejecutarse de dos formas:
1) Localmente (en tu computadora)
2) En un servidor web (recomendado: Ubiquitous)


----------------------------------------
1. EJECUCIÓN LOCAL
----------------------------------------


Pasos:
1. Descargar el archivo "simulador.zip".
2. Extraer el contenido en cualquier carpeta.
3. Abrir la carpeta extraída.
4. Dar doble clic al archivo principal (ej. index.html).


----------------------------------------
2. INSTALACIÓN EN UBIQUITOUS 
----------------------------------------


Requisitos:
- Tener acceso a Ubiquitous (UDEM)
- Tener instalado Cyberduck


Pasos:


1. Abrir Cyberduck.
2. Crear una nueva conexión:
   - Protocolo: SFTP
   - Servidor: ubiquitous.udem.edu
   - Usuario y contraseña: proporcionados por UDEM


3. Conectarse al servidor.


4. Navegar a la carpeta pública:
   /var/www/html/  o  public_html/ (dependiendo configuración)


5. Subir la carpeta descomprimida del proyecto.


6. Asegurarse de que el archivo principal se llame:
   index.html


7. Abrir el proyecto en el navegador usando:
   https://ubiquitous.udem.edu/~tu_usuario/


----------------------------------------
3. ESTRUCTURA DEL PROYECTO
----------------------------------------


/simulador/
│
├── index.html
├── scheduling.html
├── paginacion.html
├── replacement.html
├── threads.html
├── multicore.html
└── comparacion.html

----------------------------------------
4. RECOMENDACIONES
----------------------------------------


- Usar Google Chrome o Microsoft Edge.
- No modificar nombres de archivos sin actualizar referencias.
- Mantener todos los archivos en la misma estructura.


----------------------------------------
5. SOLUCIÓN DE PROBLEMAS
----------------------------------------


Problema: No carga el simulador
Solución:
- Verificar que index.html esté en la raíz


----------------------------------------
Autor:
Sisops. Salón 8:30 a.m. Equipo 03.


Fecha:
06 de Mayo 2026
----------------------------------------

----------------------------------------
