#### pklaral5esstside(side notes)

1. install amp stack. change port. copy php.ini file.
From C:\MAMP\conf\versionyouchoose\php.ini to bin\php\versionyouchoose
in order to set phpstorm and composer.

2.install composer(download exe file)
note, uncomment
```
extension=php_openssl.dll
```
if already commented.

3.install laravel:
```
composer global require "laravel/installer"
```
laraval executables path:
```
C:\Users\User\AppData\Roaming\Composer\vendor\bin
```
create new app:
```
laravel new hernanapp
cd hernanapp
```
