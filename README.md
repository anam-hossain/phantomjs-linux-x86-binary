# phantomjs-linux-x86-binary
PhantomJS static linked binary for 64 bit linux systems. Most of Linux distributions are supported including Ubuntu, Debian, Fedora and CentOS.

## Installation

Add the following to your `composer.json` file:

```json
{
  "require" : {
    "anam/phantomjs-linux-x86-binary": "~2.1.1"
  }
}
```
## PhantomJS version
phantomjs-2.1.1

## Binary location

```php
use Anam\PhantomLinux\Path;

Path::binaryPath();

```
