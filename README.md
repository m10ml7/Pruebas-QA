# Pruebas-QA
# Pruebas Funcionales de Software (E2E)
Las pruebas E2E son pruebas de extremo a extremo que validan el flujo completo de la aplicación desde la perspectiva del usuario.

  -Prueba de crear nuevo contacto:

El usuario agrega un nuevo contacto a la libreta de direcciones.

Se selecciona la opción de crear un nuevo contacto desde el menú e ingresa los detalles del nuevo contacto (nombre, apellido, teléfono, dirección, empleo).
Finalmente, guarda el contacto.

Se comprueba que el contacto se agrega correctamente y está disponible para su búsqueda.

  -Prueba de búsqueda por nombre:

El usuario desea buscar un contacto por su nombre.

El usuario selecciona la opción de buscar por nombre desde el menú, ingresa el nombre del contacto y este confirma la búsqueda.

Se muestran todos los contactos que coinciden con el nombre proporcionado.

  -Prueba de modificar un contacto:

El usuario desea modificar los detalles de un contacto existente.

Se selecciona la opción de modificar un contacto desde el menú, busca el contacto por nombre, selecciona el contacto a modificar y actualiza los detalles del contacto.
Para terminar, el usuario guarda los cambios.

Los detalles del contacto se actualizan correctamente.

  -Prueba de borrar un contacto:

El usuario desea eliminar un contacto de la libreta de direcciones.

Se selecciona la opción de eliminar un contacto desde el menú, buscamos el contacto por nombre y seleccionamos el contacto a eliminar.
El usuario confirma la eliminación.

El contacto seleccionado se elimina correctamente de la libreta de direcciones.

# Pruebas No Funcionales de Software (Unitarias)
Las pruebas unitarias se centran en probar unidades individuales de código.

  -Prueba de creación de contacto:

Creamos un nuevo contacto con nuevos datos y se verifica que se agrega correctamente a la libreta de direcciones.

  -Prueba de búsqueda por teléfono:

Realizamos una búsqueda por número de teléfono y se verifica que devuelva el contacto correcto, si existe.

  -Prueba de modificación de contacto:

Modificamos un contacto existente y se verifica que los cambios se reflejen correctamente.

  -Prueba de borrado de contacto:

Se elimina un contacto de la libreta de direcciones y se verifica que ya no esté disponible para buscar.

# Pruebas Estructurales de Software (UAT)
Las pruebas UAT (User Acceptance Testing) se centran en validar que el sistema cumple con los requisitos del usuario.

  -Prueba de interfaz de usuario:

Verificamos que el menú de texto sea intuitivo y fácil de usar para el usuario.

  -Prueba de eficiencia:

Se evalúa el tiempo de respuesta del sistema para realizar operaciones como búsqueda, creación, modificación y borrado de contactos.

  -Pruebas de Regresión de Software

Las pruebas de regresión aseguran que los cambios recientes en el código no hayan introducido nuevos errores en el sistema.

  -Prueba de regresión general:

Se ejecutan todas las pruebas anteriores para asegurar que las nuevas implementaciones no hayan afectado negativamente la funcionalidad existente.
