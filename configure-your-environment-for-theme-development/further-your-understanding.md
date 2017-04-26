**Why should you use a settings.local.php file instead of just editing settings.php directly?**

* Environment-specific settings for local

* Avoid push settings.php file to live environment \(local and live have both settings.php file\).

**In which file do I change the settings that enables the Twig engines debugging output?**

_services.yml_ or _development.services.yml_ if _settings.local.php_ file is used

