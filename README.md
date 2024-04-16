
# Installation
 Follow these steps to install the application.

1. Clone the Repository

```
git clone https://github.com/MusheAbdulHakim/Laravel-Smarthr.git

```
2. Go to project directory

```
cd Laravel-Smarthr

```

3. Install packages with composer

```
composer install

```


4. Create your database 

5. Rename .env.example to .env Or copy it and paste at project root directory and name the file .env.You can also use this command.

```
cp .env.example ./.env

```
6. Generate app key with this command
```
php artisan key:generate

```

7. Set database connection to your database in the .env file.

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=smarthr
DB_USERNAME=root
DB_PASSWORD=

```
8. Import smarthr.sql file in the database folder, or run migrations
Use this command to run migrations and seeders

```
php artisan migrate --seed

```
9. Start the local server and browser to your app.
This command will start the development server
```
php artisan serve

```

10. Open the address in the terminal in your browser.Usually address is usually like this:
```
http://127.0.0.1:8000

```
11. Enjoy and make sure to star the repo :).Report bugs,features and also send your pull requests I will be happy to merge them.

# admin login credentials

```
 email: admin@admin.com
 password: admin
```

#screenshots

![ScreenShot](screenshots/login.png?raw=true "Login page")
![Dashboard](screenshots/dashboard.png?raw=true "Dashbaord page")
![Dashboard](screenshots/clients.png?raw=true "Clients page")
![Dashboard](screenshots/employees.png?raw=true "employees page")


#for detailed - information do visit our blogpost
<a href="https://medium.com/@sankalp09ghosh/setting-up-laravel-hr-management-system-website-with-aws-services-881956177ebc">Setting up Laravel (HR Management System ) Website with AWS Services</a>
