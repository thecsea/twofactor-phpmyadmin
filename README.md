# twofactor-phpmyadmin
Build status:  [![Latest Stable Version](https://poser.pugx.org/thecsea/twofactor-phpmyadmin/v/stable)](https://packagist.org/packages/thecsea/twofactor-phpmyadmin) [![Total Downloads](https://poser.pugx.org/thecsea/twofactor-phpmyadmin/downloads)](https://packagist.org/packages/thecsea/twofactor-phpmyadmin) [![Latest Unstable Version](https://poser.pugx.org/thecsea/twofactor-phpmyadmin/v/unstable)](https://packagist.org/packages/thecsea/twofactor-phpmyadmin) [![License](https://poser.pugx.org/thecsea/twofactor-phpmyadmin/license)](https://packagist.org/packages/thecsea/twofactor-phpmyadmin)

The most powerful and the simplest library to add two factor authentication by google authenticator in phmyadmin

This project install automatically a phpmyadmin with twofactor via composer (download composer here https://getcomposer.org/):

`php composer.phar require thecsea/twofactor-phpmyadmin `

When this readme is written, *phpmyadmin* package is not recognized as *stable*, so you cannot use require way but you have to clone repository

`git clone https://github.com/thecsea/twofactor-phpmyadmin.git`

and install it with composer

`php composer.phar install`
 
*twofactor-phpmyadmin* is based on [twofactor-dir library](https://github.com/thecsea/twofactor-dir), take a look to it to see how to use twofactor

Obviously when you perform an composer update the twofactor is reinstalled, so you could lose your secret.

Update: `php composer.phar update`

# Credits
* [Sonata GoogleAuthenticator](https://github.com/sonata-project/GoogleAuthenticator): php library to use twofactor in the same way of google authenticator
* [twofactor dir](https://github.com/thecsea/twofactor-dir): php library to protect a dir via two factor
* [phpmyadmin](https://github.com/phpmyadmin/phpmyadmin): php library to manage a mysql server

# By [thecsea.it](http://www.thecsea.it)
