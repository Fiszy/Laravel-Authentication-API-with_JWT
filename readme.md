



Authentication API laravel with JWT
Clone the repository<br><br>
git clone https://github.com/Fiszy/Laravel-Authentication-API-with_JWT.git my_auth_app<br><br>
-composer install

-php artisan migrate<br>
-php artisan key:generate<br>
-php artisan jwt:secret<br>
-php artisan serve:serve<br>


## User Registration
You need to download Postman software to make a test with it

. With Postman, and while the test server is running, send a test POST request to the following url: http://localhost:8000/api/auth/register.  Its body should include name, email, and password key/value parameters in a json string. Use whatever values you like for this test user, just remember them as we’ll use them in the next part of this walk through when we authenticate this test user.

## Login

In Postman, send a request to http://localhost:8000/api/auth/login.  Send email and password key/value pairs, w/values corresponding to the test user created .  


## Contributing

 [Fiszy](https://fiszy.easyprevarsity.com).


