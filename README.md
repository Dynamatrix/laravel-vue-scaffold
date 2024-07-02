<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width=300px" alt="Laravel Logo"></a></p>
<p align="center"><a href="vuejs.org" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1200px-Vue.js_Logo_2.svg.png" width="100px" alt="Vue"></a></p></p>

## About the laravel-vue scaffold

The laravel-vue scaffold is a template repository usable for new projects that rely on Laravel and Vue. This scaffold combines the two in such a way that they work together efficiently and without issue. Laravel handling the back-end, API and database connections, while Vue handles the front-end, routing and API calls to the back-end.

### Stack

- Laravel
- Vue
- SCSS
- Tailwind
- MySQL

### Setup
You can use this scaffold by pulling it and changing the git remote, or by using `composer create-project dynamatrix/laravel-vue`.
You can find the scaffold on [packagist](https://packagist.org/packages/dynamatrix/laravel-vue).

#### Prerequisites:
- MySQL database (MariaDB is recommended) with database and user:
```shell
$ sudo apt update
$ sudo apt install mariadb-server
$ sudo mysql_secure_installation
```

For the configuration, please read [this article by DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-install-mariadb-on-ubuntu-22-04#step-2-configuring-mariadb)

- Node 20.12.x
- PHP 8.3.x

#### Installation
After setup, if you have Node and PHP installed; you may continue by using the installers:
```shell
$ npm install
$ composer install
```

After that, you may run the application using
```shell
$ php artisan serve
$ npm run watch
```

Axios is installed for the communication between front-end and backend. You may use Axios to make api calls to the laravel backend.

For information on how to use Vue, Laravel, SCSS, Tailwind and Mysql:
- https://laravel.com/docs
- https://vuejs.org/guide/introduction.html
- https://sass-lang.com/documentation/syntax/
- https://tailwindcss.com/docs/installation
- MySQL:
  - https://www.digitalocean.com/community/tutorials/how-to-create-a-new-user-and-grant-permissions-in-mysql
  - https://www.digitalocean.com/community/tutorials/how-to-create-and-manage-databases-in-mysql-and-mariadb-on-a-cloud-server
