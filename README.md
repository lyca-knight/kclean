![KCLEAN Logo](https://lycaknight.de/images/kclean/kclean_banner.png)

Easily remove old/unused kernels on your Debian system

[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)

### What is Kernel Cleaner?

Kernel Cleaner allows you to purge old/unused kernels filling the /boot directory. As new kernels are released the older ones have to be manually removed frequently to make room for newer ones. This can become quite tedious and require extensive time spent monitoring the system when new kernels are released and when older ones need to be cleared out to make room. With this issue existing, Kernel Cleaner was created to solve it.

## Example Usage

![KCLEAN Example](https://lycaknight.de/images/kclean/kclean_example.png)

## Features

* Removes old kernels from your system
* Ability to schedule kernels to automatically be removed on a daily/weekly/monthly basis
* Run a simple kclean command for ease of access
* Checks health of boot disk based on space available
* Support for the latest Debian versions and kernels

## Latest Version

* v1.0

## Prerequisites

Before using this program you will need to have the following packages installed.
* cron

To install all required packages enter the following command.

##### Debian:

```
sudo apt-get install cron
```

## Installing

To install Kernel Cleaner please enter the following commands

```
git clone https://github.com/Lyca-Knight/kclean
cd kclean
chmod +x kclean.sh
./kclean.sh
```

## Updating

To update Kernel Cleaner please run the same commands as described in the "Installing" section.


## Usage

Example of usage:
```
 pvekclean [OPTION]

-f		--force				Remove all old kernels without confirm prompts
-s		--scheduler			Have old kernels removed on a scheduled basis
-v		--version			Shows the current version of kclean
-r		--remove			Uninstalls kclean from the system
-h		--help				Show these options
```

## Developers

* **Lyca Knight**

Original by 
* **Jordan Hillis** - *Lead Developer*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* This program is original written by Jordan Hillis
