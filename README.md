[![Build Status](https://travis-ci.com/DiscipleTools/disciple-tools-dt-gapp.svg?branch=master)](https://travis-ci.com/DiscipleTools/disciple-tools-dt-gapp)

# Disciple Tools Gapp
The Disciple Tools Gapp is intended to accelerate integrations and extensions to the Disciple Tools system.
This basic plugin starter has some of the basic elements to quickly launch and extension project in the pattern of
the Disciple Tools system.


### The starter plugin is equipped with:
1. Wordpress style requirements
1. Travis Continueous Integration
1. Disciple Tools Theme presence check
1. Remote upgrade system for ongoing updates outside the Wordpress Directory
1. Multilingual ready
1. PHP Code Sniffer support (composer) @use /vendor/bin/phpcs and /vendor/bin/phpcbf
1. Gapp Admin menu and options page with tabs.

### Refactoring this plugin as your own:
1. Refactor all occurrences of the name `Gapp_Plugin`, `starter_plugin`, `dt-gapp`, and `Gapp` with you're own plugin
name for the `disciple-tools-dt-gapp.php and admin-menu-and-tabs.php files.
1. Update the README.md and LICENSE
1. Update the translation strings inside `default.pot` file with a multilingual software like POEdit, if you intend to make your plugin multilingual.

### Installing Code Quality
At your command line prompt, inside the plugin folder root:
Run composer install. You will need composer installed into your system. The command below will install
required composer elements that provide code quality tools (phpcs).
```
$ composer install
```

Once composer install has run, you can run the `phpcbf` function out of the new vendor folder.
```
$ vendor/bin/phpcbf
```
If the `phpcbf` utility cannot auto correct a style issue, then use `phpcs` to print the code style
issues that need corrected.
```
$ vendor/bin/phpcs
```

# Disciple Tools - Name

Description Description Description Description Description Description Description
Description Description Description Description Description Description Description

## Purpose

Purpose purpose purpose purpose purpose purpose purpose purpose purpose purpose purpose
Purpose purpose purpose purpose purpose purpose purpose purpose purpose purpose purpose

Purpose purpose purpose purpose purpose purpose purpose purpose purpose purpose purpose
Purpose purpose purpose purpose purpose purpose purpose purpose purpose purpose purpose

## Usage

#### Can Do

- Item
- Item
- Item

#### Can't Do

- Item
- Item

## Requirements

- Disciple Tools Theme installed on a Wordpress Server

## Installing

Install as a standard Disciple.Tools/Wordpress plugin in the system Admin/Plugins area. Requires the user role of Administrator.


## Contribution

Contributions welcome. You can report issues and bugs in the
[Issues](https://github.com/DiscipleTools/disciple-tools-list-exports/issues) section of the repo. You can present ideas
in the [Discussions](https://github.com/DiscipleTools/disciple-tools-list-exports/discussions) section of the repo. And
code contributions are welcome using the [Pull Request](https://github.com/DiscipleTools/disciple-tools-list-exports/pulls)
system for git. For a more details on contribution see the
[contribution guidelines](https://github.com/DiscipleTools/disciple-tools-list-exports/blob/master/CONTRIBUTING.md).


## Screenshots
