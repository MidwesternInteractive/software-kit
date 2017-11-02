## Local Environment
If you haven't already, make sure you have your local environment setup.

https://bitbucket.org/snippets/midwesterninteractive/q4zeox/local-environment-setup

# Set Up
*Note* `$` represents a terminal command and should not be typed out.

All commands (unless otherwise specified) should be ran from home dir:
```shell
$ cd
```

## Install Laravel Project
```shell
$ cd ~/projects/
$ laravel new project-name
```
*Note* to change `/projects/` to your project directory if different.

Use the name of the repository as the project name (replacing spaces and special characters), keep in mind that if your using `valet park` instead of `valet link` the project name will become a directory and default your local domain to "project-name.dev".

## Add composer Dependencies
```shell
$ cd project-name
$ composer require midwesterninteractive/software-starter
$ composer install
```


## Javascript Packages
These packages are on an as need basis. Most of the time the themes we incorporate will have these type of things built in. If not these are the packages we use for various features.

---

*For masking inputs*
```shell
$ npm install inputmask
```

*For form validation*
```shell
$ npm install parsleyjs
```

*For select dropdowns/multiselects*
```shell
$ npm install select2
```

*For card based layouts*
```shell
$ npm install masonry-layout
```