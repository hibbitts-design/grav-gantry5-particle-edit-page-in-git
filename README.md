# Gantry 5 'Edit this Page' Particle for Grav

Particles are small, modular blocks with preset scripting that enable you to add elements to your Grav Gantry 5 pages.

## Installing Particle

Upload `edit_page_with_git.html.twig` and `edit_page_with_git.yaml` files to your `/user/themes/THEME_DIR/custom/particles` directory. For example, to install in the default Grav Gantry 5 theme Hydrogen copy the two particle files to `/user/themes/g5_hydrogen/custom/particles`. If the `custom` folder does not exist create it.

The perfect companion to this Gantry 5 particle is the [Grav GitSync Plugin](http://www.hibbittsdesign.org/blog/posts/2016-12-22-touchdown-seamless-2-way-syncing-arrives-for-grav).

## Particle Options
!['Edit this Page' options](https://github.com/hibbitts-design/grav-gantry5-particle-edit-page-with-git/blob/master/edit-this-page-options.png?raw=true)

## Page Options
Once the particle is installed, Grav pages will support the following Header/FrontMatter option:

```
hide_git_repo_edit_link: true    # hide Git Repository edit link for this page  
git_repo_edit_url: https://github.com/hibbitts-design/grav-skeleton-course-hub/tree/master/pages/01.home   # to override the automatically calculated Git Repository URL
```
