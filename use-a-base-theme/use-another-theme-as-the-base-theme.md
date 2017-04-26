Configure your theme to use another theme as the **base theme**.

#### Determine the theme's name

Find the machine name of the theme you would like to use as a base theme.

#### Edit your .info.yml file

Edit your theme's THEMENAME.info.yml file, add a `base theme`key to the existing YAML metadata.

#### Clear the cache

Clear Drupal's internal cache using either the Drupal UI, or a tool like drush, so that the changes to your .info.yml file are read by Drupal.

Take a look at this video:

![](/assets/create-theme.gif)

