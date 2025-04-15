==========================================
Project Task 
==========================================

Este módulo extiende la funcionalidad estándar del módulo **Project** en Odoo,
añadiendo un nuevo menú llamado **Tasks** que permite visualizar y filtrar tareas
según el rol del usuario.

**Características principales:**

* **Mis Tareas:** Muestra las tareas asignadas al usuario actual.
* **Todas las Tareas:** Permite a los administradores ver todas las tareas del sistema y sus estados.
* **Tareas por Usuario:** Permite buscar un usuario y visualizar las tareas tal como las vería dicho usuario.

Esto resulta especialmente útil para supervisores y administradores de proyectos que
necesitan una visión global o para depurar problemas de visibilidad con tareas específicas.

**Tabla de Contenidos**

.. contents::
   :local:

Características
===============

Este módulo añade tres nuevas acciones en el menú de *Tareas*:

* **Mis Tareas**: muestra únicamente las tareas asignadas al usuario conectado.
* **Todas las Tareas**: lista todas las tareas del sistema, ideal para supervisores y administradores.
* **Tareas por Usuario**: permite buscar un usuario y visualizar sus tareas como si fueras él (útil para soporte o seguimiento).

Cada vista está filtrada y adaptada con vistas de tipo `tree`, `form` y `kanban`.

Uso
====

#. Ir al módulo de *Proyectos / Tareas*.
#. Usar las opciones del menú lateral para acceder a:
   - *My Tasks*
   - *All Tasks*
   - *User Tasks*
#. En "User Tasks", seleccionar un usuario desde el asistente para ver sus tareas activas.

Capturas
--------

**Menu principal**

.. image:: assets/menu.png
   :width: 80%
   :align: center

**Vista de my tasks**

.. image:: assets/view_my_tasks.PNG
   :width: 80%
   :align: center

**Vistas All Tasks**

.. image:: assets\view_all_tasks.PNG
   :width: 80%
   :align: center

**Vistas Users Tasks**

.. image:: assets\view_user_tasks.PNG
   :width: 80%
   :align: center

.. image:: assets\selection_user.PNG
   :width: 80%
   :align: center

.. image:: assets\view_user_selection_tasks.PNG
   :width: 80%
   :align: center

Seguimiento de Errores
=======================

Los errores se rastrean en `GitHub Issues <https://github.com/TU_REPOSITORIO_GITHUB/issues>`_.
Si encuentras algún problema, por favor repórtalo con los pasos detallados para reproducirlo.

Créditos
========

Autores
~~~~~~~

* Tu nombre o el de tu organización

Colaboradores
~~~~~~~~~~~~~

* Aquí puedes listar otros contribuidores.

Mantenedores
~~~~~~~~~~~~

Este módulo es mantenido por tu equipo o entidad.

.. image:: https://odoo-community.org/logo.png
   :alt: Asociación de la Comunidad de Odoo (OCA)
   :target: https://odoo-community.org


Licencia
========

Licenciado bajo la LGPL v3.0 o superior.

Este módulo no forma parte de un repositorio oficial de la OCA, pero sigue sus buenas prácticas de desarrollo.

