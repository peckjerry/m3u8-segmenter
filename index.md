---
layout: default
title: Apple HTTP Live Streaming Segmenter
---


## About

M3U8 segmenter is an Apple HTTP Live Segmenter. It takes an MPEG-TS stream
from a tool like ffmpeg and breaks it up into multiple ts-segments suitable
for HTTP Live streaming from devices like iPhones. It also creates the M3U8
stream descriptor which is required for this type of stream.

## Install

On Ubuntu/Debian

    apt-get install m3u8-segmenter

**Note**: m3u8-segmenter hasn't quite made it's way into Debian/Ubuntu yet. Until
then you will need to add the PPA first. You can do this by doing the following
first.

    apt-add-repository ppa:johnf-inodes/m3u8-segmenter
    aptitude update

See the instructions in the
[README](https://github.com/johnf/m3u8-segmenter#readme) for details on how to
install from source.

m3u8-segmenter has only been tested on Linux distributions, however it should
work on any platform that is supported by
[libav](http://libav.org)/[ffmpeg](http://ffmpeg.org).

## Support

How does it work? [Check the README](https://github.com/johnf/m3u8-segmenter#readme).

Having problems? [Report a bug](http://github.com/johnf/m3u8-segmenter/issues).

Wanna help out? [Download the source](http://github.com/johnf/m3u8-segmenter).

M3U8 Sgmenter <a href="http://en.wikipedia.org/wiki/GPL_License">GPL Licensed</a>.

