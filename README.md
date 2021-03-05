# Phel - CLI

Getting started blank template for [Phel](https://phel-lang.org/) lang.

This template creates a namespace called `app` for storing your application logic in `src/` directory, and `app\tests` in `tests/` directory for storing your application tests.

**Requirement: PHP 7.4 or 8.0**

## Installation Via Composer

If your computer already has PHP and Composer installed, you may create a new Phel project by using Composer directly. After the application has been created, you may start the Phel application using the Phel CLI's `run` command:

```bash
composer create-project mabasic/phel-cli example-app dev-master

cd example-app

./vendor/bin/phel run src/boot.phel
# or
./vendor/bin/phel run app\\boot
# or
./vendor/bin/phel run "app\boot"
```

The output will be:

```
Hello, Phel!
```

## Next Steps

From here you can learn more about using Phel from the [official website](https://phel-lang.org/), or view the [source code repository](https://github.com/phel-lang/phel-lang) and contribute to the development of the language and its ecosystem.
