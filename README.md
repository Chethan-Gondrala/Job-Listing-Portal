

![jobby1](https://github.com/user-attachments/assets/676e80fc-26f7-4cae-b7f1-fd4050b80294)


![jobby2](https://github.com/user-attachments/assets/3c9fb3f4-f7c6-41da-8df8-664279705456)

![jobby3](https://github.com/user-attachments/assets/7af1ee4d-124a-4811-991b-5b0cc2187dc4)

## Usage

### Database Setup
This app uses MySQL. To use something different, open up config/Database.php and change the default driver.

To use MySQL, make sure you install it, setup a database and then add your db credentials(database, username and password) to the .env.example file and rename it to .env

### Migrations
To create all the nessesary tables and columns, run the following
```
php artisan migrate
```

### Seeding The Database
To add the dummy listings with a single user, run the following
```
php artisan db:seed
```

### File Uploading
When uploading listing files, they go to "storage/app/public". Create a symlink with the following command to make them publicly accessible.
```
php artisan storage:link
```

### Running The App
Upload the files to your document root, Valet folder or run 
```
php artisan serve
```

## License

The LaraGigs app is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
