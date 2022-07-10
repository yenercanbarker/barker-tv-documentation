---
description: You can follow the steps on the right below to install the script.
---

# Installation

## Deployment

Installation for Cpanel : Just upload the .zip file to your hosting an extract it, thats all.

Installation for Any Shared Hosting : Just upload the .zip file to your hosting an extract it, thats all.



Installation for Custom Hosting with SSH :&#x20;

1- Deploy the project files to your hosting.

2- Open your project's main folder on terminal.

3- run that command : composer install

4- run that command : php artisan key:generate

5- Configure .env file, add your app and database values

6- run that command : php artisan migrate

7- If images are not loading, add ReWrite Access Rule in .htaccess file which you can check this out  : [https://dev.to/vumanhtrung/setup-an-htaccess-file-for-redirecting-to-laravel-s-public-folder-1e1j](https://dev.to/vumanhtrung/setup-an-htaccess-file-for-redirecting-to-laravel-s-public-folder-1e1j)&#x20;



* You need to give all permissions to **Images** folder, to upload images.
* After Installation you need to create a mysql database on hosting, and then upload the .sql file which is inside the .zip file of Barker TV.



Installation is done! You need to configure the app right now.
