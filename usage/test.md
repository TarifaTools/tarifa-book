# test

`tarifa test` launches the project's [appium](http://appium.io/) tests on a choosen device and calls the `test()` function of the `project/bin/build.js` module (refer to [the front-end project](../project/index.md#the-www-project)). It supports only ios and android.

```
Usage: tarifa test <platform> [configuration]

Start current project's appium tests on the given platform, with no
configuration 'default' will be used.

Options:

    --help, -h            Show this message
    --verbose, -V         Be more verbose on everything
    --debug, -d           Print helpful stack trace on error
```
