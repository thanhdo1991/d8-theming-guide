The machine name must be all lowercase, start with a letter, use an underscore \(_\) instead of spaces, and contain no other symbols._

Examples of a good machine name_ _are_ \_icecream_ and _ice\_cream_.

We will choose icecream as example of theme name.

=&gt; Create the file _themes/icecream/icecream.info.yml_

![](/assets/content-info-theme.png)

Here's what these key/value pairs do:

**name **\(required\) The human readable name of your theme, displayed in Drupal's UI when administrators are browsing the list of available themes

**type **\(required\) Tell Drupal what type of project this is. Required, and will always be set to 'theme' for a Theme.

**description **A short one-line description used in the UI when listing your theme.

**package **The package your theme belongs in; used for grouping projects together.

**core **\(required\) The version of Drupal core that your theme is compatible with. Required; for Drupal 8 themes this will likely always just be '8.x'.

**base theme **\(default = Stable\) The machine name of an installed theme to be used as a base theme.

If no base theme should be used, enter "false" as a value for this key.

