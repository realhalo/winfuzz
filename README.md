winFuzz is a security researching fuzzer for windows that behaves more as a precise debugger than a normal random fuzzer. This is done by isolating points (fuzzPoints) in arbitrary files to be tested against programs and/or remote services to attempt to cause memory corruption scenarios in the form of integer and/or buffer overflows.
(I made winFuzz essentially because I couldn't find a (arbitrary memory corruption) fuzzer that did the things I wanted(outside of 'taof', which I took some ideas from). So, I figured i'd make a fuzzer that did what I wanted and the way I wanted...and here we are)

Installer in: bin/
Video demonstration in: demo/
Source available in: src/ (currently private)
