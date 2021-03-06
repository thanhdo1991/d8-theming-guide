Stark is one of the themes bundled with Drupal 8. It is intentionally barebones and its purpose is to help Drupal theme and module developers get to the heart of Drupal's system templates.

## Goal

Recognize Stark theme and identify its primary features. Explain the use cases for Stark and what you can learn from it.

## Why explore Stark?

* Examine the default markup and behavior provided by the Drupal system.
* Troubleshoot Drupal core behavior and output.
* Troubleshoot and isolate problems from other modules or themes.

According to Stark's _README.txt _, Stark is provided for demonstration purposes.

Stark:

* Drupal's default markup
* No styling through CSS

Use browser tools to inspect elements or view source to see which of Drupal's system templates are in use for various elements.

![](/assets/stark.png)

Stark does include a few files that are there but don't actually do anything, except to show you that you could use them.

* Stark's _css/layout.css_ exists, but is now blank
* Stark no longer removes _normalize.css _, a file is added by core.
* Stark's _stark.libraries.yml_ exists to show you how to load a CSS library, and it does in fact add css/layout.css to the head of the HTML pages that use Stark, it just doesn't do anything to the layout, because layout.css is blank.
* Similarly, _stark.breakpoints.yml_ does include some good examples of breakpoints, but since they don't correspond to any actual media queries in a CSS file in the Stark theme, this file doesn't really represent any real breakpoints or media queries in Stark.
