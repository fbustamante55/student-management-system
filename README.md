# Sistema de Gestión de Estudiantes

Sistema de gestión de estudiantes desarrollado en Java que permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre un registro de estudiantes.

## 📋 Descripción

Este sistema permite gestionar información de estudiantes mediante una interfaz gráfica basada en ventanas de diálogo (JOptionPane). El sistema mantiene un registro de estudiantes con su información básica: cédula, nombre y apellidos.

## ✨ Características

- **Agregar Estudiantes**: Registro de nuevos estudiantes con cédula, nombre y apellidos
- **Consultar Estudiantes**: Visualización de todos los estudiantes registrados
- **Eliminar Estudiantes**: Eliminación de estudiantes por cédula
- **Modificar Estudiantes**: Actualización de nombre y apellidos de estudiantes existentes

## 🏗️ Estructura del Proyecto

```
PRACTICA EVALUDAD 3/
├── src/
│   ├── Estudiante.java    # Clase modelo para representar un estudiante
│   ├── Gestion.java       # Clase para gestionar operaciones CRUD
│   └── Principal.java     # Clase principal con menú de opciones
├── build/                 # Archivos compilados (.class)
├── dist/                  # Archivo JAR ejecutable
└── nbproject/             # Configuración de NetBeans
```

## 📦 Requisitos

- Java JDK 8 o superior
- NetBeans IDE (opcional, para desarrollo)

## 🚀 Compilación y Ejecución

### Opción 1: Ejecutar el JAR compilado

```bash
cd "PRACTICA EVALUDAD 3/dist"
java -jar PRACTICA_EVALUDAD_3.jar
```

### Opción 2: Compilar desde el código fuente

```bash
cd "PRACTICA EVALUDAD 3/src"
javac *.java
java Principal
```

### Opción 3: Usar NetBeans

1. Abrir el proyecto en NetBeans IDE
2. Ejecutar el proyecto (F6) o hacer clic en "Run Project"

## 📖 Uso del Sistema

Al ejecutar el programa, se mostrará un menú con las siguientes opciones:

1. **Agregar Estudiante**: Ingrese la cédula, nombre y apellidos del estudiante
2. **Consultar Estudiantes**: Visualice todos los estudiantes registrados
3. **Eliminar Estudiante**: Ingrese la cédula del estudiante a eliminar
4. **Modificar Estudiante**: Ingrese la cédula y los nuevos datos del estudiante
5. **Salir**: Cierra el programa

## 🎯 Clases Principales

### Estudiante
Clase modelo que representa un estudiante con los siguientes atributos:
- `cedula`: Identificación del estudiante
- `nombre`: Nombre del estudiante
- `apellidos`: Apellidos del estudiante

### Gestion
Clase que gestiona un array de estudiantes con capacidad máxima configurable:
- `agregarEstudiante()`: Añade un nuevo estudiante al registro
- `consultarEstudiantes()`: Retorna la lista de todos los estudiantes
- `eliminarEstudiante()`: Elimina un estudiante por cédula
- `modificarEstudiante()`: Modifica los datos de un estudiante existente

### Principal
Clase principal que contiene el método `main()` y el menú de opciones interactivo.

## 📝 Notas

- El sistema tiene una capacidad máxima de 10 estudiantes (configurable en el constructor de `Gestion`)
- La búsqueda y operaciones se realizan mediante la cédula del estudiante
- La interfaz utiliza `JOptionPane` para entrada y salida de datos

## 👤 Autor

**Fabia**

## 📄 Licencia

Este proyecto es una práctica académica.

