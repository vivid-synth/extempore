# Extempore

A programming environment for cyberphysical programming.

# Getting started

To get started, you can either download a binary release or build
Extempore from source yourself.

## Download a pre-built binary

Download a
[binary release](https://github.com/digego/extempore/releases), unzip
it and run `extempore.exe` from inside the `extempore` folder.

## Build from source

This will download and build all the dependencies you need (including
LLVM). So, if you've got a C++ compiler, git and CMake, here are some
one-liner build commands:

On **Linux/OSX**:

    git clone https://github.com/digego/extempore && mkdir extempore/cmake-build && cd extempore/cmake-build && cmake .. && make install

On **Windows**:

    git clone https://github.com/digego/extempore && mkdir extempore/cmake-build && cd extempore/cmake-build && cmake -G"Visual Studio 14 2015 Win64" .. && cmake --build . --target ALL_BUILD --config Release

# See Extempore in action

Check out these videos:

- Andrew Sorensen: [The Concert Programmer](https://www.youtube.com/watch?v=yY1FSsUV-8c)
- Supercomputing '15 tutorial:
  [interactive, distributed, physics simulation](https://vimeo.com/126577281)
- Andrew Sorensen: [Coding Music](https://www.youtube.com/watch?v=5DuVuoe-_UQ)
- Andrew Sorensen: [Live Coding the World](https://www.youtube.com/watch?v=eoLLF2pGY8k)
- Andrew Sorensen: [Programmer, Program, Machine and Environment](https://www.youtube.com/watch?v=A-eU_Nj2MVk)

# Docs & Community

Extempore documentation can be found at http://digego.github.io/extempore/index.html

You can also join the Extempore community:

- [Extempore google group](http://groups.google.com/group/extemporelang)
- [Extempore mailing list](mailto:extemporelang@googlegroups.com)

# Licence

Copyright (c) 2011-2015, Andrew Sorensen

All rights reserved.

Redistribution and use in source and binary forms, with or without 
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, 
   this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation 
   and/or other materials provided with the distribution.

Neither the name of the authors nor other contributors may be used to endorse
or promote products derived from this software without specific prior written 
permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" 
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE 
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE 
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE 
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR 
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF 
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS 
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN 
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE 
POSSIBILITY OF SUCH DAMAGE.
