SLATE Core
=====================

Setup
---------------------
[SLATE Core](http://slate.io/wallet) is the original SLATE client and it builds the backbone of the network. However, it downloads and stores the entire history of SLATE transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run SLATE on your native platform.

### Unix

Unpack the files into a directory and run:

- bin/32/slate-qt (GUI, 32-bit) or bin/32/slated (headless, 32-bit)
- bin/64/slate-qt (GUI, 64-bit) or bin/64/slated (headless, 64-bit)

### Unix (Method2: Snapcraft)

[Install SLATE over snapcraft](https://build.snapcraft.io/user/slateapps/slate). Currently available builds:

- i386
- armhf
- amd64

More info about snapcraft: https://snapcraft.io/

#### Installation:

- Requirements: snapd ([Don't have snapd installed?](https://docs.snapcraft.io/core/install))
- Installation command: `sudo snap install --edge slate`

### Windows

Unpack the files into a directory, and then run slate-qt.exe.

### OSX

Drag SLATE-Qt to your applications folder, and then run SLATE-Qt.

### Need Help?

* See the documentation at the [SLATE Wiki](https://github.com/slatecurrency/slate/wiki/) ***TODO***
for help and more information.
* Ask for help on [BitcoinTalk](https://bitcointalk.org/index.php?topic=3399383) or on the [SLATE Forum](http://forum.slate.io/).
* Join our Discord server [Discord Server](https://discord.gg/ENuwHH5) - [alternative invitaiont link](https://discord.gg/ENuwHH5) 

Building
---------------------
The following are developer notes on how to build SLATE on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Slate repo's [root README](https://github.com/slatecurrency/slate/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://devwiki.slate.io/) ***TODO***
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources

* Discuss on the [BitcoinTalk](https://bitcointalk.org/index.php?topic=3399383) or the [SLATE](http://forum.slate.io/) forum.

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
