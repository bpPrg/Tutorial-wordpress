# Tutorial-wordpress
My personal blog https://bhishanpoudel.ml 

# Log in to wordpress and go to admin page
- First go to the website  https://bhishanpoudel.ml.
- Then we add `/wp-admin` and make it https://bhishanpoudel.ml/wp-admin.

# Adding 3d Flip Book
First decrese the pdf size [online](https://www.ilovepdf.com/compress_pdf).
```
1. Upload small sized pdf file to Media.
2. Go to the 3D FlipBook Plugin (Left hand sidebar) and create a new book.
3. Go to the Posts and add a new post.
4. Click on Yello Book like icon to include the 3d book and publish it.
5. Click view post to see how it looks now.
```

# Customize the theme (for example meditation theme)
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
 
 
# Crawling on google
```
1. go to https://www.google.com/webmasters/tools/home?hl=en
2. click on the thumbnail of your latest post
3. Go to crawl
4. Go to Fetch As Google
5. Copy the post name after the basename of the website. eg (how-to-create-a-nice-talk-for-astro-seminar/)
   Note: do not copy initial / sign at the end of the base url
6. Click Fetch
7. Tick Crawl only this
```
