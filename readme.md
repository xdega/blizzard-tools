# Blizzard Tools

A collection of Drupal Modules to facilitate working with Battle.net REST APIs, and to help build community websites based on Blizzard Entertainment IPs, on the Drupal platform.

## Getting Started

You must have Docker installed on the host machine.

While this comes with the required themes and modules installed, you should run `composer install` from the project root. 

If you don't have composer installed natively (preferred) you may use the Docker image (https://hub.docker.com/_/composer) (unsupported)

You should run the following command on first load, in order to make the default files directory writable: 

`sudo chmod 777 web/sites/default/files/`

Then you can simply run:

`docker-compose up`

You should wait approx *10 seconds* for the SQL backup script to complete before the website will be accessible.

The website should be running at: **localhost:8080/web**

PHP My Admin is available at: **localhost:8001**


## Contributing

Pull requests should only be to improve the Docker development environment and should be fully portable to work on Windows, Linux, and Mac.

## Using Premade Install

This project is a pre-installed version of Drupal, with the following credentials for admin login:

**username:** `drupal` **password:** `guest`
