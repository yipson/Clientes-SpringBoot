# Control de saldo de clientes con Spring Boot


Software para el control de saldos e informacion de clientes

Alcance del sofware: permite realizar el login (ingreso) con dos diferentes roles, administrador y usuario. El rol administrador tiene permisos para realizar el CRUD (Create - Read - Update - Delete) a cada registro mientras que el rol de usuario unicamente podra hacer consulta de estos registros asi como del saldo  total y el numero total de clientes registrados. Los botones y links encargados de accionar opciones a las cuales no podra ingresar el rol usuario tampoco seran visibles para este rol.

El software cuenta con encripcion de contraseñas del lado del servidor, asi como validacion para evitar el envio de informacion vacia en los formularios (a excepcion de el numero telefonico) y validacion de formato correcto en el email. Tambien cuenta con la opcion de visualizar la pagina en dos idiomas diferentes, ingles y español, por defecto se mostrara en español pero se puede realizar el cambio en el pie de pagina de cualquier ventana.

El Software fue contruido siguiendo los parametros del patron de diseño MVC (Model View Controller), el cual evita que la vista y el modelo se conecten directamente, asi que el controlador se encarga de recibir todas las peticiones hechas por el cliente.

Tambien se agrego un backup de la base de datos que se usó, este se llama DBclientes, es un archivo comprimido

Tecnologias y herramientas: 
- Spring boot
- Java
- MySQL
- Workbench
- Maven
- Bootstrap
- Netbeans