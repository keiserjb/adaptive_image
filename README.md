Adaptive Image
==============

The Adaptive image module provides device-appropriate versions of images from
your fields. You can activate adaptive images by adding an adaptive effect to
any of your image styles.

The used technique is derived from http://adaptive-images.com/ by Matt Wilcox.
The hard work is done by Drupal core no need for any additional rewrites.
If image styles work on your website, this module will too.


INSTALLATION
------------

1. Install this module using the official Backdrop CMS instructions at https://backdropcms.org/guide/modules

2. Add the adaptive image effect to an image style:
- Go to admin/config/media/image-styles
- Edit an existing or add a new style. Add the Adaptive image effect.
- Click on 'Update style' button.

3. Apply the new image style to an image field:
- Go to admin/structure/types
- Click on "manage display".
- Choose a "image" field and click on the edit button.
- Choose the previously updated style as image style.
- Click on "Update".


MAINTAINERS
-----------

- [drybro](https://github.com/drybro/)


CREDITS
-------

- ported to Backdrop CMS by [biolithic](https://github.com/biolithic)
- Maintained for Drupal by [sanduhrs](https://www.drupal.org/u/sanduhrs)
- Development sponsored by [erdfisch](https://erdfisch.de)


LICENSE
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

