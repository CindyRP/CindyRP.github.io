---
layout: post
title: Blog de un aprendiz de Desarrollo Web
---

# Esta es la primera vez que uso GitHub
* Aprendí como hacer un blog en github siguiendo los pasos del link [github-jekyll](https://devexperto.com/blog-gratis-github-jekyll/)
* Se utiliza Markdown para editar lo que quiera escribir aquí, debo tener a la mano [Markdown CheatSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) para ver todas las herramientas que tiene.

## Typescript
* Hace que se pueda escribir código con menos errores, es más sencillo, coherente y fácil de probar, en definitiva, más limpio y sólido.
* Es un super conjunto de JavaScript **todo el código escrito en JS es válido para TS**.
* Para más información, leer [TS vs JS](https://profile.es/blog/que-es-typescript-vs-javascript/)
## Revisar [Prisma](https://www.prisma.io/docs/getting-started/quickstart)
* Para conocer como se hace el esquema de BD
## Tailwind CSS - Un framework CSS de utilidades básicas.
* Este framework prioriza las utilidades.
* Con Tailwind **NO** tienes que escribir estas clases ni tenerlas en un CSS globlal. Por que se obtienen de el mismo.
* En lugar de llenar un CSS con una clase, se va a agregar sobre la misma linea del HTML usando las diferente utilidades por ejemplo:
**background color: bg-white**
* Ya no hay que pensar diferentes nombres para cada clase, solo se usarán las utilerias.
* Ojo: No es lo mismo que el estilo en linea. Las utilerias en Tailwind las eliges de un diseño.
* Tiene la ventaja de contar con utilidades responsivas.
* Se pueden agregar tipografias, editar la paleta de colores, los tamaños, etc. al entrar a **tailwind.config.js**
* leer [documentacion](https://tailwindcss.com/docs/utility-first)
## cURL
* Curl es una utilidad de línea de comandos que permite enviar una petición HTTP a una URL y recibir el resultado. Viene por defecto en sistemas operativos como macOS y muchas distribuciones de Linux.
* Transfiere ficheros con formato URL.
* Actúa como navegador desde la terminal, por lo que el contenido de la petición va a mostrarse en la terminal.
* *Syntax*: curl[options...]<url> curl https://www.ejemplo.com
* Info en https://www.fastly.com/es/blog/anatomy-of-a-curl-how-to-use-curl-to-test-an-origin-servers-response#:~:text=Curl%20es%20una%20utilidad%20de,y%20muchas%20distribuciones%20de%20Linux.
## Wget
* Comando en linux para descargar archivos
## Webhook
* Mensaje automatizado que se envía a una aplicación externa cuando ocurre un evento.
* Devuelve un llamado HTTP o petición HTTP POST.
* Se registra como **URL** de webhook y almacena datos en formato **JSON**
* Envía notificaciones a un servidor web.
## Sistemas Reactivos
* Son más flexibles, con bajo acoplamiento y escalables.
* Esto hace que sean más fáciles de desarrollar y abiertos al cambio.
* Son significativamente más tolerantes a fallos y cuando fallan responden con elegancia y no con un desastre.
* Los Sistemas Reactivos son altamente responsivos, dando a los usuarios un feedback efectivo e interactivo.
* **RESPONSIVOS:**
  * El sistema responde a tiempo en la medida de lo posible,
  significa que los problemas pueden ser detectados rápidamente y tratados efectivamente.
  * Aporta seguridad al usuario final y fomenta una mayor interacción.
* **RESILIENTES:**
  * La resiliencia es alcanzada con replicación, contención, aislamiento y delegación.
  * Los fallos son manejados dentro de cada componente, aislando cada componente de los demás, y asegurando así que cualquier parte del sistema pueda fallar y recuperarse sin comprometer el sistema como *un todo*.
  * *El cliente de un componente no tiene que responsabilizarse del manejo sus fallos.*
* **ELASTICOS:**
  * Se consigue de forma rentable haciendo uso de plataformas con hardware y software genéricos.
  * Pueden reaccionar a cambios en la frecuencia de peticiones incrementando o reduciendo los recursos asignados para servir dichas peticiones.
* **ORIENTADO A MENSAJES:**
  * El uso del intercambio de mensajes explícito posibilita la gestión de la carga, la elasticidad, y el control de flujo, gracias al modelado y monitorización de las colas de mensajes en el sistema.
  * *Los sistemas grandes están compuestos de otros más pequeños y por lo tanto dependen de las propiedades Reactivas de sus partes.*
## Serverless
* Sin servidor, es una solución que permite crear y ejecutar aplicaciones con rapidez y menor costo total de propiedad, ya que no es necesario aprovisionar y administrar infraestructura.
* Con una arquitectura Serverless podemos procesar miles de peticiones, hasta millones, sin pensar en la capacidad de recursos necesarios para que la aplicación funcione correctamente, la escalabilidad está garantizada.
  * Para entender mejor: [Que es serverless?](https://www.youtube.com/watch?v=-ci7EwXaIJg)
## API REST / GraphQL
* **Qué es API?**
  * Las API son mecanismos que permiten a dos componentes de software comunicarse entre sí mediante un conjunto de definiciones y protocolos.
* **Qué significa API?**
  * API significa “interfaz de programación de aplicaciones”. En el contexto de las API, la palabra aplicación se refiere a cualquier software con una función distinta.
  * La interfaz puede considerarse como un contrato de servicio entre dos aplicaciones. Este contrato define cómo se comunican entre sí mediante solicitudes y respuestas. La documentación de su API contiene información sobre cómo los desarrolladores deben estructurar esas solicitudes y respuestas.
* **Cómo funcionan las API?**
  * La arquitectura de las API suele explicarse en términos de cliente y servidor. La aplicación que envía la solicitud se llama cliente, y la que envía la respuesta se llama servidor.
* *API REST:*
  * REST significa transferencia de estado representacional. REST define un conjunto de funciones como GET, PUT, DELETE, etc. que los clientes pueden utilizar para acceder a los datos del servidor. Los clientes y los servidores intercambian datos mediante HTTP.
  * La principal característica de la API de REST es que no tiene estado. La ausencia de estado significa que los servidores no guardan los datos del cliente entre las solicitudes.
* *Qué es GraphQL?*
  * GraphQL es un lenguaje de consulta desarrollado específicamente para las API. Prioriza dar a los clientes exactamente los datos que solicitan y nada más.
  * GraphQL proporciona una sintaxis flexible e intuitiva para describir los requisitos de datos y las interacciones.
  * Permite a los desarrolladores pedir exactamente lo que se necesita y recuperar resultados predecibles.
  * Permite que los desarrolladores creen consultas para extraer datos de varias fuentes en una sola llamada a la API.
  * GraphQL es fundamental para el funcionamiento de Facebook. Usar Facebook significa usar GraphQL.
  * Es un lenguaje tipado. Esto significa que utiliza tipos para definir recursos, añade tipos a los campos de cada recurso. También utiliza tipos para comprobar estáticamente los errores.
  * GraphQL es un lenguaje de consulta para APIs. En lugar de enviar múltiples peticiones independientes (por ejemplo, una para la lista de usuarios, otra para sus roles, otra para su empresa), GraphQL permite a los clientes hacer una sola petición, y obtener la respuesta con todos los campos que necesitan.
  * **REST es genial, pero tiene algunas limitaciones. Una de las más importantes es que no es ideal para consultar grandes conjuntos de datos. Ahí es donde entra GraphQL, GraphQL es un lenguaje de consulta para APIs, similar a SQL para bases de datos relacionales.**
## Hasura
  * Hasura es un proyecto de código abierto que conecta nuestras bases de datos y microservicios brindándonos de manera instantánea una API GraphQL lista para producción sin apenas codificar.
* Hasura te ayuda a crear aplicaciones GraphQL respaldadas por Postgres o de manera gradual permite migrar a aplicaciones GraphQL desde aplicaciones que usan Postgres.
