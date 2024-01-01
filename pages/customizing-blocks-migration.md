## Customizing Blocks: Old Template Migration 

In the previous version, Pixel came with multiple templates for each block. This guide lists the previous templates and the equivalent templates [`classes`] on the Pixel 9.


### CTA block (Button)
1. pixel_btn: _pixel_button_
2. pixel_btn_simple_right: _pixel_button_ [`utl:text:align:end`]
3. pixel_btn_rounded: _pixel_button_ [`button:rounded`]
4. pixel_btn_rounded_right: _pixel_button_ [`button:rounded`,`utl:text:align:end`]
5. pixel_btn_reveal: _pixel_button_ [`button:reveal`]
6. pixel_btn_reveal_right: _pixel_button_ [`button:reveal`,`utl:text:align:end`]
7. pixel_btn_full: _pixel_button_ [`button:full`]
8. pixel_btn_circle: _pixel_button_ [`button:circle`]
9. pixel_btn_circle_right: _pixel_button_ [`button:circle`,`utl:text:align:end`]
10. pixel_btn_border: _pixel_button_ [`button:border`]
11. pixel_btn_border_right: _pixel_button_ [`button:border`,`utl:text:align:end`]
12. pixel_btn_border_thin: _pixel_button_ [`button:border`,`button:border-thin`]
13. pixel_btn_border_thin_right: _pixel_button_ [`button:border`,`button:border-thin`,`utl:text:align:end`]
14. pixel_btn_border_fill_effect: _pixel_button_ [`button-border`,`button-fill`]
15. pixel_btn_border_fill_effect_right: _pixel_button_ [`button-border`,`button-fill`,`utl:text:align:end`]
16. pixel_btn_3d: _pixel_button_ [`button:style:3d`]
17. pixel_btn_3d_right: _pixel_button_ [`button:style:3d`,`utl:text:align:end`]


### CTA block (Promo Boxes)
1. pixel_promo: _pixel_promo_
2. pixel_promo_light: _pixel_promo_ [`promo:light`]
3. pixel_promo_full: _pixel_promo_ [`promo:full`]
4. pixel_promo_full_parallax: _pixel_promo_ [`promo:full`,`promo:color:transparent`]
5. pixel_promo_full_light: _pixel_promo_ [`promo:full`,`promo:light`]
6. pixel_promo_full_dark: _pixel_promo_ [`promo:full`,`promo:dark`]
7. pixel_promo_full_color: _pixel_promo_ [`promo:full`,`promo:color:theme`]
8. pixel_promo_dark: _pixel_promo_ [`promo:dark`]
9. pixel_promo_color: _pixel_promo_ [`promo:color:theme`]
10. pixel_promo_border: _pixel_promo_ [`promo:border`]
11. pixel_promo_border_right: _pixel_promo_ [`promo:border`,`utl:text:align:end`]
12. pixel_promo_border_center: _pixel_promo_ [`promo:border`,`utl:text:align:center`]


### CTA block (Image Feature Box)
1. pixel_image_feature_box: _pixel_image_feature_box_
2. pixel_image_feature_box_bordered: _pixel_image_feature_box_ [`ifb:border`]
3. pixel_image_feature_box_fancy_title: Deprecated


### Pricing Table block
1. view: _view_ 
2. pixel_light: _view_ [`pricing:minimal`]
3. pixel_horizontal: Deprecated


### Content block (Title)
1. pixel_fancy_title_bottom_border_short: _pixel_page_title_ [`title:bottom-border:short`]
2. pixel_fancy_title_bottom_border: _pixel_page_title_ [`title:bottom-border`]
3. pixel_fancy_title_center_aligned: Deprecated
4. pixel_fancy_title_emphasis: _pixel_page_title_ [`title:emphasis`,`title:dark`,`utl:text:align:center`]
5. pixel_fancy_title_left_aligned_border_double: Deprecated
6. pixel_fancy_title_left_border: _pixel_page_title_ [`title:left-border`]
7. pixel_fancy_title_right_aligned: _pixel_page_title_ [`title:bottom-border`,`utl:text:align:end`]
8. pixel_fancy_title: _pixel_page_title_


### Faq block
1. pixel_1: _pixel_toggle_


### Feature block
1. pixel_side_icon: _pixel_feature_box_
2. pixel_centered_icon: _pixel_feature_box_ [`fbox:layout:center`]
3. pixel_bordered: _pixel_feature_box_ [`fbox:layout:bordered`]


