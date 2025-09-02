# Gnome Settings
This repository contains Gnome Shell Extension settings.
## Extensions
- ArcMenu
- TilingShell
## Installation Instructions
1. Clone repository (or download `*-settings` files)
2. Go to `extensions.gnome.org` and find ArcMenu and TilingShell
3. Install using the switch in the top right corner of the page
4. Using the "Installed extensions" button, go to the extension management page
5. Click the link to install the browser extension
You should now be able to see both extensions in the "Installed Extensions" category at the bottom of the page.
6. Click the wrench and screwdriver icon to go to extension settings
7. To install ArcMenu settings: Go to "About" tab and click "Load" in the "ArcMenu Settings" box. Load the `arcmenu-settings` file
8. To install Tiling Shell settings: Scroll to bottom of settings. Click "Import" in the "Import, Export, and Reset" category
9. To install Tiling Shell layouts: Scroll to "Layouts" category. Click "Import layouts" in the "Import layouts" box
## Warning!
These dotfiles are distributed without promise of support or warranty. However, drop an issue and I might look at it.
### Known Issues
- Certain Tiling Shell settings are not saved into the files (or not imported from the files correctly), for whatever reason. It is recommended to test your systems functionality to make sure items such as the Snap Assistant are not appearing.
- Tiling Shell Layouts are added to the layout list instead of replacing it (I believe this is a concious choice by the developers, whether I like it or not) so it is recommended to go through the layouts editor and remove the unnecessary layouts
