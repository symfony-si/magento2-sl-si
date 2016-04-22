# Contribution Guidelines

You are most welcome to suggest improvements, report
[issues](https://github.com/symfony-si/magento2-sl_si/issues), or send pull
requests:

* Fork this repository over GitHub
* Set up your local repository

  ```bash
$ git clone git@github.com:your_username/magento2-sl_si
$ cd magento2-sl_si
$ git remote add upstream git://github.com/symfony-si/magento2-sl_si
$ git config branch.master.remote upstream
```
* Make changes and send pull request

  ```bash
$ git add .
$ git commit -m "Update files"
$ git push origin
```


## Translation Rules

Translations must follow Slovenian translation rules from
[Lugos](https://wiki.lugos.si/slovenjenje:pravila).


## Development Practices

Developing the language module and the main Magento store separately requires
a different workflow. After cloning the repository locally, you can just do the
following in package folder:

```bash
$ composer install
```


## Release Process

*(For repository maintainers)*

This repository follows [semantic versioning](http://semver.org). When source
code changes or new features are implemented, a new version (e.g. 1.x.y) is
released by the following release process:

* **1. Run the build**

    Run the build script to get HTML version of README and some other things that
    can be automated:

    ```bash
$ ./build
```

* **2. Update Changelog:**

    Create an entry in [CHANGELOG.md](CHANGELOG.md) describing all the changes
    from previous release.

* **3. Tag a new release:**

    Tag a new version on GitHub, and attach ZIP sl_si-1.x.y.zip as a binary file
    for manual installation.
