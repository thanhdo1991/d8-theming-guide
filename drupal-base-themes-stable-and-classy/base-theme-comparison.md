The decision to use Stable or Classy as the base theme:

* Stable: pristine, clean, semantic markup
* Classy: a collection of reasonably verbose defaults

If we take a look at the Stark theme directory \(_/core/themes/stark_\) we can see that there are no template files at all.

![](/assets/stark-theme.gif)

If we compare that to the Stable theme \(_/core/themes/stable_\) we see that it ships with several templates. \(In fact Stable includes every template available to Drupal core.\)

![](/assets/stable-template.png)

### Stable:_node.html.twig_

![](/assets/node-html-php-stable.png)

You can see there are basic attributes being added to the main page elements, but the overall the markup is quite clean. We can compare this to the implementation provided by the Classy theme \(in _/core/theme/class/templates/content/node.html.twig_\)

