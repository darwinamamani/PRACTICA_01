<center>
#PRACTICA N° 1
##SISTEMAS EMPRESARIALES
Carrera:    INGENIERIA DE SISTEMAS 

Materia:    EMERGENTES II

Apellido y Nombre:  MAMANI ARUQUIPA DARWIN

C.I:    9138437 L.P.

Lugar y fecha: EL ALTO 12/08/2019
</center>
 

###1) ¿EXPLIQUE QUE SON LOS SISTEMAS EMPRESARIALES?
**Es generalmente cualquier tipo de sistema de computación que es de** *clase Enterprise* **esto significa normal mente que ofrece alta calidad de servicio.**
###2) DESCRIBA CUALES SON CARACTERISTICAS MAS IMPORTANTES DE UNA APLICACIÓN EMPRESARIAL.
-Disponibilidad
-Capacidad
-Extensibilidad
-Flexibilidad
-Manejabilidad
-Rendimiento
-Confiabilidad
-Reusabilidad
-Escalabilidad
-Seguridad
-Validez
###3) INVESTIGUE Y PROPONGA 5 INSTITUCIONES QUE REQUIERAN APLICACIONES DE MISION CRITICA. JUSTIFIQUE SU RESPUESTA.
-*PLATAFORMA TECNILOGICA* ***Es importante considerar donde se va a ejecutar nuestra aplicación, sobre qué sistema operativo, con cuales base de datos necesita relacionarse y que leguaje es el que nos conviene.***

-*FLEXIBILIDAD* ***Debemos tener en claro que, a nivel tecnológico usa palabras de Heráclito lo único constate es el cambio. Por ello, debemos considerar que la decisión que tomemos respecto a la decisión que tomemos en este momento respecto a la plataforma, beses de datos, sistemas operativos y demás.***
###4) EXPLIQUE CUALES SON LAS DIFERENCIAS ENTRE LA ESCABILIDAD HORIZONTAL Y ESCABILIDAD VERTICAL.
 -**ESCABILIDAD HORIZONTAL:** ***Es el mas potente, pero también el más complicado.*** *este modelo implica tener varios servidores (conocidos como nodos) trabajando como un todo* ***se crea una red de servidores conocida como*** *Clúster* ***con la finalidad de repartirse el trabajo entre todos nodos del clúster.***
***Para que el escalamiento horizontal funcione deberá existir un servidor primario desde el cual se administra el clúster. También deberá tener un software que permita ingresar al clúster.***

-**ESCALABILIDAD VERTICAL:** ***Este es el mas simple, pues significa*** *crecer el hardware de uno de los nodos, es decir aumentar el hardware por uno más potente, como disco duro, memoria, procesador, etc. Pero también puede ser la migración completa del hardware por uno mas potente.* *el esfuerzo de este crecimiento es mínimo* ***pues no tiene recuperaciones en el software, ya que solo será respaldar y migrar los sistemas al nuevo hardware.  
La realidad es que este tipo de escalamiento tiene algunos aspectos negativos, ya que nuestros*** *crecimientos están ligado al hardware,* ***y este; tarde o temprano tendrá un límite, llegará el momento de que tengamos el mejor procesador, el mejor disco duro, la mejor memoria.*** 
###5) QUE ES UN SERVIDOR WEB Y QUE ES UN SERVIDOR DE APLICACIÓNES##
 -Servidor web ***es un programa informático que procesa una aplicación del lado del servidor realizando conexiones bidireccionales y/o unidireccionales y síncronas o asíncronas con el cliente generando o cediendo una respuesta en cualquier lenguaje.***

-*Servidor de aplicación* ***en informática es una red de computadores que ejecuta ciertas aplicaciones. Usualmente se trata de un dispositivo de software que proporciona servicios de aplicación a las computadoras cliente. Un servidor de aplicación generalmente gestiona la mayor parte *(o la totalidad)* de las funciones de lógica de negocio   y acceso a los datos de la aplicación.***
###6) CON UN GRAFICO EXPLIQUE COMO FUNCIONA EL PROTOCOLO HTTP

