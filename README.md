Mega Mitch Credit, Inc. Office Tool (MOT)
==============

MOT is an enterprise (internal) application used by [Mega Mitch Credit, Inc](http://www.megamitch.com) developed using [Zend Framework 2](http://framework.zend.com/).

[![Latest Stable Version](https://poser.pugx.org/codingmatters/megamitch-mot/v/stable.svg)](https://packagist.org/packages/codingmatters/megamitch-mot) [![Total Downloads](https://poser.pugx.org/codingmatters/megamitch-mot/downloads.svg)](https://packagist.org/packages/codingmatters/megamitch-mot) [![Latest Unstable Version](https://poser.pugx.org/codingmatters/megamitch-mot/v/unstable.svg)](https://packagist.org/packages/codingmatters/megamitch-mot) [![License](https://poser.pugx.org/codingmatters/megamitch-mot/license.svg)](https://packagist.org/packages/codingmatters/megamitch-mot) [![Build Status](https://travis-ci.org/CodingMatters/MegaOfficeTool.svg)](https://travis-ci.org/CodingMatters/MegaOfficeTool)

Installation
------------

Using Composer (recommended)
----------------------------
The recommended way to get a working copy of this project is to clone the repository
and use `composer` to install dependencies using the `create-project` command:

    curl -s https://getcomposer.org/installer | php --
    php composer.phar create-project --prefer-source --no-dev codingmatters/megamitch-mot path/to/install

Alternately, clone the repository and manually invoke `composer` using the shipped
`composer.phar`:

    cd my/project/dir
    git clone git://github.com/CodingMatters/MegaOfficeTool.git
    cd MegaOfficeTool
    git submodule init
    git submodue update
    php composer.phar self-update
    php composer.phar install

(The `self-update` directive is to ensure you have an up-to-date `composer.phar`
available.)
