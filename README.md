# SmallStack

SmallStack is the smallest and simplest way to start a website with php, oldskool style. It contains a `Router` and the `Blade template engine`. Just download the template, upload it to your webserver and you're done. Modular and with 0 dependencies.

# Creating modules

A module is a subfolder of `/modules` and contains a controller (uppercase filename, contains the routes for this controller) and some Blade templates. Take a look at `/modules/Default.php` for the default controller. To load a module, simply include it in `/public/index.php`
