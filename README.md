# SOFTWARE FJ
## Sistema Integral de Gestión de Clientes, Servicios y Reservas

### Descripción general
Software FJ es un proyecto desarrollado en Python que busca facilitar la gestión de clientes, servicios y reservas de una empresa que ofrece reservas de salas, alquiler de equipos y asesorías especializadas.

El sistema utiliza programación orientada a objetos para organizar sus funcionalidades, gestionar la información mediante objetos y listas, y registrar eventos y errores a través de archivos de logs. No utiliza bases de datos.

### Objetivo general
Desarrollar un sistema de gestión de clientes, servicios y reservas mediante Python, aplicando los principios de la programación orientada a objetos y un manejo robusto de excepciones que permita controlar errores y mantener la estabilidad del programa.

### Funcionalidades
- Registro, consulta, actualización y eliminación de clientes.
- Creación y administración de diferentes tipos de servicios.
- Gestión de reservas de salas, alquiler de equipos y asesorías.
- Confirmación, cancelación y finalización de reservas.
- Validación de datos y disponibilidad de servicios.
- Cálculo de costos según el tipo de servicio y la duración de la reserva.
- Manejo de excepciones personalizadas.
- Registro de eventos y errores mediante archivos de logs.
- Simulación de operaciones exitosas y fallidas.
- Pruebas para verificar el funcionamiento del sistema.

### Tecnologías utilizadas
- Python 3.
- Programación Orientada a Objetos (POO).
- Abstracción.
- Encapsulación.
- Herencia.
- Polimorfismo.
- Manejo de excepciones.
- Listas y archivos de registro.
- Módulo `logging`.
- Módulo `unittest`.

### Principios de programación orientada a objetos
El proyecto implementará los siguientes principios:

- **Abstracción:** creación de clases abstractas para representar entidades y servicios generales.
- **Encapsulación:** protección y validación de los datos internos de las clases.
- **Herencia:** reutilización de características y comportamientos entre clases.
- **Polimorfismo:** implementación de métodos con comportamientos diferentes según el tipo de servicio.

### Manejo de excepciones
El sistema contará con excepciones personalizadas y mecanismos de control de errores mediante `try`, `except`, `else` y `finally`, además del encadenamiento de excepciones.

Los errores y eventos relevantes serán registrados en archivos de logs, procurando que las fallas de una operación no impidan continuar con las demás.

### Organización del proyecto
El código se organizará en módulos y archivos para facilitar su mantenimiento, comprensión y futuras modificaciones.

### Pruebas del sistema
Se realizarán pruebas de operaciones válidas e inválidas, verificando el registro de clientes, la creación de servicios, las reservas, los cálculos de costos, las validaciones y el comportamiento ante errores.

Se incluirá una demostración de mínimo 10 operaciones, procurando que el sistema continúe funcionando cuando se presenten excepciones.

### Desarrollo académico
Este proyecto corresponde a la Fase 4 – Componente práctico del curso de Programación de la Universidad Nacional Abierta y a Distancia (UNAD).

El desarrollo se realizará de manera individual, siguiendo los requerimientos establecidos en la guía de actividades.

### Autor
Estudiante de la Universidad Nacional Abierta y a Distancia (UNAD).

Curso: Programación  
Actividad: Fase 4 – Componente práctico
