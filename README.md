# urlshortner
 Laravel Url Shortner

 ## Explantion 
I decided to use Laravel for this project because of its ability to manipulate the database, model, controllers and ease of creating routes. Being the first time making a url shortener i had to do some research and learn via some tutorials. 

First thing I made was the database and created the migration, then created the Url Model and then the UrlController. In the UrlController I added what was to be stored and shown via the form to the database then to the user. I edited the welcome.blade.php to have the form and then created a success page which shows the generated short url clickable link.


### Installation ###

* `git clone https://github.com/malachi358/urlshortner.git urlshortner`
* `cd urlshortner`
* `composer install`
* `php artisan key:generate`
* Create a database and inform *.env*
* `php artisan migrate --seed` to create and populate tables
* Inform *config/mail.php* for email sends
* `php artisan vendor:publish` to publish filemanager
* `php artisan serve` to start the app on http://localhost:8000/ or if you are using MAMP and local mysql database you can set that up and inform the *.env* file to match your local settings.