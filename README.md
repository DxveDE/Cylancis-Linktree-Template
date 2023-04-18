# Cylancis Linktree Template
[![](https://img.shields.io/badge/Language-PHP,%20HTML%20&%20CSS-darkblue)](#)
[![](https://img.shields.io/badge/CSS-Bootstrap%205.3-purple)](#)

Cylancis is a simple template for a linktree page.
Just change the colors in the configuration part of the `index.php` file.

In this template are the following parts:
* Profile photo
* Title & Short description
* Links (Linktree)
* Social Media Icons (Icons without description)



## Table Of Contents

* [Demo](#demo)
* [Preview](#website-preview)
* [Configuration](#configuration)



## Demo
Try the demo [here](https://dxve.de/projects/cylancis/).



## Website Preview
![Preview](https://cdn.upload-host.de/1/419111-1fe0b6.png)



## Configuration

In the first lines of the `index.php` file you will see php variables.
These you can edit according to your wishes.

The default config is red-dark styled.

```php
// Set your time zone
// https://www.php.net/manual/en/timezones.php
date_default_timezone_set('Europe/Berlin');

// General configuration
$sitename = 'Cylancis Template';
$domain = 'https://dxve.de/projects/cylancis';
$logo = 'https://cdn.upload-host.de/1/9e1281-b783a9.png';

// Your links
// Get icons from https://fontawesome.com/v5/search?m=free
$linktree = array(
    array(
        'displayName' => 'Homepage',
        'icon' => '<i class="fas fa-globe"></i>',
        'url' => 'htttps://dxve.de'
    ),
    array(
        'displayName' => 'Discord Server',
        'icon' => '<i class="fab fa-discord"></i>',
        'url' => 'https://giybf.com'
    ),
    array(
        'displayName' => 'This template on GitHub',
        'icon' => '<i class="fab fa-github"></i>',
        'url' => 'https://github.com/DxveDE/Cylancis-Linktree-Template'
    )
);

// Social media links
$socialMedia = array(
    array(
        'icon' => '<i class="fab fa-discord"></i>',
        'url' => 'https://discord.com/users/681877886172659877'
    ),
    array(
        'icon' => '<i class="fab fa-instagram"></i>',
        'url' => 'https://www.instagram.com/dxve.b'
    ),
    array(
        'icon' => '<i class="fab fa-tiktok"></i>',
        'url' => 'https://www.tiktok.com/@dxve.tiktok'
    ),
    array(
        'icon' => '<i class="fab fa-youtube"></i>',
        'url' => 'https://www.youtube.com/c/DxveDE'
    ),
    array(
        'icon' => '<i class="fab fa-twitter"></i>',
        'url' => 'https://twitter.com/@dxve_b'
    ),
    array(
        'icon' => '<i class="fab fa-facebook"></i>',
        'url' => 'https://www.facebook.com/dxve.bomke/'
    ),
    array(
        'icon' => '<i class="fab fa-github"></i>',
        'url' => 'https://github.com/DxveDE'
    ),
    array(
        'icon' => '<i class="fab fa-whatsapp"></i>',
        'url' => 'https://wa.me/+4915251838855'
    ),
    array(
        'icon' => '<i class="fas fa-envelope"></i>',
        'url' => 'mailto:kontakt@dxve.de'
    )
);

// Color settings
$titleColor = '#FF7F7F'; // Color of the titles
$titleHoverColor = '#7F3F3F'; // Color of the title on hovering
$textColor = '#C0C0C0'; // Color of texts
$secondaryColor = '#FF0000'; // Secondary color for forwarding and other
$secondaryHoverColor = '#880000'; // Secondary color for forwarding and other on hovering

$backgroundColor = '#13161B'; // Page background color (background image overrides this, if it's set)
$buttonColor = '#242936'; // Button color
$buttonShadowColor = '#353535'; // Button-shadow color
$backgroundImage = 'https://cdn.upload-host.de/1/65ec57-4dc0e5.jpeg'; // Page background image (overrides background color); No image: "NONE"
```
