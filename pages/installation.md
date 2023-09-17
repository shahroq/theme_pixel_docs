## Installation

### Installation Instructions
1. Download the package and extract files into your site's `/package` folder.
2. Log in to your site as an admin
3. Click on `Extend concrete5` and press the `Pixel Theme` Install button.
4. In order to verify if the theme has been installed completely, check `Instructions` page #36, #37.

### Installation Via CLI
1. Download the package and extract files into your site's `/package` folder.
2. To run CLI commands, open a terminal console and make the Concrete webroot folder the current directory. [(more info)](https://documentation.concretecms.org/developers/framework/console-commands-and-jobs/command-line-interface-cli-commands)
3. Depend on whether you want to install with or without sample content, run one of these commands:
```
// without sample content
$ concrete/bin/concrete5 c5:package-install theme_pixel9
// with sample content
$ concrete/bin/concrete5 c5:package-install theme_pixel9 --full-content-swap
```
4. In order to verify if the theme has been installed completely, check `Instructions` page #36, #37.
 
### After Installation
If the theme were installed with the sample contents, you should notice a number of discrepancies between your site and the theme demo site due to some shortcomings when it comes to the sample contents. The good news is that these differences can be easily fixed. Below, a list of these issues and how they can be addressed are listed:

1. Express Entries (Client, Testimonial, Team Member) are not imported: 
    - Go to `Dashboard > Express` and you see all the `Express Objects` already have been created on your site.
    - Click on each entity and start adding new entries.
    - Go back to the page where an `Express Object` is needed, and add the `List` block -under the `Express` category- to your page. Select the Entity (Client, Testimonial, Team Member) and add it to your page.
    - From the list of templates, select one, depending on which entity you have already chosen.
