Tabla de contenido
==================

* :ref:`Que es el sistema conozca a su cliente? <ref_001>`
* :ref:`Seguridades en el sistema <ref_002>`
* :ref:`Política de privacidad y condiciones de uso del sistema <ref_003>`
* :ref:`Pantalla de bienvenida al sistema <ref_004>`
* :ref:`Ingreso al sistema <ref_005>`
* :ref:`Interfaz de barras de navegación del sistema <ref_006>`
* :ref:`Menú principal del sistema <ref_007>`
* :ref:`Módulo tablero <ref_008>`
* :ref:`Menú módulos <ref_009>`
* :ref:`Módulo Inversionistas <ref_010>`
* :ref:`Módulo Inversiones <ref_011>`
* :ref:`Módulo Registro de Labor Comercial <ref_012>`
* :ref:`Módulo Control de Calidad <ref_013>`
* :ref:`Módulo de la debida diligencia o DD <ref_014>`
* :ref:`Módulo varios <ref_015>`
* :ref:`Módulo de búsquedas <ref_016>`
* :ref:`Módulo de reportes <ref_017>`
* :ref:`Módulo de matriz de riesgo <ref_018>`



   

.. _ref_001:
   
Que es el sistema conozca a su cliente?
---------------------------------------

El sistema conozca a su cliente es un sistema desarrollado para apoyar las tareas de la debida diligencia en lo que respecta a la prevención del lavado de activos y financiamiento del terrorismo. 


El sistema incluye módulos de soporte para el registro de datos de la manera más eficiente y diligente posible para conocer adecuadamente a los clientes, reforzando el conocimiento de aquellos que por su actividad o condición son sensibles al lavado de activos o financiamiento del terrorismo.


El registro digital de los procedimientos de debida diligencia implementados en el sistema permitirá anticipar con relativa certeza los tipos de transacciones y operaciones del cliente y determinar aquellas que son inusuales. 


.. _ref_002:

Seguridades en el sistema 
-------------------------

Uso del protocolo HTTPS
+++++++++++++++++++++++

HTTPS (Protocolo seguro de transferencia de hipertexto) es una versión cifrada del protocolo HTTP. Utiliza SSL o TLS para cifrar todas las comunicaciones entre un cliente y un servidor. Esta conexión segura permite a los clientes estar seguros de que están conectados con el servidor deseado e intercambiar datos confidenciales.

.. admonition:: Para mayor información sobre el protocolo HTTPS

   Consulte el enlace siguiente: https://developer.mozilla.org/en-US/docs/Web/Security


Claves de usuario almacenadas con técnicas de hash seguras
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Las claves de los usuarios se almacenan con técnicas de hash seguras con un algoritmo sólido como SHA-256 y usa un hash iterativo con una sal aleatoria para hacer que el hash sea fuerte.


Uso de reCAPTCHA
++++++++++++++++

Google reCAPTCHA es un sistema diseñado para diferenciar entre humanos y ordenadores, que se utiliza para que los bots no puedan completar formularios de forma malintencionada en nombre de un ser humano.


Ataques de fuerza bruta
+++++++++++++++++++++++

Previene ataques de búsqueda de fuerza bruta y utiliza una sal contra los ataques arcoíris. Por ejemplo, el reciclaje de credenciales es una forma de ataques de fuerza bruta en los que se utilizan nombres de usuario y contraseñas de ataques anteriores. Otro ejemplo de ataque de fuerza bruta es un ataque de diccionario en el que se prueban todas las palabras de un diccionario para encontrar una contraseña. Un ataque arcoíris o mejor conocido como una Tabla Arcoíris o en ingles como Rainbow Table suele utilizarse para romper contraseñas que se han cifrado en un hash.


Prevención de vulnerabilidades CSRF
+++++++++++++++++++++++++++++++++++

El sistema esta equipado con un token anti-CSRF para la prevención de vulnerabilidades CSRF. La falsificación de solicitud entre sitios, a menudo abreviada como CSRF, es un posible ataque que puede ocurrir cuando un sitio web, blog, mensaje de correo electrónico, mensaje instantáneo o aplicación web maliciosa hace que el navegador web de un usuario realice una acción no deseada en un sitio confiable en el que el usuario está actualmente autenticado.


Programado enteramente utilizando tecnología Cloud Computing
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

