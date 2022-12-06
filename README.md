News+ Lite
==================

This repository contains the Drupal installation that runs at [drupalizing.com](http://drupalizing.com) and demonstrates the ["News+ Lite"](https://drupal.org/project/newsplus_lite) Drupal theme. We use this repository in order to maintain the above mentioned site and develop the corresponding theme. 

You are welcome however to grab this code and have the demonstration site running on your end. By doing this you have the chance to see the ["News+ Lite" theme in action](http://demo.drupalizing.com/newsplus-lite) exactly the way it looks like on our demo.

Installation instructions
--------------
 + Checkout this repository and Run composer install to download dependecies
 + place the “web” folder under your apache path.
 + Create an empty MySQL database and import there the db file present inside “db_instances/" folder.
 + Start the Drupal installation wizard by pointing your browser to the recently created folder.
 + Continue the installation by selection "Standard" installation profile.
 + In the 4th step enter your recently created database information.
 + In the next step, the installation wizard will recognize that you are using an already populated database and will inform you accordingly. At the same time the wizard should create all the necessary files you Drupal site needs in order to work properly on your server.
 + You are done. Click on "existing site" link and visit your site.

Login to this site by using the following credentials:
- u: admin
- p: password


configure file permissions and add web/sites/default/files directory, settings.php to git .gitignore