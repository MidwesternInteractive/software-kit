## Local Environment
If you haven't already, make sure you have your local environment setup.

[Local Environment Setup](https://gist.github.com/MidwesternInteractive/1f59de79ea114403fb16a072ff03d9de)

# Set Up
__*Note*__ `$` represents a terminal command and should not be typed out.

All commands (unless otherwise specified) should be ran from home dir:
```shell
$ cd
```

## Install Laravel Project
```shell
$ cd ~/projects/
$ laravel new project-name
```
__*Note*__ to change `/projects/` to your project directory if different.

Use the name of the repository as the project name (replacing spaces and special characters), keep in mind that if your using `valet park` instead of `valet link` the project name will become a directory and default your local domain to "project-name.dev".

## Add composer Dependencies
```shell
$ cd project-name
$ composer require midwesterninteractive/software-starter
$ composer install
```


## JavaScript Packages
These packages are on an as need basis. If a theme was incorporated they may not be necessary.

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