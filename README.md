# libavahi-core

A library containing a subset of features from the [Avahi Project](https://avahi.org) suitable for using on really small embedded platforms, where only a single daemon needs to publish/scan for services. It is built on avahi 0.6.31 sources, with a few extra #ifdefs and small changes to make it build and work on the target platforms.

The purpose of this repository is solely to make this subset of avahi plus build files available because it is needed to build the [plan44 vdcd digitalSTROM deamon](https://plan44.ch/opensource/vdcd/) on some of the supported platforms.

For any normal use of Avahi, please *don't* use this version, but see the official, full-featured, up-to-date version on [avahi.org](https://avahi.org) and in the corresponding [avahi github repository](https://github.com/lathiat/avahi)!
