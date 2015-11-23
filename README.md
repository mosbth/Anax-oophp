[![Build Status](https://travis-ci.org/mosbth/Anax-oophp.svg)](https://travis-ci.org/mosbth/Anax-oophp)
[![Build Status](https://scrutinizer-ci.com/g/mosbth/Anax-oophp/badges/build.png?b=master)](https://scrutinizer-ci.com/g/mosbth/Anax-oophp/build-status/master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/mosbth/Anax-oophp/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/mosbth/Anax-oophp/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/mosbth/Anax-oophp/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/mosbth/Anax-oophp/?branch=master)

Anax-oophp
=========

[![Join the chat at https://gitter.im/mosbth/Anax-oophp](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/mosbth/Anax-oophp?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Anax-oophp builds upon Anax-base.

Anax-oophp is used as course material in the university course http://dbwebb.se/oophp.

Built by Mikael Roos, me@mikaelroos.se.



License 
------------------

This software is free software and carries a MIT license.



Use of external libraries
-----------------------------------

The following external modules are included and subject to its own license.



### Modernizr
* Website: http://modernizr.com/
* Version: 2.6.2
* License: MIT license 
* Path: included in `webroot/js/modernizr.js`



History
-----------------------------------


v1.0.1 (2015-04-01)

* Adding build on scrutinizer.
* Adding build on travis.
* Adding phpunit.
* Fixed CTextFilter to PHP 5.3.
* Fixed CTextFilter makeClickable leaving backslashes, fix #3.
* Fixed exception message in CTextFilter to fix #2.
* Cloned Anax-bas to be the base for Anax-oophp.
* Changed how jQuery is included, now using `jquery` and `jquery_src`.
* Added dynamic menu / navbar in `webroot/config.php`, `theme/index.tpl.php` and `theme/functions.php`.
* Changed order of including bootstrap.php and starting session in `config.php`. Compatible with anax-base v1.0.2.
* Changed default directory for displaying source code to '..' in `webroot/source.php`.
* Naming of session in `webroot/config.php` allows only alphanumeric characters.


v1.0.0 (2013-06-28)

* First release after initial article on Anax.



------------------
 .  
..:

Copyright (c) 2013-2015 Mikael Roos
