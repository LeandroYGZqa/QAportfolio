Día 1-2 – Producto: Trello

Diseñar casos para creación/edición/eliminación de tableros y tarjetas.

Considerar casos positivos, negativos y límites.




--------------

# ID: TC001
Título: Crear tablero con nombre válido
Módulo: Tableros
Precondiciones: 
Ingresar a https://trello.com/ , hacer login con usuario válido.
Crear un espacio de trabajo para crear nuevos tableros.
Pasos:
1. Ingresar en https://trello.com/ 
2. Login con credenciales válidas
3. Crear un espacio de trabajo
4. Crear nuevo tablero
5. colocar un nombre válido (ejemplo: Mi tablero)
6. La visibilidad debe ser "pública"
Datos de prueba:  título: "Mi tablero"
Resultado esperado:  Tablero creado
Resultado real: 
Estado: Pasó
Severidad: Alta
Notas: capturas hechas con shareX , nombre tc001.png
Fecha:  12/8/2025
Tester: Leandro YGZqa

![TC001 - Crear tablero con nombre válido](https://github.com/LeandroYGZqa/QAportfolio/blob/main/Portfolio%20de%20Pruebas/tc001.png?raw=true)
 

# ID: TC002
Título: Crear tablero seleccionando color de fondo
Módulo: Tableros
Precondiciones: 
Ingresar a https://trello.com/ , hacer login con usuario válido.
Crear un espacio de trabajo para crear nuevos tableros.
Pasos:
1. Ingresar en https://trello.com/ 
2. Login con credenciales válidas
3.  Crear un tablero llamado 'Tablero de colores'
4.  La visiblidad debe ser "pública"
5. Ingresar a Tablero de colores
6. Hacer click en el menú de tres puntos
7. Seleccionar un color rojo
Datos de prueba: 
usuario123
contraseña123
Resultado esperado:  el color  rojo seleccionado se aplica correctamente
Resultado real: el color rojo fue aplicado
Estado: Pasó
Severidad: Alta
<<<<<<< HEAD
Notas:  pruebas tc002-01, tc002-02
Fecha:  13/8/2025
Tester: Leandro YGZqa
![Catbox](https://files.catbox.moe/ouoezi.jpg)
![Catbox](https://files.catbox.moe/ttlswx.png)


=======
Notas:  2 capturas  de pantallas,  tc002-01, tc002-02
Fecha:  13/8/2025
Tester: Leandro YGZqa
>>>>>>> 3eae8c06f12346616fd95a1ea6c82c612c637433

# ID: TC003
Título: Crear tablero en un espacio de trabajo específico
Módulo: Tableros
Precondiciones: 
Ingresar a https://trello.com/ , hacer login con usuario válido.
Crear un espacio de trabajo para crear nuevos tableros.
Pasos:
1. Ingresar en https://trello.com/ 
2. Login con credenciales válidas
3. Click en 'Crear' al lado de la barra de búsqueda
4.  Crear un tablero llamado 'Tablero asociado'
5.  La visiblidad debe ser "pública"
Datos de prueba: 
usuario123
contraseña123
Resultado esperado: el tablero se asocia a ' Pruebas LeandroYGZqa  ''
Resultado real: el tablero se asoció correctamente
Estado: Pasó
Severidad: Alta
<<<<<<< HEAD
Notas:  pruebas  tc003-01,tc003-02
Fecha:  13/8/2025
Tester: Leandro YGZqa![Catbox](https://files.catbox.moe/r6xpgk.png)
![Catbox](https://files.catbox.moe/8qb53k.png)

=======
Notas:  
Fecha:  13/8/2025
Tester: Leandro YGZqa
>>>>>>> 3eae8c06f12346616fd95a1ea6c82c612c637433

# ID: TC004
Título: Crear tablero con visibilidad privada
Módulo: Tableros
Precondiciones: 
Ingresar a https://trello.com/ , hacer login con usuario válido.
Crear un espacio de trabajo para crear nuevos tableros.
Pasos:
1. Ingresar en https://trello.com/ 
2. Login con credenciales válidas
3. Crear un espacio de trabajo
4. Crear nuevo tablero de nombre "tablero privado"
5. La visibilidad debe ser "privada"
Datos de prueba: 
usuario123
contraseña123
Resultado esperado:  solo el creador del tablero puede visibilizarlo
Resultado real:  solo el creador puede visibilizarlo 
Estado: Pasó
Severidad: Alta
<<<<<<< HEAD
Notas:  captura tc004, tc004-01
Fecha:  13/8/2025
Tester: Leandro YGZqa![Catbox](https://files.catbox.moe/yanz12.png)
![Catbox](https://files.catbox.moe/ghtufd.png)

=======
Notas:  captura TC004, tc004-01
Fecha:  13/8/2025
Tester: Leandro YGZqa
>>>>>>> 3eae8c06f12346616fd95a1ea6c82c612c637433

# ID: TC005
Título: Crear tablero con visibilidad pública
Módulo: Tableros
Precondiciones: 
Ingresar a https://trello.com/ , hacer login con usuario válido.
Crear un espacio de trabajo para crear nuevos tableros.
Pasos:
1. Ingresar en https://trello.com/ 
2. Login con credenciales válidas
3. Crear un espacio de trabajo
4. Crear nuevo tablero
5. colocar un nombre válido (ejemplo: Mi tablero)
6. La visibilidad debe ser "pública"
Datos de prueba:  título: "Mi tablero"
Resultado esperado:  Tablero creado y es público, todas las personas pueden verlo
Resultado real: El tablero creado puede ser visto por cualquier persona
Estado: Pasó
Severidad: Alta
<<<<<<< HEAD
Notas:  pruebas tc005
Fecha:  12/8/2025
Tester: Leandro YGZqa![Catbox](https://files.catbox.moe/ac9jif.jpg)

=======
Notas: c
Fecha:  12/8/2025
Tester: Leandro YGZqa
>>>>>>> 3eae8c06f12346616fd95a1ea6c82c612c637433

# ID: TC006
Título: Crear tablero y agregar miembros
Módulo: Tableros
Precondiciones: 
Ingresar a https://trello.com/ , hacer login con usuario válido.
Crear un espacio de trabajo para crear nuevos tableros.
Pasos:
1. Ingresar en https://trello.com/ 
2. Login con credenciales válidas
3. Crear un espacio de trabajo
4. Crear nuevo tablero llamado coworking
5. La visibilidad debe ser 'Espacio de trabajo'
6. click en compartir
7. rellenar el campo con el mail del usuario a invitar
Datos de prueba: 
usuario123
contraseña123
Resultado esperado: tablero creado, un usuario fue invitado a colaborar y puede ver el tablero
Resultado real:  el tablero fue creado, el usuario invitado puede ver el tablero y colaborar
Estado: Pasó
Severidad: Alta
Notas: capturas de pantalla:  tc006-01,  tc006-02
Fecha:  13/8/2025
Tester: Leandro YGZqa
<<<<<<< HEAD
![Catbox](https://files.catbox.moe/zujao1.png)
![Catbox](https://files.catbox.moe/llzgi6.jpg)
=======
>>>>>>> 3eae8c06f12346616fd95a1ea6c82c612c637433