### File block
1. pixel: _pixel_ [`promo:border`,`buttom:style:3d`,`fileinfo:show-type`,`fileinfo:show-size`]
2. pixel_light: _pixel_ [`promo:light`,`buttom:dark`,`fileinfo:show-type`,`fileinfo:show-size`]
3. pixel_dark: _pixel_ [`promo:dark`,`fileinfo:show-type`,`fileinfo:show-size`]
4. pixel_color: _pixel_ [`promo-dark`,`bg-color`,`buttom:light`,`fileinfo:show-type`,`fileinfo:show-size`]


### Horizontal Rule (Spacers / Dividers) block
1. pixel: _pixel_ 
2. pixel_left: _pixel_ [`icon:circle`]
3. pixel_center: _pixel_ [`divider:center`,`icon:circle`]
4. pixel_right: _pixel_ [`divider:right`,`icon:circle`]
5. pixel_left_short: _pixel_ [`divider:left`,`icon:circle`,`divider:sm`]
6. pixel_left_rounded: _pixel_ [`divider:left`,`icon:circle`,`divider:rounded`]
7. pixel_left_rounded_short: _pixel_ [`divider:left`,`icon:circle`,`divider:sm`,`divider:rounded`]
8. pixel_left_border: _pixel_ [`divider:left`,`icon:circle`,`divider:border`]
9. pixel_left_border_short: _pixel_ [`divider:left`,`icon:circle`,`divider:sm`,`divider:border`]
10. pixel_right_short: _pixel_ [`divider:right`,`icon:circle`,`divider:sm`]
11. pixel_right_rounded: _pixel_ [`divider:right`,`icon:circle`,`divider:rounded`]
12. pixel_right_rounded_short: _pixel_ [`divider:right`,`icon:circle`,`divider:sm`,`divider:rounded`]
13. pixel_right_border: _pixel_ [`divider:right`,`icon:circle`,`divider:border`]
14. pixel_right_border_short: _pixel_ [`divider:right`,`icon:circle`,`divider:sm`,`divider:border`]
15. pixel_center_short: _pixel_ [`divider:center`,`icon:circle`,`divider:sm`]
16. pixel_center_rounded: _pixel_ [`divider:center`,`icon:circle`,`divider:rounded`]
17. pixel_center_rounded_short: _pixel_ [`divider:center`,`icon:circle`,`divider:sm`,`divider:rounded`]
18. pixel_center_border: _pixel_ [`divider:center`,`icon:circle`,`divider:border`]
19. pixel_center_border_short: _pixel_ [`divider:center`,`icon:circle`,`divider:sm`,`divider:border`]


### Page List block
1. pixel_blog_full: _pixel_blog_grid_ [`grid:1`]
2. pixel_blog_grid_2: _pixel_blog_grid_ [`grid:1`,`grid:sm:2`]
3. pixel_blog_grid_3: _pixel_blog_grid_ [`grid:1`,`grid:sm:2`,`grid:md:3`]
4. pixel_portfolio_grid_6: _pixel_portfolio_grid_ [`grid:1`,`grid:sm:2`,`grid:md:6`]
5. pixel_portfolio_grid_4: _pixel_portfolio_grid_ [`grid:1`,`grid:sm:2`,`grid:md:4`]
6. pixel_portfolio_grid_3: _pixel_portfolio_grid_ [`grid:1`,`grid:sm:2`,`grid:md:3`]
7. pixel_portfolio_grid_2: _pixel_portfolio_grid_ [`grid:1`,`grid:sm:2`]
8. pixel_portfolio_grid_1: _pixel_portfolio_grid_ [`grid:1`]
9. pixel_portfolio_carousel: _pixel_portfolio_carousel_ [`grid:2`,`grid:md:3`,`grid:md:4`]


### Page Title block
1. pixel_fancy_title_left_border: _pixel_ [`title:left-border`]
2. pixel_fancy_title_bottom_border_short: _pixel_ [`title:bottom-border:short`]
3. pixel_fancy_title_bottom_border: _pixel_ [`title:bottom-border`]
4. pixel_fancy_title_center_aligned: _pixel_ [`title:fancy-border:double`,`title:align:center`]
5. pixel_fancy_title_left_aligned: _pixel_ [`title:fancy-border:single`]
6. pixel_fancy_title_left_aligned_border_double: _pixel_ [`title:fancy-border:double`]
7. pixel_fancy_title_right_aligned: _pixel_ [`title:fancy-border:double`,`title:align:right`]
8. pixel_blog_title: _pixel_blog_entry_title_


### Social Link block
1. pixel: _pixel_


### Testimonial block
1. pixel_grid: _pixel_
2. pixel_list: _pixel_ [`layout:center`]
