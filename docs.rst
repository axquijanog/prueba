Project Task 
==========================================

Este módulo extiende la funcionalidad del módulo ``project`` de Odoo, agregando un menú personalizado llamado **Tasks** con tres vistas específicas para facilitar la gestión de tareas por parte de usuarios y administradores.

Características
---------------

- 📌 **My Tasks**: Muestra únicamente las tareas asignadas al usuario conectado.
- 👁️ **All Tasks**: Vista disponible solo para administradores. Permite visualizar todas las tareas del sistema, con sus respectivos estados y responsables.
- 🔍 **User Tasks**: Permite seleccionar un usuario específico y visualizar las tareas asignadas, simulando cómo las vería ese usuario.

Menú
-----

Este módulo añade un nuevo menú en el sistema:

.. image:: ./assets/menu.png
   :width: 80%
   :align: center

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
- Los otros menús están disponibles para todos los usuarios autenticados.

Estructura del Módulo
---------------------

::

    project_task_extension/
    ├── __manifest__.py
    ├── __init__.py
    ├── models/
    │   └── ...
    ├── views/
    │   └── project_task_views.xml
    ├── security/
    │   ├── ir.model.access.csv
    │   └── security.xml
    └── README.rst

Autor
-----

- Desarrollado por Tu Nombre o Empresa
- Email: tu@email.com

Licencia
--------

Este módulo está bajo la licencia LGPL-3.0 o la que se defina en el manifiesto.
