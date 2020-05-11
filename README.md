# Wordpress Base Theme with Sass

### Base Theme for WordPress Theme Development with SaSS

Base Theme is a clean, empty base theme with SaSS implementation for developers. 

## Inclusions
1. Jquery 3.5.1
2. Font-Awesome 5.13 included in SaSS
3. Wordpress Plugins
 + Smart Slider 3 3.3.28
 + WooCommerce 4.0.1
 + WordFence 7.4.7
 + W3 Total Cache 0.13.3
 + Yoast SEO 14.0.4
 + Contact Form 7
 + CF7 - Conditional Fields
   

## Wordpress Functions
1. Remove annoying emojis
2. Queue styles and js
3. Primary Menu and Sidebar
4. Post Thumbnails
5. Default core markup for search, comment, gallery, caption

## Wordpress Pages Included
1. 404.php
2. header.php
3. footer.php
4. index.php
5. sidebar.php
6. single.php
7. page.php
8. template-parts folder
9. page-template.php (sample page template)
10. single-featured.php (sample post template)

## Installation
1. Upload the contents of this repository to a new directory in `wp-content/themes`.

## Working with SaSS
1. This application uses [Compass](http://compass-style.org/install/) to compile Sass.
2. Enter the following command on the theme folderu using CMD
```
compass watch
```
3. SASS Files Heirarchy
+ [style.scss](wp-content/themes/base-theme-with-sass/assets/sass) 
+ [_partials](wp-content/themes/base-theme-with-sass/assets/sass/partials) folder - to help you jump start your CSS process so you won't have to start from scratch. It contains some basic SaSS mixins and functions to help with your SaSS styling.
  - mixins.scss
  - variables.scss
  - responsive.scss
  - typography.scss
  - default.scss
  - header.scss
  - footer.scss
+ [_vendor](wp-content/themes/base-theme-with-sass/assets/sass/_vendor) folder - third party sass files
+ [_pages](wp-content/themes/base-theme-with-sass/assets/sass) folder - to add wp page styles

## Settings

For optimized WordPress settings, follow these steps.
1. In "Settings -> Permalinks" click "Post name" and save.
2. In "Appearance -> Menus" click "Save Menu" and check "Display location - Primary Menu".
3. In "Appearance -> Widgets" drag a widget to "Sidebar" to view them live.
4. Activate all plugins.

### Compatibility
1. Tested with Wordpress 5.1.3
