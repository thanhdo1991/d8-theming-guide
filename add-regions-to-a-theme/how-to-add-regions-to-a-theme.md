#### Edit your theme's .info.yml file

Declare some region on .info.yml file:

![](/assets/regions_declared.png)

#### Clear the cache

Clear the cache so your new regions are detected.

#### Confirm that it's working

Navigate to Structure &gt; Block layout \(admin/structure/block\) to confirm that Drupal is now using your regions.

![](/assets/primary_menu.png)

#### Edit your page.html.twig file

Displaying regions in your _page.html.twig_ template.

If you haven't already, you'll need to override the default _page.html.twig_ file since we'll be modifying it.

Now, just adjust the markup in your _page.html.twig_ template to accommodate your new regions.

![](/assets/region_page_twig.png)

