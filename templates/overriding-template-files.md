At its core, theming in Drupal works because modules provide a default \(or base\) version of a template file that contains a minimal set of markup required to display the various elements they are responsible for, and then Drupal allows any theme to override that base template in order to change the markup.

Rather than change a template file provided by Drupal, another theme, or a contributed module, it is preferable to override the template file and make changes to a **copy **of the original. A large part of creating a custom theme consists of modifying Drupal's default output to fit your needs by locating the template file that is responsible for outputting the markup you want to change and then making changes to a copy of that template in your custom theme.

Overriding templates is a three-step process that consists of:

1. Locating the template currently being used
2. Copying the template into your theme
3. Modifying the copy of the template



