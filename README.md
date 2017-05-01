# diclish - CLI bash script for posting/reading on [Diaspora*](http://diasporafoundation.org) pod

### Dependencies:

* [curl](https://curl.haxx.se/) (ubuntu updates/main, security/main, /main repos has this)
* [jq](https://stedolan.github.io/jq/) (ubuntu backports/universe, /universe repos has this)
* grep, sed, awk, tr, mkdir, mktemp, rm, wc (normally GNU/linux has this)

### Usage:

Run `diclish -h` for help.

Config folder: ~/.diclish

### Notice:

* You can use markdown syntax in post message;
* Words like `#tag1 #tag2 ... #tag3` (hash and text) will be parsed as hashtags (if they not starting the line);