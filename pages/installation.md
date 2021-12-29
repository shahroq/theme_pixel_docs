## Installation

### Installation Instructions
1. Download package and extract files into your site's `/package` folder.
2. Log in to your site as an admin
3. Click on `Extend concrete5` and press the `Pixel Theme` Install button.
4. In order to verify if the theme has been installed completely, check `Instructions` page #36, #37.

 
### After Installation
If the theme were installed with the sample contents, you should notice a number of discrepancies between your site and the theme demo site due to some shortcomings when it comes to the sample contents. The good news is that these differences can be easily fixed. Below, a list of these issues and how they can be addressed are listed:

1. The CTA block below the slider on homepage and many other pages are not 'Full Width'
    - Click on the `CTA` block and select `Design & Custom Template`.
    - Click on the `Cog` icon beside the `Cancel` button.
    - On `Block Container Class` choose `Disable Grid Container`, and save the block.

2. Express Entries (Client, Testimonial, Team Member) are not imported: 
    - Go to `Dashboard > Express` and you see all the `Express Objects` already have been created on your site.
    - Click on each entity and start adding new entries.
    - Go back to the page where an `Express Object` is needed, and add the `List` block -under the `Express` category- to your page. Select the Entity (Client, Testimonial, Team Member) and add it to your page.
    - From the list of templates, select one, depending on which entity you have already chosen.

3. Mega Menu
    - Going to `Dashboard > Stacks & Blocks > Stacks & Global Area`, you should see a Stack named `mega_menu_blocks` is created on your list. This is a sample `Stack` indicating how a `Meg Menu` for one of your main menu items should be built.
    - In order to assign this `Mega Menu` to the main menu, go to `Dashboard > Sitemap`, click on the page you intend to assign (in this case it should be the `Blocks` page), select `Attributes`, and add `Stack` name (`mega_menu_content`) to the `Mega Menu Content` attribute.
    - Also, you may notice the links to the pages on the mega menu are not set. To fix this, go to the `mega_menu_blocks` stack, and fix the URL of each item in the menu.

4. The Horizontal Rules(Spacer/Dividers) blocks are 'Full Width`
    - Click on the block and select `Design & Custom Template`
    - Click on `Cog` icon beside `Cancel` button
    - On `Block Container Class` select `Enable Grid Container`
