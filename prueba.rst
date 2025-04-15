==========================================
Project Task 
==========================================

Este módulo extiende la funcionalidad del módulo ``project`` de Odoo, agregando un menú personalizado llamado **Tasks** con tres vistas específicas para facilitar la gestión de tareas por parte de usuarios y administradores.

Características
---------------

- 📌 **My Tasks**: Muestra únicamente las tareas asignadas al usuario conectado.
- 👁️ **All Tasks**: Vista disponible solo para administradores. Permite visualizar todas las tareas del sistema, con sus respectivos estados y responsables.
- 🔍 **User Tasks**: Permite seleccionar un usuario específico y visualizar las tareas asignadas, simulando cómo las vería ese usuario.

Menús
-----

Este módulo añade un nuevo menú en el sistema:

.. image:: https://raw.githubusercontent.com/axquijanog/prueba/refs/heads/main/assets/menu.PNG
   :alt: menu tasks
   :width: 400px



    Tasks
    ├── My Tasks
    ├── All Tasks
    └── User Tasks

Requisitos
----------

- Odoo 16+ (ajustar según versión usada)
- Módulo base ``project`` instalado

Instalación
-----------

1. Copiar el módulo en la carpeta ``addons``.
2. Reiniciar el servidor de Odoo.
3. Activar el modo desarrollador.
4. Instalar el módulo desde el menú de Aplicaciones o con el siguiente comando:

::

    $ odoo -u nombre_del_modulo -d nombre_base_datos

Seguridad
---------

- El submenú **All Tasks** solo es accesible para usuarios con permisos de administrador (``base.group_system``).
- Los otros menús están disponibles para
