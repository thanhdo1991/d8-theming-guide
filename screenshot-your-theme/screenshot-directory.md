In drupal 8, default location of screenshot is `DRUPALROOT/themes/custom/MYTHEME/screenshot.png`

We need rename above PNG image to screenshot.png and put it to theme's directory

## Specify an alternative file location

**Scenario 1: Different file name; saved in your theme's root directory.**

If your screenshot called `screenshot_icecream` that saved in theme root directory.

-&gt; Add new line to your theme's info file : `screenshot: screenshot_icecream.png`

**Scenario 2: Saved in images directory of your theme.**

If your screenshot image called `screenshot_icecream`  is saved in the images directory of your theme.

-&gt; Add new line to your theme's info file : `screenshot: images/screenshot_icecream.png`

