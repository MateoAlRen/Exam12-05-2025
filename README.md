# Exam12-05-2025
Exam by Mateo Algarin Rendon

En la interfaz de usuario mostrada en el código tenemos varias opciones:

"1. Add products."
"2. Modify a product."
"3. Find a product."
"4. Show list of products."
"5. Delete a product."
"6. Total of the inventory."
"7. Exit."

Donde cada una de estas depende de añadir algún producto.

 # "1. Add products."
 Aquí de primeras tenemos que poner el nombre del producto, si anteriormente ya se añadió un producto del mismo nombre, el sistema no permitirá hacerlo.
 Posteriormente se pedirá un precio, en el cual solo se pueden poner números positivos y se pueden añadir numeros flotantes por si el precio es un decimal.
 Luego se pone un valor entero como cantidad de producto disponible, donde claramente no se podrán poner decimales.

 Tras este proceso, el sistema arrojará al usuario su producto, precio y cantidad con la pregunta de qué si quiere añadir algún otro producto extra, si no se añade, volverá al menú.

 # "2. Modify a product."
 Aquí como en las siguientes opciones, el sistema se asegura de que tengas productos disponibles para modificar.
 En esta opción podrás modificar alguno de los productos, donde se te mostrará una lista de productos y tu eliges uno de ellos escribiendolo en el sistema.
 Si el producto está en el la lista mostrada, procederá a hacer las modificaciones, de lo contrario, te pedirá que escojas uno nuevamente.
 Se introducirá el nuevo precio y la nueva cantidad, una vez hecho esto el sistema te arrojará tu producto modificado.

 Una vez más el sistema pregunta que si quieres modificar otro producto, si es así, repetirá lo antes dicho, de lo contrario, volverá al menú.

# "3. Find a product."
El sistema se asegura de que tengas productos, en dado caso de no tener, avisará y devolverá al menú.
El sistema pide que ingreses el nombre del producto que buscas y finalmente, te lo mostrará con color cyan y volverá al menú.
En dado caso de que no encuentre el producto, también te avisará y tendrás que poner un producto si o si ya que el sistema verificó que hay productos por encontrar.

# "4. Show list of products."
Una vez más se repite el proceso de verificación de productos disponibles, en dado caso de no haber, te devolverá al menú con su debido aviso.
Aquí arroja al usuario los productos agregados en el inventario y posteriormente a ello, te devolverá al menú.

# "5. Delete a product."
Se realiza el proceso de verificación.
El sistema le pide al usuario que ingrese el nombre del producto que desea eliminar, el nombre se puede observar en la lista que se imprime antes de la pregunta.
Se mira si el producto está en la lista, en dado caso de estar, se borrará y el sistema te avisará volviendo al menú, de lo contrario, dirá que no está en la lista.

# "6. Total of the inventory."
Una vez más se realiza la verificación.
El sistema arroja al usuario el total que hay en el inventario y vuelve al menú.

# "7. Exit."
El sistema se despide del usuario y se termina apagando.

 