El sistema esta programado enteramente en el modelo de computación en la nube o conocido en el inglés como cloud computing. Que es una tecnología que permite el acceso remoto a software, almacenamiento de archivos y procesamiento de datos por medio del Internet. Siendo así una alternativa a la ejecución en una computadora personal o servidor local. En este modelo, no hay necesidad de instalar aplicaciones localmente en computadoras y ofrece a las empresas la capacidad de un pool de recursos de computación con buen mantenimiento, seguro y de fácil acceso.


Sistema de gestión de base de datos empresarial
+++++++++++++++++++++++++++++++++++++++++++++++

Utiliza el sistema de gestión de base de datos empresarial MySQL que esta entre los sistemas de gestión de bases de datos mas populares en todo el mundo.


.. _ref_003:


Política de privacidad y condiciones de uso del sistema
-------------------------------------------------------
El sistema cuenta con la política de privacidad que comprende:
* El alcance, 
* Información de los datos que se recolectan, 
* Información de los datos que no se recolectan, 
* La finalidad de la política de privacidad, 
* Explicación del proceso para ejercer derecho de acceso y rectificación de datos, 
* Descripción del proceso a seguir cuando existan cambios en la política de privacidad, 
* Descripción del uso de cookies, 
* Descripción de las medidas para precautelar la seguridad de los datos personales, 
* Descripción detallada de la base legal Ecuatoriana que sustenta el tratamiento de los datos, 
* Descripción de los términos y condiciones de uso del sistema, 
* Responsabilidad del sistema, 
* Las obligaciones del usuario del sistema, y 
* Datos de contacto del proveedor del sistema.




.. _ref_004:


Pantalla de bienvenida al sistema
---------------------------------

Para ingresar al sistema el usuario debe acceder a la página de bienvenida del sistema. Desde esta pantalla el usuario podrá iniciar una sesión en el sistema.  Esta sesión le permitirá registrarse en el sistema. En el registro del sistema el usuario ingresará información como el nombre usuario, dirección de correo electrónico y la clave de acceso. Una vez que el usuario este registrado en el sistema debe esperar que su cuenta de usuario sea autentificada y autorizada por el usuario administrador del sistema. Una vez que el administrador del sistema realice la verificación de los datos personales del usuario procederá a actualizar en el sistema los indicadores de autenticación de la cuenta y de autorización de la cuenta. Únicamente en ese momento el usuario registrado podrá ingresar al sistema.  Adicionalmente en el momento que el administrador del sistema realiza el proceso de autenticación del usuario y de autorización del usuario también asigna los privilegios de acceso a los datos.  Estos privilegios son: crear, consultar, editar y eliminar. Cuando el usuario ingrese al sistema, el sistema validará la cuenta del usuario y registrará la sesión del usuario en una cookie que permite al sistema mantener control de la sesión del usuario. Todas las cuentas de los usuarios responden al modelo de RBAC que son las siglas de Rol Base Access Control y a CRUD que son las siglas de Create, Read, Update y Delete.  El sistema de gestión de roles y privilegios de usuarios permite mantener un nivel de acceso al sistema que valida el rol del usuario para acceder a las páginas del sistema y el nivel de privilegio del usuario para acceder a los datos.  A manera de ilustración si un usuario tiene el rol de ‘comercial’ este usuario no tendrá acceso a las paginas de configuración del sistema ya que estas páginas únicamente pueden ser accedidas por usuarios con el rol de ‘administrador’. Respecto al acceso a los datos, si el usuario tiene privilegios de acceso de solo lectura, el usuario únicamente podrá visualizar la información en el sistema y no podrá crear, eliminar o cambiar los datos. La siguiente pantalla muestra el formato de ingreso al sistema.   La pantalla despliega en la parte izquierda superior el logo de un agente y a un lado el enlace iniciar en color verde. Al dar un click en iniciar, la siguiente pantalla es desplegada:   en esta pantalla el usuario tiene la opción de ingresar al sistema, de registrarse en el sistema o de regresar a la página de bienvenida al sistema. 


.. _ref_005:


Ingreso al sistema
------------------

El sistema ofrece un interfaz de usuario amigable para registrarse en el sistema y también para ingresar al sistema. Las pantallas de ingreso al sistema y de registro en el sistema incluyen reCAPTCHA para reforzar la seguridad. Una vez que el usuario ingresa al sistema el sistema desplegará un mensaje que indica que la credencial del usuario ha sido autorizada, y en ese momento es cuando el usuario esta autorizado para ingresar al tablero o dashboard. La pantalla siguiente es un ejemplo del formato de la pantalla de ingreso al sistema:   


