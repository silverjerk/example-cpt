# Example CPT using PostTypes
This is an example WordPress custom post type as a plugin using the fantastic [PostTypes](https://github.com/jjgrainger/PostTypes).

## If you want to adapt this for your own work
* Update `composer.json` to change the name of the plugin and the PSR-4 autoload namespace
* Update the plugin block and namespace in `plugin.php`, and the namespace in `app/init.php`
* Update all instances of `EXAMPLECPT_PLUGIN_DIR` and `EXAMPLECPT_PLUGIN_URL`
* Run `composer update` to regenerate the autoload files
* Rename and update `app/types/example.php` to fit your needs

Add the plugin to your WordPress `plugins` or `mu-plugins` directory.
