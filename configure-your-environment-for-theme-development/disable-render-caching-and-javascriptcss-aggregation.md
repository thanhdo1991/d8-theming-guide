In addition, aggregation can be turned off in the UI by navigating to _Configuration_&gt;_Performance _\(admin/config/development/performance\).

When setting up a development environment, change these settings directly in your _settings.php_ file. \(This is the preferred method.\) The best way to do this is to enable the use of a _settings.local.php_ file. Then put your environment-specific settings into this local file. From there, you can also include the _development.services.yml_ file that comes with core, and use that as a location for your environment-specific services settings.

Take a look at this video:

{% youtube src="https://www.youtube.com/watch?v=9bZkp7q19f0" %}{% endyoutube %}