.. _ref_006:


Interfaz de barras de navegación del sistema
--------------------------------------------

El sistema cuenta con tres barras de navegación horizontales disponibles al usuario. La barra del nivel superior es la barra del módulo que está activo. La barra de navegación del medio es la barra del menú principal en donde el usuario puede seleccionar los módulos a los que desea ir. Y por último la tercera barra de navegación es la barra que se utiliza para el control de la sesión del usuario.  Esta última barra despliega la información de usuario en el siguiente orden: el nombre del usuario que tiene activa la sesión, el estado de autenticación del usuario, el estado de autorización del usuario, el nombre del rol del usuario, la fecha y hora registrada en el sistema correspondiente a la ultima sesión activa del usuario, y los privilegios de acceso a datos de la cuenta de usuario para crear, consultar, editar y eliminar. Los privilegios del usuario se desplegarán en fondo de color gris cuando el privilegio no está activo y en fondo de color azul cuando el privilegio está activo.


La captura de pantalla siguiente a manera de ilustración muestra las tres barras de navegación horizontal. El mensaje con fondo de color verde “El proceso de Control de Acceso Basado en Roles (RBAC) ha confirmado que el usuario ha sido autenticado y autorizado para ingresar al sistema. Su ultima sesión activa fue registrada el 25/01/2022 a las 13:08:20” es desplegado para informar al usuario que las credenciales han sido procesadas por el módulo RBAC y que los privilegios de acceso a datos han sido otorgados a la cuenta de usuario:


.. _ref_007:
  

Menú principal del sistema
--------------------------


El menú principal del sistema tiene las opciones para salir del sistema, navegar en la barra de navegación del tablero o dashboard, selección de módulos del sistema, selección de los módulos de debida diligencia o DD, selección de opciones varios y selección en análisis exploratorio de datos o mejor conocido como EDA que son las siglas en lenguaje ingles para Exploratory Data Analysis.

.. _ref_008:


Módulo tablero
--------------

El módulo incluye la opción de configuración y dentro de este módulo están las opciones de la licencia de uso del sistema, de los usuarios del sistema, del idioma seleccionado, de las provincias y de los países. El módulo puede ser accedido únicamente por la cuenta administrador.


Licencia de uso: 
++++++++++++++++
en esta opción se mantienen los registros de la licencia de uso otorgada al usuario que renta el sistema como servicio.  La licencia de uso no tiene límite de usuarios. En esta opción de puede consultar la fecha de creación de la licencia, el tipo de licencia, la clase de licencia, el país al que se autoriza el uso de la licencia, fecha de la firma del contrato de licencia de uso, nacionalidad de la empresa, verificación de la licencia. El sistema tiene un registro de la licencia de uso del sistema. Lo que permite determinar al detalle los derechos del usuario que utiliza el sistema. La licencia de uso es configurada en el momento de la instalación del sistema.


Usuarios:
+++++++++

El registro de usuarios en el sistema esta implementado con mecanismos de seguridad para garantizar la confidencialidad de la información. Para controlar el nivel de acceso que tiene un usuario y los privilegios de acceso a los datos el sistema se dispone de dos mecanismos.  
* El RBAC (conocido en inglés como el Rol Base Access Control) o control de acceso basado en roles y el 
* CRUD (conocido en inglés como Create, Read, Update, Delete) o Crear, Leer, Actualizar y Eliminar.
 
A manera de ilustración la siguiente pantalla muestra la lista de usuarios registrados en el sistema: 
  
la siguiente pantalla es un ejemplo del reporte de usuarios:   la siguiente pantalla es un ejemplo del reporte del log de usuarios:    la siguiente pantalla es un ejemplo del reporte del log de actividad de los usuarios:   la siguiente pantalla es un ejemplo del reporte RBAC:   la siguiente pantalla es un ejemplo del reporte de privilegios:   






Lenguaje: 
+++++++++

El sistema incluye las opciones para seleccionar el lenguaje de preferencia para navegar en el sistema. Al momento el sistema dispone de tres diccionarios que corresponden a los idiomas español, ingles y tailandés. El lenguaje de preferencia es el español por defecto. La configuración de lenguajes como el inglés o thai pueden ser configurados en el momento de la instalación utilizando los diccionarios correspondientes.


Provincias: 
+++++++++++

