# Tutorial-wordpress
My personal blog https://bhishanpoudel.ml 

# Log in to wordpress and go to admin page
- First go to the website  https://bhishanpoudel.ml.
- Then we add `/wp-admin` and make it https://bhishanpoudel.ml/wp-admin.

# Customize the theme
Follow these steps:  

  `Bhishan Poudel > Themes > Meditation > Editor > functions.php` 
  
  Then, search for `footer_text` and edit the line.
 
 Before:

```php
'footer_text' => '<a href="' . esc_url( __( 'http://wordpress.org/', 'meditation' ) ) . '">' . __( 'Powered by WordPress', 'meditation' ). '</a> | ' . __( 'theme ', 'meditation' ) . '<a href="' .  esc_url( __( 'https://visualpharm.com/wpblogs/themes/theme/meditation/', 'meditation') ) . '">Meditation</a>',

```
After:
 ```php
 'footer_text' => '&copy; BHISHAN POUDEL',
 ```
 
 
