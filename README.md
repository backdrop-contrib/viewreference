View Reference
======================

Defines a field type View reference which creates a relationship to a Views display and allows the view to be displayed as the content of the field.

This module is modelled on Node reference and usage is similar.

Additionally, you may enter arguments for each view by a delimiter seperated list with support for PHP generated arguments.

Installation 
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.

- Add a field to a content type of type 'view reference.' Name the field what you want. Choose 'select list' or 'autocomplete' as the widget.
- Choose the views you want to be available for selection. Save.
- Create a piece of content of the type whever you added the field. Choose the view. Save. You should see the view displayed with the content.

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/viewreference/issues).

Current Maintainers
-------------------

- [Eli Lisseck](https://github.com/elisseck)
- [Peter Haight](https://github.com/Dawnthorn)
- [Anthony Nemirovsky](https://github.com/anemirovsky)

Credits
-------

- Ported to Backdrop CMS by [Lauren Blais](https://github.com/rlblais).
- Porting to Backdrop CMS development supported by [USENIX](https://www.usenix.org/).
- Porting to Backdrop CMS development supported by [Giant Rabbit](https://giantrabbit.com).
- Originally written for Drupal and co-maintained by [(danielb)](https://www.drupal.org/u/danielb).
- Drupal 7 co-mainatainers:
 - [James Silver (jamsilver)](https://www.drupal.org/u/jamsilver)

License 
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