El sistema permite realizar la gestión de las provincias en el Ecuador y de las ciudades. En esta opción el usuario establece los niveles de riesgo para las provincias y para las ciudades.


Países: 
+++++++

El sistema permite realizar el ajuste del nivel de riesgo de país para Ecuador.




.. _ref_009:


Menú módulos
------------

El menú módulos permite navegar en cuatro módulos: 
* el módulo inversionistas, 
* en el módulo inversiones, 
* en el módulo de registro de labor comercial y 
* en el módulo de control de calidad.



.. _ref_010:

Módulo Inversionistas
---------------------


En este módulo se registra el perfil del cliente. La pantalla principal de este módulo es un tablero de control de los datos del cliente. En esta pantalla se despliega: 
1. el número de identificación del cliente,
2. la clase del cliente que puede ser persona natural o persona jurídica, 
3. el tipo de cliente que puede ser un cliente de bajo riesgo, un cliente de riesgo moderado o un cliente de riesgo alto, 
4. se despliega el estado de la debida diligencia (DD) del cliente,
5. se despliega la fotografía del cliente,
6. se despliega el perfil del cliente. Específicamente se despliega la ficha del cliente con datos que permiten realizar el seguimiento del cliente. Por ejemplo: se mantiene un ficha del cliente con los datos personales del cliente, dirección de trabajo del cliente y dirección de domicilio del cliente, información de contacto del cliente que incluye números de teléfono del cliente y direcciones de correo electrónico,  se despliega el log de creación y de edición de los datos del cliente que incluye la fecha de creación del cliente, la ultima fecha de edición de los datos del cliente y el nombre del usuario responsable de la creación y edición de los datos del cliente, se despliega un log que registra la fecha y hora y el nombre del usuario realizó la debida diligencia,  el estado de verificación de la debida diligencia, observaciones de archivo de la debida diligencia y hechos relevantes de la debida diligencia. La ficha del cliente es relevante en vista que mantiene en un solo lugar la información personal del cliente, muestra en forma tabulada los domicilios particulares y laborales declarados por el cliente, muestra de forma tabulada los números de teléfono y correo electrónico del domicilio y del trabajo, muestra los log de seguimiento de creación y edición de los datos del cliente junto con el responsable de la creación y edición del perfil del cliente; y finalmente muestra el log de la debida diligencia en donde se despliegan las tareas ejecutadas durante la debida diligencia y el resultado en cada una de las tareas como son la verificación de los datos del cliente, el estado de verificación, las observaciones de archivo y los hechos relevantes de la debida diligencia. Dentro los varios reportes que el sistema dispone a manera de ilustración en la figura siguiente se muestra el formato de presentación de los datos del perfil de un cliente:   
7. El sistema incluye un módulo de análisis de datos exploratorio mejor conocido como EDA (Exploratory Data Analysis) lo que permite reforzar los procedimientos de control y detección de cambios en el perfil del cliente respecto a la línea de tiempo. Más específicamente el sistema permite detectar la frecuencia con la que el perfil del cliente ha cambiado en base a las operaciones que ha realizado el cliente, el motor de análisis inteligente de datos permite la detección de cambios en el perfil del cliente tocando al detalle cada atributo asignado en el perfil del cliente. Por ejemplo a manera de ilustración si el atributo es la dirección de domicilio, el sistema permite visualizar cuantas veces el cliente ha cambiado su dirección de domicilio en base al análisis inteligente de las operaciones que ha realizado el cliente mejor conocido como el índice de variación de los datos. La figura siguiente muestra un extracto del reporte de análisis exploratorio de datos. En donde se puede apreciar: el índice de variación de los datos y el nombre del metadato. Si se observa la figura, por ejemplo el número cinco (5) bajo la columna índice de variación de los datos se interpreta como “la frecuencia con la que el dato a variado” y muestra el detalle de la variación de los datos. Ademas el reporte EDA despliega la tabulación de los datos no duplicados.   
8. El módulo incluye también la opción para obtener reportes consolidados y detallados de la cartera del cliente. La figura siguiente muestra el ejemplo del reporte de la cartera de un cliente consolidado:   
en este reporte se puede apreciar el monto total del cliente, el monto mínimo que el cliente invirtió y el monto máximo que el cliente invirtió.  Cabe señalar que este reporte ha sido obtenido utilizando la tecnología de ciencia de datos, que permite consolidar la información para un análisis detallado. La siguiente figura muestra el ejemplo del mismo reporte pero con el detalle de as inversiones u operaciones:   en el reporte se puede observar el detalle de los montos, el monto total de la inversiones u operaciones, la inversión u operación con el monto máximo de la cartera así como también la inversión u operación con el monto mínimo.
9. Dentro de las varias opciones que se despliegan en el módulo de inversiones, está la opción de registro de labor comercial. Esta opción despliega el detalle de la labor comercial para obtener clientes. Este módulo permite llevar al detalle el registro de la labor comercial. Permitiendo obtener reportes que incluyen el detalle de la labor comercial y el capital proyectado que ingresará a la casa de valores.  Este registro de labor comercial es gestionado y controlado por el responsable del área comercial. Existen reportes detallados, y consolidados disponibles para obtener al detalle la labor comercial.  Por ejemplo la siguiente pantalla muestra las opciones para obtener el registro de labor comercial detallado por cliente:   la interfaz del usuario con el sistema es amigable y  le permite al usuario seleccionar el rango de las fechas para la selección de la labor comercial dentro de un intervalo de fechas incluyendo también la selección en el reporte  por el nombre de un comercial o de todos los comerciales.  Esta característica de la interfaz del reporte permite obtener reportes por un solo comercial o por todos los comerciales ayudando a distribuir la carga de trabajo y tener un control sobre la labor comercial de los comerciales al detalle. La figura siguiente es un ejemplo de la interfaz del usuario para seleccionar una fecha inicial:   y la siguiente pantalla es un ejemplo del reporte de labor comercial:   existen varias opciones de reportes. Por ejemplo si se desea obtener el reporte de un solo comercial, el sistema de reportes permite seleccionar el nombre del comercial y obtener el reporte de la labor comercial del comercial seleccionado, la figura siguiente es un ejemplo:   en donde se observa que al seleccionar el comercial se despliegan las opciones: todos, y los nombres de los dos comerciales registrados en el sistema.
10. Dentro de las funcionalidades incluidas en el módulo de inversionistas, están las matrices de riesgo. El sistema aplica controles de gestión de riesgos automatizados que utilizan los algoritmos empleados para la obtención de matrices de riesgo.  La implementación automatizada para calcular los niveles de riesgo sigue las recomendaciones del estándar ISO para la gestión de riesgos.  Por cada riesgo el sistema determina el nivel del riesgo que puede ser BAJO, MEDIO o ALTO y posteriormente realiza el computo de los riesgos inherentes, riesgos de control y riesgos residuales utilizando las probabilidades e impactos asignados a los riesgos.  La gestión de riesgos en el sistema incluye la opción para generar matrices de riesgo tomado en cuenta los siguientes riesgos: riesgo del inversionista, riesgo del país, riesgo de la provincia, riesgo de la ciudad. Para el calculo del riesgo de la ciudad y del riesgo de la provincia el sistema utiliza un mecanismo de ponderación de riesgos, más específicamente para el cálculo del riesgo de la ciudad y del riesgo de la provincia el riesgo es calculado con los riesgos siguientes: riesgo de frontera, riesgo de desastre natural, riesgo de presencia de contrabando, riesgo de presencia de terrorismo, riesgo de presencia de carteles, riesgo de presencia de narcotráfico, riesgo de presencia de violencia y riesgo de lavado de dinero. La figura siguiente es un ejemplo del despliegue de los riesgos inherente, riesgos de control y riesgos residuales correspondientes a los factores de riesgo inversionista, riesgo país de residencia, riesgo de provincia y riesgo de ciudad:   la siguiente figura muestra un ejemplo del despliegue de la matriz de riesgo correspondiente a una provincia:   y la siguiente figura muestra la matriz de riesgo correspondiente a la ciudad:   
 


