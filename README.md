# phplock
Php obfuscator plugin like PhpBolt for Raspberry Pi.

## Why Phplock?
There are php encoders available right now and they are expensive, later i found phpbolt and it suite my need from obfuscating php scripts to obfuscating laravel frameworks and works like a charm, now the problem is I couldn't make it run from raspberry pi board which has different cpu architecture and then I've decided to make my own php obfuscator.

## Whats Phplock?
Phplock is like phpbolt or other paid encoders which uses some php plugins compiled in .so for faster performance of executing your obfuscated codes.
It comes with Encoder and Decoder in different .so plugin.

## Features
* Free php encoder for Raspberry Pi
* Comes with .so Plugin for Encoding and Decoding for faster performance.
* Automatically Strips comments and whitespaces to reduce the encoded string.
* Pretty much like Phpbolt, in slightly different encoded output format.

## Todo
* Add some hardware lock upon encoding, this will trully lock the ebfuscated file to the machine.
* Make some improvements on obfuscation cryptography.
* Request me on the issues. 
* make .so version for x86 and x64, and different cpu architectures commonly used today.

## limitations
* only works in raspberry pi currently I just dont have resources yet on other cpu architectures other than raspberry pi and my computer and i havent have time yet to make the php plugin compiler work on my personal computer, as an alternative you can use Phpbolt instead.
 

