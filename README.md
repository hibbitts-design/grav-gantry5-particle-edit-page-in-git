# Gantry 5 'Edit/View Page in Git' Particle for Grav

Particles are small, modular blocks with preset scripting that enable you to add elements to your Grav Gantry 5 pages.

## Installing the Particle

1. Open the folder of your active Gantry theme. For example, if you are using the Hydrogen theme open the folder `/user/themes/g5_hydrogen`.
2. If a `custom` folder already exists open it, otherwise create it.
3. If a `particles` folder already exists within the `custom` folder open it, otherwise create it.
4. Upload `edit_view_page_in_git.html.twig` and `edit_view_page_in_git.yaml` files into the `/custom/particles` folder. For example, if you are using the Hydrogen theme copy the two particle files into `/user/themes/g5_hydrogen/custom/particles`.

The perfect companion to this Gantry 5 particle is the [Grav GitSync Plugin](http://www.hibbittsdesign.org/blog/posts/2016-12-22-touchdown-seamless-2-way-syncing-arrives-for-grav).

## Grav 'Edit/View in Git' Particle Setup
https://www.youtube.com/watch?v=4cHwJ27jqXM

## Particle Options
!['Edit this Page' options](https://github.com/paulhibbitts/github-repo-images/blob/master/edit-view-this-page-options.png?raw=true)

## Page Options
Once the particle is installed, Grav pages will support the following Page Header/FrontMatter option:

```
hide_git_repo_link: true    # hide Git Repository edit link for this page, up to but not including the '/pages/...' For example, 'https://github.com/paulhibbitts/grav-skeleton-gantry-oer-content/tree/master'.  
git_repo_link_url: https://github.com/hibbitts-design/grav-skeleton-course-hub/tree/master/pages/01.home   # to override the automatically calculated Git Repository URL
git_repo_link_text: View in Markdown   # to override the default URL text label
```

## Site Config Options
Once the particle is installed, Grav pages will support the following Site Config option:

```
hide_git_repo_link_pages:    # list of pages to hide Git Repository edit link on
    - login
    - logout                        
```

This Particle is also included in the [Grav OER Content Space Skeleton](https://github.com/hibbitts-design/grav-skeleton-oer-content-space).
