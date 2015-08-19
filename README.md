omv-torrentcatcher
===========
###Requirements
* transmission-remote

Forked from "archangelic/torrentcatcher" to make some adjustments to work with OpenMediaVault

###Description
Takes torrent or magnet links from rss feeds you provide, parses them and sends them to transmission via the transmission-remote command line utility.
###Installation and Usage
To install this for your personal use run these commands:
```
$ git clone https://github.com/trancen/omv-torrentcatcher
$ cd omv-torrentcatcher/
$ ./setup.py install
$ omv-torrentcatcher --setup
```
Follow the setup instructions. Once completed, you will be able to just run `omv-torrentcatcher` to start downloading from the feed you added!

`omv-torrentcatcher.py -h` will reveal all available options and their descriptions.
