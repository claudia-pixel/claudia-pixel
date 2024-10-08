icesi-proyecto1-innovacion-tecnologica-inventario
Creación de Estructura Inicial (Primera Parte)
Este proyecto consiste en la implementación de un sistema de gestión de vehículos. A continuación, se detalla la estructura inicial y las responsabilidades de cada usuario en el desarrollo del sistema.

Estructura del Proyecto
Usuario A: Clase Vehiculo
Descripción: Creará la clase principal Vehiculo que almacenará la información básica de cada vehículo.
Atributos:
marca: Marca del vehículo.
modelo: Modelo del vehículo.
año: Año de fabricación del vehículo.
kilometraje: Kilometraje actual del vehículo.
estado: Estado actual del vehículo (nuevo, usado, etc.).
tipo_combustible: Tipo de combustible utilizado (Gasolina, Diesel, Eléctrico).
Métodos:
Getters y Setters para manipular los datos de los atributos.
Usuario B: Clase HistorialMantenimiento
Descripción: Desarrollará la clase HistorialMantenimiento, que registrará información sobre las reparaciones y mantenimientos realizados a los vehículos.
Atributos:
fecha_servicio: Fecha en que se realizó el servicio.
descripcion: Descripción del servicio realizado.
kilometraje_servicio: Kilometraje del vehículo en el momento del servicio.
costo: Costo del servicio.
mecanico: Nombre del mecánico responsable del servicio.
Usuario C: Clase Main
Descripción: Implementará la clase Main, que será el punto central de interacción del sistema.
Funcionalidades:
Gestionar una lista de vehículos.
Permitir añadir vehículos a la lista.
Buscar vehículos por año.
Usuario D: Validaciones en la Clase Vehiculo
Descripción: Añadirá validaciones a la clase Vehiculo.
Validaciones:
Asegurar que el tipo_combustible solo pueda ser uno de los valores predefinidos: "Gasolina", "Diesel" o "Eléctrico".
Usuario E: Método para Imprimir Vehículos
Descripción: Implementará un método dentro de la clase Main que imprimirá todos los vehículos registrados.
Funcionalidad:
Mostrar características de cada vehículo (marca, modelo, año, etc.).
Tabla de Participantes
Nombre	Usuario
Octavio	Usuario A
Claudia	Usuario B
Enrique	Usuario C
Sebastian	Usuario D
Octavio	Usuario E