=======================
 Upgrading Horde_Image
=======================

:Contact: dev@lists.horde.org

.. contents:: Contents
.. section-numbering::


This lists the API changes between releases of the package.


Upgrading to 2.3.0
==================

  - Horde_Image_Effect_Gd_Border

    Replaces and fixes the generic border effect implementation.

  - Horde_Image_Effect_Imagick_LiquidResize

    A 'ratio' parameter has been added.

  - Horde_Image_Rgb

    This class holds a map from HTML color names to RGB values and replace the
    global $horde_image_rgb_colors variable.
