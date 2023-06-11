# Docker webserver for Bitrix CMS


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/badges/StandWithUkraine.svg)](https://stand-with-ukraine.pp.ua)


This webserver based on [docker-webserver](https://github.com/a-kryvenko/docker-webserver). All instructions are same as in general webserver configuration.

Main difference is usage of precompiled PHP version specific for Bitrix CMS.

You can choose PHP version by changing version of [andriykryvenko/bitrix-app](https://hub.docker.com/r/andriykryvenko/bitrix-app) image.

```yaml
php:
  image: andriykryvenko/bitrix-app:8.1
```

Available php versions:
 - andriykryvenko/bitrix-app:8.1
 - andriykryvenko/bitrix-app:8.0
 - andriykryvenko/bitrix-app:7.4

Where tag is PHP version.

Bitrix CMS must be in app/public folder.
