A theme may:

* Inherits markup from core
* Inherits templates, CSS, and JavaScript from its parent theme, or even its grandparent theme if it is a subtheme

-&gt; This inheritance can be chained together indefinitely.

If you choose to not declare a base theme for your custom theme, Drupal will automatically assign Stable as the base theme.

Without use base theme, the custom theme may broken in the future when drupal updated \(core change\).

You can rely upon Stable as your default base theme without worry that the markup will change on you during the Drupal 8 cycle.

If you really want to bypass Stable and inherit directly from core you need to explicitly declare so by setting the base theme to 'false' in your theme's info file.

