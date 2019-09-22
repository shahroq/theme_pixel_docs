## Instructions <!-- omit in toc -->

### Table of Contents <!-- omit in toc -->

- [1. Change the theme accent color](#1-change-the-theme-accent-color)
- [2. Enable the Transition Loader](#2-enable-the-transition-loader)
- [3. Fav, Apple Touch Icons](#3-fav-apple-touch-icons)
- [4. Boxed layout](#4-boxed-layout)
- [5. Navigation Icon](#5-navigation-icon)
- [6. Change the main Navigation Type/Style](#6-change-the-main-navigation-typestyle)
- [7. Change the Header Type](#7-change-the-header-type)
- [8. Dark Header](#8-dark-header)
- [9. Add a label to a the Navigation item](#9-add-a-label-to-a-the-navigation-item)
- [10. Not enough space for all menu items, so it falls below the header area](#10-not-enough-space-for-all-menu-items-so-it-falls-below-the-header-area)
- [11. Add & setup the Search in the main menu](#11-add--setup-the-search-in-the-main-menu)
- [12. Change/Disable the Page Title Area](#12-changedisable-the-page-title-area)
- [13. Dark Footer](#13-dark-footer)
- [14. Add the 'Back to Top' button](#14-add-the-back-to-top-button)
- [15. Enable the Footer Ribbon](#15-enable-the-footer-ribbon)
- [16. Add the Cookie Disclaimer](#16-add-the-cookie-disclaimer)
- [17. Change the Owl Slider template height/Button Label](#17-change-the-owl-slider-template-heightbutton-label)
- [18. Manually add new classes, change styles, ...](#18-manually-add-new-classes-change-styles-)
- [19. Change the Font Family](#19-change-the-font-family)
- [20. Setup the Coming Soon page](#20-setup-the-coming-soon-page)
- [21. Make the Top Bar sticky](#21-make-the-top-bar-sticky)
- [22. Fix the CTA below the slider (Full Width)](#22-fix-the-cta-below-the-slider-full-width)
- [23. Add additional 'Main' Areas](#23-add-additional-main-areas)
- [24. Using Express Objects](#24-using-express-objects)
- [25. Parallax Effect](#25-parallax-effect)
- [25.1. Adding additional color overlays](#251-adding-additional-color-overlays)
- [26. Translating to other languages](#26-translating-to-other-languages)
- [27. Replacing the Pixel logo with your own logo](#27-replacing-the-pixel-logo-with-your-own-logo)
- [28. Using customized auth pages (Login, Register, Forgot Password)](#28-using-customized-auth-pages-login-register-forgot-password)
- [29. Replacing alternative home pages with the default home page](#29-replacing-alternative-home-pages-with-the-default-home-page)
- [30. Assigning theme defined margin classes to a block](#30-assigning-theme-defined-margin-classes-to-a-block)
- [31. Changing the theme footer color](#31-changing-the-theme-footer-color)


### 1. Change the theme accent color
Once the theme has been installed, the accent color can be changed globally by using the built-in theme design customizer. Documentation on how to use this core functionality can be found [here](https://documentation.concrete5.org/editors/in-page-editing/the-toolbar/page-edit-drop-down/design).


### 2. Enable the Transition Loader
`Dashboard > Pages & Theme > Pixel Options > General > General > Page Transition Loader`


### 3. Fav, Apple Touch Icons
`Dashboard > Pages & Theme > Pixel Options > General > General > Fav Icon & Apple Touch Icon`


### 4. Boxed layout
`Dashboard > Pages & Theme > Pixel Options > General > General > Boxed`


### 5. Navigation Icon 
Icons that used in Pixel are `Font Awesome` icons Version 4.7. So for changing them, you need to specify the title of icons as they have named in the below link. Remember you only need the part that comes after `fa-`.

[https://fontawesome.com/v4.7.0/icons/](https://fontawesome.com/v4.7.0/icons/)


### 6. Change the main Navigation Type/Style
`Dashboard > Pages & Theme > Pixel Options > Header > Navigation > Navigation Type OR Navigation Style`

(Also, changeable for a specific page via `Navigation Style` and `Navigation Type` page attribute)


### 7. Change the Header Type
`Dashboard > Pages & Theme > Pixel Options > Header > Navigation > Header Type`

(Also, changeable for a specific page via `Header Type` page attribute)


### 8. Dark Header
`Dashboard > Pages & Theme > Pixel Options > Header > Navigation > Dark Header`

(Also, changeable for a specific page via `Dark Header` page attribute)


### 9. Add a label to a the Navigation item
Add `Navigation Label` attribute to a page you want to have a label. You can also change the label color at:

`Dashboard > Pages & Theme > Pixel Options > Header > Navigation > Navigation Label Color`


### 10. Not enough space for all menu items, so it falls below the header area
The space between menu items can be tweaked in:

`Dashboard > Pages & Theme > Pixel Options > Header > Navigation > Navigation Left/Right Padding (px)`

(Default Value is 15px)


### 11. Add & setup the Search in the main menu
`Dashboard > Pages & Theme > Pixel Options > Header > Main Search`


### 12. Change/Disable the Page Title Area
`Dashboard > Pages & Theme > Pixel Options > Header > Page Title Area`

(Also, changeable for a specific page via `Page Title Area Type` & `Disable Page Title Area` page attribute)


### 13. Dark Footer
`Dashboard > Pages & Theme > Pixel Options > Footer > Footer > Dark Footer`

(Also, changeable for a specific page via `Dark Footer` page attribute)


### 14. Add the 'Back to Top' button

`Dashboard > Pages & Theme > Pixel Options > Footer > Footer > Back to Top`


### 15. Enable the Footer Ribbon
`Dashboard > Pages & Theme > Pixel Options > Footer > Footer > Footer Ribbon`

(Also, changeable for a specific page via `Footer Ribbon` page attribute)


### 16. Add the Cookie Disclaimer
`Dashboard > Pages & Theme > Pixel Options > Footer > Cookie Disclaimer`
 

### 17. Change the Owl Slider template height/Button Label
`Dashboard > Pages & Theme > Pixel Options > Blocks > Image Sliders`


### 18. Manually add new classes, change styles, ...
Pixel comes with two specific files which house all your changes without losing them in next updates. For using them:
1. Rename `\theme_pixel\themes\pixel\css\less\custom.dev.less.tmp` to `custom.dev.less` (This will automatically include new file into CSS without losing it in next theme update)
2. Rename `\theme_pixel\themes\pixel\css\less\variables.dev.less.tmp` to `variables.dev.less` (This will automatically include a new file into CSS without losing it on next theme update). You can copy each variable from `variables.less` to `variables.dev.less` and change it as you intend to.
3. [only for 5.7.x] Open `\theme_pixel\themes\pixel\css\style5.7.less` and comment out line 4 & 45

 

### 19. Change the Font Family
Pixel comes with exact instruction on how to manually change the embed and assign new fonts to your site:
1. First, proceed the two steps at Instruction #18
2. Include your fonts at `\theme_pixel\themes\pixel\css\less\custom.dev.less` (A sample is provided in this file which you can uncomment/use it.)
3. Copy the lines that are responsible for assigning the fonts into the new `variables.dev.less` file. Some samples also provided in this file which can be uncommented for your use case. 


### 20. Setup the Coming Soon page
Change page type template to `Coming Soon`, then edit page properties, timer and background image, at `Dashboard > Pages & Theme > Pixel Options > Pages > Coming Soon`. You can also add blocks like Content and Social Icons via page editing UI.


### 21. Make the Top Bar sticky
`Dashboard > Pages & Theme > Pixel Options > Header > Top Bar Area > Sticky Top Bar`

(Also, changeable for a specific page via `Sticky Top Bar` page attribute)

 
### 22. Fix the CTA below the slider (Full Width)
On edit mode, click on block: `Design & Custom Template >  Cog Icon > Block Container Class > Disable Grid Container`


### 23. Add additional 'Main' Areas
Set `Main Area Number` page attribute
 

### 24. Using Express Objects
Pixel uses `Express Objects` for creating a list of `Clients`, `Testimonials` & `Team Members`. This feature is available for concrete5 version 8.1+.

When being installed, the theme creates these express objects. All you need to do is adding entries via `/dashboard/express/entries`. After adding entries, you can display them with core `Express Entry List` block and select one of the templates provided by the theme.
 

### 25. Parallax Effect
Pixel comes with built-in support for creating parallax areas. In order to make a parallax effect in an area:

1. Click on the area name, and select `Edit Area Design`
2. Click on the `Image (Background)` icon, and choose an image. Also, you can select one of the Repeat options there.
3. Click on the `Cog` (Advanced) icon, and insert `parallax` to `Custom Class` textarea. This produces a parallax effect in the area.
4. In addition, there are a number of other classes that can be inserted into the `Custom Class` textarea, which customize the area: 
    - `dark`: makes the content of area light (ideal for dark backgrounds)
    - `color-overlay`: adds an overlay on the top of the image.
    - `color-overlay-black`: adds a black overlay on the top of the image.
    - `color-overlay-white`: adds a white overlay on the top of the image.
    - `color-overlay-01` to `color-overlay-09`: adds opacity to color overlay layer (01-09).

  
### 25.1. Adding additional color overlays
Pixel already contains 2 `color-overlay-black` & `color-overlay-white` classes. These classes respectively paint the area with standard black and white colors. Although these classes combined with transparent classes -- `color-overlay-01` to `color-overlay-09` -- can adequately do the job in many use cases, you might want to add another color. In this case, the new class can be defined in `custom.dev.less`:
```
.color-overlay-red:before { background-color: red; }
```


### 26. Translating to other languages
1. Get the latest translated version of the Pixel in your language [here](https://translate.concrete5.org/translate/package/theme_pixel). (If you already have more completed version, translated into your language, you can complete it online for future users, or send it via a direct message to the Pixel developer, so we can do it.)
2. Copy translated `messages.mo` into `\packages\theme_pixel\languages\{language}_{country}\LC_MESSAGES\messages.mo`

  
### 27. Replacing the Pixel logo with your own logo
`Dashboard > Pages & Theme > Pixel Options > Header > Navigation > Standard Logo, Retina Logo, Standard Logo (Dark), Retina Logo (Dark)`


### 28. Using customized auth pages (Login, Register, Forgot Password)
Add below code to `\application\config\app.php`
```PHP
/*
* Route themes
*/
'theme_paths' => [
    '/login' => 'pixel',
    '/register' => 'pixel',
],
```


### 29. Replacing alternative home pages with the default home page
On the Sitemap drag the alternative page onto default homepage, then select Copy Page: Replace `Home` with the copy of `Home 1`.

### 30. Assigning theme defined margin classes to a block
1. In the edit mode, click on the block and select `Design & Custom Template`.
2. Click on `cog` icon and add one of these classes into `Custom Class` field:
    - Standard Margin: `leftmargin`, `rightmargin`, `topmargin`, `bottommargin`, `allmargin`
    - XSmall Margin: `leftmargin-xs`, `rightmargin-xs`, `topmargin-xs`, `bottommargin-xs`, `allmargin-xs`
    - Small Margin: `leftmargin-sm`, `rightmargin-sm`, `topmargin-sm`, `bottommargin-sm`, `allmargin-sm`
    - Large Margin: `leftmargin-lg`, `rightmargin-lg`, `topmargin-lg`, `bottommargin-lg`, `allmargin-lg`

### 31. Changing the theme footer color
Once the theme has been installed, the footer color can be changed globally by using the built-in theme design customizer. Documentation on how to use this core functionality can be found [here](https://documentation.concrete5.org/editors/in-page-editing/the-toolbar/page-edit-drop-down/design).
