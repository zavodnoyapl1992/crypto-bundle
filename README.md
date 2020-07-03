WARNING
=======

*Bundle is still in development.*
Fork  [https://github.com/agentsib/crypto-bundle](https://github.com/agentsib/crypto-bundle)

Installation
============

### Step 1: Download the Bundle

Open a command console, enter your project directory and execute the
following command to download the latest stable version of this bundle:

```console
$ composer require zavodnoyapl/crypto-bundle
```

This command requires you to have Composer installed globally, as explained
in the [installation chapter](https://getcomposer.org/doc/00-intro.md)
of the Composer documentation.

### Step 2: Enable the Bundle (Symfony 2/3)

Then, enable the bundle by adding it to the list of registered bundles
in the `app/AppKernel.php` file of your project:

```php
<?php
// app/AppKernel.php

// ...
class AppKernel extends Kernel
{
    public function registerBundles()
    {
        $bundles = array(
            // ...
            new AgentSIB\CryptoBundle\AgentSIBCryptoBundle(),
        );

        // ...
    }

    // ...
}
```