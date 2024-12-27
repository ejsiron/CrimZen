# Change Log

Change log for the CrimZen color theme.

## 3.5.0 December 27th, 2024

- Fix for WSL output (issue #8)
- Fix for invisible items on default screen (issue #8)
- Reduced color harshness on notifications and panels
- Tuned most in-editor items against the background color (language keywords, function names, etc.) using Adobe's color wheel
- Attempted to fix poor contrast of file widget in Copilot Edits, but VSCode does not allow. Refer to issue 237014: <https://github.com/microsoft/vscode/issues/237014>

## 3.2.0 July 27th, 2022

- Modification to accommodate untracked and conflicting Git file names
- Slight darkening of active tab background
- Changelog update for Marketplace
- Banner color correction on Marketplace (no change in extension)

## 3.1.0 July 26th, 2022

- Fixes for hover widget and several dropdowns
- Made the general font color as neutral as possible. Some components do not have color overrides so the default color needs to perform well on dark and light backgrounds.
- Added support for Jupyter notebooks

## 3.0.0 -  November 5th, 2020

- Finally changed colors for code window

## 2.0.2 - November 3rd, 2020 (unreleased)

- Fixed some long-standing problems with text selection
- Changed Find window again due to conflicts with hover widget
- Made hover widget text visible
- Changed background of terminal to near-black

## 2.0.1 - November 2nd, 2020

Minor patch to correct README screenshot URL.

## 2.0 - November 2nd, 2020

- Updates to colors in widgets like the Find window so that all icons are visible.
- Fixes for selected text colors.
- Terminal now has a near-black background, should fix all outstanding color problems in that section.
- Extensive readability updates to activity bar, especially list items.

## 1.2.0 - October 23rd, 2020

- Increase version support to something more current
- Minor item cleanup -- precursor to fuller color corrections

## 1.1.1 - September 16th, 2019

- Modified the "editor widget" (ex: find/replace) to use a light theme to improve glyph visibility.
- Modified other input boxes (ex: filter box on the "Problems" panel) to improve glyph visibility.

## 1.1.0 - September 7th, 2019

- Modified colors in peek editor to improve legibility
- Modified colors in "editorMarkerNavigation" (appears when clicking "Peek Problem") -- returned some to defaults
- Corrected light-on-light problems with tab colors
- Changed color of empty region of tab bar
- Modified output panel color to improve legibility
- Lightened bracket matching border to improve legibility

## 1.0.2 - September 5th, 2019

- Changed base uiTheme from "vs-dark" to "vs" to address irreconcilable color conflicts between output panel and other elements (ex. browser pages)
- Changed Panel colors to align with "vs" base theme restrictions
- Changed tab colors to align with "vs" base theme restrictions
- Changed breadcrumb colors to align with "vs" base theme restrictions

## 1.0.1 - September 4th, 2019

- First attempt to reconcile default text color conflicts

## 1.0.0 - September 3rd, 2019

- Initial release