[PRESIONE PARA VER LA IMAGEN](https://www.google.com/imgres?imgurl=https%3A%2F%2Fslideplayer.es%2Fslide%2F1701339%2F7%2Fimages%2F5%2FComo%2Bfunciona%2BProtocolo%2Bhttp%2BDame%2Bel%2BCliente%2Barchivo%2Bx%2BAqu%25C3%25AD%2Best%25C3%25A1.jpg&imgrefurl=https%3A%2F%2Fslideplayer.es%2Fslide%2F1701339%2F&docid=6zpboSdBkmMEuM&tbnid=i8AkTxpGx3tzsM%3A&vet=10ahUKEwjmitvkm_7jAhUHvFkKHUANB6sQMwhgKBAwEA..i&w=960&h=720&bih=969&biw=1920&q=COMO%20FUNCIONA%20EL%20PROTOCOLO%20DE%20HTTP&ved=0ahUKEwjmitvkm_7jAhUHvFkKHUANB6sQMwhgKBAwEA&iact=mrc&uact=8)

###7) EXPLIQUE LOS ELEMETOS IMPORTANTES DE REQUEST EN HTTP
-*Certifícate* ***contiene el certificado completo. Se recibe en binario.***

-*SerialNumber* ***contiene el numero de serie del certificado.***

-*Subject* ***información sobre el sujeto certificado.***

-*Issuer* ***información sobre el emisor del certificado.***

-*ValidFrom* ***fecha desde la que es valido el certificado.***

-*ValidUntil* ***fecha de expiración del certificado.***

###8) EXPLIQUE LOS ELEMENTOS IMPORTANTES DE RESPONSE EN HTTP##
####-Response.Buffe =  false | true

***La propiedad Response.Buffer sirve para sirve para intervenir en el proceso de buffering. Si el valor de buffer es*** *true*, ***el servidor enviara el contenido del buffer a la salida, pero si el buffer es*** *false*, ***el proceso de buffer no realizara. Esto significa que no es posible cambiar la propiedad después de que le servidor haya enviado a la respuesta.***

####-Response.CacheControl = “Public” | “Private”

Esta propiedad permite a los servidores proxy guardar o no en su cache una copia de las respuestas  ASP.

-*Servidor proxy* ***es una maquina que se instala en algunas redes locales  (también llamadas intranest), función consiste en guardar en sus discos una copia de todas las paginas web que han visitado los navegadores de esa red local.***

-*Servidor Cache* ***es un navegador instalado que tiene dos caches: en memoria y en disco. Y es configurable por el usuario el tamaño de ambas.***
###9) DESCRIBA CON UN GRAFICO LA ARQUITECTURA JAVA EE
-*Client-tier:* ***Corre sobre la maquina cliente.***

-*Web-tier:* ***Corre  en el servidor EE.***

-*Business-tier:* ***corre en el servidor EE.***

-*Enterprise Information System (EIS) – tier:* ***Corre sobre el servidor EIS.***
 

###10) EXPLIQUE CUALES SON LOS CONTENEDORES, COMPONENTES Y SERVICIOS DE JAVA EE.

-*Java EE Server:* ***La porción de tiempo de ejecución de un protocolo java EE. Provee los contenedores web y de ejb.***

-*Contenedor EJB:* ***Maneja la ejecución de los Enterprise beans.***

-*Contenedor Web:* ***Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones.***

-*Contenedor Applet:* ***Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste un servidor de aplicación.***


##11) ENVESTIGUE LOS METODOS MAS UTILIZADOS DE LAS CLASES HTTPSERVLET, HTTPSERVLETREQUEST Y HTTPSERVLETRESPONSE, Y PARA CADA UNO DE LOS METODOS MUESTRE UN EJEMPLO.
###METODO DE LA CLASE HTTPSERVLET

[PRESIONE PARA VER LA IMAGEN](https://www.google.com/imgres?imgurl=https%3A%2F%2Flh3.googleusercontent.com%2F-_VAAXXmSKuc%2FWWTMi1RpW8I%2FAAAAAAAADOI%2FX51xa353aGIwj3BHbTsib0EDVLDCCQvZgCHMYCw%2Ffuncionamiento-de-los-servlet-java_t%3Fimgmax%3D800&imgrefurl=http%3A%2F%2Facodigo.blogspot.com%2F2017%2F07%2Fservlet-java-tutorial-basico.html&docid=8_k6iIuAQB0D7M&tbnid=kjYVaxIkzwhbcM%3A&vet=10ahUKEwjNiNDTnv7jAhVEnlkKHQBkDqcQMwhnKBswGw..i&w=762&h=382&bih=920&biw=1920&q=METODO%20DE%20LA%20CLASE%20HTTPSERVLET&ved=0ahUKEwjNiNDTnv7jAhVEnlkKHQBkDqcQMwhnKBswGw&iact=mrc&uact=8)

-*INIT(SERVLETCONFIG CONFIG):* ***Es el método utilizado para crear una nueva instancia del servlet (análogo al constructor).*** 

-*EL CICLO DE LA VIDA:* ***Cada servlet tiene un siclo de vida:***

-Un servidor carga e inicializa el servlet.

-El servlet maneja cero o mas peticiones de cliente.

-El servidor elimina el servlet.


-*GETSERVLETCONFING():* ***Retorna la configuración dada para la inicialización del servlet.***

-*SERVICE (SERVLETREQUEST REQ, SERVLETRESPOSE RES)* ***Este método es el que se llama cuando se recibe una petición de un cliente y en su implementación normal para http verifica el tipo de solicitud GET, POST, etc. Y la redirige a los métodos respectivos. En general no es necesario reimplementar este método.***

-*DESTROY():* ***Este método es llamado por el servidor para indicar el servlet será destruido. Es llamado solo una vez y uno debe encargarse de esperar por posibles peticiones en curso.***

###METODO DE LA CLASE HTTPSERVLETREQUEST

[PRESIONE PARA VER LA IMAGEN](https://www.google.com/imgres?imgurl=https%3A%2F%2Fi.ytimg.com%2Fvi%2FLU_6IVpL-f4%2Fmaxresdefault.jpg&imgrefurl=http%3A%2F%2Fwww.edu4java.com%2Fes%2Fservlet%2Fservlet3.html&docid=iXFVvE_wkF8CYM&tbnid=sxI-J6sz1kfxQM%3A&vet=10ahUKEwjbye2DoP7jAhVrp1kKHYG6BdUQMwhRKBIwEg..i&w=1280&h=720&bih=920&biw=1920&q=METODO%20DE%20LA%20CLASE%20HTTPSERVLETREQUEST&ved=0ahUKEwjbye2DoP7jAhVrp1kKHYG6BdUQMwhRKBIwEg&iact=mrc&uact=8)

  -*METODO GETPARAMETER:* ***Devuelve le valor de un parámetro nombrado. Si nuestro parámetro pudiera tener mas un valor, deberíamos de utilizar*** *getParameterValues* ***en su lugar. El método*** *getParameterValues* ***devuelve un array de valores del parámetro nombrado.***

-*METODO GETQUERYSTRING:* ***Para peticiones GET de HTTP devuelve en un string una línea de datos desde le cliente. Debemos analizar estos datos nosotros mismos para obtener los parámetros y los valores.
Para peticiones POST, PUT, Y DELETE DE HTTP.***

###METODO DE LA CLASE HTTPSERVLETRESPONSE
  -*EL METODO GETWRITER:* ***Devuelve datos en forma texto al usuario.***

  -*METODO GETOUTPUTSTREAM:* ***Para devolver datos binarios.***
 






