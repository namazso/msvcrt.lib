# msvcrt.lib

I assume you know [the pitfalls of linking against the NT CRT](https://devblogs.microsoft.com/oldnewthing/20140411-00/) already. These lib files let you exactly do this!

[Download builds](https://github.com/namazso/msvcrt.lib/releases)

## ARM64

Since the builds run on GitHub actions no real ARM64 binary is available, so the .def is hacked together from the x64 one with some ARM64 specific exports added. It might not be 100% correct.
