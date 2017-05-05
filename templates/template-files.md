Drupal generates a page's HTML by combining the output of many template files.

* Sequentially smaller blocks nested inside of one another.
* The innermost template: file attached to an article node
* The outermost template: HTML opening and closing tags



Consider the file _node.html.twig_

. Any time a node is displayed on your site, this template is responsible for generating the HTML markup that represents the node.![](/assets/concept-template-node-single.png)



