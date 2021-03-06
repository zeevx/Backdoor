# Backdoor (BKDR) | Browser Based Code Editor

Backdoor is a standalone browser based code editor that operates on a LASP (Linux, Apache, SQLite, PHP) server, providing all basic development tools with the ability of adding new features via extensions and services.

![Backdoor][screenshot]

----

### Development Setup

#### Folder Structure

| Folder          | Description  |
|:----------------|:-------------|
| **\_demo-root** | This is the directory where your local development copy of BKDR is pointed to for testing file creation and modification. |
| **\_development**     | All development will be done here. |
| **\_preview** | This is where your build gets compiled for localized testing. You would point your Wamp or Mamp to this folder. |
| **\_public-release** | Running _gulp release_ will put all the minified files here. This is a submodule of [https://github.com/RecaMedia/Backdoor-Release](https://github.com/RecaMedia/Backdoor-Release)|
| **docs** | The front-end for [https://recamedia.github.io/Backdoor/](https://recamedia.github.io/Backdoor/). |

#### Installation

* Make sure you have [Node](https://nodejs.org/en/), and [Gulp](https://www.npmjs.com/package/gulp) installed globally.
* Run `npm install` within the root directory.

### Extension Docs

You can read the basic [extension documentation](https://backdoor.gitbooks.io/extensions/content/) to develop your own extensions.

### License

GNU Affero General Public License v3.0

### Copyright

Copyright (C) 2017 Shannon Reca

[screenshot]: /screenshot_v2-2.png "Backdoor v2"
