# Islamic Apps Documentation

This repository contains only Markdown files that discuss apps maintained as part of the <a href="https://github.com/islamic-apps">Islamic Apps</a> on GitHub.

Currently, this project includes all Open Sourced code related to the following projects:

## Projects and Repositories
* AlAdhan Prayer Times - https://aladhan.com
   * AlAdhan Web App - Code coming soon to GitHub.
   * <a href="https://github.com/islamic-apps/aladhan-api-client-php">AlAdhan PHP API Client</a>
   * <a href="https://github.com/islamic-apps/aladhan-api-jquery-plugin">AlAdhan JQuery Plugin</a>
   * <a href="https://github.com/islamic-apps/aladhan-wordpress-plugin">AlAdhan WordPress Plugin</a>
   * <a href="https://github.com/islamic-apps/aladhan-drupal-module">AlAdhan Drupal Module</a>
* AlQuran Cloud - https://alquran.Cloud
   * <a href="https://github.com/islamic-apps/alquran-web-app">AlQuran Cloud Web App</a>
   * <a href="https://github.com/islamic-apps/alquran-api-client-php">AlQuran Cloud PHP API Client</a>
   * <a href="https://github.com/islamic-apps/alquran-tools">AlQuran Cloud Tools</a>

## Coding Guidelines and Tools
Information on specific tools can be found within each repository. Some repositories use frameworks and others do not. As a rule, unless otherwise necessary, the attempt has been to use a micro framework - and I've mostly chosen to use <a href="https://github.com/slimphp/Slim">Slim</a>, because it felt slimmer then Silex and Lumen.


### Guidelines

#### PHP

* Always use <a href="https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md">PSR-2</a>.
* Where possible, use and contribute to existing composer packages.
* If writing code for PHP 7 only, please clearly define dependencies or make sure the code is backwards compatible
* Where reasonable, always write Unit Tests

#### JavaScript

Both AlAdhan and AlQuran use Bootstrap 3 and JQuery. Where possible, always create and use seprate JavaScript objects or JQuery plugins for any code you are writing.

#### Builds and CI
We're using CircleCI for some of the repositories (you'll see which ones, they have the build passing / failing URL on them). Time permitting, we should try and use it everywhere. It's fair to say the build scripts need some work!

## Contributing to the APIs
Both the AlAdhan API and AlQuran API are not *yet* open source. However, if you would like to contribute code to the APIs, please get in touch via <a href="https://aladhan.com/contact">https://aladhan.com/contact</a> or <a href="https://alquran.cloud/contact">https://alquran.cloud/contact</a>.

## Communication and Project Management Tools
This is not formalised or finalised yet. I've been using Asana and or Trello or Microsoft One Note so far, but with GitHub issues and projects and other add-ons for open source projects, we may not need to use separate tools.

There's also a Slack Team for those who want to discuss and / or help out actively.

## Licensing
Unless otherwise specified, all repositories are GPL 3 or LGPL 3. What this effectively means is that **All the code herein is made available in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.**

## Contacts

@meezaan and others who are willing.
