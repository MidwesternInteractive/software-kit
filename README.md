## Local Environment
If you haven't already, make sure you have your local environment setup.

https://bitbucket.org/snippets/midwesterninteractive/q4zeox/local-environment-setup

# Set Up
Note `$` represents a terminal command and should not be typed out.

All commands (unless otherwise specified) should be ran from home dir:
```shell
$ cd
```

## Install Laravel
```shell
$ cd ~/projects/
$ laravel new project-name
```

Use the name of the repository as the project name (replacing spaces and special characters), keep in mind that if your using `valet park` instead of `valet link` the project name will become a directory and default your local domain to "project-name.dev".

## Add composer Dependencies
```shell
$ cd project-name
$ composer require midwesterninteractive/software-starter
$ composer install
```

## Add Node Dependencies
