In addition to looking for a template named_node.html.twig_, Drupal will also attempt to locate variations of the file based on context, and use those variations if they exist. This allows for fine-grained control over which template file is used in any given context.

Sometimes you might want to get more specific and change the markup of an element only in specific cases. A common example would be providing different markup for nodes of a specific type, like blog posts. In addition to looking through the theme's chain of inheritance for a template file, Drupal will also look for templates that match a predefined naming convention for a best-fit match. These potential alternate names are referred to as _theme hook suggestions_.



1. _node--{NODE.NID}.html.twig -- node-123.html.twig_
2. _node--{NODE.TYPE}.html.twig -- node--blog\_post.html.twig_
3. _node.html.twig_



