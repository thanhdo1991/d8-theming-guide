Every theme can contain an optional _THEMENAME.theme_ file. This file contains additional business logic written in PHP and is primarily used for manipulation of the variables available for a template file, and suggesting alternative candidate template file names.

In this article, we need understand:

* The use-case for _THEMENAME.theme_ files
* Where to find them
* When you might need to edit one

The _THEMENAME.theme _file is a PHP file, with a _.theme _extension. It is used for complex conditional logic and data processing in the theme layer. The use of _THEMENAME _in this case is just a placeholder for the actual machine readable name of your theme.

