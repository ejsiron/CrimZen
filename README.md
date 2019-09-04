# CrimZen

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)

A mixed color theme for Visual Studio Code. CrimZen uses a light design for the coding area with a darker style for all other regions. This design seeks to achieve a balance between the harshness of light themes and the low-contrast, washed-out bleakness of dark themes. This theme will likely look its best in rooms with high ambient lighting.

## Screenshot

![Screenshot](examplescreen.png)

## CrimZen Theme Notes

This theme was built and tested using the [IBM Plex Mono](https://github.com/IBM/plex/releases) and [Deja Vu Sans Mono](https://dejavu-fonts.github.io/) fonts.

This theme was initially envisioned as a "minor change" to Visual Studio Code's built-in "Quiet Light" theme. I found the blue tones too harsh and did not like the purples at all.

The original design included a much softer lower panel (output, problems, terminal, etc.). However, Visual Studio Code does not allow you to control the colors of most of its glyphs (the action icons, such as the tab close button and the buttons to the right of the tabs in the above screenshot). It also does not allow full customization of a few other elements, such as the appearance of tabs. You cannot, for example, create a tab that switches from a black background when inactive to a white background when hovered without trying to find a color for the tab's text that looks good against both black and white. I believe that the panel's title bar is still too dark for this theme, but lightening it causes its glyphs to become less visible. I will likely tune that region in future updates.

Visual Studio Code controls the colors of a few elements, but grants access to dozens of others. I was not able to locate every single setting. In almost all of those cases, I allowed Visual Studio Code to set defaults. However, because I had to use the "vs-dark" base theme even though I have a light code editor, I expect some of those defaults might result in major legibility problems. If you find one, please report it on the theme's [issues page](https://github.com/ejsiron/CrimZen/issues). Ensure that you provide reproduction steps.

## Thanks

Thank you for trying out my theme!
