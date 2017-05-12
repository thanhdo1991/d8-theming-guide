Every theme can contain an optional _THEMENAME.theme_ file. This file contains additional business logic written in PHP and is primarily used for manipulation of the variables available for a template file, and suggesting alternative candidate template file names.

In this article, we need understand:

* The use-case for _THEMENAME.theme_ files
* Where to find them
* When you might need to edit one

The THEMENAME.theme file_ is a PHP file, with a _.theme extension. It is used for complex conditional logic and data processing in the theme layer. The use of THEMENAME in this case is just a placeholder for the actual machine readable name of your theme.

