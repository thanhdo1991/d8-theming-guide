Enabling Twig debugging involves locating the`twig.config[debug]`settings in your _services.yml_ file and changing their values.

These variables can be edited either directly in _sites/default/services.yml_, or alternately they can be added to the _sites/development.services.yml_ file if you followed the steps above to use a _settings.local.php_ file.

Take a look at this video:

[![](/assets/disable-twig-cache.gif)](https://www.youtube.com/watch?v=gOT0mnIj_ZU)

This is what each of those settings is used for: 

**debug**

\(boolean\) Enable various debugging features in the Twig engine.

**auto\_reload**

\(boolean\) When set to \`true\`, Twig will automatically recompile all templates when their source code changes.

**cache**

\(boolean\) Disabling the Twig cache by setting this to \`false\` will recompile the templates from source each time they are used. In most cases the \`auto\_reload\` setting above should be enabled rather than disabling the Twig cache.

