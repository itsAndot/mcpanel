# 🖥️ Panel de Control de Usuario para SA:MP
Versión completa y moderna del PCU para MVRDA CITY ROLEPLAY, desarrollado con PHP, HTML, CSS y JavaScript. El panel incluye diferentes características como:

🔐 Login: Página de inicio de sesión para acceder al panel:

INICIO DE SESIÓN:

![Login](https://github.com/itsAndot/mcpanel/blob/main/screenshots/nuevoinicio.png)

🏠 Página Principal: Muestra información detallada del personaje (Nivel, Dinero, Dinero Bancario, Propiedades, Horas Jugadas, Número de Teléfono, Nacionalidad, Veces Arrestado). Con 2 estilos disponibles:

DASHBOARD:

![Index](https://github.com/itsAndot/mcpanel/blob/main/screenshots/principalnuevo.png)


🆔 DNI del Personaje: Recreación del documento de identidad del personaje. 
- Se genera un ID único que sigue una lógica que identifica el documento.
- Una foto del personaje según su skin.
- Dependiendo del camino de vida elegido al registrarse en el servidor, la nacionalidad será diferente (Corporativo será de Liberty City, Callejero de Los Santos y Nómada de Vice City).

Para poder obtener el documento, la primera vez se debe entrar al panel y presionar en "Solicitar cita". Una vez realizado esto, los usuarios accederán al servidor y se dirigirán al Ayuntamiento dónde podrán obtener su DNI (si no se ha solicitado una cita previamente en el PCU al llegar al Ayuntamiento no podrán obtenerlo), una vez obtenido ya aparecerá en el panel con todos sus datos (además de poder utilizarlo dentro del juego, obviamente).

![DNI](https://github.com/itsAndot/mcpanel/blob/main/screenshots/dni2.png)

👥 Información de la Banda: Muestra detalles sobre la banda a la que pertenece el usuario, incluyendo:
- Lista de miembros
- Opción para abandonar la banda

![Banda](https://github.com/itsAndot/mcpanel/blob/main/screenshots/banda.png)

🧰 Inventario: Muestra los objetos que tiene el usuario en su inventario.

🔍 Sistema de búsqueda de usuario: Muestra información sobre un usuario, estilo red social.

![Buscar](https://github.com/itsAndot/mcpanel/blob/main/screenshots/buscar.png)

🔧 Housekeeping/Panel administrativo: En caso de tener un rango Staff, aparece la opción para acceder a la zona administrativa. Requiere introducir una contraseña especial administrativa.

![Barra](https://github.com/itsAndot/mcpanel/blob/main/screenshots/barrahk.png)

![Acceso](https://github.com/itsAndot/mcpanel/blob/main/screenshots/accesohk.png)

El panel es fácil de adaptar a otras gamemodes así como la creación de nuevos apartados, requiere conocimiento básico en PHP y HTML.
