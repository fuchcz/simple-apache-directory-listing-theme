SIMPLE: Apache Directory Listing Theme
======================================

[https://miroslavpokorny.com/simple-apache-directory-listing-theme/](https://miroslavpokorny.com/simple-apache-directory-listing-theme/)

This theme turns that ugly default file listing by autoindex mod in Apache into this:

![](https://fuchcz.github.io/simple-apache-directory-listing-theme/images/simple-screenshot.jpg)

## Installation ##

### Apache configuration ###

1. Download and extract `simple` from `conf` directory.
2. Use `example.conf` to edit conf file for selected directory / virtual host . (E.g. edit `/etc/apache2/sites-available/000-default.conf` in Ubuntu to use theme everywhere.)
3. Reload Apache.

### .htaccess ###

1. Download and extract `simple` from `htaccess` directory.
2. Either put `simple` in the root and rename `.htaccess.root`, or replace every occurrence of `{SIMPLE_DIRECTORY}` by real path in `.htaccess.customdir` and use it.
3. Reload Apache. 

## Options ##

At `footer.html` there is `ignoreDirectories` variable, where you can set number of directories that should be hidden in breadcrumb navigation.

There is also `ignoreAsNoLink` variable that sets whether to ignore as 'do not display' or ignore as 'no links, but visible'.

## Troubleshooting ##

If you have trouble running `.htaccess` version, try to look at `AllowOverride` directive. 

## Licence ##

[MIT](https://opensource.org/licenses/MIT).

## Footnotes ##

Icons by [Yusuke Kamiyamane](http://p.yusukekamiyamane.com).
