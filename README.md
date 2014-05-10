re:source
=========

## A Tool Library Management System

If installing onto the project's official Vagrant development virtual machine (https://github.com/torontotoollibrary/re-source-Vagrant), then login to the vm:
`vagran ssh`

Then clone in the /var/www directory as follows:
`git clone https://github.com/torontotoollibrary/re-source /var/www`

The project source is based on the Laravel PHP framwork. To install the framework dependencies on your system run:
Install composer, if necessary:
`sudo curl -s https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin`
`sudo mv /usr/local/bin/composer.phar /usr/local/bin/composer`
`php composer.phar install` (or just `composer install` if you've installed composer on your system) 
from the root of the application.


## Laravel PHP Framework

[![Latest Stable Version](https://poser.pugx.org/laravel/framework/version.png)](https://packagist.org/packages/laravel/framework) [![Total Downloads](https://poser.pugx.org/laravel/framework/d/total.png)](https://packagist.org/packages/laravel/framework) [![Build Status](https://travis-ci.org/laravel/framework.png)](https://travis-ci.org/laravel/framework) [![License](https://poser.pugx.org/laravel/framework/license.png)](https://packagist.org/packages/laravel/framework)

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as authentication, routing, sessions, and caching.

Laravel aims to make the development process a pleasing one for the developer without sacrificing application functionality. Happy developers make the best code. To this end, we've attempted to combine the very best of what we have seen in other web frameworks, including frameworks implemented in other languages, such as Ruby on Rails, ASP.NET MVC, and Sinatra.

Laravel is accessible, yet powerful, providing powerful tools needed for large, robust applications. A superb inversion of control container, expressive migration system, and tightly integrated unit testing support give you the tools you need to build any application with which you are tasked.

## Official Documentation

Documentation for the entire framework can be found on the [Laravel website](http://laravel.com/docs).

### Contributing To Laravel

**All issues and pull requests should be filed on the [laravel/framework](http://github.com/laravel/framework) repository.**

### License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
