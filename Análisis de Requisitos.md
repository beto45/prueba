**ANÁLISIS DE REQUISITOS**
Funcionales

    Insertar alumno (**ID: 001**)
        Datos necesarios:
            DNI.
            Apellidos.
            Teléfono.
            Email corporativo. (@uco.es).
            Dirección postal.
            Curso más alto en el que está matriculado.
            Fecha de nacimiento.
        Datos opcionales:
            Nº de equipo.
            ¿Es líder? (Sí/No)

    Modificar alumno (**ID: 002**)
        Confirmar la modificación

    Buscar alumno (**ID: 003**)
        Por apellidos (si hay repetición, pedir DNI ).
        Por DNI.
        Si el sistema no encuentra a nadie, volver a preguntar.

    Eliminar alumno (**ID: 004**)
        Buscar por apellido (si hay repetición, pedir DNI)
        Buscar por DNI
        Opción de borrar todos los datos.
        Si un líder es eliminado, el grupo correspondiente se queda así hasta que se le vuelva a asignar un líder.

    Mostrar alumno (**ID: 005**)
        En Markdown.
        En HTML.
        Opción de mostrar todos los alumnnos.

    Ordenar alumnos (**ID: 006**)
        Por DNI.
        Por nombre (Ascendente / Descendente).
        Por apellido (Ascendente / Descendente).
        Curso más alto en el que está matriculado.

    Importar datos (desde un fichero binario) (**ID: 7**)

    Poder hacer una copia de seguridad (fichero binario) (**ID: 008**)

    Guardar datos (en el fichero binario) (**ID: 009**)

**No Funcionales**

    Ha de existir una copia de seguridad que tenga la forma de fichero binario.

    El programa debe estar hecho en C++.

    El número máximo de alumnos registrados es 150.

    Debe funcionar en sistemas Linux.
