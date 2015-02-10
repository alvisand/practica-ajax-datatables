# practica-ajax-datatables

1. Funcionalidad y apariencia de Datatables
   - Configura el plugin datatables con tu estilo preferido (bootstrap, themeroller o uno propio).
   - Configura datatables con paginación y filtro que deben funcionar correctamente. 
   - Configura datatables con mensajes en español. 
   - Configura datatables para que acceda a los datos de la base de datos y muestre las mismas columnas que en el vídeo que adjunto. 
   - Para "personalizar" la vista que necesita datatables, se pueden utilizar las funciones de mysql concat y group_concat

2. Borrar doctores
   - Se deben poder borrar doctores vía ajax (no es necesario capturar error) actualizando la tabla de datos a la vez que se borra en la bbdd.
   - Antes de borrar el doctor nos debe mostrar una advertencia permitiendo cancelar la operación
   - Se debe mostrar una ventana tipo growl con el éxito o fracaso al borrar el doctor

3. Añadir doctores
   - Mediante ajax
   - Debe mostrar una ventana tipo growl con el éxito o fracaso de la operación
   - Al añadir doctores es necesario realizar **validación**: 
     - Asignación de al menos una clínica. Pueden ser más
     - Nombre de doctor requerido (solo letras)
     - Número de colegiado sea numérico, no requerido.

4. Modificar doctores
   - Mediante ajax, se deben poder modificar doctores (nombre, número colegiado, clínica/s asociada) actualizando la tabla de datos a la vez que se inserta en la bbdd.
   - Debe mostrar una ventana tipo growl con el éxito o fracaso de la operación
   - Validación: 
    - Al modificar doctores es necesario realizar validación: 
    - Asignación de al menos una clínica
    - Nombre de doctor requerido (solo letras)
    - Número de colegiado sea numérico, no requerido.

