# Server Requirements
--------------------------
PHP version 5.6 or newer is recommended.

# Installation
--------------------------
## Create project
1. Run composer create project (for init new project) or update (for reload dependencies on new environment) via command line at root folder
* Create project
```shell
composer create-project ngthuc/ci-custom-core
```
* Reload dependencies
```shell
composer update
```
2. Create .env file same [.]env to set-up database
## Require project into another project
1. Run composer require project (for init new project) or update (for reload dependencies on new environment) via command line at root folder
* Require project
```shell
composer require ngthuc/ci-custom-core
```
* Reload dependencies
```shell
composer update
```
2. Move all files from `/vendor/ngthuc/ci-custom-core/app/` to the root folder structure:
```shell
root                          # → Root Directory
└── vendor/
    └── ngthuc/
        └── ci-custom-core/
            └── app/
                ├── apllication/
                ├── public/
                ├── .bowerrc
                ├── .editorconfig
                ├── .gitignore
                ├── .htaccess
                ├── [.]env
                ├── bower.json
                ├── index.php
                └── license.txt
```
3. Create .env file same [.]env to set-up database

# Author
--------------------------
* [Nguyen Thuc](https://ngthuc.github.io/)
* Homepage: ngthuc.com
* Packagist: [CodeIgniter custom core](https://packagist.org/packages/ngthuc/ci-custom-core) by ngthuc
* Email: contact[at]ngthuc.com

# Credit
--------------------------
This project using projects or dependencies:
* CodeIgniter by [B.C. Institute of Technology](https://github.com/bcit-ci/CodeIgniter) (originally from EllisLab).
* PHP dotenv by [vlucas](https://github.com/vlucas/phpdotenv).

# License
--------------------------
CodeIgniter Core Custom is licensed under [MIT License](LICENSE).
