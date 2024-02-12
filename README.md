# pith-pack-fixie
Pack Fixie-Reset for Pith

-------

# About

This project packs fixie-reset.css so that it can be used with the Pith Framewok.

For info on fixie, see repo at https://github.com/ian-maurmann/fixie-reset

For info on Pith, see the Pith website at https://pith-framework.org/

# Install

Install to an existing Pith Framework project

Use Composer to install the pack to the `vendor` folder.
```bash
php composer.phar require pith-front/pith-pack-fixie
```

Add new route to your Route List:

```php
public array $routes = [
    // Other routes....
    // ...
    
    // Add route to call aero-gel from
    ['route', 'GET', '/resources/vendor/library/fixie-reset/{filepath:.+}', '\\PithFront\\PithPackFixie\\FixieResourceRoute'],
];
```

-------------


# Licensing Info

### fixie-reset.css
- fixie-reset.css by Ian Maurmann
- Link: https://github.com/ian-maurmann/fixie-reset
- MIT license
- Copyright (c) Ian Maurmann

### pith-pack-fixie
- pith-pack-fixie
- MIT license
- Copyright (c) Ian Maurmann
- Link: https://github.com/pith-front/pith-pack-fixie

