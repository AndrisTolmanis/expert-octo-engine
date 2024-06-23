# expert-octo-engine

A starting point to create Vue + Laravel web applications.

High level technologies used:
 - Laravel 11
 - Vite 5
 - Vue 3

## To get running:

### 1 Use Linux (Ubuntu) OS or Windows Subsystem for Linux (WSL) when using Windows.
[Ubuntu](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview)
[WSL](https://learn.microsoft.com/en-us/windows/wsl/install)

### 2 Install PHP 8.2
[PHP](https://ubuntu.com/server/docs/how-to-install-and-configure-php)

```bash
sudo apt install php8.2-{bcmath,xml,fpm,mysql,zip,intl,ldap,gd,cli,bz2,curl,mbstring,pgsql,opcache,soap,cgi}
```

### 3 Install Composer
[Composer](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-composer-on-ubuntu-20-04)

### 4 Install NPM
[NPM](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04)

### 5 Install mysql
[MySQL](https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-20-04)

```bash
sudo mysql
```
```bash
CREATE USER 'silly'@'localhost' IDENTIFIED BY 'password';
```
```bash
GRANT ALL PRIVILEGES ON *.* TO 'silly'@'localhost' WITH GRANT OPTION;
```
```bash
FLUSH PRIVILEGES;
```
```bash
exit
```

### 6 Clone or download repository
```bash
cd expert-octo-engine
```

### 7 Install what you have downloaded
```bash
composer install
```
```bash
npm install
```

### 8 Run
```bash
php artisan serve
```
```bash
npm run dev
```