.. _ref_011:


Módulo Inversiones
------------------

En este módulo se despliegan las órdenes de los clientes. El tablero de información esta conformado por tres filas de información. La primera fila incluye el número de identificación del cliente, el número de la orden o de la inversión, incluye la opción para desplegar la matriz de riesgo de la inversión, incluye el módulo de gestión de calidad en donde se listan los procesos para el control de calidad de la orden, el nombre del cliente y la clase de inversionista. En la segunda fila se despliega el detalle de la orden de inversión que incluye el nombre del instrumento bursátil, el monto, la fecha de creación de la orden, la hora de creación de la orden, el nombre del usuario que creo la orden, la fecha de la ultima edición de la orden, la hora de la ultima edición de la orden y el nombre del usuario que editó la orden. Adicionalmente incluye la opción para eliminar la orden. En tablero incluye opciones de edición de la orden, despliegue de la matriz de riesgo de la orden y gestión de control de calidad de la orden.
La pantalla siguiente muestra un ejemplo del formato de presentación de la matriz de riesgo de la orden:   la pantalla siguiente es un ejemplo del formato de presentación de edición de la orden:   la pantalla siguiente muestra el menú de opciones para acceder al módulo de gestión de calidad, en donde se despliegan los procesos para realizar el control de calidad de la orden:   en la figura se despliegan los procesos implementados para realizar el control de calidad. Y también esta incluido en la parte final de las opciones del menú el reporte de control de calidad. 


