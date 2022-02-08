Metis
=====

Metis automates the inclusion of the so called "Metis pixel" from the German association VG Wort. The pixel is included as an image that is 1px wide and high and it allows VG Wort to count visits to nodes. Based on that count, VG Wort pays authors royalties obtained through the sale of printers, copiers, and other technical devices that might be used to copy texts.

Metis stands for "Reporting System for Texts on Websites" (Meldesystem fuer Texte auf Internetseiten).

More information about VG Wort and Metis (in German):

- http://www.vgwort.de/
- https://tom.vgwort.de/
- https://de.wikipedia.org/wiki/Meldesystem_f%C3%BCr_Texte_auf_Internetseiten

The module allows to

- Add Metis codes (Zaehlmarken) to your Drupal installation
- Add the Metis codes to nodes as a field with a simple checkbox
- Display a table of nodes with their respective Metis codes (only if Views
  module is installed)

Requirements
------------

This module has no module requirements. 

To use Metis you have to be a member of VG Wort and to get your list of Metis pixel.

Installation
------------

- Install this module using the official Backdrop CMS instructions at https://docs.backdropcms.org/documentation/extend-with-modules.

- Visit the configuration page under Administration > Configuration > Search > Metis (admin/config/search/metis) and enter the required information.
  
- To use the module, you need to add a field of the type "Metis" to the nodes you want to add Metis codes to.

Documentation
-------------

Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/metis/wiki/Documentation.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/metis/issues.

Current Maintainers
-------------------

- Seeking additional maintainers.

Credits
-------

- Ported to Backdrop by [djzwerg](https://github.com/djzwerg).
- Originally written and maintained for Drupal by [yan](https://www.drupal.org/u/yan). 

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.