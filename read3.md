
# PRÁCTICA Nº1  #
## SISTEMAS EMPRESARIALES ##

___
CARRERA: **INGENIERÍA DE SISTEMAS**

MATERIA: **TECNOLOGÍA EMERGENTES 2**

APELLIDOS Y NOMBRES: **CRUZ QUISPE GABRIEL**

C.I: **7027615**

LUGAR Y FECHA:
___

##1. Explique que son los sistemas empresariales

* Un Sistema de Información Empresarial es un sistema que tiene un
impacto muy importante en el funcionamiento de la organización o
negocio y cuya falla traería graves consecuencias.

* Normalmente que ofrece alta calidad de servicio, gestiona con
grandes volúmenes de datos, disponible de forma continua y es
capaz de soportar cualquier organización grande.

* En el desarrollo de aplicaciones de misión crítica se consideran
	* Plataforma tecnológica
	* Alta disponibilidad
	* Escalabilidad
	* Seguridad
	* Mantenimiento
___
	

##2. Describa cuales son las características más importantes de una aplicación empresarial

* Acceso a bases de datos, usualmente a bases de datos
relacionales
* Operaciones transaccionales, cumple con las propiedades ACID
* Escalables, permiten escalabilidad vertical y horizontal
* Disponibles, idealmente prestan servicios de forma continua
* Seguras, no todos los usuarios acceden con la misma funcionalidad
* Permiten integración con otras tecnologías
* Arquitectura multicapa
___


##3. Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta

___


##4. Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical


##ESCALABILIDAD VERTICAL

* **Escalabilidad vertical**, que se refiere a actualizaciones o modernización de componentes existentes.

	**Ventajas:**
	
	* No implica un gran problema para las aplicaciones, pues todo el cambio es sobre el hardware
	* Es mucho más fácil de implementar que el escalamiento horizontal.
	* Puede ser una solución rápida y económica (compara con modificar el software)
	 
	
	**Desventajas:**
	
	* El crecimiento está limitado por el hardware.
	* Una falla en el servidor implica que la aplicación se detenga.
	* No soporta la Alta disponibilidad.
	* Hacer un upgrade del hardware al máximo pues llegar a ser muy caro, ya que las partes más nuevas suelen ser caras con respecto al rendimiento de un modelo anterior.
	
	![](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-vertical.png)


##ESCALABILIDAD HORIZONTAL


* **Escalabilidad horizontal**, que se refiere a aumentar el número de componentes.

	**Ventajas:**
	
	* El crecimiento es prácticamente infinito, podríamos agregar cuantos servidores sean necesarios
	* Es posible combinarse con el escalamiento vertical.
	* Soporta la alta disponibilidad
	* Si un nodo falla, los demás sigue trabajando.
	* Soporta el balanceo de cargas.
	 
	
	**Desventajas:**
	
	* Requiere de mucho mantenimiento
	* Es difícil de configurar
	* Requiere de grandes cambios en las aplicaciones (si no fueron diseñadas para trabajar en cluster)
	* Requiere de una infraestructura más grande.
	
	![](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-horizontal.png)
___
###5. Que es un servidor Web y que es un servidor de aplicaciones


##SERVIDOR WEB 


Un servidor web o servidor HTTP es un programa informático que procesa una aplicación del lado del servidor, realizando conexiones bidireccionales o unidireccionales y síncronas o asíncronas con el cliente y generando o cediendo una respuesta en cualquier lenguaje o Aplicación del lado del cliente. El código recibido por el cliente es renderizado por un navegador web. Para la transmisión de todos estos datos suele utilizarse algún protocolo. Generalmente se usa el protocolo HTTP para estas comunicaciones, perteneciente a la capa de aplicación del modelo OSI. El término también se emplea para referirse al ordenador.

