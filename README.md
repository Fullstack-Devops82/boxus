# boxus
ReactJS, Redux, Javascript, Bootstrap

Laravel 5 example
For Laravel 5.3 improved version look at this repository.

Laravel 5 example is a tutorial application for Laravel 5.2 (in french there).

Installation
git clone https://github.com/Fullstack-Devops82/boxus.git projectname
cd projectname
composer install
php artisan key:generate
Create a database and inform .env
php artisan migrate --seed to create and populate tables
Inform config/mail.php for email sends
php artisan vendor:publish to publish filemanager
php artisan serve to start the app on http://localhost:8000/

Another cool way to install it is to upload this package, unpack it in your server folder, and just launch it and follow the installation windows. It has been created with my laravel installer package. Anyway you'll have to set the email configuration.
