IoT Nexus 1.0.0
====================

This is the official reference wallet for IoTNexus digital currency and comprises the backbone of the IoTNexus peer-to-peer network. You can [download IoT Nexus](https://www.iotnexus.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run IoTNexus on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/bitcoin-qt` (GUI) or
- `bin/bitcoind` (headless)

### Windows

Unpack the files into a directory, and then run iotnexus-qt.exe.

### OS X

Drag IoTNexus to your applications folder, and then run IoTNexus.

### Need Help?

* See the [IoTNexus documentation](https://iotnexuscoin.atlassian.net/wiki/display/DOC)
for help and more information.
* Ask for help on [#iotnexuscoin](http://webchat.freenode.net?channels=iotnexuscoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=iotnexuscoin).
* Ask for help on the [IoTNexusTalk](https://iotnexustalk.org/) forums.

Building
---------------------
The following are developer notes on how to build IoT Nexus on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The IoT Nexus repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [IoTNexusTalk](https://iotnexustalk.org/) forums, in the Development & Technical Discussion board.
* Discuss on [#iotnexuscoin](http://webchat.freenode.net/?channels=iotnexuscoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=iotnexuscoin).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
