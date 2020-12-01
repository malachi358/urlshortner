# urlshortner
 Laravel Url Shortner

 ## Explantion 
I decided to use Laravel for this porject becuase of it's ability to manipulate the database, model, controllers and ease of createing routes.

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