Moderate/Advanced Commands
====

Welcome to the command line it is a wonderfull place!

Debugging
----

`tail -f` - Running this command followed by a file patch will output the the last few lines of a file in the command line window, and continue to display additions to the bottom of the file until typing `ctrl c`. This is extremely handy for monitoring a WordPress `debug.log` file in the `wp-content` directory. To output the log, both `WP_DEBUG` and `WP_DEBUG_LOG` need to be true in your [`wp-config.php` file](http://codex.wordpress.org/Editing_wp-config.php#Configure_Error_Logging).