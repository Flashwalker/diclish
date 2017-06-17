# diclish - CLI bash script for posting/reading on [Diaspora*][diaspora] pod

### Dependencies:

See: [dependencies/INSTALL.md](dependencies/INSTALL.md)

* [curl](https://curl.haxx.se/)
* [jq](https://stedolan.github.io/jq/)
* grep, sed, awk, tr, mkdir, mktemp, rm, wc, which (normally GNU/linux has this)

### Usage:

See: [INSTALL.md](INSTALL.md)

Run `diclish -h` for help.

Config folder: ~/.diclish

### Notice:

* You can use [markdown][mdown] syntax in post message;
* Words like `#tag1 #tag2 ... #tag3` (*hash and text*) will be parsed as hashtags (*if they not starting the line*);

[diaspora]: http://diasporafoundation.org
[mdown]: http://daringfireball.net/projects/markdown/syntax