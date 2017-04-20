The page\_top and page\_bottom regions are a special case.

These two are used in the _html.html.twig_ template.

The idea is that modules can rely on these two regions being present and use them to output markup at the very top or very bottom of any page.

Generally when creating a custom theme you'll create your own _page.html.twig_ and add your new regions there, but leave the _html.html.twig_ intact.

