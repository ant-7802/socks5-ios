## SOCKS5 server for iOS

This app implements a *very* simple SOCKS5 server for iOS. You can use it to increase your tethering speeds when they are artificially limited; other uses are possible.

It is not distributed via the App Store because it'd probably get rejected.

Usage is simple: download this repo, `git submodule update`, and then build & deploy from XCode. Then set your system/browser SOCKS5 proxy to whatever it says on the screen (e.g. `172.20.10.1:4884`) and away you go.

UPDATE: Because sideloading apps is a pain, I recommend using [nneonneo/iOS-SOCKS-Server](https://github.com/nneonneo/ios-socks-server) instead; it's a Python script that can be easily loaded into Pythonista for iOS and used forever without sideloading restrictions.
