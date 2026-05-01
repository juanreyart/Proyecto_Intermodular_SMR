# Redes Locales - Galería de Arte Digital

Esta carpeta contiene la documentación técnica, el diseño de la topología y los protocolos de configuración de la infraestructura de red implementada para el proyecto **Digital Art Gallery**.

El objetivo de este módulo es garantizar una conectividad estable, de alta densidad y segura para la gestión de contenido multimedia 4K y la comunicación entre dispositivos dentro de las instalaciones.

## 📂 Contenido de la Carpeta

* **`Analisis_Necesidades.pdf`**: Identificación de los requisitos de red, tipos de dispositivos (pantallas, estaciones de trabajo) y servicios necesarios.
* **`Diseño_Topologia.png`**: Diagrama lógico y físico de la red (basado en arquitectura Cisco).
* **`Plan_Direccionamiento.md`**: Especificaciones del rango de IPs, máscara de subred y configuración de dispositivos principales.
* **`Pruebas_Conectividad.md`**: Resultados de las pruebas de ping y verificación de los enlaces entre la red inalámbrica y el router.

## 🛠 Especificaciones Técnicas

La red de la galería ha sido diseñada bajo los siguientes parámetros críticos:

* **Conectividad:** Implementación de **Wi-Fi 6** para la zona de exposición, garantizando latencia mínima para la transmisión de archivos de alta resolución.
* **Segmentación:** Uso de switches Gigabit y configuración de red local (LAN) para separar el tráfico administrativo del tráfico de exposición.
* **Servicios:**
    * Compartición de archivos centralizada para el catálogo de obras.
    * Gestión de perfiles de usuario y permisos de acceso.
    * Políticas de respaldo para copias de seguridad en red.
* **Seguridad:** Implementación de medidas para garantizar la integridad de los datos, incluyendo el uso de SAI para protección eléctrica.

## 🧪 Pruebas y Simulación

Se han realizado pruebas de conectividad (ping) para asegurar que la comunicación entre los equipos de la oficina (`192.168.1.10`) y los dispositivos de la zona de exposición es bidireccional y estable.

> **Nota:** La topología de red fue simulada siguiendo las buenas prácticas de SMR, priorizando la disponibilidad y la escalabilidad del sistema.

## 📝 Documentación Adicional
Para más detalles sobre la configuración de los equipos o los scripts de red, consulta la documentación principal en el directorio raíz del proyecto.

---
*Proyecto Intermodular 1º SMR | Galería de Arte Digital | Juan Antonio Rey Vicente*
