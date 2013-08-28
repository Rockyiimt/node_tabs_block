README
============

Drupal 7 module to move the node tabs to a block. The blocks is formatted to look as a dropdown menu using Twitter Bootstrap 3.

HOW TO USE IT?
======
Just enable the module, you'll have a block that you can place anywhere you want.

If you don't want to use as a module, you can place this code inside a preprocess_page function in template.php

$vars["node_tabs_block"] = theme("node_tabs_block", array("attributes" => array()));

And then print in page.tpl.php using:

<?php print $node_tabs_block; ?>

LICENSE
========
Released under a doble license:
MIT License: http://opensource.org/licenses/MIT
GPL-2.0 License: http://opensource.org/licenses/GPL-2.0
