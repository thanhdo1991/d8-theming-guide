We use THEMENAME to represent the unique name/ID of your theme.

### THEMENAME.info.yml file

Defines required meta-data for a theme and provides additional optional settings used by Drupal's theme layer.

This is the only required file for a theme. The name of this file determines the value of THEMENAME.

### THEMENAME.theme file

A PHP file that contains conditional logic, and handles preprocessing of variables before they are output via template files.

### templates/.html.twig files

Twig template files provide HTML markup and very basic presentation logic.

We are used to override the default markup output by Drupal.

We are placed within the _templates/_ sub-directory and may into any number of sub-folders from there.

### THEMENAME.libraries.yml file

Define CSS and JavaScript libraries that can be loaded by your theme. All CSS and JavaScript should be added to the page via an asset library.

### THEMENAME.breakpoints.yml file

Defines the responsive design breakpoints used by your theme for Drupal.

### config/\* directory

Contain additional configuration for Drupal.

### CSS, JS, and image files

Any CSS, JavaScript and image assets that your theme makes use of.

In most cases it's a good idea to create a sub-directory for each: css/, js/ and images/.

---

A single theme directory for a complete theme will contain a some, or all, of these files.

As an example, take a look at the files within the Bartik theme:

![](/assets/structure-file.png)

=&gt; One of the best ways to learn more about how to keep a theme organized is to look at some examples from popular contributed themes.