La siguiente figura muestra una sección del reporte de control de calidad. En este reporte se despliegan los procesos de control de calidad y las tareas que incluye cada proceso. Cuando las tareas han sido completadas las tareas se desplegaran con un check en la caja de chequeo. Cada proceso se despliega con el control interno de la tarea que incluye el log de registro del rol del usuario que realizó la tarea, la fecha en la que fue realizada, la hora en la que fue realizada, y el nombre del usuario que realizó la tarea:   la figura siguiente es un ejemplo de cómo se visualiza el proceso de control de calidad de la línea de proceso para clientes nuevos:
  
el módulo de control de calidad presenta la línea de procesos gráficamente.  En el caso que el usuario desea obtener información de la línea de procesos, tiene la opción de ir al módulo de control de calidad en donde tiene la opción de desplegar el control de calidad en formato detallado o en formato consolidado. A manera de ilustración la figura siguiente muestra un ejemplo del formato que tiene el reporte de control de calidad de la orden Nro. 0001 correspondiente al cliente Lauren Conrad:   el mismo reporte en formato consolidado es presentado de la siguiente forma:
  
por motivos de espacio no se incluye el reporte completo. Sin embargo a manera de ilustración se incluye una captura de pantalla del reporte completo en formato reducido:  







.. _ref_012:

Módulo Registro de Labor Comercial
----------------------------------  

El módulo de registro de labor comercial esta disponible desde la opción de menú módulos. El módulo ofrece las opciones para crear registros de labor comercial, obtener un reporte de la labor comercial, opciones de reportes consolidados y opciones de reportes detallados. Los reportes de labor comercial son desplegados de acuerdo a las opciones que se indiquen para la elaboración del reporte. Por ejemplo la figura siguiente es un ejemplo de las opciones disponibles para generar el reporte de labor comercial detallado por cliente:    el formulario para parametrizar el reporte es amigable y permite especificar un rango de fechas para la obtención de los registros de labor comercial que cumplen la condición del rango de fechas. La figura siguiente muestra a manera de ilustración el calendario con el mes de enero del año 2022 en el cual el usuario puede navegar por el calendario y seleccionar la fecha inicial deseada:  de igual manera la opción seleccionar el comercial incluye dinámicamente en el menú de opciones los nombres de los usuarios con el rol de comercial. Por ejemplo en la figura siguiente se muestra a manera de ilustración como se despliegan las opciones al usuario para que seleccione el nombre del comercial o si desea todos los comerciales:   un ejemplo de cómo luce el reporte de labor comercial con la selección de un rango de fechas se muestra en la siguiente figura:    para crear un registro de labor comercial el sistema permite especificar el nombre del comercial a cargo del cliente y el nombre del supervisor del comercial.  Al tener el nombre del supervisor del comercial y el nombre del comercial asignado al cliente el sistema de reportes de labor comercial se convierte en una herramienta de gestión para realizar el seguimiento de la labor comercial al detalle.  Por ejemplo la figura siguiente muestra el reporte de labor comercial con los comerciales monicabelluci y leahflicking en donde monicabelluci tiene el rol de comercial supervisor y también realiza la labor comercial:   
en el reporte se despliegan todos los nombres de los usuarios con rol de comercial junto al nombre del evento, fecha de creación del registro de labor comercial, hora de creación del registro de labor comercial, la bandera que indica si el cliente tiene interés en el producto, y el monto del capital proyectado por el cliente a invertir. La pantalla siguiente muestra un ejemplo del formato del reporte de labor comercial de usuario comercial monicabelluci:   desde el mismo formulario que despliega el reporte el usuario puede ingresar nuevos parámetros para la generación del reporte. Por ejemplo puede especificar un nuevo rango de fechas, ingresar un número de identificación y seleccionar todos o un solo nombre de usuario con el rol de comercial.


