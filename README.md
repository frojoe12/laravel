# laravel
tips for laravel -- mac

install
vagrant, virtual box, composer,

- 1.
vagrant box add laravel/homestead     optional : --box-version 8.1.0 

- 2.
after installing composer move composer.phar to the /usr/bin/local/composer directory
mv composer.phar /usr/local/bin/composer

- 3. 
in project directory
composer create-project --prefer-dist laravel/laravel project-name
