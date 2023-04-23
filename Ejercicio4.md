# <span style="color:blue"><u>Ejercicio 4</u></span>
### Enunciado:

<div style="text-align: justify">Según un diseño lo más próximo a REST, seleccione cuál es la mejor opción de un endpoint para crear en el sistema de inventario de un almacén contenedores de paquetes. Un contenedor permite mediante una numeración hacer un agrupamiento de paquetes que se almacenan. Por ejemplo en carritos que pueden contener alrededor de 50 paquetes y son móviles para acercarlos hasta la zona de despacho. Esto permite tener un trackeo en todo momento de la ubicación de cada paquete.</div>

### Opciones:

- A. OPTION: /sites/:site/facilities/:facilityID/containers\
Body: {"name": "\<name>", "capacity": \<nro>}
- <span style="color:green">B. POST: /sites/:site/facilities/:facilityID/containers\
Body: {"name": "\<name>", "capacity": \<nro>}</span>
- C. POST: /sites/:site/facilities/:facilityID/new_container\
Body: {"name": "\<name>", "capacity": \<nro>}
- D. GET: /sites/:site/facilities/:facilityID/containers/new\
Body: {"name": "\<name>", "capacity": \<nro>}
- E. GET: /sites/:site/facilities/:facilityID/containers/new?name=\<name>&capacity=\<nro>
- F. PUT: /sites/:site/facilities/:facilityID/containers

### Mejor Opción ->   B.  
POST: /sites/:site/facilities/:facilityID/containers\
Body: {"name": "\<name>", "capacity": \<nro>}
