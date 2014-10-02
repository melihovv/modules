Caffeinated Modules
===================
[![Build Status](https://travis-ci.org/caffeinated/modules.svg?branch=master)](https://travis-ci.org/caffeinated/modules)
[![Latest Stable Version](https://poser.pugx.org/caffeinated/modules/v/stable.svg)](https://packagist.org/packages/caffeinated/modules)
[![Total Downloads](https://poser.pugx.org/caffeinated/modules/downloads.svg)](https://packagist.org/packages/caffeinated/modules)
[![Latest Unstable Version](https://poser.pugx.org/caffeinated/modules/v/unstable.svg)](https://packagist.org/packages/caffeinated/modules)
[![License](https://poser.pugx.org/caffeinated/modules/license.svg)](https://packagist.org/packages/caffeinated/modules)

Before you delve into this, I want to start out by saying that this package is under **heavy development** and is not ready for production use.

---

To learn more about the usage of this package, please refer to the full set of [documentation](https://github.com/caffeinated/modules/wiki). You will find quick installation instructions below.

---

Installation
------------
Begin by installing the package through Composer. Edit your project's `composer.json` file to require `caffeinated/modules`:

```
"require": {
	"caffeinated/modules": "dev-master"
}
```

Next, update Composer from your Terminal:

```
composer update
```

Once this operation is complete, simply add both the service provider and facade classes to your project's `config/app.php` file:

#### Service Provider
```
'Caffeinated\Modules\ModulesServiceProvider'
```

#### Facade
```
'Module' => 'Caffeinated\Modules\Facades\Module'
```

And that's it! With your coffee in reach, start building out some awesome modules!