Symfony Minimal Edition
========================

1) Installing
----------------------------------

Install composer:

    curl -s http://getcomposer.org/installer | php

Then, use the `create-project` command to generate a new Symfony application:

    php composer.phar create-project henningm/symfony-minimal path/to/install

Composer will install Symfony and all its dependencies under the
`path/to/install` directory.

2) Checking your System Configuration
-------------------------------------

Before starting coding, make sure that your local system is properly
configured for Symfony.

Execute the `check.php` script from the command line:

    php app/check.php

Access the `config.php` script from a browser:

    http://localhost/path/to/symfony/app/web/config.php

If you get any warnings or recommendations, fix them before moving on.

What's inside?
---------------

It comes pre-configured with the following bundles:

  * **FrameworkBundle** - The core Symfony framework bundle

  * [**SensioFrameworkExtraBundle**][6] - Adds several enhancements, including
    template and routing annotation capability

  * [**TwigBundle**] - Adds support for the Twig templating engine

  * [**AsseticBundle**] - Adds support for Assetic, an asset processing
    library

  * **WebProfilerBundle** (in dev/test env) - Adds profiling functionality and
    the web debug toolbar

  * **SensioDistributionBundle** (in dev/test env) - Adds functionality for
    configuring and working with Symfony distributions

  * [**SensioGeneratorBundle**] (in dev/test env) - Adds code generation
    capabilities
