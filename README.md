# Pull to refresh
Simple phpBB extension to add a Pull To Refresh function for mobile devices.

![phpBB 3.3.x Compatible](https://img.shields.io/badge/phpBB-3.3.x%20Compatible%20-blue.svg)

## Minimum Requirements
* phpBB 3.3.0
* PHP 7.1.3

## Install
1. Download the [latest release](https://github.com/cabot/pulltorefresh/releases/latest).
2. Unzip the downloaded release, and change the name of the folder to `pulltorefresh`.
3. In the `ext` directory of your phpBB board, create a new directory named `cabot` (if it does not already exist).
4. Copy the `pulltorefresh` folder to `/ext/cabot/`.
5. Navigate in the ACP to `Customise -> Manage extensions`.
6. Look for `Pull to refresh` under the Disabled Extensions list, and click its `Enable` link.

## Uninstall
1. Navigate in the ACP to `Customise -> Extension Management -> Extensions`.
2. Look for `Pull to refresh` under the Enabled Extensions list, and click its `Disable` link.
3. To permanently uninstall, click `Delete Data` and then delete the `/ext/cabot/pulltorefresh` folder.

## Credits
* This extension uses Jordan Singer's [Hook](https://github.com/jordansinger/Hook) jQuery plugin.

## License
[GNU General Public License v2](http://opensource.org/licenses/GPL-2.0)

© 2023 - cabot
