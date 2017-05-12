Knowing how to inspect the variables available within a template file enables you to discover all of the dynamic content in a Twig file, not just that which is already being used.

## Find variable information in the base template

The first place to look for information about the variables available in a template file is in the file itself, or the base version of the template.

## There's more

The best way to inspect the variables available in a template file is to use Twig's`{{dump()}}`function.

## Using Twig's dump\(\) function

1. Enable Twig debug mode: [Configure Your Environment for Theme Development](/configure-your-environment-for-theme-development.md)
2. Locate a file to inspect: Locate the file for which you would like to get a list of available variables, and open it in your editor.
3. dump\(\): Add the code `{{dump()}}`at the bottom of the file and refresh the page.
4. Dig deeper: Optionally, inspect the content of an individual variable like so: `{{dump(variable_name)}}`.



