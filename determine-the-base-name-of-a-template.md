There are many situations in which you need to know the _theme hook_, or _base name_, of a template file. This name is used for determining things like which preprocess function affects a template, and which template files are used for theming components.

In this article, we need understand:

* How to figure out the _hook_ name for any template

## Determine the hook name of a template

With the hook name, you can locate its base template file.

First, if you already know the filename of the template, you can infer the hook name from that.

The typical pattern for naming template files is `{hook}--{optional context}.html.twig`

![](/assets/hook-name-discovery.png)You can ignore the`.html.twig`suffix. Which results in`{hook}--{optional context}`

If the file name doesn't contain a`--{optional context}`part, then after removing`.html.twig`you're left with the hook name.

---

## Locate hook names in debugging output

1. ### Enable theme debugging
2. ### Open a page in your browser
3. ### View source

Example:

![](/assets/determine-theme-suggest.png)