La figura siguiente muestra a manera de ilustración un ejemplo del total proyectado del registro de labor comercial sin especificar un rango de fechas:   el mismo reporte indicado en la figura de arriba en el formato consolidado se muestra de la siguiente forma:   




.. _ref_013:


Módulo Control de Calidad
-------------------------

La figura siguiente muestra la forma de acceder al módulo de control de calidad:   el módulo incluye dos opciones. El reporte detallado de control de calidad y el reporte consolidado de control de calidad. En las páginas anteriores en la sección correspondiente al módulo de inversiones se mostró algunas pantallas de ejemplo de los reportes de control de calidad detallado y consolidado.



.. _ref_014:

Módulo de la debida diligencia o DD
-----------------------------------

La pantalla siguiente muestra a manera de ilustración el menú de opciones de la debida diligencia:   en el módulo de la DD el usuario puede ingresar a los módulos de gestión de cónyuges declarados por el cliente, representante o representantes legales declarados por el cliente, detalle de ingresos declarados por el cliente, detalle de egresos declarados por el cliente, detalle de los recursos lícitos declarados por el cliente, detalle de los bienes muebles declarados por el cliente, detalle de los bienes inmuebles declarados por el cliente, detalle de las cuentas en instituciones financieras declaradas por el cliente, detalle de las cuentas en tarjetas de crédito declarados por el cliente, política conozca a su cliente o KYC (Know Your Client) en las siglas en el idioma inglés, detalle de dependencia de terceros declarados por el cliente y el reporte de la lista de verificación de la debida diligencia.



.. _ref_015:

Módulo varios
-------------

La figura siguiente muestra a manera de ilustración el menú de opciones del módulo varios:   las opciones disponibles en este módulo son el módulo de búsquedas, el módulo de reportes y el módulo de matriz de riesgo.


.. _ref_016:

Módulo de búsquedas
-------------------

El módulo de búsquedas tiene dos opciones.  La primera opción despliega la pagina web de OFAC y la segunda opción despliega la opción de búsquedas en la Fiscalía General del Estado del Ecuador. 


OFAC
++++
La pantalla siguiente es un ejemplo del despliegue de la pagina web de OFAC, en donde el usuario puede realizar consultas:    la siguiente figura muestra la pantalla de búsquedas en las paginas de la fiscalía general del estado del Ecuador:   la siguiente figura muestra los resultados de la búsqueda utilizando el nombre Guillermo Lasso en las páginas de la fiscalía general del estado:    los resultados obtenidos son desplegados en tres columnas. El title, el link y snippet. Los resultados fueron obtenidos utilizando el motor de búsqueda de google que para los propósitos del sistema esta personalizado para buscar únicamente en las paginas web de la fiscalía general del estado del Ecuador (FGE). Sin embargo dependiendo de los requerimientos del usuario que adquiere el sistema el motor de búsqueda puede ser configurado para incluir otras fuentes de datos y de esta forma la búsqueda podrá ser realizada en un ámbito más amplio de datos. 


.. _ref_017:


Módulo de reportes
------------------

La figura siguiente muestra el módulo reportes que incluye reportes en las siguientes áreas: Política conozca a su cliente, debida diligencia, personas naturales y jurídicas, UAFE y cartera. A manera de ilustración la siguiente figura muestra el formato de la página de reportes:


  



A manera de ilustración la figura siguiente muestra la interfaz del usuario para la obtención del reporte (RESU) – Reporte de operaciones y transacciones individuales múltiples sobre el umbral de USD 10,000.00 dentro de un rango de fechas especificado por el usuario:
  
la figura siguiente muestra un ejemplo del formato de salida del reporte RESU:   
la figura siguiente muestra a manera de ilustración el ejemplo del reporte RESU listando transacciones individuales y transacciones múltiples:   
la figura siguiente muestra a manera de ilustración la pantalla para la obtención del reporte ROII:   la figura siguiente muestra a manera de ilustración un ejemplo del reporte ROII:   



.. _ref_018:


Módulo de matriz de riesgo
--------------------------

En este módulo se puede obtener la matriz de riesgo de una inversión. La figura siguiente ilustra el formato del reporte de la matriz de riesgo:   

