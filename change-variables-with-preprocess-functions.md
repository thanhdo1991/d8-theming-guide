Preprocess functions are specially named functions that allow themes and modules to perform additional manipulation of variables used in a Twig template file.

## Changing existing variables

* Create a .theme file
* Determine the hook name
* Add a preprocess function
* Find the variable you want to change
  * The `$variables`argument passed to this new function is an associative array. Each key in the array represents a variable that will be present in the Twig template file.
  * For example: `$variables['label']`in your preprocess function maps to`{{label}}`in the Twig template.
* Modify the variable : Add some code that compares the currently logged in user to the author of the node and then modifies the `{{label}}`variable.

  ![](/assets/modify_variable_preprocess.png)

* Clear the cache

## A note about Drupal 7

In Drupal 7 it was common to use preprocess functions to dynamically change the classes associated with an element.

In Drupal 8, the preferred way to deal with altering/adding class names is via the Twig template file.

