# µBlock for Chromium

See [Change log](https://github.com/gorhill/uBlock/wiki/Change-log) for latest changes. 
See [Wiki](https://github.com/gorhill/uBlock/wiki) for more information.

An efficient blocker for Chromium-based browsers. Fast and lean.

<p align="center">
    Chromium on Linux 64-bit<br>
    <img src="https://raw.githubusercontent.com/gorhill/uBlock/master/doc/img/ss-chromium-2.png" />
</p>

<p align="center">
    Opera 22 on Windows 7 32-bit<br>
    <img src="https://raw.githubusercontent.com/gorhill/uBlock/master/doc/img/ss-opera-1.png" />
</p>

<sup>The screenshots above were taken after visiting links in 
[reference benchmark](https://github.com/gorhill/uBlock/wiki/Reference-benchmark) 
plus a bit of random browsing. All blockers were active at the same time, 
thus they had to deal with exactly the same workload. Before the screenshots were 
taken, I left the browser idle for many minutes so as to let the browser's 
garbage collector kicks in. Also, after a while idling, it's good to open the dev
console for each extension and force a garbage collection cycle by clicking a couple of times 
the trashcan icon in the _Timeline_ tab (this caused a ~15MB drop for µBlock and Adguard in Opera) 
as garbage collectors sometimes work in a very lazy way, so I did this for each extension.</sup>

## Installation

From the [Chrome store](https://chrome.google.com/webstore/detail/µblock/cjpalhdlnbpafiamejdnhcphjbkeiagm), 
or [manually](https://github.com/gorhill/uBlock/tree/master/dist#install).

To benefit from the higher efficiency, it is of course not advised to use an 
inefficient blocker at the same time. µBlock will do as well or better than the 
popular blockers out there.

## Documentation

I think it is pretty obvious, except for this I suppose:

![Popup](https://raw.githubusercontent.com/gorhill/uBlock/master/doc/img/popup-1.png)

The big power button is to disable/enable µBlock **for the specific hostname
which can be extracted from the URL address of the current page**. (It applies to 
the current web site only, it is **not** a global power button.) The state of the power 
switch for a specific site will be remembered.

## About

µBlock is born out of [HTTP Switchboard](https://github.com/gorhill/httpswitchboard).
All the niceties of HTTPSB have been removed, and what is left is a straightforward
blocker which support EasyList and the likes, and also support host files. 
Cosmetic filters ("element hiding") are supported.

There is nothing more to it. But it does what popular blockers out there do, at a
fraction of CPU and memory usage for the same blocking power.

Free. Open source. No donations sought. For users by users.

Without the preset lists of filters, this extension is nothing. So if ever you 
really do want to contribute something, think about the people working hard 
to maintain the filter lists you are using, which were made available to use by 
all for free.

## License

[GPLv3](https://github.com/gorhill/uBlock/blob/master/LICENSE.txt).
