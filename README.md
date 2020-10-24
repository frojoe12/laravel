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

- 4.
cd into project
composer require laravel/homestead --dev
MAC: php vendor/bin/homestead make
WINDOWS: vendor\\bin\\homestead make

- 5.
keygen
(path to private key not found on "vagrant up" - generate new key pair)
ssh-keygen -t rsa -f ~/.ssh/id_rsa

- 6.
vagrant up
vagrant ssh
cd code

-7.
edit etc/hosts

192.168.10.10 local.test
