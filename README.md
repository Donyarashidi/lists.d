# lists.d
##  listings for known devices, device identifiers, public servers and more.

These identifiers are device data are provided as-is with no guarantee of accuracy or reliability, and are meant for ITsec-related education & training purposes only!

Lists are provided as TSVs [Tab-Seperated Values] in order to make them easily searchable whilst retaining human readability and editability with text editors, scripts and spreadsheet programs.

### NOTE: All info has been taken from publicly available sources, not from private data or leaks.
####  We will reject all pull requests with data that have been obtained from non-public data and without proper source deeplinking to verify that these are not attempts at d0xxing or other actions that are not only violating GitHub's ToS but also might have serious legal remifications attached to them!

Knowledge is Free!


##  FAQ
### Why call it lists.d ?
-   Simple: Because these are lists intended to be kept in a directory for the user to use as needed.
-   In fact, you may even make your own based off the format ( I recommend to give them the extension .private.tsv to avoid confusion.)

### Why make this ?
-   For a lot of tutorials and tools it might be vital to supply some source of legitimate data ( like IMEI and MAC adresses ) yet endorsing dubiously sourced data is bad and I'd rather provide everyone with a clean set of already long-public data instead.
-   I then collected further ideas and datapoints one could want.

### What data is currently included?
As of now the following data is in seperate files:
-   [BitTorrent Trackers](https://github.com/greyhat-academy/lists.d/blob/main/bittorent-trackers.list.tsv)
-   [Blocklist (IPv4 & IPv6 - Ranges / ASNs / Domains)](https://github.com/greyhat-academy/lists.d/blob/main/blocklists.list.tsv)
-   [Default Logins](https://github.com/greyhat-academy/lists.d/blob/main/default-logins.tsv)
-   [DNS Servers](https://github.com/greyhat-academy/lists.d/blob/main/dns-servers.list.tsv)
-   ["Don't Report Security Issues To"  - List](https://github.com/greyhat-academy/lists.d/blob/main/dontreport.security.list.tsv)
-   [Homebrew (Software & Games for Consoles)](https://github.com/greyhat-academy/lists.d/blob/main/homebrew.list.tsv)
-   [IMEI Numbers](https://github.com/greyhat-academy/lists.d/blob/main/imei.list.tsv)
-   [IRC Networks](https://github.com/greyhat-academy/lists.d/blob/main/irc-networks.list.tsv)
-   [Logins (User/Password Combos)](https://github.com/greyhat-academy/lists.d/blob/main/logins.list.tsv)
-   [MAC Adresses (EUI-48 - only for 802/Ethernet and compatible networks)](https://github.com/greyhat-academy/lists.d/blob/main/mac-adresses.list.tsv)
-   [NTP Servers](https://github.com/greyhat-academy/lists.d/blob/main/ntp-servers.list.tsv)
-   [Onion Services (bona-fide only!)](https://github.com/greyhat-academy/lists.d/blob/main/onion.list.tsv)
-   [USB Devices](https://github.com/greyhat-academy/lists.d/blob/main/usb-devices.list.tsv)

### How can I contribute?
Just [open up an issue](https://github.com/greyhat-academy/lists.d/issues) or [make a pull request.](https://github.com/greyhat-academy/lists.d/pulls)

### What license do you use?
[CC BY-NC-SA 4.0. - See license.md](https://github.com/greyhat-academy/lists.d/blob/main/irc-networks.list.tsv)

### Why use TSVs instead of CSVs?
1.  [Because Tabs are superior to spaces](https://youtu.be/V7PLxL8jIl8?t=23)
2.  Because I need to use spaces inside fields
3.  Because I hate using seperators like " " or ' '
4.  Because I can and it's my project.

### What is it good for?
See the individual files. Their names should be self-explanatory.

### My Pull-Request got denied, why?
There can be one or multiple reasons:
-   You violated the formatting convention
-   You did not provide a source for the submitted entry or that source could not be verified
-   Your source was a non-'human readable' header or tag.
-   Your submission is not a bona-fide site.
-   Your submission is not available on the clear web.
-   Your submission discriminates based off the UserAgent of the browser or program used to access it.


