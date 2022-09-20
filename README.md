# Freelance_ApiRest_ProductosElectronica

* Este desarrollo freelance se ha culminado a finales del 2021 (fines de Octubre hasta mediados de diciembre) y se realizó a cambio de una remuneración (Transferencia vía paypal) por parte de un Cliente Colombiano contactado a través de un anuncio por Facebook.
* Por temas de DERECHO INTELECTUAL, PAGO TOTAL DEL SERVICIO DESARROLLADO Y ÉTICOS no se anexa código fuente.
* La tarea asignada constó en desarrollar parte de una Api Rest (productos, especificaciones técnicas, ventas, transferencias y clientes) y depurar parte de la base de datos para dichas Colleciones (Modificación de campos, nombres, etc). Parte de dicha Api se implementaría para un proyecto Ecommerce para una tienda de electrónica.
* Contexto : El cliente presenta el esquema general de lo que quiere desarrollar junto con la base de datos madura. A partir de ahí se organiza la lógica a implementar y se procede a la modificación de la parte de la db asignada para el posterior desarrollo de la parte de la Api asignada .
* Esta se ha implementado con Spring Boot, Spring MVC, Spring Data, Maven, Swagger v2, Lombok, Log4j, STS, MongoDB Compass, MongoDB, Git y Otras Tecnologías.
* Parte de la Arquitectura desarrollada constó en la capa de acceso a datos (Beans e Interfaces) con Spring Data JPA, capa de Negocios (Services and Controllers) y depuración de capa de datos (database con mongodb). 
* Para la documentación se ha implementado Swagger v2. Todas las operaciones de la Api fueron documentadas y detalladas.
* Como buenas prácticas se ha trabajado con Validaciones para todos los campos de los Beans desarrollados. Se han implementado todos los logs capa services para el backend. Se han desarrollado excepciones personalizadas, etc.
* Se ha trabajado con Optionals, Paginaciones, etc.

</hr>



Api Rest para la Aplicación Electro Things acerca de Productos Electrónicos con Spring Boot, Spring MVC, Spring Security, JWT, Spring Data MongoDB, SpringFox, Swagger UI, Api Highchart, Maven, Lombok, Log4j, Git, MongoDBCompass, MongoDB y Otras Tecnologías.
Se Desarrollan Clases Específicas para el Manejo de Excepciones para cada Servicio , como también un manejador de excepciones y validaciones por campos de beans.
Todas las funcionalidades tienen generación de logs en el Server para los errores y excepciones personalizadas.

Se incluye documentación completa de la Api con open-api para la visualización con swagger-ui, las anotaciones de open-api se aplican junto con los códigos de respuesta de tipo HTTP para cada función en los respectivos controllers.


Se desarrolla toda la funcionalidad para las Operaciones CRUD, como así también paginados y funcionalidades para uso de filtros de búsqueda de productos desde el frontend.
Se separa la capa de seguridad para la autenticación , implementando Spring Security y JWT. Además de realizar las operaciones CRUD para usuarios se aplica login y signin para la capa de presentación.
También se desarrollan los métodos de búsquedas independientes de tipo Like para todos los campos, tanto de usuarios como productos.
Los objetos de tipo getBy se manipulan como paginados, salvo los getById y Optional que se requiere un response por objeto y no una E.D como de tipo lista, stream, etc.
Entre Otros.
Se pone a disposición todos los recursos anteriores para productos y usuarios.
