Slim Skeleton
=============

[![Join the chat at https://gitter.im/oanhnn/slim-skeleton](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/oanhnn/slim-skeleton?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

1) Creating project
----------------------------------

When it comes to creating project with Slim Framework, you have the
following options.

### Use Composer (*recommended*)

As project uses [Composer] to manage its dependencies, the recommended way
to create a new project is to use it.

If you don't have Composer yet, download it following the instructions on
http://getcomposer.org/ or just run the following command:

    curl -s http://getcomposer.org/installer | php

Then, use the `create-project` command to generate a new Symfony application:

    php composer.phar create-project oanhnn/slim-skeleton path/to/install

Composer will create Slim project and all its dependencies under the
`path/to/install` directory.
