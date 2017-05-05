When asked to display a node, the theme system attempts to locate the correct template by looking through a set of known locations for derivatives of the _node.html.twig_ template, then uses the first instance it finds. If no more specific template is found, it ultimately falls back to the base template file provided by the node module.

Locations are searched in this order:

1. Current theme
2. Parent theme \(when applicable\)
3. Drupal core or contributed module



