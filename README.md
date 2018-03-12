EasyAdmin Demo
==============

A Symfony demo backend to show [EasyAdmin](https://github.com/javiereguiluz/EasyAdminBundle) features.

How to install this project
---------------------------

  1. `git clone https://github.com/javiereguiluz/easy-admin-demo`
  2. `cd easy-admin-demo`
  3. `composer install`
  4. `php bin/console doctrine:database:create`
  5. `php bin/console doctrine:schema:create`
  6. `php bin/console doctrine:fixtures:load --append`
  7. `php bin/console assets:install --symlink`
  8. `php bin/console server:run`
  9. Browse `http://127.0.0.1:8000/admin/`
