# Tutorial-wordpress
My personal blog https://bhishanpoudel.ml  

# Change footer of the website
Let's say we have the theme `meditation` then we have the footer

```php
'footer_text' => '<a href="' . esc_url( __( 'http://wordpress.org/', 'meditation' ) ) . '">' . __( 'Powered by WordPress', 'meditation' ). '</a> | ' . __( 'theme ', 'meditation' ) . '<a href="' .  esc_url( __( 'https://visualpharm.com/wpblogs/themes/theme/meditation/', 'meditation') ) . '">Meditation</a>',

```

 Which we want to change to:
 ```php
 'footer_text' => '&copy; BHISHAN POUDEL',
 ```
 
 We first go to our blog  https://bhishanpoudel.ml, then we add `/wp-admin` and make it
  https://bhishanpoudel.ml/wp-admin.
  
  Then we login to our website.
  `Bhishan Poudel > Themes > Meditation > Editor > functions.php` search for `WordPress`, we may go the line with `footer_text` and rewrite this line.
  
  Update the file and refresh the page.
