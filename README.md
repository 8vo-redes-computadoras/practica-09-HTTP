# HTTP (Hypertext Transfer Protocol)

## ¿Qué es HTTP?

HTTP (*Hypertext Transfer Protocol* o Protocolo de Transferencia de
Hipertexto) es un protocolo de red que permite la comunicación entre un
navegador y un servidor web. Es la base del funcionamiento de la World
Wide Web.

Cuando escribes una dirección en el navegador, este envía una solicitud
HTTP al servidor, y el servidor responde con la página, imagen o archivo
que pediste.

## ¿Para qué sirve?

HTTP se utiliza para acceder a sitios web, consultar información en
aplicaciones y enviar datos desde formularios. También es el protocolo
que usan muchas aplicaciones móviles y servicios en la nube para
intercambiar información.

Entre sus principales funciones se encuentran:

-   Solicitar páginas web, imágenes, videos y otros recursos.
-   Enviar datos desde formularios, como un inicio de sesión o una compra.
-   Indicar si una solicitud fue exitosa o si hubo algún problema.
-   Permitir que las aplicaciones consulten y actualicen información en
    servidores remotos.

## Elementos que intervienen en HTTP

-   **Cliente:** programa que realiza la solicitud, como un navegador web
    o una aplicación móvil.
-   **Servidor web:** equipo o servicio que recibe la solicitud y envía
    la respuesta.
-   **Recurso:** lo que se solicita, por ejemplo una página, una imagen o
    un dato.
-   **URL:** dirección que identifica el recurso, como
    `https://ejemplo.com/inicio`.
-   **Cabeceras:** información adicional que acompaña a cada solicitud o
    respuesta, como el tipo de contenido o el idioma.

## ¿Cómo funciona HTTP?

La comunicación HTTP sigue un modelo de solicitud y respuesta:

1.  **Solicitud:** el cliente envía al servidor una petición que indica
    qué recurso quiere y qué acción realizar.
2.  **Procesamiento:** el servidor recibe la solicitud y prepara la
    respuesta.
3.  **Respuesta:** el servidor envía el resultado, junto con un código de
    estado y el contenido solicitado.
4.  **Visualización:** el cliente recibe la respuesta y muestra la página
    o la información al usuario.

Cada solicitud es independiente. Para recordar datos entre una acción y
otra, como mantener una sesión iniciada, se utilizan mecanismos adicionales
como las cookies.

## Métodos más comunes

Los métodos indican la acción que se quiere realizar sobre un recurso:

-   **GET:** solicita un recurso, como abrir una página.
-   **POST:** envía datos al servidor, como un formulario.
-   **PUT:** reemplaza o actualiza un recurso existente.
-   **DELETE:** elimina un recurso.

## Códigos de estado

Cada respuesta incluye un código numérico que resume el resultado:

-   **2xx (éxito):** la solicitud se procesó correctamente. Por ejemplo,
    `200 OK`.
-   **3xx (redirección):** el recurso se encuentra en otra dirección.
-   **4xx (error del cliente):** la solicitud tiene un problema, como
    `404 Not Found` cuando la página no existe.
-   **5xx (error del servidor):** el servidor no pudo completar la
    solicitud, como `500 Internal Server Error`.

## Puertos utilizados

HTTP utiliza el protocolo de transporte TCP:

| Puerto | Uso |
| :--- | :--- |
| **80** | Comunicación HTTP sin cifrar. |
| **443** | Comunicación HTTPS, con cifrado mediante TLS/SSL. |

## Ventajas de HTTP

-   **Sencillez:** es fácil de entender y de utilizar.
-   **Universalidad:** es compatible con prácticamente todos los
    navegadores, servidores y dispositivos.
-   **Escalabilidad:** permite atender a muchos usuarios al mismo tiempo.
-   **Flexibilidad:** sirve para transmitir páginas, datos y archivos de
    distintos tipos.

## Consideraciones de seguridad

HTTP sin cifrar envía la información tal como está, por lo que cualquier
persona que observe la red podría leer datos como contraseñas o datos
personales. Para reducir estos riesgos se utilizan:

-   **HTTPS:** versión de HTTP que cifra la comunicación mediante TLS/SSL.
    Actualmente es el estándar en la mayoría de los sitios web.
-   **Certificados digitales:** permiten verificar que el sitio es
    auténtico.
-   **Cookies seguras:** protegen la información de sesión del usuario.
-   **Actualizaciones:** mantener servidores y navegadores al día reduce
    vulnerabilidades conocidas.

## Relación entre HTTP y otros protocolos

HTTP trabaja junto con otros protocolos de red:

-   **DNS** traduce el nombre del sitio, como `ejemplo.com`, a una
    dirección IP antes de que comience la solicitud HTTP.
-   **TCP** asegura que los datos lleguen completos y en orden.
-   **FTP** y **SMTP** cumplen funciones distintas: transferir archivos y
    enviar correos, respectivamente.

HTTP no se encarga de la transferencia de correo ni de la configuración
de la red; su tarea es el intercambio de contenido entre clientes y
servidores web.

## Conclusión

HTTP es el protocolo que permite navegar por la web y utilizar la mayoría
de las aplicaciones en línea. Su modelo de solicitud y respuesta es simple
y flexible, lo que explica su amplio uso. Hoy conviene utilizar HTTPS para
proteger la información que se transmite.
