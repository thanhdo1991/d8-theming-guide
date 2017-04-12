Drupal caches any rendering it performs for Render API elements in order to speed up subsequent page loads. Since Twig template files are used to generate the HTML during the Render process, and that generated HTML is cached, changes to Twig templates for any Render API element will not take effect immediately when caching is enabled.