![](http://culturacion.com/wp-content/uploads/2011/12/figura21-1280x720.jpg)


##SERVIDOR DE APLICACIONES


En informática, se denomina servidor de aplicaciones a un servidor en una red de computadores que ejecuta ciertas aplicaciones.

Usualmente se trata de un dispositivo de software que proporciona servicios de aplicación a las computadoras cliente. Un servidor de aplicaciones generalmente gestiona la mayor parte (o la totalidad) de las funciones de lógica de negociación y de acceso a los datos de las aplicaciones. Los principales beneficios de la aplicación de la tecnología de servidores de aplicación son la centralización y la disminución de la complejidad en el desarrollo de aplicaciones.

![](http://2.bp.blogspot.com/-afANIUkbFJY/USUGCAXgPHI/AAAAAAAAAJ0/TSbT9vVpemQ/s1600/aplicaciones.gif)
___

##6. Con un gráfico explique cómo funciona el protocolo HTTP

![](https://image.slidesharecdn.com/presentacionhttp-https-dns-140922001131-phpapp02/95/presentacion-httphttpsdns-4-638.jpg?cb=1411345623)
___

##7. Explique los elementos importantes de REQUEST en HTTP


Estos son los elementos mas importantes de REQUEST en HTTP:

* **HEAD**, igual que GET pero sin el cuerpo de la respuesta.
* **GET**, pide al servidor que le envíe un recurso.
* **POST**, envía datos al servidor para que sean procesados por el recurso especificado en la petición.
* **PUT**, envía un recurso al servidor.
* **DELETE**, elimina el recurso especificado.
* **TRACE**, pide al servidor mensaje de respuesta, empleado para diagnosticar posibles problemas de conexión.
* **OPTIONS**, pide al servidor que le indique los metodos HTTP que soporta para una URL.
* **CONNECT**, para transformar una conexión a una encriptada.
* **PATCH**, se usa para modificar parcialmente un recurso existente en el servidor.
___


##8. Explique los elementos importantes de RESPONSE en HTTP


Estos son los elementos mas importantes de RESPONSE en HTTP:

* **CODIGO DE ESTADO**, Un código de estado 400 o un código de tres dígitos que comienza con 4xx indica un error de cliente. Cuando el cliente envía una petición al servidor que está dañada o defectuosa, el servidor emite un código de estado 400. Es importante corregir los errores de 4xx en una web para que los usuarios puedan acceder a todo el contenido del sitio.
* **VERSION DE PROTOCOLO**, El protocolo IP establece el sistema de identificación que emplea Internet para enviar información ente dispositivos. 
* **MENSAJE DE ESTADO**, El cuerpo del mensaje contiene el mensaje de solicitud recibido por el servidor.
* **ENCABEZADAS**, Las cabeceras (en inglés headers) HTTP permiten al cliente y al servidor enviar información adicional junto a una petición o respuesta. Una cabecera de petición esta compueta por su nombre (no sensible a las mayusculas) seguido de dos puntos ':', y a continuación su valor (sin saltos de línea). Los espacios en blanco a la izquierda del valor son ignorados.

![](https://mdn.mozillademos.org/files/13691/HTTP_Response.png)
___

##9. Describa con un gráfico la arquitectura Java EE

![](https://camo.githubusercontent.com/aeb3864c8404eda0c595db6b5d9ebf0748b61b05/687474703a2f2f736e61672e67792f3962624e682e6a7067)
___

##10. Explique cuáles son los contenedores, componentes y servicios de Java EE


##CONTENEDORES DE JAVA EE


* Contenedor Web
* Contenedor de negocio (o de EJBs)


##COMPONENTES DE JAVA EE


* Componente cliente: Cliente AWT, Swing, Applet y navegador Web.
* Componente web: Servlet, JSP y JSF.
* Componente de negocio: EJB


##SERVICIOS DE JAVA EE


* De directorio: para la indexación y búsqueda de componentes y recursos
* De despliegue: para poder personalizar los componentes y recursos
* De transaccionalidad: para poder ejecutar distintas acciones en una misma unidad transaccional
* De seguridad: para poder autenticar y autorizar a los usuarios de la aplicación
* De acceso a datos: para facilitar el acceso a Bases de Datos
* De conectividad: para poder acceder fácilmente a distintos EIS
* De mensajería: para poder comunicarse con otros componentes, aplicaciones o EIS
___


##11. Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.


##HTTPSERVLET - METODOS

	init(ServletConfig config): Es el método utilizado para crear una nueva instancia del servlet 
    (análogo al constructor). 
	Este método puede ser sobreescrito para realizar tareas como crear una conexión a una BD que se 
	mantendrá mientras el servlet se mantenga cargado y puede ser utilizada por cada petición. 
	ServletConfig contiene los parámetros de inicialización que entrega el servidor al servlet.

	getServletConfig(): Retorna la configuración dada para la inicialización del servlet.

	service(ServletRequest req, ServletResponse res): Este método es el que se llama cuando se recibe 
	una petición de un cliente y en su implementación normal para HTTP verifica el tipo de solicitud 
	GET, POST, etc. y la redirige a los métodos respectivos. En general no es necesario reimplementar 
	este método.

	destroy(): Este método es llamado por el servidor para indicar que el servlet será destruido. 
	Es llamado sólo una vez y uno debe encargarse de esperar por posibles peticiones en curso.

##HTTPSERVLETREQUEST - METODOS


	getHeader(String name): Permite obtener el valor de los Headers de HTTP con que fue llamado el servlet.
	getCookies(): Retorna un arreglo que contiene todas las cookies que el cliente envía al servlet.
	getSession(): Retorna la sesión en la cual se encuentra el cliente.
##HTTPSERVLETRESPONSE - METODOS


	addCookie(Cookie cookie): Para definir nuevas cookies en el cliente.
	setHeader(String name, String value): Para definir un header HTTP a enviar al cliente.
	sendRedirect(String location): Envía un mensaje al cliente para redireccionar la respuesta a la dirección señalada.

##EJEMPLOS HTTPSERVLET - HTTPSERVLETREQUEST - HTTPSERVLETRESPONSE(TODO EN UN CODIGO)

##SESIONES
##OBTENER UNA SESION


	public class CatalogServlet extends HttpServlet { 

        public void doGet (HttpServletRequest request,
                           HttpServletResponse response)
    	throws ServletException, IOException
        {
            // Get the user's session and shopping cart
	    HttpSession session = request.getSession(true);
            ...
	    out = response.getWriter();
            ...
        }
    }


##ALMACENAR Y OBTENER DATOS DESDE LA SESION


	public class CatalogServlet extends HttpServlet { 

        public void doGet (HttpServletRequest request,
                           HttpServletResponse response)
    	throws ServletException, IOException
        {
            // Get the user's session and shopping cart
	    HttpSession session = request.getSession(true);
	    ShoppingCart cart =
                (ShoppingCart)session.getValue(session.getId());

        // If the user has no cart, create a new one
        if (cart == null) {
            cart = new ShoppingCart();
            session.putValue(session.getId(), cart);
        }
            ...
        }
    }


#


	public void doGet (HttpServletRequest request,
                       HttpServletResponse response)
	throws ServletException, IOException
    {
	HttpSession session = request.getSession(true);
	ShoppingCart cart = (ShoppingCart)session.getValue(session.getId());
        ...
        // Check for pending adds to the shopping cart
        String bookId = request.getParameter("Buy");

        //If the user wants to add a book, add it and print the result
        String bookToAdd = request.getParameter("Buy");
        if (bookToAdd != null) {
            BookDetails book = database.getBookDetails(bookToAdd);

            cart.add(bookToAdd, book);
            out.println("<p><h3>" + ...);
        }
    }


##INVALIDAR LA SESION


	public class ReceiptServlet extends HttpServlet { 

        public void doPost(HttpServletRequest request,
                           HttpServletResponse response)
	    throws ServletException, IOException {

                ...
                scart = (ShoppingCart)session.getValue(session.getId());
                ...
                // Clear out shopping cart by invalidating the session
                session.invalidate();

                // set content type header before accessing the Writer
                response.setContentType("text/html");
                out = response.getWriter();
                ...
        }
    }


##MANEJAR TODOS LOS NAVEGADORES


	public class CatalogServlet extends HttpServlet { 

        public void doGet (HttpServletRequest request,
                           HttpServletResponse response)
	    throws ServletException, IOException
        {
            // Get the user's session and shopping cart, the Writer, etc.
            ...
	    // then write the data of the response
            out.println("<html>" + ...);
            ...
            // Get the catalog and send it, nicely formatted
            BookDetails[] books = database.getBooksSortedByTitle();
            ...
            for(int i=0; i < numBooks; i++) {
                ...
                //Print out info on each book in its own two rows
                out.println("<tr>" + ...
                        "<a href=\"" +
                        response.encodeUrl("/servlet/bookdetails?bookId=" +
                                           bookId) +
                        "\"> <strong>" + books[i].getTitle() +
                        "  </strong></a></td>" + ...
                        "<a href=\"" +
                        response.encodeUrl("/servlet/catalog?Buy=" + bookId)
	                        + "\">   Add to Cart  </a></td></tr>" +

            }
        }
    }
