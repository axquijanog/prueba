Product Image  
=============

Este módulo amplía la funcionalidad del módulo ``sale_management`` de Odoo. Permite mostrar la imagen del producto tanto en el reporte PDF de ventas como en el portal del cliente.


Features
--------

- Muestra la imagen del producto en el reporte de cotización/pedido de venta en PDF.
- Añade la imagen del producto en la vista del portal para los pedidos de venta.
- Mejora la experiencia visual del cliente al consultar pedidos desde el portal             


Configuration
-------------

Para configurar este módulo, dirígete a ``Sales > Configuration > Settings``. Allí, activa la opción ``Print product image``. Al seleccionarla, se mostrará la casilla ``Active Operation Costs``, la cual debe estar marcada.

.. image:: ./static/descripction/product_image/menu_config.PNG
   :width: 60%
   :align: center


.. image:: ./static/descripction/product_image/opc_report_product.PNG
   :width: 60%
   :align: center


Resultado Esperado
------------------

Si la instalación y configuración del módulo fue correcta, deberías observar lo siguiente:

- En el **PDF de la orden de venta**, cada línea de producto muestra una imagen en miniatura del producto, junto con su descripción y cantidad.
- En el **portal del cliente**, al abrir una orden de venta, cada línea incluye la imagen del producto correspondiente.
- No se presentan errores al generar el reporte PDF ni al acceder a la orden desde el portal.

.. image:: ./static/descripction/product_image/product_image.PNG
   :width: 60%
   :align: center


Bug Tracker
-----------

Bugs are tracked on `GitHub Issues <https://github.com/TU_REPOSITORIO_GITHUB/issues>`_.
If you find a bug, please report it with detailed steps to reproduce the issue.

Credits
-------

Authors
~~~~~~~

.. image:: https://d-3system.com.au/wp-content/uploads/2020/05/Dimension3_Systems_460x159.png.webp
   :width: 25%
   :alt: Dimension 3 systems
   :target: https://d-3system.com.au/

Contributors
~~~~~~~~~~~~

* Juan Pablo Arcos

Maintainers
~~~~~~~~~~~

This module is maintained by your team or organization.

.. image:: https://d-3system.com.au/wp-content/uploads/2020/05/Dimension3_Systems_460x159.png.webp
   :width: 25%
   :alt: Dimension 3 systems
   :target: https://d-3system.com.au/

License
=======

Licensed under the LGPL v3.0 or later.  
This module is not part of an official OCA repository but follows OCA best development practices.
