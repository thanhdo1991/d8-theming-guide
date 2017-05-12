Preprocess functions are specially named functions that can be used to add new variables to a Twig template file.

In this article, we need understand:

* Use PHP to perform some complex logic in our theme
* Store the resulting calculation in a variable
* Make that variable available to a Twig template file

## Adding variables to a template file

* Create a .theme file
* Determine the hook name
* Add a preprocess function
* Add a variable

![](/assets/add_variable_template.png)

* Use your new variable : Any new variables added in a preproccess function will have a new corresponding Twig variable injected into the template file being preprocessed. In this example, our _node.html.twig _files in the Ice Cream theme will all have an additional `{{current_user_is_owner}}`variable available.



