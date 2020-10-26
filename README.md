## Laravel Boilerplate (Current: Laravel 8.*) ([Demo](https://demo.laravel-boilerplate.com))


# install app's dependencies
$ composer install

# install app's dependencies
$ npm install


# create database

### If you choice to use MySQL

Copy file ".env.example", and change its name to ".env".
Then in file ".env" complete this database configuration:
* DB_CONNECTION=mysql
* DB_HOST=127.0.0.1
* DB_PORT=3306
* DB_DATABASE=dbname
* DB_USERNAME=root
* DB_PASSWORD=root

### Set APP_URL

> If your project url looks like: example.com/sub-folder 
Then go to `.env`
And modify this line:


### Next step

``` bash
# in your app directory
# generate laravel APP_KEY
$ php artisan key:generate

# run database migration and seed
$ php artisan migrate:refresh --seed

# generate mixing
$ npm run dev

# and repeat generate mixing
$ npm run dev
```

## Usage

``` bash
# start local server
$ php artisan serve

or

$sudo php artisan serve --port=80

# test
$ php vendor/bin/phpunit
```

Open your browser with address: [localhost:8000](localhost:8000)  


Demo Credentials
* Admin: admin@admin.com
* Password: secret

* User: user@user.com
* Password: secret

----------------------------------------


Swift_TransportException
Cannot send message without a sender address

https://stackoverflow.com/questions/31871806/laravel-homestead-swift-cannot-send-message-without-a-sender-address

.env

MAIL_DRIVER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=25
MAIL_USERNAME= ***USER NAME***
MAIL_PASSWORD= ***PASSWORD***
MAIL_ENCRYPTION=tls


or

Also note:

Port 465 is for Gmail. If it does not work, you can use 25.
The mail.php file is located at /app/config/mail.php (as OP said).
The .env file is located at the root of your project.
Mailtrap.io is a service for testing SMTP. It does not really send emails.


php artisan config:cache



