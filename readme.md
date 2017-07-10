## Mobile HOSTS

HOSTS files converted from various mobile filter lists to prevent ads and tracking.

Currently includes:
- [Adguard Mobile Ads](https://raw.githubusercontent.com/r-a-y/mobile-hosts/master/AdguardMobileAds.txt) (from [Adguard](https://github.com/AdguardTeam/AdguardFilters/blob/master/MobileFilter/sections/adservers.txt))
- [Adguard Mobile Tracking and Spyware](https://raw.githubusercontent.com/r-a-y/mobile-hosts/master/AdguardMobileSpyware.txt) (from [Adguard](https://github.com/AdguardTeam/AdguardFilters/blob/master/MobileFilter/sections/spyware.txt))

These lists will be updated from time-to-time.  To update them yourself, the repo includes a PHP-CLI script (`converter.php`) that converts ad filter lists into HOSTS files.  View the source for more details.  Send a pull request if you want me to add a specific filter list.

#### How to use?

Copy one of the above URLs into any HOSTS app that allows adding URLs as a source.

Originally created for use with Android.  For unrooted devices, use DNS66.  For rooted devices, try AdAway.


#### License

GPLv3