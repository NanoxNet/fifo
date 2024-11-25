# FIFO System Implementation

**Version:** 1.0  
**Author:** Mariano Espinoza Jimenez (E00000404309)  
**Corporation:** NanoxNet_Corp  
**Created:** 2024  

## Descripción

Este proyecto implementa un sistema de archivos FIFO (First-In, First-Out) en Python. El sistema está diseñado para gestionar archivos en un directorio específico, garantizando que se respeten límites en el número máximo de archivos almacenados. Si el límite se excede, se elimina el archivo más antiguo.

### Funcionalidades

- **Creación de archivos:** Permite generar archivos con metadatos, incluyendo información del autor, fecha y contenido personalizado.
- **Gestión FIFO:** Mantiene un número máximo de archivos en el directorio, eliminando automáticamente los más antiguos cuando se excede el límite.
- **Listar archivos:** Muestra los archivos actuales junto con sus fechas de creación.
- **Protección de integridad:** Asegura que el código original no haya sido modificado, lanzando un error en caso contrario.

## Estructura del Proyecto

```plaintext
fifo_files/          # Directorio donde se almacenan los archivos generados
fifo3.1.py              # Código principal del sistema FIFO
README.md            # Documentación del proyecto
