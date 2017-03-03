# drupal-console-fa
DrupalConsole Farsi Language / به زبان فارسی

# نسخه به زبان فارسی

## Usage

Drupal Console project it's installed per each Drupal 8 website with English language by default.

To installe Drupal Console package for Farsi language run the following instructions

```
$ composer require drupal/console-fa
```

### Install Drupal Console

To install the appropriate version of Drupal Console prohect for your drupal installation, run the following composer command

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Install Drupal Console launcher

In order to avoid conflicts between Drupal release and have a Drupal Console version between major and minor releases in Drupal, in order to faciliate to load the Drupal Console commands available to each
Drupal 8 website, a Drupal Console launcher was created.
 
Following the instruction below you could install the global application for Drupal Console launcher. 

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Contribute

If you want to contribute to this translation, you need to follow this steps

- Fork this repository following this link [https://github.com/hechoendrupal/drupal-console-fa#fork-destination-box](https://github.com/hechoendrupal/drupal-console-fa#fork-destination-box)
- Clone your repostory forked in your local machine.
- Set up upstream

In order to be updated with other contribution you must to setup a connected with main repository using the following git command

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-fa.git
```

To fetch the latest contribution before to star you must to run the next commands

```
$ git fetch upstream
$ git merge upstream/master
```

N.B: Push your changes to your forked repository in order to create PR per day to avoid any conflicts with other contributors.
