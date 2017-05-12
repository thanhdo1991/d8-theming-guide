* Preprocess functions allow Drupal themes to manipulate the variables that are used in Twig template files by using PHP functions to preprocess data before it is exposed to each template. 
* All of the dynamic content available to theme developers within a Twig template file is exposed through a preprocess function. 
* Understanding how preprocess functions work, and the role they play, is important for both module developers and theme developers.

In this article, we need understand:

* What preprocess functions are and how they work
* The use case for preprocess functions
* The order of execution for preprocess functions

## Preprocess functions

Preprocess functions can be used to perform additional conditional logic and data processing of the variables present in a Twig template file. Preprocess functions are optional, and are defined in a theme's _THEMENAME.theme_ file.

Preprocess functions are called once for each time a template is used.

Preprocess functions follow a specific naming convention: `THEMENAME_preprocess_HOOK()`

Each preprocess function receives a single argument, usually named `$variables `, that is an associative array. The array is

[passed by reference](http://php.net/manual/en/language.references.pass.php) so that you can manipulate the data it contains. The keys of this array directly correspond with the names of the variables in the preprocess function's corresponding template file.

