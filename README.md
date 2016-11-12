# Skinny Plugin Installer

|StyleCI|Stable Version|Downloads|License|
|:------:|:------:|:------:|:------:|
|[![StyleCI](https://styleci.io/repos/73428628/shield)](https://styleci.io/repos/73428628)|[![Latest Stable Version](https://img.shields.io/packagist/v/SkinnyBot/Plugin-Installer.svg?style=flat-square)](https://packagist.org/packages/skinnybot/plugin-installer)|[![Total Downloads](https://img.shields.io/packagist/dt/skinnybot/plugin-installer.svg?style=flat-square)](https://packagist.org/packages/skinnybot/plugin-installer)|[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://packagist.org/packages/skinnybot/skinny-skeleton)|

A composer installer for installing Skinny plugins.

## Usage
Your plugins themselves do not need to require `skinny/plugin-installer`. They only need to specify the type in their composer config :
```json
"type": "skinny-plugin"
```
