
# <span style="color:blue"><u>Ejercicio 5</u></span>
### Enunciado: 

<div style="text-align: justify">Hemos desarrollado un endpoint para que funcione como buscador de paquetes activos para un almacén y queremos informar que el mismo no se encuentra dentro del almacén. Determine la mejor respuesta entre las opciones.</div>

#### GET /site/:site/facilities/:facilityID/packages/:id

### Opciones: 


 - A. status: 200 body: "paquete no encontrado"
 - B. status: 200 body: [ ]
 - <span style="color:green">C. status: 404</span>
 - D. status: 500 body: "error: el paquete no pudo ser encontrado"
 - E. status: 500 body: "error: pk not found"
 - F. status: 200