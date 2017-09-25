# wp-login-css
#functions.php中加入
<code>
  function lb_enqueue_login_style() {
    wp_enqueue_style( 'admin-login', get_template_directory_uri() . '/app/admin-login.css' );
}
add_action( 'login_enqueue_scripts', 'lb_enqueue_login_style' );
</code>
