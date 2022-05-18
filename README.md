Card Recipe
======================

This module is a recipe to add the Card content type to your site. 
Cards were added as a default content to Backdrop CMS 1.22.0 and later.
If you site was built with an earlier version, you will not get the 
Card content type on upgrading. 

However, you can add it to existing sites with this recipe. 

Cards are pathless nodes, which means that only administrative users
can view them at their original path. The expectation for cards is that 
they will be displayed using views or existing content blocks. 

This particular module creates a Card content type with fields for 
- image
- body

It also comes with
- a custom image style
- a view
- a CSS file

This recipe now comes with 3 sample cards to help you immediately
see how it works. Please, delete this sample content and add your own.


Requirements
------------

Requires [BackdropCMS 1.20](https://github.com/backdrop/backdrop/releases/tag/1.20.0) or greater.

Installation
------------

- This recipe can be found in the Recipes package on the modules 
  page (admin/modules/list).

- Install this like any other module using the official Backdrop CMS 
  instructions at https://backdropcms.org/guide/modules.

- Disabling and uninstalling this module will not delete any of the 
  configuration that this module provides, but will disable the CSS
  files that came with this module. 

- Either add the testimonial page to your menu OR place the views 
  testimonial block on any page. 

Instructions
------------

After enabling the module and experimenting with it a bit. Delete
the sample content and create your own cards.

To reproduce the front page view of cards seen in new installations of 
Backdrop CMS, add the '3 promoted Cards' block to the TOP region of your
home page layout.

- Go to `Content > Add Content > Card` or `/node/add/card`
- Create several Card with or without images

Uninstall or Upgrate Options
----------------------------

It is not currently possible to uninstall or upgrade this recipe.
If you no longer wish to keep this functionality, you will need 
to remove the items added by the recipe manually.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/card-recipe/issues.

Please, use the issue queue to tell us how the recipe worked for you and
to share your ideas on how to improve it for other users. 

Feedback
--------

We are experimenting with config recipes and welcome your feedback. Please,
let us know how this config recipe worked for you and how you think we 
could improve it for other users in the future. 
https://github.com/backdrop-contrib/card_recipe/issues/1

Current Maintainers
-------------------

- [Tim Erickson](https://github.com/stpaultim).

Credits
-------

- Sponsored by [Simplo](https://www.simplo.site)

License
-------

This project is GPL v2 software. 
See the LICENSE.txt file in this directory for complete text.
