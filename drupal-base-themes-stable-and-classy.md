In this tutorial, we will take a look at Drupal's core base themes, with a focus on Stable and Classy.

There are five themes on Drupal 8 core:

* Bartik is the default user-facing theme
* Seven is the default administration theme
* Classy
* Stable
* Stark

## Stark

Stark theme provides the absolute minimal amount of markup and CSS.

It's primarily for demonstration purposes, or for sites that have very strict markup and semantic requirements.

**Stark probably isn't a good choice for a base theme**.

But it can be incredibly helpful in tracking down module-related markup and CSS bugs.

## Stable

Stable is Drupal's default "clean" base theme.

It provides minimal markup and a small handful of CSS classes.

When not use key base theme on _info.yml_ file, Stable will be used.

The intent is that this Stable base theme will be used as a backwards compatibility layer protecting your theme against changes to core's markup and styling.

