# Registro de Estudiantes

## Descripción del proyecto

Este programa es una **aplicación de escritorio** construida en **Java** usando **Swing** que permite registrar información de estudiantes como:

- Nombre completo
- Cédula de identidad
- Fecha de nacimiento
- Carrera
- Sexo
- Hobbies (Música, Deportes, Lectura)

Cada vez que un usuario llena el formulario y presiona el botón **Aceptar**, los datos se:

- Guardan en un archivo de texto (`personas.txt`).
- Agregan a una tabla visible dentro de la misma aplicación.

El sistema también permite limpiar los campos o salir del programa.

## Características principales

- **Interfaz Gráfica (GUI)** amigable usando **JFrame** y componentes Swing.
- **Persistencia de datos** en archivo `.txt`.
- **Validaciones**:
  - No permite campos vacíos.
  - La cédula debe ser numérica.
  - Debe elegirse exactamente un género (masculino o femenino).
  - Se debe seleccionar al menos un hobby.
- **Tabla** que muestra todos los estudiantes registrados (incluyendo los que ya estaban en el archivo).

## Estructura del proyecto

El proyecto tiene dos clases principales:

- **`Persona.java`**  
  Representa a un estudiante. Permite guardar y cargar datos desde el archivo de texto.

- **`RegistroEstudiantes.java`**  
  Es la ventana principal (GUI) que permite registrar estudiantes y verlos en una tabla.

## ¿Cómo ejecutar el programa?

1. Asegúrate de tener instalado **Java JDK 8** o superior eclipse IDE.
2. Descarga el archivo .zip del presente repositorio.
3. Descomprime el archivo.
4. En Eclipse IDE selecciona el paquete registroapp y en la carpeta src encontraras RegistroEstufdiantes.java y ejecutalo.
5. Se abrirá una ventana donde puedes:
   - Llenar los campos de información.
   - Seleccionar carrera, sexo y hobbies.
   - Presionar **Aceptar** para registrar un estudiante.
   - Usar **Limpiar** para borrar los campos.
   - Presionar **Salir** para cerrar el programa.

6. Los datos quedarán guardados en un archivo llamado **`personas.txt`** en la misma carpeta donde se ejecuta el programa.
7. cada darto que registres quedara en el archivo .txt.
-Puede consultar los videos y capturas de pantalla en el presente repositorio.



