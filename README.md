# Desarrollo Freelance Api Rest Productos de Electrónica

### Descripción 

* Este desarrollo freelance se ha culminado a finales del 2021 (fines de Octubre hasta mediados de diciembre) y se realizó a cambio de una remuneración (Transferencia vía paypal) por parte de un Cliente Colombiano contactado a través de un anuncio por Facebook.
* Por temas de `DERECHO INTELECTUAL, PAGO TOTAL DEL SERVICIO DESARROLLADO Y ÉTICOS NO SE ANEXA CÓDIGO FUENTE DEL DESARROLLO`.
* La tarea asignada constó en desarrollar parte de una Api Rest (productos, especificaciones técnicas, ventas, transferencias y clientes) y depurar parte de la base de datos para dichas Colleciones (Modificación de campos, nombres, etc). Parte de dicha Api se implementaría para un proyecto Ecommerce para una tienda de electrónica.
* Contexto : El cliente (Desarrollador Freelance) presenta el esquema general de lo que necesita desarrollar junto con la base de datos madura. A partir de ahí se organiza la lógica a implementar y se procede a la modificación de la parte de la db asignada para el posterior desarrollo de la parte de la Api asignada. Cabe aclarar que el servicio solicitado parte en base a desconocer el stack de tecnología backend asignado. 
* Esta se ha implementado con Spring Boot, Spring MVC, Spring Data, Maven, Swagger v2, Lombok, Log4j, STS, MongoDB Compass, MongoDB, Git y Otras Tecnologías.
* Parte de la Arquitectura desarrollada constó en la capa de acceso a datos (Beans e Interfaces) con Spring Data JPA, capa de Negocios (Services and Controllers) y depuración de capa de datos (database con mongodb). 
* Para la documentación se ha implementado Swagger v2. Todas las operaciones de la Api fueron documentadas y detalladas.
* Como buenas prácticas se ha trabajado con Validaciones para todos los campos de los Beans desarrollados. Se han implementado todos los logs capa services para el backend. Se han desarrollado excepciones personalizadas, etc.
* Se ha trabajado con Optionals, Paginaciones, etc.

</br>

#### EndPoint finales 
* https://x.co/api/v1.0/productos/
* https://x.co/api/v1.0/especificaciones-productos/
* https://x.co/api/v1.0/servicios/transferencias/
* https://x.co/api/v1.0/servicios/ventas/
* https://x.co/api/v1.0/gestion/clientes

* En todos los endpoint se desarrollaron los recursos pertinentes a cada funcionalidad requerida siguiendo las buenas prácticas para Servicios REST.

<hr>

</br>

### Proyectos personales Api Rest
* Las siguientes Api's Rest siguen un principio similar al desarrollado en el desarrollo. Algunas implementan el módulo de seguridad con Spring Security y JWT.

* Api Rest acerca de Productos de Electrónica (uso casi idéntico de tecnologías) : https://github.com/andresWeitzel/ApiRest_ElectroThingsV1_SpringBoot_MongoDB.
* Api Rest acerca de Productos de Supermercado : https://github.com/andresWeitzel/ApiRest_MicroFrontEnd_ProductosSupermercado.
* Api Rest Componentes de Microelectrónica : https://github.com/andresWeitzel/ApiRest_Microelectronica_SpringBoot_Oracle.
* Otros (Perfíl Github).


### Ejemplo Gráfico Api Rest Productos de Supermercado.

</br>

### Descripción Api Rest
![Index app](https://github.com/andresWeitzel/ApiRest_MicroFrontEnd_ProductosSupermercado/blob/master/doc/description.png)

### Response Modelo Códigos Http
![Index app](https://github.com/andresWeitzel/ApiRest_MicroFrontEnd_ProductosSupermercado/blob/master/doc/httpCodeSwagger01.png)
![Index app](https://github.com/andresWeitzel/ApiRest_MicroFrontEnd_ProductosSupermercado/blob/master/doc/httpCodeSwagger02.png)

### Beans Validations 
![Index app](https://github.com/andresWeitzel/ApiRest_MicroFrontEnd_ProductosSupermercado/blob/master/doc/beanValidations.png)


### Recursos por Endpoint

### Producto Controller. 
![Index app](https://github.com/andresWeitzel/ApiRest_MicroFrontEnd_ProductosSupermercado/blob/master/doc/productoController.png)


### Usuario Controller. 
![Index app](https://github.com/andresWeitzel/ApiRest_MicroFrontEnd_ProductosSupermercado/blob/master/doc/usuarioController.png)


### Auth Controller. 
![Index app](https://github.com/andresWeitzel/ApiRest_MicroFrontEnd_ProductosSupermercado/blob/master/doc/authController.png)




