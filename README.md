# Gantry 5 'Edit this Page' Particle for Grav

Particles are small, modular blocks with preset scripting that enable you to add elements to your Grav Gantry 5 pages.

## Installing a Particle

Upload `edit_page_with_git.html.twig` and `edit_page_with_git.yaml` files to your `/user/themes/THEME_DIR/custom/particles` directory. For example, to install in the default Grav Gantry 5 theme Hydrogen copy the two particle files to `/user/themes/g5_hydrogen/custom/particles`. If the `custom` folder does not exist create it.

The perfect companion to this Gantry 5 particle is the [Grav GitSync Plugin](https://github.com/trilbymedia/grav-plugin-git-sync).

## Page Options for All Pages
All Grav pages now also support the following option:
```
gitRepoEditURL: https://github.com/hibbitts-design/grav-skeleton-course-hub/tree/master/pages/01.home   # to override the automatically calculated Git Repository URL
