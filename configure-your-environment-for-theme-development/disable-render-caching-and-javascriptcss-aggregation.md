In addition, aggregation can be turned off in the UI by navigating to_Configuration_&gt;_Performance_\(admin/config/development/performance\).

When setting up a development environment, change these settings directly in your_settings.php_file. \(This is the preferred method.\) The best way to do this is to enable the use of a_settings.local.php_file. Then put your environment-specific settings into this local file. From there, you can also include the_development.services.yml_file that comes with core, and use that as a location for your environment-specific services settings.

