This is the root directory for the Bartik theme.

![](/assets/bartik.png)

## Explore Bartik's info file

### Define meta information with indicate a base theme

![](/assets/bartik-info-metadata.png)

### Attach libraries

![](/assets/bartik-info-libraries.png)

### Specify stylesheets for CKEditor

![](/assets/bartik-info-editor.png)

![](/assets/bartik-iframe-editor.png)

### Define regions

![](/assets/bartik-info-regions.png)

## Explore Bartik's template files

Navigate to the templates directory and explore Bartik's template files.  
Start page.html.twig file with Bartik's regions, defined in _bartik.info.yml_

## Explore Bartik's CSS libraries

Take a look at \_bartik.libraries.yml \_and notice how all of Bartik's CSS files in its \_css \_directory are listed here under the `global-styling`key.

## Explore preprocess functions in bartik.theme

Open _bartik.theme _. This is a PHP file \(known in previous versions of Drupal as _template.php_\) containing PHP functions, mostly preprocess hooks. In Bartik's ".theme" file, you'll find functions that implement a variety of preprocess hooks, altering and adding variables to various template files.

## Explore Bartik's responsive features

* Open bartik.breakpoints.yml and take note of the breakpoints defined in this YAML file.
* Navigate to the Extend page and enable the core Responsive Images module.
* Navigate to Configuration &gt;  Responsive Image styles \(`admin/config/media/responsive-image-style/narrow`\)
* Under Breakpoint group, select Bartik. Notice how the breakpoints defined in bartik.breakpoints.yml correspond with those listed in the field sets now displayed under Breakpoint group.

## Explore Bartik's integration with Color module

* Navigate to Appearance &gt;  Settings &gt;  Bartik \(`admin/appearance/settings/bartik`\)
* Notice that Bartik's settings include a color picker UI
* Try it out and change the background colors of the header
* In a code editor, navigate to c_ore/themes/bartik/color and explore the files inside: color.inc_, _preview.css_, _preview.html _, and
  _preview.js_.



