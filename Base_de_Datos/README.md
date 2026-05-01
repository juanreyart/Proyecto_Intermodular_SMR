# Bases de Datos - Galería de Arte Digital

Este repositorio contiene el diseño, modelado y estrategia de gestión de datos para la **Galería de Arte Digital**. La base de datos actúa como el núcleo lógico del sistema, permitiendo la administración eficiente de obras, artistas, clientes y transacciones mediante un esquema relacional optimizado.

## Autor
**Juan Antonio Rey Vicente** | Estudiante de 1º SMR | Vilagarcía de Arousa (Galicia)

---

## Índice del Proyecto
1.  **Análisis de Entidades:** Definición de los objetos de información clave (Ilustrador, Obra, Cliente, Empleado).
2.  **Estrategia de Normalización:** Aplicación de principios para evitar redundancias y asegurar la integridad referencial.
3.  **Diagrama Entidad/Relación (E/R):** Visualización de la arquitectura lógica y las relaciones entre tablas.
4.  **Estructura Relacional:** Configuración de claves primarias (PK) y foráneas (FK) para consultas complejas.
5.  **Gestión y Consultas:** Implementación de un esquema SQL escalable para la operatividad diaria.

---

## Arquitectura de Datos
La infraestructura de datos ha sido diseñada para garantizar la integridad, consistencia y disponibilidad de la información en tiempo real. Se ha priorizado una estructura normalizada donde cada entidad interactúa de manera lógica, facilitando tareas como el historial de adquisiciones de un cliente o la trazabilidad de una obra específica.

## Especificaciones Técnicas
* **Modelo:** Base de datos relacional (SQL) diseñada para ser escalable y eficiente.
* **Entidades Principales:**
    * **Ilustrador:** Datos personales y de contacto de los creadores.
    * **Obra:** Información técnica, título, fecha y valor de cada pieza.
    * **Cliente:** Gestión de contacto y transacciones.
    * **Empleado:** Gestión de roles (Administrador/Recepcionista) y privilegios.
* **Integridad:** Uso estricto de claves primarias y foráneas para evitar duplicidad de datos.
* **Visualización:** El diseño lógico se refleja en el diagrama E/R adjunto en este directorio.

## Resultados y Validación
* **Consistencia:** El diseño evita redundancias, asegurando que los datos se mantengan coherentes independientemente de la carga de trabajo.
* **Trazabilidad:** La estructura permite realizar consultas avanzadas para el análisis de ventas y gestión de inventario.
* **Escalabilidad:** El esquema SQL permite el crecimiento futuro del catálogo de la galería sin comprometer el rendimiento.

---

> *"La tecnología es el medio; el diseño y la funcionalidad son el mensaje."*

---
*Proyecto Intermodular 1º SMR | Galería de Arte Digital | Juan Antonio Rey Vicente*
